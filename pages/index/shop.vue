<template>
	<div class="item">
<!-- 		<van-card
		  :num="shop.nice"
		  :price="shop.price"
		  desc="描述信息"  
		  :title="shop.title"
		  :thumb="shop.img_list_url"
		/> -->
	</div>
</template>

<script>
	export default {
		name:'Shop',
		props: {
			shop: {
				type:Object,
				default(){
					return {
						img_list_url:'@/static/logo.png',
						id:123,
						title:'商品名称',
						price:'00'
					}
				}
			}
		}
	}
</script>

<style scoped>
	item{
		display: inline-block;
	}
</style>