<template>
    <div>
			<div class="head">
				<div class="title">
					<span>123</span>
				</div>

				<div class="title2">
					<span>123</span>
				</div>
			</div>
		</div>
</template>

<script>
    export default {
        data() {
            return {}
        },
        mounted() {
				
        },
        components: {
        }
    }
</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
@import "~assets/stylus/variable"
.head
	.title 
		background $color-zw 
		margin 5px 
		span 
			display block
	.title2 
		background #333 
		margin 5px 
</style>