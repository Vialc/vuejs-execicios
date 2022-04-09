<template >
    <form action="">
        <div>
            <InputText />
        </div>
        <div>
            <InputText />
        </div>
        <div>
            <Submit />
        </div>
        
    </form>
</template>
<script>
import Submit from "./form/Submit.vue"
import InputText from "./form/InputText.vue"
import InputText1 from "./form/InputText.vue"
export default {
    name: 'Form',
    components: {
    InputText,
    Submit,
    InputText1
}
}
</script>
<style >
    
</style>