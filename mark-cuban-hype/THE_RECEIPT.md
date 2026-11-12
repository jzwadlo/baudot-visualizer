# THE RECEIPT — a surreal hype film about what Mark Cuban is about right now

Runtime: about 60s, made of 5 Seedance generations of about 12s each, stitched on match cuts.
Format: 2.39:1, 35mm-film look, soft halation, night-heavy.

---

## 1. What Mark Cuban seems to care about (mid-Sept to mid-Nov 2026)

How I got this: x.com would not load from this session, so I could not scroll his timeline.
This list comes from news coverage of his posts and from search snippets of individual posts.
It is a summary of what got covered, not a full read of every post.

| # | Theme | Evidence (date) |
|---|-------|-----------------|
| 1 | **Healthcare costs are the real job-killer, not AI.** | Sept X post: "the cost of health care benefits will get more people fired, or not hired, than AI… It's far easier to blame AI than it is to blame health care costs." (Fortune, Oct 8) |
| 2 | **Transparency and naming names (Cost Plus Drugs, PBMs, insurers).** | "Our model is simple: we show what we pay…" (his Texas Capitol testimony, posted on X); "Got to name the carrier with details or they won't ever change." (Oct 16); 5-step plan against drug middlemen, backing the Break Up Big Medicine Act (Fortune, Oct 21) |
| 3 | **"The math is the math": deficit plan.** | 7-point plan: 1%-a-year cuts at every agency for 5 years, 44% top income-tax rate (Nov 7–9). "Ideology is [not] a Strategy… drive down spending and drive up revenues." |
| 4 | **Independence: no parties.** | "I'd get rid of all political parties" (Reason, Oct 14); a third party has the same power dynamics, so what's needed is a ballot path with no party involved (Nov 4); "I'm against all of these" to Musk, and independents are a growing force (Oct 30) |
| 5 | **"Enough": impact over net worth.** | Says his family has enough and he doesn't care about climbing the Forbes list (CNBC, Nov 7); "What makes me an oligarch?" (about Nov 11) |
| 6 | **AI: an ally against healthcare incumbents, but a bubble risk.** | AI could "collapse" big healthcare companies by exposing contracts (Benzinga, Nov); warns of AI debt-fueled spending and says AI lacks ethics (Diary of a CEO, late Oct) |
| 7 | **The NBA should be about fans, not franchise valuations.** | Admits he "certainly benefited" from rising valuations but questions putting them ahead of fans (Yahoo Sports, Nov 8) |
| 8 | **Sparring with Musk.** | "Whatever it takes. Right @elonmusk" (Oct 28, about Grok recommending Cost Plus Drugs); pushback on Musk's 2028 warning (Oct 30) |

**The thread through all of it:** show the real price. Drugs, deficits, parties, his own wealth.
Strip out the middlemen and the slogans, then read the receipt out loud.

---

## 2. Director's treatment

### The idea
One object runs through the whole film: **an endless strip of white thermal receipt paper.**
It starts printing in a pharmacy and never stops. It runs through every location: hallways,
highways, server farms, office towers. At the end, he finally tears it off.

It's also a nod to this repo. A receipt strip is a modern punched tape, the same lineage as
Baudot telegraph tape. Every few shots, put a row of 5-hole punches along the paper's edge.

### Visual rules (consistent across all 5 generations)
- **Hiro Murai half:** locked-off wide frames that hold too long. Deadpan, uncanny Americana.
  Sodium-vapor amber against sick pharmacy-cyan fluorescents. One impossible thing in an
  ordinary place, and nobody reacts to it.
- **Daniels half:** maximalist absurdity done in camera. Endless duplicate people, objects
  that transform, crash zooms, whip-pans and speed ramps. Stupid on the surface, sincere underneath.
- **Him:** always the same wardrobe so Seedance holds him across generations: a **navy
  quarter-zip, dark jeans, white sneakers**. He's mostly in silhouette, from behind, or in a
  partial profile. That keeps continuity and avoids a real-person face render (see notes).
- **Palette lock:** amber sodium light + cyan fluorescent + receipt-paper white. No other
  saturated colors except one: **Mavericks royal blue**, which appears only in the finale.
- **Texture lock:** 35mm grain, halation on highlights, slight gate weave.

### Edit and transitions (between generations, done in the edit)
Each generation ends on a frame that becomes the first frame of the next one:

