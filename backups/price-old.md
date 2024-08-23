<!DOCTYPE html>
<html lang="en">
<head>
 <!--

IF YOU ARE VIEWING THIS PAGE THEN YOU NEED TO LOAD THE WEBSITE AT 

https://hpssjellis.github.io/maker100-curriculum/price-list.html
    
-->
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Purchase Table for the Maker100-Curriculum</title>
<style>
    table {
        width: 100%;
        border-collapse: collapse;
    }
    th {
        border: 1px solid #ddd;
        padding: 8px;
    }
    th {
        background-color: #f2f2f2;
    }
    td {       
       border: 1px solid #ddd;
       padding: 8px;
       overflow-x:hidden; 
       overflow-y:hidden; 
       white-space:nowrap; 
       max-width:70px;"
    }
</style>
</head>
<body>
<h1 align=center>Purchase Table for the <a href="https://github.com/hpssjellis/maker100-curriculum">Maker100-Curriculum</a></h1>
 <input type=button value="Economy" onclick="myEco()"> <input type=button value="Default" onclick="myDefault()"> <input type=button value="Kitchen Sink" onclick="mySink()"> Based on 30 students per computer lab<br><br>
<br>
Note: This is an estimate of products to purchase and may not work perfectly together.<br>
<br>
<table>
    <thead>
        <tr>
            <th>#</th>
            <th>Code</th>
            <th>Item</th>
            <th>Image</th>
            <th>Amount</th>
            <th>Cost in USD</th>
            <th>Total in USD</th>
        </tr>
    </thead>
    <tbody>        
        <tr>
            <td colspan="6">Total --></td>
            <td id="grandTotal2">$135</td>
        </tr>







 <tr>
     <td>1</td>
     <td>Basic Electronics Kits</td>
     <td><a href="https://www.amazon.com/Snap-Circuits-SC-750-Electronics-Exploration/dp/B0002AHQWS/ref=sr_1_1?crid=1R33H2QRD95ZJ&dib=eyJ2IjoiMSJ9.ek44gomRfkmAtWcd4bCrumNDXbJio7xQ5Z2usjQcqHiH5xDl0eS5OQortxrcy9L_mTI9s0Q82QZWWq1PoG_f8TvUHiXhoTmEJv7UMESIViID1uBbvHHNdllFC7brRXWD9gFH51cbh8CK6zwLGMhf6VZQAJaVB41CnH_FJYK9yANOixcFCMHv-MUMd_AkcFLbEQJDpgJxJixLmztRCM74WSjX8nVAm-3XbjZsKcJFOv2_rl1FQOH9iD3mgzcVBnMc6fVzE64isQXAdlG3ZnOuDStx3epK96M3dP10yyBSlG4.V_w5Oous-VQf5r8mCysSmmJREdMIJ_uzf6wDO2wP3SQ&dib_tag=se&keywords=snap%2Bcircuits%2B750&qid=1724380552&sprefix=snap%2Bcircuits%2B750%2Caps%2C246&sr=8-1&th=1">Snap Circuits 750</a></td>
     <td><img width=100 src="https://github.com/user-attachments/assets/ea1c8c5b-549f-4004-a4fe-435da7e0eab7" ></td>
     <td><input type="number" id="amount1" style="width: 60px;" value="15"></td>
     <td>$<input type="number" id="cost1" style="width: 110px;" value="110.49"></td>
     <td id="total1"></td>
 </tr>
 <tr>
     <td>2</td>
     <td>Basic Electronic Equipment Kit</td>
     <td><a href="https://www.amazon.com/Smraza-Breadboard-Resistors-Mega2560-Raspberry/dp/B01HRR7EBG/ref=sr_1_1_sspa?crid=1U8I4WDFK2RSZ&dib=eyJ2IjoiMSJ9.gOzh6KocJwaHIhUUQtMHm-96WFYJTXv6_ul3s6WPMvwBrfPCgOsuGdbfNwuT_hCCvm6EqBXk81OPzvKKXRJqs7ZsbCDohdNZK-kxLmAFqL3a7lk6yQWA24JTsfII2DyoBOd34tBE8QZl11PDP4vbtziyv8VgPwULe8xjbE1uYQ8bjhoySvJ86QVDiie5iigZpZPMDZzO70-oPVDtUmWKznR3A31qjbsyYQMjv6c6vQI.3PZ-bgQqFMv8nXOQSnZZAQgZVQ-QIYRBPGfCDdX9VE4&dib_tag=se&keywords=basic%2Belectronic%2Bkit&qid=1724384681&sprefix=basic%2Belectronic%2Bkit%2Caps%2C239&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1">Basic Starter Kit for Arduino</a></td>
     <td><img  width=100  src="https://github.com/user-attachments/assets/04dd3a6f-9c24-43ad-a204-9254e0c5b848" ></td>
     <td><input type="number" id="amount2" style="width: 60px;"  value="5"></td>
     <td>$<input type="number" id="cost2" style="width: 110px;"  value="9.99"></td>
     <td id="total2"></td>
 </tr>
 <tr>
     <td>3</td>
     <td>Soldering Kit</td>
     <td><a href="https://www.amazon.ca/KEPIOG-Adjustable-Temperature-Controlled-Desoldering/dp/B0CRNQQMFD/ref=sr_1_17?dib=eyJ2IjoiMSJ9.Y6q0c77mIATumpcCF1h-1iXoz4TBqPRL5tDHsNbCI98DYk608CD8knHStnr3_bIMrUwHgxU0YSfWFRyS1gttu07WgX6v7HmgScWFnJPmgtQe0J-9vnLzonQe7E-N5wls1ECbrBnVYwaji46ng4Q1n3KfxhBdQvVwiEHp-WbftXQdcXqI8jQKbLF_29ylsRcpf8yJpaE-5MXmf1L7BKb5GsbAJIyce_NNCaZtrgu3N7HFX5s0qOJ7LP0UoolqUy4TXlqUIGqIMwmMDC5uAlcRpLqNHQ4lM79Z0Sf3jlOMR9Y.4p3LoB2iO94h9mpvtHoo12cG3LsI_a-yyNri3Gg92DI&dib_tag=se&keywords=soldering&qid=1724386553&sr=8-17&th=1">KEPIOG Soldering Kit</a></td>
     <td><img  width=100  src="https://github.com/user-attachments/assets/32d0f153-a6e8-436f-aa54-d4fb3d4ad468"></td>
     <td><input type="number" id="amount3" style="width: 60px;"  value="3"></td>
     <td>$<input type="number" id="cost3" style="width: 110px;"  value="49.99"></td>
     <td id="total3"></td>
 </tr>
 <tr>
     <td>4</td>
     <td>Soldering Microscope</td>
     <td><a href="https://www.amazon.ca/Andonstar-AD246S-M-Microscope-Biological-Compatible/dp/B09VPPS96M/ref=sxin_23_sbv_search_btf?content-id=amzn1.sym.8d483e07-327c-4aac-8788-cd60359f3dcb%3Aamzn1.sym.8d483e07-327c-4aac-8788-cd60359f3dcb&cv_ct_cx=soldering%2Bkit&dib=eyJ2IjoiMSJ9.dEwDE-ZcRDLc2Xn4sCUmfQ.RaHOvhZ3IlxZLeYthwCqr3cvx0N_gPjbdi3sxmLK_tM&dib_tag=se&hvadid=208395474852&hvdev=c&hvlocphy=1001970&hvnetw=g&hvqmt=e&hvrand=189228443859724970&hvtargid=kwd-21718036&hydadcr=23342_10093192&keywords=soldering%2Bkit&pd_rd_i=B09VPPS96M&pd_rd_r=001db91b-6338-48de-a25e-dbc76a4342a4&pd_rd_w=ECD4d&pd_rd_wg=BAdGI&pf_rd_p=8d483e07-327c-4aac-8788-cd60359f3dcb&pf_rd_r=5THF1YCK6F75SAEC6BRS&qid=1724385471&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sr=1-1-5190daf0-67e3-427c-bea6-c72c1df98776&th=1">Andonstar AD246S-M HDMI Digital Microscope 2000x</a></td>
     <td><img width=100  src="https://github.com/user-attachments/assets/318bde49-da29-4097-88ad-3c9c10de0d60"></td>
     <td><input type="number" id="amount4" style="width: 60px;"  value="1"></td>
     <td>$<input type="number" id="cost4" style="width: 110px;"  value="249.99"></td>
     <td id="total4"></td>
 </tr>


 <tr>
     <td>5</td>
     <td>Testing microcontroller</td>
     <td><a href="https://www.seeedstudio.com/Seeeduino-XIAO-Pre-Soldered-p-4747.html">XIAO SAMD21</a></td>
     <td><img width=100  src="https://github.com/hpssjellis/maker100-eco/assets/5605614/2d46f328-aa38-42e7-8176-94f9b82f7501"></td>
     <td><input type="number" id="amount5" style="width: 60px;"  value="15"></td>
     <td>$<input type="number" id="cost5" style="width: 110px;"  value="6.50"></td>
     <td id="total5"></td>
 </tr>



     
 <tr>
     <td>6</td>
     <td>Main Microcontroller</td>
     <td><a href="https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/">Seeedstudio XiaoEsp32S3-Sense</a></td>
     <td><img width=100  src="https://github.com/hpssjellis/maker100-eco/assets/5605614/12fe6ba4-a8f4-4563-ab6d-aa1755d568d6"></td>
     <td><input type="number" id="amount6" style="width: 60px;"  value="30"></td>
     <td>$<input type="number" id="cost6" style="width: 110px;"  value="13.99"></td>
     <td id="total6">$40</td>
 </tr>

 <tr>
     <td>7</td>
     <td>USB-C Data</td>
     <td><a href="https://www.amazon.ca/dp/B07PP2RB25/ref=redir_mobile_desktop?_encoding=UTF8&aaxitk=d45a607744b1781660ab5ef4e28f01f1&hsa_cr_id=1744542500301&pd_rd_plhdr=t&pd_rd_r=764237ba-4548-48e2-8a65-cdba84cf150f&pd_rd_w=GKZWh&pd_rd_wg=oqdsY&ref_=sbx_be_s_sparkle_td_asin_1_title&th=1">UGREEN USB Type C Cable Nylon Braided USB 2.0 to USB C Cable</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148264906-0b1934f2-d80a-4f90-b6d3-1c8acacee7fb.png"></td>
     <td><input type="number" id="amount7" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost7" style="width: 110px;"  value="8.99"></td>
     <td id="total7"></td>
 </tr>



 <tr>
     <td>8</td>
     <td>Mobile Power</td>
     <td><a href="https://www.amazon.ca/Portable-Ultra-Compact-External-Identify-Compatible/dp/B09JNX8PZR/ref=sr_1_33_sspa?crid=485TUJ0EMB4N&keywords=power+bank&qid=1641405350&s=electronics&sprefix=power+bank%2Celectronics%2C134&sr=1-33-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUFONlRUWTM1OFc0WTEmZW5jcnlwdGVkSWQ9QTA2NTUwODdCV0ZQQTlQUUE4NDYmZW5jcnlwdGVkQWRJZD1BMDEwMjU4OTNFR1AyVjQ2N0dQTFgmd2lkZ2V0TmFtZT1zcF9idGYmYWN0aW9uPWNsaWNrUmVkaXJlY3QmZG9Ob3RMb2dDbGljaz10cnVl">5000mAh Power Bank Portable Charger</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148266102-36a2d187-7eef-42db-a030-5054fa620330.png"></td>
     <td><input type="number" id="amount8" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost8" style="width: 110px;"  value="15.99"></td>
     <td id="total8"></td>
 </tr>

 <tr>
     <td>9</td>
     <td>Micro-SD Card</td>
     <td><a href="https://www.amazon.com/KEXIN-Micro-Class-Ultra-Memory/dp/B081ZXZ44G/ref=sxin_14_pa_sp_search_thematic_sspa?content-id=amzn1.sym.96232a40-8dad-410b-aa59-aa3d5b2415c7%3Aamzn1.sym.96232a40-8dad-410b-aa59-aa3d5b2415c7&crid=2GDUPJIHO7EZL&cv_ct_cx=micro%2Bsd%2Bcard%2B32%2Bgb&keywords=micro%2Bsd%2Bcard%2B32%2Bgb&pd_rd_i=B081ZXZ44G&pd_rd_r=59dd82d7-3261-4ded-ad14-7aebb51306f7&pd_rd_w=5ette&pd_rd_wg=n6Lwb&pf_rd_p=96232a40-8dad-410b-aa59-aa3d5b2415c7&pf_rd_r=KFHAW69WYSXPMCQ35254&qid=1705006842&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=micro%2Bsd%2Bcard%2B32%2Bgb%2Caps%2C134&sr=1-3-364cf978-ce2a-480a-9bb0-bdb96faa0f61-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9zZWFyY2hfdGhlbWF0aWM&th=1">Micro SD Card set</a></td>
     <td><img width=100  src="https://github.com/hpssjellis/maker100-eco/assets/5605614/fc0bbf46-0fe9-4639-ad5e-8c6abd4a1b68"></td>
     <td><input type="number" id="amount9" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost9" style="width: 110px;"  value="37.99"></td>
     <td id="total9"></td>
 </tr>

 <tr>
     <td>10</td>
     <td>22 Guage Wire</td>
     <td><a href="https://www.amazon.com/Gauge-Wire-Solid-Hookup-Wires/dp/B088KQFHV7/ref=sr_1_1?dib=eyJ2IjoiMSJ9.sktK6tem_9i_qBF5S3qj3t3Q1pVKo-tgqjT-TXckMRUhBN8ZrdMc3MOLovA_HhlXfBNIsIOd4ylXIYDpvCJB-inZ0h3jpC-SK1oJvdqfIizX7npYxIpSTE0m7oEGmA1uVXJ1RqIjF8g_eofv-PaI8B9YxdOlxUaneOps7b0Wg2zlFRCAOg8F8daImTCe-Bl-cLbs9pwIdes0SnrPdXS3hQ8ZREY3O-HMMRL0rQMZwtYPu8GQ_QjAlvVvh0c2CMZ7pCAHqZGp9bpSv7VTraB0cUUt2F0m4-zXpMpOQWfPirA.NbsFeZPmR5pwUDSi7B1waV9PXMU2fdYzo_GIFOtEAe0&dib_tag=se&keywords=Plusivo+22+Gauge+Wire+Solid+Core+Hookup+Wires-22+AWG+Pre-Tinned%2C+PVC+%28OD%3A+1.5mm%29+Coated+Copper+Wires+6+Colors+%28Black%2C+Red%2C+Yellow%2C+Green%2C+Blue%2C+White%29+33ft+or+10m+Each%2C+Hook+Up+Wire+Kit&qid=1724444995&sr=8-1">22 AWG wires solid core with cheap wire stripper</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148152005-41f2c7c8-e1f6-48b1-90ee-f26b36b129c6.png"></td>
     <td><input type="number" id="amount10" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost10" style="width: 110px;"  value="12.99"></td>
     <td id="total10"></td>
 </tr>

 <tr>
     <td>11</td>
     <td>GPS Sensor</td>
     <td><a href="https://www.robotshop.com/products/grove-gps-module">Grove GPS Module</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148159156-a26342ea-4b48-4462-807b-744fdcb80156.png"></td>
     <td><input type="number" id="amount11" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost11" style="width: 110px;"  value="19.99"></td>
     <td id="total11"></td>
 </tr>

 <tr>
     <td>12</td>
     <td>Flex Sensor</td>
     <td><a href="http://www.robotshop.com/ca/en/22-10k-flexible-sensor.html">Flex Sensor RB-Spa-989</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148158276-4efb47aa-5de5-4ad1-8048-ddd547f3a8ce.png"></td>
     <td><input type="number" id="amount12" style="width: 60px;"  value="15"></td>
     <td>$<input type="number" id="cost12" style="width: 110px;"  value="11.95"></td>
     <td id="total12"></td>
 </tr>

 <tr>
     <td>13</td>
     <td>Pixy2 ML Color Vision sensor</td>
     <td><a href="https://www.robotshop.com/products/charmed-labs-pixy-21-robot-vision-image-sensor-rbc">Charmed Labs Pixy 2 CMUcam5 Image Sensor</a></td>
     <td><img width=100  src="https://user-images.githubusercontent.com/5605614/148158393-7caaa5dc-8407-4304-823d-7a2c751b7eef.png"></td>
     <td><input type="number" id="amount13" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost13" style="width: 110px;"  value="69.95"></td>
     <td id="total13"></td>
 </tr>

 <tr>
     <td>14</td>
     <td>MCU003</td>
     <td><a href="">Microcontroller C</a></td>
     <td><img width=100  src=""></td>
     <td><input type="number" id="amount14" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost14" style="width: 110px;"  value="0"></td>
     <td id="total14"></td>
 </tr>

 <tr>
     <td>15</td>
     <td>MCU003</td>
     <td><a href="">Microcontroller C</a></td>
     <td><img width=100  src=""></td>
     <td><input type="number" id="amount15" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost15" style="width: 110px;"  value="0"></td>
     <td id="total15"></td>
 </tr>

 <tr>
     <td>16</td>
     <td>MCU003</td>
     <td><a href="">Microcontroller C</a></td>
     <td><img width=100  src=""></td>
     <td><input type="number" id="amount16" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost16" style="width: 110px;"  value="0"></td>
     <td id="total16"></td>
 </tr>

 <tr>
     <td>17</td>
     <td>Color Display</td>
     <td><a href="https://www.seeedstudio.com/Seeed-Studio-Round-Display-for-XIAO-p-5638.html">XIAO Round Color Touch sensitive display</a></td>
     <td><img width=100  src="https://github.com/user-attachments/assets/8c150cdb-14aa-4eeb-a41c-f8944a8af32e"></td>
     <td><input type="number" id="amount17" style="width: 60px;"  value="3"></td>
     <td>$<input type="number" id="cost17" style="width: 110px;"  value="18.00"></td>
     <td id="total17"></td>
 </tr>

 <tr>
     <td>18</td>
     <td>XIAO Expansion Board</td>
     <td><a href="https://wiki.seeedstudio.com/Seeeduino-XIAO-Expansion-Board/">XIAO Expansion Board</a></td>
     <td><img width=100  src="https://github.com/user-attachments/assets/ff241df5-ee81-4427-9c9e-912cd5757f55"></td>
     <td><input type="number" id="amount18" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost18" style="width: 110px;"  value="16.40"></td>
     <td id="total18"></td>
 </tr>

 <tr>
     <td>19</td>
     <td>MCU003</td>
     <td><a href="">Microcontroller C</a></td>
     <td><img width=100  src=""></td>
     <td><input type="number" id="amount19" style="width: 60px;"  value="0"></td>
     <td>$<input type="number" id="cost19" style="width: 110px;"  value="0"></td>
     <td id="total19"></td>
 </tr>


     
        <tr>
            <td colspan="6">Total --></td>
            <td id="grandTotal">135</td>
        </tr>
     
    </tbody>
