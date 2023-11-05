Introduction to Spreadsheets 
ตัวที่โคตร popular ก็จะมี google sheets, microsoft excel 
what spreadsheets can do = store - analyze - present 
แต่ task ที่เหมาะกับ spreadsheets ที่สุดคือขั้น analyze (อย่างสายเศรษฐศาสตร์ที่ทำงานธนาคาร เคยได้ยินมาว่าเค้าเก็บ data ไว้ที่อื่น excel แค่ไว้ดูดมาส่วนนึงเพื่อมาทำ math model เฉย ๆ) 
  สำหรับสาย data spreasheets เป็น skill prerequisite ที่จะไม่อยู่ใน resume ด้วยซ้ำ แต่ต้องแข็งแกร่งอยู่แล้ว 
row = x-axis, column = y-axis ("คอตั้ง") 

Function 
function_name(required_argument_1, required_argument_2, optional_argument) 
IF(condition, true, false) 
กด alt+enter เพื่อขึ้นบรรทัดใหม่ในการเขียน function เป็นเรื่องที่ควรทำเพื่อให้ code มันอ่านง่าย ๆ 
การเก็บข้อมูลเป็น array 

filter(dataset, condition) ex.FILTER(employee, salary<100000) 
=QUERY(dataset, SQL-liked Syntax) ex.=QUERY( employee, “select *” )
=SORT(dataset, column_to_sort, ascending) ex.SORT(employee, salary, descending) 
we can join table with id 
=VLOOKUP(id, look_up_table, columns_you_want, exact_match?) 
REGEXMATCH 
REGEXEXTRACT 

ctrl+k เพื่อสร้าง hyperlink 
