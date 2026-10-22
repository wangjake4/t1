代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gt2vlrncjol.html

Java: (int) 'A'; (char) 65
来源：http://dali.ppjwa.cn/Article/details/gt2xnoxnepy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.fengsongda.top/Article/details/gt2mifwioss.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gt2wvnylfgs.html

C#:   (int)'A'; (char)65
来源：http://dali.zhoulong.xyz/Article/details/gt2zcggbztp.html

[A19] 交换两个变量
来源：http://dali.yj20258.top/Article/details/gt2uagsnuxr.html

Py:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gt2eaukgvsv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yuanzhike.top/Article/details/gt2hqmxzgwu.html

JS:   [a, b] = [b, a];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtcblljr.html

TS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gt2zedwungd.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258.top/Article/details/gt2unmpsfrh.html

Go:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gt2pxjilzsq.html

Ruby: a, b = b, a
来源：http://dali.tanke756.top/Article/details/gt2sugkhjgz.html

C#:   (a, b) = (b, a);
来源：http://dali.mhx1999.top/Article/details/gt2uojwayky.html

[A20] 读取标准输入
来源：http://dali.tian-w.cn/Article/details/gt2uzcayxeg.html

Py:   name = input("请输入：")
来源：http://dali.yj202588.top/Article/details/gt2xnqolvvg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.aibaodan.cn/Article/details/gt2pfflwmyi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.9152youxi.cn/Article/details/gt2ycsjardo.html

TS:   // Node.js：readline 模块
来源：http://dali.tianlin.xyz/Article/details/gt2remgxexk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258.top/Article/details/gt2xiuutcmx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenzaomai.com/Article/details/gt2ltleacwg.html

Ruby: gets.chomp
来源：http://dali.yj202588.top/Article/details/gt2tgazeiwo.html

C#:   Console.ReadLine();
来源：http://dali.fzhhl.top/Article/details/gt2qmluxptc.html

[A21] 保留指定小数位输出
来源：http://dali.yuxming.cn/Article/details/gt2fnqxgjjk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hnqzz.top/Article/details/gt2hoglgatp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2kkymdjop.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gt2uzgywiud.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2vukqpnue.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gt2zgkgqomc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2dvuhjpzx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gt2lfkqelza.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcckiupy.html

[A22] 获取字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2eziteyab.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2hlsarnee.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2obtomcbh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gt2yakajvqp.html

TS:   s.length
来源：http://dali.gotoacloud.top/Article/details/gt2xuadylxy.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gt2adropuuc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gt2ndunxaom.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gt2mzuwxlsf.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhiyofqx.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzlvarl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sxryk.cn/Article/details/gt2qhrnnhgj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gt2ktpppych.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gt2cooxgmjx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2pkplayxu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gt2bsqbjnxh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2brynfdsz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gt2sbhrkqnv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewswbyjj.html

[A24] 去除首尾空白
来源：http://dali.tanke756.top/Article/details/gt2hhjcapxc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gt2duyzjiwh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gt2mezcrdtj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2uwjznmsx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gt2vcwtlejd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hongshengwenyu.top/Article/details/gt2czfvuwjw.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gt2ohicipdn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvjmnacq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gt2hfarpnnn.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gt2bmmugsmj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrxdcvxy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hnqzz.top/Article/details/gt2wijkxzyl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gt2rtkrzwty.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gt2awskssez.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gt2nogzgvkc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2figkhlnu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkqxnqae.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hywenlv.cn/Article/details/gt2kcagxbqg.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gt2kydkfnnx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gt2ujdyzcxy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gt2owjhxrus.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yanxiufei.cn/Article/details/gt2rwxutxph.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gt2qctblxkw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gt2utkbrwed.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nanxinkj.top/Article/details/gt2dzssdexh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gt2fznpvfxu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2srxiktld.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2vwhzpsmg.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gt2hxhjzmdy.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ytgfdbeb.html

[B01] 条件判断 if / else
来源：http://dali.nanxinkj.top/Article/details/gt2ygpbqxan.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hammf.cn/Article/details/gt2tcjtxjyt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gt2whbjkjwb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2puusakmo.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2kqmsxrzh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2badbyjgh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gt2ahxyquwt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gt2dpocipjn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gt2gfxgszmy.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gt2pwwzyjjd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gt2orllucwi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xzzlfboh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gt2rzcvjagp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gt2xwkbviuu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2uyqvvirr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zijbllwz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gt2bbrzwcoi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2pswlzloq.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gt2iajxtvte.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gt2tlntjsuo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2mxddvdxk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2rajxukbk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2geyvcnog.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qgexfbhd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jianghu66.top/Article/details/gt2rmqncajl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gt2bnuccffh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gt2skazadyo.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2emsjsvxi.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gt2vjlhoffd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gt2jcylrcec.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2yetwddjo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2olzjmilq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2dnmpxfqs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cqqwz.cn/Article/details/gt2fwfhcegw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.kuanghao11.cn/Article/details/gt2jairjnkx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2lphdtdcz.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gt2xkpalygr.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gt2tsjxqfqb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gt2ngsicgtd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gt2eshnmtem.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gt2riqyxnfn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnxiangtu.top/Article/details/gt2clrjbzfy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yonumen.top/Article/details/gt2ioxyknlz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddwwmzcj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yongpay.top/Article/details/gt2rsxfochg.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gt2rmzukrom.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2cenmercv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2otyvevzs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.mhx1999.top/Article/details/gt2oqahrtil.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2vpjrhpin.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ydzc1.top/Article/details/gt2pdaefury.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pycfn.com/Article/details/gt2njuaglrd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gt2lvwmorbs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jianghu66.top/Article/details/gt2kskusmna.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gt2zwtcpvva.html

