=== YouTube metabox ===
Contributors: congbom
Donate link: 
Tags: youtube, metabox, video
Requires at least: 2.5
Tested up to: 3.8
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Create YouTube meta-box for post with live preview 

== Description ==

To get meta value in front-end, use `get_post_meta()` with meta key is `youtube_id`.

Example:

Print YouTube video ID: 
`<?php echo get_post_meta($post->ID, 'youtube_id', true);?>`

Thumbnails: 
`<img src="http://img.youtube.com/vi/<?php echo get_post_meta($post->ID, 'youtube_id', true);?>/mqdefault.jpg" alt="" />`

Video player: 
`<iframe src="http://www.youtube.com/embed/<?php echo get_post_meta($post->ID, 'youtube_id', true); ?>" width="588" height="331" frameborder="0" allowfullscreen></iframe>`

== Installation ==

1. Upload `youtube-metabox` to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. YouTube metabox in WP 3.7
2. YouTube metabox in WP 3.8