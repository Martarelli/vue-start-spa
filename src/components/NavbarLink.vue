<template>
    <li>
        <router-link 
           class="nav-link" 
           :to="`/${index}`"
           active-class="active"
           aria-current="page"
           :title="`This link goes to the ${page.link.text} Page`"
           >{{ page.link.text }}</router-link>
    </li>
</template>

<script>
export default {
    props: ['page', 'index']
}
</script>


