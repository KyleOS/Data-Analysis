===================================================================================================================
This ZIP file contains all WID.world data for all Wid.world available countries as of 08-07-2019 at 22:56:30 (GMT)
===================================================================================================================

The WID_full_dataset folder contains data for all countries on WID.world

Within each country folder the DATA folder contains two files:

-WID_XX_MacroData.csv, which contains macro data series (aggregate and total income and wealth variables, as well as population variables and other macro indicator such as deflators, exchange rates, etc.)

-WID_XX_InequalityData.csv, which contains inequality data series (income and wealth shares, thresholds, averages for different percentiles of the population).

The list of 2-letter country codes and their associated country names is provided at the end of this readme file.

=============================================================
HOW TO INTERPRET INEQUALITY DATA AND PERCENTILES ON WID.WORLD?
=============================================================

We explain below the key features of the notation used in WID.world, to help users properly understand and interpret the inequality data provided in the database.

There are two types of percentiles in WID.world: grouped percentiles and generalized percentiles. The interpretation of income and wealth averages, shares, and thresholds depends on which type of percentile is looked at.

Grouped percentiles

Grouped percentiles are denoted as follows: p0p50 (bottom 50% of the target population), p50p90 (next 40%), p90p100 (top 10%), p99p100 (top 1%), p0p10 (bottom 10% of the population, ie. first decile), p10p20 (next 10%, ie. second decile), p20p30 (next 10%, ie. third decile), p30p40 (next 10%, ie. fourth decile), p40p50 (next 10%, ie. fifth decile), p50p60 (next 10%, ie. sixth decile), p60p70 (next 10%, ie. seventh decile), p70p80 (next 10%, ie. eighth decile), p80p90 (next 10%, ie. ninth decile), p0p90 (bottom 90%), p0p99 (bottom 99%), p99.9p100 (top 0.1%), p99.99p100 (top 0.01%).

For each grouped percentile, we provide (whenever possible) the associated income and wealth shares, averages, and thresholds.

i) grouped percentile shares correspond to the share of income (or wealth) held by a given grouped percentile. For instance, the fiscal income share of group p0p50 is the share of total fiscal income accrued to the bottom 50% group.

ii) grouped percentile averages correspond to the average income (or wealth) of a given grouped percentile. For instance, the fiscal income average of group p0p50 is the average annual fiscal income of the bottom 50% group.

iii) grouped percentile thresholds correspond to the minimum income (or wealth) level required to belong to a given grouped percentile. For instance, the fiscal income threshold of group p90p100 is the minimum annual fiscal income necessary to belong to the top 10% group, i.e. the 90th percentile income threshold.

For countries where the data permit, WID.world also makes it possible to retrieve shares, averages, and thresholds for any grouped percentile pxpy (where x and y are any two given generalized percentiles, e.g. p43p99.92; see below). However, these are not stored in the country full datasets provided in the Data section, but they need to be selected through the custom menu.

In contrast, for a number of countries we are not able to provide the series for all grouped percentiles described above, due to data limitations. Instead, we provide series for specific ones (these can be, depending on the countries, p90p95, p95p100, p95p99, p99.5p100, p99.5p99.9, p99.75p100, p99.95p100, p99.95p99.99, p99.995p100, p99.9p99.95, p99.9p99.99 or p99p99.5).

Generalized percentiles

WID.world also defines 127  generalized percentiles (g-percentiles) that are denoted as p0, p1, p2, …, p99, p99.1, p99.2, …, p99.9, p99.91, p99.92, …, p99.99, p99.991, p99.992 ,…, p99.999.

For each g-percentile, we provide shares, averages, thresholds (as for grouped percentiles), as well as what we call top-averages.

i) g–percentile shares correspond to the income (or wealth) share captured by the population group above a given g-percentile value. For example, the fiscal income share of g-percentile p90 corresponds to the fiscal income share held by the top 10% group; the fiscal income share of g-percentile p99.9 corresponds to the fiscal income share of the top 0.1% income group, and so on. By construction, the fiscal income share of g-percentile p0 corresponds to the share held by 100% of the target population, and it is equal to 100%. The g-percentile share at g-percentile px corresponds to the share of the top (100-x)% group.

ii) g–percentile averages correspond to the average income (or wealth) between two consecutive g-percentiles. Therefore, the average income of g-percentile p0 corresponds to the average annual income of the bottom 1% group, p2 corresponds to the next 1% group, and so on until p98 (the 1% population group below the top 1%).

