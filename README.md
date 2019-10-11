
| Available Function  | Tag      |Description|
| ------------- | -------------  |------------|
| include | {{ include() }}  |Includes a template such as Default Header, Default Footer, and Signature. |
| asset | {%asset assetname %} | Includes an existing asset such as a Company Logo.  
|extends| ```{{extends()}}``` |"Extends" another template by inserting it first. When the template system evaluates this tag, first if locates the parent and inserts it. The extends tag should be the first tag in the template.|
|get field answer|{{{{ get_field_answer(,)}}()}}|Loads the value of any field.|
