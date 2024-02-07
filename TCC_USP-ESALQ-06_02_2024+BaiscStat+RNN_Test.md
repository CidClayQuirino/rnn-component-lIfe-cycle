Untitled
================

# Component Life Projection Based on a Deep Learning Model for Mobile Mining Equipment

## 1.0 Introduction

Manufacturers and dealers around the world, are constantly approached by
customers about how to consistently achieve best resulting in
anticipation of component failures. One way to move forward on this
issue is using the condition monitoring process output. In certain
mining assets components (Ex: Diesel Engines/Transmission and major
components) used in mobile equipment models this measurement can be done
directly through “Electronic System” from online monitoring system data
or from telemetry.

In these cases, components have highly predictability parameters, but in
other type of components like Cylinders, Pumps and minor components is
not possible detect failures in fact from this path mainly due a few
strong parameters to monitor.

Hence the CMMS (Conditions Monitoring Management System) needs to be
improved using other practices to evaluate any changes in component
behavior and acting before failure. On the other hand, engineering team
need to be care to not have a high investment in comparison to cost
saving. Some mining customer in the north of Brazil is seeing a good
results applying the best practice developed jointly by Dealer –
monitoring the behavior of cylinder parameters to prevent unplanned
failure and reducing asset downtime.

This study intend the importance of this best practices, and wants
improve this solution using Artificial Intelligence (AI) and Neural
Network to get data directly from a sender installer on this minor
components to detect very early any changes on temperature and
vibration.

## 2.0 Project Description

### 2.1 Old insight (manual data collection/analysis)

This best practice is part of Hydro’s and Sotreq’s effort to improve the
monitoring and troubleshooting process for cylinders based on real case
of CMMS - Condition Monitoring Management System application.

The development of alternative monitoring/troubleshooting was based on
the customer’s need to reduce time to fix and improve the fleet
availability/productivity.

Thermography, along with other operational tests, provided the means to
monitor and provide detection capabilities before catastrofic failure
and helped define future intervention in the HEX, based on the HEX
monitoring of component in tool cylinder of a 390F.

Basic Operation:

There is literature that discribes the operational verification
(KENR9995-07), cylinder drop - verification - empty bucket
(KENR9995-00)“and cycle speed - verification (KENR9995-02) to evaluate
the lifting cylinders of the boom.

Figure 1. Fluid Temperature ![Figure 1. Fluid
Temperature](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%201.%20Fluid%20Temperature.png)

The equipment was positioned to perform the cylinder drop test (Figure
2), and the boom lift cylinder was measured from the rod fixing pin to
the cylinder liner fixing pin, and after 5 minutes with the engine off,
no displacement of the cylinder rod was identified through the
measurement (the cylinders kept the same measurements).

Figure 2. Position of the drop test equipment ![Figure 2. Imagem
Escavadeira Hydro Hidraulico Antes
Falha](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Imagem%20Escavadeira%20Hydro%20Hidraulico%20Antes%20Falha.png)
Before performing the cycle speed test, the pump relief pressures were
checked for the boom lift function, and found 5206 psi for the 01# pump
and 5173 psi for the 02# pump (Figure 3).

Figure 3 - Pump Pressure Test ![Figure 3. Pump
Pressure](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%203.%20Pump%20Pressure.png)

Note: The pressures were a little above the specified, but not enough to
change the test result.

The machine implement was positioned as oriented by CAT literature to
perform the cylinder cycle speed test and the cylinder cycle time from
soil to fully extended rod position, and ir was collected 7.26 seconds.

The cylinder speed procedure specifies a time of 5.8 ± 0.5 for a new
cylinder, a maximum of 7.5 seconds for reconditioning the cylinder and a
maximum of 8.7 seconds for service limit for the boom cylinder (Figure
05).

Figure 4 - Pump Pressure Test ![Figure 4 - Pump Pressure
Test](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%204%20-%20Pump%20Pressure%20Test.png)

The procedure for setting the cycle time defined in Troubleshooting CAT
was carried out, and the lifting time specified by the lower operation
and maintenance manual was detected.

