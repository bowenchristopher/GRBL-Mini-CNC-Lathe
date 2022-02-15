# GRBL Mini CNC Lathe
Part list and Instructions to convert a TAIG L1015 MICRO LATHE II into a GRBL controlled Mini CNC  Lathe

![ezgif-2-576722ba00](https://user-images.githubusercontent.com/41913546/153733846-d33d92b0-eded-4820-ba22-c7621c50b2a4.gif)

# Project Overview
This project was inspired by Ed Fraizer's Post on GRABCAD, 
<br> 
A link to the original post can be found <a href="https://grabcad.com/library/taig-micro-lathe-ii-cnc-conversion-1">here</a>
<br>
All CAD models and the original idea are credited to Ed Fraizer
<br>
That being said all, of the models in this build, have been revised to improve machinability and assembly.

# Machine Review
This is a great mini CNC lathe for the cost but, it has its limitations.
Don't expect to take large passes .003 is a healthy cut. Backlash in the Z-axis means cutting passes can only be taken in one direction. With a 5:1 reduction on the Z-axis stepper motor, the Z-axis will stall before the spindle does. After some testing, the machine can cut brass and aluminum well, ferrous metals are tougher but, it does cut.  Building the lathe was a great project and I couldn't buy a better machine for the ~650.00 Price tag. 

# Components to Manufacture
All models are made to be machined on a 3 axis CNC in a single setup, 
<br> 
Included setups in the F3d files are for a Nomad 3 CNC using a 1/8 endmill milling Corian or Delrin
<br> 
More information on the parts can be found in the individual part files
<table>
  <tr>
    <th> Part Number </th> 
    <th>Part Name</th>
    <th>Link</th>
  </tr>
  <tr>
    <td> 1 </td> 
    <td> Dove Tail </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Dove_Tail_For_Main_Plate.f3d </td> 
  </tr> 
  <tr> 
    <td> 2 </td> 
    <td> Main Plate </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Main_Plate.f3d </td> 
  </tr> 
  <tr> 
    <td> 3 </td> 
    <td> Bar Clamp </td>
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Bar_Clamp.f3d </td> 
  </tr> 
  <tr> 
    <td> 4 </td> 
    <td> Mounting Plate </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Mounting_Plate.f3d </td> 
  </tr> 
  <tr> 
    <td> 5 </td> 
    <td> X-axis Bracket </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/X_Axis_Bracket.f3d </td> 
  </tr> 
  <tr> 
    <td> 6 </td> 
    <td> Z-axis Bracket </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Z_Axis_Bracket.f3d </td> 
  </tr> 
  <tr> 
    <td> 7 </td> 
    <td> Z-axis Adapter for 5:1 Nema 17 motor </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Z_Axis_Nema17_Adaptor.f3d </td> 
  </tr> 
</table>

# Part List
<table>
  <tr>
    <th>Part Name:</th>
    <th>Link:</th>
    <th>USD Cost:</th>
  </tr>
  <tr>
    <td>Pulley for brushless spindle motor</td>
    <td>https://www.amazon.com/dp/B07C4YJK42?psc=1&ref=ppx_yo2_dt_b_product_details</td>
    <td>12.50</td>
  </tr>
  <tr>
    <td>NEMA 23 Bracket for Brushless spindle motor</td>
    <td>https://www.amazon.com/dp/B00Q6GIO5K?psc=1&ref=ppx_yo2_dt_b_product_details</td>
    <td>7.41</td>
  </tr>
  <tr>
    <td>Quick Change tool Post</td>
    <td>https://www.amazon.com/dp/B018QMTXB0?psc=1&ref=ppx_yo2_dt_b_product_details</td>
    <td>35.83</td>
  </tr>
  <tr>
    <td>5:1 Planetary stepper for Z-axis (Minimum gear ration greater than 5:1 preferred)</td>
    <td>https://www.amazon.com/dp/B00WATUFIG?psc=1&ref=ppx_yo2_dt_b_product_details</td>
    <td>39.01</td>
  </tr>
  <tr>
    <td>5mm to 5mm shaft for X-axis coupler</td>
    <td>https://www.amazon.com/dp/B06X9Y65XD?ref=ppx_yo2_dt_b_product_details&th=1</td>
    <td>8.49</td>
  </tr>
  <tr>
    <td>Nema 17 motor for X-axis</td>
    <td>https://www.amazon.com/gp/product/B00PNEQKC0/ref=ppx_yo_dt_b_asin_title_o04_s00?ie=UTF8&psc=1</td>
    <td>13.99</td>
  </tr>
  <tr>
    <td>L1015 MICRO LATHE II</td>
    <td>https://taigtools.com/product/micro-lathe-ii-l1015/</td>
    <td>359.81</td>
  </tr>
  <tr>
    <td>¼ to ¼ Coupler for Z-Axis</td>
    <td>https://www.amazon.com/6-35x6-35mm-Flexible-Coupling-Motor-Coupler/dp/B00N732LVI/ref=pd_bxgy_img_1/134-1649443-8906817?pd_rd_w=HSHsZ&pf_rd_p=6b3eefea-7b16-43e9-bc45-2e332cbf99da&pf_rd_r=Y0Y2SZ2E20P0KSZSTYPR&pd_rd_r=96f90020-fe21-4465-81a6-ebcc3091f655&pd_rd_wg=uoCXR&pd_rd_i=B00N732LVI&psc=1</td>
    <td>8.39</td>
  </tr>
  <tr>
    <td>Arduino and GRBL shield CNC Controller </td>
    <td>https://www.amazon.com/gp/product/B08K34T4Q2/ref=ppx_yo_dt_b_asin_title_o01_s00?ie=UTF8&psc=1</td>
    <td>25.00</td>
  </tr>
  <tr>
    <td>BLD120A 24V 120W BLDC Motor Driver</td>
    <td>https://www.robotdigg.com/product/1234/BLD120A-24V-120W-BLDC-Motor-Driver</td>
    <td>25.00</td>
  </tr>
  <tr>
    <td> 125W BLDC Motor </td>
    <td> https://www.robotdigg.com/product/1352/NEMA23-Brushless-DC-Motor-60W,-125W-or-188W </td>
    <td> 32.00 </td>
  </tr>
  <tr> 
    <td> Total </td> 
    <td> </td> 
    <td> 567.42 </td> 
  </tr> 
</table>

# Required Screws and T-Nuts
<table>
  <tr>
    <th>Part Name</th>
    <th>Quantity</th>
    <th>Notes </th>
  </tr>
  <tr>
    <td>10-32 square nuts</td>
    <td>10</td>
    <td>Used to attach Nema 23 bracket to lathe and quick change adapter</td>
  </tr>
  <tr>
    <td> 3/16 10-32 screw </td> 
    <td> 6 </td> 
    <td> Used to attach brushless DC motor to bracket and Quick Change adapter </td> 
  </tr> 
  <tr>
    <td>M3×6mm Machine screws</td>
    <td>4</td>
    <td> Used to attach Z-axis stepper motor </td> 
  </tr>
  <tr>
    <td>M3x54mm Machine screw</td>
    <td>4</td>
    <td> Used to attach X-axis stepper motor </td> 
  </tr>
  <tr>
    <td>M6X12mm</td>
    <td>12</td>
    <td> Used to assemble mounting plate and brackets </td> 
  </tr> 
  <tr>
    <td>M6X8mm</td>
    <td>3</td>
    <td> These may need to be shortened to fit cross slide Tslot on lathe cross slide </td> 
  </tr> 
</table>

# Wiring Diagram
<br> 
In process

# Lathe Chuck and Tooling
<table>
  <tr>
    <th>Part Name:</th>
    <th>Link:</th>
    <th>USD Cost:</th>
  </tr>
  <tr>
    <td>Self centering 3 Jaw Scroll Chuck</td>
    <td>https://taigtools.com/product/3-jaw-3-1-4-dia-self-centering-scroll-chuck/</td>
    <td>75.30</td>
  </tr>
  <tr>
    <td>HSS Tool Blanks</td>
    <td>https://www.amazon.com/PROLINEMAX-Square-Lathe-Cutter-Blank/dp/B07F3GQV13</td>
    <td>17.99</td>
  </tr>
  <tr>
    <td> Total </td> 
    <td> </td> 
    <td> 93.29 </td> 
  </tr> 
</table>

# Get Started with the Mini CNC Lathe
![IMG_0364](https://user-images.githubusercontent.com/41913546/153736142-b2daa419-4b97-4c72-87cd-f94900b01ae1.JPG)
<table>
   <tr>
    <th>File </th>
    <th>Link </th>
    <th>Notes </th>
  </tr>
  <tr>
    <td> GRBL Lathe Post Processor </td>
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/Modifed_Grbl_Post.cps </td>
    <td> Post changed to fix an apparent bug</td>
  </tr>
  <tr> 
    <td> Test Chess Pawn </td> 
    <td> https://github.com/bowenchristopher/GRBL-Mini-CNC-Lathe/blob/main/test_pawn.f3d </td> 
    <td> Test Pawn with Demo Setup</td> 
  </tr>
</table> 

# Future Improvements
In no particular order. A true Lead Screw on the X-axis and Z-axis could make the lathe more repeatable.
A chip cover over the ways would prolong the life of the machine. Adding a larger BLDC motor or Servo motor could make a more useful mini-lathe. 
A higher gear ratio on the Z-axis stepper motor might reduce some of the directional backlash.
