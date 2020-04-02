<template lang="html">
    <div>
        <Heador/>
        <Mlider/>
        <Adone/>
        <Money/>
        <Adtwo/>
        <Finance/>
        <Adthree/>
        <Footer cname="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Mlider from "./mslider.vue"
import Adone from "./adone.vue"
import Money from "./money.vue"
import Adtwo from "./adtwo.vue"
import Finance from "./finance.vue"
import Adthree from "./adthree.vue"
export default {
    components: {
        Heador,
        Mlider,
        Footer,
        Navbar,
        Adone,
        Money,
        Adtwo,
        Finance,
        Adthree,
    },
}
</script>

<style lang="scss">
.mfooter{
    margin-top: 0!important;
    ul{
        li:first-child{
            display: none;
        }
    }
}
</style>


