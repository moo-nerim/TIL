# 06.26 ๐
### console ์ฐฝ์ ์ถ๋ ฅ
* Console.WriteLine("Hello C#"); -> ํ ์ค์ฉ ์ถ๋ ฅ
* Console.Write("Hello C#"); -> ์ด์ด์ ์ถ๋ ฅ

### Textbox ์ฌ์ฉ
* HelloLabel.Text = "";

### int -> string
* int๋ณ์.ToString();

### string -> int
* int num1 = Convert.ToInt32(sum1.Text);

### ์ฌ์ฉ์์๊ฒ ์๋ฆผ์ฐฝ ๋์ฐ๊ธฐ
* MessageBox.Show("์ซ์๋ฅผ ์๋ ฅํด์ฃผ์ธ์.");

### ์๋ ฅ์นธ์ ํฌ์ปค์ค(์ฌ์ฉ์ ๋ฐฐ๋ ค)
* sum1.SelectAll();
sum1.Focus();

### ๋ฌธ์์ด์ null ๋๋ ๊ณต๋ฐฑ ํ์ธ
* string.IsNullOrWhiteSpace(sum1.Text);

### ๋ฌธ์์ด์ int๋ก ๋ฐ๊ฟ ์ ์๋์ง ํ์ธ
* if (int.TryParse(sum1.Text, out num1) == false )
* sum1.Text๋ฅผ intํ์ผ๋ก ๋ฐ๊ฟ์ out ํ์์ num1์ ์ ์ฅ

# 06.27 ๐
### enum class (์ด๊ฑฐํ ํด๋์ค)
* ํํ -> public enum Operators { Add, Sub, Multi, Div }
* ์ ์ํ ์์์ ์ด๋ฆ์ ๋ถ์ฌ์ ์ฝ๋๋ฅผ ์ดํดํ๊ธฐ ์ฝ๊ฒ ํด์ค
### object sender
* ์ด๋ฒคํธ ๋ฐ์ ๊ฐ์ฒด
โณ ์ฌ์ฉ๋ฒ : 
Button numButton = (Button)sender;
SetNum(numButton.Text);
### string -> int ํ๋ณํ
* int num = int.Parse(NumScreen.Text);
* int num = Convert.ToInt32(NumScreen.Text);