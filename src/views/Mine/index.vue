<template>
    <div id="main">
        <Header title="我的"></Header>
        <TabBar></TabBar>
    </div>
</template>

<script>
import Header from '@/components/Header'
import TabBar from '@/components/TabBar'
export default {
    name:'Movie',
    components:{
        Header,
        TabBar
    }
}
</script>