# Threat-Emulation-Toolkit ![alt tag](app/tet.png)

## Documentation
* [Cyber Tactics Volume - 3-1.Threat_Emulation](Cyber_Tactics_Volume_3-1.Threat_Emulation.md)
* [Threat Guide](threat-intelligence/Threat_Guide.md)

### Tactics Bulletins

* [Tactics_Bulletin.Command_and_Control](c2/Tactics_Bulletin.Command_and_Control.md)
* [Tactics_Bulletin.Discovery](discovery/Tactics_Bulletin.Discovery.md)
* [Tactics_Bulletin.Exploitation](exploitation/Tactics_Bulletin.Exploitation.md)
* [Tactics_Bulletin.Effects](effects-generation/Tactics_Bulletin.Effects.md)
* [Tactics_Bulletin.Evasion](evasion/Tactics_Bulletin.Evasion.md)
* [Tactics_Bulletin.Code_Execution](execution/Tactics_Bulletin.Code_Execution.md)
* [Tactics_Bulletin.Lateral_Movement](lateral-movement/Tactics_Bulletin.Lateral_Movement.md)
* [Tactics_Bulletin.Persistence](persistence/Tactics_Bulletin.Persistence.md)
* [Tactics_Bulletin.Privilege_Escalation](privilege-escalation/Tactics_Bulletin.Privilege_Escalation.md)

Tactical Objectives:
c2
discovery
exploitation
effects-generation
evasion
execution
lateral-movement
persistence
privilege-escalation

Cyber tactics cover a much wider arrangement of scenarios than typical employment of forces might so we have -> TTP Subcategories -> Breakdown into specific kind of situation/signifier that can drive employment scenarios

What is project, How to use, repo structure - tactics folders (Tactical objectives), Information/Background: ,, what is threat emulation (structured employment of forces) (and what are TTP, JP 1-02), training the defense to the threat, identifying specific organizational threats by matching to IP/critical information/PII/HIPAA/Theat Intel, ATT&CK Matrix, What are threat archetypes?

what is a:Threat_Intelligence- -> Who does this TTP? Specific actors/archetypes
what is a:Tactics_Bulletin- -> How to implement the TTP -> Specific Techniques/Procedures
what is a:Employment_Scenario- -> Scenario

Project Description: Cyber 3-1.Threat Emulation - The Tactics Volume for emulating threat TTP based on archetypes and actual campaigns structured employment of forces

Structure:
/
. cyber tactics folders: c2 discovery exploitation effects-generation evasion execution lateral-movement persistence privilege-escalation
. tools
. threat-intelligence
. LICENSE
. README.md -> What is project, How to use, repo structure - tactics folders (TTP categories), Information/Background: ,, what is threat emulation (structured employment of forces) (and what are TTP, JP 1-02), training the defense to the threat, identifying specific organizational threats by matching to IP/critical . information/PII/HIPAA/Theat Intel, ATT&CK Matrix
. /Cyber Tactics Volume 3-1.Threat_Emulation -> Intro/Purpose/Intrusion Sets and Archetypes/Threat Guide by Industry matrixed to IS and Arcs/Chapters(Objectives) & Tactics Bulletins/attachments: . /Brevity Words,defs/tools

/TTP Folders/
. Tactics_Bulletin -> Objective Description, Tactics listing, Tactics Description, Threat Matrix, Technique Description, Procedure steps
. Tactic or TTP subcategories when breakdown necessary
/TTP Folders/SubCat/
. Tactic -> Tactic description, (Threat_Matrix -> Which threats perform this activity, and what tactics do they employ, list techniques if known), Technique listing, Technique Description, Procedure steps
Employment_Scenario
. Tactic
. Tactic
...

/tools/
. Tool Type/Category Folders

/tools/type/
. tool or ./SubCat/tool
...

/threat-intelligence/
. Threat_Guide
. Intrusion Set Folders

/threat-intelligence/Intrusion Set Folder/
. Threat_Assessment -> Intro/Sourcing of Data/Confidence Assessment/Group breakdown: level of funding, skill, sophistication, motivation, sponsorship, facilities, location & geography, nationality/Targets and Target Types/Known TTP Listing & Threat Matrix/identified attack campaigns & confidence assessment/References
