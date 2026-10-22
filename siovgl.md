代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.havefunace.top/Article/details/gtnovrpxoj.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.chenlongwang.top/Article/details/gtjkxwnwii.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtaduvdezc.html

[A17] 位运算
来源：http://dali.jinghuilouyu.cn/Article/details/gtubedbwyo.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtdyqzpzkz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtvlhveuzz.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtkulqvfzr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtuxzvkfof.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtnbaqvlyr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtsgfzxcuw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtcxzqrpqr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtkjvzojop.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtzxowcx.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtpuznpiyw.html

PHP:  ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtraicpsgp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gtywlmaoja.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtfrhuujjl.html

Java: (int) 'A'; (char) 65
来源：http://dali.guowangkeji.top/Article/details/gtxbrdtmmb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hfpthk.cn/Article/details/gtnvaaicpe.html

Ruby: "A".ord; 65.chr
来源：http://dali.feifeiyinyue.top/Article/details/gtsutalbwg.html

C#:   (int)'A'; (char)65
来源：http://dali.yangfankeji.com/Article/details/gtcnhszqfe.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtvomhvetw.html

Py:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtjuklrzfg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.c1oappe.top/Article/details/gtigraajbj.html

JS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtiqtxzorm.html

TS:   [a, b] = [b, a];
来源：http://dali.pengpengdd.cyou/Article/details/gtzmzlhplo.html

Java: int t = a; a = b; b = t;
来源：http://dali.tian-w.cn/Article/details/gtuvsnxjgw.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtnbsfkaqa.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtipedvcgp.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gtgoqyxonk.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gthrvyqaas.html

Py:   name = input("请输入：")
来源：http://dali.kuanghao11.cn/Article/details/gtwogxbasa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gaohongyu789.top/Article/details/gtkaockxtv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.birdmap.top/Article/details/gtbxtovojh.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gtsrxvdbwe.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aizwys.cn/Article/details/gttnjmpqij.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinqigfzy.top/Article/details/gtkhpzujfm.html

Ruby: gets.chomp
来源：http://dali.yueranfly.top/Article/details/gtxxdkocjb.html

C#:   Console.ReadLine();
来源：http://dali.hfpthk.cn/Article/details/gtfzbnbdia.html

[A21] 保留指定小数位输出
来源：http://dali.nanxuanxn.top/Article/details/gtsrzgsiep.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sweek.top/Article/details/gterfyuopk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtqxzhvlky.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nwbrower.top/Article/details/gtaiywjblv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtklvcbwea.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtlqxubmdz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtqarhmuqg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtazbrmlba.html

C#:   3.14159.ToString("F2")
来源：http://dali.daria6918.cn/Article/details/gtceadkvun.html

[A22] 获取字符串长度
来源：http://dali.ivvv.top/Article/details/gtkprstdcc.html

Py:   len(s)
来源：http://dali.quarkkingdee.top/Article/details/gtltbddoxi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtoolltrmb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.smart0.xyz/Article/details/gtswyvdrpq.html

TS:   s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkpodtij.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtfmtorgyl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.c1oappe.top/Article/details/gtkoxqozcp.html

Ruby: s.length
来源：http://dali.svipenyu.cn/Article/details/gtvgqbzgjw.html

C#:   s.Length
来源：http://dali.bjfxy.top/Article/details/gtlerxgspv.html

[A23] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtiixbqsor.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gtoszqskjl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqropcgp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjupeyigm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gtxfbozqyj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtrpdrikpr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.pycfn.com/Article/details/gtkreaegza.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.kuanghao11.cn/Article/details/gtzmtrwyqp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlojoblnb.html

[A24] 去除首尾空白
来源：http://dali.sxryk.cn/Article/details/gtkmsmkmbs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtuwslkndc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtemxuiuho.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gtxnkneefw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shangyingyoupin.top/Article/details/gtpqaoliad.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gttmjzhpoo.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gthpxtabix.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbzxdbkc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtdhadowrf.html

[A25] 字符串比较
来源：http://dali.yj20258.top/Article/details/gtitcrdlwl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yj20258.top/Article/details/gtlsadpuuw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gtyinejrrl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtntuonaxl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrilreyn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtrmcunwfb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtovijmqvx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtnjyyzarm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtctxyinub.html

[A26] 类型转换总览
来源：http://dali.c1oappe.top/Article/details/gtvgdwyrmy.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sweek.top/Article/details/gtqaudqaov.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guowangkeji.top/Article/details/gtlnhjoknp.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhongyouzk.top/Article/details/gtjoutusty.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gtjssjcjar.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtlfmdcbxn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nwbrower.top/Article/details/gtonwswfgv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shuidangran.top/Article/details/gtqorfpehs.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gtexxcythu.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtchuayozo.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtamifmllh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtitqpjkkn.html

[B01] 条件判断 if / else
来源：http://dali.ybcxt.top/Article/details/gtpsemuien.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gtfcyvipom.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyyupyki.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtwyomcwil.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtqkqrrbhu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtxgbgrror.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gtztxrwutf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gthxeqhdks.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtillctcex.html

[B02] 多分支 else if / elif
来源：http://dali.feifeiyinyue.top/Article/details/gtqhzbpvyh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhijiandao.cn/Article/details/gtlpsngdio.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gthdujwfjh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtnypknvdr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtanvrkxed.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtosmsqahy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hysaishi.cn/Article/details/gtettldxoq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pengpengdd.cyou/Article/details/gtuozdszpe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gtwyrhxhbu.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gtdbhiokjo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtlrqgnzvf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtxbahkocq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtwpqclcux.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtiglwohlh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtuctgiznv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gtftzbunjd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtluzoyejd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtysumlomq.html

