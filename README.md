# ABM_Tool_CMs
An Agent Based Modeling Tool for Secondary Critical Materials Market Development

About:
This repository contains files to enable the use of a novel Agent Based Model (ABM). Specifically, this ABM integrates techno-economic analysis and lifecycle assessment metrics to quantitatively evaluate the feasibility and impacts of Secondary Materials Markets (SMMs). SMMs are formed as a consequence of developing viable secondary material feedstocks and are viewed as a vital strategy to diversify and expand critical materials sources thereby mitigating supply chain risks. The given ABM considers multiple interdependent factors are simultaneously, including techno-economic developments, demand uncertainty, inconsistent used product management scenarios, and changing stakeholder business strategies and interactions. The current version of the tool is demonstrated using a solar photovoltaic (PV) waste management case-study.

Given below are an itemized list of contents in the repository:
1. annual_pv_waste_el.pkl: A .pkl file created using Python’s pickle module for converting the list of annual early loss PV waste quantities into a binary format. Located in folder titled Source code.
2. annual_pv_waste_avg.pkl: A .pkl file created using Python’s pickle module for converting the list of annual average (of early and regular loss numbers) PV waste quantities into a binary format. Located in folder titled Source code.
3. annual_pv_waste_rl.pkl: A .pkl file created using Python’s pickle module for converting the list of annual regular loss PV waste quantities into a binary format. Located in folder titled Source code.
4. PV SMM ABM Tool 2025_AC and NM.ipynb: Is the code for the actual ABM model itself and is accessible via Jupyter Notebook. Located in folder titled Source code.
5. Parameter Data and Sources.xlsx: Describes source data used namely. Tab 1 is the cover sheet that specifies the contents of the spreadsheet. Tab 2 provides End of Use solar panel projected waste quantities (in metric tons) from 2020 - 2050. Tab 3 provides expected domestic material demands (in metric tons) for a range of manufacturing raw materials in 2030. Tab 4 compiles a range of primary and secondary material costs, landfilling costs and transportation costs based on literature sources. Tab 5 compiles individual material recovery and yield rates based on literature sources. Tab 6 provides Life Cycle Assessment metrics compiled from preceding studies.

The model requires as input the following information: 1. EoU product collection data from which critical materials may be recovered 2. Material demands by partner firms 3. Material costs, shipping costs, disposal costs 4. Recovery process cost and yields 5. Partner firm behavioral factors such as confidence in use of secondary materials, tendency for opportunistic negotiation regarding cost sharing 6. Firm locations

This model generates the following outputs (under tested conditions): 1. Critical material recovery potential 2. Net financial benefits projections for firms participating in the secondary materials market 3. Potential for net avoided environmental impacts. 

Disclaimers:
Software:
NIST-developed software is provided by NIST as a public service. You may use, copy, and distribute copies of the software in any medium, provided that you keep intact this entire notice. You may improve, modify, and create derivative works of the software or any portion of the software, and you may copy and distribute such modifications or works. Modified works should carry a notice stating that you changed the software and should note the date and nature of any such change. Please explicitly acknowledge the National Institute of Standards and Technology as the source of the software. 
 
NIST-developed software is expressly provided "AS IS." NIST MAKES NO WARRANTY OF ANY KIND, EXPRESS, IMPLIED, IN FACT, OR ARISING BY OPERATION OF LAW, INCLUDING, WITHOUT LIMITATION, THE IMPLIED WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, AND DATA ACCURACY. NIST NEITHER REPRESENTS NOR WARRANTS THAT THE OPERATION OF THE SOFTWARE WILL BE UNINTERRUPTED OR ERROR-FREE, OR THAT ANY DEFECTS WILL BE CORRECTED. NIST DOES NOT WARRANT OR MAKE ANY REPRESENTATIONS REGARDING THE USE OF THE SOFTWARE OR THE RESULTS THEREOF, INCLUDING BUT NOT LIMITED TO THE CORRECTNESS, ACCURACY, RELIABILITY, OR USEFULNESS OF THE SOFTWARE.
 
You are solely responsible for determining the appropriateness of using and distributing the software and you assume all risks associated with its use, including but not limited to the risks and costs of program errors, compliance with applicable laws, damage to or loss of data, programs or equipment, and the unavailability or interruption of operation. This software is not intended to be used in any situation where a failure could cause risk of injury or damage to property. The software developed by NIST employees is not subject to copyright protection within the United States.
 
 
Products:
Certain equipment, instruments, software, or materials are identified in this software in order to specify the experimental procedure adequately.  Such identification is not intended to imply recommendation or endorsement of any product or service by NIST, nor is it intended to imply that the materials or equipment identified are necessarily the best available for the purpose.
