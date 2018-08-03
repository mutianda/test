<template>
    <div class="header">
        <div class="header-left">
			<div class="iconfont back-icon">&#xe624;</div>
		</div>
        <div class="header-input">
			<div class="iconfont search-icon">&#xe632;</div>
			输入城市/景点/酒店</div>
        <div class="header-right">城市
			<div class="iconfont down-icon">&#xe697;</div>
			</div>
    </div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style  type="text/css"  >

    .header {
		display: flex;
		line-height: .86rem;
		background: darkcyan;
		color:#CACACA;
	}
    .header-left {
        width: .64rem;
        float: left;
    }
	.back-icon{
		text-align: center;
		margin-left: .1rem;
		font-size: .4rem;
     }
    .header-input{
        flex :1;
		height: .64rem;
		margin-top: .12rem;
		background: cornsilk;
		border-radius: .1rem;
		margin-left: .2rem;
		line-height: 0.62rem;
		color: darkgrey;
 }
	.search-icon{
		display: inline;
		margin-left: .3rem;
	}
	.header-right{
		width:1.24rem;
		text-align: center;
		float: right;
		padding-left: 0.1rem;
		letter-spacing:.04rem;
	}
	.down-icon{
		display: inline-block;
		font-size: .2rem;
	}
</style>
