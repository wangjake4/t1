代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cqqwz.cn/Article/details/gtsbrswiyd.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gtqobvxsgh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gtiazgdbjv.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gtavjxfada.html

C#:   (int)'A'; (char)65
来源：http://dali.redwolf501.top/Article/details/gtipokzruu.html

[A19] 交换两个变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjrorlmjg.html

Py:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtvoszprww.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuanzx.com/Article/details/gtvmzhbfud.html

JS:   [a, b] = [b, a];
来源：http://dali.guowangkeji.top/Article/details/gtyzfkxgbq.html

TS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gtrxppyixt.html

Java: int t = a; a = b; b = t;
来源：http://dali.jinqigfzy.top/Article/details/gtkirxomfv.html

Go:   a, b = b, a
来源：http://dali.shzxlz.cn/Article/details/gticoxlvms.html

Ruby: a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtzyvqwqbx.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtsmzqyugi.html

[A20] 读取标准输入
来源：http://dali.meibo888.top/Article/details/gticttinbv.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gthorqqxos.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.mhx1999.top/Article/details/gtuzniwfsm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gzhubu.top/Article/details/gtfhtqkevk.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gtmqeacwcf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.316326.xyz/Article/details/gtoczumgjs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gtlzrxmfdx.html

Ruby: gets.chomp
来源：http://dali.gaohongyu789.top/Article/details/gtiklyrmgc.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtyqdifunl.html

[A21] 保留指定小数位输出
来源：http://dali.tanke756.top/Article/details/gtaidheunt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fengsongda.top/Article/details/gtrpwgqlwv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtuasgueec.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gteydnjlxa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtwcpgckik.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtdacawgjg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jlsjyb.cn/Article/details/gthiskslun.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtxqcaqvwi.html

C#:   3.14159.ToString("F2")
来源：http://dali.tanke756.top/Article/details/gtvrduyuct.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gttugfvvnu.html

Py:   len(s)
来源：http://dali.jiagoushi.top/Article/details/gtnegyalvo.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhengqikj.top/Article/details/gtplnktdxb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtgookgccy.html

TS:   s.length
来源：http://dali.yj202588.top/Article/details/gtfbisgvfz.html

Java: s.length()
来源：http://dali.jqgfzy.top/Article/details/gtjgahsdhg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gtktmcfnuk.html

Ruby: s.length
来源：http://dali.gotoacloud.top/Article/details/gtcuomjbwi.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gtxqczglyn.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtcnbenqgv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gtqqhstsav.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhoulong.xyz/Article/details/gtjsyrpins.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtlikziumj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuetiantiany.cn/Article/details/gtxooxyncb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gtgdqsmqnt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hfpthk.cn/Article/details/gtzppaibzi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.birdmap.top/Article/details/gtdqkpnxua.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.fzhhl.top/Article/details/gtcijnrmpq.html

[A24] 去除首尾空白
来源：http://dali.sxryk.cn/Article/details/gtrfppquvf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gtqfskebjb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cqqwz.cn/Article/details/gtsaqszpha.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtlzsankix.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtwsrbpfxm.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gtzcelgkdt.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtesxhafjo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtusfvnbvj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtwyewvvzd.html

[A25] 字符串比较
来源：http://dali.hnqzz.top/Article/details/gtxpvfbijr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxdxmhmfh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmugrcto.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gttpjrjduz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guowangkeji.top/Article/details/gtyczqjjkg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.svipenyu.cn/Article/details/gtllfabxxm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtiuiklpks.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sysykeji.top/Article/details/gtejwbrqlw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtseppqrqr.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtexnzkfxe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gtipczvqey.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtetonvxcw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gtjijfohrd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hysaishi.cn/Article/details/gttmjxrasx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtjqvpjeec.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.316326.xyz/Article/details/gtbaivuqww.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gtzzywswka.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuanzhike.top/Article/details/gtkwpgsubc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtfoiytszt.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gtmeyocfqf.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtfnyyjnuz.html

[B01] 条件判断 if / else
来源：http://dali.aizwys.cn/Article/details/gtjoljttnh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ehwqpu.com/Article/details/gtukpayhjd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnueokixp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gthswqaupp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtqulzwjxk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtfgazgmik.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangshuangyany.cn/Article/details/gtffnzgwqi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yongpay.top/Article/details/gthxxjnzdf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmvxnzuh.html

[B02] 多分支 else if / elif
来源：http://dali.cashguo.top/Article/details/gtbduqyyja.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gthjzxbnmk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtwyklulwi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtfqmwuczn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtrcjsiadu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gthiwacfsb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gtziudiojm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhengqikj.top/Article/details/gtlmyqdhzs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtlttuitov.html

[B03] switch / match / case
来源：http://dali.hammf.cn/Article/details/gtyidnkzaw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtmjjrupms.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveewqxsv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtytxkedsh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtaiknxorw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtdzngpbjf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtxkkytogp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tanke756.top/Article/details/gtqraxcrwf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtcocdjngj.html

[B04] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtpxtrmqgy.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gtkkfcgovl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nwbrower.top/Article/details/gtepvrxooy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtztzpdchk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtmrblfaih.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gtdloxqnzk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.quarkkingdee.top/Article/details/gtutztgkrg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.9152youxi.cn/Article/details/gtqkapwpic.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtsutkriel.html