</table>






    


<script>
 
 // Global Variables
 let myMaxRows = 19;


function myEco(){
  document.getElementById('amount1').value = 0;
  document.getElementById('amount2').value = 1;
  document.getElementById('amount3').value = 0;
  document.getElementById('amount4').value = 3;
  document.getElementById('amount5').value = 3;
  document.getElementById('amount6').value = 3;
  document.getElementById('amount7').value = 3;
  document.getElementById('amount8').value = 3;
  document.getElementById('amount9').value = 3;
  document.getElementById('amount10').value = 3;
  document.getElementById('amount11').value = 3;
  document.getElementById('amount12').value = 3;
  document.getElementById('amount13').value = 3;
  document.getElementById('amount14').value = 3;
  document.getElementById('amount15').value = 3;
  document.getElementById('amount16').value = 3;
  document.getElementById('amount17').value = 3;
  document.getElementById('amount18').value = 3;
  document.getElementById('amount19').value = 3;


 calculateTotal();
}

function myDefault(){
  document.getElementById('amount1').value = 15;
  document.getElementById('amount2').value = 5;
  document.getElementById('amount3').value = 5;
  document.getElementById('amount4').value = 15;
  document.getElementById('amount5').value = 15;
  document.getElementById('amount6').value = 15;
  document.getElementById('amount7').value = 15;
  document.getElementById('amount8').value = 15;
  document.getElementById('amount9').value = 15;
  document.getElementById('amount10').value = 15;
  document.getElementById('amount11').value = 15;
  document.getElementById('amount12').value = 15;
  document.getElementById('amount13').value = 15;
  document.getElementById('amount14').value = 15;
  document.getElementById('amount15').value = 15;
  document.getElementById('amount16').value = 15;
  document.getElementById('amount17').value = 15;
  document.getElementById('amount18').value = 15;
  document.getElementById('amount19').value = 15;

 
 calculateTotal();
}
 
