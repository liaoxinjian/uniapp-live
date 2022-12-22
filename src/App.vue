<script>
	export default {
		onLaunch: function() {
			console.log('App Launch', uni)
			// const domModule = uni.requireNativePlugin('dom');
			// domModule.addRule('fontFace', {
			// 	'fontFamily': 'iconfont',
			// 	'src': "url('https://at.alicdn.com/t/c/font_3836179_4fr6zttv627.ttf?t=1671695330737')"
			// })
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
	@import url("/common/css/common.css");
	/* #ifndef */
	@import url("/common/css/icon.css");
	/* #endif */
</style>
