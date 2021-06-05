## homework

## 註冊系統

題目:
註冊開始
是否結束(y/n):n
請輸入學生姓名:小王
是否結束(y/n):n
請輸入學生姓名:小李
是否結束(y/n):p
輸入錯誤請輸入y/n:y
註冊結束
班級共2人,名稱為小王 小李'''


```print('註冊開始')

student_list=[]
while True:
  enter = input('是否結束(y/n)')
  if enter in ['n']:
      student = input('請輸入姓名:')
      student_list.append(student)
  elif enter in ['y']:
        print('註冊結束')
        print('班級總人數共',(len(student_list)),'人','名稱:',student_list[:])
        break
        student_list=False
  else:
      print('輸入錯誤!請輸入Y/N')```

註冊開始
是否結束(y/n)n
請輸入姓名:小小
是否結束(y/n)ㄙ
輸入錯誤!請輸入Y/N
是否結束(y/n)n
請輸入姓名:大大
是否結束(y/n)y
註冊結束
班級總人數共 2 人 名稱: ['小小', '大大']

---
