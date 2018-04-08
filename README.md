# MarqueeView
垂直跑马灯效果。

# Screenshot
![](http://i.imgur.com/iXIFktz.gif)

# Usage
		
	//设置数据
	marqueeView.setMarqueeData(data);
	//切换暂停和滚动
	marqueeView.toggleMarquee();
	// 设置切换的时间间隔，默认是2000
	marqueeView.setInterval(3000);

# Depedency [![](https://jitpack.io/v/li-xiaojun/MarqueeView.svg)](https://jitpack.io/#li-xiaojun/MarqueeView)

- step1, Add it in your root build.gradle at the end of repositories:

			allprojects {
				repositories {
					...
					maven { url "https://jitpack.io" }
				}
			}

- step2, Add the dependency

			dependencies {
			        compile 'com.github.li-xiaojun:MarqueeView:latest'
			}


