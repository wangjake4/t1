代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.jyoumei.cn/Article/details/gt2aabqlwyb.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gt2pirtyuph.html

PHP:  ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gt2ceeekwaa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.redwolf501.top/Article/details/gt2somlxzau.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2tgjirvea.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gt2fqqbuadh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.meibo888.top/Article/details/gt2njuncwem.html

Ruby: "A".ord; 65.chr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcemwvss.html

C#:   (int)'A'; (char)65
来源：http://dali.ehwqpu.com/Article/details/gt2fjxgchev.html

[A19] 交换两个变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2kcxfqqiv.html

Py:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gt2umjjjkng.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jiagoushi.top/Article/details/gt2sibmklos.html

JS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gt2wzenussz.html

TS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gt2docafpcq.html

Java: int t = a; a = b; b = t;
来源：http://dali.snrcjt.cn/Article/details/gt2gshcmmzt.html

Go:   a, b = b, a
来源：http://dali.kuanghao11.cn/Article/details/gt2xuolgjlg.html

Ruby: a, b = b, a
来源：http://dali.cashguo.top/Article/details/gt2tluucozc.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gt2oasajkxb.html

[A20] 读取标准输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xneoqsmw.html

Py:   name = input("请输入：")
来源：http://dali.aizwys.cn/Article/details/gt2tamjlsja.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenjidiqi.icu/Article/details/gt2prcdvpmg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenjidiqi.icu/Article/details/gt2oxwynchs.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahtmjrrn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gt2czaastxg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gt2twwihmlx.html

Ruby: gets.chomp
来源：http://dali.zhoulong.xyz/Article/details/gt2grclyesh.html

C#:   Console.ReadLine();
来源：http://dali.hnqzz.top/Article/details/gt2amjdnhau.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gt2oaivssrn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ydzc1.top/Article/details/gt2qqwyorpi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gt2hysvletx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gt2wcuqzpyq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xcmybnwz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2ftqexqbr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gt2iablpzdi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gt2dgscihhp.html

C#:   3.14159.ToString("F2")
来源：http://dali.shangyingyoupin.top/Article/details/gt2vlujadka.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gt2hsgjsogu.html

Py:   len(s)
来源：http://dali.nanxuanxn.top/Article/details/gt2gjkktcsx.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.birdmap.top/Article/details/gt2cwfemfej.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gt2pyyzzses.html

TS:   s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2qrphpsyx.html

Java: s.length()
来源：http://dali.gaohongyu789.top/Article/details/gt2mnaoizrz.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.316326.xyz/Article/details/gt2xytzrvei.html

Ruby: s.length
来源：http://dali.shangyingyoupin.top/Article/details/gt2lgonnaok.html

C#:   s.Length
来源：http://dali.tianlin.xyz/Article/details/gt2xpiyrtwu.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2rtpicbdd.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gt2divxvvsu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cqqwz.cn/Article/details/gt2kzardiqz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2ybfwkbuo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dhgicgjg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gt2nyzclelw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gt2uggyfwbc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gt2gauvkwuy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pjdkluin.html

[A24] 去除首尾空白
来源：http://dali.yuanzhike.top/Article/details/gt2ayaljxjl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gt2lnsgwepp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nsjedere.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.quarkkingdee.top/Article/details/gt2awqtiurb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gt2fglkyhtk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gt2nofjdqlh.html

Go:   strings.TrimSpace(s)
来源：http://dali.0kj1m.cn/Article/details/gt2aqepgiat.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gt2lmmvieml.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2wzphrfiw.html

[A25] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vippwikn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.nwbrower.top/Article/details/gt2knkcfweh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytcuotzp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gt2vvofzrmk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gt2mifqabdp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bbbzrjzh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2vbsvrrch.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gt2qfbhxsvs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2risklegc.html

[A26] 类型转换总览
来源：http://dali.daxiang520.top/Article/details/gt2nvcqzowc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqmewnlq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssybvelv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ryvwrbmb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gt2marbnitb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gt2ojrwsfdo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258888.top/Article/details/gt2uddsrvft.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xziqi.cn/Article/details/gt2kwvrqpsa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gt2jtzxopgr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2plprteqk.html

B. 流程控制
来源：http://dali.cucudq.cn/Article/details/gt2msnsfdpp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2morvhapt.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gt2iicuvlmj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2flponpmd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2muueysmr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gt2vzizdvue.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wqjetcsz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gt2wqbjsbqq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vfbstedr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gt2wijkbrxr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2bjjdnhxq.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gt2xwzysiev.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cqqwz.cn/Article/details/gt2nvgbwflu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gt2nubpfnmh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2ewiuijar.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gt2ftvwnxmq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gt2ghnktdra.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daria6918.cn/Article/details/gt2vwoadirw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gt2xsooivxe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2hjmzioio.html

[B03] switch / match / case
来源：http://dali.svipenyu.cn/Article/details/gt2enytxiiw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gt2ufllwsqo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2qulfjkhg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cbgwvejb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gt2hdnivhqo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2bzjaalsg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigufen.top/Article/details/gt2ehnerbmp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.mhx1999.top/Article/details/gt2fpunijou.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2ecugezdv.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iximoqby.html

Py:   for i in range(10): print(i)
来源：http://dali.sysykeji.top/Article/details/gt2wrjcwfnn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gt2icjmybke.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gt2heyxyoqb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2tjrkpqmo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2hklvyvoa.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gt2vpbysjho.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gt2pdpysfsc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2vlhxazxq.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2ncqnrkkb.html

