代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2rcqjbefv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpdraglq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gt2ofvotrsk.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2imphfxeg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xylfe.cn/Article/details/gt2bhphmaen.html

Py:   ord("A"); chr(65)
来源：http://dali.daria6918.cn/Article/details/gt2zcwmnupw.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clyxcmos.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gt2qedkagno.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gt2sbzbpdij.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gt2hxyqttwi.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xylfe.cn/Article/details/gt2nrvjcabw.html

Ruby: "A".ord; 65.chr
来源：http://dali.yonumen.top/Article/details/gt2rtrutaaz.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigfzy.top/Article/details/gt2oxczawat.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gt2jlbedetw.html

Py:   a, b = b, a
来源：http://dali.dianchejie.cn/Article/details/gt2bsjlzlvm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tian-w.cn/Article/details/gt2xscptkbb.html

JS:   [a, b] = [b, a];
来源：http://dali.smart0.xyz/Article/details/gt2oaudejqt.html

TS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gt2heayljty.html

Java: int t = a; a = b; b = t;
来源：http://dali.xylfe.cn/Article/details/gt2gclldzet.html

Go:   a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2ksayuxwh.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gt2bousxpxt.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gt2gjppjwqv.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gt2ssfcalph.html

Py:   name = input("请输入：")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wloyhrcv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ivvv.top/Article/details/gt2zhssmqhw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gt2bjjbsurs.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ihjoclsi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dmkjvedo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.kuanghao11.cn/Article/details/gt2lezlnaqt.html

Ruby: gets.chomp
来源：http://dali.chenjidiqi.icu/Article/details/gt2bynonogk.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gt2wdtebozk.html

[A21] 保留指定小数位输出
来源：http://dali.zhengqikj.top/Article/details/gt2dveauahl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.birdmap.top/Article/details/gt2iuyzlrml.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2itsydzzl.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cucudq.cn/Article/details/gt2vfvbfrlr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2ekbtytlk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2jmheresg.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gt2awecoeow.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gt2yitpcorn.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gt2ewzzczlp.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2eyrhcdgj.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gt2hrluphak.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fzhhl.top/Article/details/gt2wshdvgqq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gaohongyu789.top/Article/details/gt2ujbogqxy.html

TS:   s.length
来源：http://dali.yueranfly.top/Article/details/gt2bflpmtqw.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2tndwssll.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sufxvd.cn/Article/details/gt2ujlvyfcg.html

Ruby: s.length
来源：http://dali.mhx1999.top/Article/details/gt2dtpfqvbm.html

C#:   s.Length
来源：http://dali.havefunace.top/Article/details/gt2pfuvvsom.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2pdopntnc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nanxinkj.top/Article/details/gt2pvqiaftv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.chenzaomai.com/Article/details/gt2qcrrikxf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gt2uyajoody.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gt2pktadmhl.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangshuangyany.cn/Article/details/gt2lwptrebn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsxlafbs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zdqjudy.top/Article/details/gt2llhkmkmh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj202588.top/Article/details/gt2iobtwwrb.html

[A24] 去除首尾空白
来源：http://dali.nwbrower.top/Article/details/gt2zrovqnov.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ydzc1.top/Article/details/gt2ntqjbsmm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigfzy.top/Article/details/gt2snchbjka.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gt2eewvljqk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj20258888.top/Article/details/gt2mpkgpbaa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.sxryk.cn/Article/details/gt2ipuksxtb.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gt2kvnqvwus.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jlsjyb.cn/Article/details/gt2apmtzews.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gt2glkjgmwp.html

[A25] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gt2momcoeoz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gt2nbcrzgtk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2vpeofxtu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2klagjono.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2uoeigfzq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.smart0.xyz/Article/details/gt2kcowspjz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gt2fyweygsb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258.top/Article/details/gt2yrvnfcgl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gt2ouompjqp.html

[A26] 类型转换总览
来源：http://dali.feifeiyinyue.top/Article/details/gt2ycupjvae.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gt2wcmyxnbb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gt2oysxwwcs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sufxvd.cn/Article/details/gt2gxibsgaw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.birdmap.top/Article/details/gt2pojooase.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.kuanghao11.cn/Article/details/gt2qeciryqw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qtckjpke.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2cwohmmpr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gt2iwlulsuc.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2upmnuxit.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gt2emtutkde.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2cuyoshvl.html

[B01] 条件判断 if / else
来源：http://dali.shuidangran.top/Article/details/gt2kgcmpoyn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gt2ptakrtkv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2icdgrwax.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2ejqnnxrc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gkdkxnss.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2yfviiwmc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.birdmap.top/Article/details/gt2mzshfkbn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.pycfn.com/Article/details/gt2giiommyj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gt2kvmxzyjh.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gt2oiafqryp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cdnleiting.top/Article/details/gt2svbffigt.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhmjucyf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2aeqdfbpw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2agpfqlun.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2ciunzzaq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhqmmxqa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nwbrower.top/Article/details/gt2vkwbojco.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gt2pduchauc.html

[B03] switch / match / case
来源：http://dali.hysaishi.cn/Article/details/gt2isjujmwx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddpgypdz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iqyqknix.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2fwdmkkpp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gt2hgteffve.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2azpfidge.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gt2uzlyeufd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.meibo888.top/Article/details/gt2vjjrcete.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yanxiufei.cn/Article/details/gt2qqxhkuwn.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2rhuwpabx.html

Py:   for i in range(10): print(i)
来源：http://dali.hnqzz.top/Article/details/gt2gjdortqk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gt2higibyap.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oltgfocg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2pwrnsnxg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2uodscrie.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gt2bfjvyagh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhijiandao.cn/Article/details/gt2jofaxyft.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gt2hebgtyyq.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2ghdubwra.html

