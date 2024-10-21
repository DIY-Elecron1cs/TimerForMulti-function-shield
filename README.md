<h1>TimerForMulti-function-shield</h1>
<p>таймер на millis() на базе multi-functions shield (шилд на UNO).</p>
<h2>Версии</h2>
<h3>Версия 1.0</h3>
<h4>Как можно собрать</h4>
<img src="https://i.postimg.cc/J0ScwyzS/alarm-Clock1-0.jpg" alt="scheme" width="200">
<p>В версии 1.0 используется одновременно millis() и delay(), из-за чего таймер сбивается после срабатывания.</p>
<p>Подходит для теста шилда и МК Arduino UNO.</p>
<ul>
  <li>В версии 1.0 есть функция с мелодией. По умолчанию это AHA - Take on me</li>
  <li>Пьезопищалка вынесена отдельно на пин D5, т.к. встроенная имеет генератор тона.</li>
</ul>
