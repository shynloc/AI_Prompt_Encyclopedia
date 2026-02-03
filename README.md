# AI_Prompt_Encyclopedia
这是一本真正的“提示词单词书”。

# **虚拟影像的终极法典：光影、质感与人像摄影的AI提示词百科全书**

## **执行摘要：从关键词堆砌到光子级精度的语义构建**

随着生成式人工智能技术的飞跃，特别是Midjourney V7、Stable Diffusion XL (SDXL)以及Flux模型的问世，数字图像的生成逻辑已经发生了根本性的范式转移。我们已经告别了早期的“关键词沙拉”（Keyword Salad）——即混乱地堆砌不相关词汇的时代，迈入了一个语义精确、物理逻辑严密的新纪元。现在的提示词工程（Prompt Engineering）不再是简单的拼凑，而是一门融合了光学物理、材料科学、摄影美学与计算机图形学的综合学科。

为了响应对“高清晰度”、“最佳光影”、“皮肤质感”以及“详尽词汇表”的深度需求，本报告将作为一份详尽的研究专著与实用指南。本报告不仅是一份操作手册，更是一部关于虚拟光学的理论著作与实战词典。我们将深入解构光线在潜空间（Latent Space）中的传播行为，分析数字皮肤的微观结构，探讨虚拟镜头的像差原理，并最终提供一份像“单词书”一样全面、分类清晰、直接可用的提示词大全。

本报告旨在通过超过一万五千字的篇幅，穷尽当前AI绘画领域与摄影质感相关的所有核心词汇与概念，帮助创作者在Midjourney、Stable Diffusion等主流模型中，重现甚至超越物理摄影的质感。

## ---

**第一章：影像保真度的基石——分辨率与成像质量**

在AI生成中，“高质量”并不是一个单一的指令，而是由边缘对比度、信噪比、微观纹理密度以及光学行为的合理性共同构成的复合概念。要生成一张“照片级”的图像，我们需要用语言构建出高分辨率摄影的物理特征。

### **1.1 定义清晰度与渲染引擎的词汇矩阵**

模糊的指令如“好看的图片”只会产生平庸的结果。为了获得专业级的锐度，我们必须借用信号处理与高端渲染领域的专用术语。这些词汇不仅仅是形容词，它们在模型的潜空间中充当着“锚点”，将生成结果拉向高质量的训练数据簇。

#### **1.1.1 通用质量修饰词（Global Quality Modifiers）**

以下词汇通常用于Prompt的开头或结尾，用于设定画面的基础物理属性。

| 核心词汇 (中文/英文) | 技术含义与潜空间映射 | 最佳应用场景 | 关联引用 |
| :---- | :---- | :---- | :---- |
| **8K分辨率 (8k Resolution)** | 强制模型参考高像素密度的源数据，显著提升边缘锐度与细节保留率。 | 风景大片、需要极高细节的微距摄影。 | 1 |
| **照片级真实感 (Photorealistic)** | 抑制绘画性（Painterly）伪影，使光影过渡符合物理规律，增强纹理的随机性。 | 追求绝对真实的纪实摄影、新闻摄影风格。 | 3 |
| **超写实主义 (Hyper-realistic)** | 超越肉眼观察的极限，强化微观对比度（Micro-contrast），使细节呈现出一种“超真”的质感。 | 昆虫复眼特写、皮肤毛孔级特写、珠宝摄影。 | 1 |
| **杰作 (Masterpiece)** | （SD模型专用）在早期数据集中关联高审美评分的图像。在MJ V7中更多指构图的完整性。 | 避免生成结构崩坏或模糊的图像，作为保底词使用。 | 6 |
| **虚幻引擎5 (Unreal Engine 5\)** | 召唤实时渲染的“数字清晰感”，强调高动态范围（HDR）、锐利的几何边缘与精确的全局光照。 | 科幻场景、硬表面建模、建筑可视化、汽车广告。 | 8 |
| **Octane渲染 (Octane Render)** | 引用基于物理的渲染（PBR）引擎风格，以极其准确的光线衰减和焦散效果著称。 | 产品摄影、3D艺术风格、玻璃与金属材质表现。 | 10 |
| **锐利聚焦 (Sharp Focus)** | 指示AI最小化主体上的模糊，增强边缘检测算法的权重，使主体与背景分离。 | 人像摄影、产品特写，任何需要主体极度清晰的场景。 | 1 |
| **RAW照片 (Raw Photo)** | 模拟相机传感器未压缩的原始数据，保留高光与阴影细节，减少AI过度饱和的倾向。 | 纪实风格、电影剧照、追求自然色调的肖像。 | 13 |
| **最佳质量 (Best Quality)** | 在NovelAI或某些SD模型中作为触发词，但在V7中，更建议通过描述细节来体现质量。 | 通用增强，但在现代模型中需配合具体细节描述使用。 | 6 |

**深度洞察：** 在Midjourney V7或Flux等现代模型中，单纯堆砌“Best Quality”的效果正在减弱。模型现在更倾向于通过“证据”来理解质量。例如，描述“visible dust on the lens”（镜头上的灰尘）或“fabric weave texture”（织物编织纹理），比单纯说“高质量”更能诱导模型生成高频细节。这被称为“特征性提示”（Feature-based Prompting）1。

#### **1.1.2 渲染技术与数字伪影术语表**

为了进一步控制画面的“数字味道”，我们需要掌握渲染技术的底层词汇。

* **光线追踪 (Ray Tracing):** 模拟光线的物理反弹，增强反射和折射的真实感 8。  
* **全局光照 (Global Illumination / GI):** 确保光线能像现实中一样漫反射，照亮阴影区域，使画面不再死黑 9。  
* **环境光遮蔽 (Ambient Occlusion):** 强调物体接触面和缝隙处的阴影，增加体积感和立体感。对于建筑和复杂的机械结构至关重要。  
* **次表面散射 (Subsurface Scattering / SSS):** 光线穿透半透明物体（如皮肤、蜡、树叶）并在内部散射的现象。这是生成真实人像的**核心词汇** 8。  
* **色差 (Chromatic Aberration):** 模拟镜头无法将所有颜色的光聚焦在同一点产生的红蓝边缘溢出。适度使用可增加“真实镜头的缺陷感”，避免画面过于完美的CG感 15。  
* **ISO噪点 (ISO Noise / Film Grain):** 增加胶片颗粒感或数字噪点，不仅能增加复古感，还能在视觉上掩盖AI生成的微小瑕疵，提升整体的真实度.3

## ---

**第二章：虚拟相机光学——镜头语言与视觉几何**

