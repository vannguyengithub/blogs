<template>
    <div class="latest-news section">
        <div class="tcl-container">
            <MainTitle title="Latest Articles"/>
            <div class="latest-news__list spacing">
                <NewsLatestCard />
                <NewsLatestCard />
                <NewsLatestCard />
            </div>
        </div>
    </div>
</template>
<script>
import MainTitle from './MainTitle.vue';
import NewsLatestCard from './NewsLatestCard.vue';

export default {
    components: { MainTitle , NewsLatestCard}
}
</script>
<style>
    @import url('~/assets/css/latest-news-list.css');
</style>