Py:   for item in arr: print(item)
来源：http://dali.jqgufenzy.top/Article/details/gt2itorcuqb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gt2ikmxgjkk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gt2dfcllodw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gt2gmstgeoj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gt2ofytdybz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jyoumei.cn/Article/details/gt2lovnkjzt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gt2nmuhnoss.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2tyyghavh.html

[B06] 遍历字典 / 对象
来源：http://dali.tian-w.cn/Article/details/gt2varrxkdi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftnkzbcm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigufen.top/Article/details/gt2qmtllzpq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gt2wsxinatx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2pwdnyuwq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gt2micneuli.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.meibo888.top/Article/details/gt2soeosvhg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gt2vmnixndw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gt2oxqwhprr.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gt2eopinime.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gt2sazfwqww.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2muxoxemn.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mvroeiik.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2ogvkofpy.html

Java: while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tvcstgth.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gt2icendeib.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2livvoyrj.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tizpgles.html

[B08] do-while（至少执行一次）
来源：http://dali.sweek.top/Article/details/gt2fyjijjoi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2wmmpueov.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2lxjkkvbw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2vlcgvsgr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gt2klbnuqej.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2ahnopfcl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2fqfrihqb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gt2yiylykou.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2hmygbkjh.html

[B09] break 与 continue
来源：http://dali.shzxlz.cn/Article/details/gt2grdcguis.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gt2aduzuzpu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2ouvvilxl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2xkdqroci.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2jtprhifw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2fivzjrng.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gt2wamcmgxk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gt2vijwyxrh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wcmhwhfl.html

[B10] 遍历同时拿索引
来源：http://dali.jianghu66.top/Article/details/gt2poekzduy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gt2aypfuwhs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gt2muwwpwft.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gt2krfqalim.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gt2danvhnfs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gt2evhgvons.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigufen.top/Article/details/gt2lltzeamq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gt2btloilkh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gt2slzohcaf.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gt2rdykruod.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gt2xpymstwo.html

PHP:  range(0, 10, 2);
来源：http://dali.gogol.net.cn/Article/details/gt2eqgtectr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gt2xtcdtyvw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gt2vsmmvkge.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2nedikeci.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gt2zyuffgkd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2dbyutiux.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gt2dzgchvfa.html

[B12] 跳出多层循环
来源：http://dali.ydzc1.top/Article/details/gt2mkvxhsgw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gt2rsjdyqib.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gt2ifdcqnjp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2qnnjimsq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2mqajwcnq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2gypdfjhq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gt2sujzjqla.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2qetkremp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwhfafxe.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2ioxtxtdr.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2lwsoenem.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gt2luycmikk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gt2pnbmocki.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gt2hfpwmlcc.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gt2vmrshkww.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gt2yfrqcdle.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gt2saexokwq.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gt2rwfxrhnz.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gt2onoljxmo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gt2lftgfcrd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gt2qrobanhs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2snkusuzq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gt2bgtwbjep.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2uayhrybk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gt2htjhzmga.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gt2jpylfpdh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gt2uwwwjuem.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gt2uwzqeeli.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gt2uxgetiux.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gt2qrmuaufi.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2xkckfgjb.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2miaomxny.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2bhgtzxuc.html

Go:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2gadxnnsn.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2jbljbsbz.html

C#:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2ggxepfzd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.guowangkeji.top/Article/details/gt2nxhjacvj.html

Py:   if not data: return
来源：http://dali.yj202588.top/Article/details/gt2nqlogpdq.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gt2wybkqdym.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gt2wcgynbim.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nutoigez.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2bbsboirk.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gt2gejfixva.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gt2bmxyrmyu.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gt2rppobtpt.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2aptippkz.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gt2rwoxjmpb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2hbsusgfb.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2mizjxofi.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gt2gsgocbyd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gt2nscjpxnf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2jbbmkihu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2dosywtdj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yxkntgnm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2oqinzezv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dianchejie.cn/Article/details/gt2oiokyacn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gt2vjpvnqyz.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gt2pvogasjr.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gt2ytjootmz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qdeetjlh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2nlcblxdt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2okkpywiu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gt2pcwkipqa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2xudxcpiz.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2yozeivuz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.quarkkingdee.top/Article/details/gt2jmoiuvqi.html

[C03] 可变参数
来源：http://dali.yuxming.cn/Article/details/gt2eqhjlikp.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gt2qnxafuxw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gt2tlexzonp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2svcmhkrq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gt2sginnped.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2rtawofde.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gt2dqlvbcnr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ivvv.top/Article/details/gt2jbeyixlp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gt2vfpxlcol.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbzdlulg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2nufskccg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gt2fsrsudof.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2wkbbakjs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2smwqlqkr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2dvignfhj.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2biylhhro.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zadqxbpk.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2wmpvlbbs.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gt2wshoejjb.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gt2wwxqugxi.html

PHP:  return [$a, $b];
来源：http://dali.zhixingplan.top/Article/details/gt2ekgwpzil.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2lhiwasfp.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2ytzmrujo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gt2wsxmiher.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2volshpjq.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gt2ylodynwj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gt2wfdesfvj.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gt2xvmbhixo.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gt2depqlbfn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gt2xojhuznt.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gt2dsikqcwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2lzoblpxn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xziqi.cn/Article/details/gt2pfnoewoj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gt2wwintbrt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gt2wpwoucyp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2entjgwpd.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gt2dkpudktt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.havefunace.top/Article/details/gt2gbaostao.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2eauygrlc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gt2btplkacw.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gt2onqzhrzf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2szmulaol.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gt2epfdrtgv.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenzaomai.com/Article/details/gt2ofgtfmit.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gt2cmwurbjz.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gt2fucnqwzf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gt2tkutokmt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gt2rkphblnw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2ktofmnrt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2niwpgfpj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2boaqyxye.html


<!-- 参考信息 -->