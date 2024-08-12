# Lccnet HTML 20240808

## 基本語法
```
<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

## 作業參考
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Document</title>
</head>
<body>
<div class="container">
    <header>
        Troie Pan
        Senior Product Designer
        <img src="" alt="">
    </header>
    <article>
        experience
        Senior UI/UX Product Designer
        Enterprise name
        Aug 2018 - Present - 1 year, Paris
        Directly collaborated with CEO and Product team to prototype, design and deliver the UI and UX experience with a lean design process: research, design, test, and iterate.

        UI/UX Product Designer
        Enterprise name
        Aug 2013 - Aug 2018 - 5 years, Paris
        Lead the UI design with the accountability of the design system, collaborated with product and development teams on core projects to improve product interfaces and experiences.

        UI Designer
        Enterprise name
        Aug 2012 - jul 2013 - 1 year, Paris
        Designed mobile UI applications for Orange R&D departement, BNP Paribas, La Poste, Le Cned...

        Graphic Designer
        Enterprise name
        Sept 2010 - jul 2012 - 2 years, Paris
        Designed print and web applications for Pau Brasil, Renault,
        Le théatre du Mantois, La mairie de Mantes la Ville...

        education
        Bachelor European in Graphic Design
        School name
        2009 - 2010, Bagnolet

        BTS Communication Visuelle option Multimédia
        School name
        2007 - 2009, Bagnolet
    </article>
    <aside>
        yourmail@gmail.com
        +33 6 33 33 33 33
        Vernouillet

        Industry Knowledge
        Product Design
        User Interface
        User Experience
        Interaction Design
        Wireframing
        Rapid Prototyping
        Design Research

        Tools & Technologies
        Figma, Sketch, Protopie, Framer, Invision, Abstract, Zeplin, Google Analytics, Amplitude, Fullstory...

        Other Skills
        HTML, CSS, jQuery

        Languages
        French (native)
        English (professionnal)

        Social
        yoursite.com
        linkedin.com/in/yourname
        dribbble.com/yourname
    </aside>
</div>
</body>
</html>
```
HTML 標題元素用於定義網頁中的標題或主題，它們用來組織內容，讓瀏覽器和用戶都能清楚地了解網頁結構。HTML 提供了六種標題元素，從 `<h1>` 到 `<h6>`，它們按照重要性依次遞減。

### HTML 標題元素

1. **`<h1>`** - 最高層級的標題，通常用於網頁或章節的主要標題。
   - 範例：
     ```html
     <h1>網站標題</h1>
     ```

2. **`<h2>`** - 用於次級標題，通常是 `<h1>` 標題下的子標題。
   - 範例：
     ```html
     <h2>章節標題</h2>
     ```

3. **`<h3>`** - 用於次級的子標題，通常用於 `<h2>` 標題下的更細分的標題。
   - 範例：
     ```html
     <h3>小節標題</h3>
     ```

4. **`<h4>`** - 用於 `<h3>` 標題下的進一步細分。
   - 範例：
     ```html
     <h4>段落標題</h4>
     ```

5. **`<h5>`** - 用於 `<h4>` 標題下的細分，較少使用，適合非常深入的分層內容。
   - 範例：
     ```html
     <h5>細節標題</h5>
     ```

6. **`<h6>`** - 最低層級的標題，通常用於 `<h5>` 標題下的內容。
   - 範例：
     ```html
     <h6>附加信息標題</h6>
     ```

#### 標題使用最佳實踐
- **語義結構**：標題應該按照層次結構合理使用，避免跳級（例如，直接從 `<h1>` 跳到 `<h4>`），這樣有助於維持清晰的文檔結構。
- **SEO 影響**：搜索引擎依賴標題來理解內容的結構和主題，因此合理使用標題標籤有助於 SEO。
- **可訪問性**：正確的標題結構可以幫助使用屏幕閱讀器的用戶更好地導航和理解網頁內容。

#### 其他注意事項
- 每個頁面通常只應有一個 `<h1>` 標題，作為頁面的主標題。
- 標題不僅影響頁面結構，還會影響瀏覽器默認樣式和搜索引擎優化，因此使用時應該謹慎。

這些標題標籤在 HTML 中是必不可少的，因為它們定義了內容的層次結構，使頁面更易於閱讀和理解。

HTML 中的段落是由 `<p>` 標籤定義的。每個 `<p>` 標籤都表示一個獨立的段落，瀏覽器會自動在段落前後添加空白間距，以便更清晰地顯示文本。

### HTML 段落基本用法
- **定義段落**：使用 `<p>` 標籤來包裹段落文本。
  - 範例：
    ```html
    <p>這是一個段落。</p>
    ```

#### 段落標籤的特點
- **自動換行**：當文本內容超過容器的寬度時，瀏覽器會自動將文本換行。
- **多段落**：可以使用多個 `<p>` 標籤來定義多個段落，每個段落都是獨立的文本區塊。
  - 範例：
    ```html
    <p>這是第一個段落。</p>
    <p>這是第二個段落。</p>
    ```

