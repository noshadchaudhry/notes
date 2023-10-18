# Regex-Notes
# Regex-Powershell
about_regular_expression
Select-String, -match -cmatch -replace -split operators, switch STMT with -regex option.
-casesensitive param/flag

KB chars char class range [ -~].

[regex]::escape('3.\d{2,}')
When put $ in Regex Exp '5.72' -replace '(.+)', '$$$1'
"5.72" -replace "(.+)", "`$`$`$1"



Use the $Matches Hashtable automatic variable to retrieve captured text. 
Entire match is in key $Matches.0;
Can use [0] or ..Iitem[0].
$& reps all matched.

?<NamedCapt>
Then use matches.name

-replace Use ‘$1 $2 $3’.
${var} for named or even {$1}.
More

https://learn.microsoft.com/en-us/dotnet/standard/base-types/substitutions-in-regular-expressions


System.Globalization;
System.Text.RegularExpressions;

RegexOptions.IgnoreCase as Arg 4 to replace.

\n is u000A
Have \r.
Supp \p{ name }.

