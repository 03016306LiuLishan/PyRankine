# PyRankine

The **step-by-step codes** of the rankine cycle simulator to demonstrate:

  * **Data Structures + Algorithms = Programs** 
  * **Computational Thinking** 

    * step 0 :    Zero @  Data Structures,Program architecture, Algorithms(The Ideal Rankine Cycle)
                    
            simple data type and expression only 

    * step 1 :   Basic @  Data Structures,Program architecture, Algorithms(The Ideal Rankine Cycle)
                    
           list,dict,function
     
    * step 2 : Forward @  Data Structures,Program architecture, Algorithms(The Ideal Rankine Cycle)
     
           object-oriented programming
     
    * step 3 : Forward @  Data Structures,Program architecture, Algorithms(The Ideal Rankine Cycle)

     
      [Rankine Cycle Representation of CSV or JSON File](./step3/README.md)
     
          object-oriented programming and data files: 
                   
          step3-csv: csv file 

          step3-json: json file
      
    * step 4 : Advanced @  Data Structures,Program architecture, Algorithms

      [The UML diagram of the step4-json](./step4/UML-STEP$-JSON.md)
                
          object-oriented programming,general module
                      
          Michael J . Mora. Chapter 8 : Vapour Power Systems 
              1) Example 8.1: The Ideal Rankine Cycle, Page 438
              2) Example 8.5: A Regenerative Cycle with Open Feedwater Heater,Page 456

          step4-csv: csv file

          step4-json: json file       

          step4-json-dict: json file  and  __init__ device with dict,modified the component class       

## Run

```bash
>cd step0/1/2/3/4
>python rankine.py
``` 

**You need to**
 
* reading the codes
* understanding computational thinking and programming skills
* programming one solution to the  rankine cycle 

## Dependencies：SEUIF97

* IAPWS-IF97 high-speed shared library

  * https://github.com/PySEE/SEUIF97

## Example Rankine Cycles

* Michael J . Mora. Fundamentals of Engineering Thermodynamics(7th Edition). John Wiley & Sons, Inc. 2011

      Chapter 8 : Vapour Power Systems 
        1) Example 8.1: Analyzing an Ideal Rankine Cycle, Page 438
        2) Example 8.5：A Regenerative Cycle with Open Feedwater Heater, Page 456

####  Example 8.1: Analyzing an Ideal Rankine Cycle  Page 438

   * Steam is the working fluid in an ideal Rankine cycle. 

   * Saturated vapor enters the turbine at 8.0 MPa 
   
   * Saturated liquid exits the condenser at a pressure of 0.008 MPa. 

   * The net power output of the cycle is 100 MW.

   * Cooling water enters the condenser at 15°C and exits at 35°C.

![rankine81](./step4/img/rankine81.jpg)

* Determine for the cycle

  * the thermal efficiency, %

  * the back work ratio,  %

  * the mass flow rate of the steam,in kg/h,

  * the rate of heat transfer, Qin, into the working fluid as it passes through the boiler, in MW,

  * the rate of heat transfer, Qout, from the condensing steam as it passes through the condenser, in MW,

  * the mass flow rate of the condenser cooling water, in kg/h

####  Example 8.5: A Regenerative Cycle with Open Feedwater Heater, Page 456

Consider a regenerative vapor power cycle with one open feedwater heater.

* Steam enters the turbine at 8.0 MPa, 480°C and expands to 0.7 MPa, 

* Some of the steam is extracted and diverted to the open feedwater heater operating at 0.7 MPa. 

* The remaining steam expands through the second-stage turbine to the condenser pressure of 0.008 MPa

* Saturated liquid exits the open feedwater heater at 0.7 MPa. 

* The isentropic efficiency of each turbine  stage is 85% and each pump operates isentropically. 

If the net power output of the cycle is 100 MW, determine

* (a) the thermal efficiency  %

* (b) the mass flow rate of steam entering the first turbine stage, in kg/h.

If the mass flow rate of steam entering the first-stage turbine were 150 kg/s 

* (a) what would be the net power, in MW

* (b) the fraction of steam extracted, y? 

![rankine85](./step4/img/rankine85.jpg)

Engineering Model:

1. Each component in the cycle is analyzed as a steady-state control volume. The control volumes are shown in the accompanying sketch by dashed lines.


2. All processes of the working fluid are internally reversible, except for the expansions through the two turbine stages and mixing in the open feedwater heater.


3. The turbines, pumps, and feedwater heater operate adiabatically.


4. Kinetic and potential energy effects are negligible.


5. Saturated liquid exits the open feedwater heater, and saturated liquid exits the condenser.

## Reference

* Computational thinking

  * Algorithms + Data Structures = Programs: https://en.wikipedia.org/wiki/Algorithms_%2B_Data_Structures_%3D_Programs

  * Computational thinking: https://en.wikipedia.org/wiki/Computational_thinking

* Modeling and Simulation of Engineering Systems

  * R Sinha, Christiaan J. J. Paredis. etc. **Modeling and Simulation Methods for Design of Engineering Systems**. Transactions of the ASME[J]. 2001.03(1):84-91

  * Wolfgang Borutzky. Bond Graph Modelling of Engineering Systems：Theory, Applications and Software Support. Springer Science Business Media, LLC 2011

  * OpenModelica: An open-source Modelica-based modeling and simulation environment https://openmodelica.org/

    * https://github.com/OpenModelica

  * MATLAB：Simscape https://cn.mathworks.com/products/simscape.html  

  * Michael M.Tiller (作者),  刘俊堂等译. Modelica多领域物理系统建模入门与提高, 航空工业出版社(第1版),2017.05

  * 王中双. 键合图理论及其在系统动力学中的应用, 哈尔滨工程大学出版社,2007.08

* ThermoCycle Simulator 

    * Maarten Winter: pyDNA https://github.com/mwoc/pydna

    * ORC Modeling Kit: https://github.com/orcmkit/ORCmKit

    * ACHP: https://github.com/TSTK/ACHP 

    * Rankine Cycle(Steam Turbine) http://cn.mathworks.com/help/physmod/simscape/examples/rankine-cycle-steam-turbine.html

*  Electronic circuit simulator 

   * Jan M. Rabaey: SPICE http://bwrcs.eecs.berkeley.edu/Classes/IcBook/SPICE/

      * SPICE: https://en.wikipedia.org/wiki/SPICE

   * ahkab：a SPICE-like electronic circuit simulator written in Python https://github.com/ahkab/ahkab

   * 杨华中等. 电子电路的计算机辅助分析和设计方法（第二版），清华大学出版社，北京，2008.02

* Others

  * OpenMDAO: An open-source MDAO framework written in Python  http://openmdao.org/

  * ASCEND4: The ASCEND Modelling and Simulation Environment  http://ascend4.org/

## Appendix

* The Jupyter Notebook of Ideal Rankine Cycle

  * Step0 http://nbviewer.jupyter.org/github/PySEE/PyRankine/blob/master/notebook/IdealRankineCycle-Step0.ipynb

  * Step1 http://nbviewer.jupyter.org/github/PySEE/PyRankine/blob/master/notebook/IdealRankineCycle-Step1.ipynb

  * Step2 http://nbviewer.jupyter.org/github/PySEE/PyRankine/blob/master/notebook/IdealRankineCycle-Step2.ipynb

```bash
>StartNB.bat
```