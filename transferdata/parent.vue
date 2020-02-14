<!-- 父组件 -->
<template>
    <div>
        <my-child :parentMessage="parentMessage"></my-child>
    </div>
</template>

<script>
    import MyChild from '@components/common/MyChild'

    export default {
        components: {
            MyChild
        },
        data() {
            return {
                parentMessage: "我是来自父组件的消息"
            }
        }
    }
</script>
