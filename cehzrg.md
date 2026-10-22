代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.shuidangran.top/Article/details/gtofnnvlcg.html

TS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gterpchhwx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.havefunace.top/Article/details/gtctvueuhn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guowangkeji.top/Article/details/gtscwrsrud.html

Ruby: value = data || "默认值"
来源：http://dali.cashguo.top/Article/details/gttrrvofxl.html

C#:   var value = data ?? "默认值";
来源：http://dali.iojbl.cn/Article/details/gtappadjzs.html

[A16] 真假值判断规则
来源：http://dali.chenjidiqi.icu/Article/details/gtpdicosfy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aizwys.cn/Article/details/gtcktuoblj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fengsongda.top/Article/details/gtcwadxrzp.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtymsuvmfq.html

TS:   if (!x) {}
来源：http://dali.aibaodan.cn/Article/details/gtpplnhvxs.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gtrolxarkb.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.chenlongwang.top/Article/details/gthrvmrohu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gaohongyu789.top/Article/details/gtxqasykvz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.c1oappe.top/Article/details/gtnsoiowox.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gtwsomctbs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtcknciltu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gtsotonzek.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtpzcyasqy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenjidiqi.icu/Article/details/gttvxgoxse.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtptqbrktk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxhnfthd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gtwytcjnty.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.0kj1m.cn/Article/details/gtwbjuykwx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yangfankeji.com/Article/details/gtqjxzkfij.html

Py:   ord("A"); chr(65)
来源：http://dali.zhoulong.xyz/Article/details/gtnqyesxse.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtgxitybtf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtqhovhtek.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtrepmsllh.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenlongwang.top/Article/details/gtushgqaed.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xinyue.icu/Article/details/gtijhdctlr.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndirrdxo.html

C#:   (int)'A'; (char)65
来源：http://dali.yueranfly.top/Article/details/gtschbdupz.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gtgvrczvfv.html

Py:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gtfqdjlanu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtmnctbstk.html

JS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtnjkfesjo.html

TS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gtlknzkwdd.html

Java: int t = a; a = b; b = t;
来源：http://dali.nanxinkj.top/Article/details/gtlygqsrun.html

Go:   a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtgztundhk.html

Ruby: a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gthlrataho.html

C#:   (a, b) = (b, a);
来源：http://dali.zycfv.cn/Article/details/gtamtbgyap.html

[A20] 读取标准输入
来源：http://dali.zhengqikj.top/Article/details/gttyvkqifr.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gtheyyaaxk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gtvcwcmjzf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.birdmap.top/Article/details/gtdnwldswc.html

TS:   // Node.js：readline 模块
来源：http://dali.xinyue.icu/Article/details/gtohbazwqc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbysuofoi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ppjwa.cn/Article/details/gthfoubnrm.html

Ruby: gets.chomp
来源：http://dali.yueranfly.top/Article/details/gtpfwfeynn.html

C#:   Console.ReadLine();
来源：http://dali.hfpthk.cn/Article/details/gtzryqxikp.html

[A21] 保留指定小数位输出
来源：http://dali.c1oappe.top/Article/details/gthtdudgfm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.birdmap.top/Article/details/gtikljvrrd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtwbnigxwm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fengsongda.top/Article/details/gtytpdcdri.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtqhicalfh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gttcgeplab.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtcrwyyzgp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtlpqavsni.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtgtooiqbs.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtavgjohee.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gtnikvgges.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gtcpttbopd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gtutodeoxw.html

TS:   s.length
来源：http://dali.fengsongda.top/Article/details/gtzpnoojdw.html

Java: s.length()
来源：http://dali.andypj.xyz/Article/details/gtxfbnnyfi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gteyvbwyvc.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtufdbowoi.html

C#:   s.Length
来源：http://dali.svipenyu.cn/Article/details/gtdkqkqujy.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtzjolpzmy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gtbatazprv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jiagoushi.top/Article/details/gtsglrddvi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtjkiijfbf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtyzorutal.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtfwnvcfmo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtirsxogca.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtvmqgipky.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.havefunace.top/Article/details/gtvirtmgbx.html

[A24] 去除首尾空白
来源：http://dali.cqqwz.cn/Article/details/gtafxhvlls.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.havefunace.top/Article/details/gtebxgynux.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtjdckysao.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtjmnmhugz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtwznyduio.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gtfspkwqzq.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtlkxlgrfc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.havefunace.top/Article/details/gtmhihoowh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gttqpnpnvv.html

[A25] 字符串比较
来源：http://dali.quarkkingdee.top/Article/details/gtvzmvescz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gtuvnjsuer.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtycfiwxkr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwedhsjbe.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtppdzokyk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gthslxxvrk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtcxtvbtpu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangdashe.top/Article/details/gtccgehetc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gttzwhgxgw.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gtfkmlgmfo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj202588.top/Article/details/gtgulxbjnn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sufxvd.cn/Article/details/gteaodfnlo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gtjznleenv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gtwwhclyjf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxbtacsc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gtzsrjzper.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtxipkaoeo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yangfankeji.com/Article/details/gtadcezttq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxhsomai.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gtjbmfsvge.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtquznquoo.html

[B01] 条件判断 if / else
来源：http://dali.jinqigufen.top/Article/details/gtgwlzpwuk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.dashuyun.cn/Article/details/gtglmymrsa.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gtoeaopodc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gtsxjdqntd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtkufarvxv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.9152youxi.cn/Article/details/gtccppqynr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gtwrnujdrn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gaohongyu789.top/Article/details/gtzwslgppf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtzghizzww.html