Average income of g-percentile p99 corresponds to average annual income of grouped percentile p99p99.1 (ie. the bottom 10% group within the top 1% group), p99.1 corresponds to the next 0.1%, p99.2 corresponds to the next 0.1%, and so on until p99.8.

Average income of p99.9 corresponds to the average annual income of group percentile p99.9p99.91 (ie. the bottom 10% group of earners within the top 0.1% group of earners), p99.91 corresponds to the next 0.01% group, p99.92 corresponds to the next 0.01% group and so on until p99.98.

The average income of p99.99 corresponds to the average annual income of group percentile p99.99p99.991 (i.e. the bottom 10% group within the top 0.01% group of earners), p99.991 corresponds to the next 0.001%, p99.992 corresponds to the next 0.001%, and so on until p99.999 (average income of the top 0.001%).

As an example, the average fiscal income of g-percentile p50 is the average annual fiscal income of the p50p51 group (i.e. the average annual income of the population group earning more than 50% of the population and less than the top 49% of the population). The average fiscal income of g-percentile p99 is the average annual fiscal income within group percentile p99p99.1 (ie. a group representing 0.1% of the total population earning more than 99% of the population but less than the top 0.9% of the population).

iii) g–percentile thresholds are the minimum income (or wealth) levels required to belong to the group above a given g-percentile value. For instance, the fiscal income threshold at g-percentile p90 is the minimum annual fiscal income required to belong to the top 10% group. Fiscal income threshold at g-percentile p99.9 is the minimum annual fiscal income required to belong to the top 0.1% group. The g-percentile threshold at g-percentile px is the threshold of the top (100-x)% group.

iv) g–percentile top–averages are the average income (or wealth) above a given g-percentile threshold. For instance, the top-average fiscal income at g-percentile p50 correspond to the average annual fiscal income of individuals earning more than 50% of the target population. The top average fiscal income at g-percentile p90 is the average annual fiscal income of the top 10% group.

=================================================
WID.world uses 2-letter ISO codes for countries : 
=================================================

