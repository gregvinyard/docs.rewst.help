# **Jinja Filters: Enhancing Rewst with Powerful Data Manipulation**

Jinja filters are a core part of the Jinja templating engine used by Rewst, allowing users to modify and manipulate data directly. Filters provide a quick, efficient way to format, transform, and interact with data dynamically, ensuring that workflow actions remain flexible and concise. They can be applied to variables, expressions, and even complex data structures, allowing you to adjust content presentation without altering the underlying data source.

Each filter serves a unique purpose, from text formatting and number calculations to date parsing and advanced data encoding. By leveraging filters, you can:

- **Format data for readability:** Convert raw data into user-friendly formats, such as dates, currency, or human-readable strings.
- **Enhance functionality:** Process lists, dictionaries, and other data structures to sort, group, or manipulate them based on dynamic conditions.
- **Improve efficiency:** Simplify complex operations, minimizing the need for extensive additional code.

This documentation provides an organized overview of Jinja filters, categorized by function, to help you quickly find the right tool for your task. Whether you're formatting text, working with dates, or performing conditional logic, Jinja filters add powerful, versatile capabilities to your templates.

### Text and String Manipulation
- `capitalize`
- `center`
- `e`, `escape`
- `first`
- `last`
- `lower`
- `replace`
- `safe`
- `title`
- `trim`
- `truncate`
- `upper`
- `wrap_text`
- `striptags`
- `wordcount`
- `wordwrap`

### Data Type Conversion

- `int`
- `float`
- `string`
- `tuple`
- `list`
- `dict`
- `set`

### Encoding/Decoding and Parsing
- `base64`
- `json`
- `json_dump`
- `json_escape`
- `json_parse`
- `json_stringify`
- `jsonpath_query`
- `from_json_string`
- `to_json_string`
- `from_yaml_string`
- `to_yaml_string`
- `yaml_dump`
- `yaml_parse`
- `to_ascii`
- `unidecode`
- `urlencode`
- `urlize`
- `xmlattr`
- `csv`
- `parse_csv`

### Regex and Pattern Matching
- `regex_findall`
- `regex_match`
- `regex_replace`
- `regex_search`
- `regex_substring`

### Conditional and Logical Filters
- `all`
- `any`
- `d`, `default`
- `select`
- `reject`
- `selectattr`
- `rejectattr`
- `use_none`

### Datetime and Time Manipulation
- `as_timezone`
- `convert_from_epoch`
- `datedelta`
- `format_datetime`
- `time_delta`
- `load_datetime`
- `to_human_time_from_seconds`
- `parse_datetime`

### List and Collection Manipulation
- `batch`
- `combine`
- `count`
- `dictsort`
- `enumerate`
- `flatten`
- `groupby`
- `items`
- `join`
- `length`
- `map`
- `reverse`
- `slice`
- `sort`
- `unique`
- `zip`

### Math and Number Manipulation
- `abs`
- `max`
- `min`
- `round`
- `sum`
- `random`

### File and Path Manipulation
- `basename`
- `dirname`
- `filesizeformat`

### Version Control
- `version_bump_major`
- `version_bump_minor`
- `version_bump_patch`
- `version_compare`
- `version_equal`
- `version_less_than`
- `version_more_than`
- `version_match`
- `version_strip_patch`

### Miscellaneous
- `attr`
- `hmac`
- `hex`
- `pprint`
- `reduce`
