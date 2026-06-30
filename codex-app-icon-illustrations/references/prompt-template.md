# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean product-sketch feeling. No shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no cute mascot poster, no children's illustration, no realistic UI screenshot.

Recurring character required:
A living Codex desktop app icon character: white rounded-square app tile body, blue-purple cloud core, simple terminal glyph ">_" inside the cloud, tiny functional stick arms and feet. The character must perform the core conceptual action, not decorate the scene. It should read as a hand-drawn course illustration character inspired by the Codex desktop app icon, not a polished official logo export.

Theme:
{正文配图主题}

Structure type:
{结构类型：工作流 / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：Codex App 图标角色在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art. Blue-purple only for the app-icon cloud core and small system notes. Orange for main flow/path/arrows. Red only for key warnings/problems/results.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, or dense explainer. Do not draw a black creature mascot. Do not draw a realistic app screenshot. Avoid third-party platform logos unless explicitly requested. Invent a fresh visual metaphor for this specific article. It should be clear but not instructional, interesting but not childish, strange but clean.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: character, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强角色参与感：

```text
Regenerate this illustration with the same core meaning and simple layout, but make the Codex App icon character more central to the conceptual action. It should do the work that explains the idea, not stand beside the diagram. Keep the white rounded-square body, blue-purple cloud core, and ">_" glyph recognizable. Keep it clean, sparse, hand-drawn, and not cute.
```
