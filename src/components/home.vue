<template>

	<div class="mui-content">
		<ul class="mui-table-view">
			<li class="mui-table-view-cell">
				新春快乐！
				<div id="Gallery_Toggle" class="mui-switch">
					<div class="mui-switch-handle"></div>
				</div>
			</li>
		</ul>
		<div id="Gallery" class="mui-slider" style="margin-top:15px;">
			<div class="mui-slider-group">
				<div class="mui-slider-item">
					<ul class="mui-table-view mui-grid-view mui-grid-9">
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<router-link to='/card'>
								<span class="svg-container">
                                   <svg id="icon" aria-hidden="true">
                                     <use xlink:href="#icon-chunjie-yu"></use>
                                   </svg>
                               </span>
								<div class="mui-media-body">年年有鱼</div>
							</router-link>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<router-link to='/HelloWorld'>
								<span class="svg-container">
                                   <svg id="icon" aria-hidden="true">
                                     <use xlink:href="#icon-chunjie-yuanbao"></use>
                                   </svg>
                               </span>
								<div class="mui-media-body">财源广进</div>
							</router-link>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<router-link to='/index'>
								<span class="svg-container">
                                   <svg id="icon" aria-hidden="true">
                                     <use xlink:href="#icon-chunjie-bianpao"></use>
                                   </svg>
                               </span>
								<div class="mui-media-body">除旧迎新</div>
							</router-link>
						</li>
						
					</ul>
				</div>
				<div class="mui-slider-item">
					<ul class="mui-table-view mui-grid-view mui-grid-9">
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-home"></span>
								<div class="mui-media-body">Home</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-email"><span class="mui-badge">5</span></span>
								<div class="mui-media-body">Email</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-chatbubble"></span>
								<div class="mui-media-body">Chat</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-location"></span>
								<div class="mui-media-body">location</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-search"></span>
								<div class="mui-media-body">Search</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-phone"></span>
								<div class="mui-media-body">Phone</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-gear"></span>
								<div class="mui-media-body">Setting</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-info"></span>
								<div class="mui-media-body">about</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-more"></span>
								<div class="mui-media-body">more</div>
							</a>
						</li>
					</ul>
				</div>
				<div class="mui-slider-item">
					<ul class="mui-table-view mui-grid-view mui-grid-9">
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-home"></span>
								<div class="mui-media-body">Home</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-email"><span class="mui-badge">5</span></span>
								<div class="mui-media-body">Email</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-chatbubble"></span>
								<div class="mui-media-body">Chat</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-location"></span>
								<div class="mui-media-body">location</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-search"></span>
								<div class="mui-media-body">Search</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-phone"></span>
								<div class="mui-media-body">Phone</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-gear"></span>
								<div class="mui-media-body">Setting</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-info"></span>
								<div class="mui-media-body">about</div>
							</a>
						</li>
						<li class="mui-table-view-cell mui-media mui-col-xs-4 mui-col-sm-3">
							<a href="#">
								<span class="mui-icon mui-icon-more"></span>
								<div class="mui-media-body">more</div>
							</a>
						</li>
					</ul>
				</div>

			</div>
			<div class="mui-slider-indicator">
				<div class="mui-indicator mui-active"></div>
				<div class="mui-indicator"></div>
				<div class="mui-indicator"></div>
			</div>
		</div>
	</div>
</template>

<style>
	.icon {
		width: 1em;
		height: 1em;
		vertical-align: -0.15em;
		fill: currentColor;
		overflow: hidden;
	}
</style>
<link rel="stylesheet" href="./iconfont.css">