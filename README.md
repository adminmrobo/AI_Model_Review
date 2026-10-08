# AI Model Review — 딥러닝 A to Z

[한국어](#한국어) · [English](#english) · [中文](#中文) · [日本語](#日本語) · [Oʻzbekcha](#oʻzbekcha) · [Русский](#русский)

---

## 한국어

AI의 작동 원리부터 신경망의 부품, 이미지·음성·텍스트·시계열 데이터, 순서 모델, 어텐션·트랜스포머까지 여덟 편의 웹 페이지로 배운다. 버튼을 눌러 그림과 숫자를 바꿔 보며 읽는다. 글 안상선 ((주)M-Robo 대표).

**웹으로 보기:** `https://<깃허브아이디>.github.io/AI_Model_Review/`

### 언어

모든 페이지는 한국어가 기본이며 영어·중국어·일본어·우즈베크어·러시아어로 볼 수 있다.

- **자동 전환:** 한국어 페이지에 처음 들어오면 브라우저 언어를 읽어 해당 언어 페이지로 자동으로 옮겨 간다(지원하지 않는 언어는 한국어 그대로).
- **직접 고르기:** 모든 페이지 오른쪽 아래의 🌐 버튼에서 언어를 고른다. 고른 언어는 브라우저에 기억된다.
- **주소로 지정:** `?lang=en` 처럼 붙이면 그 언어로 연다 (`ko`, `en`, `zh`, `ja`, `uz`, `ru`).
- 3-5 텍스트 편은 한국어 문장을 토큰으로 바꾸는 과정을 보여 주므로, 어느 언어로 보아도 예시 문장과 토큰은 한국어로 남는다.

### 편 목록

| 편 | 파일 | 내용 |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | AI는 어떻게 작동하나 |
| 3-2 | `3-2_building_blocks.html` | 신경망의 부품 |
| 3-3 | `3-3_image_cnn.html` | 이미지와 CNN |
| 3-4 | `3-4_speech.html` | 음성 |
| 3-5 | `3-5_text.html` | 텍스트 |
| 3-6 | `3-6_timeseries_stock.html` | 시계열·주가 (교육용 예시, 투자 조언 아님) |
| 3-7 | `3-7_sequence_models.html` | 순서 모델 |
| 3-8 | `3-8_attention_transformer.html` | 어텐션·트랜스포머 |

### 폴더 구조

```
AI_Model_Review/
├── index.html      첫 화면 (한국어)
├── 3-1 … 3-8 .html 각 편 (그림·코드가 모두 파일 안에 들어 있다)
├── answers.html    교육자용 정답
├── en/ zh/ ja/ uz/ ru/   같은 파일 이름의 영어·중국어·일본어·우즈베크어·러시아어판
├── code/           각 편의 Colab 코드 (.py)
├── README.md
├── LICENSE.md
└── .nojekyll
```

강사용 자료: 각 편의 확인 문제 채점 기준과 Colab 과제 예시 답안은 `answers.html`(교육자용 정답)에 있다.

### 라이선스

이 저작물(웹 페이지, 그림, 코드)은 [크리에이티브 커먼즈 저작자표시-비영리 4.0 국제 라이선스(CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.ko)로 공개한다.

- 비상업적 목적에 한해 자유롭게 공유하고 고쳐 쓸 수 있다.
- **출처를 반드시 표기**해야 한다. 표기 예: 안상선, 「딥러닝 A to Z · 3-1 AI는 어떻게 작동하나」, AI Model Review.
- 상업적 이용은 저작자의 별도 허락이 필요하다.

---

## English

Learn deep learning in eight interactive web pages — from how AI works, through the building blocks of neural networks, images, speech, text and time-series data, to sequence models, attention and Transformers. You read by pressing buttons and watching the pictures and numbers change. Written by Sangsun Ahn (CEO, M-Robo Inc.).

**View online:** `https://<github-id>.github.io/AI_Model_Review/en/`

### Languages

Korean is the default; every page is also available in English, Chinese, Japanese, Uzbek and Russian.

- **Automatic:** when you first open a Korean page, it reads your browser language and switches to that language (unsupported languages stay in Korean).
- **Manual:** pick a language from the 🌐 button at the bottom right of any page. Your choice is remembered in the browser.
- **By URL:** add `?lang=en` (`ko`, `en`, `zh`, `ja`, `uz`, `ru`).
- Part 3-5 (Text) shows how *Korean* sentences become tokens, so its example sentences and tokens stay in Korean in every language.

### Parts

| Part | File | Topic |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | How AI Works |
| 3-2 | `3-2_building_blocks.html` | Building Blocks of Neural Networks |
| 3-3 | `3-3_image_cnn.html` | Images and CNNs |
| 3-4 | `3-4_speech.html` | Speech |
| 3-5 | `3-5_text.html` | Text |
| 3-6 | `3-6_timeseries_stock.html` | Time Series & Stock Prices (educational example, not investment advice) |
| 3-7 | `3-7_sequence_models.html` | Sequence Models |
| 3-8 | `3-8_attention_transformer.html` | Attention & Transformers |

### Folder structure

```
AI_Model_Review/
├── index.html      landing page (Korean)
├── 3-1 … 3-8 .html each part (all images and code are embedded in the file)
├── answers.html    answer key for educators
├── en/ zh/ ja/ uz/ ru/   English, Chinese, Japanese, Uzbek and Russian versions (same file names)
├── code/           Colab code for each part (.py)
├── README.md
├── LICENSE.md
└── .nojekyll
```

For instructors: grading criteria for the check questions and sample solutions for the Colab assignments are in `answers.html` (answer key for educators).

### License

This work (web pages, images, code) is released under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.en).

- You may share and adapt it freely for non-commercial purposes.
- **Attribution is required.** Example: Sangsun Ahn, "Deep Learning A to Z · 3-1 How AI Works", AI Model Review.
- Commercial use requires separate permission from the author.

---

## 中文

用八个交互式网页学习深度学习：从 AI 的工作原理、神经网络的部件，到图像、语音、文本、时间序列数据，再到序列模型、注意力与 Transformer。按下按钮，看着图和数字变化来阅读。作者：Sangsun Ahn（M-Robo 公司代表）。

**在线浏览：** `https://<GitHub账号>.github.io/AI_Model_Review/zh/`

### 语言

默认语言为韩语，所有页面也提供英语、中文、日语、乌兹别克语和俄语版本。

- **自动切换：** 首次打开韩语页面时，会读取浏览器语言并自动跳转到对应语言（不支持的语言保持韩语）。
- **手动选择：** 在任意页面右下角的 🌐 按钮中选择语言，浏览器会记住你的选择。
- **通过网址指定：** 加上 `?lang=zh` 即可（`ko`、`en`、`zh`、`ja`、`uz`、`ru`）。
- 3-5「文本」篇演示的是*韩语*句子如何变成词元，因此无论用哪种语言浏览，示例句子和词元都保留韩语。

### 篇目

| 篇 | 文件 | 内容 |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | AI 是如何工作的 |
| 3-2 | `3-2_building_blocks.html` | 神经网络的部件 |
| 3-3 | `3-3_image_cnn.html` | 图像与 CNN |
| 3-4 | `3-4_speech.html` | 语音 |
| 3-5 | `3-5_text.html` | 文本 |
| 3-6 | `3-6_timeseries_stock.html` | 时间序列·股价（教学示例，非投资建议） |
| 3-7 | `3-7_sequence_models.html` | 序列模型 |
| 3-8 | `3-8_attention_transformer.html` | 注意力与 Transformer |

### 目录结构

```
AI_Model_Review/
├── index.html      首页（韩语）
├── 3-1 … 3-8 .html 各篇（图片和代码全部内嵌在文件中）
├── answers.html    教师用答案
├── en/ zh/ ja/ uz/ ru/   英语、中文、日语、乌兹别克语、俄语版本（文件名相同）
├── code/           各篇的 Colab 代码（.py）
├── README.md
├── LICENSE.md
└── .nojekyll
```

教师资料：各篇检测题的评分标准和 Colab 作业参考答案在 `answers.html`（教师用答案）中。

### 许可协议

本作品（网页、图片、代码）以[知识共享 署名-非商业性使用 4.0 国际许可协议（CC BY-NC 4.0）](https://creativecommons.org/licenses/by-nc/4.0/deed.zh-hans)发布。

- 仅限非商业目的，可自由分享和改编。
- **必须注明出处。** 示例：Sangsun Ahn，《深度学习 A to Z · 3-1 AI 是如何工作的》，AI Model Review。
- 商业使用需另行获得作者许可。

---

## 日本語

AIの仕組みからニューラルネットワークの部品、画像・音声・テキスト・時系列データ、系列モデル、アテンションとトランスフォーマーまで、8本のWebページで学びます。ボタンを押して図や数字を動かしながら読み進めます。文：Sangsun Ahn（株式会社M-Robo代表）。

**Webで見る：** `https://<GitHubのID>.github.io/AI_Model_Review/ja/`

### 言語

韓国語が基本で、すべてのページを英語・中国語・日本語・ウズベク語・ロシア語でも読めます。

- **自動切り替え：** 韓国語のページを初めて開くと、ブラウザの言語設定を読み取り、その言語のページへ自動で移動します（対応していない言語の場合は韓国語のまま）。
- **手動で選ぶ：** 各ページ右下の 🌐 ボタンから言語を選べます。選んだ言語はブラウザに記憶されます。
- **URLで指定：** `?lang=ja` のように付けるとその言語で開きます（`ko`、`en`、`zh`、`ja`、`uz`、`ru`）。
- 3-5「テキスト」回は*韓国語*の文がトークンになる過程を見せるため、どの言語で読んでも例文とトークンは韓国語のままです。

### 回の一覧

| 回 | ファイル | 内容 |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | AIはどう動くのか |
| 3-2 | `3-2_building_blocks.html` | ニューラルネットワークの部品 |
| 3-3 | `3-3_image_cnn.html` | 画像とCNN |
| 3-4 | `3-4_speech.html` | 音声 |
| 3-5 | `3-5_text.html` | テキスト |
| 3-6 | `3-6_timeseries_stock.html` | 時系列・株価（教育用の例であり、投資助言ではありません） |
| 3-7 | `3-7_sequence_models.html` | 系列モデル |
| 3-8 | `3-8_attention_transformer.html` | アテンションとトランスフォーマー |

### フォルダ構成

```
AI_Model_Review/
├── index.html      トップページ（韓国語）
├── 3-1 … 3-8 .html 各回（図とコードはすべてファイル内に埋め込み）
├── answers.html    教育者用解答
├── en/ zh/ ja/ uz/ ru/   英語・中国語・日本語・ウズベク語・ロシア語版（ファイル名は同じ）
├── code/           各回のColabコード（.py）
├── README.md
├── LICENSE.md
└── .nojekyll
```

講師向け資料：各回の確認問題の採点基準とColab課題の解答例は `answers.html`（教育者用解答）にあります。

### ライセンス

この著作物（Webページ、図、コード）は[クリエイティブ・コモンズ 表示-非営利 4.0 国際ライセンス（CC BY-NC 4.0）](https://creativecommons.org/licenses/by-nc/4.0/deed.ja)で公開しています。

- 非営利目的に限り、自由に共有・改変できます。
- **出典の表示が必要です。** 表示例：Sangsun Ahn「ディープラーニング A to Z · 3-1 AIはどう動くのか」、AI Model Review。
- 商用利用には著作者の別途許可が必要です。

---

## Oʻzbekcha

Chuqur oʻrganishni sakkizta interaktiv veb-sahifa orqali oʻrganing: AI qanday ishlashidan boshlab neyron tarmoq qismlari, tasvir, nutq, matn va vaqt qatorlari maʼlumotlari, ketma-ketlik modellari, attention va Transformergacha. Tugmalarni bosib, rasmlar va raqamlar oʻzgarishini kuzatgan holda oʻqiysiz. Muallif: Sangsun Ahn (M-Robo MChJ rahbari).

**Internetda koʻrish:** `https://<github-id>.github.io/AI_Model_Review/uz/`

### Tillar

Asosiy til — koreys tili; barcha sahifalar ingliz, xitoy, yapon, oʻzbek va rus tillarida ham mavjud.

- **Avtomatik:** koreyscha sahifani birinchi marta ochganingizda brauzer tili aniqlanadi va sahifa oʻsha tilga oʻtadi (qoʻllab-quvvatlanmaydigan tillarda koreyscha qoladi).
- **Qoʻlda tanlash:** istalgan sahifaning pastki oʻng burchagidagi 🌐 tugmasidan tilni tanlang. Tanlovingiz brauzerda saqlanadi.
- **Manzil orqali:** `?lang=uz` qoʻshing (`ko`, `en`, `zh`, `ja`, `uz`, `ru`).
- 3-5 «Matn» qismi *koreyscha* gaplar tokenlarga qanday aylanishini koʻrsatadi, shuning uchun misol gaplar va tokenlar har qanday tilda koreyscha qoladi.

### Qismlar

| Qism | Fayl | Mavzu |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | AI qanday ishlaydi |
| 3-2 | `3-2_building_blocks.html` | Neyron tarmoq qismlari |
| 3-3 | `3-3_image_cnn.html` | Tasvirlar va CNN |
| 3-4 | `3-4_speech.html` | Nutq |
| 3-5 | `3-5_text.html` | Matn |
| 3-6 | `3-6_timeseries_stock.html` | Vaqt qatorlari va aksiya narxlari (oʻquv misoli, investitsiya maslahati emas) |
| 3-7 | `3-7_sequence_models.html` | Ketma-ketlik modellari |
| 3-8 | `3-8_attention_transformer.html` | Attention va Transformer |

### Papka tuzilishi

```
AI_Model_Review/
├── index.html      bosh sahifa (koreyscha)
├── 3-1 … 3-8 .html har bir qism (barcha rasmlar va kod fayl ichida)
├── answers.html    oʻqituvchilar uchun javoblar
├── en/ zh/ ja/ uz/ ru/   ingliz, xitoy, yapon, oʻzbek va rus tilidagi versiyalar (fayl nomlari bir xil)
├── code/           har bir qismning Colab kodi (.py)
├── README.md
├── LICENSE.md
└── .nojekyll
```

Oʻqituvchilar uchun: har bir qismdagi tekshiruv savollarining baholash mezonlari va Colab topshiriqlarining namunaviy yechimlari `answers.html` (oʻqituvchilar uchun javoblar) faylida.

### Litsenziya

Ushbu asar (veb-sahifalar, rasmlar, kod) [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.en) litsenziyasi ostida eʼlon qilingan.

- Faqat notijorat maqsadlarda erkin tarqatish va oʻzgartirish mumkin.
- **Manbani albatta koʻrsating.** Misol: Sangsun Ahn, «Chuqur oʻrganish: A dan Z gacha · 3-1 AI qanday ishlaydi», AI Model Review.
- Tijorat maqsadida foydalanish uchun muallifning alohida ruxsati kerak.

---

## Русский

Глубокое обучение в восьми интерактивных веб-страницах: от того, как работает ИИ, через детали нейросети, изображения, речь, текст и временные ряды — к последовательным моделям, вниманию и трансформерам. Вы читаете, нажимая кнопки и наблюдая, как меняются рисунки и числа. Автор: Сансон Ан (генеральный директор M-Robo).

**Смотреть онлайн:** `https://<github-id>.github.io/AI_Model_Review/ru/`

### Языки

Основной язык — корейский; все страницы доступны также на английском, китайском, японском, узбекском и русском.

- **Автоматически:** при первом открытии корейской страницы определяется язык браузера, и страница переключается на него (для неподдерживаемых языков остаётся корейский).
- **Вручную:** выберите язык кнопкой 🌐 в правом нижнем углу любой страницы. Выбор запоминается в браузере.
- **Через адрес:** добавьте `?lang=ru` (`ko`, `en`, `zh`, `ja`, `uz`, `ru`).
- Часть 3-5 «Текст» показывает, как *корейские* предложения превращаются в токены, поэтому примеры предложений и токены остаются на корейском на любом языке.

### Части

| Часть | Файл | Тема |
|---|---|---|
| 3-1 | `3-1_how_ai_works.html` | Как работает ИИ |
| 3-2 | `3-2_building_blocks.html` | Детали нейросети |
| 3-3 | `3-3_image_cnn.html` | Изображения и CNN |
| 3-4 | `3-4_speech.html` | Речь |
| 3-5 | `3-5_text.html` | Текст |
| 3-6 | `3-6_timeseries_stock.html` | Временные ряды и цены акций (учебный пример, не инвестиционный совет) |
| 3-7 | `3-7_sequence_models.html` | Последовательные модели |
| 3-8 | `3-8_attention_transformer.html` | Внимание и трансформеры |

### Структура папок

```
AI_Model_Review/
├── index.html      главная страница (корейский)
├── 3-1 … 3-8 .html части курса (все рисунки и код встроены в файл)
├── answers.html    ответы для преподавателей
├── en/ zh/ ja/ uz/ ru/   версии на английском, китайском, японском, узбекском и русском (те же имена файлов)
├── code/           код Colab для каждой части (.py)
├── README.md
├── LICENSE.md
└── .nojekyll
```

Для преподавателей: критерии оценки проверочных вопросов и примеры решений заданий Colab — в `answers.html` (ответы для преподавателей).

### Лицензия

Это произведение (веб-страницы, рисунки, код) распространяется по [лицензии Creative Commons «Атрибуция — Некоммерческое использование» 4.0 Международная (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/deed.ru).

- Свободно делиться и переделывать можно только в некоммерческих целях.
- **Указание авторства обязательно.** Пример: Сансон Ан, «Глубокое обучение от A до Z · 3-1 Как работает ИИ», AI Model Review.
- Коммерческое использование требует отдельного разрешения автора.
