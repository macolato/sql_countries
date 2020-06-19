# sql_countries
codeacademy sql project
Microsoft Windows [Version 10.0.18363.900]
(c) 2019 Microsoft Corporation. All rights reserved.

C:\Users\marcy> cd Downloads

C:\Users\marcy\Downloads>sqlite-tools-win32-x86-3320300
'sqlite-tools-win32-x86-3320300' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\marcy\Downloads>cd sqlite-tools-win32-x86-3320300

C:\Users\marcy\Downloads\sqlite-tools-win32-x86-3320300>cd sqlite-tools-win32-x86-3320300

C:\Users\marcy\Downloads\sqlite-tools-win32-x86-3320300\sqlite-tools-win32-x86-3320300>sqlite3.exe population_queries.sql
SQLite version 3.32.3 2020-06-18 14:00:33
Enter ".help" for usage hints.
sqlite> SELECT * FROM countries
   ...> SELECT * FROM countries;
Error: near "SELECT": syntax error
sqlite> SELECT * FROM countries;
Error: file is not a database
sqlite> SELECT * FROM countries;
Error: file is not a database
sqlite> .schema
Error: file is not a database
sqlite> ls
   ...> cd
   ...> END
   ...> ESC
   ...> STOP
   ...> TERMINATE
   ...> ^D
   ...> ^D;
Error: near "ls": syntax error
sqlite> ^D;
Error: unrecognized token: ""
sqlite> ^D
   ...>
Error: unrecognized token: ""

C:\Users\marcy\Downloads\sqlite-tools-win32-x86-3320300\sqlite-tools-win32-x86-3320300>sqlite3.exe db.sqlite
SQLite version 3.32.3 2020-06-18 14:00:33
Enter ".help" for usage hints.
sqlite> .help
.archive ...             Manage SQL archives
.auth ON|OFF             Show authorizer callbacks
.backup ?DB? FILE        Backup DB (default "main") to FILE
.bail on|off             Stop after hitting an error.  Default OFF
.binary on|off           Turn binary output on or off.  Default OFF
.cd DIRECTORY            Change the working directory to DIRECTORY
.changes on|off          Show number of rows changed by SQL
.check GLOB              Fail if output since .testcase does not match
.clone NEWDB             Clone data into NEWDB from the existing database
.databases               List names and files of attached databases
.dbconfig ?op? ?val?     List or change sqlite3_db_config() options
.dbinfo ?DB?             Show status information about the database
.dump ?TABLE?            Render database content as SQL
.echo on|off             Turn command echo on or off
.eqp on|off|full|...     Enable or disable automatic EXPLAIN QUERY PLAN
.excel                   Display the output of next command in spreadsheet
.exit ?CODE?             Exit this program with return-code CODE
.expert                  EXPERIMENTAL. Suggest indexes for queries
.explain ?on|off|auto?   Change the EXPLAIN formatting mode.  Default: auto
.filectrl CMD ...        Run various sqlite3_file_control() operations
.fullschema ?--indent?   Show schema and the content of sqlite_stat tables
.headers on|off          Turn display of headers on or off
.help ?-all? ?PATTERN?   Show help text for PATTERN
.import FILE TABLE       Import data from FILE into TABLE
.imposter INDEX TABLE    Create imposter table TABLE on index INDEX
.indexes ?TABLE?         Show names of indexes
.limit ?LIMIT? ?VAL?     Display or change the value of an SQLITE_LIMIT
.lint OPTIONS            Report potential schema issues.
.load FILE ?ENTRY?       Load an extension library
.log FILE|off            Turn logging on or off.  FILE can be stderr/stdout
.mode MODE ?TABLE?       Set output mode
.nullvalue STRING        Use STRING in place of NULL values
.once ?OPTIONS? ?FILE?   Output for the next SQL command only to FILE
.open ?OPTIONS? ?FILE?   Close existing database and reopen FILE
.output ?FILE?           Send output to FILE or stdout if FILE is omitted
.parameter CMD ...       Manage SQL parameter bindings
.print STRING...         Print literal STRING
.progress N              Invoke progress handler after every N opcodes
.prompt MAIN CONTINUE    Replace the standard prompts
.quit                    Exit this program
.read FILE               Read input from FILE
.recover                 Recover as much data as possible from corrupt db.
.restore ?DB? FILE       Restore content of DB (default "main") from FILE
.save FILE               Write in-memory database into FILE
.scanstats on|off        Turn sqlite3_stmt_scanstatus() metrics on or off
.schema ?PATTERN?        Show the CREATE statements matching PATTERN
.selftest ?OPTIONS?      Run tests defined in the SELFTEST table
.separator COL ?ROW?     Change the column and row separators
.sha3sum ...             Compute a SHA3 hash of database content
.shell CMD ARGS...       Run CMD ARGS... in a system shell
.show                    Show the current values for various settings
.stats ?on|off?          Show stats or turn stats on or off
.system CMD ARGS...      Run CMD ARGS... in a system shell
.tables ?TABLE?          List names of tables matching LIKE pattern TABLE
.testcase NAME           Begin redirecting output to 'testcase-out.txt'
.testctrl CMD ...        Run various sqlite3_test_control() operations
.timeout MS              Try opening locked tables for MS milliseconds
.timer on|off            Turn SQL timer on or off
.trace ?OPTIONS?         Output each SQL statement as it is run
.vfsinfo ?AUX?           Information about the top-level VFS
.vfslist                 List all available VFSes
.vfsname ?AUX?           Print the name of the VFS stack
.width NUM1 NUM2 ...     Set column widths for "column" mode
sqlite> SELECT * FROM countries
   ...> SELECT * FROM countries;
