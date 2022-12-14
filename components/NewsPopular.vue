<template>
    <div class="popular-news section bg-white-blue">
        <div class="tcl-container">
            <MainTitle title="Popular Articles" v-bind:isViewMore="true" viewMoreText="View More" viewMoreLink="/"/>

            <div class="popular-news__list spacing">
                <div class="popular-news__list--left">
                    <div class="popular-news__list--row">
                        <NewsPopularCard/>
                    </div>
                    <div class="popular-news__list--row">
                        <NewsPopularCard/>
                    </div>
                </div>
                <div class="popular-news__list--right">
                    <div class="popular-news__list--row">
                        <NewsPopularCard/>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import NewsPopularCard from './NewsPopularCard.vue';

export default {
    components: { NewsPopularCard }
}
</script>
<style>
    @import url('~/assets/css/popular-news-list.css');
</style>