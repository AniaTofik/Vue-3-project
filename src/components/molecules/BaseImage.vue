<template>
    <figure>
        <img :src="require('@/assets/img/1.jpg')" alt="slide" class="image">
<BaseCaption></BaseCaption>
    </figure>
</template>

<script>

import BaseCaption from '../atoms/BaseCaption.vue';
export default({
name: 'BaseImage',
components: {BaseCaption}
});
</script>

<style lang="scss" scoped>
.image {
	height: auto;
	max-width: 100%;
}
</style>