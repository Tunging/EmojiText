# EmojiText
Based on UGUI to support emoji system on Text component.

Unity Version: 2017

	How to use?
	1)
		Put all emojies in Asset/Framework/Resource/Emoji/Input.
		Multi-frame emoji name format : Name_Index.png , Single frame emoji format: Name.png
	2)
		Excute EmojiText->Build Emoji from menu in Unity.
	3)
		It will outputs two textures and a txt in Emoji/Output.
		Drag emoji_tex to "Emoji Texture" and emoji_data to "Emoji Data" in UGUIEmoji material.
	4)
		Repair the value of "Emoji count of every line" base on emoji_tex.png.
	5)
		It will auto copys emoji.txt to Resources, and you can overwrite relevant functions base on your project.
	
	Author:zouchunyi
	E-mail:zouchunyi@kingsoft.com

zouchunyi大佬的原版  
lijia4423大佬添加了超链接的支持  