| Cut | Out-frame | In-frame | Transition |
|-----|-----------|----------|------------|
| 1→2 | Receipt paper rushes into the lens and goes full white | White corporate corridor | White-flash match cut |
| 2→3 | Price stickers flutter down like snow | Stickers become snow over a night highway | Match on motion |
| 3→4 | Deflating balloon skin wraps over the lens, goes dark | Dark server aisle, LEDs blink on | Black-wipe match cut |
| 4→5 | Receipt strip pulled through a revolving door, whip-pan | Whip lands in a dark arena tunnel | Whip-pan match |

Sound bed: a low thermal-printer chatter that turns into a beat, the printer's buzz used as
the kick drum. It hard-stops on the paper tear in segment 5, then the drop hits.

### Beat sheet
1. **THE PHARMACY AT THE END OF THE WORLD** (Murai): Show what it costs.
2. **THE MIDDLEMEN** (Daniels): Cut the line.
3. **THE MATH IS THE MATH** (Murai): No parties, just numbers.
4. **IT'S NOT THE ROBOTS** (Daniels): The bill is what's firing people.
5. **ENOUGH** (both): Tear it off, play for the fans.

---

## 3. Seedance prompts (seedance-director skill format: EN + ZH JSON, about 12s each)

### Segment 1 — The Pharmacy at the End of the World (Atmosphere → Reveal)

```json
[{"lang":"en","prompt":"Style & Mood: Deadpan surreal Americana, 35mm film grain, soft halation on every highlight, slight gate weave. Sodium-vapor amber outside, sickly cyan fluorescent inside. Long locked-off frames that hold a beat too long. Narrative Summary: A lone pharmacy in a dark field prints a receipt that never ends. Dynamic Description: Static extreme wide shot at night — a single small-town pharmacy glows in the middle of an empty flat field, one sodium streetlamp buzzing beside it, moths circling. Nothing moves except the light flickering. Hard cut to slow stabilized dolly-in down an aisle inside, shelves of identical white pill bottles stretching far past where the building should end. The man in the navy quarter-zip, seen from behind, stands at the register; the receipt printer starts chattering and a strip of white thermal paper spills out, curling to the floor, then across the floor, then down the aisle toward camera. Cut to handheld close-up of the price labels on the shelf beside him — the numbers flip like split-flap displays, tumbling downward digit by digit. Cut to low-angle locked-off ECU at floor level: the receipt strip slides toward the lens, a row of five punched holes along its edge, and rushes into the lens until the frame is pure white. Static Description: Empty field, flat horizon, single sodium lamp, moths. Pharmacy interior with endless identical shelves of white bottles, cyan tube lights, scuffed linoleum, thermal receipt printer at the counter."},{"lang":"zh","prompt":"风格与氛围：冷面超现实美国小镇感，35毫米胶片颗粒，高光柔和溢光，轻微片门抖动。室外钠灯琥珀色，室内病态青色日光灯。长时间固定镜头，刻意多停留一拍。叙事概要：荒野中孤零零的药房，打印出一张永不停止的收据。动态描述：夜晚固定极远景——空旷平原正中，一间小镇药房独自发光，旁边一盏钠灯嗡嗡作响，飞蛾盘旋。画面中只有灯光闪烁。硬切至室内缓慢稳定推镜头，沿货架通道推进，一排排相同的白色药瓶延伸至远超建筑本身的深处。身穿藏青色半拉链衫的男人背对镜头站在收银台前，收据打印机开始咔嗒作响，一条白色热敏纸吐出，卷落地面，铺过地板，沿通道朝镜头蔓延。切至手持特写：他身旁货架上的价格标签如翻牌显示屏般逐位翻转，数字一路下跌。切至贴地低角度固定大特写：收据纸带滑向镜头，边缘一排五孔穿孔，直冲镜头，画面变为纯白。静态描述：空旷荒野，平直地平线，单盏钠灯，飞蛾。药房内部无尽相同货架摆满白色药瓶，青色灯管，磨损油毡地面，柜台上的热敏收据打印机。"}]
```

### Segment 2 — The Middlemen (Journey, Daniels absurdity)

