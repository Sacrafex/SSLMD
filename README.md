# SSLMD (A2V2-LX1)
===========

Short Syntax Layout Markdown
----------------------------

*A Writing Language based on Logic mainly used for compact and fast note taking or logic testing.*

* * * * *

Rules / Allowances
---------------------

1.  **No Spaces**

2.  **Terms can be surrounded by multiple parameters**

3.  **Functions are followed until closing `&`**

* * * * *

Symbols & Short Syntax
-------------------------

### `>text` → Consequence / Result

**Syntax**: `>He failed the test`\
**Meaning**: What resulted due to a statement

### `@text` → Person / Attribution

**Syntax**: `@KJ`\
**Meaning**: Sourcing a person or giving attribution

### `#text` → Topic / Tag

**Syntax**: `#Math`\
**Meaning**: A tag showing relatedness

### `!text!` → Urgent

**Syntax**: `!Due Tomorrow!`\
**Meaning**: Important or urgent information

### `&text&` → Grouping

**Syntax**: `&if-true&John is cool`\
**Meaning**: Groups functions together

### `?text?` → Question / Confusion

**Syntax**: `?Why this happened?`\
**Meaning**: Indicates confusion or uncertainty

### `=text=` → Definition

**Syntax**: `=Osmosis=`\
**Meaning**: Indicates a definition

### `/text/` → Example or Directory

**Syntax**: `/rainforest/`\
**Meaning**: Gives a location or example

### `%text%` → Statistic / Number

**Syntax**: `%75%`\
**Meaning**: Shows a stat or numerical value

### `[text]` → Source / Reference

**Syntax**: `[GitHub]`\
**Meaning**: Cites a source or reference

### `+text+` → Addition / Inclusion

**Syntax**: `+New Feature+`\
**Meaning**: Adds something to logic or list

### `-text-` → Removal / Exclusion

**Syntax**: `-Old Feature-`\
**Meaning**: Removes or negates something

### `^text^` → Highlight / Focus

**Syntax**: `^Main Point^`\
**Meaning**: Emphasizes something

### `~text~` → Approximate / Estimate

**Syntax**: `~30 minutes~`\
**Meaning**: Approximate or uncertain value

### `$text$` → Value / Variable

**Syntax**: `$userInput$`\
**Meaning**: Represents a variable or dynamic value

### `*text*` → Action / Command

**Syntax**: `*Login*`\
**Meaning**: Represents an action or command

* * * * *

Functions
------------

### **IF**

Check a statement\
Example:\
`&IF&$x$>10>*DoThis*>END`

### **WHILE**

Waits for a condition to be true\
Example:\
`&WHILE&$loading$=*true*>*ShowSpinner*>END`

### **REPEAT**

Loops until told to stop\
Example:\
`&REPEAT&*PlaySound*>END`

### **END**

Ends a section

### **ENDALL**

Closes entire logic block

* * * * *

⚙Advanced Functions
---------------------

### **WHEN**

Trigger logic when condition is met\
Example:\
`&WHEN&$x$>10>*Alert*>END`

### **MATCH**

Compare data and act on match\
Example:\
`&MATCH&$input$=/rainforest/*Show Example*>END`

### **CHOOSE**

Branch logic based on value\
Example:\
`&CHOOSE&$option$=[A,B,C]*Execute A*>END`

### **TRY**

Attempt and handle failure\
Example:\
`&TRY&*Connect*>*Retry*>END`

### **NOT**

Negate a logical value\
Example:\
`&IF&!condition!*Reject*>END`

* * * * *

Structural Elements
----------------------

### `||text||` → Divider / Context Shift

**Syntax**: `||Switching Topics||`\
**Meaning**: Separates logic or thought

### `::text::` → Comment / Side Note

**Syntax**: `::Optional::`\
**Meaning**: Notes or non-critical info

### `<<text>>` → Backup / Historical Note

**Syntax**: `<<Used in v1>>`\
**Meaning**: Marks legacy or deprecated item

* * * * *