AD Andorra
AE United Arab Emirates
AF Afghanistan
AG Antigua and Barbuda
AI Anguilla
AL Albania
AM Armenia
AN Netherlands Antilles
AO Angola
AR Argentina
AS American Samoa
AT Austria
AU Australia
AW Aruba
AZ Azerbaijan
BA Bosnia and Herzegovina
BB Barbados
BD Bangladesh
BE Belgium
BF Burkina Faso
BG Bulgaria
BH Bahrain
BI Burundi
BJ Benin
BM Bermuda
BN Brunei Darussalam
BO Bolivia
BR Brazil
BS Bahamas
BT Bhutan
BW Botswana
BY Belarus
BZ Belize
CA Canada
CD DR Congo
CF Central African Republic
CG Congo
CH Switzerland
CI Cote d'Ivoire
CK Cook Islands
CL Chile
CM Cameroon
CN-RU Rural China
CN-UR Urban China
CN China
CO Colombia
CR Costa Rica
CS Czechoslovakia
CU Cuba
CV Cabo Verde
CW Curacao
CY Cyprus
CZ Czech Republic
DD German Democratic Republic
DE-BD Baden
DE-BY Bavaria
DE-HB Bremen
DE-HE Hesse
DE-HH Hamburg
DE-PR Prussia
DE-SN Saxony
DE-WU Wurttemberg
DE Germany
DJ Djibouti
DK Denmark
DM Dominica
DO Dominican Republic
DZ Algeria
EC Ecuador
EE Estonia
EG Egypt
EH Western Sahara
ER Eritrea
ES Spain
ET Ethiopia
FI Finland
FJ Fiji
FK Falkland Islands
FM Micronesia
FO Faroe Islands
FR France
GA Gabon
GB United Kingdom
GD Grenada
GE Georgia
GH Ghana
GI Gibraltar
GL Greenland
GM Gambia
GN Guinea
GQ Equatorial Guinea
GR Greece
GT Guatemala
GU Guam
GW Guinea-Bissau
GY Guyana
HK Hong Kong
HN Honduras
HR Croatia
HT Haiti
HU Hungary
ID Indonesia
IE Ireland
IL Israel
IM Isle of Man
IN India
IQ Iraq
IR Iran
IS Iceland
IT Italy
JM Jamaica
JO Jordan
JP Japan
KE Kenya
KG Kyrgyzstan
KH Cambodia
KI Kiribati
KM Comoros
KN Saint Kitts and Nevis
KP North Korea
KR Korea
KS Kosovo
KW Kuwait
KY Cayman Islands
KZ Kazakhstan
LA Lao PDR
LB Lebanon
LC Saint Lucia
LI Liechtenstein
LK Sri Lanka
LR Liberia
LS Lesotho
LT Lithuania
LU Luxembourg
LV Latvia
LY Libya
MA Morocco
MC Monaco
MD Moldova
ME Montenegro
MG Madagascar
MH Marshall Islands
MK Macedonia
ML Mali
MM Myanmar
MN Mongolia
MO Macao
MP Northern Mariana Islands
MR Mauritania
MS Montserrat
MT Malta
MU Mauritius
MV Maldives
MW Malawi
MX Mexico
MY Malaysia
MZ Mozambique
NA Namibia
NC New Caledonia
NE Niger
NG Nigeria
NI Nicaragua
NL Netherlands
NO Norway
NP Nepal
NR Nauru
NU Niue
NZ New Zealand
OM Oman
PA Panama
PE Peru
PF French Polynesia
PG Papua New Guinea
PH Philippines
PK Pakistan
PL Poland
PM Saint Pierre and Miquelon
PR Puerto Rico
PS Palestine
PT Portugal
PW Palau
PY Paraguay
QA Qatar
QB Africa
QC Americas
QD Asia
QE Europe
QF-MER null
QF Oceania
QG Australia and New Zealand
QH Caribbean
QI Central America
QJ Central Asia
QK Eastern Africa
QL Eastern Asia
QM Eastern Europe
QN Middle Africa
QO Northern Africa
QP Northern America
QQ Oceania (excl. Australia and New Zealand)
QR South America
QS South-Eastern Asia
QT Southern Africa
QU Southern Asia
QV Western Africa
QW Western Asia
QX Western Europe
QY European Union
RO Romania
RS Serbia
RU Russian Federation
RW Rwanda
SA Saudi Arabia
SB Solomon Islands
SC Seychelles
SD Sudan
SE Sweden
SG Singapore
SH Saint Helena
SI Slovenia
SK Slovakia
SL Sierra Leone
SM San Marino
SN Senegal
SO Somalia
SR Suriname
SS South Sudan
ST Sao Tome and Principe
SU USSR
SV El Salvador
SX Sint Maarten (Dutch part)
SY Syrian Arab Republic
SZ Swaziland
TC Turks and Caicos Islands
TD Chad
TG Togo
TH Thailand
TJ Tajikistan
TK Tokelau
TL Timor-Leste
TM Turkmenistan
TN Tunisia
TO Tonga
TR Turkey
TT Trinidad and Tobago
TV Tuvalu
TW Taiwan
TZ Tanzania
UA Ukraine
UG Uganda
US-AK Alaska
US-AL Alabama
US-AR Arkansas
US-AZ Arizona
US-CA California
US-CO Colorado
US-CT Connecticut
US-DC District of Columbia
US-DE Delaware
US-FL Florida
US-GA Georgia
US-HI Hawaii
US-IA Iowa
US-ID Idaho
US-IL Illinois
US-IN Indiana
US-KS Kansas
US-KY Kentucky
US-LA Louisiana
US-MA Massachusetts
US-MD Maryland
US-ME Maine
US-MI Michigan
US-MN Minnesota
US-MO Missouri
US-MS Mississippi
US-MT Montana
US-NC North Carolina
US-ND North Dakota
US-NE Nebraska
US-NH New Hampshire
US-NJ New Jersey
US-NM New Mexico
US-NV Nevada
US-NY New York
US-OH Ohio
US-OK Oklahoma
US-OR Oregon
US-PA Pennsylvania
US-RI Rhode Island
US-SC South Carolina
US-SD South Dakota
US-TN Tennessee
US-TX Texas
US-UT Utah
US-VA Virginia
US-VT Vermont
US-WA Washington
US-WI Wisconsin
US-WV West Virginia
US-WY Wyoming
US USA
UY Uruguay
UZ Uzbekistan
VA Holy See
VC Saint Vincent and the Grenadines
VE Venezuela
VG Virgin Islands, British
VI Virgin Islands, US
VN Viet Nam
VU Vanuatu
WF Wallis and Futuna
WO World
WS Samoa
XI Channel Islands
XM Middle East
YE Yemen
YU Yugoslavia
ZA South Africa
ZM Zambia
ZW Zimbabwe
ZZ Zanzibar