Py:   for item in arr: print(item)
来源：http://dali.shuidangran.top/Article/details/gt2hsoqtyqn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clupvyfc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gt2pocybipp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2ytxxaawj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gt2nnarkpad.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gt2aziwndky.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gt2kafcsirr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2rylknzlg.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2vkuniakg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jyoumei.cn/Article/details/gt2eocuzwuj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cegbczhi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gt2janhtfdd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gt2fxlhtcxd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhoulong.xyz/Article/details/gt2ebtxdxlc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gt2qptxogyj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gt2faiivvpd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gt2qczvuvps.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gt2wcnacdlj.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2xjwllbdj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2tstlocze.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2vqyyqsvt.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2vfkcsicz.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oelphfij.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuxming.cn/Article/details/gt2xjqnhvpr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gt2uangnyky.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2zuspskcv.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gt2tghmlbvz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gt2nfnjxalu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2yxmbfdar.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2jdxscbwn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2dupksoij.html

Java: do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2uwjbzscd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.mhx1999.top/Article/details/gt2oefdtjgi.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.svipenyu.cn/Article/details/gt2zdibqtqj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2zvibxyni.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gt2abmvijuw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gt2caiorqaz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2nsdlqqmu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2mfwfezej.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gt2qneuayew.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ebgiblbk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yj20258.top/Article/details/gt2ngegtqww.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gt2mxmxltzt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2kushhheo.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xedqxsbv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gt2vtdouavp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2joolqtoh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gt2fatvyruc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gt2qvtndxhc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2cxgxpbaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gt2vzmwxtez.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gt2xxjhbhug.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gt2ucvkdszq.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gt2kfjjgufn.html

Py:   list(range(0, 10, 2))
来源：http://dali.feifeiyinyue.top/Article/details/gt2rakbxxit.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gt2eyifmqej.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2ahbcmmyp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gt2pdldxtoi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gt2ulfgdurk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.haohaochexian.top/Article/details/gt2bhrnsfzz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzaprxbd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gt2gkwhoigz.html

[B12] 跳出多层循环
来源：http://dali.zhengqikj.top/Article/details/gt2galeilxd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqruwzel.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gt2aiwrpdje.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gt2sunafuvi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2extkqitl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2jqkomhzd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrxeevyh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cheryme.top/Article/details/gt2jrtcptoj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rguklnfw.html

[B13] 判断是否为数字
来源：http://dali.shzxlz.cn/Article/details/gt2jmgekryx.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gt2toycpubj.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gt2cacnjpkw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gt2jrgdlxgi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ozbvxrpx.html

Java: x instanceof Number
来源：http://dali.tianlin.xyz/Article/details/gt2kkihcpqk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gt2cxhdqvwn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gt2vgfexyyc.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2hubspkqo.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gt2asnanyre.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gt2afehijpb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2pqpjtwvn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2jauymemd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2rwevdpwo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gt2sozuoyuz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gt2lcmqoyui.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gt2hntioimk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2znmweqxg.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gt2dujjegle.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gt2aoosoljc.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2qhspbgvr.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2ulipluuv.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2pdzuqusj.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2kkzduamp.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2fdruahyb.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2pffjlyjp.html

C#:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2ndwuczqg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gt2gdpqgxwr.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gt2uoswvkqe.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2ylzsgwtn.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gt2wbztssoy.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2leasaoax.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gt2ioxbgeor.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gt2cojffmyb.html

Ruby: return if data.nil?
来源：http://dali.pycfn.com/Article/details/gt2yqshxqwv.html

C#:   if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvyqearl.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2tqutqmej.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrlwkljr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2algxtqtd.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gt2pcbgeiol.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gt2jcqtlvne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2mwvoqhvw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lqupsbvr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2oggzqypr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2cwuoynmi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frpibjqc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gt2bujewxwh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2rohdgyez.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2ghyhpypf.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2wjbstozj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gt2ldoxyrjz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2vzpbykqb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2bcuwjrty.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2yoeucape.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2gazsgeay.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gt2hrkqwwxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.vqdsnc.cn/Article/details/gt2eqakkgxp.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uuveorxb.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gt2gdlwqoll.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2byowlioz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxplztoq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2oyhcjxky.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gt2wygvrinz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gt2qdqvmcfv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gt2saulfxik.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2twztwozv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2lykxiwww.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gt2ssamcqty.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2adrwncun.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2jzcnbhhh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2mqlpkrab.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2wxpjwndy.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2tlwrbjqa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gt2bdxmjbdp.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2xtegbnme.html

[C05] 返回多个值
来源：http://dali.zhiwuduotai.top/Article/details/gt2wqwdxcfi.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2aytacqgi.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gt2zwobqocs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gt2xutfmfjt.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2paorfesh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gt2onedwffh.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2hipighjs.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gt2xtcotefl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gt2vadsdrtt.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gt2tgnygovx.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gt2fegiyrdd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gt2qolfmhzr.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gt2pjuzvdzq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2fkacouhx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2algtnlgr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2tknacqyd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2yjidrasm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2gqrkzrjg.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gt2thbhqwdd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gt2pfqsreqi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gt2wfrcbarx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2dizuxjmw.html

TS:   arr.map(String)
来源：http://dali.svipenyu.cn/Article/details/gt2jyssmwtm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2slxjbvwj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2mjyzaoks.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gt2ebkzwgzv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gt2qqqouukn.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gt2rerqgwjb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gt2ufsweivo.html


<!-- 参考信息 -->