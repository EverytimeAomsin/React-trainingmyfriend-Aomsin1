***เพื่อนคนไหนสงสัย ถามเราได้เลยนะ
React คือ Javascipt library ที่สร้างโดย Facebook มีหน้าที่สร้างส่วนแสดงผล โดยอาศัย Js ที่เรียกว่า JSX โดยใช้หลักการแบ่งแยกออกเป็นส่วนๆที่เรียกว่า คอมโพเนนท์ แล้วนำมาประกอบกัน

*****ก่อนใช้งาน React ต้องติดตั้ง Node ก่อนซึ่งสามารถโหลดได้ที่ https://nodejs.org/en/

สำหรับการใช้งาน React.js เราจะใช้ create-react-app 
1.เปิด cmd  แล้ว cd เลือกพื้นที่จะสร้างโปรเจ็ค
2.ในการติดตั้งสามารถใช้คำสั้งได้ทั้ง npm และ yarn 
 yarn จะใช้
  1.yarn global add create-react-app
  2.create-react-app เขียนชื่อโปรเจ็คที่เราต้องการไป เช่น create-react-app test
  3.cd เขียนชื่อโปรเจ็คของเราไป
  4.yarn start
 npm จะใช้
  1.npx create-react-app เขียนชื่อโปรเจ็คที่เราต้องการไป
  2.cd เขียนชื่อโปรเจ็คของเราไป
  3.npm start
เมื่อรันแล้ว มันจะเปิดหน้าเว็บเราให้อัตโนมัติ โดย default แล้วจะเป็น http://localhost:3000


คือวิธีการดู library เราสามารถดูได้ที่ไฟล์ package.json หรือแม้แต่ตัว ver react เองก็ดูได้ที่ไฟล์นี้ที่หัวข้อ dependencies

เริ่มแรกตัวเริ่มต้น ไฟล์ต่างๆจะมี 
public/index.html : คือไฟล์ html หลักของเรา
src/index.js : เป็นไฟล์หลักของ React
src/App.js : ไฟล์สำหรับ Component ที่ชื่อว่า App

เราจะมาลองเปลี่ยนหน้าเริ่มต้นของเว็บเรากัน
ไปที่ src/App.js
เราสามารถเปลียนหน้าตาเว็บได้โดยแก้ 
return(
 
 ....แก้ตรงนี้....
 
)