在AI生成中，我们实际上是在操作一台“虚拟相机”。如果不指定镜头参数，AI会随机选择一个视场角，往往导致构图平庸。通过精确指定焦距、光圈和传感器尺寸，我们可以控制透视关系、景深以及主体与背景的空间压缩感。

### **2.1 焦距与透视的百科全书**

焦距不仅决定了拍到多少内容，还决定了人脸的“胖瘦”和背景的距离感。

#### **2.1.1 广角镜头体系 (The Wide Angle System)**

* **14mm \- 24mm (超广角/广角):**  
  * *视觉效果:* 极度夸张的透视，近大远小，背景囊括范围极广。边缘会有桶形畸变。  
  * *心理暗示:* 宏大、震撼、动态、压迫感。  
  * *常用提示词:* Wide-angle lens (广角镜头), Fisheye lens (鱼眼镜头), GoPro footage (运动相机视角), Panoramic view (全景视图), Distorted perspective (夸张透视).  
  * *适用场景:* 史诗级风景、狭窄的室内空间展示、具有冲击力的动作场面 16。

#### **2.1.2 标准镜头体系 (The Standard System)**

* **35mm \- 50mm (人文/标准):**  
  * *视觉效果:* 最接近人眼的自然视角，畸变极小，透视关系平和。  
  * *心理暗示:* 真实、亲切、纪实、客观、身临其境。  
  * *常用提示词:* 50mm lens (50mm镜头), Prime lens (定焦镜头), Nifty Fifty (小痰盂/50mm), Street photography (街头摄影), Human eye view (人眼视角).  
  * *适用场景:* 街拍、环境人像、新闻纪实、日常快照 3。

#### **2.1.3 长焦镜头体系 (The Telephoto System)**

* **85mm \- 135mm (人像黄金焦段):**  
  * *视觉效果:* 适度的空间压缩，对面部有极佳的修饰作用（使面部显得更平整、立体），背景虚化效果明显。  
  * *心理暗示:* 专注、美化、专业、隔离。  
  * *常用提示词:* 85mm f/1.2, Portrait lens (人像镜头), Medium telephoto (中长焦), Flattering compression (美化压缩), Canon 85mm L (佳能红圈头).  
  * *适用场景:* 专业半身像、时尚大片、特写 16。  
* **200mm+ (超长焦):**  
  * *视觉效果:* 极端的空间压缩，背景仿佛贴在主体身后，景深极浅（背景完全模糊）。  
  * *心理暗示:* 窥视、遥远、极度聚焦、压缩感。  
  * *常用提示词:* Super-telephoto (超长焦), Zoom lens (变焦镜头), 200mm lens, Sports photography (体育摄影), Paparazzi shot (狗仔队视角).  
  * *适用场景:* 野生动物、体育赛事、或是需要把远处的月亮拍得巨大的场景 18。

#### **2.1.4 特殊光学镜头**

* **微距镜头 (Macro Lens):**  
  * *关键词:* Macro photography, 100mm Macro, 1:1 magnification (1:1放大率), Microscopic (显微级).  
  * *用途:* 拍摄昆虫复眼、露珠、虹膜纹理、珠宝细节。  
* **移轴镜头 (Tilt-Shift Lens):**  
  * *关键词:* Tilt-shift, Miniature effect (微缩模型效果), Selective focus (选择性对焦).  
  * *用途:* 让城市看起来像玩具模型，或者创造奇异的焦平面 19。

### **2.2 光圈与景深控制词典**

光圈（Aperture）决定了画面的进光量和虚化程度（Bokeh）。在AI中，它是控制背景干扰、突出主体的最强工具。

| 术语 (中文/英文) | 光圈值对应 | 视觉效果描述 | 提示词应用 |
| :---- | :---- | :---- | :---- |
| **浅景深 (Shallow Depth of Field)** | f/1.2 \- f/2.8 | 背景模糊，主体清晰。创造梦幻感，分离主体。 | Shallow depth of field, Blurred background, f/1.8 3。 |
| **散景 (Bokeh)** | f/1.2 \- f/1.4 | 焦外模糊区域形成的光斑效果，通常呈圆形或多边形。 | Creamy bokeh (奶油般散景), Swirly bokeh (旋焦), Bokeh balls (光斑), Cinematic bokeh 18。 |
| **深景深 (Deep Depth of Field)** | f/8 \- f/16 | 从前景到背景都清晰锐利。 | Deep focus, Sharp background, f/16, Everything in focus。 |
| **超焦距 (Hyperfocal Distance)** | f/11 \- f/22 | 风景摄影常用，确保最大范围的清晰度。 | Hyperfocal focus, Landscape focus, Crisp horizon。 |

**实战技巧：** 在Stable Diffusion或MJ中，如果你只写“Bokeh”，AI可能会随机生成杂乱的光斑。如果你写Creamy bokeh或Smooth background blur，AI会生成更柔和、更有高级感的虚化效果，避免背景抢镜 13。

## ---

**第三章：光线的物理学——照明模式与氛围构建**

光线是摄影的灵魂，也是AI生成“质感”的关键。AI模型并不像3D引擎那样计算光线路径，而是通过识别训练数据中光影的“视觉特征”来模拟光照。因此，使用专业的布光术语，可以极大地提升画面的立体感和情绪。

### **3.1 自然光分类大全 (The Natural Light Lexicon)**

自然光随时间、天气和地理位置而变化。

#### **时间维度的光线**

* **黄金时刻 (Golden Hour):** 日出后或日落前的一小时。  
  * *特征:* 暖色调（金黄/橙色），低角度光线，拉长的投影，柔和的漫反射。  
  * *关键词:* Golden hour, Warm lighting, Sun flare (太阳耀斑), Long shadows, Soft directional light 3。  
  * *情绪:* 温暖、怀旧、希望、浪漫。  
* **蓝调时刻 (Blue Hour):** 日出前或日落后的暮光时分。  
  * *特征:* 冷色调（深蓝/紫色），天空呈现深邃的蓝色，城市灯光开始亮起，冷暖对比。  
  * *关键词:* Blue hour, Twilight, Deep blue sky, Cool tones, Magical hour。  
  * *情绪:* 宁静、忧郁、神秘、电影感。  
* **正午阳光 (Hard Sunlight):** 太阳直射。  
  * *特征:* 强烈的对比度，极硬的阴影，高光溢出，色彩饱和。容易暴露皮肤瑕疵，但极具冲击力。  
  * *关键词:* Hard shadows, High contrast, Noon, Harsh sunlight, Direct sunlight。  
  * *情绪:* 真实、残酷、充满活力、干燥。

