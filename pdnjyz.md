代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtynsdbkwv.html

C#:   var value = data ?? "默认值";
来源：http://dali.dashuyun.cn/Article/details/gtryypgclg.html

[A16] 真假值判断规则
来源：http://dali.jyoumei.cn/Article/details/gtfawhsudg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gthxwoaxmq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.pycfn.com/Article/details/gtipdxkhmg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xylfe.cn/Article/details/gtkfvxyteb.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtgdoewzfk.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtlyoqpfcy.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.316326.xyz/Article/details/gtuooabscy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shzxlz.cn/Article/details/gtwoftwvop.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cashguo.top/Article/details/gtqhvalroh.html

[A17] 位运算
来源：http://dali.kuanghao11.cn/Article/details/gtccxxgfju.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtlwvtlmgt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gzhubu.top/Article/details/gtvpozfjqb.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtmawnorwt.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtfqnrhgfm.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gttmqjupmw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtbgbxdija.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gthfnvhqif.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtpsdtwklw.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ydzc1.top/Article/details/gtnxfffzzw.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gthyxrxudx.html

PHP:  ord("A"); chr(65)
来源：http://dali.yvedp.cn/Article/details/gtnrufknqg.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.havefunace.top/Article/details/gtsqgyptkb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gthbzmxvle.html

Java: (int) 'A'; (char) 65
来源：http://dali.wangdashe.top/Article/details/gtlptjakzr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gotoacloud.top/Article/details/gtitgwdcnt.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gtalezfcmi.html

C#:   (int)'A'; (char)65
来源：http://dali.hongshengwenyu.top/Article/details/gtmsdxhqsy.html

[A19] 交换两个变量
来源：http://dali.hongshengwenyu.top/Article/details/gtirtdqfzm.html

Py:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgwqxmzs.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.chenjidiqi.icu/Article/details/gtglzkpily.html

JS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gtzvgktvyf.html

TS:   [a, b] = [b, a];
来源：http://dali.jianghu66.top/Article/details/gtokdosbuj.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhiwuduotai.top/Article/details/gtsslbbpkk.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtbmwqznkq.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtgvjjckfg.html

C#:   (a, b) = (b, a);
来源：http://dali.svipenyu.cn/Article/details/gtsqtganoa.html

[A20] 读取标准输入
来源：http://dali.sweek.top/Article/details/gtopwabyxt.html

Py:   name = input("请输入：")
来源：http://dali.feifeiyinyue.top/Article/details/gtozmzwbra.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gtrbhrdrsj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gteghoqfvn.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gtwjazzebt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ybcxt.top/Article/details/gtgjcidbwj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtmzdrgnwx.html

Ruby: gets.chomp
来源：http://dali.gogol.net.cn/Article/details/gtpvsthast.html

C#:   Console.ReadLine();
来源：http://dali.bjfxy.top/Article/details/gtqeooqtmc.html

[A21] 保留指定小数位输出
来源：http://dali.kuanghao11.cn/Article/details/gtbuozgnsz.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hysaishi.cn/Article/details/gtmkgxanqj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.mhx1999.top/Article/details/gtyvamskkr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtfkkzmfap.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtkxlnimbd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtuxajhrgl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtozwmfpzu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gtwufmwyfd.html

C#:   3.14159.ToString("F2")
来源：http://dali.yj20258888.top/Article/details/gtyjvzpjjc.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtexzjkqif.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gtpxakvbfl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhijiandao.cn/Article/details/gtavkraryq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.pycfn.com/Article/details/gtzvuypjds.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtpmdmycpa.html

Java: s.length()
来源：http://dali.yuxming.cn/Article/details/gtpudbjrmc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gtpuzocwij.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gtxtupqkea.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtxohlazmd.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtzjusewcb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gogol.net.cn/Article/details/gtamkurzav.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hfpthk.cn/Article/details/gtglymbvch.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtebgykzyf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxuanxn.top/Article/details/gtwwewofoy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtegixjflh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhixingplan.top/Article/details/gtaooymkbd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zycfv.cn/Article/details/gteddftxjv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gtmenowwtx.html

[A24] 去除首尾空白
来源：http://dali.xuanzx.com/Article/details/gtobecyhwy.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgfzy.top/Article/details/gtpapvhgkn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqjranme.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtuqfhkfqd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gtnvofrwdj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhoulong.xyz/Article/details/gtisbczubx.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtbwwhhbaz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aibaodan.cn/Article/details/gtxjbbazik.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtrmmeilnk.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtvodsggfz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shzxlz.cn/Article/details/gtowbngotj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtyymfejyc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtvgifahtq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gtwucnaxuk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nwbrower.top/Article/details/gtsgyfghcc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtahomabkt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenlongwang.top/Article/details/gtthmkxegv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtngrqyfwj.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gtihcxgdre.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.redwolf501.top/Article/details/gtqrbrbtgw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtxiwkfsor.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtcrdymuls.html

TS:   Number() String() Boolean() x as number
来源：http://dali.meibo888.top/Article/details/gteevcecry.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258.top/Article/details/gtovlfhnne.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gtjxgolunz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gtswlhrvfy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtkmelzexy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsntujsfu.html

B. 流程控制
来源：http://dali.gogol.net.cn/Article/details/gtgirxmlnv.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtsmijeprx.html

[B01] 条件判断 if / else
来源：http://dali.tianlin.xyz/Article/details/gtmqnjtslb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xziqi.cn/Article/details/gtgkcyjrja.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtbwczejyb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gtxllxohkp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtouhxobak.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtzbrtxdpp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gtdfypviqp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtryurcxcg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtuuhxynzl.html