After finishing the cycle time and pressure tests, the thermography test
was performed, with the aid of the thermographic camera, so that the
differential temperature of the cylinders was recorded.

Using thermography on the EH3201, a thermal differential was identified
in the boom cylinder on the right side, as can be seen in Figure 6a with
a temperature differential of 4.7°C in relation to the left side.

Figure 5a. Thermography on the EH3201 Lift Cylinders


src="D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%205a.%20Thermography%20on%20the%20EH3201%20Lift%20Cylinders.png"
alt="Figure 5a. Thermography on the EH3201 Lift Cylinders" />
<figcaption aria-hidden="true">Figure 5a. Thermography on the EH3201
Lift Cylinders</figcaption>


Figure 5b. EH3201 on the operation front being inspected by predictive
team

![Figure 5b. EH3201 on the operation front being inspected by predictive
team](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%205b.%20EH3201%20on%20the%20operation%20front%20being%20inspected%20by%20predictive%20team.png)
The hottest points of the cylinders were captured by the camera and it
was observed that the lifting cylinder l/d of the boom has a temperature
of 5° c above the lifting cylinder l/e (Figure 7).

Figure 6. Thermographic image indicating a 5° c difference between the
hottest points of the boom lift cylinders

src="D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%206.%20Thermographic%20image%20indicating%20a%205°%20c%20difference%20between%20the%20hottest%20points%20of%20the%20boom%20lift%20cylinders.png"
alt="Figure 6. Thermographic image indicating a 5° c difference between the hottest points of the boom lift cylinders" />
<figcaption aria-hidden="true">Figure 6. Thermographic image indicating
a 5° c difference between the hottest points of the boom lift


The CRC evaluation of the cylinder allowed us to relate the field
symptoms and conclude that the thermographic method can be used to
define with more assurance that the cylinder needed to be removed.

Figure 8. Cyclinder at the CRC ![Figure 8. Cyclinder at the
CRC](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%208.%20Cyclinder%20at%20the%20CRC.png)

Next image shows some important details after disassembling the cylinder
in remanufacture center, and evaluated internally evidences, confirm the
relation from cylinder failure mode presented in field and causes after
disassembled. See bellow that the failure mode presented in Figure 9,
represent the cause os temperature increase in field termografic
process.

Figure 8a. Images of disassemlbed cylinder at CRC 1 ![Figure 8a. Images
of disassemlbed cylinder at CRC
1](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%209.%20Images%20of%20disassemlbed%20cylinder%20at%20CRC%201.png)

Figure 8b. Images of disassemlbed cylinder at CRC 2 ![Figure 8b. Images
of disassemlbed cylinder at CRC
2](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%209.%20Images%20of%20disassemlbed%20cylinder%20at%20CRC%202.png)

Figure 8c. Images of disassemlbed cylinder at CRC 3 ![Figure 8c. Images
of disassemlbed cylinder at CRC
3](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%209.%20Images%20of%20disassemlbed%20cylinder%20at%20CRC%203.png)

## 3.0 New Application Using Deep Learning and Online Data Colection

Based on this study, it was possible see the effectiveness of using this
process to indicate possible internal oil leakage by the cylinder seal
assembly. The Re manufacturing Center confirmed the issues with with
cylinder. Removing the cylinder based on the thermography along with the
other tests was shown to be the proper course of action.

Figure 7a. New application on Major Mining Excavator ![Figure 7a. New
application on Major Mining
Excavator](D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%207a.%20New%20application%20on%20Major%20Mining%20Escavator.png)

### 3.1 Project esquematic

### 3.2 Implementation Steps

Figure 7. Project Datra Collection on CAT 6030

<figure>
<img
src="D:/RNN_Sensor%20Dynamox/Git%20Repositório/rnn-component-lIfe-cycle/Figure%207.%20Project%20Datra%20Collection%20on%20CAT%206030.png"
alt="Figure 7. Project Datra Collection on CAT 6030" />
<figcaption aria-hidden="true">Figure 7. Project Datra Collection on CAT
6030</figcaption>
</figure>