#### **气象维度的光线**

* **漫射光/阴天 (Overcast / Diffused):** 云层作为巨大的柔光箱。  
  * *特征:* 无明显投影，光线均匀柔和，色彩还原准确，适合表现细腻质感。  
  * *关键词:* Soft light, Overcast, Cloudy day, Diffused light, Shadowless 22。  
* **体积光/丁达尔效应 (Volumetric Lighting / God Rays):** 光线穿过空气中的微粒（雾、尘、烟）。  
  * *特征:* 可见的光柱，极强的空间感和神圣感。  
  * *关键词:* God rays, Crepuscular rays, Light shafts, Volumetric fog, Tyndall effect, Dust motes 21。

### **3.2 影棚布光模式指南 (Studio Lighting Patterns)**

在生成人像时，指定布光模式是区分“游客照”与“大片”的关键。

| 布光模式 (中文/英文) | 光位描述 | 视觉特征 | 适用场景与关键词 |
| :---- | :---- | :---- | :---- |
| **伦勃朗光 (Rembrandt)** | 主光在侧上方45度。 | 在暗部脸颊形成一个倒三角形的光斑。高对比，极具戏剧性。 | Rembrandt lighting, Chiaroscuro (明暗对照法), Triangle of light 22。男性、情绪人像。 |
| **蝴蝶光 (Butterfly)** | 主光在正面高处。 | 在鼻子下方形成像蝴蝶形状的阴影。突出颧骨，显瘦。 | Butterfly lighting, Paramount lighting, Glamour lighting 14。女性、美妆片、好莱坞复古风格。 |
| **分割光 (Split Lighting)** | 光源在正侧面90度。 | 半张脸亮，半张脸暗。最强的戏剧冲突感。 | Split lighting, Side lighting, Half shadow 25。反派角色、神秘人物、艺术创作。 |
| **环形光 (Loop Lighting)** | 光源在侧上方稍低。 | 鼻子投下小片阴影指向嘴角。最常见的自然布光。 | Loop lighting, Studio portrait lighting, 45-degree light 14。通用人像、证件照、亲切风格。 |
| **轮廓光 (Rim Lighting)** | 光源在主体正后方。 | 勾勒出主体的边缘轮廓，使主体从黑暗背景中分离。 | Rim light, Backlighting, Kicker light, Halo effect, Edge lighting 3。体育、科幻、史诗感海报。 |
| **宽光与窄光 (Broad vs Short)** | 宽光照亮正对镜头的脸，窄光照亮侧面。 | 宽光显脸胖，窄光显脸瘦且更有立体感。 | Short lighting (窄光/显瘦), Broad lighting (宽光/显胖) 27。 |

### **3.3 电影级与氛围照明词汇**

* **黑色电影 (Film Noir):** Venetian blind shadows (百叶窗阴影), Low key (低调摄影), Silhouette (剪影), Dramatic shadows 22。  
* **赛博朋克 (Cyberpunk/Neon):** Neon lighting, Cyan and magenta lighting, Glow effect, Reflective wet streets。  
* **生物发光 (Bioluminescent):** Glowing flora, Subsurface glow, Ethereal glow。  
* **烛光 (Candlelight):** Flickering light, Warm glow, Intimate atmosphere, Firelight。

**深度洞察：** 仅仅使用“Studio lighting”是不够的。你需要描述光线的“质地”。例如，Softbox lighting（柔光箱）会产生柔和的漫射光，而Hard spotlight（硬聚光灯）会产生边缘锐利的阴影。将光线描述与介质结合（如Volumetric lighting through fog）能创造出具有物理厚度的空间感 22。

## ---

**第四章：人像领域的终极词汇表——从毛孔到灵魂**

恐怖谷效应（Uncanny Valley）是AI人像的大敌。要生成有“人味”的照片，必须描述瑕疵、不对称性和生物学细节。

### **4.1 皮肤质感与“毛孔地图” (The Pore Map)**

真实的皮肤不是塑料，它有纹理、有色素沉着、有透光性。

#### **提升真实感的正面提示词 (Positive Prompts)**

* **基础质感:** Real skin texture (真实皮肤纹理), Visible pores (可见毛孔), Skin details (皮肤细节), High fidelity skin (高保真皮肤).  
* **瑕疵与特征:** Freckles (雀斑), Moles (痣), Acne scars (痤疮疤痕), Blemishes (瑕疵), Uneven skin tone (肤色不均), Redness (泛红), Spider veins (红血丝).  
* **生物学特性:**  
  * **次表面散射 (Subsurface Scattering):** 必加词汇。让皮肤在逆光下呈现半透明的肉红色，而不是像石膏一样死板 8。  
  * Peach fuzz / Vellus hair (面部绒毛): 这是区分AI图和真照片的终极细节，尤其在逆光下 17。  
  * Oily skin (油性皮肤), Sweat droplets (汗珠): 增加生动感。  
* **年龄特征:**  
  * *年轻:* Baby fat (婴儿肥), Rosy cheeks (红润面颊), Smooth complexion (光滑肤色).  
  * *成熟:* Wrinkles (皱纹), Crow's feet (鱼尾纹), Laugh lines (法令纹), Sun spots (晒斑), Weathered skin (风霜感的皮肤) 29。

#### **人像负面提示词 (Negative Prompts \- 必背)**

在SD中使用Negative Prompt框，MJ中使用--no参数：

Airbrushed (喷枪磨皮), Smooth skin (光滑皮肤), Plastic skin (塑料皮肤), Makeup (浓妆 \- 如果想要素颜), Blur (模糊), Cartoon (卡通), Doll-like (娃娃脸), Oversmoothed (过度平滑), Filter (滤镜感) 30。

### **4.2 眼睛：心灵的窗户 (The Lexicon of Eyes)**

AI常画坏眼睛（瞳孔不圆、眼神空洞）。

* **解剖结构:** Iris details (虹膜细节), Dilated pupils (瞳孔放大), Limbal ring (角膜缘环 \- 虹膜外圈的深色环), Tear duct (泪腺), Sclera (巩膜/眼白), Eyelashes (睫毛 \- 需配合Detailed eyelashes以免糊成一团) 5。  
* **光影与反射:** Catchlight (眼神光 \- 至关重要，没有它眼睛就是死的), Reflection in eye (眼球反射), Glistening eyes (水润的眼睛), Wet eyes (湿润眼眶)。  
* **颜色与状态:** Heterochromia (异色瞳), Piercing blue eyes (穿透力的蓝眼), Hazel eyes (榛色眼), Bloodshot eyes (充血的眼睛)。

