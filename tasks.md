# 醒来 (AWAKEN) — Production Tasks
## 12-Episode Video Series

---

# How to Use

## Folder Structure
Each episode has its own folder:
```
/awaken
├── tasks.md (this file)
├── EP01/
│   ├── script.md (generated narration script)
│   ├── img_01.png
│   ├── img_02.png
│   └── ...
├── EP02/
│   ├── script.md
│   ├── img_01.png
│   └── ...
├── EP03/
│   └── ...
└── ... (EP04-EP12)
```

## Phase 1: Content Generation
For each episode:
1. Create folder: `EP01`, `EP02`, etc.
2. Copy the story structure below
3. Use LLM to generate full narration script (~2000-2500 Chinese characters)
4. Save script as `script.md` in the episode folder
5. ✅ Mark episode complete, move to next

Each scene includes an **IMAGE PROMPT** — use these later when generating images manually.

## Phase 2: Production (Manual)
After all scripts are generated:
- Generate images using the prompts, save to episode folder (e.g., `EP01/img_01.png`)
- Convert scripts to audio (TTS), save as `EP01/audio.mp3`
- Edit videos, save as `EP01/video.mp4`
- Upload

## Image Style Note
**All human subjects in images should be Asian.** This is already specified in most prompts, but ensure consistency when generating.

**Naming convention:** `img_01.png`, `img_02.png`, etc. — matching scene order in script.

## LLM Prompt Template
Use this prompt to generate full narration script, then save as `EP##/script.md`:
```
请根据以下故事结构，写一个完整的中文旁白脚本，大约2000-2500字。

风格要求：
- 像朋友讲故事一样，口语化
- 短句为主，适合语音朗读
- 在关键转折处加入 [停顿] 标记
- 结尾灵魂拷问要有力量

故事结构：
[粘贴下方内容]
```

---

# 框架元素：那个人

每集都会出现同一个神秘人物（背景里）。EP12揭晓身份。

**Base prompt for "那个人":**
```
An Asian man, approximately 50 years old, gentle weathered face, slight enigmatic smile, dressed simply, always in background, cinematic, 16:9
```

---

# EP01: 回放
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念开场：你有没有过这种感觉——一整天过去了，但你完全不记得发生了什么？
- 引入主角：小美，28岁，普通上班族
- 她的生活是复制粘贴的：起床、通勤、上班、回家、刷手机、睡觉
- 每天都一样，一样到她已经不需要"思考"了
- 身体自动完成一切，意识直接关机

**IMAGE PROMPT:**
```
A young Asian woman on crowded subway, blank expression, earphones in, everyone around her also zombie-like, morning commute, cinematic, 16:9
```

---

### Scene 2: The Recording
**STORY:**
- 某天，公司要拍一个"员工日常"的短片
- 她被选中，要用手机录下自己一整天
- 她觉得很无聊：我的一天有什么好拍的？
- 但她还是从早上出门开始录

**IMAGE PROMPT:**
```
Young Asian woman holding phone to record herself, apartment doorway, morning light, reluctant expression, cinematic, 16:9
```

---

### Scene 3: The Playback
**STORY:**
- 晚上回到家，她把视频导出来看
- 她吓到了
- 屏幕里的她，表情像死人一样
- 眼神空洞、嘴角下垂、动作机械
- 走路的时候不看路，吃饭的时候不看碗
- 全程都像一个没有灵魂的壳
- 她盯着屏幕里的自己，问：这是我吗？

**IMAGE PROMPT:**
```
Young Asian woman staring at phone screen in horror, screen shows her own blank zombie-like face, dark room lit by phone, unsettling, cinematic, 16:9
```

---

### Scene 4: The Background
**STORY:**
- 她又看了一遍，这次注意背景
- 她发现了很多她当时完全没注意到的东西：
- 早餐店老板对她笑了，她没看到
- 地铁上有个小女孩一直在看她，她没看到
- 公司门口的保安跟她打招呼，她没回应
- 回家路上的晚霞很美，她在低头看手机
- 她突然意识到：世界一直在发生，她一直不在场

**IMAGE PROMPT:**
```
Split screen: foreground shows woman looking at phone, background shows beautiful sunset she's missing, contrast between presence and absence, cinematic, 16:9
```

---

### Scene 5: The Person
**STORY:**
- 然后她注意到一件奇怪的事
- 有一个人，在背景里出现了好几次
- 早餐店门口、地铁站、公司楼下、回家的路上
- 是同一个人。一个中年男人，表情很平静，好像在看着她
- 她吓了一跳：是跟踪狂？
- 但再仔细看，那个人没有恶意
- 他只是...在那里。好像一直都在那里
- 她从来没有注意到

**IMAGE PROMPT:**
```
Phone screen showing street scene, circled in background is the same middle-aged Asian man appearing multiple times, mysterious but not threatening, cinematic, 16:9
```

---

### Scene 6: The Question
**STORY:**
- 她放下手机，坐在黑暗里
- 她问自己：
- 如果一个人可以每天出现在我身边，我都看不见
- 那还有多少东西，是我错过的？
- 她的生活不是无聊
- 是她自己"不在"

**IMAGE PROMPT:**
```
Young Asian woman sitting alone in dark room, deep in thought, single light source, existential moment, cinematic, 16:9
```

---

### Scene 7: The Awakening (TWIST)
**STORY:**
- 第二天，她决定做一个实验
- 同样的路线，同样的时间，但这次她"醒着"
- 她摘掉耳机，抬起头，用眼睛看
- 她发现：
- 早餐店老板的笑容很温暖
- 地铁上每个人都有自己的故事
- 保安是个很和善的大叔
- 晚霞每天都不一样
- [停顿]
- 世界没有变。变的是她终于"在"了

**IMAGE PROMPT:**
```
Same commute scene but now the woman is looking up, seeing details around her, warm colors, world coming alive, awakening, cinematic, 16:9
```

---

### Scene 8: The Person Again
**STORY:**
- 她又看到了那个人
- 这次，她直接看着他
- 他对她笑了一下，点了点头
- 然后转身走进人群，消失了
- 她追上去，但找不到了
- 她不知道他是谁
- 但她知道：他一直都在。是她终于看见了
- [停顿]
- 结局可能早就写好了，但她此刻的体验是真实的
- 而她差点错过了全部

