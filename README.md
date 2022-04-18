# Gittest

EditOrCreateWord.vue
```
จะทำการเรียกใช้ component ดังต่อไปนี้คือ InsertWord.vue และ ListWord.vue คือทำการรับคำศัพที่ถูกเพิ่ม้ข่ามาใหม่จาก InsertWord.vue 
มาเพื่อเพิ่มลงใน listword และส่งต่อ listword ไปที่ component  ListWord.vue เพื่อแสดงผล  
และใน component นี้ยังมีการทำงานที่เกี่ยวการให้ตั้งชื่อของ deck (ชื่อชุดคำศัพท์) เมื่อมีการสร้าง deck 
ใหม่ขึ้นมา(การสร้างdeck ใหม่ คือการที่ตัวแปร status ซึ่งรับเข้ามาจาก Home.vue มีค่าเป็น create ) และมีปุ่ม save ซึ่งจะทำหน้าที่ในการ save 
ข้อมูลรายการคำศัพท์ที่ถูกเพิ่มเข้ามาใหม่จากการทำงานของ InsertWord.vue ลงใน database
และมีการใช้งาน api dictionaryapi ใน function เพื่อทำการค้นหาและกำหนดคำอธิบาบให้กับคำศัพท์ต่างๆที่ถูก add เข้ามา
```
