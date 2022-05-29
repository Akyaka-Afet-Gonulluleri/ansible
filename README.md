# ansible

Tekno AAG ekibi tarafından AAG sunucusunu konfigüre etmek amacıyla ansible kullanılmıştır.
vscode dev containers eklentisi ile geliştirme ortamını kullanabilirsiniz.


`ansible all -m ping` sunucu erişimini kontrol etmek adına bu komutu çalıştırabilirsiniz, bu tüm sunuculara ping isteği atacaktır.

`ansible all -b -a "whoami"`bu scriptin çalışması için sudoers için nopasswd direktifi verilmesi gerekli, ilgili komutla bunu test edebilirsiniz.