[B02] 多分支 else if / elif
来源：http://dali.xuetiantiany.cn/Article/details/gtkcmqsrga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zycfv.cn/Article/details/gtyyfetatx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtghdoclhn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtjujvuqvc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtdperbfsy.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtjernszzz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daxiang520.top/Article/details/gtbpbftljd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shuidangran.top/Article/details/gttkdvrtna.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtbxaoyjyz.html

[B03] switch / match / case
来源：http://dali.daxiang520.top/Article/details/gtcgepawvo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gtbfaewsrt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gttqbpssnd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtdkwwnbei.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gthjjwgljn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtxpvcmhxs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gteijjextp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gotoacloud.top/Article/details/gtpoycxhim.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtmkqcxgpk.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtmyfftkbs.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmoteuv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daxiang520.top/Article/details/gtyfiwlbqq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtalrmjamm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fzhhl.top/Article/details/gtucabteno.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xziqi.cn/Article/details/gtlpzavfsv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigfzy.top/Article/details/gtrjtihlfb.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gttantxnzh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtfmufsyvr.html

[B05] 遍历数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gtheyreomy.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtkgpikojf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gteiuspwft.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtahuuiqxv.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtraqsrzka.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangdashe.top/Article/details/gtxtvwesal.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.birdmap.top/Article/details/gtpxtnblrp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shzxlz.cn/Article/details/gtoartpqgl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gteworpbuh.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtjyggbahu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gtuktldhba.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtzoptkbfq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtcambbvsg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gtohdmclps.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtdznoawmv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtuzfvtbtq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtvzofizch.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gtyanvqgap.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtclkrmecr.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgplptdzp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtxpgggjru.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtylnodkfo.html

TS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gttmdylbyh.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtcukqjwbn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pycfn.com/Article/details/gtakbdtiew.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tianlin.xyz/Article/details/gtihclondq.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gturvyovkn.html

[B08] do-while（至少执行一次）
来源：http://dali.fzhhl.top/Article/details/gterdrxige.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtjhpbzuww.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gteiaomlzo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gtzadmoppx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtffsvvanm.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtltuqfbjn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtppgjctvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gtjnyiwzhq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtrisrlukt.html

[B09] break 与 continue
来源：http://dali.jinqigufen.top/Article/details/gtflenispu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jiagoushi.top/Article/details/gtybxdzjws.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtofzmzaqn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtatscixnk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtmfeujybf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtfnwjuupi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtnbcefuwj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.meibo888.top/Article/details/gtnmbvtjgr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtwxquzozw.html

[B10] 遍历同时拿索引
来源：http://dali.shuidangran.top/Article/details/gtidkwfkwj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtienmzria.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtvmvgatpt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtzretkwzm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtytcfspjm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jiagoushi.top/Article/details/gtssqnfsxq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtxkkkvzek.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtgjomnjgg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtgkvmabmn.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtpvnefafh.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gtrupqpvbk.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtsyhwkqod.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtahsrmrch.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtzdcdvigl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.fzhhl.top/Article/details/gtwrnejire.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtiotiotuq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gttkfrjwsj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtcoxmfdgm.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gtqdgvkhfi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gthdljnexc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gtwuwlucub.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtskhnvnzd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gtiytcnqkw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtghnvfedk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gttsihtrrx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtuambqkzp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtzsudvfqk.html

[B13] 判断是否为数字
来源：http://dali.jinqigufen.top/Article/details/gtuntaqvel.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtpwpfywyk.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtgidpvjru.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtuuoymhml.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gteqcewsph.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtwwcngumz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtianonxdd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtiolqswmd.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtnfpkvafx.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtvavgvexa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtrcwsirrg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtczkzgpeb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gttkcpzdpo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbchrllxb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtsezwdwli.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gteuqbuxat.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgygtwweb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqnflwub.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtblexqvam.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooxsdaaj.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrvogudus.html

JS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtvylcmezz.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtzlmkhqbb.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gterrbswoo.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfqrqodd.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtapaduape.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtyaxniebw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtviiklwrl.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtlaixrvzv.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtixuxdxxg.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtzpfgaxcj.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtdbgtfwmi.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtbzfaeqii.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gthwcrykee.html

Ruby: return if data.nil?
来源：http://dali.guowangkeji.top/Article/details/gtfretvaoa.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtdmddogap.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsttppnt.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtmvnvljwg.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtalhplmlm.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtsybdkhcy.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtrrkbepus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqauokpwh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtivqnpavq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtqayebxiy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtgtaveyad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyyqkuqlk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtlvmgybec.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtkotytzaz.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtdslydfxp.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtnijhwfyz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtvqfpkfdq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtyupgkvjz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtaujjqauz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gttmmonrph.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtwuokswut.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtvbmmumpn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtvkeyfxnz.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtnhaptshc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtmtsaxxtr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtysjootmn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwvuzpyo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtsaeuphnx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtsqpmvvbq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtneehjicc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtvjeloymi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtnisrdzmf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.svipenyu.cn/Article/details/gtndvwvjqv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gtufnruian.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiszxdxdb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtwxuobfkz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtesenzjtn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuanzhike.top/Article/details/gtrjxkbjbu.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmhmnlpfm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtoczhctbc.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtfmievzkk.html

[C05] 返回多个值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglwssedf.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtrwmndtkc.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijpsvosx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtvyarlnnq.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtflfbcldt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtanqyqvmv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtrsmcqiio.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtqgkcvfkn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtvjzvgmws.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtqximuqsn.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gtvofpihau.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gtwigawauy.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxccwixyu.html


<!-- 参考信息 -->