function mySink(){
  document.getElementById('amount1').value = 30;
  document.getElementById('amount2').value = 30;
  document.getElementById('amount3').value = 30;
  document.getElementById('amount4').value = 30;
  document.getElementById('amount5').value = 30;
  document.getElementById('amount6').value = 30;
  document.getElementById('amount7').value = 30;
  document.getElementById('amount8').value = 30;
  document.getElementById('amount9').value = 30;
  document.getElementById('amount10').value = 30;
  document.getElementById('amount11').value = 30;
  document.getElementById('amount12').value = 30;
  document.getElementById('amount13').value = 30;
  document.getElementById('amount14').value = 30;
  document.getElementById('amount15').value = 30;
  document.getElementById('amount16').value = 30;
  document.getElementById('amount17').value = 30;
  document.getElementById('amount18').value = 30;
  document.getElementById('amount19').value = 30;

 calculateTotal();
}

 

function calculateTotal() {
  let grandTotal = 0;

  for (let i = 1; i <= myMaxRows; i++) {
      const cost = parseFloat(document.getElementById(`cost${i}`).value);
      const amount = parseFloat(document.getElementById(`amount${i}`).value);
      const total = cost * amount;
      document.getElementById(`total${i}`).textContent = '$'+total.toFixed(2);
      grandTotal += total;
  }

  document.getElementById('grandTotal').textContent = '$'+grandTotal.toFixed(2);
  document.getElementById('grandTotal2').textContent = '$'+grandTotal.toFixed(2);
}

