# ibtproject
An online shop for summer dresses

Курсовият проект, който съм решилa да направя, е интернет магазинът, който е предложен като примерно задание.
Проектът е на тема онлайн магазин за дамски дрехи. Магазинът ще покрива изискванията на задачата за Текуща Оценка.

Потребителите имат възможност да преглеждат продукти, да ги добавят в кошница си и след това да ги поръчват.

Технологии : HTML, CSS, JS


Файлове:

1. products.html :
	- съдържа:
		- "картички" на предлаганите продукти
	- функционалности:
		- "картичките" препращат към страниците на съответните им продукти(product1.html - product5.html)
		
2-6.  (product1.html - product5.html)

	- съдържа:
		- информация за продукта: 
			- име
			- кратко описание
			- цена
			- снимки
			- пълно описание
		- секция за потребителски ревюта
		- форма за закупуване
	- функционалности:
		- преглед на снимки на продукта
		- след кликане на бутона "Add To Cart" избраните данни за продукта се изпращат чрез localStorage към "cart.html"
		- след кликане на бутона "Submit", нов list item се визуализира над последния добавен коментар
		- при натискане на бутона "Submit", формата се "нулира"
		
7. cart.html :
	- съдържа:
		- таблица с избраните за закупуване продукти
		- форма за данни за доставка
		- стойност на поръчката
	- функционалности:
		- при натискане върху снимка на продукт се отваря съответстващата му страница
		- пресмятане на стойност на поръчката
		- при натискане на бутона за изпращане, се показва съобщение гласящо "%ИМЕ%, благодарим за поръчката!". При непълни полета се показва подобно съобщение, също.
		- при натискане на бутона за изпращане, формата да се "нулира"
		
8. login.html :
	- съдържа:
		- статична форма за Регистрация
		- интерактивна форма за Вход
	- функционалности:
		- при username="az" и password="123", след натискане върху "Log in", се показва съобщение за успешно влизане и след 2,5 секунди препраща към главната страница "products.html"
		- при грешни данни, след натискане върху "Log in", се показва съобщение изискващо попълване на празните полета
