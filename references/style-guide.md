# TNM 視覺風格指南

## 即時參考網站

**https://kq-bee.tnm.de5.net**

此站為本風格的完整實作，開發時請以此為視覺與語氣的 ground truth。

## 字體

優先順序：

```css
font-family: "PMingLiU", "新細明體", "MingLiU", "Microsoft JhengHei", serif;
```

- Windows 繁體中文系統幾乎都有 PMingLiU / 新細明體
- 沒有時 fallback 到 Microsoft JhengHei 或系統 serif
- 字重保持 normal，不要用 bold 當主體

## 色彩

| 用途 | 色碼 |
|------|------|
| 背景 | `#ffffff` |
| 文字 | `#000000` |
| 次要文字 | `#555` / `#444` / `#666` |
| 主按鈕 | `#111` → hover `#333` |
| Discord 按鈕 | `#5865F2` → hover `#4752C4` |
| 強調底色 | `#fff3cd` |
| Rant 底色 | `#f8f8f8` |
| 分隔線 | `#ddd` / `#eee` |

## 版面原則

- 內容最大寬度約 520–680px，置中
- 上下留白充足（padding 30px 20px 40px）
- section 之間用 margin 分開，標題下方加細線
- 文字左對齊（section 內），整體頁面置中
- 行高 1.6–1.7，閱讀舒適

## 元件

### 主按鈕
- 黑底白字
- padding 較大（16px 36px）
- 圓角 6px
- active 時 scale(0.97)

### Rant 區塊
- 左邊 4px 黑色邊框
- 淺灰背景
- 用來放強烈吐槽或範例台詞

### Tag
- 黑底白字小標籤
- 圓角 3px
- 適合列出特徵

### 頁尾
- 上方細線分隔
- 字級略小
- 版權文字再更小、灰色

## 動畫

- 按鈕 hover / active 用簡單 transition
- 表情區用 opacity 淡入
- 不要過度動畫，保持乾淨
