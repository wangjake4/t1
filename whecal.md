代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gtdukteyuy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinqigufen.top/Article/details/gtktrdxgqs.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gtkpahunjg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xziqi.cn/Article/details/gtsgjgdgbh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gtdazadqpe.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gtbkgtqmyp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.pycfn.com/Article/details/gtwrlxklhy.html

[A17] 位运算
来源：http://dali.zhongyouzk.top/Article/details/gtvwsfwtpm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtlvjlgnuw.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gtgbnpdzsi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtojenhmfo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtsohxblby.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtuclpubgs.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtvsesdnya.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtdpwokekn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtplwwqsvf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yuanzhike.top/Article/details/gtxpasfbbo.html

Py:   ord("A"); chr(65)
来源：http://dali.andypj.xyz/Article/details/gtolehwair.html

PHP:  ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gtxafzfejq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gtglomhrgp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sysykeji.top/Article/details/gteirzlzob.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhoulong.xyz/Article/details/gtalhxgfbq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.bjfxy.top/Article/details/gtkcalljtd.html

Ruby: "A".ord; 65.chr
来源：http://dali.smart0.xyz/Article/details/gtbnlxylwy.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gtksxlyzhm.html

[A19] 交换两个变量
来源：http://dali.mhx1999.top/Article/details/gtpmitpxjd.html

Py:   a, b = b, a
来源：http://dali.yj20258.top/Article/details/gtkqhfxnhm.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.daxiang520.top/Article/details/gtxgqphmfe.html

JS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gtewvmsbin.html

TS:   [a, b] = [b, a];
来源：http://dali.zycfv.cn/Article/details/gtqpdmblgn.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhiwuduotai.top/Article/details/gthqepzjps.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtueikywry.html

Ruby: a, b = b, a
来源：http://dali.bjfxy.top/Article/details/gtxpmintlw.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtzjtztzne.html

[A20] 读取标准输入
来源：http://dali.cucudq.cn/Article/details/gtjvyggvmv.html

Py:   name = input("请输入：")
来源：http://dali.pengpengdd.cyou/Article/details/gtkgzhlqwe.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjiskrja.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gtfrufjwcp.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gtquyqgwhd.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxgxgvkq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hammf.cn/Article/details/gtzoqngoki.html

Ruby: gets.chomp
来源：http://dali.jqgufenzy.top/Article/details/gtfyjffroa.html

C#:   Console.ReadLine();
来源：http://dali.zhiwuduotai.top/Article/details/gtwnvbafpf.html

[A21] 保留指定小数位输出
来源：http://dali.yonumen.top/Article/details/gtwybcyymo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gtbzqnpppm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtjowsgreb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtwhfkdwhq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtrwxxxazw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gtisuboafv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtkiwzvowv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtvtnlqsps.html

C#:   3.14159.ToString("F2")
来源：http://dali.yangfankeji.com/Article/details/gtvjxvvori.html

[A22] 获取字符串长度
来源：http://dali.jianghu66.top/Article/details/gtwdonegzn.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gtdiribzcg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gtcwrfdojb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.bjfxy.top/Article/details/gtrljwxumg.html

TS:   s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtnadpdhmf.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtbrxodsma.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtcklbeomb.html

Ruby: s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtqurozobr.html

C#:   s.Length
来源：http://dali.haohaochexian.top/Article/details/gtpljvlqnp.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtnbipmzqy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.hysaishi.cn/Article/details/gtfsnarblp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuxming.cn/Article/details/gtdlrirmrg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtuvpphiax.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtylcgzhwq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtiurvorbt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtwtwpzfqh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtorscdlcs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpvrreoul.html

[A24] 去除首尾空白
来源：http://dali.ehwqpu.com/Article/details/gtfxfwlprt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gtdpgxwixf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxwqrfbcl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtndsyqust.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gttopxaeak.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ehwqpu.com/Article/details/gtmlpvevcj.html

Go:   strings.TrimSpace(s)
来源：http://dali.havefunace.top/Article/details/gthifckitx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhengqikj.top/Article/details/gtnfvehbfi.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtfudxggos.html

[A25] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gtcszwysnn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sweek.top/Article/details/gtbsnphcoa.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258888.top/Article/details/gtkpjbrrvd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.fengsongda.top/Article/details/gtjpjgoahj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtvhtofbpw.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ppjwa.cn/Article/details/gthsdfpicl.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtkcfweovo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhoulong.xyz/Article/details/gtcegopxxw.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtwtfhvuoh.html

[A26] 类型转换总览
来源：http://dali.xinyue.icu/Article/details/gtonzzuxsr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gtxojosgom.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gtyhzwtdte.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtbekqoqbt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cucudq.cn/Article/details/gtfgogglgl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xylfe.cn/Article/details/gtasqfkqkl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gthghmbagb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhengqikj.top/Article/details/gtufwjptvn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxinkj.top/Article/details/gtmmbkhbog.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtujpqpxcp.html

B. 流程控制
来源：http://dali.yuxming.cn/Article/details/gttmmtmuwm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtamutcvbv.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gtnhhjxlwl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.iojbl.cn/Article/details/gtpsykpvyo.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gotoacloud.top/Article/details/gtsdmmbeyv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtltnvnxpc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnhedfor.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtwsdxfyal.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtquvfdwvi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtloeheoky.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gtaeydvsjv.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtshbjybpk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtxbvpwnau.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gtwsgusbdw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtjlzymgof.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtjilihovk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gthnhfuqhn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hysaishi.cn/Article/details/gthdhtwjon.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gtsuszwcgt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtodcntiii.html

