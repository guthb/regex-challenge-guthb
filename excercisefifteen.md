#Regex

1. `/p.*\n.*\n.*(?<propertyName>PartName).*\n\s{4}.*(?<propertyId>PartId).*\n./`

2. `/.*\n{\n*\n.*(?<varible>PartName).*\n\s{4}.*(?<varible2>PartId).*\n}/`

#Test Strings
`public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}`
