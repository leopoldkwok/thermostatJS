<h1>A colour-coded thermostat app written in JavaScript.</h1>

*specifications:*
<ol>
<li>Thermostat starts at 20 degrees</li>
<li>You can increase the temp with the up button</li>
<li>You can decrease the temp with the down button</li>
<li>The minimum temperature is 10 degrees</li>
<li>If power saving mode is on, the maximum temperature is 25 degrees.</li>
<li>If power saving mode is off, the maximum temperature is 32 degrees.</li>
<li>Power saving mode is default.</li>
<li>You can reset the temperature to 20 degrees by hitting the reset button.</li>
<li>The thermostat should colour the display based on energy usage - < 18 is green, < 25 is yellow, otherwise it's red.</li>
<li>After every temperature change, the thermostat makes a POST request to localhost:4567/temperature_change, with the new temperature.</li>
</ol>