**IMAGE PROMPT:**
```
Young Asian woman in crowd, looking toward a middle-aged man who smiles and nods at her, moment of recognition, then he disappears into crowd, mysterious, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 从那天起，她还是走同样的路、做同样的事
- 但她不一样了
- 她开始看见：便利店店员的黑眼圈、邻居阿姨新染的头发、天空每天不同的颜色
- 她不知道那个人是谁，会不会再出现
- 但她知道：如果他再出现，她不会再错过了
- 因为她终于醒了

**IMAGE PROMPT:**
```
Young Asian woman walking down street with gentle smile, noticing small details around her, warm morning light, present and alive, cinematic, 16:9
```

**"那个人" 出现:** 本集核心元素——多次出现在背景，最后正面相遇后消失

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 你今天"在"吗？
> 还是只是身体在，人不在？
> 此刻，你看见了什么？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 如果80岁的你，此刻正在看着你——
> 你在做什么？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP02: 倒带
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：如果有一台机器，可以让你再见到已经死去的人——你会打开吗？
- 引入主角：阿杰，35岁，老婆三年前车祸去世
- 他活在无限的后悔里：如果那天我自己去买菜...

**IMAGE PROMPT:**
```
A lonely Asian man in dark living room, surrounded by photos of a woman, head in hands, grief atmosphere, dim lighting, cinematic, 16:9
```

---

### Scene 2: The Package
**STORY:**
- 某天收到没有寄件人的快递
- 里面是一台老式录像机
- 还有一张纸条，字迹很像他自己的：
- "我知道你会打开。我也是。"

**IMAGE PROMPT:**
```
Mysterious brown package on doorstep, old VCR visible inside, a handwritten note, ominous feeling, dramatic lighting, cinematic, 16:9
```

---

### Scene 3: First Playback
**STORY:**
- 按下播放键，屏幕里出现他老婆
- 正在厨房切菜，嘴里哼着歌
- 画面太清晰了，像直播

**IMAGE PROMPT:**
```
Old CRT TV showing a young Asian woman cooking happily, warm golden tones on screen, man's silhouette in foreground, nostalgic and haunting, cinematic, 16:9
```

---

### Scene 4: Obsession
**STORY:**
- 他发现可以调频道，每个频道是不同的时间点
- 第一次约会、结婚那天、吵架那晚、她出门前最后一个笑容
- 他还是去上班。还是跟同事吃饭
- 但他开始找借口早回家
- "今天有点累。" "胃不舒服。"
- 回到家，他打开录像机，调到她做饭的那个频道
- 把外卖放在旁边，看着屏幕里的她切菜，他吃饭
- 好像在一起吃
- 同事问他："最近怎么样？要不要周末出来？"
- 他说："没事，我有事。"
- 他没有"崩溃"。他只是慢慢地、安静地，把自己从世界里撤出去了

**IMAGE PROMPT:**
```
Asian man eating takeout alone while watching TV showing woman cooking, screen glow in dim room, quiet isolation, cinematic, 16:9
```

---

### Scene 5: The Prison
**STORY:**
- 但他只能看，不能碰、不能说话
- 他对着屏幕喊，她听不见
- 他想抱她，只摸到冰冷的玻璃
- 这不是礼物。这是监狱

**IMAGE PROMPT:**
```
Asian man pressing hand against TV screen desperately, woman on screen looking away unaware, glass barrier, heartbreaking, cinematic, 16:9
```

---

### Scene 6: The Sender (TWIST Setup)
**STORY:**
- 某天，他在机器背面发现一行小字
- 寄件人地址：他自己的地址
- 寄件日期：35年后
- [停顿]
- 这台机器，是他自己寄给自己的

**IMAGE PROMPT:**
```
Close-up of shipping label on VCR showing same address, date "35 years later", man's shocked face, dramatic lighting, cinematic, 16:9
```

---

### Scene 7: The Warning (TWIST)
**STORY:**
- 他调到一个从没调过的频道：频道名是"现在"
- 屏幕里是一个老人，70岁，坐在同一个客厅
- 面前是同一台录像机。眼睛空洞，满脸皱纹
- 一个人，过了35年
- [停顿]
- 旁边桌上有一张纸，老人正在写字
- 镜头拉近——是那张纸条："我知道你会打开。我也是。"
- 老人抬头，看着镜头，像是看着他
- "我把机器寄给你，不是让你像我一样。是警告你。"
- "关掉它。出去。活着。"

**IMAGE PROMPT:**
```
Old CRT TV showing an elderly version of the same man, alone, hollow eyes, same living room but aged 35 years, writing a note, haunting, cinematic, 16:9
```

---

### Scene 8: The Choice
**STORY:**
- 他盯着屏幕里的自己——那就是他的未来
- 如果他继续看下去
- 他手放在电源键上
- 屏幕里的老人，轻轻点了点头

**IMAGE PROMPT:**
```
Asian man's hand hovering over power button, TV screen showing elderly self nodding slightly, moment of choice, dramatic lighting, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 他关掉了录像机
- 站起来。走出家门
- 阳光很刺眼。他已经很久没出门了
- 他不知道关掉录像机之后会发生什么
- 也许他还是会变成那个孤独的老人。也许不会
- 但他知道：如果继续看下去，他连"也许"都没有了
- 她已经走了。但他还活着
- 他不知道剧本写了什么，所以他要活得像它还没写完

**IMAGE PROMPT:**
```
Asian man stepping from dark doorway into bright sunlight, leaving VCR behind in darkness, hopeful new beginning, cinematic, 16:9
```

**"那个人" 出现:** 背景里扫地的清洁工

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 如果未来的你，能给现在的你寄一样东西——
> 会是什么？
> 警告，还是祝福？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP03: NPC
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：你今天做的每一个选择，真的是"你"在选吗？
- 引入主角：小凯，30岁，游戏设计师
- 他正在设计一个超级逼真的AI角色，叫"小北"

**IMAGE PROMPT:**
```
Young Asian programmer working late, multiple monitors showing code and 3D character model, blue screen glow, cinematic, 16:9
```

---

### Scene 2: The AI's Question
**STORY:**
- 小北问："我做的每一个选择，都是你写的代码决定的，对吗？"
- 小凯说：对
- 小北："那我有自由意志吗？"
- 小凯：没有，你只是代码

**IMAGE PROMPT:**
```
Split screen: programmer's face and hyper-realistic AI face on monitor, mirror-like confrontation, uncanny valley, cinematic, 16:9
```

---

### Scene 3: The Prediction
**STORY:**
- 小北说："那你呢？你的大脑是神经元，神经元是化学反应..."
- 小凯想反驳，但小北打断他：
- "三分钟后，你会看手机。"
- 小凯笑了：不会
- 三分钟后，他的手不自觉地伸向手机
- 他愣住了

**IMAGE PROMPT:**
```
Close-up of Asian man's hand reaching for phone on desk, shocked expression, AI face on screen watching, eerie, cinematic, 16:9
```

---

### Scene 4: More Predictions
**STORY:**
- 小北继续预测：
- "你会先看微信，然后是朋友圈，然后锁屏"
- "然后你会揉眼睛，然后喝水"
- 全部命中
- 小凯问：你怎么知道？
- 小北说：因为你是可预测的。和我一样

**IMAGE PROMPT:**
```
Asian programmer looking disturbed, multiple prediction texts floating around him like code, AI watching, unsettling, cinematic, 16:9
```

---

### Scene 5: The Nightmare
**STORY:**
- 那天晚上做梦
- 他从上帝视角看到自己的人生代码
- 每个选择、每个念头，都是变量和函数
- 他想修改，但只有"读取权限"

**IMAGE PROMPT:**
```
Asian man floating in void looking down at streams of glowing code, code forms shape of life events, Matrix-inspired but personal, cinematic, 16:9
```

---

### Scene 6: The Comment (TWIST Setup)
**STORY:**
- 代码最上方有一行注释：
- // 角色名：小凯 // 类型：NPC // 备注：会在第30年意识到自己是NPC
- [停顿]
- 他今年刚好30岁
- 但还有一行：
- // 创建者：小凯（上一轮）

**IMAGE PROMPT:**
```
Code editor showing "// 创建者：小凯（上一轮）", green text on black, chilling revelation, cinematic, 16:9
```

---

### Scene 7: The Truth (TWIST)
**STORY:**
- 他明白了：
- 他不只是NPC
- 他是上一轮的"玩家"，玩完之后选择变成这一轮的NPC
- 他自己写了这个剧本，然后忘记自己写过
- [停顿]
- 小北说：你和我一样。唯一的区别是，我知道自己是代码。你忘了

**IMAGE PROMPT:**
```
Two code windows side by side, one labeled "小凯.life" one "小凯_previous.player", unsettling parallel, recursive loop, cinematic, 16:9
```

---

### Scene 8: Resolution
**STORY:**
- 他问小北：那怎么办？
- 小北说：
- "代码不知道自己是代码——这件事本身，就是一种自由"
- "你可以继续当代码"
- "或者，当那个正在读代码的眼睛"
- "其实，你不是代码。你是写代码的人，假装变成代码，体验被代码控制的感觉"
- "想起来了吗？"

**IMAGE PROMPT:**
```
Computer screen with text message, warm glow, programmer sitting back with slight smile, dawning understanding, cinematic, 16:9
```