```json
[{"lang":"en","prompt":"Style & Mood: Maximalist in-camera absurdity, bright clinical white corridor under flat fluorescent light, 35mm grain and halation carried over, crash zooms and speed ramps. Narrative Summary: An endless line of identical middlemen marks up one pill bottle until he cuts the line. Dynamic Description: Opens on pure white that resolves into a symmetrical static wide of an infinite white office corridor. A line of identical figures in gray suits stands shoulder to shoulder down its full length, passing a single small pill bottle hand to hand from the far end toward camera; each figure slaps a new price sticker onto it, the bottle growing fatter with stickers at every handoff. Crash zoom into a medium close-up on the bottle mid-handoff, now a lumpy ball of stickers. Cut to stabilized tracking shot moving right-to-left alongside the man in the navy quarter-zip as he walks against the flow of the line, the white receipt strip from the pharmacy trailing from his hand along the floor behind him. Speed ramp into slow motion as he pulls a pair of large office scissors and snips the space between two gray-suited figures; the line topples away from that point like dominoes in both directions, figures falling stiff and silent. Cut to high-angle crane shot rising above the corridor — thousands of loose price stickers lift off the fallen figures and float upward, then drift down through the frame like snow. Static Description: Endless white corridor, glossy white floor, flat ceiling panels of fluorescent light. Identical gray suits. One small white pill bottle. Price stickers. Office scissors. White receipt strip with a row of five punched holes along its edge."},{"lang":"zh","prompt":"风格与氛围：极繁主义实拍荒诞感，平光日光灯下明亮冰冷的白色走廊，延续35毫米颗粒与溢光，急推镜头与变速。叙事概要：一排无穷无尽的相同中间商不断给一瓶药加价，直到他剪断这条队伍。动态描述：纯白画面渐显为对称固定广角——一条无限延伸的白色办公走廊。一排身穿灰色西装的相同人影肩并肩站满全程，从远端朝镜头方向手手相传一个小药瓶，每人都往上拍一张新价格贴纸，药瓶每传一次就被贴纸裹得更胖。急推至中近景：传递中的药瓶已成一团鼓胀的贴纸球。切至稳定跟拍，镜头从右向左与身穿藏青色半拉链衫的男人并行，他逆着队伍方向行走，药房那条白色收据纸带从他手中拖曳在身后地面。变速进入升格慢动作，他拿出一把大号办公剪刀，在两个灰西装人影之间一剪；队伍从断口向两侧如多米诺骨牌般倒下，人影僵直无声倒地。切至高角度摇臂上升越过走廊——成千上万张价格贴纸从倒地人影身上剥离飘起，随后如雪花般从画面中缓缓落下。静态描述：无尽白色走廊，光亮白色地面，平顶日光灯板。相同灰色西装。一个白色小药瓶。价格贴纸。办公剪刀。边缘带五孔穿孔的白色收据纸带。"}]
```

### Segment 3 — The Math Is The Math (Atmosphere, Murai stillness)

```json
[{"lang":"en","prompt":"Style & Mood: Eerie deadpan stillness, night highway under sodium-vapor amber, flakes of white falling, 35mm grain and halation, long held frames, a single impossible image treated as ordinary. Narrative Summary: Two giant party-mascot parade balloons deflate over an empty highway while he walks between them doing the math. Dynamic Description: Continuous white flakes drift down into a static extreme wide shot of an empty eight-lane highway at night, sodium lamps receding to the horizon. Floating low over the lanes, tethered to the guardrails, are two enormous parade balloons — a red elephant on the left, a blue donkey on the right — both slowly sagging, air hissing out, their heads drooping toward the asphalt. The man in the navy quarter-zip walks away from camera down the center median between them, small in frame. Cut to handheld medium close-up from behind his shoulder: he holds the long white receipt strip open in both hands, reading down it, the paper covered in columns of figures, the elephant balloon's sagging red skin filling the background out of focus. Cut to locked-off low-angle wide: an overhead highway sign beside him has digital numbers spinning rapidly, then the digits slow, click down, and stop. Cut to aerial drone shot descending onto the balloons as both collapse fully onto the highway like spilled fabric; the drone keeps pushing down until the deflated red skin fills the lens and the frame goes dark. Static Description: Empty eight-lane highway, center median, guardrails, receding sodium lamps, overhead gantry sign with a digital number display. Two giant deflating parade balloons, red elephant and blue donkey, tethered by ropes. Falling white flakes. White receipt strip printed with columns of numbers."},{"lang":"zh","prompt":"风格与氛围：诡异冷面的静止感，钠灯琥珀色笼罩的夜间公路，白色碎片飘落，35毫米颗粒与溢光，长时间停留画面，一个不可能的画面被当作日常呈现。叙事概要：两只巨型政党吉祥物游行气球在空荡公路上空泄气，他在两者之间一边行走一边算账。动态描述：白色碎片持续飘落，固定极远景——深夜空无一车的八车道公路，钠灯一路延伸至地平线。两只巨大游行气球低悬于车道上方，绳索系在护栏上——左侧红色大象，右侧蓝色驴子，正缓缓瘪下，嘶嘶漏气，头部向沥青路面耷拉。身穿藏青色半拉链衫的男人背对镜头沿中央隔离带向远处走去，在画面中显得渺小。切至手持中近景越肩拍摄：他双手展开长长的白色收据纸带，自上而下阅读，纸上印满成列数字，背景中大象气球瘪塌的红色表皮虚焦铺满画面。切至低角度固定广角：他身旁的公路龙门架标牌上，电子数字飞速滚动，随后放慢，逐位跳落，最终停住。切至无人机航拍下降逼近气球，两只气球彻底瘫倒在公路上如泼洒的布料；镜头持续下压，直到瘪掉的红色表皮填满镜头，画面陷入黑暗。静态描述：空旷八车道公路，中央隔离带，护栏，延伸的钠灯，带电子数字显示屏的龙门架标牌。两只巨型泄气游行气球，红色大象与蓝色驴子，绳索牵引。飘落白色碎片。印满成列数字的白色收据纸带。"}]
```