#### 段落中的其他元素
- **內嵌元素**：段落內可以包含其他內嵌元素，如 `<a>`、`<strong>`、`<em>` 等，用來增加超連結、強調文本或斜體字等。
  - 範例：
    ```html
    <p>這是一個包含 <strong>強調文本</strong> 和 <a href="#">連結</a> 的段落。</p>
    ```

#### 其他注意事項
- **段落內不能嵌套段落**：HTML 規範不允許段落內嵌套其他段落標籤。
- **語義化**：正確使用 `<p>` 標籤可以增強文檔的語義化，使搜索引擎和輔助技術更容易理解內容結構。

段落是 HTML 中最基本的文本區塊元素之一，使用正確的 `<p>` 標籤來組織內容，有助於提升網頁的可讀性和結構清晰度。

在 HTML 中，文字修飾主要是通過一系列標籤和 CSS 屬性來實現的。這些修飾可以改變文本的外觀，例如粗體、斜體、下劃線等。以下是一些常見的 HTML 文字修飾方式：

### HTML 修飾標籤
#### 1. **粗體文字 (`<strong>` 和 `<b>`)**
- **`<strong>`**：表示語義上重要的文字，通常顯示為粗體。
  - 範例：
    ```html
    <p>這是一個<strong>重要的</strong>段落。</p>
    ```
- **`<b>`**：僅用來使文字顯示為粗體，沒有語義上的強調。
  - 範例：
    ```html
    <p>這是一個<b>粗體</b>文字。</p>
    ```

#### 2. **斜體文字 (`<em>` 和 `<i>`)**
- **`<em>`**：表示強調的文字，通常顯示為斜體，具有語義上的強調意義。
  - 範例：
    ```html
    <p>這是一個<em>強調</em>的段落。</p>
    ```
- **`<i>`**：僅用來使文字顯示為斜體，沒有語義上的強調。
  - 範例：
    ```html
    <p>這是一個<i>斜體</i>文字。</p>
    ```

#### 3. **下劃線文字 (`<u>`)**
- **`<u>`**：將文字顯示為帶有下劃線的形式。通常用於表示文本是超連結的一部分，但也可以用來標示需要注意的文字。
  - 範例：
    ```html
    <p>這是一個<u>帶下劃線</u>的文字。</p>
    ```

#### 4. **刪除線文字 (`<del>` 和 `<s>`)**
- **`<del>`**：表示被刪除的文本，通常顯示為帶刪除線的形式，適合在修訂過的文檔中標示被刪除的部分。
  - 範例：
    ```html
    <p>這是一個<del>刪除</del>的文字。</p>
    ```
- **`<s>`**：通常用於標示不再準確或不再相關的文本，顯示為刪除線。
  - 範例：
    ```html
    <p>這是一個<s>過時</s>的文字。</p>
    ```

#### 5. **下標與上標文字 (`<sub>` 和 `<sup>`)**
- **`<sub>`**：將文字顯示為下標，通常用於數學公式或化學符號。
  - 範例：
    ```html
    <p>H<sub>2</sub>O 是水的化學式。</p>
    ```
- **`<sup>`**：將文字顯示為上標，通常用於指數或註解。
  - 範例：
    ```html
    <p>2<sup>nd</sup> 是第二的縮寫。</p>
    ```

#### 6. **等寬字體 (`<code>` 和 `<pre>`)**
- **`<code>`**：用來標示程式碼片段，顯示為等寬字體，適合在文檔中標示代碼。
  - 範例：
    ```html
    <p>請使用 <code>console.log()</code> 來輸出訊息。</p>
    ```
- **`<pre>`**：保留文字中的所有空格和換行，並以等寬字體顯示，適合用來顯示格式化的文本，如程式碼段落。
  - 範例：
    ```html
    <pre>
function test() {
    console.log("Hello, world!");
}
    </pre>
    ```

#### 7. **引用 (`<blockquote>` 和 `<q>`)**
- **`<blockquote>`**：用來標示一段較長的引用，通常會增加縮排。
  - 範例：
    ```html
    <blockquote>
      這是一段引用的文字，來自某個來源。
    </blockquote>
    ```
- **`<q>`**：用來標示行內引用，通常會加上引號。
  - 範例：
    ```html
    <p>莎士比亞說過：<q>人生如戲。</q></p>
    ```

#### 8. **強調 (`<mark>`)**
- **`<mark>`**：用來高亮顯示文字，表示它在上下文中有重要性或相關性。
  - 範例：
    ```html
    <p>這是一個<mark>高亮顯示</mark>的文字。</p>
    ```

這些 HTML 標籤可以幫助你有效地修飾網頁中的文字，使其更具可讀性和結構性。同時，使用這些標籤還能提升網頁的語義化和可訪問性。
