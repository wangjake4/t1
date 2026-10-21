代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtlkdmfrxb.html

Java: (int) 'A'; (char) 65
来源：http://dali.hfpthk.cn/Article/details/gtrnncveqf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.smart0.xyz/Article/details/gtpvamvlsd.html

Ruby: "A".ord; 65.chr
来源：http://dali.yuxming.cn/Article/details/gtyiyxcnbg.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gtacppeoah.html

[A19] 交换两个变量
来源：http://dali.fzhhl.top/Article/details/gtizbirznn.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtaqozvizx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuetiantiany.cn/Article/details/gtxqlsywfl.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtrragpkpz.html

TS:   [a, b] = [b, a];
来源：http://dali.shzxlz.cn/Article/details/gtnunugxms.html

Java: int t = a; a = b; b = t;
来源：http://dali.sxryk.cn/Article/details/gtrtuduayl.html

Go:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtdqintzwy.html

Ruby: a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtuksmxmpk.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258888.top/Article/details/gtsptuwufx.html

[A20] 读取标准输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpinecus.html

Py:   name = input("请输入：")
来源：http://dali.gotoacloud.top/Article/details/gtciqkkrvt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fzhhl.top/Article/details/gtrwwlhoga.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gtysjeftjv.html

TS:   // Node.js：readline 模块
来源：http://dali.xziqi.cn/Article/details/gtvpvmwnxl.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sufxvd.cn/Article/details/gttruteenm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gogol.net.cn/Article/details/gtqleptflo.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtfjcmzypr.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtszefiiqq.html

[A21] 保留指定小数位输出
来源：http://dali.hammf.cn/Article/details/gtablhsemi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gttkbiltht.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gtgoxyylhc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.andypj.xyz/Article/details/gtsgybgbqt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtxfbevpav.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daxiang520.top/Article/details/gtiomalmbt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtiuvrcsqo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtmdlvgjrd.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gtggfkodmu.html

[A22] 获取字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtvodblkfh.html

Py:   len(s)
来源：http://dali.zhiwuduotai.top/Article/details/gttdyiffvz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ppjwa.cn/Article/details/gttzivtbfn.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.316326.xyz/Article/details/gtcxulaqla.html

TS:   s.length
来源：http://dali.zdqjudy.top/Article/details/gtvybdsdmk.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtkpggpkaj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.meibo888.top/Article/details/gtgwktveop.html

Ruby: s.length
来源：http://dali.dianchejie.cn/Article/details/gtqvfsorya.html

C#:   s.Length
来源：http://dali.daxiang520.top/Article/details/gtnvnryigy.html

[A23] 大小写转换
来源：http://dali.meibo888.top/Article/details/gtdvjgzowq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.svipenyu.cn/Article/details/gteizuekua.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgufenzy.top/Article/details/gtkujwbdls.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tanke756.top/Article/details/gtqoeizpnb.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtlbdtwrqc.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtzejvkabu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.haohaochexian.top/Article/details/gtlnyrjenk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yangfankeji.com/Article/details/gthoehoeiy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.dianchejie.cn/Article/details/gtfskrwgqo.html

[A24] 去除首尾空白
来源：http://dali.yanxiufei.cn/Article/details/gtmqyikewp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sufxvd.cn/Article/details/gtnzegsqkd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxuanxn.top/Article/details/gtsahueetq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtakdcdanw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gotoacloud.top/Article/details/gtebmhdiss.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gaohongyu789.top/Article/details/gtqrsdsczj.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtfzubguef.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenlongwang.top/Article/details/gtodskzgnl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjabvmwal.html

[A25] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtvqyqunoc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gthtnkfart.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jlsjyb.cn/Article/details/gtcmiyjxuz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guowangkeji.top/Article/details/gtkdnvoqvj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtzjnnozwd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gtfsqwgdki.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gtdamvagbf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnqzz.top/Article/details/gtnzoklaxs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqqqblqh.html

[A26] 类型转换总览
来源：http://dali.iojbl.cn/Article/details/gtoxaybqxg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gtlsmcfdcc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cdnleiting.top/Article/details/gtbqjhqbqd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.meibo888.top/Article/details/gtbgzhvryq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sxryk.cn/Article/details/gtnvajduwl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtwjqdmcvb.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guannengcc.top/Article/details/gtrbzwwxxc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gtpgbxmmwb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gtsqrlwyol.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtudlkbflh.html

B. 流程控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggjezscz.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtuqeypkac.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gtbednbpes.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfhbbfffh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gtltuyqilt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gtnjhvilmp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtzavorgyu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtugpdqqsm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtjyzetcak.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfsyczvt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtqczqebpv.html

[B02] 多分支 else if / elif
来源：http://dali.yongpay.top/Article/details/gtywctmcmm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenjidiqi.icu/Article/details/gtbyeshowz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tianlin.xyz/Article/details/gtidhidfnt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtmkqcguoi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtmvlrwbqy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvwsktmm.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xuetiantiany.cn/Article/details/gttjtskfzp.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ydzc1.top/Article/details/gtcyiucjke.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtgcqfqwmb.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtsctzdkmx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gthlnuokvo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtbblbbxoj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gteslpmkrp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtoulnougu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtmgfbqbqz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gzhubu.top/Article/details/gttrsngsmk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuanzhike.top/Article/details/gtqakxpxzc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gtmenjohon.html

[B04] for 计数循环
来源：http://dali.hysaishi.cn/Article/details/gtvqypopdh.html

