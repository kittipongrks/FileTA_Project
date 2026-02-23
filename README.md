# Repo นี้สำหรับการใช้งานใน Dify


## File(H)
#### แยกเป็น 2 Chatbot
  - Herb_Chatbot
      - RAG_file
        สามารถปรับเปลี่ยนข้อมูลได้ ตอนนี้ Chatbot_herb ยังไม่สมบูรณ์มาก
      - Flow_Dify
        ไม่ซับซ้อน
  - TA_Chatbot
      - RAG_file
        แยกเป็น 2 อัน ได้แก่
        1.)แบบสุ่มจะใช้ RAG ที่เป็น Vector
        2.)แบบดูจากคำตอบของ User จะใช้ RAG ที่เป็น Hybrid
      - Flow_Dify
        ซับซ้อนนิดหน่อยสามารถเขียน Flow ได้ตาม Diagram นี้
        ![Flow Chatbot TA](File(H)/TA_Chatbot/Flow_Dify/ภาพการทำงานของระบบโดยรวม.png)

        Flow หมายเลข 4 จะไปทำการทำงานของ ไฟล์ Project ฝึกงาน(พี).zip
# Repo สำหรับเชื่อม Dify กับ Flutter
  
  - https://github.com/kittipongrks/Chatbot-TA-project
