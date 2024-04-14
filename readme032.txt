定義一個整數num，用 IntToRoman 方法將整數 num 轉換為羅馬數字，然後將結果儲存在 romannum中，再用Console.WriteLine(romannum);輸出結果。
定義一個 IntToRoman 方法，接收一個整數 num 作為參數，並輸出對應的羅馬數字。
定義兩個陣列 symbols 和 x，分別儲存羅馬數字符號和對應的數值，創立一個字串 roman用在最終的羅馬數字符號，然後使用 for 迴圈放入 symbols 陣列，再用 while 迴圈，當輸入的整數 num 大於等於 x[i] 時，將 symbols[i] 添加到 roman 中，同時減去對應的數值 x[i]，最後回傳到roman.ToString()。
