 这个 repo 专门用来收集scmroad.com 网站的所有问题。吐槽、灌水都可以，请在上方开 issue.

 本站改版，问题还有很多。请大家开 issue 前：
 - 清理浏览器缓存
 - ping scmroad.com 应该是 59 开头的 ip 地址. ping 出来的是74 开头的 ip，证明 dns 缓存还没失效，可以强制刷新 dns
   - windows
     获得缓存中的DNS ：ipconfig /displaydns
     强制清除DNS 缓存：ipconfig /flushdns

     也可以在服务器管理中重新启动DNS Client服务：net stop dnscache && net start dnscache

 - 直接访问 http://scmroad.com 前后都不要加前缀，后缀。如果浏览器自动补全，那是缓存没清理干净，请再次清理
 - http://scmroad.com/forum.php 的地址是不正确的，因为本站现在是 ror 的，不会有 php 页面，如果是这个地址证明缓存还是没清理干净。
 - 再次清理了本地缓存，浏览器依然顽固的跳转到 http://scmroad.com/forum.php  这有可能是有些 cdn 缓存还没有失效

 谢谢大家

 laofo
