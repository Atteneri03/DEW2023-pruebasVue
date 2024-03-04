<template>
    <div>
        <ArticleContent />
        <MoreButton/>
    </div>
</template>

<script>
import ArticleContent from './ArticleContent.vue'
import MoreButton from './MoreButton.vue'


export default {
  components: {
    MoreButton,
    ArticleContent
  }
};

</script>