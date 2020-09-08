# Boxplot 
* ใช้แสดงสาระที่สำคัญของข้อมูลคือ ค่ากลาง ค่าการกระจาย สัดส่วนข้อมูลที่มากหรือน้อยกว่าค่ากลาง ( Symmetry ) รวมทั้งข้อมูลที่อยู่ห่างจากกลุ่มมากๆ (Outlier)
* Box plot จะแสดงข้อมูลทั้งหมดออกมา 3 Quartiles โดยมีการจัดเรียงอันดับของข้อมูลแล้ว ข้อมูลที่ตกอยู่ภายใต้ Q1 (Quartile 1) คือข้อมูล 25% แรกจากค่าต่ำขึ้นมา จะแสดงในรูปเส้นตรง หนึ่งเส้น (Whisker)  ข้อมูลที่ตกอยู่ภายใต้ Q2 คือข้อมูลตัวที่มากกว่า 25% จนถึงตัวที่ 75% โดยแสดงออกมาในรูป สี่เหลี่ยมผืนผ้า ภายใน Q3 นี้ จะมีค่าที่ 50% ของข้อมูลอยู่ เขียนแทนด้วยเส้นตรงอยู่ภายในรูปสี่เหลี่ยมผืนผ้า ค่านี้คือค่าค่ากลางของข้อมูลทั้งหมด (Median)  และตรงค่า เฉลี่ย(Mean) จะแทนด้วย เครื่องหมายบวก โดยที่ค่าอาจจะเท่าหรือต่างกับค่า Median ก็ได้  ส่วนค่าที่ตกอยู่ภายใต้ Q3 คือตัวที่มากกว่า 75% ขึ้นไป จะเขียนแทนด้วยเส้นตรง เช่นเดียวกับ Q1
* วิธีหาจุดเริ่มต้นของ Q1  และจุดสุดท้ายของ Q3 จะหามาจากสมการตามที่ปรากฏ อยู่ในรูป ดังนั้น ค่าที่ต่ำกว่า ค่าเริ่มต้นของ Q1 และค่าสุดท้ายของ Q3 จะเรียกว่า Outlier เขียนสัญญลักญ์แทนด้วย * ถ้าสังเกตดูเราจะพบว่า เส้นค่ากลางจะแบ่งจำนวนขอ้มูลใน Q2 ออกเป็นสองส่วนเท่าๆกัน ดังนั้นถ้า ค่ากลางนี้ไม่ได้อยู่ตรงกลางรูปสี่เหลี่ยมผืนผ้า นั่นหมายถึงรูปกราฟจะเบ้ ไป หรือความหนาแน่นของข้อมูลจะไม่เท่ากัน   แต่โดยทั่วไป โปรแกรมทางสถิติจะมีคำสั่งให้ทำ Box plot ให้ใช้
***อ่านเพิ่มเติมได้ที่ https://sites.google.com/site/mystatistics01/chapter2/graphical-data-presentation
- - -
# หาโค้ดในการพิมพ์ Boxplot ได้จากไหน?
* เราสามารถศึกษาเพิ่มเติมทั้งหมดได้ที่ https://matplotlib.org/api/_as_gen/matplotlib.pyplot.boxplot.html
* ในลิ้งก์ข้างต้นจะบอกการใช้โค้ดที่จำเป็นที่ต้องใช้ใน Boxplot
- - -
# หาข้อูลทำโปรเจคจากไหนได้บ้าง?
* ได้ที่นี่เลย "https://data.go.th/" 
- - - 
# Chapter 3: Data Preprocessing
* Data	Preprocessing:	An	Overview
* Data	Cleaning
  * จัดการข้อมูลที่สูญหาย, ทำข้อมูลให้ smooth, หาข้อมูลที่ผิดปกติแล้วก็ลบมันออกไป และแก้ไขความไม่สอดคล้องกันของข้อมูล
* Data	Integration
* Data	Reduction	and	Transformation
* Dimensionality	Reduction
* Summary
## Why Preprocess the Data?
* Measures	for	data	quality:	A	multidimensional	view
* Accuracy:	correct	or	wrong,	accurate	or	not
* Completeness:	not	recorded,	unavailable,	…
* Consistency:	some	modified	but	some	not,	dangling,	…
* Timeliness:	timely	update?	
* Believability:	how	trustable	the	data	are	correct?
* Interpretability:	how	easily	the	data	can	be	understood?
## How to Handle Missing Data?
* Ignore	the	tuple:	usually	done	when	class	label	is	missing	(when	doing	
classification)—not	effective	when	the	%	of	missing	values	per	attribute	varies	
considerably
* Fill	in	the	missing	value	manually:	tedious	+	infeasible?
* Fill	in	it	automatically	with
* a	global	constant	:	e.g.,	“unknown”,	a	new	class?!	
* the	attribute	mean
* the	attribute	mean	for	all	samples	belonging	to	the	same	class:	smarter 
* the	most	probable	value:	inference-based	such	as	Bayesian	formula	or	decision	
tree

