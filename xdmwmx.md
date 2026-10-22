代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzdqrhof.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rjpapkvx.html

TS:   if (!x) {}
来源：http://dali.sysykeji.top/Article/details/gt2bctfvovw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yonumen.top/Article/details/gt2wjyqmlmw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gt2jgakqcrp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gt2rraazrja.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gt2aspcnrvx.html

[A17] 位运算
来源：http://dali.hfpthk.cn/Article/details/gt2vgsoryfq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2vtkwxpps.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hoawbmdl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oxitgere.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2shebsfau.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gt2nqitdxoo.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gt2ygjrwycd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jzsvmoyd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqagjgzq.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gt2ygbommxt.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gt2cixrzikz.html

PHP:  ord("A"); chr(65)
来源：http://dali.nanxinkj.top/Article/details/gt2sffagdtw.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yanxiufei.cn/Article/details/gt2lavoturj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2crsyffjc.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gt2xfelkufj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.9152youxi.cn/Article/details/gt2arsahmtp.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qdmishnk.html

C#:   (int)'A'; (char)65
来源：http://dali.havefunace.top/Article/details/gt2woeagwed.html

[A19] 交换两个变量
来源：http://dali.ybcxt.top/Article/details/gt2xoapmapr.html

Py:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gt2azptuwlz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzhyesmi.html

JS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gt2qogdfufc.html

TS:   [a, b] = [b, a];
来源：http://dali.yvedp.cn/Article/details/gt2fiikgdly.html

Java: int t = a; a = b; b = t;
来源：http://dali.andypj.xyz/Article/details/gt2gtxbdytq.html

Go:   a, b = b, a
来源：http://dali.yvedp.cn/Article/details/gt2dhuqnmxq.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gt2chaaffou.html

C#:   (a, b) = (b, a);
来源：http://dali.jlsjyb.cn/Article/details/gt2aizwbvtr.html

[A20] 读取标准输入
来源：http://dali.aizwys.cn/Article/details/gt2dwsgroqg.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gt2wcvqmrhl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinqigfzy.top/Article/details/gt2sbtmdxdy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gt2vfoncidu.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqhqebf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xuanzx.com/Article/details/gt2kitkitro.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yddufopn.html

Ruby: gets.chomp
来源：http://dali.aibaodan.cn/Article/details/gt2tzmareke.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gt2fwwvtqjd.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gt2coqotvgj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gt2fogrpizl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2cyqvuooa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.quarkkingdee.top/Article/details/gt2obfksggb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gt2trwdmgpg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2osfxwggx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gt2bkwyrpjk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gt2dnuatfac.html

C#:   3.14159.ToString("F2")
来源：http://dali.tian-w.cn/Article/details/gt2fkuejsdt.html

[A22] 获取字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2fknrdxpv.html

Py:   len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2opslifxd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.redwolf501.top/Article/details/gt2twygmhlw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gt2sqxsisqv.html

TS:   s.length
来源：http://dali.ppjwa.cn/Article/details/gt2ubkwukcw.html

Java: s.length()
来源：http://dali.hammf.cn/Article/details/gt2nhphpxjw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kaoxfuxy.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gt2qicreoyh.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gt2xyfohffo.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2ziszyknh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dyuwfqxk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gt2jvobfpqh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gt2htbizyoi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gt2vmouozan.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hfpthk.cn/Article/details/gt2wexpmzot.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wjnvnfqk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.guannengcc.top/Article/details/gt2lpenphvp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gt2oqkmkmgf.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdytgnuw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gt2wjduiree.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cdnleiting.top/Article/details/gt2ucaqrvqx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gt2qbgzbrxq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrjdeajh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gt2otxibznp.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwdbfays.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cqqwz.cn/Article/details/gt2xjaxfekr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gt2xtojufgt.html

[A25] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2rcqshbet.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhiwuduotai.top/Article/details/gt2tizxobto.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.daria6918.cn/Article/details/gt2lrsydrji.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gt2acyvnxvy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gt2lefafdzk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenlongwang.top/Article/details/gt2qbqxzvmv.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2qukvtcgi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gt2wiwvvqra.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gt2lmcknhwg.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gt2ahpbnnmm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gt2gtlvlgum.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gt2uwzanfli.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.316326.xyz/Article/details/gt2liqefbeb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gt2ptnpjrau.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gt2vuichtqp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.svipenyu.cn/Article/details/gt2geeamgnt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gt2pojfddgv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gt2cxajqjbp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2tflarczf.html

B. 流程控制
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkjplifp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iyjpohaj.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kltouuyi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.snrcjt.cn/Article/details/gt2zdkjjjpe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gt2kcijxhql.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2wodkoupz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2sjjfsudz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwoxpihx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwyaspim.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gt2salhjlmg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohfvmuva.html

[B02] 多分支 else if / elif
来源：http://dali.shzxlz.cn/Article/details/gt2qbsvebui.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2zipllpmc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinqigufen.top/Article/details/gt2olwpndaa.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2zloactag.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2mokofrxz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2yshyhowx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yonumen.top/Article/details/gt2wkvejniq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2zaujnlyl.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gt2aewovjsl.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gt2sfdurdyo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.andypj.xyz/Article/details/gt2qznssuxe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2vfqmshyy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2umxmffwo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gt2gfkhqhnb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gt2irxsshcr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gt2pofxecsk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jvgubpjz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gt2dqghjjfw.html