for (let i = 1; i <= myMaxRows; i++) {
  document.getElementById(`cost${i}`).addEventListener('input', calculateTotal);
  document.getElementById(`amount${i}`).addEventListener('input', calculateTotal);
}

// Initial calculation
calculateTotal();


        
</script>


























1. $7.56 CAD Slide Potentiometer	[RB-See-229](	http://www.robotshop.com/ca/en/grove-slide-potentiometer.html)	  <br> <img src="https://user-images.githubusercontent.com/5605614/148158797-a4eb34ff-f924-4857-a873-9155d5bc78c4.png" width=100 /> 



1. $4.80 CAD Moisture	[RB-Dfr-161](http://www.robotshop.com/en/dfrobot-moisture-sensor.html)	  <br> <img src="https://user-images.githubusercontent.com/5605614/148158607-3d2f57d6-1970-4a3e-b148-e910df7696ed.png" width=100 />



1. $4.12 USD  [ADXL362 Accelerometer](https://www.amazon.com/Reland-Sun-ADXL362-Acceleration-Interface/dp/B09B7ZNWCY/ref=sr_1_1?crid=16ZSFGWJ0Z54E&dib=eyJ2IjoiMSJ9.dT8Bx5C1KY7YVB_eKW_jQhU_VJrRMXwDtSWjZp_GfHUaJdaM1jD3_jkVimfmSm1SPx3-P_UaiFmxQOqw4Kxm3Q.RIfS_2ceBtpfp72EV_atz3cREVe1aCTGtlvyXqPWD2I&dib_tag=se&keywords=ADXL362&qid=1705005894&sprefix=adxl362%2Caps%2C110&sr=8-1)  or [RobotShop 16.95](https://www.robotshop.com/products/sfe-3g-tripleaxis-accelerometer-breakout-board-adxl335)  <br> <img width="100" alt="image" src="https://github.com/hpssjellis/maker100-eco/assets/5605614/1841093a-e129-428b-b9c4-5e9f02a92301">



<hr>


### Actuators

1.  $23.00 USD [1.5inch OLED Display Module 128x128 16 Gray Scale SPI/I2C Interface SSD1327 Driver Raspberry Pi/Arduino/STM32](https://www.amazon.ca/dp/B079KRC9X3?psc=1&smid=AIVH4OZ6D0Y4K&ref_=chk_typ_imgToDp) or from waveshare ($12.99 USD) [128x128, General 1.5inch OLED display Module, SKU: 13992](https://www.waveshare.com/1.5inch-oled-module.htm)      <br><img src="https://user-images.githubusercontent.com/5605614/136551247-6a7fc635-e00c-4b14-80a9-550cb4e7a7b3.png" width=100 />




1. $19.95 USD [Servo motor](https://www.pololu.com/product/1057)  <br> <img src="https://user-images.githubusercontent.com/5605614/148157541-3e94daf8-de27-4c3e-8d7f-c8c585c91d46.png" width=100 /> 


1. $23.95 USD [Stepper Motor](https://www.pololu.com/product/1204)   <br> <img src="https://user-images.githubusercontent.com/5605614/148157634-a4eaa3d7-e029-482f-940b-32558939223a.png" width=100 /> 




1. $5.95 USD Driver [A4988 Stepper Motor Driver Carrier](https://www.pololu.com/product/1182)  <br> <img src="https://user-images.githubusercontent.com/5605614/148157700-bfd155e6-13a4-4563-ab63-fa53a07535b8.png" width=100 /> 





1. $9.95 USD [Dual motor driver](https://www.pololu.com/product/2135)   <br> <img src="https://user-images.githubusercontent.com/5605614/148157752-79f4e6c2-90a0-453b-adfe-647c32886f05.png" width=100 /> 
 
1. $54.95 USD [big motor driver](https://www.pololu.com/product/1451)   <br> <img src="https://user-images.githubusercontent.com/5605614/148157798-c2236fdd-162d-4fc6-b86b-a057c165b0b8.png" width=100 /> 







<hr>




1. $12.43 *[10 Snap to pin cables](https://www.amazon.ca/Snap-Circuits-SCJW10-Project-Connectors/dp/B013DA8XH0/ref=sr_1_fkmr0_1?s=toys&ie=UTF8&qid=1504073209&sr=1-1-fkmr0&keywords=snapcircuits+10+Snap+to+pin+cables)  <br> <img src="https://user-images.githubusercontent.com/5605614/148173782-08bf870c-924d-4920-ba45-fa578b35ff0c.png" width=100 />  




1. $15.99 CAD   *[10 pack of 40 pin male female headers](https://www.amazon.ca/Pieces-2-54mm-Single-Female-Header/dp/B08CMNRXJ1/ref=sr_1_1_sspa?dchild=1&keywords=40+female+headers&qid=1633693932&sr=8-1-spons&psc=1&smid=A2FXQ4Q1N0PO2C&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExTDdVQ1JWU05MQUhJJmVuY3J5cHRlZElkPUEwNTU0NzY2MU9MREgzN0ZZN1BZRyZlbmNyeXB0ZWRBZElkPUEwNDk4MDAyMVlXRTA4UE1HTjc1QiZ3aWRnZXROYW1lPXNwX2F0ZiZhY3Rpb249Y2xpY2tSZWRpcmVjdCZkb05vdExvZ0NsaWNrPXRydWU=) <br> <img src="https://user-images.githubusercontent.com/5605614/136552450-901d787f-d894-402c-9c72-4052aad977ca.png" width=100 /> 




1. $104 USD [Arduino PortentaH7](https://store.arduino.cc/usa/portenta-h7)   <br><img src="https://user-images.githubusercontent.com/5605614/133374580-13deb749-820c-46db-bc04-597c610d2bd0.png" width=100 />

1. $63.00 USD [LoRa Vision Shield](https://store.arduino.cc/usa/portenta-vision-shield-lora)     <br><img src="https://user-images.githubusercontent.com/5605614/133374592-36bb6dfd-ec10-4796-b998-782b58ce8730.png" width=100 />

1. $14.00 USD set of 4. LoRa Antenna with u.fl connector and 915MHz for North America  *[DIYmalls 915MHz LoRa Antenna U.FL IPEX to SMA Connector Pigtail 2dBi](https://www.amazon.ca/915MHz-Antenna-Connector-Pigtail-Internet/dp/B086ZG5WBR/ref=sr_1_1_sspa?keywords=lora+915+ufl+connector&qid=1636056723&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExTVNETEoxSDlYNUEmZW5jcnlwdGVkSWQ9QTA5Mjg4NTAzSDk5RVZIS09JVks2JmVuY3J5cHRlZEFkSWQ9QTA0MDc3MDQyOEdBU0oxMEpVNk1EJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)       <br><img src="https://user-images.githubusercontent.com/5605614/148133801-89c8d12b-9897-49c0-b8fc-d1637ae5e4aa.png" width=100 />  Just found this set of 2 for $9.00 USD [DIYmall-Connector-Antenna-915MHz](https://www.amazon.com/DIYmall-Connector-Antenna-915MHz-Lora32u4/dp/B084KVYBH5)


1. $49.00 USD [Grove Starter Kit](https://www.seeedstudio.com/Seeed-XIAO-Starter-Kit-p-5378.html)     <br><img src="https://user-images.githubusercontent.com/5605614/253413674-ec64b824-19b5-45e1-9391-6949646b7628.png" width=100 />



1. $5.40 USD [Seeeduino XIAO for testing unknowns](https://www.seeedstudio.com/Seeeduino-XIAO-Arduino-Microcontroller-SAMD21-Cortex-M0+-p-4426.html)    <br><img src="https://user-images.githubusercontent.com/5605614/148135336-83ae3fb5-9482-4cf7-8f92-dc2df5fdac62.png" width=100 /> 


1. $40.50 USD *[Nano 33 Ble Sense-rev2](https://store-usa.arduino.cc/products/nano-33-ble-sense-rev2)     <br><img src="https://github.com/hpssjellis/maker100/assets/5605614/8be224a6-317a-4f63-ba6f-e348192ba914" width=100 />


1. The $115.00 USD *[NiclaVision](https://store-usa.arduino.cc/products/nicla-vision?selectedStore=us) is very good for Vision, sound and accelerometer Machine Learning <br><img src="https://user-images.githubusercontent.com/5605614/157479032-f93ac6e1-1139-4886-bf40-9dfc6e8c2b9c.png" width = 200/><br><br>


1. $25.00 USD [arduino-mkr-imu-shield](https://store-usa.arduino.cc/collections/mkr-family/products/arduino-mkr-imu-shield)  <br><img src="https://user-images.githubusercontent.com/5605614/151890361-860f98f5-b373-4114-acb1-49dbb5c61fe6.png" width=200 />





1. $35.26 CAD Arduino Starter Kit: Everything you need to get going building things with Arduino (breadboards, LED's, push buttons, resistors ...) 
[Elecrow Starter Kit for Raspberry Pi & Arduino](https://www.robotshop.com/ca/en/elecrow-starter-kit-raspberry-pi-arduino.html) <br> <img src="https://user-images.githubusercontent.com/5605614/134213537-0113a757-f7ef-424d-af33-592488304cdf.png" width=100 /> or do a generic search [https://www.amazon.com/s?k=arduino+starter+kit](https://www.amazon.com/s?k=arduino+starter+kit)


1. $35 CAD Sensor Kit: Consider getting one of the many Arduino style sensor kits on the market. 
*[Kuman 37-in-1 Sensor Kit Compatible with Arduino Raspberry Pi Mega 2560 Kits Compatible K5](https://www.amazon.ca/Kuman-sensor-arduino-raspberry-Compatible/dp/B01BY16552/ref=sr_1_29?dchild=1&keywords=maker+breadboard+wire+kit+solder&qid=1631683832&sr=8-29) <br> <img src="https://user-images.githubusercontent.com/5605614/133377159-586ccaba-56fd-42ac-8390-51c33fe5d086.png" width=100 /> 

1. $24.21 CAD Basic Solder kit: good to have   *[Plusivo Soldering Kit for Electronics (US Electrical Plug)](https://www.robotshop.com/ca/en/plusivo-soldering-kit-electronics-us-plug.html)<br> <img src="https://user-images.githubusercontent.com/5605614/134214253-310de7c1-6ebc-451d-a616-e6741990d710.png" width=100 /> 



1. $36.80 USD [Arduino MKR GPS Shield](https://store-usa.arduino.cc/products/arduino-mkr-gps-shield) <br> <img src="https://user-images.githubusercontent.com/5605614/171311357-a205b38b-f3b4-48cb-8060-c2738f25d7b3.png" width=100 />





1. $146.99  CAD *[2 in 1 750W LED Digital Soldering Station Hot Air Gun Rework Station Electric Soldering Iron for Phone PCB IC SMD BGA Welding Set 110V](https://www.amazon.ca/Digital-Soldering-Station-Electric-Welding/dp/B07T9JJZG7/ref=sr_1_6?dchild=1&keywords=pcb+oven+small+reflow&qid=1634680295&sr=8-6)   <br> <img src="https://user-images.githubusercontent.com/5605614/148177651-3b6d04e5-ed7f-454a-87cd-9512ae047215.png" width=100 /> 

1. $20.26  CAD *[Chip Quik SMDLTLFP Solder Paste Sn42/Bi57.6/Ag0.4 No-Clean Lead-Free Low Temperature Melts 138C 281F](https://www.amazon.ca/Solder-Bi57-6-No-Clean-Lead-Free-Temperature/dp/B0195V1QEI/ref=sr_1_20?crid=3HS20F6T940JL&keywords=lead+free+solder+kit&qid=1641369185&sprefix=lead+free+solder+kit%2Caps%2C137&sr=8-20)   <br> <img src="https://user-images.githubusercontent.com/5605614/148180802-beb1cd4b-7c06-4394-b47c-bdd951fbe870.png" width=100 /> 

1. $36.99  CAD *[Keadic 5Pcs Solder Wire with Rosin Core Set 0.6mm 0.8mm 1.0mm 1.2mm 1.5mm for Most Electrical Soldering, Sn 99% Ag 0.3% Cu 0.7%](https://www.amazon.ca/Keadic-Solder-Electrical-Soldering-0-11Ib/dp/B07MMZL658/ref=sr_1_33?crid=1CZZNQ74XMC4N&keywords=lead+free+solder+micro+size&qid=1641369331&sprefix=lead+free+solder+micro+sizes%2Caps%2C146&sr=8-33)   <br> <img src="https://user-images.githubusercontent.com/5605614/148181442-5d5880e6-a09d-4e67-8cb5-42fa277a67fc.png" width=100 /> 









 
</body>
</html>