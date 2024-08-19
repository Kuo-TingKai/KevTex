# KevTex

A Tex Editor for helping mathematicians/physicists to derive and verify the formulae.

![image](https://github.com/user-attachments/assets/58468526-688d-42e9-acf6-a441574ae5bf)

## Todo

### Formula Moduler
當選取公式渲染結果區域中，公式的其中一部份，可以將選中的部分存為一個"公式模組"，公式模組擁有以下功能:
- "定義"是替選中的公式部分定義一個化簡版的公式答案，此答案是一個函數，同樣也是latex格式。此函數需要指定特定的變數輸入，並且可以保存為新的"公式模組"。
- "替換"是能夠將選中的公式區域用已經保存過的"公式模組"來替換。

### Math Obj Hinter
- 公式中的變數以及模組可以自行定義物件類型，並且滑鼠滑過去會出現自動提示。
- 更進階的功能是希望編輯器在遇見兩(多)種物件類型的模式時，可以自動推論這些模組合併之後的物件類型and/or接下來要做的運算操作。