Error: near "SELECT": syntax error
sqlite> SELECT * FROM countries;
1|Bermuda|North America
2|Canada|North America
3|Greenland|North America
4|Mexico|North America
5|Saint Pierre and Miquelon|North America
6|United States|North America
7|Antigua and Barbuda|North America
8|Argentina|South America
9|Aruba|North America
10|Bahamas, The|North America
11|Barbados|North America
12|Belize|North America
13|Bolivia|South America
14|Brazil|South America
15|Cayman Islands|North America
16|Chile|South America
17|Colombia|South America
18|Costa Rica|North America
19|Cuba|North America
20|Dominica|North America
21|Dominican Republic|North America
22|Ecuador|South America
23|El Salvador|North America
24|Falkland Islands (Islas Malvinas)|South America
25|French Guiana|South America
26|Grenada|North America
27|Guadeloupe|North America
28|Guatemala|North America
29|Guyana|South America
30|Haiti|North America
31|Honduras|North America
32|Jamaica|North America
33|Martinique|North America
34|Montserrat|North America
35|Netherlands Antilles|North America
36|Nicaragua|North America
37|Panama|North America
38|Paraguay|South America
39|Peru|South America
40|Puerto Rico|North America
41|Saint Kitts and Nevis|North America
42|Saint Lucia|North America
43|Saint Vincent/Grenadines|North America
44|Suriname|South America
45|Trinidad and Tobago|North America
46|Turks and Caicos Islands|North America
47|Uruguay|South America
48|Venezuela|South America
49|Virgin Islands,  U.S.|North America
50|Virgin Islands, British|North America
51|Albania|Europe
52|Austria|Europe
53|Belgium|Europe
54|Bosnia and Herzegovina|Europe
55|Bulgaria|Europe
56|Croatia|Europe
57|Cyprus|Asia
58|Czech Republic|Europe
59|Denmark|Europe
60|Faroe Islands|Europe
61|Finland|Europe
62|Former Serbia and Montenegro|Europe
63|France|Europe
64|Germany|Europe
65|Gibraltar|Europe
66|Greece|Europe
67|Hungary|Europe
68|Iceland|Europe
69|Ireland|Europe
70|Italy|Europe
71|Luxembourg|Europe
72|Macedonia|Europe
73|Malta|Europe
74|Netherlands|Europe
75|Norway|Europe
76|Poland|Europe
77|Portugal|Europe
78|Romania|Europe
79|Slovakia|Europe
80|Slovenia|Europe
81|Spain|Europe
82|Sweden|Europe
83|Switzerland|Europe
84|Turkey|Asia
85|United Kingdom|Europe
86|Armenia|Asia
87|Azerbaijan|Asia
88|Belarus|Europe
89|Estonia|Europe
90|Georgia|Asia
91|Kazakhstan|Asia
92|Kyrgyzstan|Asia
93|Latvia|Europe
94|Lithuania|Europe
95|Moldova|Europe
96|Russia|Europe
97|Tajikistan|Asia
98|Turkmenistan|Asia
99|Ukraine|Europe
100|Uzbekistan|Asia
101|Bahrain|Asia
102|Iran|Asia
103|Iraq|Asia
104|Israel|Asia
105|Jordan|Asia
106|Kuwait|Asia
107|Lebanon|Asia
108|Oman|Asia
109|Palestine|Asia
110|Qatar|Asia
111|Saudi Arabia|Asia
112|Syria|Asia
113|United Arab Emirates|Asia
114|Yemen|Asia
115|Algeria|Africa
116|Angola|Africa
117|Benin|Africa
118|Botswana|Africa
119|Burkina Faso|Africa
120|Burundi|Africa
121|Cameroon|Africa
122|Cape Verde|Africa
123|Central African Republic|Africa
124|Chad|Africa
125|Comoros|Africa
126|Congo (Brazzaville)|Africa
127|Congo (Kinshasa)|Africa
128|Cote dIvoire (IvoryCoast)|Africa
129|Djibouti|Africa
130|Egypt|Africa
131|Equatorial Guinea|Africa
132|Eritrea|Africa
133|Ethiopia|Africa
134|Gabon|Africa
135|Gambia, The|Africa
136|Ghana|Africa
137|Guinea|Africa
138|Guinea-Bissau|Africa
139|Kenya|Africa
140|Lesotho|Africa
141|Liberia|Africa
142|Libya|Africa
143|Madagascar|Africa
144|Malawi|Africa
145|Mali|Africa
146|Mauritania|Africa
147|Mauritius|Africa
148|Morocco|Africa
149|Mozambique|Africa
150|Namibia|Africa
151|Niger|Africa
152|Nigeria|Africa
153|Reunion|Africa
154|Rwanda|Africa
155|Saint Helena|Africa
156|Sao Tome and Principe|Africa
157|Senegal|Africa
158|Seychelles|Africa
159|Sierra Leone|Africa
160|Somalia|Africa
161|South Africa|Africa
162|Sudan|Africa
163|Swaziland|Africa
164|Tanzania|Africa
165|Togo|Africa
166|Tunisia|Africa
167|Uganda|Africa
168|Western Sahara|Africa
169|Zambia|Africa
170|Zimbabwe|Africa
171|Afghanistan|Asia
172|American Samoa|Oceania
173|Australia|Oceania
174|Bangladesh|Asia
175|Bhutan|Asia
176|Brunei|Asia
177|Burma (Myanmar)|Asia
178|Cambodia|Asia
179|China|Asia
180|Cook Islands|Oceania
181|Fiji|Oceania
182|French Polynesia|Oceania
183|Guam|Oceania
184|Hong Kong|Asia
185|India|Asia
186|Indonesia|Asia
187|Japan|Asia
188|Kiribati|Oceania
189|Korea, North|Asia
190|Korea, South|Asia
191|Laos|Asia
192|Macau|Asia
193|Malaysia|Asia
194|Maldives|Asia
195|Mongolia|Asia
196|Nauru|Oceania
197|Nepal|Asia
198|New Caledonia|Oceania
199|New Zealand|Oceania
200|Niue|Oceania
201|Pakistan|Asia
202|Papua New Guinea|Oceania
203|Philippines|Asia
204|Samoa|Oceania
205|Singapore|Asia
206|Solomon Islands|Oceania
207|Sri Lanka|Asia
208|Taiwan|Asia
209|Thailand|Asia
210|Timor-Leste (East Timor)|Asia
211|Tonga|Oceania
212|U.S. Pacific Islands|Oceania
213|Vanuatu|Oceania
214|Vietnam|Asia
sqlite> .schema
CREATE TABLE countries (
      id INTEGER NOT NULL,
      name TEXT NOT NULL,
      continent TEXT NOT NULL,
      PRIMARY KEY(id)
    );