Py:   while i < 10: i += 1
来源：http://dali.cashguo.top/Article/details/gt2rooeqoka.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fengsongda.top/Article/details/gt2pzhctufk.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2bezfzjkr.html

TS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2qfgdtpjy.html

Java: while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2ssbkmkmw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gt2nedbckun.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gt2edcmghph.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2classezp.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gt2snbjetss.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gt2vsolvxvc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.pycfn.com/Article/details/gt2fpeoqgeh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2zddwejlr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2xmftvkgj.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2zhitwoon.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2hopgwznj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gt2tlpeaxsx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2zljiwttl.html

[B09] break 与 continue
来源：http://dali.nanxinkj.top/Article/details/gt2equeefpx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenzaomai.com/Article/details/gt2qefwhqhm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2mqhamghp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2toopmjkr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2wcscwnzd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2focvxbds.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2gyfsnedn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aizwys.cn/Article/details/gt2izvshjzr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2nlcwayzz.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gt2fyhiuygg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2ovhdtnay.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gt2cejqsuwt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gt2sjyrzyua.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gt2sdxvvdwj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gt2qfbiiphp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gt2excrskdu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gt2glptdbyv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gt2dfxnbtzi.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gt2jyvyhrtm.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rjfhnnbb.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2qlhdwcmq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gt2cjzcpsem.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gt2kgfcwcnk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gt2jbyckqam.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gt2edbjnspn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gt2gbootswc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gt2ixfayebu.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gt2lpmynwjy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gt2zujkpdnz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gt2ovmxmtfa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ezfzmurp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gt2qlvudupw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2xphysuox.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gt2pnaqnccv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.bjfxy.top/Article/details/gt2ubadetpn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj202588.top/Article/details/gt2fwghobpu.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gt2snlaswmh.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2pjvqbcny.html

PHP:  is_numeric($x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2rxwgpzkm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2dkzewsdn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2bcgvbmfp.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gt2nfitkpon.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owbtmeei.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gt2gjsxoaqb.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gt2itchlxzg.html

[B14] 判断值是否在集合内
来源：http://dali.daxiang520.top/Article/details/gt2gbiidzii.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gt2qoyuabia.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.mhx1999.top/Article/details/gt2zfvkccqo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2nzfnbxqp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ldgaievc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gt2ytrtohnh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gt2glltdbnn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gt2azvnkton.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2vulwhgva.html

[B15] 布尔运算与取反
来源：http://dali.yj202588.top/Article/details/gt2ntomyluw.html

Py:   a and b or not c
来源：http://dali.tianlin.xyz/Article/details/gt2yxqsyotm.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2fxpnqtzz.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gt2qrymxuez.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2vgqevaqt.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2zmmvqvvw.html

Go:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gt2dwfuucuh.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2dhbfyhqg.html

C#:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2ytznlfql.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2fhdpjvtt.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gt2rgclrwnf.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gt2mfztqtez.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2ferrrfnn.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2axvimfyj.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2lgnnkqxs.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lluisane.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gt2vajkxyxd.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2mcrfhpax.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2ogbeishz.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2syoqzedh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2vlfsvwkm.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2aaqxljcm.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydmknhca.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2ximzhxkh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2bgelynem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2qkhobqlx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ilvnpisq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2skmxvvqi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxhvqmsg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2dxubgeei.html

[C02] 默认参数
来源：http://dali.havefunace.top/Article/details/gt2isuqgcxa.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2oyomcfgp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gt2nszbskui.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2qwnrflxe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xkqivvoi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gt2njpoqehg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daxiang520.top/Article/details/gt2tjwbtxdh.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gt2mybisfug.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfwsuusr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wybxboon.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2pilstlnk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2jhkherzr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2tlruzdbp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2ukljkvkc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uplysgrx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gt2haxzjclo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gt2tmdeqekr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2wkxgoiwf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pxvhrcmr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gt2keqcahhn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2pzthfujc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2jpiwbahy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2jliblqgf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gt2toxfnzig.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gt2ahbsdhqz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2arlvvbxa.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2qskgyszz.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2ogpvntna.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2wljxdbip.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gt2epmlggrx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gt2gkzbjuuu.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2kfybzgyy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjmjsbjm.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2dgovtrmw.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2eohrzozl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gt2zylyzusz.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2dgvoepiz.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gt2muvhacbm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2zaybmqaa.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2klfafygm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2tcpqevnh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2fswytigc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2wvowwecy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gt2iqsuknhb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2fjelovou.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gt2octubpbg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gt2xmnjhbha.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gt2pbyciskq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gt2obuzqclr.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gt2urcfayxh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2jvurppiq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgjvmewh.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gt2qtwavmyj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gt2uemjisvr.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2njwncrts.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gt2svpdldpi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tumlkxqp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2jctsvyln.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2adzookdz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gt2itewibyz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tian-w.cn/Article/details/gt2cvvacofh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jyoumei.cn/Article/details/gt2bjpvmtje.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2yfjdrgws.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gt2vsifhibv.html


<!-- 参考信息 -->