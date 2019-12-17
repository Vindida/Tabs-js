# Tabs-js
### Описание: 

Используется для того чтобы:

1. скрыть лишний таб-контент, но оставить первый из них
2. скрыть все остальные таб-контенты при переключении таба
3. показать таб-контент, который относится к определенному табу

### Использование:

 .info-header-tab - класс пунктов меню табов  
 .info-header - класс обертки меню табов  
 .info-tabcontent - контент, который будет переключаться

 show, hide прописываем в CSS

### HTML-структура:

	<div class="info-header">
		<div class="info-header-tab">пункт меню табов</div>
		<div class="info-header-tab">пункт меню табов</div>
		<div class="info-header-tab">пункт меню табов</div>
	</div>

	<div class="info-tabconten">контент таба</div>
	<div class="info-tabcontent">контент таба</div>
	<div class="info-tabcontent">контент таба</div>