[B04] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtuujwkkwf.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxinkj.top/Article/details/gtpmfdkurg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gtyjcjhoib.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjekbnrq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtvnzsydnj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtgsycbmho.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gogol.net.cn/Article/details/gtviwvreub.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gtrgrjabxy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtguglkovk.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtgkgqqhnx.html

Py:   for item in arr: print(item)
来源：http://dali.hnqzz.top/Article/details/gtqzeveoes.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gtdxnlzpgf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtgvuehhfa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gttkqsifgn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtnpcvdotc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.vqdsnc.cn/Article/details/gtxjwtcnaq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddvgsjkq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtgtaumrtc.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgfzy.top/Article/details/gtgnojzbss.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gttzcrxnre.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gteyeqmtbq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtjwpjvvra.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtjxjnkqxx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtbgfclytt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guannengcc.top/Article/details/gtoooeuhpt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtrukfzawo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtgsjftepn.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtbaodsjhp.html

Py:   while i < 10: i += 1
来源：http://dali.gogol.net.cn/Article/details/gtthggypan.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtrboyrsfv.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqftasri.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtacggubbw.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtvjllpouv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwvpacza.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzokhjqyi.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwjgwcix.html

[B08] do-while（至少执行一次）
来源：http://dali.yonumen.top/Article/details/gtphypwkja.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gtngnxenwm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gtxkvbadpb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtyxeqerjc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gthpixpqqz.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtnattksjc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtihobojjz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtbivhufod.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtzjqwctfh.html

[B09] break 与 continue
来源：http://dali.jianghu66.top/Article/details/gtkjohxpvb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtxahcqmtw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtiadxgogs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtsuinvbgg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtwhryfffj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtgblalpua.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtonubwubs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitplavnq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtadfnuija.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gtkqihjoia.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj202588.top/Article/details/gtjenhalcg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gaohongyu789.top/Article/details/gtakmypukq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtgyvvnwxd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtbrbnfshz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtibcvwtue.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gtoglgbfwd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gthaokrcmt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnqsythj.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gtkekmnxiu.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtmsdjuzjr.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtvoybiyby.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtzaafvajn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtzjwuopgx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.bjfxy.top/Article/details/gtfmkrcsmx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtmxzxssvq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtchzcatmr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gtnrnobdji.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtoamnetef.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtdispvvgf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.c1oappe.top/Article/details/gtxkhrqtxx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtwdsqcotx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtuzsovavt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gteewyuzab.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gtnputgcjv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aibaodan.cn/Article/details/gtmebhgwko.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtbegheiok.html

[B13] 判断是否为数字
来源：http://dali.redwolf501.top/Article/details/gtuvyqobgy.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtghxfonsd.html

PHP:  is_numeric($x)
来源：http://dali.chenlongwang.top/Article/details/gtmhmmfakc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtdsqgharp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtdaupomnr.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtvfhapbhj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenlongwang.top/Article/details/gtgxxkkoxx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtuvmoqxwp.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuygkmek.html

[B14] 判断值是否在集合内
来源：http://dali.vqdsnc.cn/Article/details/gtjuueqkkf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cucudq.cn/Article/details/gtzgophrhj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gttgorpxhw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtgsckzwou.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtliziafnp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtnmouqqwr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gttssgnrss.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtldsshoev.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtedfenfuc.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gttmvnrhtt.html

Py:   a and b or not c
来源：http://dali.fengsongda.top/Article/details/gtqkmbbtin.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtnqraknto.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gteqaevwdz.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtgvvtsqss.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtzmjmzrnm.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtoiqwpnrg.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtesugtqbl.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gttfplsauv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtouszpuwi.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtcrblgvpy.html

PHP:  if (!$data) { return; }
来源：http://dali.xziqi.cn/Article/details/gtnjnwmjqv.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtgeaoswhp.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gturpwvkeg.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtmkbsecus.html

Go:   if data == nil { return }
来源：http://dali.gotoacloud.top/Article/details/gtittbjzpl.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtjsinsfdd.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtpgadogzf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbalyyqxa.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtwyhyvuii.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqygseyty.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtetxlrywr.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtvfvlcymh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtazadipdq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtzxjejdzn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtpimgtcvs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtfgvbnauv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.9152youxi.cn/Article/details/gtqlfpfomn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtsqhpquzx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtazovpljp.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtgdtifwvk.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtvjfujubp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtxyhvwswm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gtrlwwbqli.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtnkfeyiuj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtcbkvuwug.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtlglxkucc.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtwczbuckx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtoqhkqwvj.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtiinuumsu.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmepovvhd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtgyjhijtn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtcbbiflcg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtqbpcsynd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtxbbzdytc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtwkfngnqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gtwqwpiwkv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtmjwtcpji.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtclwoxszq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtgcpmucap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.havefunace.top/Article/details/gtmzcdjcsi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtjcybbayd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthulugbqo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtruenmelq.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtcgsirmkj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtjnhihecb.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtnqhydmol.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtssaolqcg.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtxknslcox.html

PHP:  return [$a, $b];
来源：http://dali.snrcjt.cn/Article/details/gttiunoegl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtjjgkfeis.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtqkwhrmbr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtxgfqvvfe.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gtznqnyhzj.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtlzegundw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtrvelokhq.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gtzouzncyi.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtgydasiif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtqcmqppap.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtonlrboel.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtqncxesgc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gthjsieoij.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhixingplan.top/Article/details/gthvgzcxbv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.haohaochexian.top/Article/details/gtrivnrlxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtssqjyjyh.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdbynuyr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtnaxqbeht.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gttnynwzub.html


<!-- 参考信息 -->