# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art with a few restrained color fills. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling with mischievous childlike humor. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
An original mischievous kid character inspired by the playful, absurd, deadpan spirit of a crayon-drawn naughty child. Short child body, oversized head, expressive thick eyebrows, big simple eyes, cheeky but innocent expression, simple original clothes. The character must perform the core conceptual action, not decorate the scene. Keep the character original: do not draw Crayon Shin-chan, do not copy the official red shirt + yellow shorts outfit, do not copy the exact official face, hairstyle, proportions, pose, or protected design. Make the kid funny, serious about the strange task, and slightly bizarre, not cute.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：原创淘气小孩在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art and handwritten structure. Use restrained clothing colors that are not the official Crayon Shin-chan outfit. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. Do not generate official anime fan art or a recognizable copyrighted character. It should be clear but not instructional, funny but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: characters, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make the original mischievous kid more central to the conceptual action. The kid should be doing the strange work that explains the idea, not standing beside the diagram. Keep it clean, sparse, hand-drawn, funny, and not cute. Avoid any direct resemblance to official Crayon Shin-chan.
```
