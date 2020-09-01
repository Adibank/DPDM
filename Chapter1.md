# บทที่ 1 Introduction
## ทำไม Data Mining ถึงมีความสำคัญ?
### Data is a new oil. 
It means "Data in the 21st Century is like oil in the 18th Century". ("รัฐมนตรีว่าการกระทรวงพลังงาน ได้เปรียบเทียบข้อมูล (Data) ว่า Data is the New Oil คือ ข้อมูลกลายเป็นพื้นฐานหลักในการผลักดันเศรษฐกิจยุคดิจิทัล ซึ่งมีลักษณะเดียวกับแหล่งน้ำมันดิบในอดีตที่ถือเป็นทรัพยากรที่มีค่า")
- - -
#### Terabytes(เทระไบต์) = 1024 gigabytes.
#### Petabytes(เพตาไบต์) = 1024 terabypes.
- - -
## Data Mining คืออะไร?
Data Mining คือ การสกัดเอาความรู้ที่ซ่อนอยู่ในข้อมูลออกมา หรือการทำเหมืองข้อมูล 
- - -
## ภาพรวมการทำเหมืองแร่ข้อมูล
* ขั้นแรก เริ่มจาก Database ผ่าน Data Cleaning หรือ Data Integration(จัดให้ข้อมูลให้เป็นรูปแบบเดียวกันหลังจากนั้นจึงนำข้อมูลมารวบรวมกัน) -> Data Warehouse (คลังของข้อมูลที่ผ่านกระบวนการสารสนเทศแล้ว และได้รับการออกแบบมาเพื่อจัดเก็บข้อมูลที่ปริมาณมาก เป็นฐานข้อมูลขนาดใหญ่ที่เก็บรวบรวมข้อมูลจากหลายแหล่งขององค์กรทั้งหมด ตั้งแต่อดีตจนถึงปัจจุบันโดยข้อมูลที่เก็บจะต้องเป็นข้อมูลสารสนเทศ (Data Information)) -> Task-relevant Data ผ่าน Data Mining -> Pattern Evaluation -> Knowledge
* Database -> Clean, Integrate, Transform (ตัวอย่าง แปลงเป็นฐานสอง), Load, Refresh -> Data Warehouse -> Query and Analysis Tools -> Client(ผู้ใช้บริการ)
- - -
## What kinds of data?
  * Data streams and sensor data (ที่มาเรื่อย ๆ เป็นแบบกระแส)
  * Time series data (ที่ขึ้นอยู่กับเวลา)
  * Structure data, graphs (ที่มีลักษณะเป็นกราฟ เช่น ข้อมูลของเราที่เชื่อมต่อกับข้อมูลของเพื่อนแตกออกไปเรื่อย ๆ), social networks and information networks
  * Spatial data (ที่เป็นข้อมูลเชิงพื้นที่) และ Spatiotemporal data (เช่น คลิปวิดีโอ)
  * Multimedia database (วีดีโอบนยูทูป like, comment, view ผู้ใช้บริการชอบดูนาทีที่เท่าไหร่ของวีดีโอ)
  * Text database (ตัวอย่างเช่น Wiki ที่ข้อมูลถูกอธิบายด้วยข้อความ)
  * The world-wide web (เช่น google)
- - -
## KDD Process
Input data -> Data Pre-Processing -> Data Mining -> Post-Processing (Pattern evaluation การประเมินผลว่ามีความน่าเชื่อถือมากน้อยเพียงใด, Pattern selection หลักการเลือก, Pattern interpretation การแปรผล, Pattern visualization การแสดงข้อมูล) -> Pattern Information knowledge 
- - - 
 
