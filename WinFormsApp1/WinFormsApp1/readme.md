by kittisak kankaeng,
673450031-4,
Computer and Infomation Science, KKU

# การรับและการแสดงผลข้อมูล

รับข้อมูลจากผู้ใช้งาน และทำงานผ่านการกดปุ่มเพื่อคำนวนตัวเลข


## ปุ่มบวก


```
private void button1_Click(object sender, EventArgs e)
{
    // ข้อความตัวอักษร
    string inputNum1 = num1.Text;
    string inputNum2 = num2.Text;
    // convert string to number (integer)
    int iNum1 = Int32.Parse(inputNum1);
    int iNum2 = Int32.Parse(inputNum2);
    // int ทำให้เราสามารถทำการ + - * / ได้
    int iResult = iNum1 + iNum2;
    // ที่ตัวแปรชื่อ result
    // มีคุณสมบัติชื่อ Text
    result.Text = iResult.ToString();
}
```

### รับข้อมูล

ตัวอย่าง

```
string input = num1.Text();-
```

### แปลงชนิดของข้อมูล

ตัวอย่าง

```
float input1 = float.Parse(inputnum1);
float input2 = float.Parse(inputnum2);
```

### คำนวนผลลัพท์

ตัวอย่าง

```
float result1 = input1 * input2;
```

### แสดงผล

ตัวอย่าง

```
result.Text = result1.ToString();
```

## ปุ่มลบ
  private void button2_Click(object sender, EventArgs e)
  {
      string inputnum1 = Num1.Text;
      string inputnum2 = Num2.Text;
      float input1 = float.Parse(inputnum1);
      float input2 = float.Parse(inputnum2);
      float result1 = input1 - input2;
      result.Text = result1.ToString();
  }
## ปุ่มคูณ
private void button3_Click(object sender, EventArgs e)
{
    string inputnum1 = Num1.Text;
    string inputnum2 = Num2.Text;
    float input1 = float.Parse(inputnum1);
    float input2 = float.Parse(inputnum2);
    float result1 = input1 * input2;
    result.Text = result1.ToString();
            }

## ปุ่มหาร
  private void button4_Click(object sender, EventArgs e)
  {
      string inputnum1 = Num1.Text;
      string inputnum2 = Num2.Text;
      float input1 = float.Parse(inputnum1);
      float input2 = float.Parse(inputnum2);
      float result1 = input1 / input2;
      result.Text = result1.ToString();
  }
## ปุ่มลบข้อมูล
        private void button5_Click(object sender, EventArgs e)
        {
            Num1.Clear();
            Num2.Clear();
            result.Clear();
        }
    