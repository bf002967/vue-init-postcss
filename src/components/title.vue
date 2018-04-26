<template>
	<div class="title">
		<div class="title-main">
			<div class="title-contant">
				<i class="iconfont icon-logo"></i>
				<span>YUANCHAIN</span>
			</div>
			<ul class="title-ul">
				<li v-for="item in lillist">{{item}}</li>
			</ul>
		</div>
	</div>
</template>
<script>
	export default{
		data(){
			return{
				lillist:['首页','白皮书','技术特色','应用场景','顾问介绍','云矿机']
			}
		},
		mounted(){

		},
		methods:{

		}
	}
</script>
<style>
	.title{
		.title-main{
			float: left;
			overflow: hidden;
			height: 59px;
			width: 100%;
			.title-contant{
				margin-top: 13px ;
               width: 8.3%;
               height: 32px;
               line-height: 32px;
               color: #000;
               float: left;
               margin-left: 34px;
               font-weight: bold;
               .icon-logo{
                     border: 2px solid #000;
                     border-radius: 50%;
               }
			}
			.title-ul{
				float: left;
				width: 26.47%;
				line-height: 59px;
				font-size: 14px;
				margin-left: 141.75px;
				li{ 
					width: 20%;
					float: left;
				}
			}
			.title-ul:hover{
				li{

				}
			}
		}
	}
</style>