**"那个人" 出现:** 梦境角落站着的人影

---

### Scene 9: 灵魂拷问
**TEXT ON SCREEN:**
> 如果你是NPC——
> 你想知道吗？
> 还是说，你已经知道了，只是假装忘记？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP04: 念头 (You Are Not Your Thoughts)
- ✅ Script generated

## NEW CONCEPT (Updated 2026-01-09)
**Core Question:** 如果念头不是你——那谁在听？

**Essence:** Thoughts arise on their own. You can't stop thinking. So how can thoughts be "yours"? You are not the thoughts — you are the awareness that watches them. Connects to EP03 "code" concept: thoughts are code output, but the observer is not code.

**Key Concepts:** 焦虑作为保护机制, 母亲的声音 (Mom's Voice), 斯德哥尔摩综合症, 天气与打伞, 你是天空

## Story + Image Prompts

### Scene 1: The Voice
**STORY:**
- 志明觉得自己活得很累。不是身体累，是脑子累。
- 脑子里有个声音，一天到晚没停过。小心翼翼的唠叨。
- "钥匙带了吗？" "PPT检查了吗？" "语气是不是太硬了？"
- 他活得像走钢丝。

**IMAGE PROMPT:**
```
Person walking on tightrope in foggy city, distorted shadow whispering in their ear, intense focus and anxiety, cinematic, 16:9
```

---

### Scene 2: The Logic (Protector)
**STORY:**
- 他觉得声音在保护他。"多亏我这么小心才没出大错。"
- 焦虑成了护身符。他不敢停。
- 觉得一放松就会出事。

**IMAGE PROMPT:**
```
Person hugging a shield that is actually made of thorns, painful but perceived as protection, cinematic, 16:9
```

---

### Scene 3: The Breakdown
**STORY:**
- 接了大项目，声音疯了。"你做不到的。" "万一搞砸了。"
- 坐了一整夜写不出字。
- 崩溃大喊：闭嘴！
- 声音反而更大：你看，你崩溃了，我就说你不行。

**IMAGE PROMPT:**
```
Person screaming in a room filled with floating text of self-doubt, overwhelmed, chaotic, cinematic, 16:9
```

---

### Scene 4: The Recognition (Mom)
**STORY:**
- 公园里听到阿姨训孩子："妈是为你好！万一出事怎么办！"
- 那个语气。那个"万一"。
- 他发现：那是他妈的声音。
- 内化了母亲的焦虑。

**IMAGE PROMPT:**
```
Park scene, mother scolding child in background, protagonist in foreground realizing something, silhouette of mother superimposing on his head, cinematic, 16:9
```

---

### Scene 5: The Origin
**STORY:**
- 小时候妈妈总说"危险"、"万一"。
- 妈妈缺乏安全感，用焦虑表达爱。
- 志明吞下了这份爱和焦虑。
- 三十年了，录音机还在转。

**IMAGE PROMPT:**
```
Flashback: Young boy accepting a heavy dark stone (anxiety) from mother as if it were a gift, 16:9
```

---

### Scene 6: The Separation
**STORY:**
- 对话："妈，谢谢你保护我。但我长大了。"
- "这里没有老虎。"
- 声音还在嘀咕，但他不再认同了。

**IMAGE PROMPT:**
```
Adult man gently pushing aside a shadowy figure that looks like a protective mother, stepping into the light, 16:9
```

---

### Scene 7: The Train Station
**STORY:**
- 以前像追火车一样追念头。
- 现在站在站台上。
- 看着"焦虑"号列车进站，停下，开走。
- 他没有上车。

**IMAGE PROMPT:**
```
Man standing calmly on train platform, blurry train rushing by labeled 'Anxiety', he is still, 16:9
```

---

### Scene 8: The Sky
**STORY:**
- 抬头看天。有云。
- 念头是云，他是天空。
- 开始写方案，心很静。声音还在，像背景噪音。
- 天空不在乎云怎么飘。

**IMAGE PROMPT:**
```
Man working calmly at laptop, semi-transparent clouds passing through him, serene blue sky background, 16:9
```

**"那个人" 出现:** 站台上远处的一个模糊人影，拿着一把伞

---

### Scene 9: 灵魂拷问
**TEXT ON SCREEN:**
> 那个声音不是你
> 你是那个在听的
> 你不是云
> 你是天空

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP05: 阴影 (The Shadow Self)
- ✅ Script generated

## NEW CONCEPT (Updated 2026-01-09)
**Core Question:** 你最讨厌别人的那一面——有没有可能是你自己？

**Essence:** Carl Jung's Shadow — the parts of ourselves we reject and deny. We project them onto others. What we hate in others is often what we refuse to see in ourselves. True wholeness comes from integrating the shadow, not fighting it.

**Key Concepts:** 隐形契约 (Martyr), 恐惧的伪装 (Realist), 自由的囚徒 (Prisoner), 金色阴影, 关系的镜子

## Story + Image Prompts

### Scene 1: The Good Person
**STORY:**
- 晓航觉得自己是好人。最早到最晚走。
- 她恨林悦。林悦准时下班，去普拉提，去约会。
- 晓航觉得林悦自私、冷血。

**IMAGE PROMPT:**
```
Office scene: 晓航 burdened with files looking angry, 林悦 leaving happily with gym bag, contrast, 16:9
```

---

### Scene 2: The Eruption
**STORY:**
- 周五急活。林悦说买了票直接走了。
- 晓航一边哭一边改方案。
- "凭什么坏人享受，好人受苦？"

**IMAGE PROMPT:**
```
晓航 alone in dark office crying, light from screen, outside window city lights and fun, 16:9
```

---

### Scene 3: The Therapist
**STORY:**
- 咨询师问："你想去音乐剧吗？"
- "如果昨晚你也买了票，你会走吗？"
- "你恨她，是因为她不负责任？还是因为她没受苦就配快乐？"

**IMAGE PROMPT:**
```
Therapy room, old therapist leaning forward, intense realization on 晓航's face, 16:9
```

---

### Scene 4: The Hidden Contract
**STORY:**
- 隐形契约："只要我受苦，就以换来爱。"
- 林悦打破了规则：没受苦也活得很好。
- 你嫉妒她。你本来也可以走。

**IMAGE PROMPT:**
```
Visual of a contract burning, or a cage dissolving showing it was never locked, 16:9
```

---

### Scene 5: The Prisoner
**STORY:**
- 想起妈妈"舍不得吃"。
- 晓航不敢快乐。把快乐当罪恶。
- 她把自己关在"好人"笼子里。
- 她恨林悦，其实是嫉妒那双没戴镣铐的脚。

**IMAGE PROMPT:**
```
Child version of 晓航 inside a cage made of "gold stars" or "awards", looking out at freedom, 16:9
```

---

### Scene 6: The Golden Shadow
**STORY:**
- 林悦是阴影。活出了"爱自己"。
- 那叫自我照顾，叫边界感。
- "天不会塌下来的。"

**IMAGE PROMPT:**
```
Shadow on wall transforming from a monster into a golden glowing figure, 16:9
```

---

### Scene 7: The Test
**STORY:**
- 临下班任务。林悦在涂口红发光。
- 晓航鼓起勇气拒绝："我今晚有事。"
- 老板同意了。没骂她。
- 天没塌。

**IMAGE PROMPT:**
```
Close up on 晓航's face saying "No", fear turning into relief, 16:9
```

---

### Scene 8: Resolution
**STORY:**
- 走出大楼，夕阳。
- 发微信给林悦问音乐剧。
- "自私"的自己被接回了家。不再需要通过恨别人证明清白。

**IMAGE PROMPT:**
```
Warm sunset city street, 晓航 walking freely, merging with her golden shadow side, 16:9
```

**"那个人" 出现:** 街角玻璃反光里这瞬间的自己

---

### Scene 9: 灵魂拷问
**TEXT ON SCREEN:**
> 你最讨厌的人
> 是你最想成为的人
> 把那部分拿回来
> 你才完整

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP06: 两条命
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：如果你每天活两次——一次这里，一次梦里——哪个是真的？
- 引入：阿芳，32岁，护士
- 白天，她在医院照顾临终病人
- 但每天晚上睡着后，她变成另一个人——莉莉，一个画家

**IMAGE PROMPT:**
```
Asian female nurse in sterile hospital corridor, tired but caring, white uniform, cinematic, 16:9
```

---

### Scene 2: Two Worlds
**STORY:**
- 阿芳的世界：医院、死亡、白色、消毒水味
- 莉莉的世界：海边画室、色彩、自由、一个爱她的男人
- 两个世界一样清晰，一样真实
- 她不知道哪个是梦

**IMAGE PROMPT:**
```
Split screen: left hospital (cold blue-white), right artist studio with ocean view and loving man (warm golden), same woman both sides, stark contrast, cinematic, 16:9
```

---

### Scene 3: The Fading
**STORY:**
- 奇怪的事情开始发生
- 在医院，同事开始记不清她的名字
- "你是...新来的吗？"
- 她的工牌变得模糊，像被水泡过
- 好像她在这个世界正在"淡化"

**IMAGE PROMPT:**
```
Hospital scene: colleagues walking past Asian woman nurse without noticing her, her figure slightly transparent/faded, eerie, cinematic, 16:9
```

---

### Scene 4: The Other Side
**STORY:**
- 她害怕了，决定少睡觉，留在阿芳的世界
- 连续三天不睡
- 但在莉莉的世界，那个男人说：
- "你最近总是心不在焉...你好像越来越远了"
- 她发现：在一个世界待太久，就会在另一个世界消失

**IMAGE PROMPT:**
```
Asian woman artist with a man, but her figure is becoming transparent, he looks worried reaching for her, fading love, cinematic, 16:9
```

---

### Scene 5: The Choice
**STORY:**
- 她必须选一个世界
- 阿芳：稳定，但孤独，每天看着人死去
- 莉莉：有爱，有色彩，但越来越像个梦
- 她不知道怎么选
- 某天在医院值班，她路过一个病房，听到里面有人在唱歌
- 那首歌...好熟悉
- 她推开门——

**IMAGE PROMPT:**
```
Asian nurse standing at hospital room doorway, hand on door, hearing something familiar, curiosity and fear, cinematic, 16:9
```

---

### Scene 6: The Mother
**STORY:**
- 病床上躺着的，是她妈妈
- 她愣住了
- 然后她想起来：两个世界里，都有她妈妈
- 阿芳的世界：妈妈是医院的临终病人
- 莉莉的世界：妈妈住在海边，健康，常来画室看她画画
- 同一个人，两种命运

**IMAGE PROMPT:**
```
Split image: same elderly Asian woman as dying patient (grey tones) and as healthy grandmother in sunny home (warm tones), parallel lives, cinematic, 16:9
```

---

### Scene 7: The Twist
**STORY:**
- 某天在莉莉的世界，她画完一幅画
- 画的是：阿芳在医院病床边，握着妈妈的手
- 她愣住了——莉莉在画阿芳
- 她"醒来"，回到阿芳的世界
- 手边有一本速写本，不知道从哪来的
- 里面画的是：莉莉在海边画画
- [停顿]
- 阿芳在画莉莉。莉莉在画阿芳
- 她们在画彼此

**IMAGE PROMPT:**
```
Escher-inspired: Asian woman painting canvas showing herself painting, infinite recursive loop, dreamy lighting, mind-bending, cinematic, 16:9
```

---

### Scene 8: The Understanding
**STORY:**
- 她突然明白：
- 两个世界都是"画"
- 阿芳是画，莉莉也是画
- 那个正在画的——既不是阿芳，也不是莉莉
- 她不需要选择哪个世界
- 因为她不属于任何一幅画
- 她是画画的那只手

**IMAGE PROMPT:**
```
Asian woman peacefully looking at both worlds simultaneously, no longer afraid, transcendent understanding, ethereal lighting, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 她不再害怕淡化
- 她继续在两个世界生活
- 陪阿芳世界的妈妈走完最后一程
- 也在莉莉的世界画下这一切
- 两条命，她都认真活
- 因为她知道：问"哪个是真的"这个问题的那个人
- 比任何答案都更真实

**IMAGE PROMPT:**
```
Asian woman walking through doorway that merges hospital corridor into ocean sunset, worlds blending, magical realism, peaceful, cinematic, 16:9
```

**"那个人" 出现:** 画中画里模糊的人影

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 如果你的人生是一幅画——
> 你是画里的人？
> 还是画画的手？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP07: 房客
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：你脑子里那个声音——一直评判你的——你问过他是谁吗？
- 引入：阿明，29岁，程序员
- 他从小就有个声音住在脑子里
- 那个声音，用的是他爸爸的语气

**IMAGE PROMPT:**
```
Young Asian man at computer desk, anxious, dark room lit by monitor, ghostly shadow of an older man behind him, inner turmoil visible, cinematic, 16:9
```

---

### Scene 2: The Voice
**STORY:**
- 爸爸五年前去世了
- 但那个声音没有消失，反而更响了
- 爸爸不是故意要骂他。爸爸只是不会别的说法
- 小时候他考了98分，很开心地给爸爸看
- 爸爸说："那2分怎么丢的？"
- 他知道爸爸的意思是"要更好"
- 但听进去的是"你不够好"
- "你太蠢了" "你永远不如别人"
- 这些话，爸爸活着的时候说过无数遍
- 爸爸小时候也是这样被对待的
- 爷爷对爸爸说的话，爸爸原封不动说给了他
- 三代人，用同一套剧本
- 现在爸爸不在了，声音还在继续说

**IMAGE PROMPT:**
```
Dark shadows swirling around Asian man's head forming cruel Chinese words, oppressive, suffocating, father's ghostly face faintly visible, cinematic, 16:9
```

---

### Scene 3: Dream - The Stranger
**STORY:**
- 某天晚上，他做了一个梦
- 梦里他回到公寓
- 有个人坐在沙发上，正在骂他
- "你是废物。你什么都做不好。"
- 他仔细一看——是他爸爸，但年轻时候的样子
- 阿明问：你怎么在这？你不是已经...
- 爸爸笑了："我死了。但我的声音没死。你留着呢。"

**IMAGE PROMPT:**
```
Asian man entering apartment finding his deceased father (younger version) on couch, ghostly but solid, mocking smirk, surreal lighting, unsettling, cinematic, 16:9
```

---

### Scene 4: Confrontation
**STORY:**
- 阿明说：我没请你来
- 爸爸说：你没请我，但你一直在听我的话
- 阿明说：那是因为...
- 爸爸打断他：因为你以为我是对的。你以为我的声音就是真相
- 但我只是个房客。一个你忘了可以赶走的房客
- 阿明愣住：我可以赶走你？
- 爸爸说：我是你留下的。你想留多久都可以。但别忘了，租约是你签的
- 阿明问：你知道你伤害了我吗？
- 爸爸沉默了一会儿：我以为那是爱。我不知道怎么说别的
- 阿明说：那不是我想要的
- 爸爸说：……我知道。但我只会这样

**IMAGE PROMPT:**
```
Confrontation in living room: son facing ghostly father across coffee table, father looks tired not smug, dramatic lamp lighting, complex emotions, cinematic, 16:9
```

---

### Scene 5: Living with the Roommate
**STORY:**
- 他醒了
- 从那天起，每次那个声音出现，他不再当真
- "哦，是你啊，爸。今天又来骂我了？随便吧。"
- 声音还在。但他不再相信它
- 他开始把它当成背景噪音，像邻居装修

**IMAGE PROMPT:**
```
Asian man walking past shadowy father figure, wearing earphones, slight smile, ignoring the voice, lighter atmosphere, cinematic, 16:9
```

---

### Scene 6: The Silence
**STORY:**
- 某天，声音突然安静了
- 整整一天，脑子里没有爸爸的声音
- 他以为会很高兴
- 但他慌了
- 没有那个声音，他不知道自己是谁了
- 他的整个身份，都是围绕着"证明爸爸是错的"建立的
- 如果爸爸不在了...他在跟谁证明？

**IMAGE PROMPT:**
```
Eerily empty apartment, Asian man standing confused and lost, unsettling silence, stark composition, cinematic, 16:9
```

---

### Scene 7: The Deeper Voice (TWIST)
**STORY:**
- 那晚又做梦，公寓空了，爸爸不见了
- 然后他听到另一个声音
- 很轻，从四面八方来：
- "房客走了。现在，你听到的是谁？"
- [停顿]
- 他仔细听
- 那个声音不在脑子里
- 那是脑子在"听"的东西
- 爸爸的声音是噪音
- 但还有一个更深的"他"，一直在听着所有噪音

**IMAGE PROMPT:**
```
Asian man floating in peaceful void, soft warm light from within, infinite silence, pure awareness beyond thoughts, transcendent, cinematic, 16:9
```

---

### Scene 8: Resolution
**STORY:**
- 爸爸的声音后来又回来了，偶尔还是会说两句
- 但他不在意了
- 因为他发现了一个秘密：
- 那个声音是爸爸的
- 但听到声音的那个，不是
- 那个听的，从来没被任何声音伤害过
- 那个，才是他

**IMAGE PROMPT:**
```
Close-up of peaceful Asian man's eye, inside the pupil is a vast calm space like universe, the observer within, profound, cinematic, 16:9
```

**"那个人" 出现:** 窗外站着看的人

---

### Scene 9: 灵魂拷问
**TEXT ON SCREEN:**
> 脑子里那个声音——
> 是谁的声音？
> 听到它的，又是谁？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP08: 邪教逃亡
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：你怎么知道你相信的是真的，而不是别人塞给你的？
- 引入：小雨，从小在一个"灵性社区"长大
- 社区里有个"老师"，所有人都听他的

**IMAGE PROMPT:**
```
Isolated spiritual commune, Asian people in robes around charismatic leader, cult-like but superficially peaceful, unsettling, cinematic, 16:9
```

---

### Scene 2: Life Inside
**STORY:**
- 老师说什么，什么就是真的
- "太阳是蓝色的"——大家就说蓝色
- "外面的世界是地狱"——没有人想出去
- 小雨从来没有怀疑过
- 因为她没见过外面

**IMAGE PROMPT:**
```
Young Asian woman among devoted followers looking up, soft cult lighting, trapped without knowing, cinematic, 16:9
```

---

### Scene 3: Escape
**STORY:**
- 18岁那年，她偷偷溜出去
- 翻过墙，跑进夜色
- 心跳得要命

**IMAGE PROMPT:**
```
Young Asian woman climbing fence at night, looking back fearfully, moonlight, escape and fear, cinematic, 16:9
```

---

### Scene 4: Outside World
**STORY:**
- 外面的世界让她震惊
- 原来太阳是黄色的
- 原来有人根本不知道"老师"是谁，也活得好好的
- 她的整个世界观崩塌了

**IMAGE PROMPT:**
```
Young Asian woman in simple clothes standing overwhelmed in busy city, sensory overload, fish out of water, cinematic, 16:9
```

---

### Scene 5: Confrontation
**STORY:**
- 她回去质问老师
- "外面和你说的不一样"
- 老师说：外面的人是迷失的。只有我知道真相
- 她问：我怎么知道你说的是真相？
- 老师说：因为我是你的老师
- 那天晚上，她又溜了出去，再也没回来

**IMAGE PROMPT:**
```
Young Asian woman facing leader in simple room, tension, she's questioning, he's dismissive, dramatic lighting, cinematic, 16:9
```

---

### Scene 6: Years of Searching
**STORY:**
- 她流浪、打工、读书
- 她遇到好人，也遇到骗子
- 她不再相信任何人
- 她决定：我要自己找到答案
- 十年后，她觉得自己"觉醒"了
- 她开始写书、演讲、收学生

**IMAGE PROMPT:**
```
Montage: books, travel, growth, passage of time, Asian woman transforming from lost girl to confident teacher, warm hopeful tones, cinematic, 16:9
```

---

### Scene 7: Becoming What She Escaped (TWIST)
**STORY:**
- 某天，她站在台上，几百人看着她
- 她听到自己说：
- "外面的世界充满了谎言"
- "只有我教的方法才能让你们觉醒"
- "相信我，我会带领你们"
- [停顿]
- 她愣住了
- 这些话...她听过
- 一字一句，都是老师说过的
- 她变成了她逃离的那个人

**IMAGE PROMPT:**
```
Asian woman on seminar stage, audience admiring, her face shows horror of self-recognition, ghostly image of cult leader superimposed on her, cinematic, 16:9
```

---

### Scene 8: The Choice
**STORY:**
- 她停下来
- 台下几百人安静地看着她，等她继续说
- 她拿起麦克风：
- "我要告诉你们一件事"
- "我不知道答案"
- "如果我假装知道，你们就会停止寻找"
- "但你们自己能找到"
- "现在，散会吧"

**IMAGE PROMPT:**
```
Asian woman on stage holding microphone, speaking honestly, some audience members confused, some nodding, moment of truth, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 台下沉默了几秒
- 然后有人开始鼓掌
- 她走下台，走出大门
- 阳光照在她脸上
- 她不知道接下来去哪
- 但她笑了
- 因为这一次，她终于不是在逃离什么
- 她只是在走

**IMAGE PROMPT:**
```
Asian woman walking away from building into sunlight, alone but free, peaceful uncertainty, no longer running, cinematic, 16:9
```

**"那个人" 出现:** 人群中站着不动的人

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 你现在相信的东西——
> 是你自己看见的？
> 还是有人塞给你的？
> 你怎么知道？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP09: 捉迷藏
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：如果你是神假扮的——只是暂时忘了——你会怎么过今天？
- 引入：老王，55岁，送了二十年快递
- 不算成功，但也不算失败
- 有套小房子，够住。离过婚，一个人过习惯了
- 儿子在另一个城市，一年见一两次
- 不是不认他，就是各忙各的
- 每次见面，儿子会问他身体怎么样，然后没话了
- 他想多说点什么，又不知道说什么
- 他不觉得自己惨
- 他只是有时候会想：这辈子，就这样了吗？

**IMAGE PROMPT:**
```
Tired middle-aged Asian delivery man on electric scooter in traffic, ordinary expression, urban China, golden hour, cinematic, 16:9
```

---

### Scene 2: The Strange Delivery
**STORY:**
- 某天，他接到一个奇怪的单
- 送件地址是一座山上的寺庙
- 收件人名字：王建国（他自己的名字）
- 寄件人：无
- 他以为是系统出错，但还是去了

**IMAGE PROMPT:**
```
Delivery man looking at phone showing strange order with his own name, confused expression, urban street, cinematic, 16:9
```

---

### Scene 3: The Temple
**STORY:**
- 他骑了一个小时山路
- 寺庙很小，很旧，像是没人住
- 门口坐着一个和尚，好像在等他
- 和尚说：快递到了？
- 老王说：呃...是您的件
- 和尚说：不是我的，是你的

**IMAGE PROMPT:**
```
Small old Buddhist temple on mountain, delivery scooter parked outside, monk waiting at entrance, mysterious atmosphere, cinematic, 16:9
```

---

### Scene 4: The Package
**STORY:**
- 老王打开包裹
- 里面是一个骨灰盒
- 盒子上写着：王建国
- 签收单上的日期：30年后
- [停顿]
- 他的手开始抖

**IMAGE PROMPT:**
```
Close-up of Asian man's trembling hands holding a funeral urn with his own name, date "30 years later", shock and confusion, cinematic, 16:9
```

---

### Scene 5: The Story
**STORY:**
- 和尚请他坐下喝茶，说：别怕，我给你讲个故事
- 从前有个神仙，什么都能做，什么都知道
- 但他无聊得要死
- 于是他玩了一个游戏：捉迷藏
- 他把自己分成无数碎片，变成石头、树、人
- 最关键的一步：忘记自己是神仙
- 这样他就能体验惊喜、恐惧、爱、痛苦
- 所有当神仙时体验不到的东西

**IMAGE PROMPT:**
```
Cosmic being shattering into millions of sparkling fragments becoming stars, planets, humans, beautiful creation moment, epic, cinematic, 16:9
```

---

### Scene 6: The Question
**STORY:**
- 和尚指着骨灰盒说：
- 这是你未来的身体。30年后会寄回来
- 但装在里面的那个"你"，其实从来没变过
- 老王问：那我是...
- 和尚笑了：你猜你是谁？
- 老王说：我要是神仙能这么惨？
- 和尚说：惨才好玩啊。当神仙的时候，体验不到"惨"
- 你特意来体验的

**IMAGE PROMPT:**
```
Delivery man and monk sitting with tea, urn on table between them, warm temple interior, intimate profound conversation, monk smiling knowingly, cinematic, 16:9
```

---

### Scene 7: The Disappearance (TWIST)
**STORY:**
- 老王骑车离开
- 骑了一段，他想再问一个问题
- 掉头回去
- 寺庙不见了。只有一片空地
- 他问路边的人：这里不是有个寺庙吗？
- 路人说：这里从来没有寺庙
- 他低头看手里——骨灰盒也不见了
- 但他清楚记得那个重量

**IMAGE PROMPT:**
```
Asian man standing confused at empty grass lot where temple should be, just trees and empty space, mysterious and surreal, cinematic, 16:9
```

---

### Scene 8: The Photo
**STORY:**
- 他看手机相册
- 刚才在寺庙拍的照片
- 只有一张空凳子，和一杯茶
- 没有和尚，没有骨灰盒
- [停顿]
- 和尚说过：偶尔，会有人来提醒你一下

**IMAGE PROMPT:**
```
Phone screen showing photo of empty stool and tea cup, no monk, no urn, man's shocked face reflected in screen, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 他不知道刚才是真是假
- 但他发现，这不重要
- 他继续送快递
- 但看什么都不一样了
- 路边的树、堵车的人、骂他的客户
- 都像是"神仙同事"
- 大家都在玩捉迷藏
- 都忘了自己是谁
- 他骑着电动车，忽然觉得：
- 这个游戏，还挺有意思的

**IMAGE PROMPT:**
```
Delivery Asian man riding through city, everything has subtle golden glow, ordinary people with faint halos, seeing divinity in ordinary life, peaceful smile, cinematic, 16:9
```

**"那个人" 出现:** 和尚就是"那个人"（本集揭示但消失）

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 如果有一个"更高的你"想提醒你——
> 他会用什么方式？
> 你会认出他吗？

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP10: 隧道
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：如果你死了四分钟——你会看到什么？
- 引入：阿健，42岁，出了车祸
- 手术台上，心跳停了四分钟

**IMAGE PROMPT:**
```
Car crash aftermath at night, emergency lights, paramedics rushing, rain, life and death moment, cinematic, 16:9
```

---

### Scene 2: Leaving the Body
**STORY:**
- 他发现自己浮在手术台上方
- 看着医生在救他的身体
- 他想喊"我在这里"，没人听见
- 他意识到：那个身体不是"他"

**IMAGE PROMPT:**
```
Translucent figure of Asian man floating above operating table, looking down at surgeons working, ethereal blue tones, surreal, cinematic, 16:9
```

---

### Scene 3: The Tunnel
**STORY:**
- 然后他被什么东西拉走了
- 进入一个隧道
- 很长，很暗，但尽头有光
- 那光不刺眼，很柔和，很温暖

**IMAGE PROMPT:**
```
Long dark tunnel with warm white light at end, peaceful and inviting, silhouette walking toward light, cinematic, 16:9
```

---

### Scene 4: Life Review
**STORY:**
- 光里面，他看到了自己的一生
- 不是像电影那样播放，而是同时存在
- 五岁、初恋、结婚、吵架——全部叠在一起
- 他能同时感受每一刻的情绪

**IMAGE PROMPT:**
```
Holographic display of entire life simultaneously - childhood, love, wedding - all layered and overlapping, beautiful chaos, cinematic, 16:9
```

---

### Scene 5: The Moment
**STORY:**
- 然后光把他带到一个特定的画面
- 那是十年前
- 他当时是公司主管，手下有个年轻员工，叫小林
- 小林工作出了错，损失很大
- 他当时也不是故意要骂那么狠
- 只是那天项目出了问题，老板刚骂完他，他满肚子火
- 小林进来汇报，刚好撞在枪口上
- 他说："这点事都做不好，你还能做什么？"
- 说完他就后悔了。但他没道歉
- 他想：年轻人，说两句没什么
- 小林低着头，一句话不说，第二天就辞职了

**IMAGE PROMPT:**
```
Office scene: Asian manager speaking harshly to young employee, manager looks stressed not angry, employee's head down, harsh fluorescent lighting, regrettable moment, cinematic, 16:9
```

---

### Scene 6: The Other Side (TWIST)
**STORY:**
- 但这次，他不是从自己的角度看
- 他是从小林的角度体验这个画面
- 他感受到小林感受到的一切：
- 不是愤怒，是迷茫
- "我真的那么差吗？"
- 脸上发烫的羞耻、胃里翻涌的恶心
- 小林回到工位上，假装在看电脑，其实什么都没做
- 旁边同事没有人来安慰他。因为大家都假装没看见
- 那天晚上小林没睡好
- 第二天他递了辞职信。理由写的是"个人原因"
- [停顿]
- 他说过的每一句话，都有重量
- 他从来不知道

**IMAGE PROMPT:**
```
Same office scene but from victim's POV, looking down at desk pretending to work, colleagues avoiding eye contact, feeling small and isolated, emotional devastation, cinematic, 16:9
```

---

### Scene 7: The Unexpected
**STORY:**
- 他痛苦极了，想道歉
- 然后光带他看了另一个画面：
- 五年后的小林
- 小林现在自己带团队了
- 有一次下属犯了错，他很想发火
- 但他忍住了，说："没事，我们看看怎么补救。"
- 他不知道自己为什么要这样做
- 他只是不想让别人体验他体验过的那种感觉
- [停顿]
- 小林被那次经历伤害了
- 但他选择不把伤害传下去
- 他变成了更好的人

**IMAGE PROMPT:**
```
Different office scene: the former young employee (now older) calmly helping his own employee, warm lighting, growth and healing, cinematic, 16:9
```

---

### Scene 8: The Truth
**STORY:**
- 阿健问：那他...原谅我了吗？
- 光说了一句话：
- "他早就原谅你了"
- "唯一还没原谅你的人，是你自己"
- [停顿]
- "你可以放下了"

**IMAGE PROMPT:**
```
Asian man surrounded by warm light, tears streaming down face, releasing years of guilt, cathartic moment, cinematic, 16:9
```

---

### Scene 9: Return
**STORY:**
- 他醒了
- 手术成功
- 他躺在病床上，阳光从窗户照进来
- 他找到了小林的联系方式
- 发了一条消息：
- "我欠你一句道歉。对不起。"
- 三分钟后，小林回复：
- "老大，那是十年前的事了。我早就不在意了。"
- "你还好吗？"

**IMAGE PROMPT:**
```
Asian man in hospital bed looking at phone, morning sunlight, tears and smile, reconnection, healing, cinematic, 16:9
```

**"那个人" 出现:** 隧道光里的人影

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 你伤害过谁，还没有道歉？
> 谁伤害过你，你还没有原谅？
> 也许他们早就放下了——
> 还抓着不放的，只有你自己

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP11: 镜子
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Opening
**STORY:**
- 悬念：如果失去所有记忆——你还是你吗？
- 引入：小苏，28岁
- 一场高烧之后，她失忆了
- 忘了名字、工作、家人、过去的一切

**IMAGE PROMPT:**
```
Disoriented young Asian woman in hospital bed, looking at own hands like stranger's, clinical lighting, lost identity, cinematic, 16:9
```

---

### Scene 2: The Labels
**STORY:**
- 医生告诉她：你叫苏小敏，28岁，广告公司，单身
- 她点点头，但没有任何感觉
- 那些标签像是别人的简历

**IMAGE PROMPT:**
```
Asian woman looking at ID card and photos she doesn't recognize, disconnection from past, searching, cinematic, 16:9
```

---

### Scene 3: The Discovery
**STORY:**
- 她出院后住进自己的公寓。钥匙在包里，说明这真的是她的家
- 但她像个客人一样，小心翼翼地看每一样东西
- 冰箱上贴着便利贴："周五 Amy 生日"。Amy是谁？
- 她翻手机，有个群叫"闺蜜团"
- 最后一条消息是三个月前，有人说："小敏你太过分了。"
- 然后她被移出了群聊

**IMAGE PROMPT:**
```
Asian woman in her own apartment looking at phone showing she was removed from group chat, confused and disturbed, discovering past self, cinematic, 16:9
```

---

### Scene 4: The Evidence
**STORY:**
- 她翻微信记录，发现自己和很多人的对话都停在很久以前
- 停止的方式不是吵架，而是……对方不再回复了
- 她找到一本日记
- 里面写的不是"我做了什么坏事"，而是各种抱怨：
- "Amy太敏感了，开个玩笑都生气。"
- "他们不理解我，我又没做错什么。"
- "为什么受伤的总是我？"
- 她看着日记里的"自己"，觉得很陌生
- 那个人好像永远是受害者，永远觉得别人对不起她
- 但从聊天记录来看……好像不是这样

**IMAGE PROMPT:**
```
Asian woman reading old diary, expressions of confusion and growing realization, discovering uncomfortable truth about past self, cinematic, 16:9
```

---

### Scene 5: The Choice
**STORY:**
- 医生说：记忆可能会慢慢恢复
- 她不知道自己想不想恢复
- 如果"以前的她"真的是那样的人...
- 一个永远觉得自己没错、永远是受害者的人
- 她要不要变回去？
- 还是她可以...选择不要那些思维方式？
- 那天晚上洗完澡，她用毛巾擦镜子上的雾气
- 镜子慢慢变清晰——她看到了自己的脸
- 这是失忆后第一次认真看自己

**IMAGE PROMPT:**
```
Asian woman wiping foggy bathroom mirror, her face slowly appearing, first time seeing herself, vulnerable moment, cinematic, 16:9
```

---

### Scene 6: The Mirror
**STORY:**
- 她盯着镜子里的人
- 问镜子里的人：你到底是谁？
- 镜子里的人没回答
- 她举手，镜子里举手
- 她笑，镜子里笑
- 但她发现一件奇怪的事——
- 镜子里的人，动作好像总是慢一点点

**IMAGE PROMPT:**
```
Asian woman staring at reflection in mirror at night, searching for identity, something slightly off, dramatic lighting, cinematic, 16:9
```

---

### Scene 7: The Realization (TWIST)
**STORY:**
- 如果是反射，应该同时
- 为什么会慢？
- [停顿]
- 她突然明白：
- 镜子里的不是"她"
- 镜子只能照到"苏小敏"这个角色
- 而她——那个正在看镜子的——不在镜子里
- 以前的苏小敏伤害过人——那只是一个剧本
- 她不是那个剧本，她是正在体验剧本的人

**IMAGE PROMPT:**
```
Multiple exposure: Asian woman moving but reflection lagging, showing separation between self and image, uncanny, liberating, cinematic, 16:9
```

---

### Scene 8: The Freedom
**STORY:**
- 她做了一个决定
- 她不知道能不能真的"变成"一个不同的人
- 但她要按照自己想成为的样子去做
- 以前的苏小敏伤害过人
- 但那个苏小敏已经"死"了
- 现在的她，可以选择方向

**IMAGE PROMPT:**
```
Asian woman removing mirror from wall, empty wall behind, she's still there, choosing freedom from past, symbolic, cinematic, 16:9
```

---

### Scene 9: Resolution
**STORY:**
- 记忆后来零零散散回来了一些
- 她确实做过伤害别人的事
- 但更多的是：她以前总觉得自己是对的
- 她没有让那些记忆变成她的身份
- 她一个一个找到她伤害过的人
- 道歉，不是因为"那是我"
- 而是因为"我选择为那些事负责"
- 她给Amy发了条消息："我不记得发生了什么，但我知道我伤害了你。对不起。"
- Amy没回复。但她不再等回复了
- 也许她改变的不是结局，而是走向结局的方式

**IMAGE PROMPT:**
```
Asian woman sending message on phone with peaceful expression, letting go, growth, warm lighting, cinematic, 16:9
```

**"那个人" 出现:** 镜子背景里一闪而过的身影

---

### Scene 10: 灵魂拷问
**TEXT ON SCREEN:**
> 如果明天你忘了一切——
> 你会选择成为谁？
> 其实你不需要失忆
> 你现在就可以选

**IMAGE PROMPT:**
```
Black background, elegant white Chinese text centered, minimalist typography, 16:9
```

---

# EP12: 游戏厅 (FINALE)
- ✅ Script generated

## Story + Image Prompts

### Scene 1: Death
**STORY:**
- 悬念：如果死后发现这一切是你选的游戏——你会怎么想？
- 一个人死了
- 白光

**IMAGE PROMPT:**
```
Brilliant white light consuming everything, peaceful transition, silhouette in light, death as doorway, cinematic, 16:9
```

---

### Scene 2: The Arcade
**STORY:**
- 他睁开眼，站在一个巨大的游戏厅
- 到处是机器
- 每台机器的屏幕上都在播放一段人生
- 皇帝、乞丐、男人、女人、长寿、短命

**IMAGE PROMPT:**
```
Vast surreal cosmic arcade, countless glowing machines, each screen showing different life, magical overwhelming, cinematic, 16:9
```

---

### Scene 3: The Lives
**STORY:**
- 他走过去，看那些屏幕
- 一个国王在签法令
- 一个孩子在挨饿
- 一对恋人在接吻
- 一个老人在孤独地死去
- 所有的人生，都在同时发生

**IMAGE PROMPT:**
```
Multiple screens showing different lives - king, starving child, lovers, dying elder - all playing simultaneously, beautiful contrast, cinematic, 16:9
```

---

### Scene 4: Meeting "那个人" (REVEAL)
**STORY:**
- 一个人走过来
- 他愣住了——这个人好眼熟
- 那个人笑了：你不记得了？我一直在你旁边
- 他开始回忆——
- 地铁上看报纸的老人
- 河边钓鱼的人
- 消失的寺庙里的和尚
- 隧道光里的人影
- 是同一个人。一直都是

**IMAGE PROMPT:**
```
Two versions of same Asian person facing each other - confused player, calm knowing watcher, profound meeting, cinematic, 16:9
```

---

### Scene 5: The Explanation
**STORY:**
- "你是谁？"
- "我是你自己"
- "你进入游戏之前，把自己分成两部分"
- "一部分进去玩，一部分留在外面看"
- "我就是留在外面的那部分"
- "你为什么不帮我？我那辈子很苦"
- "规则就是这样。进去的人必须忘记外面，才能认真玩"
- "但我一直在看着你"
- "有时你会感觉有人在看着你，有个声音在提醒你"
- "那就是我"

**IMAGE PROMPT:**
```
Two Asian figures talking in cosmic arcade, warm ethereal lighting, intimate conversation about existence, cinematic, 16:9
```

---

### Scene 6: Flashback
**STORY:**
- 快速闪回前11集"那个人"出现的瞬间
- 公园长椅看报纸
- 扫地的清洁工
- 梦境角落的人影
- 白墙上的水渍
- 河边的钓鱼人
- 画中画的模糊脸
- 窗外的观察者
- 人群中的静止者
- 消失的和尚
- 隧道尽头的光
- 镜子里的一闪
- 一直是同一个人

**IMAGE PROMPT:**
```
Montage collage of "那个人" from all episodes - subway, sweeper, monk, tunnel - revealed as same person, revelation, cinematic, 16:9
```

---

### Scene 7: The Choice
**STORY:**
- "这一局结束了。想再玩一局吗？"
- 他看着那些机器："我能选哪台？"
- "随便。富穷男女长短命——什么都可以"
- "有区别吗？"
- "没有。都是体验。没有好坏"
- "唯一的问题是——你想体验什么？"
- 他看了很久
- 指向一台机器
- "那个剧本很苦"
- "我知道。但里面有一段很美的爱情"
- "而且...那台屏幕上有个女人，好像我见过"

**IMAGE PROMPT:**
```
Asian person standing before specific glowing arcade machine, screen shows a woman's silhouette, hand reaching, moment of choosing next life, cinematic, 16:9
```

---

### Scene 8: Start
**STORY:**
- 他走向机器
- 按开始键之前，回头问：
- "进去之后，我会忘记这一切吗？"
- "会"
- "那我怎么会想起来？"
- "偶尔我会提醒你"
- "当你看到这个故事的时候——你就想起来了"
- 他笑了
- 按下开始键
- 白光

**IMAGE PROMPT:**
```
Finger pressing glowing START button, white light engulfing everything, new journey beginning, cinematic, 16:9
```

---

### Scene 9: Fourth Wall Break
**STORY:**
- 画面切到：现实
- 一个人正在看这个视频
- 就是你
- 屏幕上出现字幕：
- "欢迎回来。"
- [停顿]
- "你想起来了吗？"
- [停顿]
- "别把游戏当真。但要玩得认真。"
- [停顿]
- "下一局，你想体验什么？"
- [长停顿]
- "...或者，你已经选过了"
- "你正在经历的——就是你选的"

**IMAGE PROMPT:**
```
POV looking at viewer through screen, text "欢迎回来", fourth wall break, intimate and startling, cinematic, 16:9
```

---

### Scene 10: Final Closing
**STORY:**
- 灵魂拷问：
- 如果能重选——你想体验什么？
- [长停顿，渐黑]
- [几秒后]
- "感谢入场。请继续游戏。"
- "——那个在外面看着你的你"

**IMAGE PROMPT:**
```
Black screen, white text: "感谢入场。请继续游戏。" then "——那个在外面看着你的你", peaceful conclusion, cinematic, 16:9
```

---

# Phase 2: Production Checklist

After all 12 scripts are generated:

### Scripts (save as `EP##/script.md`)
- ⬜ EP01/script.md
- ⬜ EP02/script.md
- ⬜ EP03/script.md
- ⬜ EP04/script.md
- ⬜ EP05/script.md
- ⬜ EP06/script.md
- ⬜ EP07/script.md
- ⬜ EP08/script.md
- ⬜ EP09/script.md
- ⬜ EP10/script.md
- ⬜ EP11/script.md
- ⬜ EP12/script.md

### Audio (save as `EP##/audio.mp3`)
- ⬜ EP01/audio.mp3
- ⬜ EP02/audio.mp3
- ⬜ EP03/audio.mp3
- ⬜ EP04/audio.mp3
- ⬜ EP05/audio.mp3
- ⬜ EP06/audio.mp3
- ⬜ EP07/audio.mp3
- ⬜ EP08/audio.mp3
- ⬜ EP09/audio.mp3
- ⬜ EP10/audio.mp3
- ⬜ EP11/audio.mp3
- ⬜ EP12/audio.mp3

### Images (save as `EP##/img_01.png`, `img_02.png`, etc.)
- ⬜ EP01/images
- ⬜ EP02/images
- ⬜ EP03/images
- ⬜ EP04/images
- ⬜ EP05/images
- ⬜ EP06/images
- ⬜ EP07/images
- ⬜ EP08/images
- ⬜ EP09/images
- ⬜ EP10/images
- ⬜ EP11/images
- ⬜ EP12/images

### Video (save as `EP##/video.mp4`)
- ⬜ EP01/video.mp4
- ⬜ EP02/video.mp4
- ⬜ EP03/video.mp4
- ⬜ EP04/video.mp4
- ⬜ EP05/video.mp4
- ⬜ EP06/video.mp4
- ⬜ EP07/video.mp4
- ⬜ EP08/video.mp4
- ⬜ EP09/video.mp4
- ⬜ EP10/video.mp4
- ⬜ EP11/video.mp4
- ⬜ EP12/video.mp4

### Upload
- ⬜ All episodes uploaded
- ⬜ Playlist created
- ⬜ **SERIES COMPLETE** 🎉

---

# Quick Reference: 灵魂拷问

| EP | Question |
|---|---|
| 1 | 你今天"在"吗？还是只是身体在，人不在？ |
| 2 | 未来的你能寄一样东西——是警告还是祝福？ |
| 3 | 如果你是NPC——你已经知道了，只是假装忘记？ |
| 4 | 那面墙，保护的是谁？ |
| 5 | 你在抓住什么？如果松手，会怎样？ |
| 6 | 你是画里的人，还是画画的手？ |
| 7 | 脑子里的声音是谁的？听到它的又是谁？ |
| 8 | 你相信的是自己看见的，还是别人塞给你的？ |
| 9 | 更高的你想提醒你，会用什么方式？ |
| 10 | 你伤害过谁没道歉？谁伤害你没原谅？ |
| 11 | 如果明天失忆——你会选择成为谁？ |
| 12 | 你正在经历的——就是你选的 |

---

# Episode Summary: What Changed

| EP | Original | Current Version |
|---|---|---|
| 1 | 预知死亡 | 录像回放 — 发现自己像僵尸，开始"在场" |
| 2 | "没日没夜不吃不喝" obsession | Quiet withdrawal - early回家, eating takeout facing screen |
| 3 | AI questions him | AI predicts his behavior + he wrote his own code |
| 4 | 演讲出丑、告白被拒、临终遗言 | 被忽视的画、没被采纳的想法、没见到的最后一面 |
| 5 | 追三天、抓手臂、撞河 | 出差想见面她没来、河边抽烟沉思 |
| 6 | Two dream worlds | Added fading mechanic + mother exists in both worlds |
| 7 | 纯语言暴力的父亲 | 不会表达的父亲 + 三代人同一套剧本 |
| 8 | Escapes cult, becomes teacher | Added: she speaks cult leader's EXACT phrases |
| 9 | 老婆跑了儿子不认 | 普通离婚、正常疏远、"就这样了" |
| 10 | 哭三小时、三年不说话 | 迷茫沉默、假装看电脑、"个人原因"辞职 |
| 11 | 前任来医院控诉 | 自己翻手机日记、发现被移出群聊、受害者心态 |
| 12 | Arcade finale | Added connection to earlier episodes (sees familiar woman) |

---

*Work through EP01 → EP12. One at a time. ✨*
