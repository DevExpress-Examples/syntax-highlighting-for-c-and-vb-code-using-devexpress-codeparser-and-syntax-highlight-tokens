# Syntax highlighting for C# and VB code using DevExpress CodeParser and Syntax Highlight tokens


<p>This example demonstrates the use of the <strong>ISyntaxHighlightService </strong>to display source code of this example in different colors and fonts according to the category of terms. To accomplish this, the text is parsed into tokens according to language syntax elements. The project uses DevExpress parsers for C# and VB, available in the  <strong>DevExpress.CodeParser</strong> library. Resulting tokens are converted into <strong>SyntaxHighlightToken </strong>objects and format settings for different token types are specified. The <strong>DevExpress.XtraRichEdit.API.Native.SubDocument.ApplySyntaxHighlight</strong> method applies formatting to document ranges corresponding to the tokens.</p><p>
<br/>