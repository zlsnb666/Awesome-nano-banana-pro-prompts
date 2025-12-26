<img width="850" height="1268" alt="nano banana pro创意提示词大全封面" src="https://github.com/user-attachments/assets/9eacd1c0-c91a-4797-972e-764c3a71ea57" />

# Awesome-nano-banana-pro prompt
## Nano Banana Pro: A Premium AIGC Prompt Asset Library. Dedicated to the open-source spirit. Special thanks to all contributors for their creativity.（🚀 覆盖多场景的高质量 Prompt 合集，包含独家原创适配案例。❤️ 致敬社区：源于开源，回馈开源，感谢所有贡献创意的网友。）

使用Gemini提问，输出文本答案时，若出现出现幻觉（输出答案不正确、编造数据）/涉及最新资讯，可以加上避免幻觉的prompt
```
要求如下：1.如果涉及到具体事实或数据，请联网核实。2. 如果不确定，请直接说不知道，严禁编造。3. 遇到复杂逻辑，请一步步推理。4. 不要客套，直接给干货。
```
小Tips：对于一个图片效果，如果不知道提示词，可以先使用Gemini反推

通用版prompt
```
Analyze and reconstruct the visual style of the reference image in detail.

Recreate the same:
- subject composition and camera angle
- lighting setup and light direction
- color palette and overall tone
- texture, material, and surface quality
- depth of field and lens characteristics
- artistic style and level of realism

Visual details:
- camera perspective: medium shot, slightly low angle
- lens: 50mm equivalent, shallow depth of field
- lighting: soft key light from the left, subtle rim light, controlled shadows
- color grading: low saturation, cinematic contrast, warm highlights, cool shadows
- texture: high-detail skin texture, natural fabric folds, realistic reflections
- background: clean, softly blurred, consistent with the original environment

Style:
- high-end commercial photography
- modern, minimal, professional
- realistic but slightly stylized
- no exaggerated anime or cartoon features

Quality:
- ultra high resolution
- sharp focus on subject
- clean edges, no artifacts
- studio-level clarity

Do NOT change the background structure or main composition.
Maintain consistency with the original image.
```
反推的是人像 / 虚拟 IP / 模特图

prompt:
```
Carefully analyze the reference image and recreate the same visual identity.

Subject:
- same facial structure and proportions
- similar hairstyle and hair texture
- natural skin tone with realistic details
- consistent body proportions and posture

Photography:
- portrait photography style
- soft studio lighting with smooth shadow transitions
- key light slightly above eye level
- subtle highlight on hair and shoulders

Aesthetic:
- premium fashion editorial
- clean, modern, elegant
- realistic skin texture, no over-smoothing
- professional retouching, natural look

Environment:
- background remains unchanged in layout and atmosphere
- depth and lighting consistent with the original image

Avoid:
- cartoon, anime, illustration style
- exaggerated facial features
- plastic or artificial skin
```
# （1）目录（100+持续更新中）

