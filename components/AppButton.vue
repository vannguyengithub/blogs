<template>
    <button 
        v-if="!href" 
        v-bind:class="classNames">
        <slot />
    </button>
    <nuxt-link 
        v-else 
        v-bind:to="href" 
        v-bind:class="classNames">
        <slot />
    </nuxt-link>
</template>
<script>
export default {
    props: {
        href: {
            type: String,
            default: ''
        },
        type: {
            type: String,
            default: 'default'
        }
    },
    computed: {
        classNames() {
            return {
                'btn': true,
                'btn-default': this.type === 'default',

            }
        }
    }
}
</script>
<style>
@import url('~/assets/css/button.css');
</style>