# fifa2018dc
This dataset was parsed from the FIFA 2018 Player database
It can be accessed via url here: https://github.com/adevuyst/fifa2018dc/raw/master/data/CompleteDataset.csv.gz

The data set is in CSV format and contains the following columns:

	Name	Age	Photo	Nationality	Flag	Overall	Potential	CAM	CB	CDM	CF	CM	ID	LAM	LB	LCB	LCM	LDM	LF	LM	LS	LW	LWB	Preferred Positions	RAM	RB	RCB	RCM	RDM	RF	RM	RS	RW	RWB	ST
	
Based on the positions listed here:
* GK - Goalkeeper
* CB - Centre back
* RCB / LCB - Right / left Center Back
* CDM - Central Defensive midfielder
* CM - Central midfield
* CAM - Central Attacking midfielder
* CF - Center Forward
* RB / LB - Right / Left Back
* RWB / LWB - Right / Left Wing Back
* RM / LM - Right / Left Midfield
* RW / LW - Right / Left Wing
* RF / LF - Right / Left Forward
* RS / LS - Right / Left Side Player
* ST - Striker

Position Layout:
![Positions](https://1.bp.blogspot.com/-8mh5E9lV7Oo/WdhqbTJGWSI/AAAAAAAADms/YL61AOC_qwQvxwblU2r1H-RlF2hE6F4_wCLcBGAs/s1600/fifa-18-Positions-Short-Forms-Terms-Abbreviations.jpg)

I used the fifa2018 data set and I attempted to build out different teams based on a players overall rating for different formations.
The formations I included are:
* 3-5-2
* 4-4-2
* 4-3-3
* 3-4-3
* 5-3-2

These are based on the traditional nomenclature of Defense-Midfield-Forwards where the total is always 10 and the 11th player (Goalie or GK) is implied.