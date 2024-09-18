<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/141567505/18.2.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T830557)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# Syntax highlighting for C# and VB code using DevExpress CodeParser and Syntax Highlight tokens

This example demonstrates the use of the [ISyntaxHighlightService](https://docs.devexpress.com/OfficeFileAPI/DevExpress.XtraRichEdit.Services.ISyntaxHighlightService) to display the source code of this example in different colors and fonts according to the category of terms. The project uses DevExpress parsers for C# and VB, available in the **DevExpress.CodeParser** library. Resulting tokens are converted into [SyntaxHighlightToken](https://docs.devexpress.com/OfficeFileAPI/DevExpress.XtraRichEdit.API.Native.SyntaxHighlightToken) objects and format settings for different token types are specified. The [SubDocument.ApplySyntaxHighlight](https://docs.devexpress.com/OfficeFileAPI/DevExpress.XtraRichEdit.API.Native.SubDocument.ApplySyntaxHighlight(System.Collections.Generic.List-DevExpress.XtraRichEdit.API.Native.SyntaxHighlightToken-)) method applies formatting to document ranges corresponding to the tokens.

## More Examples

* [Rich Text Editor for WPF -- How to Use Syntax Highlight Tokens to implement T-SQL language Syntax Highlight](https://github.com/DevExpress-Examples/how-to-implement-t-sql-language-syntax-highlighting-by-creating-syntax-highlight-tokens)

## Documentation

* [How to: Highlight Document Syntax](https://docs.devexpress.com/WPF/14714/controls-and-libraries/rich-text-editor/examples/automation/how-to-highlight-document-syntax)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=syntax-highlighting-for-c-and-vb-code-using-devexpress-codeparser-and-syntax-highlight-tokens&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=syntax-highlighting-for-c-and-vb-code-using-devexpress-codeparser-and-syntax-highlight-tokens&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
