wunderground.com-Weather
========================

Get local weather with wunderground.com api, PHP Class

How to use
-----------
`````php
<?php

include_once 'weather.php';
$w = new weather();
echo $w->getLocation();
echo '<br/>';
echo $w->getWeatherIcon(true);
echo '<br/>';
echo $w->getTemperature();
echo ' C';
echo '<br/>';
echo $w->getSateliteImage(true);
?>
`````
