```J. Mark Locklear
Web225
15Aug17```

### General

These rules apply to all the languages below and have broad application regardless of the programming language or frameworking used.

Database queries-Avoid touching the database directly. Database abstraction (using functions instead of queries) helps keep your code forward-compatible and, in cases where results are cached in memory, it can be many times faster. The use of ORM’s is recommended when possible. This makes your database functions agnostic which has the advantage of giving developers and sysadmins more flexibility in using a database they prefer and also allowing for a change in a database as an application grows and changes.

Be Consistent-A consistent use of style, standards and syntax allows others (and yourself) to better understand and modify/update your code.

### PHP

Naming conventions-For general functions or methods use lowercase letters in variable, action/filter, and function names (never camelCase). Separate words via underscores. Don’t abbreviate variable names unnecessarily; let the code be unambiguous and self-documenting.

Namespace and Class Names:

* Only the characters a-z, A-Z and 0-9 are allowed for namespace and class names.

* Namespaces are usually written in UpperCamelCase but variations are allowed for well established names and abbreviations.

* Class names are always written in UpperCamelCase.

* The unqualified class name must be meant literally even without the namespace.

* The main purpose of namespaces is categorization and ordering

Method Names-All method names are written in lowerCamelCase. In order to avoid problems with different filesystems, only the characters a-z, A-Z and 0-9 are allowed for method names – don’t use special characters.

Variable Names-Variable names are written in lowerCamelCase and should be self-explanatory. They should not shortened beyond recognition, but rather longer if it makes their meaning clearer.

### HTML5

Always declare the document type as the first line in your document: <!DOCTYPE html>.

Close all HTML elements.

It is optional to close empty elements: <meta charset="utf-8"> or

<meta charset="utf-8" />

Use lowercase attribute names because:

* Mixing uppercase and lowercase names is bad

* Developers normally use lowercase names (as in XHTML)

* Lowercase look cleaner

* Lowercase are easier to write

### JavaScript

Variable Names-Use camelCase for both variable names and fuctions. All names start with a lowercase letter.

Always put spaces around operators: 	var x = y + z;

var values = ["Volvo", "Saab", "Fiat"];

Always Use four spaces for indentation: function toCelsius(fahrenheit) {

    						return (5 / 9) * (fahrenheit - 32);

}

End statements with semicolons ;

Object Rules-

* Place the opening bracket on the same line as the object name.

* Use colon plus one space between each property and its value.

* Use quotes around string values, not around numeric values.

* Do not add a comma after the last property-value pair.

* Place the closing bracket on a new line, without leading spaces.

* Always end an object definition with a semicolon.

