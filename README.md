# DaciaLodgy-K9K-OBD2-PIDs

This is a list of OBD2 PIDs supported by a Dacia Lodgy MY2015 (First Gen) with the 1.5 dCi (110 CP) FAP engine.

The vehicle is equiped with the K9K R8 engine but most PIDs should also work for <a href="https://en.wikipedia.org/wiki/Renault_K-Type_engine#K9K_dCi">other variants</a> of this engine.

These have been tested using the following setup:
<ul>
<li>Hardware</li>
        <ul>
        <li><a href="https://www.scantool.net/obdlink-lxbt/">OBDLink LX</a>
        </ul>
<li>Software</li>
        <ul>
        <li><a href="https://play.google.com/store/apps/details?id=org.prowl.torque&hl=en&gl=US">Torque (Android)</a></li>
        </ul>
</ul>

<h2> Standard PIDs (Service 01) </h2>

Please refer to https://en.wikipedia.org/wiki/OBD-II_PIDs for more details on these and the equations used for each one.

<table border="0" cellpadding="0" cellspacing="0" width="2259" style="border-collapse:
 collapse;table-layout:fixed;width:1694pt">
 <colgroup><col class="xl65" width="92" style="mso-width-source:userset;mso-width-alt:3364;
 width:69pt">
 <col class="xl65" width="152" style="mso-width-source:userset;mso-width-alt:5558;
 width:114pt">
 <col class="xl65" width="64" span="3" style="width:48pt">
 <col class="xl65" width="75" style="mso-width-source:userset;mso-width-alt:2742;
 width:56pt">
 <col class="xl65" width="64" span="6" style="width:48pt">
 <col class="xl65" width="72" style="mso-width-source:userset;mso-width-alt:2633;
 width:54pt">
 <col class="xl65" width="64" span="2" style="width:48pt">
 <col class="xl65" width="76" style="mso-width-source:userset;mso-width-alt:2779;
 width:57pt">
 <col class="xl65" width="64" span="17" style="width:48pt">
 </colgroup><tbody><tr height="15" style="height:11.25pt">
  <td height="15" class="xl65" colspan="2" width="244" style="height:11.25pt;
  mso-ignore:colspan;width:183pt">PIDs supported [$01 - $20]	</td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="75" style="width:56pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="72" style="width:54pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="76" style="width:57pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
  <td class="xl65" width="64" style="width:48pt"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl65" style="height:12.0pt"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;width:69pt">Hexadecimal</td>
  <td colspan="4" class="xl71" width="344" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:258pt">9</td>
  <td colspan="4" class="xl71" width="267" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:200pt">8</td>
  <td colspan="4" class="xl71" width="264" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:198pt">3</td>
  <td colspan="4" class="xl71" width="268" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:201pt">B</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">A</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">1</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">1</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Binary</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Supported?</td>
  <td class="xl68" width="152" style="border-top:none;border-left:none;width:114pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl68" width="75" style="border-top:none;border-left:none;width:56pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl68" width="72" style="border-top:none;border-left:none;width:54pt">Yes</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="76" style="border-top:none;border-left:none;width:57pt">Yes</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">PID number</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">2</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">4</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">5</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">6</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">7</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">8</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">9</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0B</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">0C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0E</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">0F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">10</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">11</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">12</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">13</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">14</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">15</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">16</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">17</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">18</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">19</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1B</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1E</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">20</td>
 </tr>
 <tr height="91" style="height:68.25pt">
  <td height="91" class="xl66" width="92" style="height:68.25pt;border-top:none;
  width:69pt">Description</td>
  <td class="xl74" width="152" style="border-top:none;border-left:none;width:114pt">Monitor
  status since DTCs cleared. (Includes malfunction indicator lamp (MIL), status
  and number of DTCs, components tests, DTC readiness checks)</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Calculated
  engine load</td>
  <td class="xl70" width="75" style="border-top:none;border-left:none;width:56pt">Engine
  coolant temperature</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Intake
  manifold absolute pressure</td>
  <td class="xl70" width="72" style="border-top:none;border-left:none;width:54pt">Engine
  speed</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Vehicle
  speed</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="76" style="border-top:none;border-left:none;width:57pt">Intake
  air temperature</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Mass
  air flow sensor (MAF)&nbsp;air flow rate</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Throttle
  position</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Oxygen
  sensors present (in 2 banks)</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">OBD
  standards this vehicle conforms to</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">PIDs
  supported [$21 - $40]	</td>
 </tr>
 <tr height="15" style="height:11.25pt">
  <td height="15" class="xl65" style="height:11.25pt"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="15" style="height:11.25pt">
  <td height="15" class="xl65" colspan="2" style="height:11.25pt;mso-ignore:colspan">PIDs
  supported [$21 - $40]	</td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl65" style="height:12.0pt"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;width:69pt">Hexadecimal</td>
  <td colspan="4" class="xl71" width="344" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:258pt">A</td>
  <td colspan="4" class="xl71" width="267" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:200pt">0</td>
  <td colspan="4" class="xl71" width="264" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:198pt">0</td>
  <td colspan="4" class="xl71" width="268" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:201pt">1</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">8</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">1</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Binary</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">1</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Supported?</td>
  <td class="xl68" width="152" style="border-top:none;border-left:none;width:114pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="75" style="border-top:none;border-left:none;width:56pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="72" style="border-top:none;border-left:none;width:54pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="76" style="border-top:none;border-left:none;width:57pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl68" width="64" style="border-top:none;border-left:none;width:48pt">Yes</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">PID number</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">21</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">22</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">23</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">24</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">25</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">26</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">27</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">28</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">29</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">2A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">2B</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">2C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">2D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">2E</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">2F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">30</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">31</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">32</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">33</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">34</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">35</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">36</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">37</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">38</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">39</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3B</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3E</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">3F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">40</td>
 </tr>
 <tr height="76" style="height:57.0pt">
  <td height="76" class="xl66" width="92" style="height:57.0pt;border-top:none;
  width:69pt">Description</td>
  <td class="xl70" width="152" style="border-top:none;border-left:none;width:114pt">Distance
  traveled with malfunction indicator lamp (MIL) on</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="75" style="border-top:none;border-left:none;width:56pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="72" style="border-top:none;border-left:none;width:54pt">Commanded
  EGR</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="76" style="border-top:none;border-left:none;width:57pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Warm-ups
  since codes cleared</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">Distance
  traveled since codes cleared</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">PIDs
  supported [$41 - $60]</td>
 </tr>
 <tr height="15" style="height:11.25pt">
  <td height="15" class="xl65" style="height:11.25pt"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="15" style="height:11.25pt">
  <td height="15" class="xl65" colspan="2" style="height:11.25pt;mso-ignore:colspan">PIDs
  supported [$41 - $60]	</td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl65" style="height:12.0pt"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
  <td class="xl65"></td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;width:69pt">Hexadecimal</td>
  <td colspan="4" class="xl71" width="344" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:258pt">8</td>
  <td colspan="4" class="xl71" width="267" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:200pt">0</td>
  <td colspan="4" class="xl71" width="264" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:198pt">0</td>
  <td colspan="4" class="xl71" width="268" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:201pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
  <td colspan="4" class="xl71" width="256" style="border-right:1.0pt solid #A2A9B1;
  border-left:none;width:192pt">0</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Binary</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">1</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">0</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">Supported?</td>
  <td class="xl68" width="152" style="border-top:none;border-left:none;width:114pt">Yes</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="75" style="border-top:none;border-left:none;width:56pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="72" style="border-top:none;border-left:none;width:54pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="76" style="border-top:none;border-left:none;width:57pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
  <td class="xl69" width="64" style="border-top:none;border-left:none;width:48pt">No</td>
 </tr>
 <tr height="16" style="height:12.0pt">
  <td height="16" class="xl66" width="92" style="height:12.0pt;border-top:none;
  width:69pt">PID number</td>
  <td class="xl67" width="152" style="border-top:none;border-left:none;width:114pt">41</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">42</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">43</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">44</td>
  <td class="xl67" width="75" style="border-top:none;border-left:none;width:56pt">45</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">46</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">47</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">48</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">49</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">4A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">4B</td>
  <td class="xl67" width="72" style="border-top:none;border-left:none;width:54pt">4C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">4D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">4E</td>
  <td class="xl67" width="76" style="border-top:none;border-left:none;width:57pt">4F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">50</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">51</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">52</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">53</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">54</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">55</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">56</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">57</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">58</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">59</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5A</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5B</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5C</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5D</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5E</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">5F</td>
  <td class="xl67" width="64" style="border-top:none;border-left:none;width:48pt">60</td>
 </tr>
 <tr height="61" style="height:45.75pt">
  <td height="61" class="xl66" width="92" style="height:45.75pt;border-top:none;
  width:69pt">Description</td>
  <td class="xl70" width="152" style="border-top:none;border-left:none;width:114pt">Monitor
  status this drive cycle</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="75" style="border-top:none;border-left:none;width:56pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="72" style="border-top:none;border-left:none;width:54pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="76" style="border-top:none;border-left:none;width:57pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">-</td>
  <td class="xl70" width="64" style="border-top:none;border-left:none;width:48pt">PIDs
  supported [$61 - $80]	</td>
 </tr>
 <!--[if supportMisalignedColumns]-->
 <tr height="0" style="display:none">
  <td width="92" style="width:69pt"></td>
  <td width="152" style="width:114pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="75" style="width:56pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="72" style="width:54pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="76" style="width:57pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
  <td width="64" style="width:48pt"></td>
 </tr>
</tbody></table>
    
<h2> Custom PIDs </h2>

<a href="https://github.com/gdincu/DaciaLodgy-K9K-OBD2-PIDs/blob/main/K9K.csv">These</a> PIDs are setup to be used via the Torque Pro app and therefore some of the formulas are based on the <a href="https://wiki.torque-bhp.com/view/Equations">Torque Wiki</a>.