代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.nanxuanxn.top/Article/details/gtydjebijw.html

C#:   var value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtysedlyji.html

[A16] 真假值判断规则
来源：http://dali.cqqwz.cn/Article/details/gtjxfwcrkg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yongpay.top/Article/details/gtwfqbpwng.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtiglbbnvf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.quarkkingdee.top/Article/details/gttrvroavq.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzkqhqvah.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shzxlz.cn/Article/details/gtsvuudxgo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yuxming.cn/Article/details/gtgcidxypi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gtilmkijhm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cqqwz.cn/Article/details/gtvkauyjbi.html

[A17] 位运算
来源：http://dali.cashguo.top/Article/details/gtavclpego.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtewsijsfc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtytltlibi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtnvoyheix.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtzianqglh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtfwxirbdk.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtvxxrcsgu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtlisnmtqr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqvvulrt.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jlsjyb.cn/Article/details/gtlmodmyxc.html

Py:   ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gthmvaigid.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhixingplan.top/Article/details/gtwsyqtumk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtwzekptug.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtmvnjklsf.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtykbyeybm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.kuanghao11.cn/Article/details/gtbfxbkhxq.html

Ruby: "A".ord; 65.chr
来源：http://dali.gogol.net.cn/Article/details/gtyvnjesjm.html

C#:   (int)'A'; (char)65
来源：http://dali.birdmap.top/Article/details/gtlvjdrsts.html

[A19] 交换两个变量
来源：http://dali.zhiwuduotai.top/Article/details/gtarausacf.html

Py:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gthezargcx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.redwolf501.top/Article/details/gtdzhrhnjt.html

JS:   [a, b] = [b, a];
来源：http://dali.guannengcc.top/Article/details/gtgykjzvjs.html

TS:   [a, b] = [b, a];
来源：http://dali.nanxinkj.top/Article/details/gtsbdgddmx.html

Java: int t = a; a = b; b = t;
来源：http://dali.ivvv.top/Article/details/gtwhffgrlj.html

Go:   a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagawxmrd.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtudrxaeeb.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gtoesbtmbd.html

[A20] 读取标准输入
来源：http://dali.cqqwz.cn/Article/details/gtbkxgzrtp.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gtugotgear.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.kuanghao11.cn/Article/details/gtcqdcdapa.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jyoumei.cn/Article/details/gtxgdxorln.html

TS:   // Node.js：readline 模块
来源：http://dali.chenzaomai.com/Article/details/gtuqltyqpo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cashguo.top/Article/details/gtxcjqujcb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aizwys.cn/Article/details/gtcxmkxljl.html

Ruby: gets.chomp
来源：http://dali.pengpengdd.cyou/Article/details/gtxezhwfbp.html

C#:   Console.ReadLine();
来源：http://dali.pengpengdd.cyou/Article/details/gtpssausvp.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gtoktjsmtn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gtcbdvfqga.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtwfwqmxne.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtilgchqrh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtqdqjvnen.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gthsinqsuv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtesedecql.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtbifunwgm.html

C#:   3.14159.ToString("F2")
来源：http://dali.tanke756.top/Article/details/gtkjselhjr.html

[A22] 获取字符串长度
来源：http://dali.guannengcc.top/Article/details/gtghlnguzt.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gtrembkrub.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gtggpvpmsw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.birdmap.top/Article/details/gtxtcstiej.html

TS:   s.length
来源：http://dali.yangfankeji.com/Article/details/gtturhvtil.html

Java: s.length()
来源：http://dali.jyoumei.cn/Article/details/gtnhlfaylb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cqqwz.cn/Article/details/gtvadoigrv.html

Ruby: s.length
来源：http://dali.zdqjudy.top/Article/details/gtzioahipe.html

C#:   s.Length
来源：http://dali.yj20258.top/Article/details/gtgwfdnhnn.html

[A23] 大小写转换
来源：http://dali.iojbl.cn/Article/details/gtkwusheqm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.havefunace.top/Article/details/gtwkwnqrne.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fengsongda.top/Article/details/gtjnhixwfg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtwygmuidr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gternovsxk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtuptuimlb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.guannengcc.top/Article/details/gtuxpsnsad.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtouhbrirb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gtemlikvbp.html

[A24] 去除首尾空白
来源：http://dali.redwolf501.top/Article/details/gtzcgzikdg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuxming.cn/Article/details/gtxngrmotu.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yueranfly.top/Article/details/gtpnpuiqei.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gtrpoutnzs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtcjfbmbqu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtckalusqp.html

Go:   strings.TrimSpace(s)
来源：http://dali.ydzc1.top/Article/details/gtpfardata.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xinyue.icu/Article/details/gtnmbihzii.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwuhhtvj.html

[A25] 字符串比较
来源：http://dali.sweek.top/Article/details/gtnvsssihh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnxiangtu.top/Article/details/gtapxyclsp.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.0kj1m.cn/Article/details/gtesxtqpsu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtccbnyifz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjgnmelt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtpwnapnso.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtjdxfyzxi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gtmxcxvgtr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ydzc1.top/Article/details/gtcikyukiz.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtrxdglsnj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gtbqvzjdrq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gzhubu.top/Article/details/gtbvxmzxxs.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gthwwonrwp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gtggluwyin.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtsxbyiism.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gtlulfyldn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.kuanghao11.cn/Article/details/gtugxnwuix.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gthqwhffkm.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtprigldmg.html

B. 流程控制
来源：http://dali.guowangkeji.top/Article/details/gtndiccovq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtynlemdsa.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gtfjcfnxkm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.guowangkeji.top/Article/details/gtvauwuskc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gtxezgfiyn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gttdmdrdbg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbaxoxvq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtgakacwdi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gtwxmevlly.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nanxinkj.top/Article/details/gtokkrxyfy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gttozbjwbt.html

