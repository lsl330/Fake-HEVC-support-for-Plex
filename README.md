# Fake-HEVC-support-for-Plex
<p>Plex direct play hevc video in windows

<p>https://greasyfork.org/zh-CN/scripts/439243-fake-hevc-support-for-plex

<p>中文简介</p>
<p>使plex网页端在windows上可以直接播放（不转码）hevc的视频（需浏览器支持hevc播放）</p>
<p>制作原因</p>
<p>plex网页端对hevc的限制太严重，edge for chromium安装hevc扩展后，在emby上可以直接播放hevc内容，但在plex上却依旧需要转码播放。</p>
因此制作此脚本</p>

<p>windows浏览器支持播放hevc视频的便捷方法（以edge for chromium为例，chrome需自行测试可行性）</p>
<p>1、在https://www.free-codecs.com/hevc_video_extension_download.html 下载31823版本的插件</p>
<p>2、在地址栏输入：edge://restart，重启edge使安装的插件生效</p>
<p>注意：必须安装31823版本的插件，后续版本的插件有bug，会导致播放时间出现抖动。安装后，建议关闭windows store的自动更新。</p>
<p>完成上述步骤后，你的浏览器即可支持hevc视频，但即使如此，你的plex播放hevc内容仍然会提示转码播放</p>
<p>要解决此问题，需要安装Fake-HEVC-support-for-Plex脚本，让plex知道你的浏览器支持hevc解码播放</p>
<p>（需先安装Tampermonkey类插件）</p>
<p>（若你的plex端口非32400，请自行更改将脚本中的32400更改为你的plex网页端口）</p>
<p>完成上述步骤，即可直接播放hevc内容。朋友们，进行享受支持播放的快乐吧</p>

<p>English Introduction</p>
<p>Make plex web on windows can directly play (not transcode) hevc video (need browser support hevc play)</p>
Reason</p>
<p>The hevc limitation on plex web is too serious, after installing the hevc extension on edge for chromium, the hevc content can be played directly on emby, but on plex it still needs to be transcoded.</p>
<p>So this script was created</p<p>>

<p>windows browser to support the convenient way to play hevc video (edge for chromium as an example, chrome need to test the feasibility of their own)</p>
<p>1、In https://www.free-codecs.com/hevc_video_extension_download.htm download 31823 video_extension</p>
<p>2, enter in the address bar: edge://restart, Restart edge to enable the installed plug-ins</p>
<p>Note: you must install the 31823 version of the video_extension, the subsequent version of the plug-in has bugs that can lead to jittering playback time. After installation, it is recommended to turn off the automatic update of windows store.</p>
<p>After completing the above steps, your browser can support hevc video, but even so, your plex will still prompt transcoded playback when playing hevc content</p>
<p>To solve this problem, you need to install Fake-HEVC-support-for-Plex script to let plex know that your browser supports hevc decoding</p>
<p>(you need to install Tampermonkey class plugin first)</p>
<p>(If your plex port is not 32400, please change the 32400 in the script to your plex web port)</p>
<p>After completing the above steps, you can play hevc content directly. Friends, enjoy the joy of supported playback!</p>

<p>Translated with www.DeepL.com/Translator (free version)</p>




