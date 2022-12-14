<template>
    <div class="latest-news__card">
        <ArticleItem />
    </div>
</template>
<script>
import ArticleItem from './articles/ArticleItem.vue';
export default {
    components: { ArticleItem}
}
</script>
<style>
    @import url('~/assets/css/article-item.css');
</style>