<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/184236614/19.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T830412)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->

# Rich Text Editor for WinForms - Open and Save Encrypted Files 

The following sample project shows how to use the WinForms Rich Text Editor to load and save password-encrypted files. You can specify a password and an encryption type on the left pane and export the result to DOCX or DOC format. When a user re-opens the file with a new password, the [RichEditControl.EncryptedFilePasswordRequested](https://docs.devexpress.com/WindowsForms/DevExpress.XtraRichEdit.RichEditControl.EncryptedFilePasswordRequested) and [RichEditControl.EncryptedFilePasswordCheckFailed](https://docs.devexpress.com/WindowsForms/DevExpress.XtraRichEdit.RichEditControl.EncryptedFilePasswordCheckFailed) events occur. If the user cancels the operation or exceeds the number of attempts to enter the password, RichEditControl shows an exception message.

![image](./media/project_image.png)

## Files to Review

* [Form1.cs](./CS/RichEditControl_Encryption/Form1.cs) (VB: [Form1.vb](./VB/RichEditControl_Encryption/Form1.vb))

## Documentation

* [Restrictions and Protection in RichEdit Documents](https://docs.devexpress.com/WindowsForms/9331/controls-and-libraries/rich-text-editor/restrictions-and-protection)
<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=winforms-richedit-document-encryption&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=winforms-richedit-document-encryption&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
