<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			//检测更新
			//网络监听
			//初始化数据
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	/* css样式 */
	@import url("./common/uni.css");
	/* 图标库 */
	@import url("./common/icon.css");
	/* 动画库 */
	@import url("./common/animate.min.css");
</style>