### **4.3 发型与毛发物理 (Hair Physics)**

* **质地:** Silky straight (丝滑直发), Frizzy (毛躁 \- 增加真实感), Greasy hair (油头), Wet hair (湿发), Windblown (风吹乱), Flyaways (飞发/碎发 \- 极其重要，模拟真实头发的凌乱感).3  
* **发型大全:**  
  * *短发:* Pixie cut (精灵短发), Buzz cut (寸头), Crew cut (平头), Undercut (底削), Fade (渐变铲青).  
  * *中长:* Bob (波波头), Lob (长波波), Shag (碎发层次), Mullet (狼尾).  
  * *长发:* Waist-length (及腰长发), Layers (层次感), Ponytail (马尾), Messy bun (丸子头).  
  * *卷发:* Beach waves (大波浪), Ringlets (小卷), Afro (爆炸头), Dreadlocks (脏辫), Braids (辫子), Cornrows (贴头皮辫) 32。

### **4.4 表情与微表情 (Micro-Expressions)**

避免只会用“Smile”或“Sad”。使用具体的面部肌肉动作描述。

* **喜悦:** Duchenne smile (杜兴微笑 \- 眼角有笑纹的真笑), Smirk (坏笑/假笑), Grinning (咧嘴笑), Dimples (酒窝).  
* **愤怒:** Furrowed brows (紧锁眉头), Snarl (龇牙), Clenched jaw (咬紧牙关), Flared nostrils (鼻孔张大).  
* **悲伤:** Teary-eyed (含泪), Quivering lip (嘴唇颤抖), Downturned mouth (嘴角下撇), Grief-stricken (极度悲伤).  
* **复杂情绪:** Contemplative (沉思), Skeptical (怀疑 \- 挑眉), Wistful (渴望/惆怅), Deadpan (面无表情/冷面滑稽), Seductive (诱惑), Disgusted (厌恶) 34。

**V7 技巧：** 在Midjourney V7中，描述**情境**往往比直接描述表情更自然。例如，不要只写“scared face”（害怕的脸），试试写“Face of a man watching a ghost materialize in front of him”（一个男人看着鬼魂在面前显形时的脸），AI会自动生成瞳孔放大、嘴巴微张等细腻的微表情 3。

## ---

**第五章：材质科学与环境纹理——触觉的视觉化**

要让照片有“质感”，必须让观众能通过眼睛“摸”到物体。这涉及到光线与不同材质表面的相互作用（粗糙度、反射率、金属度）。

### **5.1 时尚面料与织物百科 (Fabric & Textiles)**

不同的布料对光线的反射完全不同。

| 面料分类 | 物理特性与光线交互 | 核心提示词 |
| :---- | :---- | :---- |
| **丝绸类 (Silk)** | 高反射、流体感、光滑。 | Charmeuse silk (查米尤斯绸), Satin (缎面), Glossy (光泽), Fluid drape (垂坠感), Shimmering (微光). 36 |
| **绒面类 (Velvet)** | 吸光、边缘有柔和光晕、深沉阴影。 | Plush velvet (长毛绒), Crushed velvet (压皱天鹅绒), Soft sheen (柔光), Light absorption (吸光). |
| **粗糙/厚重 (Rough)** | 纹理清晰、不反光、硬朗。 | Raw denim (原牛丹宁), Heavy wool (厚羊毛), Tweed (粗花呢), Canvas (帆布), Corduroy (灯芯绒). 37 |
| **皮革类 (Leather)** | 强高光、有折痕、表面纹理。 | Full-grain leather (全粒面皮), Patent leather (漆皮 \- 高反光), Suede (麂皮 \- 哑光), Worn leather (磨损皮革). |
| **透视类 (Sheer)** | 半透明、轻盈、梦幻。 | Chiffon (雪纺), Organza (欧根纱), Tulle (薄纱), Lace (蕾丝), Mesh (网眼). 37 |
| **针织类 (Knits)** | 复杂的编织结构、毛绒感。 | Chunky knit (粗棒针), Cable knit (绞花针织), Cashmere (羊绒), Angora (安哥拉兔毛 \- 极强的毛绒感). |

### **5.2 环境材质与旧化纹理 (Environmental Textures)**

* **城市:** Wet asphalt (湿沥青), Cracked concrete (龟裂混凝土), Rusty metal (生锈金属), Peeling paint (剥落的油漆), Graffiti-covered brick (涂鸦砖墙)。  
* **自然:** Mossy rock (长苔藓的石头), Rough bark (粗糙树皮), Granular sand (颗粒感沙子), Morning dew on grass (草上露珠)。  
* **室内:** Polished hardwood (抛光硬木), Dusty floorboards (积灰地板), Fingerprints on glass (玻璃上的指纹 \- 极度真实细节), Shag carpet (长毛地毯)。

### **5.3 大气粒子与介质 (Atmospheric Particles)**

增加空气中的杂质，是消除“AI塑料感”的绝招。

* Floating dust motes (漂浮尘埃 \- 配合耶稣光使用)  
* Pollen in the air (空气中的花粉)  
* Falling snow flakes (飘落雪花)  
* Rain droplets on camera lens (镜头上的雨滴 \- 增加临场感)  
* Heat haze / Mirage (热浪/海市蜃楼 \- 模糊远景)  
* Smoke wisps (一缕缕烟雾)  
* Fog / Mist (雾/霭) 23。

## ---

**第六章：构图与电影语言——导演的视角**

### **6.1 摄影机角度 (Camera Angles)**

* **水平视角 (Eye-Level):** 中性、客观、连接感。  
* **低角度 (Low Angle):** 仰拍。Worm's eye view (虫视). 赋予主体力量、压迫感、英雄主义。 39  
* **高角度 (High Angle):** 俯拍。Bird's eye view (上帝视角/鸟瞰), Drone shot (无人机). 显示环境、主体显得渺小或脆弱。  
* **荷兰角 (Dutch Angle):** 倾斜地平线。Canted angle, Tilted shot. 创造紧张、不安、动态或迷幻感。  
* **过肩镜头 (Over-the-shoulder):** 交代两人关系，增加对话感。  
* **第一人称 (POV):** Point of view shot. 沉浸式体验。

### **6.2 景别 (Shot Sizes)**