### Segment 4 — It's Not The Robots (Reveal, Daniels absurdity)

```json
[{"lang":"en","prompt":"Style & Mood: Absurd corporate surrealism, cold blue server-LED light giving way to an amber office lobby, 35mm grain and halation, whip-pans and crash zooms, sincere under the absurdity. Narrative Summary: Everyone blames the robot, but the thing pushing workers out the door is a growing medical bill. Dynamic Description: Darkness, then rows of server LEDs blink on in sequence — a slow stabilized dolly-in down a narrow data-center aisle, cables hanging like vines. At the end of the aisle, a humanoid robot sits on a folding chair with its hands in its lap, perfectly still. Hard cut to static wide of a vast corporate office lobby: office workers in business clothes stand frozen, all pointing at the seated robot in the center of the room. Behind them, unnoticed, the white receipt strip pours in through the revolving front door — thick folds piling up, rising, a slow paper flood that nudges the workers backward one by one toward the exits. Crash zoom handheld into close-up of the receipt's surface: rows of hospital line-item charges, a row of five punched holes along its edge. Cut to low-angle locked-off medium shot: the robot turns its head slowly toward the paper flood, then toward camera. Cut to stabilized tracking shot as the man in the navy quarter-zip wades through the waist-high paper, grabs the strip where it enters the revolving door, and hauls it hand over hand; the camera whip-pans with the paper as it whips through the door. Static Description: Narrow data-center aisle, blinking blue LEDs, hanging cables. Grand corporate lobby, polished stone floor, revolving glass front door. One humanoid robot on a folding chair. Office workers in business wear. Endless white receipt strip printed with medical charges."},{"lang":"zh","prompt":"风格与氛围：荒诞职场超现实主义，冷蓝服务器指示灯过渡到琥珀色办公大堂，35毫米颗粒与溢光，甩镜头与急推，荒诞之下藏着真诚。叙事概要：所有人都在指责机器人，真正把员工推出门的却是一张不断变长的医疗账单。动态描述：一片黑暗，服务器指示灯依次亮起——缓慢稳定推镜头穿过狭窄数据中心通道，线缆如藤蔓垂挂。通道尽头，一台人形机器人坐在折叠椅上，双手放在膝头，纹丝不动。硬切至固定广角：宽阔企业办公大堂，身着职业装的员工定格站立，齐齐指向房间中央坐着的机器人。他们身后无人察觉，白色收据纸带正从旋转正门涌入——厚厚纸褶层层堆积、不断升高，缓慢的纸潮将员工一个个推向出口。手持急推至特写：收据表面印满医院逐项收费明细，边缘一排五孔穿孔。切至低角度固定中景：机器人缓缓转头望向纸潮，又转向镜头。切至稳定跟拍：身穿藏青色半拉链衫的男人蹚过齐腰深的纸堆，抓住纸带进入旋转门的那一端，双手交替向外猛拽；镜头随纸带甩镜头穿过旋转门。静态描述：狭窄数据中心通道，闪烁蓝色指示灯，垂挂线缆。宏伟企业大堂，抛光石材地面，玻璃旋转正门。一台坐在折叠椅上的人形机器人。身着职业装的员工。印满医疗收费的无尽白色收据纸带。"}]
```

