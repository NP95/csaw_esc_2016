**For the 2017 ESC repository, please visit [this link](https://github.com/momalab/csaw_esc_2017).**

*The final results of ESC 2016 are announced [here](esc2016_finalists.md).* 
*Sample exploits for OpenRISC Linux are available [here](tools/exploits).*

CSAW 2016 Embedded Security Challenge (ESC)
===========================================

In 2016, for the first time in ESC history, the competition will be **world-wide** with finals held in 3 regions simultaneously: United States, Middle East & North Africa, and India. The finals will take place on **November 11-12, 2016** and the venues for each region are as follows:
-   **New York**: NYU Tandon School of Engineering, Metrotech Center, Brooklyn, NY
-   **Abu Dhabi**: NYU Abu Dhabi Campus, Saadiyat Island, Abu Dhabi, UAE
-   **Kanpur**: Indian Institute of Technology, Kanpur, Uttar Pradesh, India

The competition is organized in all regions under the supervision of Professor Michail Maniatakos (NYU-AD), and the global challenge leader is Nektarios Tsoutsos. In the MENA region, the competition is coordinated by Professor Ramesh Karri (NYU-NY) with Dr. Subidh Ali as the MENA challenge leader. In India, ESC is coordinated by Professor Sandeep Shukla (IIT-Kanpur) and the India challenge leader is Asan Basiri.

This year, ESC will focus on *hardware mitigations for memory corruption and control flow integrity attacks* in Embedded Systems, and the challenge will have a *qualification phase* and a *final phase*. During the qualification phase, participants will play the role of the **attacker** and design software exploits for Linux programs running on an OpenRISC system. In the final phase, 10 qualified teams in each region will play the role of the **defender** and implement hardware-based mitigations for the OpenRISC processor in Verilog HDL, to protect against different exploitation methods. The [challenge description](challenge_description.md) provides all necessary details on the challenge, while the [quick-start guide](quickstart_guide.md) provides assistance on how to start with the OpenRISC environment. A **pre-configured Virtual Machine** is also available [here](http://tinyurl.com/csaw-esc16-vm). *It is recommended to 'watch' this repository on GitHub, as the challenge will be updated periodically*.


Registration Policies
---------------------

Each team must have a **team leader** and up to 3 additional team members (a total of 4 participants per team). The team leader will be responsible for coordinating with other team members and will be the point of contact for the entire team. Each team should also have a university **faculty advisor**. Except for unforeseen and exceptional situations, if a team has qualified for the final round of the competition and withdraws after October 12, 2016, the team members and their faculty advisor cannot qualify for the 2017 competition; the same policy applies to no-shows at the day of the finals.

The team leaders should register their teams and faculty advisor electronically at https://hotcrp.engineering.nyu.edu/, using the team name and affiliation abbreviation as the 'Submission Title'. ESC uses a HotCRP-based registration & submission system, for both the qualification and final rounds, and teams *should register before finalizing their report and file submissions* by the posted deadlines. In addition, CSAW requires all participating individuals (i.e., each team member separately) to complete a **supplementary questionnaire** available at http://goo.gl/forms/wyMJcQyZqmnWhBpJ3. 

Students of all university levels are invited to compete. Each team is eligible to register for **only one region**: New York, MENA or India; registering for more than one regions is not allowed, and such registrations will be cancelled. In addition, after the registration closes, making changes to the existing members of a team (e.g., replacing a team member) or adding of new team members, requires permission from the organizers. This is also necessary for teams replacing team members or adding new team members during the final phase of the competition.

For ESC 2016, each region has different team sponsorship and prize policies, and the assignment of each team to the corresponding region depends on the *country of the university affiliations of its members*. Specifically, all members of the same team should be enrolled in universities **within the same country** for the duration of the competition, and these affiliations cannot be modified after the submission deadline. At the finals, each region will announce separate winners for the first, second and third place, while the region assignment is as follows:
-   **United States**: includes universities in the US. Visit https://csaw.engineering.nyu.edu/esc for information about the prizes and travel sponsorship within the US region. This year, **two (2)** students from each team qualified to the finals will receive a travel sponsorship to attend the finals in NY during CSAW. 
-   **MENA**: visit http://sites.nyuad.nyu.edu/ccs-ad/portfolio/csaw/ for more information about the prizes and travel sponsorship within the MENA region.
-   **India**: includes universities from India. Visit https://csaw.iitk.ac.in/esc.html for information about the prizes in the India region.

To be able to qualify to the final round, each team should register for the correct region, corresponding to the country of the universities of its members.  

Competition Deadlines
---------------------
To participate in the competition, each team needs to register with the HotCRP registration system by ~~September 9, 2016~~ ~~September 18, 2016~~ **(Extended) September 30, 2016**. In addition, each team member should also complete the supplementary CSAW questionnaire by this deadline. Registered teams should submit their qualification reports and developed computer files using the HotCRP system by ~~September 18, 2016~~ **(Extended) September 30, 2016**. The teams that qualified to the final phase will be announced on this repository by ~~September 25, 2016~~ **October 7, 2016**. The qualified teams should submit their final reports and associated computer files using the HotCRP system by ~~November 4, 2016~~ **(Extended) November 7, 2016 5pm EST**. 


Deliverables
------------
For the qualification phase, each participating team should upload to HotCRP **a written report** in PDF format, as well as a TAR.GZ archive with all developed **computer files and instructions**. For the final phase, each qualified team should upload a final version of their PDF report to HotCRP along with a TAR.GZ with all associated computer files and instructions for the preliminary and final phase. The qualifying reports can be up to **4 pages** and the final reports can be up to **8 pages**. In addition, all reports need to follow the *standard IEEE conference format* (10pt font, double column, letter size paper, not compsoc mode); templates are available [here](http://www.ieee.org/conferences_events/conferences/publishing/templates.html). 
For the day of the live finals at CSAW, each team is asked to prepare a **PowerPoint presentation** (up to 10') and a **poster** (up to 36"x48") of their work.

Code of Conduct
---------------
All ESC participants are subject to the NYU Tandon School of Engineering [student code of conduct](http://engineering.nyu.edu/life/student-affairs/code-of-conduct). Any act of academic dishonesty (such as plagiarism, cheating, fabrication, unauthorized collaboration across different teams, work duplication, etc.) *will not be tolerated* and the offenders will be automatically disqualified from the competition.

Equipment Requirements
----------------------

For the live finals of the competition, the teams will be asked to present their solution to the challenge using a low-cost **DE0-nano FPGA** (available [here](http://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=593)). Communication with a computer also requires a **3.3 Volt** FTDI USB to UART cable that is available [here](https://www.sparkfun.com/products/12977) (this is in addition to the JTAG cable provided with the FPGA board itself). Note that the I/O pins of the FTDI cable (*RX-Yellow*, *TX-Orange* and *GND-Black*) operate at 3.3 Volt (i.e., they are compatible with DE0-nano), but the power supply pin of the cable (*VCC-Red*) is at 5.0 Volt. **This means that the VCC pin of the cable is incompatible with the DE0-nano board (even the VCC pin of the board) and must be left unconnected at all times, as it will cause permanent damage to the FPGA**. The required equipment (FPGA board and FTDI cable) will be provided to the finalists of all 3 regions by the organizers. *The organizers would like to thank Intel for donating the DE0-nano FPGA boards used in this competition*.
<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Intel-logo.svg/200px-Intel-logo.svg.png" alt="Intel logo"/>
</p>

Contact Information
-------------------

Teams can contact the organizers at the following address: `csaw dot esc at nyu dot edu`. To properly route each message and avoid delays in the response, each message should prepend `[NewYork]`, `[AbuDhabi]`, or `[India]` in the subject, depending on the region of the participating team.