* **极特写 (Extreme Close-Up / ECU):** 聚焦局部（眼睛、嘴唇、手指）。  
* **特写 (Close-Up / CU):** 头部到肩部。强调情绪。  
* **中景 (Medium Shot / MS):** 腰部以上。交代动作。  
* **牛仔景 (Cowboy Shot):** 大腿中部以上。展示自信姿态。  
* **全景 (Full Shot / Wide Shot):** 全身及周围环境。  
* **大远景 (Establishing Shot):** 极宽阔，交代场景位置。 40

### **6.3 构图法则**

* Rule of thirds (三分法)  
* Center framing (中心构图 \- 韦斯·安德森风格)  
* Symmetrical composition (对称构图)  
* Golden ratio (黄金分割)  
* Negative space (留白 \- 极简风格)  
* Leading lines (引导线 \- 道路、栏杆指向主体)  
* Framing within a frame (框式构图 \- 透过门窗拍摄)。

## ---

**第七章：色彩科学与后期处理——胶片与数码的炼金术**

### **7.1 胶片模拟 (Film Stocks)**

指定具体的胶片型号，可以直接调用该胶片特有的颗粒感、色彩偏向和宽容度。

| 胶片型号 | 视觉特征 | 适用风格 |
| :---- | :---- | :---- |
| **Kodak Portra 400** | 极佳的肤色还原，暖色调，细腻颗粒，高宽容度。 | 人像首选，婚礼，日系写真。 17 |
| **Kodak Gold 200** | 金黄色调，浓郁的怀旧感，颗粒较粗。 | 夏日度假，复古街拍，家庭相册风。 |
| **Fujifilm Velvia 50** | 极高的饱和度，高对比度，偏紫红/洋红。 | 风景摄影，鲜花，色彩浓郁的商业片。 |
| **Cinestill 800T** | 钨丝灯平衡（偏冷），高光处有独特的红色光晕（Halation）。 | 夜景，霓虹灯，赛博朋克，电影感街拍。 |
| **Ilford HP5 Plus** | 经典的黑白胶片，反差适中，颗粒感强且美。 | 纪实黑白，新闻摄影，艺术人像。 |
| **Kodak Ektar 100** | 世界上颗粒最细的负片，色彩鲜艳锐利。 | 现代风景，高细节旅游照。 |
| **Polaroid / Instax** | 柔和焦距，偏色，低对比度，特定的边框感。 | 复古快照，私房照，Lomo风格。 |

### **7.2 色彩分级与后期术语 (Color Grading)**

* **青橙色调 (Teal and Orange):** 好莱坞大片标配。肤色（橙）与阴影/背景（青）形成互补色对比。关键词：Teal and orange, Blockbuster color grading, Complementary colors 42。  
* **莫兰迪/粉彩 (Pastel):** Soft pastels, Desaturated tones, Dreamy, Wes Anderson palette.  
* **单色/黑白 (Monochrome):** Black and white, Sepia (以此), Grayscale, High contrast B\&W, Noir.  
* **酸性/霓虹 (Acid/Neon):** Vivid colors, Saturated, Neon palette, Cyberpunk colors.  
* **漂白效果 (Bleach Bypass):** Bleach bypass, Desaturated, High contrast, Gritty. 电影《拯救大兵瑞恩》风格，低饱和高对比，适合战争或硬汉题材 44。

### **7.3 光学缺陷与数字后期**

适度的缺陷让画面更真实。

* Film grain (胶片颗粒)  
* Vignette (暗角)  
* Light leaks (漏光)  
* Lens flare (镜头光晕 \- J.J. Abrams风格)  
* Halation (高光溢出/光晕)  
* Chromatic aberration (色差/紫边) 15  
* Motion blur (动态模糊)

## ---

**第八章：风格指引——艺术流派与大师**

除了“Photorealistic”，你可以引用特定的风格来定调。

* **Vogue风格:** Fashion editorial, High fashion, Studio strobe, Clean background, Pose.  
* **国家地理风格:** National Geographic style, Documentary photography, Cultural storytelling, Raw, Authentic.  
* **极简主义:** Minimalist, Clean lines, Simple composition, Less is more.  
* **韦斯·安德森 (Wes Anderson):** Symmetrical, Pastel colors, Quirky, Flat lay.  
* **赛博朋克:** Cyberpunk 2077, Blade Runner style, Futuristic, Dystopian, High tech low life.  
* **蒸汽朋克:** Steampunk, Brass, Gears, Victorian industrial.

## ---

**第九章：模型特定的语法架构 (Midjourney V7 vs. Stable Diffusion)**

虽然词汇是通用的，但“组装”方式不同。

### **9.1 Midjourney V7 语法架构**

MJ V7 对自然语言理解极佳，偏好完整的句子结构，但也接受词组堆叠。

* **标准公式:**\[主体描述\] \+ \[环境/背景\] \+ \[光线与氛围\] \+ \[摄影机参数/胶片型号\] \+ \[风格/美学\] \--参数  
* V7 核心参数 45:  
  * \--ar 16:9 (宽高比)。  
  * \--s 150 (风格化 Stylize: 0-1000)。低值（50-100）更忠实于Prompt，更写实；高值（250+）更具MJ的艺术性。  
  * \--style raw (原始风格)。**写实必备**。它减少了MJ自带的“美化滤镜”，使照片更像相机直出，质感更粗砺真实。  
  * \--sref (风格参考)。上传一张你喜欢的色调/质感的图，让MJ模仿其风格。配合 \--sw (0-1000) 控制强度 47。  
  * \--oref (Omni Reference / 全局参考)。V7新功能，用于保持物体或角色的特征一致性（替代了V6的--cref）48。  
  * \--p (个性化)。使用你个人的审美偏好模型 49。

**V7 写实作弊码:**

Subject..., shot on 35mm film, grainy texture, high contrast, street photography style \--s 100 \--style raw

### **9.2 Stable Diffusion (SDXL / Flux) 语法架构**

SD 更依赖**权重控制**和**负面提示词**。

* **权重语法:** (keyword:1.2) 增加权重；(keyword:0.8) 减少权重。  
  * 例: (visible pores:1.3), (freckles:0.8)。  
* **LoRA模型:** SD用户通常会挂载专门的LoRA（如"Real Skin", "Film Grain"）来增强特定质感。  
* **负面提示词 (Negative Prompts):** 在SD中，你不写负面词，AI就可能放飞自我。  
  * *通用负面组:* cartoon, 3d, illustration, painting, disfigured, deformed, extra limbs, bad anatomy, watermark, blurry, low quality, worst quality, sketch, render.  
  * *人像负面组:* makeup, plastic skin, airbrushed, smooth skin, doll 30。

## ---

**第十章：实战速查表 (The Master Lexicon Tables)**

