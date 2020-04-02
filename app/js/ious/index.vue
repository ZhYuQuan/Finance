<template lang="html">
    <div>
        <Heador/>
        <Ilider/>
        <Welfore/>
        <Service/>
        <Footer/>
        <Navbar/>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footer from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Ilider from "./islider.vue"
import Welfore from "./welfore.vue"
import Service from "./service.vue"
export default {
    components: {
        Heador,
        Ilider,
        Welfore,
        Service,
        Footer,
        Navbar,
    },
}
</script>