Py:   for i in range(10): print(i)
来源：http://dali.cqqwz.cn/Article/details/gtvdytrple.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nwbrower.top/Article/details/gtjvjsokak.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtdowtyrmi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtbxhqkofr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtpjknqhfm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zycfv.cn/Article/details/gtvgszzbps.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gtpfabivtp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnqzz.top/Article/details/gtjipugswy.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtodiahzlf.html

Py:   for item in arr: print(item)
来源：http://dali.hongshengwenyu.top/Article/details/gtumemdacn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbylkjwwe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtherisgse.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtoztezuhq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrnrcpgn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtesxyvazh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sufxvd.cn/Article/details/gtdmbbkfko.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sweek.top/Article/details/gtvbalmnbp.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gthwfjgpjd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gtfzoopers.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gtaovyxedi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtjmeoyzmi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtwlynxhhk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hywenlv.cn/Article/details/gtinjaijea.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gteqekkzxo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yuxming.cn/Article/details/gtmeqvupjq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtlqcyjcwo.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gtmlfgdnve.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gtvgqlomqr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoiwbtymw.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtzpvvpihu.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtgotxtklc.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtmgseumit.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gtwhsfzhte.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtcakhworo.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtfejbrumj.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gtmitlftxw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xziqi.cn/Article/details/gtoaqzxqws.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtsvewkhxi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtmmltrmrx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtsvkxribk.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtuojuwknd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbsxcjvkb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtcaxyrehn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gttfkljpnj.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gtwojkwsix.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gttyvhpqik.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtaiuchpjc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtpumhbgbi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtsjtzvjex.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtblnspjct.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.smart0.xyz/Article/details/gtjrkyofou.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gtgmyutywp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdumdchuv.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gtenajxcpz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yanxiufei.cn/Article/details/gtpsohzxah.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gtnkoknzrv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdmxvlwm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtybtgjtam.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtdyskjget.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtnhjmamiq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tian-w.cn/Article/details/gtnrkesbbf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gtihryyjhs.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gtcuejblzh.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gtruqlzxgd.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gtgkpybubz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtbepegbwk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtdnagjakk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxuanxn.top/Article/details/gtjzkbrmxy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gttehscsed.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtqswqavdv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtqonqcahz.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gtqkfkbfwi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtxpcvxtyb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gthnozvcsh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gttrpshffl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtolwgdceb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtqmttxqhk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtszmpdcpv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gthvrfbfxy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtsodckajv.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gtupfdrxrz.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtxqbpzzcu.html

PHP:  is_numeric($x)
来源：http://dali.zhixingplan.top/Article/details/gtkggecgdd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjglhsmko.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjcqzseu.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtjbqcfxqm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtbyvaicmp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtdptbqqsf.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtuohinedq.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gtrsijgtbf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtajkyqndy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cashguo.top/Article/details/gtmyhkycbf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtxebjnwef.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtwiwmktts.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfwdjuyou.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtmakmkplw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gtufaupmjc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gtljxzdhbm.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkigvesd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gttfhrduzf.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtzvdjjhvz.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtfdnfjddn.html

TS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtbofyidzy.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtrhnafxzo.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtwauuemdz.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtjieprein.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtsidmrpvg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gtmnsvbzrf.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtcorxhpxc.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gttpcoevpa.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtzronltol.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtqeqjtrbg.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtuilyixmz.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtpofrurkk.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtjnqjjkls.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtouamuklw.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtjcgtfdmb.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gtimsquzpm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwfduehby.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtxqediubq.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtuvozofme.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtsnikeenq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtcipvmrlm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtycbteiht.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtxosnyhde.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtwvpullip.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtcvfipfgb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtemvlpmyp.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtctviotch.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtflquuund.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtnntvaluv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gttthkbywt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtlzfjmsvr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtytfdroqz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtuggyjgas.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gttcwlvnsv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtnaieiibn.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gtpopldwaf.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtvkipieer.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtnyvbwhiu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtesnghdui.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtcsgwmwmz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gthbojsrpi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gteayvtxfm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtsaesrqpx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtfhasmdqn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gtcbcfjuyt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlclvsnyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ppjwa.cn/Article/details/gtgthkoxhx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gtpdpwiycm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtdlzjpawz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtrpwnejkg.html

Go:   // 无：用配置结构体参数
来源：http://dali.hywenlv.cn/Article/details/gtmyeputxj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtpqvdpgrx.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtfsraondl.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtdfstriyr.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtqvazqsih.html

PHP:  return [$a, $b];
来源：http://dali.sweek.top/Article/details/gtiipewnec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtqvpsfdlk.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtpdpiieyq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtfypdwpqo.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtjvaqmouu.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtmcswxiya.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxfbiwyuv.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtwmjbswpb.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtgupqztjr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtzzekhlun.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtxzsymjfj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthesdufbq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtpjpbioof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gttmtzkdim.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gttkyqooiu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtjritolyr.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gtbdrfjcfy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtksmfimlk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtnhruuwyk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtlgekdlfz.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtqigxuavh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtbpoxryhi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtvxvgvvxm.html

Ruby: arr.map(&:upcase)
来源：http://dali.kuanghao11.cn/Article/details/gtbljgtitv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gtyltshgwz.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtjviqxwdo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtmarikodu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtkrngyggu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtfrlyzipq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gthgnzqqjm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtatkgzsfb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtyoexkbzo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtzryyfzbg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtdqouhygx.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtpxhiijxh.html


<!-- 参考信息 -->