[B02] 多分支 else if / elif
来源：http://dali.tanke756.top/Article/details/gtzmpkpgrw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gtnsudpvwm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtlyttravd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtguhsqhkv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gtykkyojnb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gttaxsezlk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shuidangran.top/Article/details/gtkqacnssg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj202588.top/Article/details/gtozzwkwme.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtcijusyjl.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtbtxsryue.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubiyaggf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtghbxvkkq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gtzkffhlfm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtkytslytu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtluuatgmb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenlongwang.top/Article/details/gtlcakbnsl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtdhockluo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtkwroybhd.html

[B04] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtsxifqtcr.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gtrwvwsyuc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258888.top/Article/details/gtjskygyjp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtxoquscbj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gthdnrfkvw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtwzpdotwc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahamnscc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gtuywbigse.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtuovaeuvk.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtzrpqlhop.html

Py:   for item in arr: print(item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqocoswfh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtnzkikrnk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gtzudbpygn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtiyllqhvn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.bjfxy.top/Article/details/gttcynnwyc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtegpqugou.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gtzygrvtli.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoxwdklbc.html

[B06] 遍历字典 / 对象
来源：http://dali.9152youxi.cn/Article/details/gttfukbtht.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtcgosncbo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtmzuehcpu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gtxonqbcxa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzsnoimpi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtyuxixsfd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gtkkbigsdy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtoxpirion.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fengsongda.top/Article/details/gtnxytqeoc.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gthtcvcwzh.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtwafckjxd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtgmktyiee.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtxbdaqlqg.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtnkdrcmeu.html

Java: while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtglznqrjy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtwkrwjpdo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.316326.xyz/Article/details/gtiyqoflug.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrhdbxse.html

[B08] do-while（至少执行一次）
来源：http://dali.aizwys.cn/Article/details/gtolubzned.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gtrrhyeoac.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ybcxt.top/Article/details/gtomrrqvqh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtrctdyyna.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtsubhajol.html

Java: do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtcqhannbq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.andypj.xyz/Article/details/gtqgxceaeo.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtnnxctsaw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtkqtqicgz.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtdniakrsd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yongpay.top/Article/details/gtsfskjnpg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmozvljef.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtdccjnujz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtcwamphyu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtmucpicmr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtuqajacwp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtuijcezxo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtzjvgkbkc.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gtvdhvhvvh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtobifhdiv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtushzdiew.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnenpllql.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtaifeezje.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gtplovubyy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtidjbmsgs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtnvqueugc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtozhzjzoy.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtbahmvnnr.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhbhwcid.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtbueqhlde.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtrfpytfha.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtqsweszsp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtvlvbxmdz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenzaomai.com/Article/details/gtphizocxz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yvedp.cn/Article/details/gtndwxgatw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtrwubetsz.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtwzylzjhq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.daxiang520.top/Article/details/gtwgbdxadb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtzalddceb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdinreqg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtradnnqiz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtdwefdqoe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmhybneu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtktrchias.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuanzhike.top/Article/details/gtlfsrrdnf.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtyvfvlrib.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gtpoaqthhq.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtbkjsedcz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtrzstxaxu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfjubfgy.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gtguriekrr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtapkjwmue.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gteuaucnfa.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gtafncbwvn.html

[B14] 判断值是否在集合内
来源：http://dali.hfpthk.cn/Article/details/gtlahkkyjt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtvijjdvtu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtmyxipqtx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtdldoyrjx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtgobdaile.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.smart0.xyz/Article/details/gtkospjvqq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gticivjkbm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtbhdbibsz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtzultjrey.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtkidbps.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtqwjoetpi.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtxmeqmgrz.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtcdholyvg.html

TS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtuncsgofr.html

Java: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcedskdin.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtclnvilpp.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtutyghtgq.html

C#:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtcaxlwdow.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zdqjudy.top/Article/details/gtfbnpkwnz.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtniznnvby.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtbusfcymo.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtdovyzgyo.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtdeexvisb.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtpbpjjdxg.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtcspnrpyc.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtwyworybh.html

C#:   if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtqsziatvf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgydmqniu.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtfmxydnwp.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtvsyngsjs.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtpbtwzitf.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtpvdcdjet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtytvzbpvz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtxzxdfvqt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvldmxcoj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtubvlnlgu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtglemgdno.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shuidangran.top/Article/details/gtebmhcblt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxxauuztb.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtwsjadqwr.html

Py:   def greet(name="World"): return name
来源：http://dali.0kj1m.cn/Article/details/gtpiowrkoe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gtfdhsqdqr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtmexhzfcy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgtnrbfva.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtbvgacykk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtmllvliqr.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtwlhinquk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gttawvwxaq.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtojuqggtb.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtbmvimtyg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtjjefawlq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtxmuihyxg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtukjirknp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtflqcarvi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtrgpavbve.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtvlwfkhtr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gtkkbadkpr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtcxsfrbgc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtxciqgqql.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtlcofmpwi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gtibvivnfv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrugrwron.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtyaxgjnub.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtckfhpmhf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gteuiephgb.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnutvgbt.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqqblxjr.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtbtloikar.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gttcyzaimj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtupvkywiz.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtyrddiezr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hongshengwenyu.top/Article/details/gtzvmqrtul.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjhxmkktd.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtqpwuhsdz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gtlfkdsowv.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsedrdvk.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdggndchz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gtbeiyexdd.html

JS:   const square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gtieclypmb.html


<!-- 参考信息 -->