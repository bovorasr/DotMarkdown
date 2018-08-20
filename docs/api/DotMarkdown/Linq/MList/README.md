<a name="_top"></a>

# MList Class

[Home](../../../README.md#_top) &#x2022; [Constructors](#constructors) &#x2022; [Properties](#properties) &#x2022; [Methods](#methods)

**Namespace**: [DotMarkdown.Linq](../README.md#_top)

**Assembly**: DotMarkdown\.dll

```csharp
public abstract class MList : MContainer
```

### Inheritance

[Object](https://docs.microsoft.com/en-us/dotnet/api/system.object) &#x2192; [MObject](../MObject/README.md#_top) &#x2192; [MElement](../MElement/README.md#_top) &#x2192; [MContainer](../MContainer/README.md#_top) &#x2192; MList

### Derived

* DotMarkdown\.Linq\.[MBulletList](../MBulletList/README.md#_top)
* DotMarkdown\.Linq\.[MOrderedList](../MOrderedList/README.md#_top)
* DotMarkdown\.Linq\.[MTaskList](../MTaskList/README.md#_top)

## Constructors

| Constructor | Summary |
| ----------- | ------- |
| [MList()](-ctor/README.md#DotMarkdown_Linq_MList__ctor) | |
| [MList(MList)](-ctor/README.md#DotMarkdown_Linq_MList__ctor_DotMarkdown_Linq_MList_) | |
| [MList(Object)](-ctor/README.md#DotMarkdown_Linq_MList__ctor_System_Object_) | |
| [MList(Object\[\])](-ctor/README.md#DotMarkdown_Linq_MList__ctor_System_Object___) | |

## Properties

| Property | Summary |
| -------- | ------- |
| [Document](../MObject/Document/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [FirstElement](../MContainer/FirstElement/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [IsEmpty](../MContainer/IsEmpty/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Kind](../MObject/Kind/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [LastElement](../MContainer/LastElement/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [NextElement](../MElement/NextElement/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [Parent](../MObject/Parent/README.md#_top) |  \(Inherited from [MObject](../MObject/README.md#_top)\) |
| [PreviousElement](../MElement/PreviousElement/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |

## Methods

| Method | Summary |
| ------ | ------- |
| [Add(Object)](../MContainer/Add/README.md#DotMarkdown_Linq_MContainer_Add_System_Object_) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Add(Object\[\])](../MContainer/Add/README.md#DotMarkdown_Linq_MContainer_Add_System_Object___) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Ancestors()](../MElement/Ancestors/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [AncestorsAndSelf()](../MContainer/AncestorsAndSelf/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Descendants()](../MContainer/Descendants/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [DescendantsAndSelf()](../MContainer/DescendantsAndSelf/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Elements()](../MContainer/Elements/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [ElementsAfterSelf()](../MElement/ElementsAfterSelf/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [ElementsBeforeSelf()](../MElement/ElementsBeforeSelf/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [Equals(Object)](https://docs.microsoft.com/en-us/dotnet/api/system.object.equals) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [GetHashCode()](https://docs.microsoft.com/en-us/dotnet/api/system.object.gethashcode) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [GetType()](https://docs.microsoft.com/en-us/dotnet/api/system.object.gettype) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [MemberwiseClone()](https://docs.microsoft.com/en-us/dotnet/api/system.object.memberwiseclone) |  \(Inherited from [Object](https://docs.microsoft.com/en-us/dotnet/api/system.object)\) |
| [Remove()](../MElement/Remove/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [RemoveAll()](../MContainer/RemoveAll/README.md#_top) |  \(Inherited from [MContainer](../MContainer/README.md#_top)\) |
| [Save(MarkdownWriter)](../MElement/Save/README.md#DotMarkdown_Linq_MElement_Save_DotMarkdown_MarkdownWriter_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [Save(Stream, MarkdownFormat)](../MElement/Save/README.md#DotMarkdown_Linq_MElement_Save_System_IO_Stream_DotMarkdown_MarkdownFormat_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [Save(String, MarkdownFormat)](../MElement/Save/README.md#DotMarkdown_Linq_MElement_Save_System_String_DotMarkdown_MarkdownFormat_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [Save(TextWriter, MarkdownFormat)](../MElement/Save/README.md#DotMarkdown_Linq_MElement_Save_System_IO_TextWriter_DotMarkdown_MarkdownFormat_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [ToString()](../MElement/ToString/README.md#DotMarkdown_Linq_MElement_ToString) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [ToString(MarkdownFormat)](../MElement/ToString/README.md#DotMarkdown_Linq_MElement_ToString_DotMarkdown_MarkdownFormat_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [ToString(MarkdownWriterSettings)](../MElement/ToString/README.md#DotMarkdown_Linq_MElement_ToString_DotMarkdown_MarkdownWriterSettings_) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
| [WriteTo(MarkdownWriter)](../MElement/WriteTo/README.md#_top) |  \(Inherited from [MElement](../MElement/README.md#_top)\) |
