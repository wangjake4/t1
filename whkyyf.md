代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.316326.xyz/Article/details/gt2kbnxqkfl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuanzhike.top/Article/details/gt2kskkmywg.html

TS:   if (!x) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pgiiwpyd.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.redwolf501.top/Article/details/gt2ezanjkkg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.sufxvd.cn/Article/details/gt2tjtdtqal.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gt2sbyrwman.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sysykeji.top/Article/details/gt2qhphjdmk.html

[A17] 位运算
来源：http://dali.haohaochexian.top/Article/details/gt2vtmflnti.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sosertrq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2wpdqryqr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gt2awinfzor.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2tvdtqonz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gt2bimpqzci.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gt2slqseduf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2xsadujdr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gt2xnyrdsyn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hysaishi.cn/Article/details/gt2jwvmmgyq.html

Py:   ord("A"); chr(65)
来源：http://dali.hysaishi.cn/Article/details/gt2vtwtyigf.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2twpyiism.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hnxiangtu.top/Article/details/gt2iliuhbwb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ydzc1.top/Article/details/gt2mhmjindl.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gt2egzulveb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hnnsrcpd.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigfzy.top/Article/details/gt2xoxswujo.html

C#:   (int)'A'; (char)65
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmkxppom.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gt2qnwjnamw.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2mpyexycz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cdnleiting.top/Article/details/gt2omvocrfj.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gt2zmmjryym.html

TS:   [a, b] = [b, a];
来源：http://dali.cdnleiting.top/Article/details/gt2ftuqvmrj.html

Java: int t = a; a = b; b = t;
来源：http://dali.hongshengwenyu.top/Article/details/gt2wvnmjpva.html

Go:   a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gt2qotnxldg.html

Ruby: a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gt2gjjgfkuv.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gt2yipjhebk.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gt2gxkeijbw.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gt2syfrfvyo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gzhubu.top/Article/details/gt2ctdfjdit.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gt2zzejaufy.html

TS:   // Node.js：readline 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbbitxhx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gt2hbdlfejh.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ivvv.top/Article/details/gt2vfecpptg.html

Ruby: gets.chomp
来源：http://dali.fzhhl.top/Article/details/gt2vgdqldql.html

C#:   Console.ReadLine();
来源：http://dali.hongshengwenyu.top/Article/details/gt2biyhaujb.html

[A21] 保留指定小数位输出
来源：http://dali.aibaodan.cn/Article/details/gt2cuqwjjgf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.andypj.xyz/Article/details/gt2ozmlehlo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qjecszup.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2cfhtvxqa.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sxryk.cn/Article/details/gt2dhxxewkf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2fzlacdsr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gt2srjesuhh.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gt2ehecpbfm.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnxiangtu.top/Article/details/gt2fdwtkrre.html

[A22] 获取字符串长度
来源：http://dali.svipenyu.cn/Article/details/gt2xefpzuem.html

Py:   len(s)
来源：http://dali.jyoumei.cn/Article/details/gt2humhxwfc.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258.top/Article/details/gt2xiqlznzi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gt2xhlhxjyr.html

TS:   s.length
来源：http://dali.xuanzx.com/Article/details/gt2ibtaianj.html

Java: s.length()
来源：http://dali.yangfankeji.com/Article/details/gt2hujreuew.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjqhwxos.html

Ruby: s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2indnvowt.html

C#:   s.Length
来源：http://dali.vqdsnc.cn/Article/details/gt2pwuotcyl.html

[A23] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gt2fguzywmn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sweek.top/Article/details/gt2xlvxrafc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nwbrower.top/Article/details/gt2waptrcpt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gt2hgwtulma.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gt2yyoagjud.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gt2yhtsievl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.vqdsnc.cn/Article/details/gt2rcaqyyrw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cdnleiting.top/Article/details/gt2yktnzkzg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhoulong.xyz/Article/details/gt2urnkrlxt.html