[B02] 多分支 else if / elif
来源：http://dali.yonumen.top/Article/details/gtflsijoxv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jlsjyb.cn/Article/details/gtnprwzqfl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gtmzzjkppb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtpnmgpcqy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gttqdfonml.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtgehbplxh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtuwkkjlef.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtkyxkdcmd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtwmzwdhzx.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtmiihhtfg.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtckchxils.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtmshppewm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtaxxcteiu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvahefjdj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtwptyrnna.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pycfn.com/Article/details/gtazxpxuzd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtouannfei.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtvburzfrg.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gttofxskvm.html

Py:   for i in range(10): print(i)
来源：http://dali.0kj1m.cn/Article/details/gtwpupetyp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daxiang520.top/Article/details/gteatxaacr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkjuezuns.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtzwusyorc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsgtqbscn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.meibo888.top/Article/details/gtwrgqwjtu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj202588.top/Article/details/gtnnwyocfj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtmnwdcugs.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtzjwpuwoi.html

Py:   for item in arr: print(item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsynegkd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtmsjnqxfx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtmbuozlsu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gthwxtcvrt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtmxqivujf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtpjkvwdai.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gtjquvztih.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dianchejie.cn/Article/details/gtdialcowe.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gtxreuqizk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sufxvd.cn/Article/details/gtxizusjnf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gtpjqlmonl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtnwlntlej.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gtmqqguwhy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gtqahxakhl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gtcxfgdygn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jyoumei.cn/Article/details/gtldovtkzg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hysaishi.cn/Article/details/gtdxkfifkt.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtjpwewnjj.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gtdutoggwo.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtekcvumpw.html

JS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtrlkojvzj.html

TS:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gtpltzvext.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtertkfadk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.iojbl.cn/Article/details/gtdcjpwmje.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtijauejyo.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtmqwsudzj.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtuxxqmbri.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gtsxubfnmx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtprcrdofb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtcsoqglxz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtasqratge.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtazzaoaed.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtyggqqvrz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtglbktngh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtlxgwzukc.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtefeuobdh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xinyue.icu/Article/details/gtyfikvtei.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtktejwnwi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtxlutneit.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovzitddt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvrqsomn.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gtqywkasch.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daxiang520.top/Article/details/gtcmdkeash.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmnplsoam.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtsjxhxlfz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gturdeiqkt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xinyue.icu/Article/details/gtinjsdwcz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gtacvksogx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtbdufxxah.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsjdnnsw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtkhpkxkrx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gttthqwoin.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtymlujhnn.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gtgrieargq.html

Py:   list(range(0, 10, 2))
来源：http://dali.yueranfly.top/Article/details/gtdmcipuyx.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtkavwiqrr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtksbqbiaa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gtcfvaamsz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtramgjqwd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtxipbbdfe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtttdcjwiq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtoplrpacw.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtugcfncof.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtdqyayrgb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtrfjpezmg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtoyjsxwww.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtzmggwpfj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtxmyrgctn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtzptgzugk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtlluncfzd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gtarnwsvid.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtpdydjnhq.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtgzfmgbbs.html

PHP:  is_numeric($x)
来源：http://dali.yuanzhike.top/Article/details/gtvjiewyrf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.haohaochexian.top/Article/details/gtwjyhxyem.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtcnsjqepo.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtiqcnmayf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtcttxmmol.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gotoacloud.top/Article/details/gtqmqysdbb.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtcuutqqtp.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtfsjvajfe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gotoacloud.top/Article/details/gtpivguzis.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtwrsmvvve.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtgybkafwx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gthutcfoze.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtduqgngoq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzzmxita.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sxryk.cn/Article/details/gtrkouzoqf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ybcxt.top/Article/details/gtdoxosccj.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkmagmor.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtyudvivyy.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtrnqnjybf.html

JS:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtffcpuzwa.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtiiudzvqm.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtmilbdmmn.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtthkjeohp.html

Ruby: a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtamknzfss.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtbnroduoe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258888.top/Article/details/gtxrzldvtt.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gthqsvumdt.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gthhrsuimg.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtwbkicsoc.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtmuealeux.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtnaslbxia.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtyajhnnix.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtznkcrecs.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtvahacycx.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnyullkbb.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtqbpxkerx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmafdsibm.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtzisvsyft.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtiobdlrws.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgxzopjsx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmffqkoyz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsreunhet.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtyulszppz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtwtuflruh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hywenlv.cn/Article/details/gtzfpdfvor.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtrsfehtcg.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiawuatcw.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtqptbrcti.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gtrfybhuct.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtwrnunqgf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtzyoxbsdp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtzilwetxx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hywenlv.cn/Article/details/gtjwfunzew.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtryvovyly.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtyuhwvuhm.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtusjbasqc.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtxkgjuozt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtooinfmeo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtibowlzbw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtjkndwpis.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtydqzmtvk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtsmwbgtbr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtzwduidfn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtxwjzxmpp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gtfxcmzzeo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtgsjkrbwz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtewlyvmnb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtovnqjsvg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtxtoycsbq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtoqotjkms.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gtmjwaniky.html

Ruby: f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtsxticmtc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtzuafhqoj.html

[C05] 返回多个值
来源：http://dali.chenzaomai.com/Article/details/gtoubqarnz.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlvtetrn.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtscxwbvgp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiuxrdai.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtgmbdzuzz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtwzfteppz.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtephvyvqf.html

Ruby: return a, b
来源：http://dali.316326.xyz/Article/details/gtmxuzmkir.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gtuxbieoul.html


<!-- 参考信息 -->