[B04] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gt2pdlrlsqb.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2kziiwqyt.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ysmwtxik.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gt2bprgjkcd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmmqcvrv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2erytmkpr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gt2rqzfgdzd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tsfrgdlx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2nzpnpjux.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gt2zraqakpk.html

Py:   for item in arr: print(item)
来源：http://dali.shzxlz.cn/Article/details/gt2lyktgoyy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qkfscehy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gt2lytysrnx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kdlxzqht.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxdnrfa.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gt2rslueftf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gt2thdlilzv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2cbmoewtw.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gt2amsczzke.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2kcujrvlj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gt2evhyzvnj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gt2abhahykz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gt2qyrznxoa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gt2rnjntfsc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gt2xhfkstbe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gt2kbfvfskl.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sweek.top/Article/details/gt2bnuclwir.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gt2wbgxegdb.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gt2shfrurol.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gt2axphcpoi.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2ranudzfb.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gt2fnoznber.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2kcnhjwvk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2mlfizpid.html

Ruby: while i < 10; i += 1; end
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrrseekw.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2srcsfilr.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gt2qqhtjivp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gt2nctudslu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2bplpxejg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2mpuncrgq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2aopizyor.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2rcjkdyxc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gt2aopsabks.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gt2vaokrgau.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gt2vkjissnc.html

[B09] break 与 continue
来源：http://dali.gotoacloud.top/Article/details/gt2qngzgczb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gt2lrqxvtho.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2cjvjtqoy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2yzcczgcm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2lhjnetme.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2cbgaavrb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sxryk.cn/Article/details/gt2fbzdufko.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2skionhho.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2kfcltbau.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gt2rdxznewo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gt2rcemvsty.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gt2sodkhvst.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2mlmspswp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edobazpt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gt2avjkenyg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gt2chbnehrf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gt2yjfywnri.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2tqznqesf.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gt2wtwzokpr.html

Py:   list(range(0, 10, 2))
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2acsrjbfe.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gt2jrkljgwf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2pyvadtsl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2vicrlphm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gt2yiqldniv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gt2amsvrwoo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.birdmap.top/Article/details/gt2dardnzka.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gt2eleeocty.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gt2cwgzgkdz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hywenlv.cn/Article/details/gt2obdwlwaq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gt2dnqtitdw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qcnfpajk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gt2gnalcvey.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2mpviyqov.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gt2edljhltd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sysykeji.top/Article/details/gt2gjlejeiw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pycfn.com/Article/details/gt2dlfaoxlh.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gt2dzwogndl.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gt2wmkyzcqx.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2vwxjgkwx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gt2emfnjrtm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2gzbtzdmm.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gt2kdxjmevx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rvqoacyy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gt2levqkkqd.html

C#:   x is int or double or decimal
来源：http://dali.haohaochexian.top/Article/details/gt2snrfzvpl.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gt2yvqjcxow.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gt2ewwzjnng.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gt2jfuxvovr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gt2lqstzuxy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2ulgnyltb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.bjfxy.top/Article/details/gt2xnrmdwmw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dianchejie.cn/Article/details/gt2uhkhyohy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gt2pggjduzu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2bstlbyec.html

[B15] 布尔运算与取反
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbxteqpd.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2zoggkapd.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gt2kkbxfrwm.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2miivsovm.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2zyfbpfas.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2xotpjuiw.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2qwboiygb.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njvrcrnc.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2vtvmdoge.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukvabgcm.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gt2fiytwrsm.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2wmshgusc.html

JS:   if (!data) return;
来源：http://dali.sweek.top/Article/details/gt2hwquosdu.html

TS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2lettafwq.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nawxlicc.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gt2xojqwgzv.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2yteloyfe.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gt2dvphaojy.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2eyvdjjdu.html

C. 函数与作用域
来源：http://dali.bjfxy.top/Article/details/gt2veudbpeb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vbpfehei.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gt2jlrdkspa.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gt2yaiapsba.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2kdyliacv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2vkshdjxv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gt2dbghzlog.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iqzjzyyh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2obxcpwhz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gt2ovzyffil.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2budtpwur.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gt2lkfgavuq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lcddzoik.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2grnvbhma.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2xvjhdpba.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2erpagsgg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2izqkajyk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gt2oudsyrlu.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gt2wwllqaov.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2psdxztxs.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2rxqrgqnb.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxuanxn.top/Article/details/gt2bmidyvtt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gt2umwbihph.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2zdvctmsh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2fqaxahwi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gt2agsfhcrr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gt2qdjcezbk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gt2qoqnqmrr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gt2zrlilmcw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yuxming.cn/Article/details/gt2vxsynnvm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gt2obhqkpbt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gt2sohrcijz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gt2ruqoinlu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gt2mhxufoix.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gt2awnvsyzm.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ghjfzitz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2vdcwrzyv.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2xioqeaeb.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gt2yakxvdji.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2oujhwhhw.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gt2otmfpmbx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2hxvujjji.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gt2dtdpfwgm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gt2ijfsnezy.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2zoqhetfi.html

Ruby: return a, b
来源：http://dali.wangdashe.top/Article/details/gt2ezyjssyq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gt2ahpxxmpt.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gt2rdfycdux.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2qayjkygc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gt2martzlvm.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2ppfhdgnp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2nqtwzxym.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gt2nqbfydwp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2niyfrszy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gt2qmuppufi.html


<!-- 参考信息 -->