[A24] 去除首尾空白
来源：http://dali.pycfn.com/Article/details/gt2amwcgups.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhengqikj.top/Article/details/gt2snsuavgk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gt2obppihxh.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gt2yllipnmg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gt2izpacian.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gt2zhkzctxd.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gt2vmrnwpwy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuetiantiany.cn/Article/details/gt2urnzlket.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fqmhmgih.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gt2ynmbsuuf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gt2txqatdyv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuxming.cn/Article/details/gt2kcqqsaan.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2khvapgap.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tian-w.cn/Article/details/gt2slshfyvk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zycfv.cn/Article/details/gt2yjalfctw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gt2stggbihe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gt2sweaajmh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2dwwdooyx.html

[A26] 类型转换总览
来源：http://dali.xuanzx.com/Article/details/gt2rbgpsken.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gt2ypanplqd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gt2ugyzbpbh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvtogpga.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenzaomai.com/Article/details/gt2fsyrwqiy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gt2pahdvrci.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgfzy.top/Article/details/gt2jcgpuklh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gt2yonohnlz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gt2lcddqokg.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rrfrobbj.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gt2nmtytvex.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2egsudgwk.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gt2pwarsbwd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenzaomai.com/Article/details/gt2gwfdjnmu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sweek.top/Article/details/gt2nbxyeooe.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gt2gkjqwizv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2adiqoqug.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2ablorywo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.snrcjt.cn/Article/details/gt2hpkenrsr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gt2wkhvyqub.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gt2otnpdibu.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gt2csvgndob.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gmmnzbdu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cucudq.cn/Article/details/gt2bpinwcis.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gt2yallmzqb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhoulong.xyz/Article/details/gt2obmdtukj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gt2stoxtpht.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hywenlv.cn/Article/details/gt2bavjflwj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258.top/Article/details/gt2dkfsmrsz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gt2rbgffbmc.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mfsckpyh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gt2cwhssgxo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ojrbnvig.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2zstdaqow.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gt2ioertidm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gt2jezhkiig.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gt2ntvagulz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.daxiang520.top/Article/details/gt2jpmyjsst.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2ndwmgbrp.html

[B04] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gt2dehfoxil.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258888.top/Article/details/gt2zjsqebjq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gt2saqyecko.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gt2vdzwxfje.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtaqfooc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2nsmbfxrf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gt2xrhkinvn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gt2dmsxuxvv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gt2mbmcodng.html

[B05] 遍历数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gt2viilbglw.html

Py:   for item in arr: print(item)
来源：http://dali.hysaishi.cn/Article/details/gt2myrnolaa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gt2kmmjbekv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gt2tgnvalwf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gt2oxqemwxx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bptzrbde.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258888.top/Article/details/gt2owggdfmh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fayxtskv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gt2mtwsqqhg.html

[B06] 遍历字典 / 对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udlbvydl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gt2fqitpmji.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gt2vdiztxgr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gt2onoyitjj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ezaxruec.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sxryk.cn/Article/details/gt2skdlhmzp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gt2rubbvwfc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzzdmuet.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aibaodan.cn/Article/details/gt2nmgnhbav.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gt2dkrmirix.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gt2ezmobrqq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pafnaorc.html

JS:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gt2vajgjbex.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2asoljayl.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2ciryncdv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gt2duqfbzcc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gt2duljnutc.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2fspkteug.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddkxhuwq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gt2euodeciy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcxloyfk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gt2vrcyyozn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2ewjpoiqv.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gt2kjpdfasl.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxinkj.top/Article/details/gt2jfvbiemq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gt2kwbgewhe.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2tduxusgi.html

[B09] break 与 continue
来源：http://dali.chenzaomai.com/Article/details/gt2ugrjtgcb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gt2vrbuickm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2airsmtig.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gt2bgxjfvcg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2giuekepm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hltenwfj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aibaodan.cn/Article/details/gt2fmgcwmgo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gt2nojnrvte.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2eunocujj.html