为了满足您“单词书”的需求，以下是分类整理的速查表。

### **10.1 质量与真实感 (Quality & Realism)**

| 英文提示词 | 中文含义 | 作用 |
| :---- | :---- | :---- |
| **8k resolution** | 8K分辨率 | 提升整体清晰度 |
| **Photorealistic** | 照片级真实 | 基础写实风格 |
| **Unreal Engine 5** | 虚幻引擎5 | 极高锐度和动态范围 |
| **Sharp focus** | 锐利对焦 | 防止主体模糊 |
| **Detailed texture** | 细节纹理 | 增加表面细节 |
| **Micro-details** | 微观细节 | 增加极小处的真实感 |
| **Raw photo** | 原始照片 | 自然、无滤镜感 |

### **10.2 光影与氛围 (Lighting & Atmosphere)**

| 英文提示词 | 中文含义 | 作用 |
| :---- | :---- | :---- |
| **Natural light** | 自然光 | 柔和、真实 |
| **Cinematic lighting** | 电影布光 | 戏剧性、叙事感 |
| **Rembrandt lighting** | 伦勃朗光 | 经典人像、三角光斑 |
| **Volumetric lighting** | 体积光 | 增加空间介质感 |
| **Backlight / Rim light** | 逆光/轮廓光 | 勾勒边缘，分离背景 |
| **Softbox lighting** | 柔光箱 | 影棚柔光，质感细腻 |
| **Moody lighting** | 情绪照明 | 暗调、神秘 |
| **Bioluminescence** | 生物发光 | 奇幻、发光植物/生物 |

### **10.3 摄影器材与胶片 (Gear & Film)**

| 英文提示词 | 中文含义 | 作用 |
| :---- | :---- | :---- |
| **Shot on 35mm** | 35mm胶片拍摄 | 经典电影感 |
| **Kodak Portra 400** | 柯达Portra 400 | 绝佳肤色，暖调 |
| **Fujifilm** | 富士胶片 | 绿色/蓝色表现好，日系 |
| **Polaroid** | 宝丽来 | 复古、瞬时成像感 |
| **Leica M6** | 徕卡M6 | 德味、高对比、锐利 |
| **Wide angle lens** | 广角镜头 | 宏大、透视夸张 |
| **Telephoto lens** | 长焦镜头 | 压缩空间、虚化背景 |
| **Bokeh** | 散景 | 背景唯美虚化 |

### **10.4 人像细节 (Portrait Details)**

| 英文提示词 | 中文含义 | 作用 |
| :---- | :---- | :---- |
| **Visible pores** | 可见毛孔 | 拒绝磨皮感 |
| **Skin texture** | 皮肤纹理 | 增加真实度 |
| **Subsurface scattering** | 次表面散射 | 皮肤通透感 |
| **Freckles** | 雀斑 | 增加生动性 |
| **Imperfections** | 瑕疵 | 增加由于不完美而产生的真实感 |
| **Catchlight** | 眼神光 | 眼睛有神 |
| **Peach fuzz** | 面部绒毛 | 逆光下的极致细节 |
| **Flyaways** | 飞发/碎发 | 发丝真实感 |

### **10.5 构图词汇 (Composition)**

| 英文提示词 | 中文含义 | 作用 |
| :---- | :---- | :---- |
| **Rule of thirds** | 三分法 | 均衡构图 |
| **Symmetrical** | 对称 | 庄重、秩序 |
| **Low angle** | 低角度 | 仰视、宏伟 |
| **High angle** | 高角度 | 俯视、全知 |
| **Close-up** | 特写 | 强调细节 |
| **Wide shot** | 广角/全景 | 强调环境 |
| **Depth of field** | 景深 | 强调前后空间关系 |

## **结语**

掌握AI提示词，本质上是掌握**摄影学、光学与美术史**的通识。当你输入"Cinestill 800T"时，你调用的不只是一个滤镜，而是人类摄影史上关于夜景、霓虹与胶片颗粒的所有集体记忆。希望这份法典能成为您在潜空间探索光影的罗盘，助您生成超越现实的极致影像。

#### **引用的著作**