### Segment 5 — Enough (Impact, finale)

```json
[{"lang":"en","prompt":"Style & Mood: Builds from Murai stillness to a full-scale release. A dark arena lit by a single cold spotlight, then the house lights blast on in royal blue and white. 35mm grain and halation, speed ramps, slow-motion on the release. Narrative Summary: He tears off the receipt, shoots it, and the empty arena fills with fans. Dynamic Description: Whip-pan lands in a dark concrete arena tunnel; stabilized tracking shot following the man in the navy quarter-zip from behind as he walks out onto an empty basketball court, the receipt strip trailing behind him back up the tunnel. Cut to extreme wide static high-angle shot: the whole arena dark and every seat empty, a single spotlight on him at center court. Cut to handheld close-up of his hands as he grips the strip and tears it off with one sharp pull — the paper snaps and the printer chatter in the tunnel stops dead. Cut to low-angle locked-off medium shot as he crumples the torn length into a ball and shoots it toward the hoop; speed ramp into slow motion as the paper ball arcs through the spotlight beam. Cut to crane shot rising from the rim as the ball drops cleanly through the net — the house lights slam on in royal blue and white and every seat is suddenly full of ordinary fans on their feet, arms raised, mid-roar. Cut to static extreme wide, held long: the packed, roaring arena, and him sitting cross-legged alone at center court, small and still, looking up at the crowd. Static Description: Concrete arena tunnel, hardwood basketball court, hoop and net, tiers of seats, one cold spotlight, royal blue and white house lights. Ordinary fans in casual clothes. White receipt strip with five punched holes along its edge, crumpled into a ball."},{"lang":"zh","prompt":"风格与氛围：从冷面静止逐渐推向全面释放。漆黑球馆，仅一束冷色追光，随后皇家蓝与白色场灯轰然亮起。35毫米颗粒与溢光，变速，释放时刻升格慢动作。叙事概要：他撕下收据，投篮，空荡球馆瞬间坐满球迷。动态描述：甩镜头落入漆黑水泥球员通道；稳定跟拍从背后跟随身穿藏青色半拉链衫的男人走上空无一人的篮球场，收据纸带在他身后一路拖回通道深处。切至高角度固定极远景：整座球馆漆黑，座位全空，一束追光打在中圈的他身上。切至手持特写：他双手攥住纸带，猛然一扯撕断——纸带啪地断开，通道里打印机的咔嗒声戛然而止。切至低角度固定中景：他把撕下的纸揉成团，朝篮筐出手；变速进入升格，纸团划过追光光柱。切至摇臂从篮筐处升起，纸团干净利落穿网而过——皇家蓝与白色场灯轰然全亮，每个座位瞬间坐满普通球迷，全体起立，高举双臂，正在呐喊。切至固定极远景长时间停留：座无虚席、声浪沸腾的球馆，他独自盘腿坐在中圈，渺小而静止，抬头望向人群。静态描述：水泥球员通道，硬木篮球场，篮筐与篮网，层层看台，一束冷色追光，皇家蓝与白色场灯。身穿便装的普通球迷。边缘带五孔穿孔、被揉成团的白色收据纸带。"}]
```

---

## 4. Production notes and caveats

- **Skill version:** the `seedance-director` skill in this workspace is written for **Seedance 2.0**,
  not 2.5. These prompts follow its rules: 15s cap, double contrast on every cut, EN+ZH, ZH ≤ 1,800
  chars, no age words, antislop list. I haven't checked whether Seedance 2.5 changes any of those limits.
- **Real-person likeness:** I didn't check Seedance's current policy on rendering real people.
  The prompts describe "the man in the navy quarter-zip" from behind or in silhouette. If you want
  his face, use a licensed reference or a lookalike, and expect it may be refused.
- **No real logos:** "royal blue and white" stands in for Mavericks branding, and the elephant and
  donkey stand in for the parties. That avoids trademark renders. Swap them in during the edit if you have rights.
- **Text rendering:** Seedance renders text unreliably, so the receipt shows "columns of figures"
  and "medical charges", not readable lines. Add real Cuban quotes as burned-in supers in the edit
  (for example "The math is the math." / "Name the carrier." / "Enough."). Use quotes you've checked
  against his actual posts.
- **Continuity anchors:** the same wardrobe, receipt strip, 5-hole punch row, and amber/cyan palette
  appear in every prompt. If you have a start-frame or reference-image slot, feed the last frame of
  each segment into the next one.
