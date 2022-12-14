<template>
    <div class="main-title spacing" v-bind:class="classNames">
        <h2>{{title}}</h2>
        <AppButton 
            v-if="isViewMore"
            v-bind:href="viewMoreLink"
            >{{ viewMoreText }}</AppButton>
    </div>
</template>
<script>
import AppButton from './AppButton.vue';

export default {
    props: {
        title: {
            type: String,
            default: ""
        },
        isViewMore: {
            type: Boolean,
            default: false
        },
        viewMoreText: {
            type: String,
            default: ''
        },
        viewMoreLink: {
            type: String,
            default: ''
        }
    },
    computed: {
        classNames() {
            return {
                'd-flex': this.isViewMore,
                'tcl-jc-between': this.isViewMore,   
                'tcl-ais-center': this.isViewMore,   
            }
        }
    },
    components: { AppButton }
}
</script>
<style>
    @import url('~/assets/css/main-title.css');
</style>