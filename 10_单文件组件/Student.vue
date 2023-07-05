<template>
    <div>
        <h2>学生姓名: {{ name }}</h2>
        <h2>年龄: {{ age }}</h2>
    </div>
</template>

<script>
export default {
    name:'Student',
    data() {
        return {
            name: '小明',
            add: '22'
        }
    }
}
</script>

<style></style>