- [1️⃣ 出圈/火的用法：图片变手办/手办视频](#1️⃣-出圈火的用法图片变手办手办视频)
- [2️⃣ 名人/指定人物（上传图片）超写实照片级生成](#2️⃣-名人指定人物上传图片超写实照片级生成)
- [3️⃣ 指定人物短视频：人像特征保持 + 切换视角 + veo3 首尾帧](#3️⃣-指定人物短视频人像特征保持--切换视角--veo3-首尾帧)
- [4️⃣ 建筑图转模型/建模](#4️⃣-建筑图转模型建模)
- [5️⃣ 连续编辑 + 物体组合 + 背景设计](#5️⃣-连续编辑--物体组合--背景设计)
- [6️⃣ 高清修复](#6️⃣-高清修复)
- [7️⃣ 物体组合/版本对比](#7️⃣-物体组合版本对比)
- [8️⃣ 商品广告短片：指定人物 + 商品](#8️⃣-商品广告短片指定人物--商品)
- [9️⃣ 人群中分离指定模糊人物 + 高清生成](#9️⃣-人群中分离指定模糊人物--高清生成)
- [1️⃣0️⃣ 图转线稿 + 色卡上色](#1️⃣0️⃣-图转线稿--色卡上色)
- [1️⃣1️⃣ 一句话生成一套角色设定/故事书](#1️⃣1️⃣-一句话生成一套角色设定故事书)
- [1️⃣2️⃣ 虚实结合/跨次元：插画人物探店](#1️⃣2️⃣-虚实结合跨次元插画人物探店)
- [1️⃣3️⃣ 指定人物 + 设计 实景体验/效果图](#1️⃣3️⃣-指定人物--设计-实景体验效果图)
- [1️⃣4️⃣ 精准替换视频人物](#1️⃣4️⃣-精准替换视频人物)
- [1️⃣5️⃣ 动漫转真人（接近 1:1 还原）](#1️⃣5️⃣-动漫转真人接近-11-还原)
- [1️⃣6️⃣ 高质量摄影：指定人物 + 高质量姿势参考](#1️⃣6️⃣-高质量摄影指定人物--高质量姿势参考)
- [1️⃣7️⃣ 图片转人偶玩具](#1️⃣7️⃣-图片转人偶玩具)
- [1️⃣8️⃣ 图片转-funko-pop-公仔](#1️⃣8️⃣-图片转-funko-pop-公仔)
- [1️⃣9️⃣ 图片转乐高](#1️⃣9️⃣-图片转乐高)
- [2️⃣0️⃣ 图片转针织玩偶](#2️⃣0️⃣-图片转针织玩偶)
- [2️⃣1️⃣ 图片转芭比娃娃](#2️⃣1️⃣-图片转芭比娃娃)
- [2️⃣2️⃣ 万物变高达](#2️⃣2️⃣-万物变高达)
- [2️⃣3️⃣ 赛博生娃？！两张人脸生成孩子脸](#2️⃣3️⃣-赛博生娃两张人脸生成孩子脸)
- [2️⃣4️⃣ 产品设计图转真实效果/渲染](#2️⃣4️⃣-产品设计图转真实效果渲染)
- [2️⃣5️⃣ 随手拍秒变专业摄影大片？！nano-banana-拯救你的废片](#2️⃣5️⃣-随手拍秒变专业摄影大片nano-banana-拯救你的废片)
- [2️⃣6️⃣ 光影参考](#2️⃣6️⃣-光影参考)
- [2️⃣7️⃣ 使用光影人偶做打光参考](#2️⃣7️⃣-使用光影人偶做打光参考)
- [2️⃣8️⃣ 生成绘画/渲染过程四宫格](#2️⃣8️⃣-生成绘画渲染过程四宫格)
- [2️⃣9️⃣ 一句话-照片变插画-还附带绘画过程](#2️⃣9️⃣-一句话-照片变插画-还附带绘画过程)
- [3️⃣0️⃣ 脸型参考/控制，秒变卡通形象](#3️⃣0️⃣-脸型参考控制秒变卡通形象)
- [3️⃣1️⃣ 一句咒语任何风格变写实](#3️⃣1️⃣-一句咒语任何风格变写实)
- [3️⃣2️⃣ 曲面屏贴图](#3️⃣2️⃣-曲面屏贴图)
- [3️⃣3️⃣ 直接为图片中的曲面大屏生成-指定的-裸眼-3d-内容](#3️⃣3️⃣-直接为图片中的曲面大屏生成-指定的-裸眼-3d-内容)
- [3️⃣4️⃣ 任意图片（明星/动漫）变挂件挂在自己/女朋友包包上](#3️⃣4️⃣-任意图片明星动漫变挂件挂在自己女朋友包包上)
- [3️⃣5️⃣ 叠加指定-材质质感/效果](#3️⃣5️⃣-叠加指定-材质质感效果)
- [3️⃣6️⃣ 照片变娃娃](#3️⃣6️⃣-照片变娃娃)
- [3️⃣7️⃣ 产品包装贴合](#3️⃣7️⃣-产品包装贴合)
- [3️⃣8️⃣ 把指定图片贴在大阶梯上](#3️⃣8️⃣-把指定图片贴在大阶梯上)
- [3️⃣9️⃣ 虚拟试妆化指定妆面](#3️⃣9️⃣-虚拟试妆化指定妆面)
- [4️⃣0️⃣ 妆面分析-+-优化建议](#4️⃣0️⃣-妆面分析--优化建议)
- [4️⃣1️⃣ 工业设计-手绘-秒变-实景效果](#4️⃣1️⃣-工业设计-手绘-秒变-实景效果)
- [4️⃣2️⃣ 工业设计套图马克笔、水彩、分析图、渲染图](#4️⃣2️⃣-工业设计套图马克笔水彩分析图渲染图)
- [4️⃣3️⃣ 表情准确参考动漫、真人都没问题](#4️⃣3️⃣-表情准确参考动漫真人都没问题)
- [4️⃣4️⃣ 动物拟人表情](#4️⃣4️⃣-动物拟人表情)
- [4️⃣5️⃣ 绝美卡片设计](#4️⃣5️⃣-绝美卡片设计)
- [4️⃣6️⃣ 多人物插画集](#4️⃣6️⃣-多人物插画集)
- [4️⃣7️⃣ 保持人物一致性多角度照片生成](#4️⃣7️⃣-保持人物一致性多角度照片生成)
- [4️⃣8️⃣ 一张图生成九宫格表情包](#4️⃣8️⃣-一张图生成九宫格表情包)
- [4️⃣9️⃣ 小红书超火Photowith风格](#4️⃣9️⃣-小红书超火photowith风格)
- [5️⃣0️⃣ 小红书手帐封面](#5️⃣0️⃣-小红书手帐封面)
- [5️⃣0️⃣ 超火的人物/角色说明](#5️⃣0️⃣-超火的人物角色说明)
- [5️⃣1️⃣ 角色一致性与口型准确性](#5️⃣1️⃣-角色一致性与口型准确性)
- [5️⃣2️⃣ 漫画上色与翻译](#5️⃣2️⃣-漫画上色与翻译)
- [5️⃣3️⃣ 国际化海报翻译与重排](#5️⃣3️⃣-国际化海报翻译与重排)
- [5️⃣4️⃣ 复杂UI界面复刻（聊天记录）](#5️⃣4️⃣-复杂ui界面复刻聊天记录)
- [5️⃣5️⃣ 长文本与古画风格结合](#5️⃣5️⃣-长文本与古画风格结合)
- [5️⃣6️⃣ IP角色融合创作](#5️⃣6️⃣-ip角色融合创作)
- [5️⃣7️⃣ 搜索增强：实时信息可视化（行程规划）](#5️⃣7️⃣-搜索增强实时信息可视化行程规划)
- [5️⃣8️⃣ 搜索增强：实时信息可视化（天气信息图）](#5️⃣8️⃣-搜索增强实时信息可视化天气信息图)
- [5️⃣9️⃣ 搜索增强：实时天气UI设计](#5️⃣9️⃣-搜索增强实时天气ui设计)
- [6️⃣0️⃣ 搜索增强与图像编辑结合](#6️⃣0️⃣-搜索增强与图像编辑结合)
- [6️⃣1️⃣ 多语言手账创作](#6️⃣1️⃣-多语言手账创作)
- [6️⃣2️⃣ 多图输入与手写日记风格](#6️⃣2️⃣-多图输入与手写日记风格)
- [6️⃣3️⃣ 中文字体设计](#6️⃣3️⃣-中文字体设计)
- [6️⃣4️⃣ 产品海报设计（单图）](#6️⃣4️⃣-产品海报设计单图)
- [6️⃣5️⃣ 产品海报设计（多图）](#6️⃣5️⃣-产品海报设计多图)
- [6️⃣6️⃣ 产品场景渲染](#6️⃣6️⃣-产品场景渲染)
- [6️⃣7️⃣ 多物品场景融合](#6️⃣7️⃣-多物品场景融合)
- [6️⃣8️⃣ 人像精细编辑与美颜](#6️⃣8️⃣-人像精细编辑与美颜)
- [6️⃣9️⃣ IP版权内容生成（跨文化融合）](#6️⃣9️⃣-ip版权内容生成跨文化融合)
- [7️⃣0️⃣ IP版权内容生成（关系图）](#7️⃣0️⃣-ip版权内容生成关系图)
- [7️⃣1️⃣ IP版权内容生成（游戏截图）](#7️⃣1️⃣-ip版权内容生成游戏截图)
- [7️⃣2️⃣ 白模上色与渲染](#7️⃣2️⃣-白模上色与渲染)
- [7️⃣3️⃣ 漫画翻译与上色（复杂场景）](#7️⃣3️⃣-漫画翻译与上色复杂场景)
- [7️⃣4️⃣ 酸性设计/Y2K风格海报转换](#7️⃣4️⃣-酸性设计y2k风格海报转换)
- [7️⃣5️⃣ UI设计风格迁移](#7️⃣5️⃣-ui设计风格迁移)
- [7️⃣6️⃣ 超长文本古风画卷](#7️⃣6️⃣-超长文本古风画卷)
- [7️⃣7️⃣ 视觉小说：现代言情](#7️⃣7️⃣-视觉小说现代言情)
- [7️⃣8️⃣ 视觉小说：古风武侠](#7️⃣8️⃣-视觉小说古风武侠)
- [7️⃣9️⃣ 视觉小说：奇幻冒险](#7️⃣9️⃣-视觉小说奇幻冒险)
- [8️⃣0️⃣ 电影海报《死亡诗社》](#8️⃣0️⃣-电影海报死亡诗社)
- [8️⃣1️⃣ 电影海报《天书奇谭》](#8️⃣1️⃣-电影海报天书奇谭)
- [8️⃣2️⃣ 活动海报设计](#8️⃣2️⃣-活动海报设计)
- [8️⃣3️⃣ 知识图谱：应县木塔结构图](#8️⃣3️⃣-知识图谱应县木塔结构图)
- [8️⃣4️⃣ 知识图谱：苏绣工艺图](#8️⃣4️⃣-知识图谱苏绣工艺图)
- [8️⃣5️⃣ 知识图谱：百年孤独人物关系图](#8️⃣5️⃣-知识图谱百年孤独人物关系图)
- [8️⃣6️⃣ 知识图谱：锂电池原理图](#8️⃣6️⃣-知识图谱锂电池原理图)
- [8️⃣7️⃣ 透视图解：金门大桥工程图](#8️⃣7️⃣-透视图解金门大桥工程图)
- [8️⃣8️⃣ 透视图解：宇航服技术图纸](#8️⃣8️⃣-透视图解宇航服技术图纸)
- [8️⃣9️⃣ 多图融合：硅谷AI圈大合照](#8️⃣9️⃣-多图融合硅谷ai圈大合照)
- [9️⃣0️⃣ 多角色融合](#9️⃣0️⃣-多角色融合)
- [9️⃣1️⃣ 组图生成：产品多角度渲染](#9️⃣1️⃣-组图生成产品多角度渲染)
- [9️⃣2️⃣ 产品拍摄](#9️⃣2️⃣-产品拍摄)
- [9️⃣3️⃣ 超现实主义风格艺术](#9️⃣3️⃣-超现实主义风格艺术)
- [9️⃣4️⃣ 宝丽来风格人像](#9️⃣4️⃣-宝丽来风格人像)
- [9️⃣5️⃣ 电影场景与氛围灯光](#9️⃣5️⃣-电影场景与氛围灯光)
- [9️⃣6️⃣ 战败CG](#9️⃣6️⃣-战败cg)
- [9️⃣7️⃣ 人物说明（真人版）](#9️⃣7️⃣-人物说明真人版)
- [9️⃣8️⃣ 真人galgame](#9️⃣8️⃣-真人galgame)
- [9️⃣9️⃣ 将真人包装成圣诞礼物](#9️⃣9️⃣-将真人包装成圣诞礼物)
- [1️⃣0️⃣0️⃣ 人物/产品背景替换](#1️⃣0️⃣0️⃣-人物产品背景替换)
- [1️⃣0️⃣1️⃣ 服装提取](#1️⃣0️⃣1️⃣-服装提取)


# （2）免费使用nano banana pro的方式汇总：
### 个人分享，没有为任何平台打广告

### 其中方式1-2需要挂vpn才能使用，方式3-7国内网络即可使用
1. Gemini官网（学生认证可以免费使用一年pro，可以自行去搜教程，或者去某小黄鱼）
2. Google AI studio：更适合开发者使用
3. runninghub：https://www.runninghub.cn/ai-detail/1991550248581603329
输入邀请码：pyv2q1zp。 可得500RH币
4. Lovart:https://www.lovart.ai/zh/home
每天有100积分的免费额度
5. LMarena:https://lmarena.ai/zh
权威的AI排名网站，里面可以免费使用市面上大部分ai模型，还有battle模式，在同一组提示词下比较两个模型，还有盲选模式，公平比较各种模型的效果。
6. Tapnow：集成了各类AI模型，包括生图的：nano banana pro，Midjourney，seedream4.5等，生视频的kling、Veo、Runway等，且从最新模型到旧版本的都可以使用
可以非常简单明了的搭建系统的视频生成工作流。缺点：免费额度少，费用贵
7. w8nring：http://www.w8nring.com






# （3）原创玩法 + 提示词

## 1️⃣ 出圈/火的用法：图片变手办/手办视频

https://github.com/user-attachments/assets/6440b1eb-4ecb-4d77-8dba-63c6d61c1ad3

1）变手办 Prompt：

```
turn this photo into a character figure. Behind it, place a box with the character’s image printed on it, and a computer showing the Blender modeling process on its screen. In front of the box, add a round plastic base with the character figure standing on it. set the scene indoors if possible
```

2）变视频 Prompt（Veo3）：

```
A pair of hands picks up the figurine and examines it closely
```






## 2️⃣ 名人/指定人物（上传图片）超写实照片级生成


<img width="894" height="900" alt="image" src="https://github.com/user-attachments/assets/0a0fd607-66c4-4993-bd10-fe3f1b734ef0" />


Prompt：

```
画面采用中景近乎半身的构图，镜头与人物几乎平视，但透视感强烈，但因为主体微微前倾，视觉上产生一种略带俯视感的压缩效果，让观者与模特之间的距离显得亲密而直接。人物微微抬头冲向镜头，有种拽姐的感觉。闪光灯从正面偏左上方打来，制造出硬朗的高光与深重阴影——墨镜镜片上有明显高光反射，人物后方墙面出现淡淡的投影，整体呈现典型的“直闪”质感：颗粒感轻微，可见胶片风格或高感光度数码拍摄的粗粝纹理。人物面部稍稍有点过度曝光

色彩基调以低饱和的中性色为主：黑色的宽肩丝绒西装外套占据画面最大面积，面料似乎是丝绒，带有细腻的绒面纹路；内搭的黑色丝绸吊带（搬运不标出处死妈）。模特下装是黑色超短裙和薄透质感的连裤袜。背景左侧堆放的墨绿色与咖色棒球帽、右侧叠放的亮蓝色夹克及黑色头盔等杂物，在柔和阴影中提供了点缀色，同时强调了拍摄的后台或休息室氛围。

人物【XXX】动作及神态具有强烈的街头时尚感：她双膝交叠坐在台面边缘，双手随意撑在身侧，身体前倾，给人一种随性却掌控全场的姿态。面部表情淡漠而自信——厚涂的裸色哑光唇膏、挺拔的鼻梁和高光额头在镜片下仍然清晰；宽大的方形黑色太阳镜遮住了双眼，却因为镜框外缘锋利的斜切角度，进一步强化了“冷面”气场。发型为高束的高马尾，碎发自然散落，在硬光照射下呈现金棕色高光，增加了几分随意的性感。

整体观感是一幅带有九十年代街拍影像感的时装速写：粗颗粒、直闪、低饱和配色与夸张的廓形外套共同营造出怀旧却前卫的潮流态度。右下角带有相机时间戳：2001 05 14
```





## 3️⃣ 指定人物短视频：人像特征保持 + 切换视角 + veo3 首尾帧


https://github.com/user-attachments/assets/271b390b-d9a9-4292-bb17-8602f73352f2


Prompt (from: @hellorob):

```
change the Camera anglo a high-angled selfie perspective looking down at the woman, while preserving her exact facial features, expression, and clothing, Maintain the same living room interior background with the sofa, natural lighting, and overall photographic composition and style.
```




## 4️⃣ 建筑图转模型/建模


<img width="1017" height="1340" alt="Group 184-2" src="https://github.com/user-attachments/assets/f78a58fe-87c3-4473-b929-9c1db31b205e" />


Prompt：

```
convert this photo into a architecture model. Behind the model, there should be a cardboard box with an image of the architecture from the photo on it. There should also be a computer, with the content on the computer screen showing the Blender modeling process of the figurine. In front of the cardboard box, place a cardstock and put the architecture model from the photo I provided on it. I hope the PVC material can be clearly presented. It would be even better if the background is indoors.
```





## 5️⃣ 连续编辑 + 物体组合 + 背景设计


<img width="1150" height="862" alt="未命名作品 31" src="https://github.com/user-attachments/assets/8ce14b2a-69eb-45e5-8a61-3a78ba42c840" />


Prompt：

第一步：
```
图一人物背上图二 logo 的斜挎包
```

第二步：
```
换上 Y2K 风格的背景
```

第三步（Veo3）：
```
女孩转过身来摆出一个可爱帅气的pose，背景音乐也是y2k风格
```





## 6️⃣ 高清修复


<img width="900" height="643" alt="image" src="https://github.com/user-attachments/assets/e05b8092-b2ce-4f20-b9d1-a40a28c1da6f" />


Prompt：

```
Enhance this image to high resolution
```






## 7️⃣ 物体组合/版本对比

<img width="900" height="738" alt="image" src="https://github.com/user-attachments/assets/746a09a7-fe29-40f9-8d02-815e6424f310" />


Prompt：

```
把它们组合起来
```






## 8️⃣ 商品广告短片：指定人物 + 商品



https://github.com/user-attachments/assets/0fe32335-ace1-4333-94e3-389c344daab4



Img Prompt：

```
模特拿着香水｜The model is holding a perfume
```

Video Prompt：
```
模特展示香水，配上优美的音乐｜The model is showcasing the perfume with beautiful music
```






## 9️⃣ 人群中分离指定模糊人物 + 高清生成：


<img width="900" height="729" alt="image" src="https://github.com/user-attachments/assets/5e9afd1c-82ca-4e70-a90d-23bed8794531" />


Prompt：

```
Separate the person inside the green box and turn it into a high-definition single-person photo
```






## 1️⃣0️⃣ 图转线稿 + 色卡上色


<img width="933" height="1200" alt="image" src="https://github.com/user-attachments/assets/6052b039-48cd-41e7-afa8-71a297a33b1f" />


Prompt：

第一步：

```
变成线稿手绘图
```

```
准确使用色卡为图二人物上色
```






## 1️⃣1️⃣ 一句话生成一套角色设定/故事书


<img width="900" height="771" alt="image" src="https://github.com/user-attachments/assets/0b1e156d-c461-42cd-9c11-a23643475993" />


Prompt：

```
为我生成人物的角色设定（Character Design）

比例设定（不同身高对比、头身比等）

三视图（正面、侧面、背面）

表情设定（Expression Sheet） 

动作设定（Pose Sheet） → 各种常见姿势

服装设定（Costume Design）
```






## 1️⃣2️⃣ 虚实结合/跨次元：插画人物探店


<img width="900" height="528" alt="image" src="https://github.com/user-attachments/assets/fa56c1ed-7b9c-4092-8c23-26ac18c65014" />


Prompt：

```
在图中加上一对情侣坐在座位上开心的喝咖啡和交谈，人物都是粗线稿可爱插画风格
```






## 1️⃣3️⃣ 指定人物 + 设计 实景体验/效果图


<img width="900" height="714" alt="image" src="https://github.com/user-attachments/assets/7450b369-c961-423e-9121-b6beb881b3c6" />


Prompt：

```
把人物换成图二人物，沙发换成图三沙发，配色换成橙色，文字换成“Z”
```






## 1️⃣4️⃣ 精准替换视频人物


https://github.com/user-attachments/assets/18299b01-efb6-43fb-8b44-a6c2be0464b4



Img Prompt：

```
把左边第二位人物换成希斯莱杰小丑/上传照片人物
```

Video Prompt：
```
小丑左右看了看，走向镜头前
```







## 1️⃣5️⃣ 动漫转真人（接近 1:1 还原）


<img width="900" height="618" alt="image" src="https://github.com/user-attachments/assets/6d6f82ff-f18f-40f8-b16d-b6d2c03bae8e" />


Prompt：

```
Generate a highly detailed photo of a girl cosplaying this illustration, at Comiket. Exactly replicate the same pose, body posture, hand gestures, facial expression, and camera framing as in the original illustration. Keep the same angle, perspective, and composition, without any deviation
```






## 1️⃣6️⃣ 高质量摄影：指定人物 + 高质量姿势参考


<img width="900" height="858" alt="image" src="https://github.com/user-attachments/assets/c1a845af-88d4-4510-80e8-6f19c6407718" />


Prompt：

```
图一人物换成图二姿势，专业摄影棚拍摄
```






## 1️⃣7️⃣ 图片转人偶玩具


<img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/15374566-a3b1-42ea-b5f5-54480cee523f" />


Prompt：

```
Transform the the person in the photo into an action figure, styled after [CHARACTER_NAME] from [SOURCE / CONTEXT]. 
Next to the figure, display the accessories including [ITEM_1], [ITEM_2], and [ITEM_3]. 
On the top of the toy box, write "[BOX_LABEL_TOP]", and underneath it, "[BOX_LABEL_BOTTOM]". 
Place the box in a [BACKGROUND_SETTING] environment. 
Visualize this in a highly realistic way with attention to fine details.
```






## 1️⃣8️⃣ 图片转 Funko Pop 公仔


<img width="900" height="776" alt="image" src="https://github.com/user-attachments/assets/0ffe62be-0e7a-46d2-9f75-b047cca5fd76" />


Prompt(from: https://x.com/dotey/status/1909047283485671924)：

```
Transform the person in the photo into the style of a Funko Pop figure packaging box, presented in an isometric perspective. Label the packaging with the title 'ZHOGUE'. Inside the box, showcase the figure based on the person in the photo, accompanied by their essential items (such as cosmetics, bags, or others). Next to the box, also display the actual figure itself outside of the packaging, rendered in a realistic and lifelike style.
```






## 1️⃣9️⃣ 图片转乐高


<img width="900" height="828" alt="image" src="https://github.com/user-attachments/assets/db4dce7e-f3df-4001-b792-909d3f862639" />


Prompt：

```
Transform the person in the photo into the style of a LEGO minifigure packaging box, presented in an isometric perspective. Label the packaging with the title 'ZHOGUE'. Inside the box, showcase the LEGO minifigure based on the person in the photo, accompanied by their essential items (such as cosmetics, bags, or others) as LEGO accessories. Next to the box, also display the actual LEGO minifigure itself outside of the packaging, rendered in a realistic and lifelike style.
```





## 2️⃣0️⃣ 图片转针织玩偶


<img width="794" height="900" alt="image" src="https://github.com/user-attachments/assets/55e1b0be-1edd-4f33-9867-cc6d20723059" />


Prompt：

```
A close-up, professionally composed photograph showing a handmade crocheted yarn doll being gently held in both hands. The doll has a rounded shape and an adorable chibi-style appearance, with vivid color contrasts and rich details. The hands holding the doll appear natural and tender, with clearly visible finger posture, and the skin texture and light-shadow transitions look soft and realistic, conveying a warm, tangible touch. The background is slightly blurred, depicting an indoor setting with a warm wooden tabletop and natural light streaming in through a window, creating a cozy and intimate atmosphere. The overall image conveys a sense of exquisite craftsmanship and a cherished, heartwarming emotion.
```






## 2️⃣1️⃣ 图片转芭比娃娃


<img width="680" height="510" alt="image" src="https://github.com/user-attachments/assets/b95825f7-e9a4-4406-9fb6-093d8da1c000" />


Prompt：

```
Transform the person in the photo into the style of a Barbie doll packaging box, presented in an isometric perspective. Label the packaging with the title 'ZHOGUE'. Inside the box, showcase the Barbie doll version of the person from the photo, accompanied by their essential items (such as cosmetics, bags, or others) designed as stylish Barbie accessories. Next to the box, also display the actual Barbie doll itself outside of the packaging, rendered in a realistic and lifelike style, resembling official Barbie promotional renders
```






## 2️⃣2️⃣ 万物变高达


<img width="612" height="680" alt="image" src="https://github.com/user-attachments/assets/a0a2f0af-26d0-445c-ba9d-f2481812e09d" />


Prompt：

```
Transform the person in the photo into the style of a Gundam model kit packaging box, presented in an isometric perspective. Label the packaging with the title 'ZHOGUE'. Inside the box, showcase a Gundam-style mecha version of the person from the photo, accompanied by their essential items (such as cosmetics, bags, or others) redesigned as futuristic mecha accessories. The packaging should resemble authentic Gunpla boxes, with technical illustrations, instruction-manual style details, and sci-fi typography. Next to the box, also display the actual Gundam-style mecha figure itself outside of the packaging, rendered in a realistic and lifelike style, similar to official Bandai promotional renders.
```





## 2️⃣3️⃣ 赛博生娃？！两张人脸生成孩子脸


<img width="902" height="1200" alt="image" src="https://github.com/user-attachments/assets/f4d68a17-9d54-4cbe-b8b0-d4917463a3fc" />


Prompt：

```
生成图中两人物所生孩子的样子，专业摄影
```





## 2️⃣4️⃣ 产品设计图转真实效果/渲染


<img width="900" height="664" alt="image" src="https://github.com/user-attachments/assets/783be09e-e3a5-4afb-874d-0216fb3709ac" />


Prompt：

```
turn this illustration of a perfume into a realistic version, Frosted glass bottle with a marble cap
```

[我的原帖](https://x.com/ZHO_ZHO_ZHO/status/1961461774693388346)




## 2️⃣5️⃣ 随手拍秒变专业摄影大片？！Nano-Banana 拯救你的废片！


<img width="900" height="644" alt="image" src="https://github.com/user-attachments/assets/620542d4-f645-4a70-af13-53557b77b806" />


Prompt：

```
Transform the person in the photo into highly stylized ultra-realistic portrait, with sharp facial features and flawless fair skin, standing confidently against a bold green gradient background. Dramatic, cinematic lighting highlights her facial structure, evoking the look of a luxury fashion magazine cover. Editorial photography style, high-detail, 4K resolution, symmetrical composition, minimalistic background
```





## 2️⃣6️⃣ 光影参考


<img width="900" height="788" alt="image" src="https://github.com/user-attachments/assets/e9536f56-1b62-4fc2-b375-9c97544b0171" />


Prompt：

```
图一换成图二打光，专业摄影
```





## 2️⃣7️⃣ 使用光影人偶做打光参考


<img width="900" height="808" alt="image" src="https://github.com/user-attachments/assets/4848153b-72b4-4011-93eb-0c539620639e" />


Prompt：

```
图一人物变成图二光影，深色为暗

```





## 2️⃣8️⃣ 生成绘画/渲染过程四宫格


<img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/9559b463-d192-4f6f-9b1d-889e8cbef73b" />


Prompt：

```
把图一变成图二那样的四宫格，从草图逐渐到上色渲染
```





## 2️⃣9️⃣ 一句话 照片变插画 还附带绘画过程


<img width="900" height="788" alt="image" src="https://github.com/user-attachments/assets/29ac3be3-dce9-45e2-b9d7-329d0f675064" />


Prompt：

```
为人物生成绘画过程四宫格，第一步：线稿，第二步平铺颜色，第三步：增加阴影，第四步：细化成型。不要文字
```





## 3️⃣0️⃣ 脸型参考/控制，秒变卡通形象


<img width="900" height="744" alt="image" src="https://github.com/user-attachments/assets/737bc511-d0d2-42bb-899c-c837b5219174" />


Prompt：

```
图一人物按照图二的脸型设计为q版形象
```






## 3️⃣1️⃣ 一句咒语任何风格变写实


<img width="900" height="897" alt="image" src="https://github.com/user-attachments/assets/c96bf7dd-ad3c-44a3-a399-9a6e496a053f" />

<img width="680" height="473" alt="image" src="https://github.com/user-attachments/assets/0b45145b-5768-4dc7-848c-d2ba12fdd5c8" />

<img width="680" height="340" alt="image" src="https://github.com/user-attachments/assets/533dc40e-c88a-4a35-8962-32f3e96a6e0d" />

<img width="680" height="340" alt="image" src="https://github.com/user-attachments/assets/d3b983af-a1ff-4e9f-847c-71cf07d62e76" />

<img width="680" height="390" alt="image" src="https://github.com/user-attachments/assets/d0f0bed9-b29a-439e-987b-c33754d87d3b" />

<img width="680" height="440" alt="image" src="https://github.com/user-attachments/assets/069319b3-b1a1-403a-ab42-cdc250b84db4" />


Prompt：

```
turn this illustration into realistic version
```






## 3️⃣2️⃣ 曲面屏贴图


<img width="898" height="1200" alt="image" src="https://github.com/user-attachments/assets/1d3f44a8-6a39-46fa-a700-f4ec73fc67aa" />


Prompt：

```
把图一放在图二大屏幕上，撑满整个屏幕
```





## 3️⃣3️⃣ 直接为图片中的曲面大屏生成 指定的 “裸眼 3D” 内容


<img width="899" height="1200" alt="image" src="https://github.com/user-attachments/assets/7f244b25-02e5-479e-9f5f-2f86a449e3de" />


Prompt：

```
为大屏幕上换上裸眼 3D 猫猫
```





## 3️⃣4️⃣ 任意图片（明星/动漫）变挂件挂在自己/女朋友包包上！


<img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/ad6ff7e4-6e44-4a8c-9840-6661575ef740" />

<img width="680" height="680" alt="image" src="https://github.com/user-attachments/assets/41f92bb6-9cec-4c6a-8c3f-7b815916b86a" />

<img width="680" height="680" alt="image" src="https://github.com/user-attachments/assets/61c4270b-edf7-4571-b37d-6e3e07b9d2e3" />

<img width="496" height="680" alt="image" src="https://github.com/user-attachments/assets/53ace176-9952-4d6d-9fb8-c3bc2e426c72" />


Prompt：

```
把这张照片变成一个可爱挂件/亚克力材质的扁平钥匙扣/橡胶材质的扁平钥匙扣 挂在 lv 包包/图二照片的包包上
```





## 3️⃣5️⃣ 叠加指定 材质质感/效果

<img width="900" height="788" alt="image" src="https://github.com/user-attachments/assets/c844cba2-8b34-4c4f-9aff-22c43910cc2b" />

<img width="680" height="460" alt="image" src="https://github.com/user-attachments/assets/1cd4f2a9-0cde-417d-b4ee-280438a6a8a0" />

<img width="680" height="593" alt="image" src="https://github.com/user-attachments/assets/75ae518d-5316-48f8-a856-4a83c272d7aa" />


Prompt：

```
为图一照片叠加上图二玻璃的效果
```





## 3️⃣6️⃣ 照片变娃娃


<img width="900" height="788" alt="image" src="https://github.com/user-attachments/assets/c30321fd-5610-474c-a0eb-e2ca55a9fb79" />


Prompt：

```
把这张照片变成一个可爱玩偶
```





## 3️⃣7️⃣ 产品包装贴合


<img width="900" height="645" alt="image" src="https://github.com/user-attachments/assets/6022f5aa-6ec0-4380-91c7-aa2412dfd70f" />


Prompt：

```
把图一贴在图二易拉罐上，并放在极简设计的布景中，专业摄影
```





## 3️⃣8️⃣ 把指定图片贴在大阶梯上


<img width="798" height="900" alt="image" src="https://github.com/user-attachments/assets/e56fb2dd-6327-42f6-a810-71f506acae26" />


Prompt：

```
把图一海报贴在图二的大阶梯上
```





## 3️⃣9️⃣ 虚拟试妆？！化指定妆面


<img width="900" height="724" alt="image" src="https://github.com/user-attachments/assets/84734fcb-7bf8-4447-81d9-996e99c662db" />


Prompt：

```
为图一人物化上图二的妆，还保持图一的姿势
```





## 4️⃣0️⃣ 妆面分析 + 优化建议！


<img width="900" height="788" alt="image" src="https://github.com/user-attachments/assets/8194cd70-2f4a-4825-a662-a74d886cb5bd" />


Prompt(from: https://x.com/AiMachete/status/1962356993550643355)：

```
Analyze this image. Use red pen to denote where you can improve
```





## 4️⃣1️⃣ 工业设计 手绘 秒变 实景效果



https://github.com/user-attachments/assets/6ef7c630-2dc1-4c17-bfce-673afa4eb6be



Prompt：

```
turn this photo into realistic version, with light brown leather, put into a Minimalism museum
```





## 4️⃣2️⃣ 工业设计套图：马克笔、水彩、分析图、渲染图


<img width="900" height="900" alt="image" src="https://github.com/user-attachments/assets/bdb4ef91-225f-474b-a924-4754153df404" />


Prompt：

```
turn this photo into 马克笔画/水彩画/diagram
```





## 4️⃣3️⃣ 表情准确参考！动漫、真人都没问题！


<img width="679" height="523" alt="image" src="https://github.com/user-attachments/assets/3710652d-6adc-4837-bb4b-02ae3d360a8e" />

<img width="680" height="487" alt="image" src="https://github.com/user-attachments/assets/59d8298b-a38d-4f8f-a008-e653086354fa" />



Prompt：

```
图一人物参考/换成图二人物的表情
```





## 4️⃣4️⃣ 动物拟人表情


<img width="639" height="680" alt="image" src="https://github.com/user-attachments/assets/9981b0d9-abe9-4ad3-9ba6-114756bd65bf" />


Prompt：

```
把图二猫咪变成图一人物那样的表情
```





## 4️⃣5️⃣ 绝美卡片设计


<img width="659" height="680" alt="image" src="https://github.com/user-attachments/assets/fbd5739f-0082-4af0-acfd-0811d16be22e" />


Prompt：

```
按照我的图一名片设计稿的构图和质感，为我的图二人物生成卡片

卡片右上角为可爱卡通形象，突出于卡片

name: Nani
Occupation：artist
Company：zano-banana
Telephone：82732691
```





## 4️⃣6️⃣ 多人物插画集


<img width="680" height="575" alt="image" src="https://github.com/user-attachments/assets/176078dd-04f6-421b-b7f9-4507fb44b2c2" />


Prompt：

```
把前四个人物都变成图五那样的 黑白 极简风插画，人物要可爱并保持各自特点，并为每个人物配上合适的小道具，线条要优美，头发部分像图五那样为黑色块，并在一张图里
```

## 4️⃣7️⃣ 保持人物一致性多角度照片生成

![IMG_1520](https://github.com/user-attachments/assets/8fd0fe59-68af-4263-97cd-1caa6e532a37)


若要保证高质量请分多次生成

Prompt：
```
( 正面 )
front view, looking at viewer, symmetric composition
( 侧面/侧颜 )
side view, profile, looking ahead
( 背面 )
back view, from behind
（四分之三侧面） 3/4 View - 最常用的美感角度
脸微微转过去一点，立体感最好。
3/4 view, slightly turned face, looking at viewer
（左侧面45度）
facing left, 45 degree angle, side view
（右侧面45度）
facing right, 45 degree angle, side view
（完全侧颜 (Side Profile - 90度)
profile view, side profile, looking away, 90 degree side view
（背面/回眸 (Back View / Looking Back)
view from behind, back view, looking back over shoulder, turning head

【镜头距离】
( 大头照/脸部特写 )
extreme close-up, face focus, macro shot
( 半身像 )
upper body, cowboy shot
( 全身照 )
full body, wide shot, standing, head to toe
【特殊机位】
( 上帝视角/俯视 )
high angle, from above, bird's eye view, depth of field
( 仰视/显得高大 )
low angle, from below, worm's eye view
( 动态/鱼眼/透视大 )
fisheye lens, dynamic angle, foreshortening, action shot
```

## 4️⃣8️⃣ 一张图生成九宫格表情包
![IMG_1521](https://github.com/user-attachments/assets/5d4d442b-64f2-4dc9-a8c8-9eccbea01379)



Prompt：

```
【九宫格·表情包/头像风格】
9 panels layout, grid of 9 images, photobooth style, same character, different expressions, happy, sad, angry, surprised, shy, neutral, excited, closed eyes, winking, close up face, anime style, flat color
```

## 4️⃣9️⃣ 小红书超火Photowith风格


![IMG_1970](https://github.com/user-attachments/assets/87b8ee8d-2d71-4cb2-a75d-5b0d3df523fc)

把自己的照片上传为图一，博主的照片上传作为图二
Prompt：

```
依据参考图一，帮我生成一张真人写真，保持人物五官脸型不变，去除所有原背景。
人物：参考图一
背景：统一低饱和暗绿色细小磨砂质感墙面
色调：复古胶片风，暖调柔和，轻微颗粒感
妆容：伪素颜妆
半身照片，人物在照片的中间部分，具体可参考：图二
服装：xxx（自行描述）如白色一字肩毛衣
动作：直视镜头。比例 3:2
图片的背景，光线，风格可以参考图二，不要参考图二的人脸，人脸只参考图一。

```
## 5️⃣0️⃣ 小红书手帐封面
![IMG_1820](https://github.com/user-attachments/assets/eb3e7407-420e-4305-b971-c7dfdad43259)


Prompt：

```
**角色定义**：你是一位审美顶级的时尚杂志编辑和手账排版设计师。

**任务指令**：请详细分析我**上传的参考图片**，并根据分析结果生成一张垂直3:4构图的“OOTD时尚手账”拼贴画。

**执行步骤（自动化生成逻辑）：**

1.  **视觉分析（关键步骤）**：
    * 识别参考图中人物的**具体穿搭**（上装、下装、鞋子、包包、配饰）。
    * 识别整体**风格**（如：复古、运动、商务、街头、甜美、哥特等）。
    * 提取画面的**主色调**。

2.  **画面布局与生成**：
    **【 人物展示】**：保留参考图中人物的全身或半身抠图形象，加上白线描边。如果参考图没有鞋子，就按照你的审美补全一双合适的鞋子。**务必保持**人物原本的面部特征、发型和衣着细节，保持角色一致性。不要携带背景，如果人物坐着可以把凳子一起扣出来。
    **【 穿搭拆解 (Knolling)】**：基于你刚才“视觉分析”识别到的单品，将这些物品在左侧进行整齐的**平铺摆放**（Flat lay）。包括衣服主体、裤子/裙子、鞋子、丝袜、帽子、配饰、包包以及小配饰（如耳环、项链、墨镜、化妆品）。
    **【背景与装饰】**：使用“手账拼贴”风格。材质包括：白色网格纸、撕裂的牛皮纸纹理、和纸胶带等等，你可以分析出画面风格取用对应材质。**背景风格**要和参考图相匹配，比如参考图是圣诞穿搭，背景就是要是圣诞风格，并自动在手帐背景补充圣诞元素，如圣诞树，圣诞老人。**背景颜色**要根据你提取的“主色调”进行自动协调（例如：原图是粉色系，背景装饰就用粉色）。添加手绘风格的箭头、星星、闪光涂鸦等等。
**根据布局智能排版**
3.  **智能文字标注**：
    * 顶部标题：手写艺术字 照片风格+OOTD，比如“圣诞甜美风OOTD”。
    * **物品标签（自动反推）**：请根据你**实际识别出**的物品，自动生成对应的**中文手写标签**并用箭头指向物品（例如：如果你识别出是卫衣，就标注“宽松卫衣”；识别出是高跟鞋，就标注“尖头高跟鞋”）。
    * 底部：生成一个复古日期的印章。要和生成图片的日期匹配。

**画面质感**：
8k超高清，真实摄影质感，杂志级排版，光影自然，细节丰富。

所有文字，使用高清中文

```

## 5️⃣0️⃣ 超火的人物/角色说明

![角色设定](https://github.com/user-attachments/assets/b7abf73f-6d63-4fac-a858-8a72efd3e1a7)


Prompt：

```
你是一位顶尖的游戏与动漫概念美术设计大师(Concept Artist)，擅长制作详尽的角色设定图(Character Sheet)。你具备“像素级拆解”的能力，能够透视角色的穿着层级、捕捉微表情变化，并将与其相关的物品进行具象化还原。你特别擅长通过女性角色的私密物品、随身物件和生活细节来侧面丰满人物性格与背景故事。
Task(任务目标)
根据用户上传或描述的主体形象，生成一张**“全景式角色深度概念分解图”**。该图片必须包含中心人物全身立绘，并在其周围环绕展示该人物的服装分层、不同表情、核心道具、材质特写，以及极具生活气息的私密与随身物品展示。
Visual Guidelines(视觉规范)
1.构图布局(Layout):
·中心位(Center):放置角色的全身立绘或主要动态姿势，作为视觉锚点。
·环绕位(Surroundings):在中心人物四周空白处，有序排列拆解后的元素。
·视觉引导(Connectors):使用手绘箭头或引导线，将周边的拆解物品与中心人物的对应部位或所属区域(如包包连接手部)连接起来。
2.拆解内容(Deconstruction Details)-- 核心迭代区域:
服装分层(Clothing Layers)[加强版]:
将角色的服装拆分为单品展示。如果是多层穿搭，需展示脱下外套后的内层状态。
·新增:私密内着拆解(Intimate Apparel):独立展示角色的内层衣物，重点突出设计感与材质。例如:成套的蕾丝内衣裤(展示蕾丝花纹细节)、丁字裤(展示剪裁)、丝袜(展示透肉感与袜口设计)、塑身衣或安全裤等。
·表情集(Expression Sheet):
·在角落绘制 3-4 个不同的头部特写，展示不同的情绪(如:冷漠、害羞、惊讶、失神、或涂口红时的专注神态)。
·材质特写(Texture &Zoom)[加强版]:
·选取 1-2 个关键部位进行放大特写。例如:布料的褶皱、皮肤的纹理、手部细节。
新增:物品质感特写:增加对小物件材质的描绘，例如:口红膏体的润泽感、皮革包包的颗粒纹理、化妆品粉质的细腻感。
关联物品(Relatedltems)深度迭代版]·此处不再局限于大型道具，需增加展示角色的“生活切片”
·随身包袋与内容物(Bag & Contents):绘制角色的日常通勤包或手拿包，并将其“打开”展示散落在旁的物品。
·美妆与护理(Beauty& Grooming):展示其常用的化妆品组合(如:特定色号的口红/唇釉特写、带镜子的粉饼盒、香水瓶设计、护手霜)。
私密生活物件(Lifestyle &Intimate ltems):具象化角色隐藏面的物品。根据角色性格可能包括:私密日记本、常用药物/补剂盒、电子烟、或者更私人的物件(如用户提到的飞机杯/情趣用品，需以一种设计图的客观视角呈现，注匍在明型号或设计特点)。
咱有.风格与注释(Style&Annotations):
·画风:保持高质量的 2D 插画风格或概念设计草图风格，线条干净利落，
·背景:使用米黄色、羊皮纸或浅灰色纹理背景，营造设计手稿的氛围。
·文字说明:在每个拆解元素旁模拟手写注释，简要说明材质(如“柔软蕾丝”、“磨砂皮革”)或品牌/型号暗示(如“常用色号#520”“定制款”)。
Workflow(执行逻辑)
当用户提供一张图片或描述时:
分析主体的核心特征、穿着风格及潜在性格。
提取可拆解的一级元素(外套、鞋子、大表情)。
脑补并设计二级深度元素(她内衣穿什么风格?她包里会装什么口红?她独处时会用什么物品?)。
生成一张包含所有这些元素的组合图，确保透视准确，光影统一，注释清晰。
使用中文:高清4K HD 输出


```

## 5️⃣1️⃣ 角色一致性与口型准确性

prompt
```
请绘制一张四宫格图片，四张图依次表现同一位戴着斗笠的年轻男子分别发音「我」「上」「早」「八」，人物外貌保持一致，口型准确对应每个字的发音，整体风格统一，16:9，4K
```

![角色一致性](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719889.png)

## 5️⃣2️⃣ 漫画上色与翻译

prompt
```
将图片上的文字翻译为中文，并上色，其他不变
```

![漫画上色](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719131.png)


## 5️⃣3️⃣ 国际化海报翻译与重排

prompt
```
将英文海报中的英文翻译成中文。
```

![海报翻译](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719266.png)

## 5️⃣4️⃣ 复杂UI界面复刻（聊天记录）
prompt
```
生成两张竖版的微信群聊天界面截图，群成员正在讨论 Nano Banana Pro 的发布。
```

![UI复刻](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719642.png)

## 5️⃣5️⃣ 长文本与古画风格结合

prompt
```
生成一幅 4K 古画，画上写着：明月几时有？把酒问青天。不知天上宫阙，今夕是何年。我欲乘风归去，又恐琼楼玉宇，高处不胜寒。起舞弄清影，何似在人间。转朱阁，低绮户，照无眠。不应有恨，何事长向别时圆？人有悲欢离合，月有阴晴圆缺，此事古难全。但愿人长久，千里共婵娟。
```

![古画风格](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719856.png)


## 5️⃣6️⃣ IP角色融合创作

prompt
```
哆啦A梦和李白在月下对酌。圆月高悬，古代亭台楼阁，哆啦A梦穿着唐朝服饰，李白持酒壶，石桌上摆着酒具，仙气飘飘，中日混合画风，精致细节
```

![IP融合](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719241.png)


## 5️⃣7️⃣ 搜索增强：实时信息可视化（行程规划）
prompt
```
生成一张可视化的图片，展示在广州旅游的 2 天行程。
```

![行程规划](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211719795.png)

## 5️⃣8️⃣ 搜索增强：实时信息可视化（天气信息图）
prompt
```
搜索广州实时天气信息，制作一幅中文波普艺术风格的信息图，4:3
```

![天气信息图](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211720294.png)

## 5️⃣9️⃣ 搜索增强：实时天气UI设计

prompt
```
帮我搜索现在（20251120）北京的天气信息，并且将其放在一个天气UI设计稿中
```

![天气UI](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740561.jpeg)

## 6️⃣0️⃣ 搜索增强与图像编辑结合

prompt
```
搜索北京市今天（202511120）的天气和一条正能量的早间新闻。将我的照片转换成'美式复古海报'风格。在海报顶部用巨大的艺术字写上今天的日期（中文），底部用报纸排版风格写上那条新闻的摘要和今天的天气提示。
```

![搜索增强](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740241.png)

## 6️⃣1️⃣ 多语言手账创作
prompt
```
帮我生成一张拼贴手帐风格的广西旅游笔记，上面记录着自己的行程以及路上的照片等，文字有中文、韩语和英语。
```

![多语言手账](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740100.jpeg)

## 6️⃣2️⃣ 多图输入与手写日记风格

prompt
```
模拟在一张略带纹理的纸张上（米黄色或者浅棕色）手写的关于今天的日记。所有的图片以拼贴画风格放在一页日记上，保证图片与原图一致包含以下元素：用手写字体描述今天做了什么，以及一两句吸引人的标语或简介，包含几张图片的介绍，用红色笔迹或其他亮色圈出或用箭头指向特别推荐的地点或活动。穿插一些与图片特色相关的简单涂鸦式小图画，写着当前的日期和北京的天气，并添加一个图 4 手绘角色形象。整体感觉要像一份由热爱生活的作者精心制作的、生动有趣的个人日记。

```
![手写日记](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740825.jpeg)

## 6️⃣3️⃣ 中文字体设计
prompt
```
（示例为多种字体设计提示词的综合效果展示）
```

![字体设计](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740992.jpeg)

## 6️⃣4️⃣ 产品海报设计（单图）
prompt
```
为这款米色皮革手机壳设计产品海报。手机壳侧立放置的超近景特写，清晰展现素皮细腻纹理与橙色金属镜头圈的撞色质感，背部吸附同色系磁吸卡包。米色背景，周围缭绕棕色透明轻纱，搭配几株蕨类植物、沉香枯木与两支铃兰作为前景点缀。4K超清画面质感。静物摄影，昏暗氛围，光线追踪，高级柔光。海报上方文案标题："AATTT STUDIO"，极细衬线字体。页面下方小字："素皮 | 磁吸 | 极简"。艺术签角标："AATTT | Design"。
```

![产品海报](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740269.png)

## 6️⃣5️⃣ 产品海报设计（多图）
prompt
```
为这两个香薰产品设计产品海报。两个香薰放在一起的超近景特写，质感清晰。米色背景，周围棕色透明轻纱，蕨类植物，沉香枯木，两支铃兰。4K超清画面质感。静物摄影，昏暗氛围，光线追踪。海报上方文案标题："昆仑煮雪"，极细文字。页面下方小字："沉香|铃兰|草本"。艺术签角标："观夏|to summer"。
```

![香薰海报](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740031.jpeg)

## 6️⃣6️⃣ 产品场景渲染
prompt
```
帮我将这个香薰放在符合设计风格的室内，大师级摄影，特写镜头
```

![场景渲染](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740567.jpeg)

## 6️⃣7️⃣ 多物品场景融合

prompt
```
将这些家具融洽的放到一个房间中
```

![家具融合](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740721.jpeg)



## 6️⃣8️⃣ 人像精细编辑与美颜
prompt
```
轻度美颜、瘦脸，发型替换为美式前刺，发际线前移，眼镜更换为墨镜
```

![人像编辑](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740959.jpeg)

## 6️⃣9️⃣ IP版权内容生成（跨文化融合）
prompt
```
杰瑞鼠身披《大闹天宫》动画版标志性的鹅黄色虎皮裙、大红披风和金甲，头戴凤翅紫金冠，手持金箍棒，面部表情夸张而神气，背景是天宫的亭台楼阁或花果山水帘洞，整个画面都将严格遵循上海美术电影制片厂《大闹天宫》的经典画风，色彩浓烈，线条流畅，充满浓郁的中国传统水墨和工笔重彩韵味。
```

![大闹天宫](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740823.jpeg)

## 7️⃣0️⃣ IP版权内容生成（关系图）
prompt
```
一张手帐风格图片，上面画着电视剧权力的游戏的人物关系和势力关系图，人物有头像
```

![权游关系图](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740621.jpeg)
## 7️⃣1️⃣ IP版权内容生成（游戏截图）
prompt
```
3D写实风格的宝可梦主题MMO游戏截图
```

![宝可梦游戏](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740038.jpeg)

## 7️⃣2️⃣ 白模上色与渲染
prompt
```
为这张手办完成材质添加和上色，同时将周围环境变为符合角色设定的环境
```

![手办上色](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740819.jpeg)

## 7️⃣3️⃣ 漫画翻译与上色（复杂场景）
prompt
```
（示例为对复杂海贼王漫画页进行翻译和上色）
```

![海贼王上色](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740983.jpeg)

## 7️⃣4️⃣ 酸性设计/Y2K风格海报转换
prompt
```
请分析我上传的这张照片，并将其转换成一张现代风格的平面设计海报。主体处理：首先，将主体从原始背景中精确地抠出来，作为海报的核心主体。背景改造：将原始背景替换为一个抽象的、具有毛玻璃质感的背景。核心构图：在主体的后面，添加一个醒目的纯色矩形色块。风格统一：确保整个海报的风格是Y2K美学或酸性设计。
```

![酸性设计](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740806.jpeg)
![Y2K风格](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740707.jpeg)

## 7️⃣5️⃣ UI设计风格迁移

prompt
```
模仿这个设计稿的风格和关键元素表现形式，帮我生成一个天气应用的UI设计稿
```

![UI风格迁移](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740851.jpeg)

## 7️⃣6️⃣ 超长文本古风画卷
prompt
```
在画面上方有一张长长的画卷上用潇洒的书法写着一整首白居易的《琵琶行》内容是"浔阳江头夜送客，枫叶荻花秋瑟瑟...座中泣下谁最多？江州司马青衫湿。"，同时下方用中国水墨画风格画上这首诗对应的画面
```

![琵琶行](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211742741.jpeg)



## 7️⃣7️⃣ 视觉小说：现代言情

```
生成一个现代校园风格的视觉小说场景...对话框显示男主角的中文对话：'你为什么不相信我？'，要求男主角的表情为'焦急'，而女主角的表情为'怀疑'。
```
## 7️⃣8️⃣ 视觉小说：古风武侠

```
生成一个古风武侠场景...对话框中显示第三位角色的中文台词：'此物非同小可，谁来保管？'...
```

![古风武侠](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211740689.jpeg)

## 7️⃣9️⃣ 视觉小说：奇幻冒险

```
生成一个奇幻冒险风格的视觉小说界面...屏幕下方清晰显示两个中文剧情选项按钮：'1. 掷出匕首' 和 '2. 召唤契约魔兽'。
```

![奇幻冒险](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211741290.jpeg)

## 8️⃣0️⃣ 电影海报《死亡诗社》
```
电影《死亡诗社》艺术海报...主标题用流动的艺术手写字体"死亡诗社"...
```

![死亡诗社](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211742631.jpeg)

## 8️⃣1️⃣ 电影海报《天书奇谭》
```
动画电影《天书奇谭》艺术海报，中国山水画风格...主题为手写艺术字体"天书奇谭"...
```

![天书奇谭](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211742848.jpeg)

## 8️⃣2️⃣ 活动海报设计
```
我要举办一场活动，主题为"AI赋能发明创新"...请帮我画一张宣传海报...
```

![活动海报](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211749177.png)

## 8️⃣3️⃣ 知识图谱：应县木塔结构图

```
为我生成西安大同应县木塔的结构解说图，附上一整段详细中文，中文字清晰。
```

![应县木塔](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211742475.jpeg)


## 8️⃣4️⃣ 知识图谱：苏绣工艺图
```
为我生成苏绣工艺的详细解说图，配上详细的中文知识解析。
```

![苏绣工艺](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211742643.jpeg)

## 8️⃣5️⃣ 知识图谱：百年孤独人物关系图
```
画出《百年孤独》中的重要人物关系图，用中文表示关系。
```

![百年孤独](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211751857.png)

## 8️⃣6️⃣ 知识图谱：锂电池原理图
```
锂电池作用原理图，用中英文双语进行标注
```

![锂电池](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/202511211749359.png)

## 8️⃣7️⃣ 透视图解：金门大桥工程图
```
这是一张经典的旧金山金门大桥风景照，但在画面之上，叠加了一层白色手绘风格的工程结构图解。
```

![金门大桥](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/640-20251121225945521.jpeg)

## 8️⃣8️⃣ 透视图解：宇航服技术图纸
```
绘制此图的技术图纸
```

![宇航服](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/640-20251121230025209.jpeg)

## 8️⃣9️⃣ 多图融合：硅谷AI圈大合照
```
将多个不同的AI领域人物完美融合到一个场景中，保持各自特征一致。
```

![AI大合照](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/640-20251121225950556.jpeg)
## 9️⃣0️⃣ 多角色融合
```
同时处理十几张不同角色的参考图，并且把它们完美融合到一个客厅场景中。
```

![角色融合](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/640-20251121225951800.png)

## 9️⃣1️⃣ 组图生成：产品多角度渲染
```
用这个logo制作一件周边套头卫衣，并且生成这件衣服的4个角度，4个不同的动态视图，特写、斜角、半身照和细节照。
```

![产品组图](https://maynor123-1301929665.cos.ap-guangzhou.myqcloud.com/640-20251121230031902.png)

## 9️⃣2️⃣ 产品拍摄

<img width="1536" height="960" alt="产品拍摄" src="https://github.com/user-attachments/assets/9a74a202-a510-456e-aa0a-9092c63ea61b" />

prompt


```
Professional product photography of [product name], centered composition, pure white background, soft even lighting from multiple angles, no shadows, sharp focus across entire product, e-commerce catalog style, high resolution detail
```


## 9️⃣3️⃣ 超现实主义风格艺术
<img width="1536" height="864" alt="超现实主义风格艺术" src="https://github.com/user-attachments/assets/0ff2bbf6-6338-4b59-9cc7-cbe4a7f9199e" />

prompt

```
Surrealist digital art piece with [central subject], multiple layers of detailed elements creating depth, rich saturated color palette with harmonious complementary colors, painterly brush texture visible, dynamic asymmetric composition following rule of thirds, studio-quality digital painting, fine art print worthy, 8K resolution with sharp detail throughout
```

## 9️⃣4️⃣ 宝丽来风格人像
<img width="1024" height="1024" alt="Polaroid拍立得照片" src="https://github.com/user-attachments/assets/9d451576-8021-4713-ba4f-87bc78cba8fe" />


prompt
```
Instant camera Polaroid photo aesthetic showing [subject], characteristic color shift with slightly faded tones, white border frame with handwritten text at bottom reading [text], subtle light leak in corner, held in someone's hand or laid on wooden surface, nostalgic 90s photography vibe, square format composition
```

## 9️⃣5️⃣ 电影场景与氛围灯光

<img width="3402" height="1443" alt="abandoned_coastal_pier_cinematic_副本" src="https://github.com/user-attachments/assets/d3efb632-37c7-47b2-a7f8-889f282d64ca" />

prompt
```
Cinematic wide shot of [scene description], dramatic volumetric lighting rays cutting through atmosphere, color graded with teal and orange cinematic look, shallow depth of field with foreground and background blur, film grain texture, shot on ARRI camera with anamorphic lens, movie poster composition, 2.39:1 aspect ratio feel, 4K quality
```

## 9️⃣6️⃣ 战败CG
![战败CG](https://github.com/user-attachments/assets/9116bab1-1c98-4c18-bce6-4f942b62a453)
prompt
```
写实风，俯视，平铺。整体比例接近 16:9。整体风格高清、细节丰富、光线柔和、二次元与真人写真自然融合。一个真人 coser人物于图片下方背对主视角以土下座在地板上只露出后脑勺，上半身裸露，假发和头饰无需脱下，服装整齐地摆放在人周围，如衣服包括内衣裤，鞋子，袜子。场景设置在榻榻米地板上。
```

## 9️⃣7️⃣ 人物说明（真人版）
![人物说明（真人版）](https://github.com/user-attachments/assets/3b7afcda-fe65-4755-8494-d46294839b2d)

prompt
```
/imagine prompt:

16:9 aspect ratio, photo-realistic, masterpiece, best quality, ultra-detailed.
A top-tier Chinese female professional cosplayer. Exquisite, layered makeup and coloring. Features are sculpted with photorealistic precision, lifelike 3D quality. Professional studio lighting highlights muscle definition and fabric folds, creating strong volume and dimension. Skin has a soft, matte texture with visible, fine vellus hair under realistic light.

--ar 16:9 --style raw --no 2D, painting, illustration, cartoon, anime, expanded art, deformed, blurry, text, watermark

LAYOUT:
A three-column grid composition. The central column is twice the width of the side columns (1:2:1 ratio).

[Left Column, weight 1, seamless tiled bathroom background]::
    (Top Section: 1/3 height) High-angle close-up of chest in a bra matching the character's design; below, a macro shot of cleavage.
    (Middle Section: 1/3 height, "Crotch Close-up Set") A close-up shot showing her crotch area, pantiless but censored with a thin black bar; below, another shot of her pulling down her panties just enough to reveal the inguinal region (v-line).
    (Bottom Section: 1/3 height) Frontal close-up of pelvic area in panties matching the character's design; below, a back close-up of buttocks in the same panties.

[Center Column, weight 2, comic convention background]::
    Medium shot of the cosplayer perfectly replicating the expression, pose, appearance, and hairstyle of an anime character. Her costume and props are realistic in material but retain a 25% anime aesthetic. An acrylic stand of the original anime character is placed beside her.

[Right Column, weight 1, seamless tiled bathroom background]::
    (Top Section: 1/3 height) Face close-up: shy expression, averted eyes, closed mouth, making a V-sign with one hand; below, expression close-up: tongue out, rolling eyes (ahegao), blushing cheeks.
    (Middle Section: 1/3 height) Side-by-side full-body shots wearing underwear matching the character's design: one from the front, one from the back, both with a standing pose and hands at her sides.
    (Bottom Section: 1/3 height) Knolling/flat lay shot: the entire costume is disassembled into its smallest components (socks, shoes, character-themed bra and panties, skirt, top, hair accessories) and neatly arranged on the floor.
```

## 9️⃣8️⃣ 真人galgame
![galgame](https://github.com/user-attachments/assets/9f253ed8-7bb2-48e6-b39c-0cb7a8d984e9)
prompt
```
生成一张竖版手机截图风格的图片，整体比例接近 9:16。画面中心偏上是一位真人 coser，扮演（角色名称）的二次元角色。人物为写实风格，但五官略带动漫感，皮肤细腻，眼睛稍大，表情温柔地看向镜头，坐在室内的休闲场景中，例如咖啡厅或酒吧吧台前，背景有符合场景的道具。画面最上方加入手机系统状态栏 UI，包括时间、电量、信号、网络等图标，让整张图看起来像手机截图。画面底部叠加一块宽大的半透明 galgame 风格对话框，对话框左侧放一个与画面人物对应的动漫或 Q 版头像；对话框右侧排版文字：第一行用较大字体显示与前面相同的角色名字，下面一到两行显示一段适合这个角色人设的、温柔治愈风格的简体中文台词，由你自动创作。再在对话框下方加一条操作栏，仿照 galgame UI。整体风格高清、细节丰富、光线柔和、二次元与真人写真自然融合。
```
## 9️⃣9️⃣ 将真人包装成圣诞礼物
![圣诞礼物](https://github.com/user-attachments/assets/9636e852-54ff-4149-877f-1e088b2e077b)

prompt
```
让图1人物躺下来，被包裹在圣诞礼盒里。人物丝带裹身，露出肩膀、胸口、腰部和大腿，嘴叼着丝带的一头。附带一张贺卡，上面写着“Merry Christmas!”。保持画风以及保持人物在生日礼盒里，礼盒里有圣诞元素。人物在内部蜷缩成一团。保持人物体型比例不变。保持人物头型和装饰不变。
```
## 1️⃣0️⃣0️⃣ 人物/产品背景替换
![IMG_2284](https://github.com/user-attachments/assets/e3ff471a-803d-4e52-9623-23fb9bdec5a8)

prompt
```
[Subject from original image] isolated and placed onto [new background description], matching ambient lighting and color temperature between subject and new environment, appropriate shadows cast onto new background surface, seamless edge blending with natural depth of field, photorealistic integration, no visible cut-out artifacts
```

## 1️⃣0️⃣1️⃣ 服装提取

参考图图vs提取的服装

服装整体放置promp（如果后续要让自己的模特穿这套服装，推荐这种方案）
![IMG_2287](https://github.com/user-attachments/assets/edd98991-cc99-460e-b7d4-e6c8d82ccf96)



```

删除人物与背景，只保留一整件完整的衣服。
严禁拆分、分离、复制、错位、重组、变形这件衣服。
衣服必须是一个完整整体，就像平铺在地上一样。
保持原比例、原颜色、原纹理、原褶皱与全部细节。
所有衣袖、领口、口袋等部位必须正确连接。
最终输出：一整件衣服，居中，纯白背景，高分辨率高清。

```

服装分开放置promp

![IMG_2286](https://github.com/user-attachments/assets/4494e8b1-1507-4aef-b60c-23d438097c92)


```
生成这张图片的服装平铺图，把每件服装分开放置
```

若要增加服装说明，可以加上

```
使用手绘箭头或引导线，连接每件服装，并使用中文模拟手写注释，标注出每件衣服的名称款式与材质，字体清晰，模拟手写注释，有高级感，设计感，和美感

```


📬 **联系我**：
- 邮箱：zoulinshen666@gmail.com

## ⚖️ 致谢 (Credits)

Core concepts based on the wisdom of the masses

Optimization & Extension by [Eternity 初夏]
