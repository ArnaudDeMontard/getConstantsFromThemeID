creates a collection of constants of the passed theme number (4D v20r10).  

example  
```
$c:=DOA_getConstantsFromTheme (2)  //2 = form events
```
returns this:  
```
[
	{
		"value": 1,
		"constant": "System date short",
		"token": ":K1:1"
	},
	{
		"value": 2,
		"constant": "System date abbreviated",
		"token": ":K1:2"
	},
	{
		"value": 3,
		"constant": "System date long",
		"token": ":K1:3"
	},
	{
		"value": 4,
		"constant": "Internal date short special",
		"token": ":K1:4"
	},
	{
		"value": 5,
		"constant": "Internal date long",
		"token": ":K1:5"
	},
	{
		"value": 6,
		"constant": "Internal date abbreviated",
		"token": ":K1:6"
	},
	{
		"value": 7,
		"constant": "Internal date short",
		"token": ":K1:7"
	},
	{
		"value": 8,
		"constant": "ISO date",
		"token": ":K1:8"
	},
	{
		"value": 100,
		"constant": "Blank if null date",
		"token": ":K1:9"
	},
	{
		"value": 9,
		"constant": "ISO date GMT",
		"token": ":K1:10"
	},
	{
		"value": 10,
		"constant": "Date RFC 1123",
		"token": ":K1:11"
	}
]
```
Correspondance theme/id  
| theme | id |  
| :------------ | -------------: |  
|  Date Display Formats | 1 |  
|  Form Events | 2 |  
|  Trigger Events | 3 |  
|  Standard System Signatures | 4 |  
|  4D Environment | 5 |
|  Picture Display Formats | 6 |
|  Time Display Formats | 7 |
|  Field and Variable Types | 8 |
|  Platform Interface | 9 |
|  Days and Months | 10 |
|  Colors | 11 |
|  Function Keys | 12 |
|  Process State | 13 |
|  Font Styles | 14 |
|  ASCII Codes | 15 |
|  Events (Modifiers) | 16 |
|  Events (What) | 17 |
|  Resources Properties | 18 |
|  Queries | 19 |
|  Pasteboard | 20 |
|  TCP Port Numbers | 21 |
|  BLOB | 22 |
|  SET RGB COLORS | 23 |
|  System Documents | 24 |
|  Platform Properties | 25 |
|  Find Window | 26 |
|  Windows | 27 |
|  Hierarchical Lists | 28 |
|  Database Engine | 29 |
|  Math | 30 |
|  Communications | 31 |
|  ISO Latin Character Entities | 32 |
|  SCREEN DEPTH | 33 |
|  Open Window | 34 |
|  Expressions | 35 |
|  Process Type | 36 |
|  Database Parameters | 37 |
|  Log Events | 38 |
|  Open Form Window | 39 |
|  Euro Currencies | 40 |
|  System Folder | 41 |
|  Form Objects (Properties) | 42 |
|  | | | |
|   Form Area | 43 |
|  Is License Available | 44 |
|  XML | 45 |
|   |
|  Web Services (Server) | 46 |
|  Print Options | 47 |
|  Web Services (Client) | 48 |
|  SQL | 49 |
|  Form Parameters | 50 |
|  Relations | 51 |
|  Dictionaries | 52 |
|  List Box | 53 |
|  Backup and Restore | 54 |
|  Picture Compression | 55 |
|  Menu Item Properties | 56 |
|  Data File Maintenance | 57 |
|  Index Type | 58 |
|  Value for Associated Standard Action | 59 |
|  System Format | 60 |
|  Picture Transformation | 61 |
|  Web Area | 62 |
|  PHP | 64 |
|  Multistyle Text Attributes | 65 |
|  Digest Type | 66 |
|  Form Objects (Access) | 67 |
|  Picture Metadata Names | 68 |
|  Picture Metadata Values | 69 |
|  Listbox Footer Calculation | 70 |
|  HTTP Client | 71 |
|  Design Object Access | 72 |
|  Serveur Web | 73 |
|  Database Events | 74 |
|  Shortcut and Associated Keys | 75 |
|  Standard Action | 76 |
|  Multistyle Text | 78 |
|  Form Object Types | 79 |
|  Font Type List | 80 |
|  4D Write Pro | 81 |
|  Graph Parameters | 82 |
|  LDAP | 83 |
|  Cache Management | 84 |
|  Objects and collections | 85 |
|  Strings | 86 |
|  File and Folder | 87 |
|  Parse formula | 88 |
|  Mail | 90 |
|  Compression | 91 |
|  Error handler | 92 |
|  DataStore Request Log | 93 |
|  Export structure | 94 |