CREATE TABLE population_years (
      id INTEGER NOT NULL,
      population NUMBER,
      year NUMBER,
      country_id INTEGER NOT NULL,
      PRIMARY KEY(id),
      FOREIGN KEY(country_id) REFERENCES countries(id)
    );
sqlite> SELECT COUNT(*) FROM countries;
214
sqlite> SELECT COUNT(*) FROM countries WHERE continent = 'Africa';
56
sqlite> SELECT * FROM population_years LIMIT 3;
1|0.06306|2000|1
2|0.06361|2001|1
3|0.06418|2002|1
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT SUM(population), name FROM continentpop WHERE continent = 'Oceania';
359.47808|American Samoa
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT SUM(population), name FROM continentpop WHERE continent = 'Oceania' AND WHERE year = 2005;
Error: near "WHERE": syntax error
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT SUM(population), name FROM continentpop WHERE continent = 'Oceania' AND year = 2005;
32.66417|American Samoa
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT AVG(population), name FROM continentpop WHERE continent = 'South America' AND year = 2003;
25.8906514285714|Argentina
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT MIN(population) FROM continentpop WHERE year = 2007;
0.00216
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT name, MIN(population) FROM continentpop WHERE year = 2007;
Niue|0.00216
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT name, AVG(population) FROM continentpop WHERE country = 'Poland';
Error: no such column: country
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT name, AVG(population) FROM continentpop WHERE name = 'Poland';
Poland|38.5606790909091
sqlite> SELECT * FROM countries WHERE name CONTAINS '%The%';
Error: near "CONTAINS": syntax error
sqlite> SELECT * FROM countries WHERE name CONTAINS 'The%';
Error: near "CONTAINS": syntax error
sqlite> SELECT * FROM countries WHERE name LIKE 'The%';
sqlite> SELECT * FROM countries WHERE name LIKE 'The%';
sqlite> SELECT * FROM countries WHERE name LIKE 'The%';
sqlite> SELECT name FROM countries WHERE name LIKE 'The%';
sqlite> SELECT * FROM countries;
1|Bermuda|North America
2|Canada|North America
3|Greenland|North America
4|Mexico|North America
5|Saint Pierre and Miquelon|North America
6|United States|North America
7|Antigua and Barbuda|North America
8|Argentina|South America
9|Aruba|North America
10|Bahamas, The|North America
11|Barbados|North America
12|Belize|North America
13|Bolivia|South America
14|Brazil|South America
15|Cayman Islands|North America
16|Chile|South America
17|Colombia|South America
18|Costa Rica|North America
19|Cuba|North America
20|Dominica|North America
21|Dominican Republic|North America
22|Ecuador|South America
23|El Salvador|North America
24|Falkland Islands (Islas Malvinas)|South America
25|French Guiana|South America
26|Grenada|North America
27|Guadeloupe|North America
28|Guatemala|North America
29|Guyana|South America
30|Haiti|North America
31|Honduras|North America
32|Jamaica|North America
33|Martinique|North America
34|Montserrat|North America
35|Netherlands Antilles|North America
36|Nicaragua|North America
37|Panama|North America
38|Paraguay|South America
39|Peru|South America
40|Puerto Rico|North America
41|Saint Kitts and Nevis|North America
42|Saint Lucia|North America
43|Saint Vincent/Grenadines|North America
44|Suriname|South America
45|Trinidad and Tobago|North America
46|Turks and Caicos Islands|North America
47|Uruguay|South America
48|Venezuela|South America
49|Virgin Islands,  U.S.|North America
50|Virgin Islands, British|North America
51|Albania|Europe
52|Austria|Europe
53|Belgium|Europe
54|Bosnia and Herzegovina|Europe
55|Bulgaria|Europe
56|Croatia|Europe
57|Cyprus|Asia
58|Czech Republic|Europe
59|Denmark|Europe
60|Faroe Islands|Europe
61|Finland|Europe
62|Former Serbia and Montenegro|Europe
63|France|Europe
64|Germany|Europe
65|Gibraltar|Europe
66|Greece|Europe
67|Hungary|Europe
68|Iceland|Europe
69|Ireland|Europe
70|Italy|Europe
71|Luxembourg|Europe
72|Macedonia|Europe
73|Malta|Europe
74|Netherlands|Europe
75|Norway|Europe
76|Poland|Europe
77|Portugal|Europe
78|Romania|Europe
79|Slovakia|Europe
80|Slovenia|Europe
81|Spain|Europe
82|Sweden|Europe
83|Switzerland|Europe
84|Turkey|Asia
85|United Kingdom|Europe
86|Armenia|Asia
87|Azerbaijan|Asia
88|Belarus|Europe
89|Estonia|Europe
90|Georgia|Asia
91|Kazakhstan|Asia
92|Kyrgyzstan|Asia
93|Latvia|Europe
94|Lithuania|Europe
95|Moldova|Europe
96|Russia|Europe
97|Tajikistan|Asia
98|Turkmenistan|Asia
99|Ukraine|Europe
100|Uzbekistan|Asia
101|Bahrain|Asia
102|Iran|Asia
103|Iraq|Asia
104|Israel|Asia
105|Jordan|Asia
106|Kuwait|Asia
107|Lebanon|Asia
108|Oman|Asia
109|Palestine|Asia
110|Qatar|Asia
111|Saudi Arabia|Asia
112|Syria|Asia
113|United Arab Emirates|Asia
114|Yemen|Asia
115|Algeria|Africa
116|Angola|Africa
117|Benin|Africa
118|Botswana|Africa
119|Burkina Faso|Africa
120|Burundi|Africa
121|Cameroon|Africa
122|Cape Verde|Africa
123|Central African Republic|Africa
124|Chad|Africa
125|Comoros|Africa
126|Congo (Brazzaville)|Africa
127|Congo (Kinshasa)|Africa
128|Cote dIvoire (IvoryCoast)|Africa
129|Djibouti|Africa
130|Egypt|Africa
131|Equatorial Guinea|Africa
132|Eritrea|Africa
133|Ethiopia|Africa
134|Gabon|Africa
135|Gambia, The|Africa
136|Ghana|Africa
137|Guinea|Africa
138|Guinea-Bissau|Africa
139|Kenya|Africa
140|Lesotho|Africa
141|Liberia|Africa
142|Libya|Africa
143|Madagascar|Africa
144|Malawi|Africa
145|Mali|Africa
146|Mauritania|Africa
147|Mauritius|Africa
148|Morocco|Africa
149|Mozambique|Africa
150|Namibia|Africa
151|Niger|Africa
152|Nigeria|Africa
153|Reunion|Africa
154|Rwanda|Africa
155|Saint Helena|Africa
156|Sao Tome and Principe|Africa
157|Senegal|Africa
158|Seychelles|Africa
159|Sierra Leone|Africa
160|Somalia|Africa
161|South Africa|Africa
162|Sudan|Africa
163|Swaziland|Africa
164|Tanzania|Africa
165|Togo|Africa
166|Tunisia|Africa
167|Uganda|Africa
168|Western Sahara|Africa
169|Zambia|Africa
170|Zimbabwe|Africa
171|Afghanistan|Asia
172|American Samoa|Oceania
173|Australia|Oceania
174|Bangladesh|Asia
175|Bhutan|Asia
176|Brunei|Asia
177|Burma (Myanmar)|Asia
178|Cambodia|Asia
179|China|Asia
180|Cook Islands|Oceania
181|Fiji|Oceania
182|French Polynesia|Oceania
183|Guam|Oceania
184|Hong Kong|Asia
185|India|Asia
186|Indonesia|Asia
187|Japan|Asia
188|Kiribati|Oceania
189|Korea, North|Asia
190|Korea, South|Asia
191|Laos|Asia
192|Macau|Asia
193|Malaysia|Asia
194|Maldives|Asia
195|Mongolia|Asia
196|Nauru|Oceania
197|Nepal|Asia
198|New Caledonia|Oceania
199|New Zealand|Oceania
200|Niue|Oceania
201|Pakistan|Asia
202|Papua New Guinea|Oceania
203|Philippines|Asia
204|Samoa|Oceania
205|Singapore|Asia
206|Solomon Islands|Oceania
207|Sri Lanka|Asia
208|Taiwan|Asia
209|Thailand|Asia
210|Timor-Leste (East Timor)|Asia
211|Tonga|Oceania
212|U.S. Pacific Islands|Oceania
213|Vanuatu|Oceania
214|Vietnam|Asia
sqlite> SELECT * FROM countries WHERE name LIKE 'The%';
sqlite> SELECT name FROM countries WHERE name LIKE 'The%';
sqlite> SELECT name FROM countries;
Bermuda
Canada
Greenland
Mexico
Saint Pierre and Miquelon
United States
Antigua and Barbuda
Argentina
Aruba
Bahamas, The
Barbados
Belize
Bolivia
Brazil
Cayman Islands
Chile
Colombia
Costa Rica
Cuba
Dominica
Dominican Republic
Ecuador
El Salvador
Falkland Islands (Islas Malvinas)
French Guiana
Grenada
Guadeloupe
Guatemala
Guyana
Haiti
Honduras
Jamaica
Martinique
Montserrat
Netherlands Antilles
Nicaragua
Panama
Paraguay
Peru
Puerto Rico
Saint Kitts and Nevis
Saint Lucia
Saint Vincent/Grenadines
Suriname
Trinidad and Tobago
Turks and Caicos Islands
Uruguay
Venezuela
Virgin Islands,  U.S.
Virgin Islands, British
Albania
Austria
Belgium
Bosnia and Herzegovina
Bulgaria
Croatia
Cyprus
Czech Republic
Denmark
Faroe Islands
Finland
Former Serbia and Montenegro
France
Germany
Gibraltar
Greece
Hungary
Iceland
Ireland
Italy
Luxembourg
Macedonia
Malta
Netherlands
Norway
Poland
Portugal
Romania
Slovakia
Slovenia
Spain
Sweden
Switzerland
Turkey
United Kingdom
Armenia
Azerbaijan
Belarus
Estonia
Georgia
Kazakhstan
Kyrgyzstan
Latvia
Lithuania
Moldova
Russia
Tajikistan
Turkmenistan
Ukraine
Uzbekistan
Bahrain
Iran
Iraq
Israel
Jordan
Kuwait
Lebanon
Oman
Palestine
Qatar
Saudi Arabia
Syria
United Arab Emirates
Yemen
Algeria
Angola
Benin
Botswana
Burkina Faso
Burundi
Cameroon
Cape Verde
Central African Republic
Chad
Comoros
Congo (Brazzaville)
Congo (Kinshasa)
Cote dIvoire (IvoryCoast)
Djibouti
Egypt
Equatorial Guinea
Eritrea
Ethiopia
Gabon
Gambia, The
Ghana
Guinea
Guinea-Bissau
Kenya
Lesotho
Liberia
Libya
Madagascar
Malawi
Mali
Mauritania
Mauritius
Morocco
Mozambique
Namibia
Niger
Nigeria
Reunion
Rwanda
Saint Helena
Sao Tome and Principe
Senegal
Seychelles
Sierra Leone
Somalia
South Africa
Sudan
Swaziland
Tanzania
Togo
Tunisia
Uganda
Western Sahara
Zambia
Zimbabwe
Afghanistan
American Samoa
Australia
Bangladesh
Bhutan
Brunei
Burma (Myanmar)
Cambodia
China
Cook Islands
Fiji
French Polynesia
Guam
Hong Kong
India
Indonesia
Japan
Kiribati
Korea, North
Korea, South
Laos
Macau
Malaysia
Maldives
Mongolia
Nauru
Nepal
New Caledonia
New Zealand
Niue
Pakistan
Papua New Guinea
Philippines
Samoa
Singapore
Solomon Islands
Sri Lanka
Taiwan
Thailand
Timor-Leste (East Timor)
Tonga
U.S. Pacific Islands
Vanuatu
Vietnam
sqlite> SELECT name FROM countries WHERE name LIKE 'The%';;
sqlite> SELECT name FROM countries WHERE name LIKE 'The%';
sqlite> SELECT name FROM countries WHERE name LIKE '%a%';
Bermuda
Canada
Greenland
Saint Pierre and Miquelon
United States
Antigua and Barbuda
Argentina
Aruba
Bahamas, The
Barbados
Bolivia
Brazil
Cayman Islands
Colombia
Costa Rica
Cuba
Dominica
Dominican Republic
Ecuador
El Salvador
Falkland Islands (Islas Malvinas)
French Guiana
Grenada
Guadeloupe
Guatemala
Guyana
Haiti
Honduras
Jamaica
Martinique
Montserrat
Netherlands Antilles
Nicaragua
Panama
Paraguay
Saint Kitts and Nevis
Saint Lucia
Saint Vincent/Grenadines
Suriname
Trinidad and Tobago
Turks and Caicos Islands
Uruguay
Venezuela
Virgin Islands,  U.S.
Virgin Islands, British
Albania
Austria
Bosnia and Herzegovina
Bulgaria
Croatia
Denmark
Faroe Islands
Finland
Former Serbia and Montenegro
France
Germany
Gibraltar
Hungary
Iceland
Ireland
Italy
Macedonia
Malta
Netherlands
Norway
Poland
Portugal
Romania
Slovakia
Slovenia
Spain
Switzerland
Armenia
Azerbaijan
Belarus
Estonia
Georgia
Kazakhstan
Kyrgyzstan
Latvia
Lithuania
Moldova
Russia
Tajikistan
Turkmenistan
Ukraine
Uzbekistan
Bahrain
Iran
Iraq
Israel
Jordan
Kuwait
Lebanon
Oman
Palestine
Qatar
Saudi Arabia
Syria
United Arab Emirates
Algeria
Angola
Botswana
Burkina Faso
Cameroon
Cape Verde
Central African Republic
Chad
Congo (Brazzaville)
Congo (Kinshasa)
Cote dIvoire (IvoryCoast)
Equatorial Guinea
Eritrea
Ethiopia
Gabon
Gambia, The
Ghana
Guinea
Guinea-Bissau
Kenya
Liberia
Libya
Madagascar
Malawi
Mali
Mauritania
Mauritius
Mozambique
Namibia
Nigeria
Rwanda
Saint Helena
Sao Tome and Principe
Senegal
Sierra Leone
Somalia
South Africa
Sudan
Swaziland
Tanzania
Tunisia
Uganda
Western Sahara
Zambia
Zimbabwe
Afghanistan
American Samoa
Australia
Bangladesh
Bhutan
Burma (Myanmar)
Cambodia
China
Cook Islands
French Polynesia
Guam
India
Indonesia
Japan
Kiribati
Korea, North
Korea, South
Laos
Macau
Malaysia
Maldives
Mongolia
Nauru
Nepal
New Caledonia
New Zealand
Pakistan
Papua New Guinea
Samoa
Singapore
Solomon Islands
Sri Lanka
Taiwan
Thailand
Timor-Leste (East Timor)
Tonga
U.S. Pacific Islands
Vanuatu
Vietnam
sqlite> SELECT name FROM countries WHERE name LIKE '%The%';
Bahamas, The
Netherlands Antilles
Netherlands
Gambia, The
sqlite> SELECT COUNT(*) FROM countries WHERE name LIKE '%The%';
4
sqlite> SELECT COUNT(*) FROM countries WHERE name LIKE '%The';
2
sqlite> WITH continentpop AS (SELECT * FROM countries JOIN population_years ON countries.id = population_years.country_id) SELECT continent, SUM(population) FROM continentpop WHERE year = 2010 GROUP BY continent;
Africa|1015.47846
Asia|4133.09148
Europe|723.06044
North America|539.79456
Oceania|34.95696
South America|396.58235
sqlite>