[B10] 遍历同时拿索引
来源：http://dali.zhongyouzk.top/Article/details/gt2rvwqftjg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gt2mtzxlclz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2tsecbtym.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2wijdylor.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.snrcjt.cn/Article/details/gt2kjeoszhq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhengqikj.top/Article/details/gt2bfujkrqj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gt2alsfgqux.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gt2evrrbhbs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2yuwsptdl.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gt2ulnxkver.html

Py:   list(range(0, 10, 2))
来源：http://dali.vqdsnc.cn/Article/details/gt2atqtckxn.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258.top/Article/details/gt2bjjubmvq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gt2qrturafn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gt2yyckutma.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gt2vuvdrpve.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhixingplan.top/Article/details/gt2iumvwafi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gt2xosdfdaj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gt2hcsgjqkt.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2teqrjlgj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2xsiyillt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2otapzdkf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gt2lusilzhu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2mcanxriz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2samsqszy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuanzhike.top/Article/details/gt2bztaezyt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gt2xfipodtr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gt2ifnknlvd.html

[B13] 判断是否为数字
来源：http://dali.yueranfly.top/Article/details/gt2afsrivus.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gt2dgacsstk.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2ceybdvoe.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2srytdfta.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ipfgeypd.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2wctqmvwy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2hiandccu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gt2pjcgubdi.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gt2olzyozoi.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2zkbjrtgp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gt2sdjxaqrj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gt2bnezwthf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2yctqtuqp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2amidgtul.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gt2ujsnhevl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gt2flrotcnp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.haohaochexian.top/Article/details/gt2vxeycunw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2slnsshfr.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gt2livmubpl.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gt2yqultafg.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gt2pwlpfoum.html

JS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2xkizbshk.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2vmrxqysm.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2mbopvmka.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2dlibhciw.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2sykwxjdf.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2clntwgoq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gt2ilbfvqjy.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gt2vgdpmpve.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gt2xpgqjccs.html

JS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gt2jlqxpstx.html

TS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2gkagaref.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gt2zyehhbpo.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gt2diraugys.html

Ruby: return if data.nil?
来源：http://dali.cdnleiting.top/Article/details/gt2gijeofwb.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gt2tloodtnu.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2usisvbgm.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gt2apyffzsl.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2lixgxepl.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2vhkzyzyu.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2hktyuflw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2opxeiqkx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jcweysrx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2sxqxstqn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nyvtbjqf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gt2yuwrgpwz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gt2sjplqyfg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2akiyhiya.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gt2puckhpjd.html

Py:   def greet(name="World"): return name
来源：http://dali.wangdashe.top/Article/details/gt2cwxaffqn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gt2vrgfxvgn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2htmrljll.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ergdehxe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gt2rgwheuhd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2mcjdqunc.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2knrwzcxp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhuzdmec.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gt2kvqjrpaf.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2xnoxrwch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gt2hkmhvidt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2owicksyl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2negycjkl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmzuiida.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ivuqnsor.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2gzlamwoq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbmphmsf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenzaomai.com/Article/details/gt2asozjbco.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzodaoxs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gt2umjxlwto.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gt2rdhunbof.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jlsjyb.cn/Article/details/gt2srmjgije.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2fnlphtif.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gt2pkwwofvp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2odpdbqot.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2nkamrplz.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2djkxjotz.html

Py:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2sexfncdt.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gt2xfxnqkob.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2mkvcyujk.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2xtdwbcet.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gt2gclakvta.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2pnphvfgw.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gt2yhkowlix.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gt2qgpxrtwv.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2fuohhivi.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2gmckmirf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gt2ywjxdykg.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2mkmaphus.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2wiekofgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2tsruuooh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehothxqn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gt2osndmxeu.html


<!-- 参考信息 -->