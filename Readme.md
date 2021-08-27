<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/141567505/18.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T830557)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# Syntax highlighting for C# and VB code using DevExpress CodeParser and Syntax Highlight tokens


<p>This example demonstrates the use of the <a href="https://documentation.devexpress.com/CoreLibraries/DevExpress.XtraRichEdit.Services.ISyntaxHighlightService.class">ISyntaxHighlightService</a> to display source code of this example in different colors and fonts according to the category of terms. To accomplish this, the text is parsed into tokens according to language syntax elements. The project uses DevExpress parsers for C# and VB, available in the  <strong>DevExpress.CodeParser</strong> library. Resulting tokens are converted into <a href="https://documentation.devexpress.com/CoreLibraries/DevExpress.XtraRichEdit.API.Native.SyntaxHighlightToken.class">SyntaxHighlightToken</a> objects and format settings for different token types are specified. The <a href="https://documentation.devexpress.com/CoreLibraries/DevExpress.XtraRichEdit.API.Native.SubDocument.ApplySyntaxHighlight.method">DevExpress.XtraRichEdit.API.Native.SubDocument.ApplySyntaxHighlight</a> method applies formatting to document ranges corresponding to the tokens.</p><p>
<br/>