1. Quality Boosters: Elevate AI Image Generation with Enhanced Detail \- Learn Prompting, 访问时间为 二月 3, 2026， [https://learnprompting.org/docs/image\_prompting/quality\_boosters](https://learnprompting.org/docs/image_prompting/quality_boosters)  
2. ChatGPT Formula for Quick AI Image Prompts : r/StableDiffusion \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/StableDiffusion/comments/17bk9p0/chatgpt\_formula\_for\_quick\_ai\_image\_prompts/](https://www.reddit.com/r/StableDiffusion/comments/17bk9p0/chatgpt_formula_for_quick_ai_image_prompts/)  
3. 50 Midjourney Prompts and Prompt Formulas for 2025 (Beginner to ..., 访问时间为 二月 3, 2026， [https://skywork.ai/blog/midjourney-prompts-formulas-2025/](https://skywork.ai/blog/midjourney-prompts-formulas-2025/)  
4. Prompt Basics \- MidJourney Docs, 访问时间为 二月 3, 2026， [https://docs.midjourney.com/hc/en-us/articles/32023408776205-Prompt-Basics](https://docs.midjourney.com/hc/en-us/articles/32023408776205-Prompt-Basics)  
5. The Best 25 Stable Diffusion Prompts for Eye \- OpenArt, 访问时间为 二月 3, 2026， [https://openart.ai/blog/post/stable-diffusion-prompts-for-eye](https://openart.ai/blog/post/stable-diffusion-prompts-for-eye)  
6. 20+ Unique Prompts for AI Image Generation \- Stockimg AI, 访问时间为 二月 3, 2026， [https://stockimg.ai/blog/design-and-creativity/20-unique-prompts-for-ai-image-generation](https://stockimg.ai/blog/design-and-creativity/20-unique-prompts-for-ai-image-generation)  
7. Do "masterpiece" "best quality" really matter? : r/StableDiffusion \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/StableDiffusion/comments/13eq9ap/do\_masterpiece\_best\_quality\_really\_matter/](https://www.reddit.com/r/StableDiffusion/comments/13eq9ap/do_masterpiece_best_quality_really_matter/)  
8. Using Subsurface Scattering in Unreal Engine Materials \- Epic Games Developers, 访问时间为 二月 3, 2026， [https://dev.epicgames.com/documentation/en-us/unreal-engine/using-subsurface-scattering-in-unreal-engine-materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/using-subsurface-scattering-in-unreal-engine-materials)  
9. \[Twitch\] Subsurface Scattering and Ray Traced Soft Shadows Demos \- Oct. 16, 2014, 访问时间为 二月 3, 2026， [https://forums.unrealengine.com/t/twitch-subsurface-scattering-and-ray-traced-soft-shadows-demos-oct-16-2014/13116](https://forums.unrealengine.com/t/twitch-subsurface-scattering-and-ray-traced-soft-shadows-demos-oct-16-2014/13116)  
10. Subsurface Scattering \- Help | OTOY, 访问时间为 二月 3, 2026， [https://help.otoy.com/hc/en-us/articles/37194799796635-Subsurface-Scattering](https://help.otoy.com/hc/en-us/articles/37194799796635-Subsurface-Scattering)  
11. Silverwing Training: Subsurface Scattering in Octane \- YouTube, 访问时间为 二月 3, 2026， [https://www.youtube.com/watch?v=a7NEHVdLJjg](https://www.youtube.com/watch?v=a7NEHVdLJjg)  
12. TOP 10 Google Gemini AI Photo Editing Prompts | Skylum Blog, 访问时间为 二月 3, 2026， [https://skylum.com/blog/gemini-ai-photo-editing-prompts](https://skylum.com/blog/gemini-ai-photo-editing-prompts)  
13. The Complete Guide to Crafting Professional Midjourney Photography Prompts | by Hui Zhu, 访问时间为 二月 3, 2026， [https://medium.com/@robertgo8/the-complete-guide-to-crafting-professional-midjourney-photography-prompts-e16c413c07d5](https://medium.com/@robertgo8/the-complete-guide-to-crafting-professional-midjourney-photography-prompts-e16c413c07d5)  
14. 5 Common Key Light Patterns Every Portrait Photographer Should Know \- SLR Lounge, 访问时间为 二月 3, 2026， [https://www.slrlounge.com/common-key-light-patterns/](https://www.slrlounge.com/common-key-light-patterns/)  
15. Chromatic Aberration | Post Processing | 3.5.1 \- Unity \- Manual, 访问时间为 二月 3, 2026， [https://docs.unity3d.com/Packages/com.unity.postprocessing@3.5/manual/Chromatic-Aberration.html](https://docs.unity3d.com/Packages/com.unity.postprocessing@3.5/manual/Chromatic-Aberration.html)  
16. Camera and Lenses / Settings | Midjourney Compendium, 访问时间为 二月 3, 2026， [https://www.midjourneycompendium.ch/settings/camera-and-lenses](https://www.midjourneycompendium.ch/settings/camera-and-lenses)  
17. AI Portrait Prompts for Realistic Photos (Flux 2, Nano Banana Pro ..., 访问时间为 二月 3, 2026， [https://fiddl.art/blog/en/ai-portrait-prompts](https://fiddl.art/blog/en/ai-portrait-prompts)  
18. Best Midjourney Prompts: an epic list of 644 crazy text to image ideas \- Creativindie, 访问时间为 二月 3, 2026， [https://www.creativindie.com/best-midjourney-prompts-an-epic-list-of-crazy-text-to-image-ideas/](https://www.creativindie.com/best-midjourney-prompts-an-epic-list-of-crazy-text-to-image-ideas/)  
19. Midjourney Inspirational Prompts vol 5 \- YouTube, 访问时间为 二月 3, 2026， [https://www.youtube.com/watch?v=9HEDXzZTOck](https://www.youtube.com/watch?v=9HEDXzZTOck)  
20. Comparing Camera Settings in Prompts : r/midjourney \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/midjourney/comments/1ffdj3d/comparing\_camera\_settings\_in\_prompts/](https://www.reddit.com/r/midjourney/comments/1ffdj3d/comparing_camera_settings_in_prompts/)  
21. The 20 Secret Words Pro AI Image Artists Are Using — And You ..., 访问时间为 二月 3, 2026， [https://medium.com/@mericreativAI/the-20-secret-words-pro-ai-image-artists-are-using-and-you-should-too-eb09feabeb6f](https://medium.com/@mericreativAI/the-20-secret-words-pro-ai-image-artists-are-using-and-you-should-too-eb09feabeb6f)  
22. Lighting in AI Images: techniques for cinematic results \- Human Academy \- The studio that teaches you about AI with the most updated tools in the market, 访问时间为 二月 3, 2026， [https://www.humanacademy.ai/en/blog/lighting-images-ai](https://www.humanacademy.ai/en/blog/lighting-images-ai)  
23. AI Prompt | PDF | Sky | Shadow \- Scribd, 访问时间为 二月 3, 2026， [https://www.scribd.com/document/904879955/AI-Prompt](https://www.scribd.com/document/904879955/AI-Prompt)  
24. 24 Portrait Character Lighting Setups |Photography |Cinematography | by Sukesh G Tambi, 访问时间为 二月 3, 2026， [https://medium.com/@sukeshgtambi/24-portrait-character-lighting-setups-photography-cinematography-bdd7a967407c](https://medium.com/@sukeshgtambi/24-portrait-character-lighting-setups-photography-cinematography-bdd7a967407c)  
25. 6 Portrait Lighting Patterns Every Photographer Should Know \- Digital Photography School, 访问时间为 二月 3, 2026， [https://digital-photography-school.com/6-portrait-lighting-patterns-every-photographer-should-know/](https://digital-photography-school.com/6-portrait-lighting-patterns-every-photographer-should-know/)  
26. Describing angles/perspective/etc, if you have any other examples, please, share it here\! : r/StableDiffusion \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/StableDiffusion/comments/y46k9t/describing\_anglesperspectiveetc\_if\_you\_have\_any/](https://www.reddit.com/r/StableDiffusion/comments/y46k9t/describing_anglesperspectiveetc_if_you_have_any/)  
27. Glossary of Photography Lighting Terms \- iPhotography courses, 访问时间为 二月 3, 2026， [https://www.iphotography.com/blog/glossary-of-photography-lighting-terms/](https://www.iphotography.com/blog/glossary-of-photography-lighting-terms/)  
28. 10 Prompt Phrases That Transform Your AI Image Lighting | by Meri CreativAI | Jan, 2026 | Medium, 访问时间为 二月 3, 2026， [https://medium.com/@mericreativAI/10-prompt-phrases-that-transform-your-ai-image-lighting-4a2ca76e9f6a](https://medium.com/@mericreativAI/10-prompt-phrases-that-transform-your-ai-image-lighting-4a2ca76e9f6a)  
29. Best prompts for original face \- OpenAI Developer Community, 访问时间为 二月 3, 2026， [https://community.openai.com/t/best-prompts-for-original-face/1225266](https://community.openai.com/t/best-prompts-for-original-face/1225266)  
30. Negative Prompts for Perfect AI Image Generation | Medium, 访问时间为 二月 3, 2026， [https://medium.com/@johnnythedeveloper/negative-prompts-for-perfect-ai-image-generation-4b45744363c7](https://medium.com/@johnnythedeveloper/negative-prompts-for-perfect-ai-image-generation-4b45744363c7)  
31. 200+ Best Stable Diffusion Negative Prompts for Text to Video \[2025 Updated\] \- Aitubo, 访问时间为 二月 3, 2026， [https://aitubo.ai/blog/post/stable-diffusion-negative-prompts/](https://aitubo.ai/blog/post/stable-diffusion-negative-prompts/)  
32. Hairstyle Prompts | PDF \- Scribd, 访问时间为 二月 3, 2026， [https://www.scribd.com/document/980089265/Hairstyle-Prompts](https://www.scribd.com/document/980089265/Hairstyle-Prompts)  
33. 36 Midjourney Prompts For Hairstyles \- Robot The Robot, 访问时间为 二月 3, 2026， [https://www.robotfilmschool.com/midjourney-prompts-for-hairstyles/](https://www.robotfilmschool.com/midjourney-prompts-for-hairstyles/)  
34. Master List of Facial Expressions \- Bryn Donovan, 访问时间为 二月 3, 2026， [https://www.bryndonovan.com/2015/04/05/master-list-of-facial-expressions/](https://www.bryndonovan.com/2015/04/05/master-list-of-facial-expressions/)  
35. The Best 25 Stable Diffusion Prompts for Facial Expression \- OpenArt, 访问时间为 二月 3, 2026， [https://openart.ai/blog/post/stable-diffusion-prompts-for-facial-expression](https://openart.ai/blog/post/stable-diffusion-prompts-for-facial-expression)  
36. Midjourney Silk-fabric Image Prompts \- PromptDen, 访问时间为 二月 3, 2026， [https://promptden.com/inspiration/midjourney/silk-fabric+all](https://promptden.com/inspiration/midjourney/silk-fabric+all)  
37. The 70+ Types of Fabrics and Textiles for Clothing: A Glossary \- Myles Price, 访问时间为 二月 3, 2026， [https://mylesprice.com/blogs/guide/types-of-fabrics-and-textiles-for-clothing](https://mylesprice.com/blogs/guide/types-of-fabrics-and-textiles-for-clothing)  
38. Image Generation Prompt Structure for OpenAI's Sora \- Cyber Raiden, 访问时间为 二月 3, 2026， [https://cyberraiden.wordpress.com/2025/08/10/image-generation-prompt-structure-for-openais-sora/](https://cyberraiden.wordpress.com/2025/08/10/image-generation-prompt-structure-for-openais-sora/)  
39. 访问时间为 二月 3, 2026， [https://www.aiarty.com/midjourney-prompts/midjourney-camera-angles.htm](https://www.aiarty.com/midjourney-prompts/midjourney-camera-angles.htm)  
40. Shot Types: Enhance AI Image Generation with Camera Angles \- Learn Prompting, 访问时间为 二月 3, 2026， [https://learnprompting.org/docs/image\_prompting/shot\_type](https://learnprompting.org/docs/image_prompting/shot_type)  
41. 15 Midjourney prompts for fashion photography | by Zack MacTavish | Bootcamp \- Medium, 访问时间为 二月 3, 2026， [https://medium.com/design-bootcamp/15-midjourney-prompts-for-fashion-photography-5fc499cdce9b](https://medium.com/design-bootcamp/15-midjourney-prompts-for-fashion-photography-5fc499cdce9b)  
42. Teal & Orange Color Grading in Under 2 Minutes \- YouTube, 访问时间为 二月 3, 2026， [https://www.youtube.com/watch?v=XjFLmf\_TYlw](https://www.youtube.com/watch?v=XjFLmf_TYlw)  
43. Teal & Orange Color Grading for a Cinematic Look | FCP Tutorial \- YouTube, 访问时间为 二月 3, 2026， [https://www.youtube.com/watch?v=bfe15QsvCPo](https://www.youtube.com/watch?v=bfe15QsvCPo)  
44. Some heavier post processing again, this time with Orange & "Teal" Color Grading \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/postprocessing/comments/z1y9ly/some\_heavier\_post\_processing\_again\_this\_time\_with/](https://www.reddit.com/r/postprocessing/comments/z1y9ly/some_heavier_post_processing_again_this_time_with/)  
45. Parameter List \- MidJourney Docs, 访问时间为 二月 3, 2026， [https://docs.midjourney.com/hc/en-us/articles/32859204029709-Parameter-List](https://docs.midjourney.com/hc/en-us/articles/32859204029709-Parameter-List)  
46. The Ultimate Midjourney v7 Cheat Sheet: Parameters, Styles and Tips | by Alijee Writes, 访问时间为 二月 3, 2026， [https://medium.com/@alijeebutt99/the-ultimate-midjourney-v7-cheat-sheet-parameters-styles-and-tips-a9a4e4c99583](https://medium.com/@alijeebutt99/the-ultimate-midjourney-v7-cheat-sheet-parameters-styles-and-tips-a9a4e4c99583)  
47. Style Reference \- MidJourney Docs, 访问时间为 二月 3, 2026， [https://docs.midjourney.com/hc/en-us/articles/32180011136653-Style-Reference](https://docs.midjourney.com/hc/en-us/articles/32180011136653-Style-Reference)  
48. Character Reference \- MidJourney Docs, 访问时间为 二月 3, 2026， [https://docs.midjourney.com/hc/en-us/articles/32162917505293-Character-Reference](https://docs.midjourney.com/hc/en-us/articles/32162917505293-Character-Reference)  
49. Updated List of Style Libraries, Prompt Guides and Resources : r/midjourney \- Reddit, 访问时间为 二月 3, 2026， [https://www.reddit.com/r/midjourney/comments/1agstz4/updated\_list\_of\_style\_libraries\_prompt\_guides\_and/](https://www.reddit.com/r/midjourney/comments/1agstz4/updated_list_of_style_libraries_prompt_guides_and/)  
50. List of Key Words-Negative Prompt \- AI Visualizer \- Vectorworks Forum, 访问时间为 二月 3, 2026， [https://forum.vectorworks.net/index.php?/topic/116408-list-of-key-words-negative-prompt/](https://forum.vectorworks.net/index.php?/topic/116408-list-of-key-words-negative-prompt/)
