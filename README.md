# BlazeLibs.CkEditor
BlazeLibs.CkEditor is free rich text editor for blazor using ckeditor library. 
It is super simple to use.
all the credit goes to https://ckeditor.com/
For more information about CKEDITOR please visit to https://ckeditor.com/docs/


*How to implement
>>> install NuGet Package : nuget install BlazeLibs.CkEditor</br>


For Blazor Wasm > On the index.Html File befor the
   </br>
   <code><script src="_framework/blazor.webassembly.js"></script></code>
     </br>
   place
   <code>
   <script src="_content/BlazeLibs.CkEditor/ckeditor.js"></script>
   <script src="_content/BlazeLibs.CkEditor/CKEditorInterop.js"></script>
   </code>
</br>
   For Blazor Server > On the Host.razor File befor the
   </br>
   <code><script src="_framework/blazor.js"></script></code>
     </br>
   place
   <code>
   <script src="_content/BlazeLibs.CkEditor/ckeditor.js"></script>
   <script src="_content/BlazeLibs.CkEditor/CKEditorInterop.js"></script>
   </code> </br>
>>> Use in the form and bind value 
</br>
 <\BlazeLibs.CkEditor.CkEditor Id="demo_editor"
                             @bind-Value=@Model.Body
                             UrlToPostImage="https://example.com/uploadroute"></BlazeLibs.CkEditor.CkEditor>\>

   </br>
Please replce the \ after <.

#Thank You