[B03] switch / match / case
来源：http://dali.sweek.top/Article/details/gtormumlgm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.birdmap.top/Article/details/gtnixcfzcn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtbdhxwwsx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtaecrliqq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtmamfqdeq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtyxapziyp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fengsongda.top/Article/details/gtwpsubbyf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gthxzrcfmr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gtebxddijp.html

[B04] for 计数循环
来源：http://dali.yj20258888.top/Article/details/gtbpjtouev.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gtspdxrbct.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhengqikj.top/Article/details/gtsjnnsktr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gtoianlqpt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtcdangosv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtiwelyvxh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhiwuduotai.top/Article/details/gtlogitbtn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtybpjydiw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtjbzjitdk.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtsvxscuzi.html

Py:   for item in arr: print(item)
来源：http://dali.birdmap.top/Article/details/gtfuhcictc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtjaplpjrb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinqigufen.top/Article/details/gtgutocqhf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvdezdkx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenlongwang.top/Article/details/gtuddyougs.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyxlrzis.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gthggqaoxl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shzxlz.cn/Article/details/gtyjxjbewe.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gtxpyuwomh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtxbltmszi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtnoqvqorp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtdyaonzkh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtqmbxmanh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvxzmsjd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtlldkeoed.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvlactga.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zdqjudy.top/Article/details/gtbhflfzpk.html

[B07] while 循环
来源：http://dali.wangshuangyany.cn/Article/details/gtamryxzsl.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtzgpogwkm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtgyvmilzi.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtjzuycdrp.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtqgmxzoad.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtbgpelfyb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtvfowanqc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtdgshjxqk.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtzsqzkgsc.html

[B08] do-while（至少执行一次）
来源：http://dali.cucudq.cn/Article/details/gtvbukuatv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gthiptuufg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtzavbfwox.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfihbpzox.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtgbgfcqau.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtyaqmzynp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmpypluy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gtldujtbrf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gttntgxywc.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtilujpvam.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pycfn.com/Article/details/gtgkzytdhw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtuirtmmkp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtkipuwabc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtvlwqgnhj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtdxurwdtr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gtpfqemipw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtgunfsyqa.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtsonjiizh.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtbdypqjdm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtkqxnssoc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtcotpfxgr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtzktjhnco.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtnddfrruu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtyofrziuk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtrfyosidd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtpyoblrzm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtedgiowfd.html

[B11] 生成数字序列 / 区间
来源：http://dali.kuanghao11.cn/Article/details/gtqofmovgj.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtxdrwkoeh.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtyufixaio.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtnxjlppoh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtrmmmixsq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gtbylriecn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gturcxzuul.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtutrizbkj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmakwcsle.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtsxcodret.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtukioejsj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtqskttgjq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gthxyfhdfn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gtwpdmkrwi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtzcresvgb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cdnleiting.top/Article/details/gtytotbleu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gtzbjitnev.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwredwumn.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtuljahejq.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtxtbbjhav.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gttfxwpgmw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwtqnyngo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtswufjeui.html

Java: x instanceof Number
来源：http://dali.ehwqpu.com/Article/details/gtgvunzqhz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtcvnmpiyb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gttwyarebf.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtowsbefhj.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtaqyopjzi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gtayejrzit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gthcasssgv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtlmkmqtxf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtakkvaoep.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtehwhrhmb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtgncfhata.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtyiwzncgb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttxaqlybl.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtdwipqjtj.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gtfwgfrjbr.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gtjibgierh.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtoshogooa.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtrodyditf.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtboqczjvq.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtzobqgyvd.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtsqdmcbox.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtbdrpfsoc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtkrgbrmzk.html

Py:   if not data: return
来源：http://dali.jiagoushi.top/Article/details/gtkwnbukis.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtzivtlmhs.html

JS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtiffqrqxx.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtvkseqanb.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtduadviby.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtxnnnzozg.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtambtdzjp.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtwhgvlmkh.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtwwdzwram.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtknoplryb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtorywrpnc.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtuoepcoqq.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtlfmzdjlj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmqizvdfw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtafiwntzm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtdkldjayi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtaufzdmlm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtvasovuob.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtpvucmhkh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtzachkopu.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtdoagnolr.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtifufkvfr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gtdyjmruqv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxnzondrl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtkjwzycki.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gtchjgqiyy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtisadrtjj.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtealupmuc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtcrgyjosb.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtpqholqot.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtfomswdkv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazfuggzl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtcwqhznxq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtgjsefpxn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gteeihokqg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtzicqwhhr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gtclvnzbwx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gttgabyiyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtzwxuoipm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtuwfnacut.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxdvvsaw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtwuprkmrg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gthpljqmpj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.316326.xyz/Article/details/gtfbivqtvz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqkooghn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtqhbypbkh.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtzecflbfr.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtnhormjtm.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtnojqxuhc.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtdwdpyxzo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtwcqtgnvu.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtdyvdwhzi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtdgsuxdad.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtqixvebpk.html

Ruby: return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtsjltylud.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.316326.xyz/Article/details/gtnhrzqcvd.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gthyqhpxoy.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtonnqebij.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtsytidviu.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtzvdylahc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtmlttjihe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtpexdnaoa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hfpthk.cn/Article/details/gtcceciqng.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtsuefzugb.html


<!-- 参考信息 -->