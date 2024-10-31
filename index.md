
<a id="article_top"></a>

# Agenda

* IDE 開發工具的安裝&介紹
  * CS+ , e² studio , CCRH , CCRL , Smart Configurator , Renesas Flash programmer
* Smart Configurator
  * [Clock tree , Pin configuration , Peripheral configuration](#article_clock)
  * [Timer](#article_timer)
  * [GPIO](#article_gpio)
  * [external pin interrupt](#article_ext)
  * [I2C](#article_i2c)
  * [SPI](#article_spi)
  * [UART](#article_uart)
  * [PWM](#article_pwm)
  * [ADC](#article_adc)
* CS+
  * Code Compiler & programming flow ( from C code to IC ).
* Tips

---

# IDE & Debug tool

[Debug & programmer - E2 emulator](https://www.renesas.com/us/en/software-tool/e2-emulator-rte0t00020kce00000r)


[Debug & programmer - E2 emulator lite for RL78](https://www.renesas.com/us/en/software-tool/e2-emulator-lite-rte0t0002lkce00000r)


[IDE – CS+ , suggest for automotive product](https://www.renesas.com/en/software-tool/cs)


[IDE – e² studio](https://www.renesas.com/en/software-tool/e-studio)

![](img/slide_extend_RH8500.png)

![](img/slide_extend_RH8501.png)

---

# User manual : CS+


[CS+ User’s Manual](https://www.renesas.com/en/software-tool/cs)

![](img/slide_extend_RH8502.png)

![](img/slide_extend_RH8503.png)

<u>Integrated Development Environment User's Manual: RH850 Debug Tool</u>
[back to top](#article_top)

---

# User manual : e² studio


[e² studio User’s Manual](https://www.renesas.com/en/software-tool/e-studio)

![](img/slide_extend_RH8504.png)

![](img/slide_extend_RH8505.png)

---

# Compiler : CC-RH for RH850
 

[Compiler – C Compiler Package for RH850 Family [CC-RH] ](https://www.renesas.com/en/software-tool/c-compiler-package-rh850-family)

***Base on selected IDE , install the related compiler ( RH850 Compiler CC-RH for CS+ or for e² studio)**


[Compiler Licenses](https://www.renesas.com/en/software-tool/compiler-licenses)

![](img/slide_extend_RH8506.png)

![](img/slide_extend_RH8507.png)


---

# User manual : CC-RH for RH850


[Compiler CC-RH User’s Manual](https://www.renesas.com/en/software-tool/c-compiler-package-rh850-family)

![](img/slide_extend_RH8508.png)

![](img/slide_extend_RH8509.png)

---

# Smart Configurator main window

[IDE plug in  – Smart Configurator](https://www.renesas.com/en/software-tool/smart-configurator)

***Base on selected IDE , install the related Smart Configurator**

[https://www.renesas.com/en/software-tool/rh850-smart-configurator](https://www.renesas.com/en/software-tool/rh850-smart-configurator)

![](img/slide_extend_RH85014.png)

---

# Renesas Flash Programmer


[Renesas Flash Programmer (Programming GUI)](https://www.renesas.com/en/software-tool/renesas-flash-programmer-programming-gui)

![](img/slide_extend_RH85015.png)

![](img/slide_extend_RH85016.png)

---

# Create project by CS+ (RH850)

![](img/slide_extend_RH85018.png)

![](img/slide_extend_RH85017.png)

<u>Integrated Development Environment User's Manual: Project Operation</u>
[back to top](#article_top)

---

# CS+ (RH850) : main window

![](img/slide_extend_RH85019.png)

---

# CS+ (RH850) : open smart configurator

![](img/slide_extend_RH85020.png)

<span style="color:#FF0000">
Open smart configurator from IDE (CS+)<br><br> 
</span>

![](img/slide_extend_RH85021.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
<u>Smart Configurator User's Manual: RH850 API Reference</u>
<u>Smart Configurator Guide on Sample Projects for RH850/F1KM Devices</u>
[back to top](#article_top)

---

# CS+ (RH850) – CC-RH options

![](img/slide_extend_RH85022.png)

![](img/slide_extend_RH85023.png)

<u>Integrated Development Environment User's Manual: RH850 Debug Tool</u>
[back to top](#article_top)

---

# CS+ (RH850) – Debug Tool options

<span style="color:#FF0000">
Select Debug Tool<br><br>
</span>

![](img/slide_extend_RH85024.png)


![](img/slide_extend_RH85025.png)

<u>Integrated Development Environment User's Manual: RH850 Debug Tool</u>
[back to top](#article_top)

---

# Smart Config. : main window (RH850)

![](img/slide_extend_RH85026.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top) 

---

<a id="article_clock"></a>

# Smart Config. - Clock

![](img/slide_extend_RH85027.png)


<span style="color:#FF0000">
Select clock for PLL0 , PLL1<br><br> 
</span>

![](img/slide_extend_RH85029.png)

![](img/slide_extend_RH85028.png)

![](img/slide_extend_RH85030.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85031.png)

<span style="color:#FF0000">
use MainOSC (external osc) will enable X1 , X2 pin<br><br>
</span> 

![](img/slide_extend_RH85032.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : add component

![](img/slide_extend_RH85033.png)

![](img/slide_extend_RH85034.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_timer"></a>

# Smart Config. – Interval Timer

![](img/slide_extend_RH85036.png)

![](img/slide_extend_RH85035.png)

![](img/slide_extend_RH85037.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
TAUxx timer difference<br><br>
</span>

![](img/slide_extend_RH85038.png)


<span style="color:#FF0000">
TAUxx timer clock source<br><br>
</span>

![](img/slide_extend_RH85039.png)

![](img/slide_extend_RH85040.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85041.png)

![](img/slide_extend_RH85042.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Press <b>[Generate Code]</b> in Smart config. will automatically generate driver source code under CS+ project<br><br>
</span> 

![](img/slide_extend_RH85044.png)

![](img/slide_extend_RH85043.png)

![](img/slide_extend_RH85045.png)


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Re-build project , will see the build result is complete without error<br><br>
</span>

![](img/slide_extend_RH85046.png)

![](img/slide_extend_RH85047.png)


<span style="color:#FF0000">
This will be project main code : <br>
<b>r_cg_main.c</b><br><br>
</span>

![](img/slide_extend_RH85048.png)


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85049.png)

![](img/slide_extend_RH85051.png)

![](img/slide_extend_RH85052.png)

![](img/slide_extend_RH85050.png)

![](img/slide_extend_RH85053.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_TAUJ0_0_Start(); 
```

![](img/slide_extend_RH85054.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85055.png)

![](img/slide_extend_RH85056.png)

![](img/slide_extend_RH85059.png)


<span style="color:#FF0000">
Add TIMER interrupt function under <br><br>
</span>  

```
r_Config_TAUJ0_0_interrupt()
```

![](img/slide_extend_RH85058.png)

![](img/slide_extend_RH85057.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. : Timer delay

![](img/slide_extend_RH85061.png)

![](img/slide_extend_RH85060.png)


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – Generate code

<span style="color:#FF0000">
[Generate Code] in Smart configurator , will re-generate driver code <b><u>every time</b></u><br><br>
</span> 

![](img/slide_extend_RH85062.png)

![](img/slide_extend_RH85063.png)



<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ - driver code

<span style="color:#FF0000">
Put custom application code , variable , declaration , between these 2 comment , will merge into driver code when execute [Generate Code] in Smart config<br><br>
</span>  

![](img/slide_extend_RH85064.png)

![](img/slide_extend_RH85065.png)

![](img/slide_extend_RH85066.png)



<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_gpio"></a>

# Smart Config. – GPIO

![](img/slide_extend_RH85067.png)

![](img/slide_extend_RH85068.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Select target GPIO port , to set GPIO input , output<br><br>
</span>>

![](img/slide_extend_RH85069.png)

![](img/slide_extend_RH85070.png)

![](img/slide_extend_RH85071.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85072.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – GPIO output

![](img/slide_extend_RH85074.png)

![](img/slide_extend_RH85073.png)

![](img/slide_extend_RH85075.png)

![](img/slide_extend_RH85076.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – GPIO input

![](img/slide_extend_RH85078.png)

![](img/slide_extend_RH85077.png)

![](img/slide_extend_RH85079.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# RH850 F1KM-S4 example code

Y-ASK-RH850F1KM-S4-V3

[https://www.renesas.com/en/products/microcontrollers-microprocessors/rh850-automotive-mcus/y-ask-rh850f1km-s4-v3-rh850f1km-s4-and-rh850f1km-s2-starter-kit](https://www.renesas.com/en/products/microcontrollers-microprocessors/rh850-automotive-mcus/y-ask-rh850f1km-s4-v3-rh850f1km-s4-and-rh850f1km-s2-starter-kit)

Y-ASK-RH850F1KM-S4-V3 Software Package

[https://www.renesas.com/document/sws/y-ask-rh850f1km-s4-v3-software-package?language=en&r=1261056](https://www.renesas.com/document/sws/y-ask-rh850f1km-s4-v3-software-package?language=en&r=1261056)

![](img/slide_extend_RH85080.png)

![](img/slide_extend_RH85081.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_ext"></a>

# Smart Config. – external int.

![](img/slide_extend_RH85082.png)

![](img/slide_extend_RH85083.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85084.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85085.png)

![](img/slide_extend_RH85086.png)


<span style="color:#FF0000">
Add code when trigger external interrupt INTP2<br><br>
</span>

![](img/slide_extend_RH85088.png)

![](img/slide_extend_RH85089.png)

<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_INTC_INTP2_Start();
```

![](img/slide_extend_RH85087.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_i2c"></a>

# Smart Config. – I2C

![](img/slide_extend_RH85090.png)

![](img/slide_extend_RH85091.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85092.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85093.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH85094.png)

![](img/slide_extend_RH85095.png)

![](img/slide_extend_RH85096.png)

![](img/slide_extend_RH85097.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_RIIC0_Start();
```

![](img/slide_extend_RH85098.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_spi"></a>


# Smart Config. – SPI (CSIG0)

![](img/slide_extend_RH85099.png)

![](img/slide_extend_RH850100.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850101.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – CPOL/CPHA

* CPOL :
  * 0 : clock idle at LOW
  * 1 : clock idle at HIGH
* CPHA :
  * 0 : 1^st^ EDGE
  * 1 : 2^ND^ EDGE

![](img/slide_extend_RH850118.png)

![](img/slide_extend_RH850119.png)


| CPOL | CPHA | mode | Type |
|:--:|:--:|:--:|:--:|
| 1  | 1 | 3 | 1 |
| 0  | 1 | 1 | 2 |
| 1  | 0 | 2 | 3 |
| 0  | 0 | 0 | 4 |


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850102.png)

![](img/slide_extend_RH850103.png)

![](img/slide_extend_RH850104.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_CSIG0_Start();
```

![](img/slide_extend_RH850105.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – SPI (CSIH0)

![](img/slide_extend_RH850106.png)

![](img/slide_extend_RH850107.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850109.png)

![](img/slide_extend_RH850108.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850110.png)

![](img/slide_extend_RH850111.png)

![](img/slide_extend_RH850112.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_CSIH0_Start();
```

![](img/slide_extend_RH850113.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – CSIG vs CSIH

![](img/slide_extend_RH850115.png)

![](img/slide_extend_RH850116.png)

![](img/slide_extend_RH850114.png)

![](img/slide_extend_RH850117.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_uart"></a>

# Smart Config. – UART0

![](img/slide_extend_RH850120.png)

![](img/slide_extend_RH850121.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850122.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850123.png)

![](img/slide_extend_RH850124.png)

![](img/slide_extend_RH850125.png)

![](img/slide_extend_RH850127.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_UART0_Start();
```

![](img/slide_extend_RH850126.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_pwm"></a>

# Smart Config. – PWM

![](img/slide_extend_RH850128.png)

![](img/slide_extend_RH850129.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850131.png)

![](img/slide_extend_RH850130.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850132.png)

![](img/slide_extend_RH850134.png)

![](img/slide_extend_RH850133.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850135.png)

![](img/slide_extend_RH850137.png)


PWM duty adjust example

![](img/slide_extend_RH850136.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_TAUB0_Start();
```

![](img/slide_extend_RH850138.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<a id="article_adc"></a>

# Smart Config. – ADC

![](img/slide_extend_RH850139.png)

![](img/slide_extend_RH850140.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850141.png)

![](img/slide_extend_RH850142.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – ADC sampling

![](img/slide_extend_RH850143.png)

![](img/slide_extend_RH850144.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Smart Config. – ADC

![](img/slide_extend_RH850145.png)

![](img/slide_extend_RH850146.png)

![](img/slide_extend_RH850149.png)

![](img/slide_extend_RH850147.png)


<span style="color:#FF0000">
Need to manual add driver start API , ex : <br><br>
</span>

```
R_Config_ADCA0_ScanGroup1_Start();
```

![](img/slide_extend_RH850148.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Add root path in Path Edit


<span style="color:#FF0000">
After generate driver code , compile project under CS+ , if meet compile error (not open iodefine.h) , save and close CS+ project and re-open<br><br>
</span>

![](img/slide_extend_RH850150.png)

![](img/slide_extend_RH850151.png)


<span style="color:#FF0000">
Check CC-RH (Build Tool) > Common Options > Additional include paths , make sure already include the new add driver path (ex : TAUJ0_0 )<br><br>
</span>

![](img/slide_extend_RH850153.png)


<span style="color:#FF0000">
add root path under project to fix compile error issue<br><br>
</span>

```
.\
.
```

![](img/slide_extend_RH850152.png)


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# Add main loop

<span style="color:#FF0000">
Need to manual add main loop , ex : <br><br>
</span>

```
while(1)
{
}
```

![](img/slide_extend_RH850154.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
If not add while loop under main code , program will <b>stop</b> at exit in csstart.asm<br><br>
</span> 

![](img/slide_extend_RH850155.png)


<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# To fix INTERRUPT NOT WORK ISSUE

<span style="color:#FF0000">
Remove [ ; ] , to enable table reference method<br><br>
</span>

```
USE_TABLE_REFERENCE_METHOD .set 1
```

![](img/slide_extend_RH850156.png)


![](img/slide_extend_RH850157.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Add [ ; ] , to disable default interrupt<br><br> 
</span>

```
;.section "EIINTTBL", const
;.align 512
;.dw #_Dummy_EI ; INT0
;.dw #_Dummy_EI ; INT1
;.dw #_Dummy_EI ; INT2
;.rept 512 - 3
;.dw #_Dummy_EI ; INTn
;.endm
```

![](img/slide_extend_RH850158.png)

![](img/slide_extend_RH850159.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

![](img/slide_extend_RH850160.png)

<span style="color:#FF0000">
Add [ .const ]<br><br>   
</span>

```
mov #__sEIINTTBL.const , r6 
```

![](img/slide_extend_RH850161.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
Open [<b>Section</b>] modify under [<b>Link Options</b>] in [<b>CC-RH Property</b>]<br><br>
</span>

![](img/slide_extend_RH850162.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

<span style="color:#FF0000">
REMOVE [<b>EIINTTBL</b>] in Section Settings
1. Select [on Section : EIINTTBL]
2. Select [Remove]
</span>

![](img/slide_extend_RH850164.png)


<span style="color:#FF0000">
ADD [address 0x200] in Section Settings
1. Select on [blank in Address]
2. Select [Add]
3. Key in [200]<br><br>
</span>

![](img/slide_extend_RH850163.png)


<span style="color:#FF0000">
ADD [<b>EIINTTBL.const</b>] in Section Settings
1. Select on [blank in Section] (addr : 0x200) 
2. Select [Add]
3. Key in [EIINTTBL.const]<br><br>
</span>

![](img/slide_extend_RH850165.png)


<span style="color:#FF0000">
Final section table result<br><br>
</span>

![](img/slide_extend_RH850166.png)

<u>RH850 Smart Configurator User's Guide: CS+</u>
[back to top](#article_top)    

---

# CS+ - entry debug mode


<span style="color:#FF0000">
Make sure <u><b>[DISCONNECT]</b></u> CS+ project before REMOVE DEBUGGER tool <br><br>
</span> 

![](img/slide_extend_RH850167.png)

download program after rebuild
![](img/slide_extend_RH850170.png)


debug function
![](img/slide_extend_RH850168.png)
![](img/slide_extend_RH850169.png)
![](img/slide_extend_RH850172.png)
![](img/slide_extend_RH850173.png)

![](img/slide_extend_RH850171.png)


<u>Integrated Development Environment User's Manual: RH850 Debug Tool</u>
[back to top](#article_top)    

---

# Renesas Flash Programmer

![](img/slide_extend_RH850174.png)

![](img/slide_extend_RH850176.png)

![](img/slide_extend_RH850175.png)

![](img/slide_extend_RH850177.png)

<u>Renesas Flash Programmer V*.** Flash memory programming softwareUser's Manual </u>
[back to top](#article_top)   

---

<a id="article_tips"></a>

# Tips : Convert to Hex


![](img/slide_extend_RH850178.png)

![](img/slide_extend_RH850179.png)


---

# Tips : Emulator power on MCU

![](img/slide_extend_RH850180.png)

![](img/slide_extend_RH850181.png)


---

# Tips : Set CLOCK (F1KM-S1)

![](img/slide_extend_RH850182.png)

![](img/slide_extend_RH850183.png)


---

# Tips : map file display


![](img/slide_extend_RH850190.png)

<span style="color:#FF0000">
Function address<br>
size display<br>
location assignment<br>
Code size <br>
RAM size display<br><br>
</span>

![](img/slide_extend_RH850191.png)


---

# Tips : section message display

![](img/slide_extend_RH850192.png)

Display section message

![](img/slide_extend_RH850193.png)


---

# Tips : size display display in output window

![](img/slide_extend_RH850194.png)


![](img/slide_extend_RH850195.png)


---

# Tips : Backup times (generate code)

![](img/slide_extend_RH850196.png)


---

# Tips : section define modify

![](img/slide_extend_RH850197.png)

<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section define (const)


<span style="color:#FF0000">
ADD [<b>privateData.const</b>] in Section Settings<br>
1. Select on [.data] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.const</b>] <br><br>
</span>  

![](img/slide_extend_RH850198.png)


| item | note |
|:--:|:--:|
| data  | variables with initial value  |
| bss  | variables with no initial value  |
| text  | program code  |
|<span style="color:#FF0000"><b>const</b></span>   | <span style="color:#FF0000"><b>constant data</b></span>  |

![](img/slide_extend_RH850199.png)

Code assignment example
![](img/slide_extend_RH850200.png)

<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section define (data)

<span style="color:#FF0000">
ADD [<b>privateData.data</b>] in Section Settings<br>
1. Select on [.data] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.data</b>] <br><br>
</span>

![](img/slide_extend_RH850201.png)


| item | note |
|:--:|:--:|
| <span style="color:#FF0000"><b>data</b></span>  | <span style="color:#FF0000"><b>variables with initial value</b></span>  |
| bss  | variables with no initial value  |
| text  | program code  |
|const   | constant data  |


![](img/slide_extend_RH850203.png)

Code assignment example
![](img/slide_extend_RH850202.png)


<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section define (bss)

<span style="color:#FF0000">
ADD [<b>privateData.bss</b>] in Section Settings<br>
1. Select on [.bss] in Section<br>
2. Select [Add]<br>
3. Key in [<b>privateData.bss</b>] <br><br>
</span>

![](img/slide_extend_RH850204.png)


| item | note |
|:--:|:--:|
| data  | variables with initial value  |
| <span style="color:#FF0000"><b>bss</b></span>  | <span style="color:#FF0000"><b>variables with no initial value</b></span>  |
| text  | program code  |
|const   | constant data  |

![](img/slide_extend_RH850206.png)

Code assignment example
![](img/slide_extend_RH850205.png)


<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section define (not assigned address)

<span style="color:#FF0000">
New add custom define section as below <br>
Also able to define the address base on application<br><br>
</span>


![](img/slide_extend_RH850207.png)

Code assignment example
![](img/slide_extend_RH850208.png)

check the address in map file
![](img/slide_extend_RH850209.png)


<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section define (assigned address)

<span style="color:#FF0000">
New add custom define section as the capture<br>
Also able to define the address base on application<br><br>
</span>

![](img/slide_extend_RH850210.png)

Code assignment example
![](img/slide_extend_RH850211.png)

check the address in map file
![](img/slide_extend_RH850212.png)

<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

# Tips : section allocation , size

![](img/slide_extend_RH850213.png)

CC\-RH Compiler User's Manual

# Tips : project split


<span style="color:#FF0000">
Use [<b> Build Mode Setting </b>] , to split different macro in different project setting if necessary<br><br>
</span>

![](img/slide_extend_RH850214.png)

Project split example , modify the projec name
![](img/slide_extend_RH850215.png)

![](img/slide_extend_RH850216.png)

![](img/slide_extend_RH850217.png)

Add the macro define for extra project 
![](img/slide_extend_RH850218.png)

<u>CC-RH Compiler User's Manual</u>
[back to top](#article_top)    

---