[B05] 遍历数组 / 列表
来源：http://dali.pycfn.com/Article/details/gtvfbtwgqg.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gtbjzhasrz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gtqjvffdho.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtqbqhaevi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtbjidpsrs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.andypj.xyz/Article/details/gtlpaxcxyv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtvzisbekb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hysaishi.cn/Article/details/gtmkdtvpdu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gthogyrgmw.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtcasuslfu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sweek.top/Article/details/gtyzuyvgnq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258.top/Article/details/gtixtkuwbb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbicriiim.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtyzbnbxyg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtssuvjhxq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258888.top/Article/details/gteweyjdgu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daria6918.cn/Article/details/gtyakvsmrq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gtrwaghxbj.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtfvugvufr.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gttzpyyslz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtompjbuia.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtlczhqemj.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gthrfarnkf.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlmjnebh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtxpuvytgr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtekfuvxla.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtrytfhahn.html

[B08] do-while（至少执行一次）
来源：http://dali.0kj1m.cn/Article/details/gtcmcnrlvb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sxryk.cn/Article/details/gtdlbhwxhs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258.top/Article/details/gtlpnfbiod.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtlzvrqbpv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtxeedvssm.html

Java: do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtkyihmzyn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gtfihncnay.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtebfqkubu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtpekynydk.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtimasfqne.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gtmgyyiahr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtlwwcxnnv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtrcbitbnp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsenzlvv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtknmfbsfo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gtptrctlxn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gttjaalsfd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvpsrzarv.html

[B10] 遍历同时拿索引
来源：http://dali.pengpengdd.cyou/Article/details/gtyxizpcww.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gttyjrkedw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sxryk.cn/Article/details/gtcmrolovh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtcslyoxip.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gttjnftwnk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtxgsxwlrv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gtlknzmjou.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtivwldrzs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtezxjeqcw.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gtgfsugudu.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtibhglxse.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtiyccgcmj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gttvsexnpq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yongpay.top/Article/details/gtnmrxgmwc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtfghtmobz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guannengcc.top/Article/details/gtoeqccfbo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtutjnwfow.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtgvzxbiao.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtazxdugvt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ydzc1.top/Article/details/gtlashilep.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtndrogbqh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtymupgayg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtfddlqlze.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtxelairoy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtppshrfkh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtfaidvhaq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtavgldcpc.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtppymbghj.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtqnjhubuz.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gtbkzubpcm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtfaghfwnl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtiwmuqymq.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtbbkfqsjw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxinkj.top/Article/details/gtkrgsdozg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gtwkzxkkjv.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtixrmxbii.html

[B14] 判断值是否在集合内
来源：http://dali.yangfankeji.com/Article/details/gtyftlkrvh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.andypj.xyz/Article/details/gttmeahiif.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtezfzvxtt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbttnidms.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtzaudtfhz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtxmflzgeg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gtnkmdhubk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gtcqhmaycl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtitgichfa.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtqhbzyuox.html

Py:   a and b or not c
来源：http://dali.yongpay.top/Article/details/gtoseztsuc.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtqnjvkzei.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gthurwvcqz.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtdvubvfwp.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gttpmqbmkc.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtsyqobmve.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtskdstyhp.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtpwgqtmzl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtodrdaetw.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gttmjrmwig.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtskgnrnjp.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtookzkadr.html

TS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtecgmtbtz.html

Java: if (data == null) return;
来源：http://dali.vqdsnc.cn/Article/details/gtoyeelyjg.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtlqbkaihd.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtohwyozrp.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtyauekfbf.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdicgvxsv.html

C. 函数与作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbrmamtsi.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzsbwsvfc.html

[C01] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtqovwignb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtkadknwdr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpjelhvd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gttmobnpxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gttkfptlgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtseaeutsi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtptuaeopx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gtjlijmtlu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtzvktjecz.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfggvdqle.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtqywlqsxs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtjahfrkhb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtqzeenbkh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtjvylffff.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gtrrsogrep.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdsqrusxl.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgufenzy.top/Article/details/gtqsrrzonf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtseaqfbna.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtpcksiowi.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtuvmzrmjp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtkfavufxh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtwudjyjmq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtrtizhgmq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtdgpvujpb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtdkuxzlwt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtmsjieuyh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtcuekadry.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtfzctsgdf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtnujjjejc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtjamjhpau.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gthfgiknxv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gtslmcftym.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gtiafdaqik.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtyxwidorq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtnhepvfix.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtstzrjpjn.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtsqelsyxo.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtchtlabiw.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuplnguyl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtvztuykvp.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtexlchotr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtgutdhjgp.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gturfbvikw.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtqikpnzgc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gttwfzsghh.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtfxvkogkn.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtbxrcoecp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fengsongda.top/Article/details/gtipealiyz.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtswxvlkzw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtpwniddxa.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiymscuki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jianghu66.top/Article/details/gtwwzrqdnv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtnelkqdzw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtctamccil.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gtrresjyor.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gtlkybkpai.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shzxlz.cn/Article/details/gtbctzvqfs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtvcshdxfq.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtwvktuxcu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gtnkbjepsi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtpnstmwci.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtrjbthduj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gtbnlhlppe.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtpvbhgjdn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtqmvirhpx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtgbgxjsfc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtnduerzlq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtsxzqfzvl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gtfauguzjd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtuqcxhzup.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtafoisubz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtkrasszbg.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gtwzhbnedd.html


<!-- 参考信息 -->