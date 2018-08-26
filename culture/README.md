# Utility.js


### _.parseDate(str)
Parse a string in a valid date pattern on current culture. Returns new `Date` or `null` if string was not a valid date
- `str` (_String_) - Date to parse

### _.parseNumber(str)
Parse a string in a valid number pattern on current culture. Returns `Number` or `null` if string was not a valid number
- `str` (_String_) - Number to parse

### _.format(value, fmt)
Format a date, number or string (like `String.Format`) into a string using current culture. Returns `string`
- `value` (_Date|Number|String_) - Value to be formated
- `fmt` (_String_) - String format. See: 

### _.culture(culture)
Get or set object to define current culture. If culture parameter are undefined, returns current culture object
- `culture` (_Object_) - Culture object definition

### _.dateAdd(datepart, number, date)
Add period into a date. Returns new `Date` object
- `datepart` (_String_) - Interval king definition (`y`, `M`, `d`, `H`, `m`, `s`, `f`)
- `number` (_Number_) - Amouth of interval
- `date` (_Date_) - Date to be added

### _.dateDiff(datepart, start, end)
Returns interval (`Number`) between two dates
- `datepart` (_String_) - Interval definition (`y`, `M`, `d`, `H`, `m`, `s`, `f`)
- `start` (_Date_) - Inital date
- `end` (_Date_) - Final date

### _.timeAgo(date)
Returns human time spend from now to date (returns `String`)
- `date` (_Date_) - Date to be converted