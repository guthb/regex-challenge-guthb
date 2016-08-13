#Regex

1. `p\w+\s\w+\s\w+\n{\n(?:\s{4}p\w+\s\w+\s(?<propertyName>\w+)\s{\s\w+;\s\w+;\s}\n)+}`


#Test Strings
`public class Part
{
    public string PartName { get; set; }
    public int PartId { get; set; }
}`
