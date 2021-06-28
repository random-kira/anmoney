<template>
    <div class="nav">
        <router-link to="/money">
            <Icon name="money"/>
            记账
        </router-link>
        |
        <router-link to="/labels">
            <Icon name="labels"/>
            记账
        </router-link>
        |
        <router-link to="/statistics">
            <Icon name="statistics"/>
            记账
        </router-link>
    </div>
</template>

<script lang="ts">
  export default {
    name: 'Nav'
  };
</script>

<style lang="scss" scoped>
    import x from '@/assets/icons/label.svg';

    .nav{

    }
</style>
