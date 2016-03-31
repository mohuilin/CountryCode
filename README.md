# CountryCode
最近开发中用到选择国家信息的功能，用于添加电话号码的国家代号前缀，所以，在网上趴了一下，找到的是这样的一个字典。
<br>
![](http://upload-images.jianshu.io/upload_images/1315663-03360f2e2b55454a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
<br>
但是我们在使用tableView的时候，如果做分组功能，对于中文，我们还需要获取中文的拼音首字母，并且针对搜索功能做优化。<br>
考虑到国家信息基本不会更变，所以，持久化了这样一个Json文件：
<br>
![](http://upload-images.jianshu.io/upload_images/1315663-f92a94c68ec41678.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
<br>
下次在用到这个的时候，可以自己加载这个json文件，到数组，当然你也可以根据需求，分组。