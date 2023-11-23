<template>
  	<div>
    	<itemcontainer father-component="item">1111111111我00000们我们我们</itemcontainer>
  	</div>
</template>

<script>
import itemcontainer from '../../components/itemcontainer'

export default {
	name: 'item',
  	components: {
   		itemcontainer
  	},
  	created(){
      //进入题目页面，开始计时
  		this.$store.commit('REMBER_TIME');
  	}
}

</script>

<style lang="less">
    

</style>
