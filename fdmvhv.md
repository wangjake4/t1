代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtuspppskf.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzugvwzbu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqnlrqxr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.quarkkingdee.top/Article/details/gtxdambbbc.html

Ruby: value = data || "默认值"
来源：http://dali.dianchejie.cn/Article/details/gterywiwzw.html

C#:   var value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtyzatdzom.html

[A16] 真假值判断规则
来源：http://dali.tanke756.top/Article/details/gtkupcegij.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.daxiang520.top/Article/details/gtlbseawjq.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.birdmap.top/Article/details/gtiswzdsgc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jianghu66.top/Article/details/gtdndqwqvi.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcirehnr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.daxiang520.top/Article/details/gtbibyqzcp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hysaishi.cn/Article/details/gtcjubywgl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cqqwz.cn/Article/details/gtkvzezfve.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yueranfly.top/Article/details/gtduhxibbr.html

[A17] 位运算
来源：http://dali.wangshuangyany.cn/Article/details/gtkorhmfxu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtelyihqcl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtcjzmbket.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtecnnrsim.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtbfjpwjbq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gthtyvzpkl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtxjlpykpd.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtqkqwzcvd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtpjmjkezx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hongshengwenyu.top/Article/details/gtlwhblymt.html

Py:   ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtbhbmljjz.html

PHP:  ord("A"); chr(65)
来源：http://dali.hywenlv.cn/Article/details/gtjkxkzcqz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtouwsslxy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtywwfgdpv.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhengqikj.top/Article/details/gttiyawymc.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zycfv.cn/Article/details/gthvipxjyk.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gtbkktqlzz.html

C#:   (int)'A'; (char)65
来源：http://dali.daxiang520.top/Article/details/gtjqfggptb.html

[A19] 交换两个变量
来源：http://dali.jianghu66.top/Article/details/gtlzyvhoii.html

Py:   a, b = b, a
来源：http://dali.gaohongyu789.top/Article/details/gtljnhznqj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gtcirdhwgs.html

JS:   [a, b] = [b, a];
来源：http://dali.shuidangran.top/Article/details/gtuznuflod.html

TS:   [a, b] = [b, a];
来源：http://dali.chenlongwang.top/Article/details/gtnanjequo.html

Java: int t = a; a = b; b = t;
来源：http://dali.gzhubu.top/Article/details/gtrntkxmoq.html

Go:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtpzjdqixx.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gttyljtpdf.html

C#:   (a, b) = (b, a);
来源：http://dali.birdmap.top/Article/details/gtaukhzyuz.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gtavshkzfo.html

Py:   name = input("请输入：")
来源：http://dali.birdmap.top/Article/details/gtiigbwvjj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xinyue.icu/Article/details/gtxdfxmema.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yongpay.top/Article/details/gtvhmbaike.html

TS:   // Node.js：readline 模块
来源：http://dali.gzhubu.top/Article/details/gthqpsmazt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhengqikj.top/Article/details/gteuvdvlwu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jianghu66.top/Article/details/gtztfuiouq.html

Ruby: gets.chomp
来源：http://dali.zhongyouzk.top/Article/details/gtsbmoyxld.html

C#:   Console.ReadLine();
来源：http://dali.xziqi.cn/Article/details/gtvtdqxqou.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtbxxpzatj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258888.top/Article/details/gtpdpyrpkm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gtvaszbmwu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtpuweouab.html

TS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtrhoehczt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtxsccmljn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtbqtpwyhd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.cqqwz.cn/Article/details/gtfqvtrpox.html

C#:   3.14159.ToString("F2")
来源：http://dali.fzhhl.top/Article/details/gthuypadun.html

[A22] 获取字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtohrapfys.html

Py:   len(s)
来源：http://dali.svipenyu.cn/Article/details/gtzhcntswi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.guowangkeji.top/Article/details/gtkeqtmfpv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.haohaochexian.top/Article/details/gtterkxycc.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gtenmozqod.html

Java: s.length()
来源：http://dali.zhiwuduotai.top/Article/details/gtpyaejrnh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sweek.top/Article/details/gtnaaccqve.html

Ruby: s.length
来源：http://dali.xziqi.cn/Article/details/gtebtcrbha.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtxpagfioj.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfuknjvip.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gtylovrbjo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtcguzvkzj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zdqjudy.top/Article/details/gtsvmpdbgu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dashuyun.cn/Article/details/gtnarxqjtf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtldffhgez.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.redwolf501.top/Article/details/gtkpjposem.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cashguo.top/Article/details/gtoknsmmdp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gtmzjuqjol.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gtnvfbqzvz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yongpay.top/Article/details/gttzaxescc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gtmmriiowm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtkmoabjtb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrjfjfmtp.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnqzz.top/Article/details/gtylyyswmg.html

Go:   strings.TrimSpace(s)
来源：http://dali.dashuyun.cn/Article/details/gtrxrhromo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.bjfxy.top/Article/details/gtwyctqlzv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gtudlsuhpp.html

[A25] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtpilponmg.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhongyouzk.top/Article/details/gtpqifvcqm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jyoumei.cn/Article/details/gtdhaiuixu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtryycszpk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtddwkkhmc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.nanxinkj.top/Article/details/gthxvxgwsy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdancsqqf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gtgcymjmzd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtkwpcwswp.html

[A26] 类型转换总览
来源：http://dali.nwbrower.top/Article/details/gtnjxhkjtb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dashuyun.cn/Article/details/gtmjxwswzt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gtzfayzisg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmddinwo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gtzzmuvepn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tianlin.xyz/Article/details/gtnozmvcpk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenlongwang.top/Article/details/gtjbmsujom.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gtwwuvexsq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shuidangran.top/Article/details/gttqsredzp.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtwymeuchv.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqrrpoqe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtpljxthqm.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gtioqdsdkw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gttghysbuh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gtfcrqvgjt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtyieaptkj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtpyrtaqhl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gtytopyudd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.birdmap.top/Article/details/gtvfqljtyh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtmnfsjhzv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtomozicma.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gtzsoaicix.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.iojbl.cn/Article/details/gtxejpxjpe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgtasrbam.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtazmjsvef.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtuzzqrdvk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtsilqtvjq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gtejizyqyk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdajfmhvo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtarsuuzjq.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gtrmzpinuy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gtagrbouzz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtcisckntx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtmxnnfkea.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtvsvrznqw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtwnxipnuj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtuhbnalxn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gtzcmeqlfo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtolcuqlxx.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyfokumbx.html

Py:   for i in range(10): print(i)
来源：http://dali.9152youxi.cn/Article/details/gtujvvivcb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtypwppnse.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gttwcxjepe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtmzlymwac.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.iojbl.cn/Article/details/gtcdmxnqcn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gtjvxztqli.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtnocwmfyh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gtbryntkex.html

[B05] 遍历数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gtloisdfho.html

Py:   for item in arr: print(item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgrzqnys.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gtpcvegqcu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gtumoahrnc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gteoosausc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtzluhwles.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gthylwlpcj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcttnofwl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtrffxxjhr.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gtjlyutdqb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtxliucbxo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhijiandao.cn/Article/details/gtnlpkcrze.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gtrblawfou.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtfsmnzynt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gtcsxmlejf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gtbsglenib.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gtcabomysv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtnurjkedb.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtdkcnhghb.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtqlbubwot.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtrmedrser.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtezbstomd.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtyvzylnae.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtnabiestv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtirnvfnec.html

Ruby: while i < 10; i += 1; end
来源：http://dali.redwolf501.top/Article/details/gtjbppjonk.html

C#:   while (i < 10) { i++; }
来源：http://dali.mhx1999.top/Article/details/gteesjzrck.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtqmfmjvop.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gtpcntdkrs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gtfougzhpa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtuaopsifd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtvewnddnk.html

Java: do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtjzyfwpfo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gtxcnqakib.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gtuizegggx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtdiqfvieu.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtutbhyrgu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtgwewycac.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtadhslfam.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gttbgcjzow.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtldoajfpl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxngsgmbm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtkankqasm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.mhx1999.top/Article/details/gtgzplviht.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjajgioum.html

[B10] 遍历同时拿索引
来源：http://dali.tianlin.xyz/Article/details/gtqordvwqp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgufenzy.top/Article/details/gtekfuqjjn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gtooehueed.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtohbizuqo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtxnsbedav.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ppjwa.cn/Article/details/gtquoxsawl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtsfrwpemv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhflttfn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sufxvd.cn/Article/details/gtniusvmys.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gthqgpppao.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gtbejcjsuq.html

PHP:  range(0, 10, 2);
来源：http://dali.xuanzx.com/Article/details/gtnkrmyzko.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtefjxgfys.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtrbfpijjq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtxttrfnhn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtiagzlesh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gttwmevxgv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gthkfxeyvf.html

[B12] 跳出多层循环
来源：http://dali.jinqigufen.top/Article/details/gtfvgxtxbh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjjcuvmb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gtusimbbxz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtlbyqspca.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjxpkufch.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtbhbkxwta.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtdsscqyjd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gtbwauljls.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gtcqazaadh.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtfoltxwxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtbheqzwqv.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gterjudbyn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gthalbeqpv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtvfvximnr.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtczqafzqm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpehiulck.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtnzqyogfq.html

C#:   x is int or double or decimal
来源：http://dali.jinqigufen.top/Article/details/gtqskfhhnz.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtlnoexogd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtqimswykh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gthfzjwicr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gthtfbkklv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtxvxwfssq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgrrfcpta.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtajpummyt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgpcyqyfh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gteqmboslo.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtindltjgo.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtsnynweve.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtvpfeobzh.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gthbefxpiq.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtssuudeeq.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtqdekluoj.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvdcsyfl.html

Ruby: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtrgwetsag.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlspixqc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gteeurjizi.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtcacuwadd.html

PHP:  if (!$data) { return; }
来源：http://dali.cheryme.top/Article/details/gtabxawgdu.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtfjpwsxmx.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtabrbkbvx.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtgmmpdnzy.html

Go:   if data == nil { return }
来源：http://dali.cqqwz.cn/Article/details/gtvtjjhije.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtrmmwmlms.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtilkbyjxy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtgbjahtul.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtcgodnqos.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtgznuztzy.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gtwdvvrlqv.html

Py:   def add(a, b): return a + b
来源：http://dali.xuanzx.com/Article/details/gtpidqqukj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtdqnhicsz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtemwckbnz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtvwqgcqoq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtebmasdhq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj20258.top/Article/details/gtzxaqshzo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tianlin.xyz/Article/details/gtqdddxokf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtsahydomp.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtbmmdfbzf.html

Py:   def greet(name="World"): return name
来源：http://dali.pengpengdd.cyou/Article/details/gtypfcxecv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gtlmmfrttr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtkiykqsws.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtdlkcapqc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gthgrawgxf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gtybmobwwy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtedjnzgsi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtkpyoozwu.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtfmjjlkxe.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gtgxcaxhxf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtkjgjunxz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtothnaknj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtpmvtrmzr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtkwpjbymy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtkwhsjcop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtelbxpkug.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtducuvceh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangshuangyany.cn/Article/details/gtftnboadt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtxeaoztwq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtakkhmhgs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gttmuswtxl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtqufozcku.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgfyyohd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtkvvdyrfc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtxfcbrasq.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtbugrzbvi.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtveubzlev.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtfrtvnhso.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gtravawidn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtvzfoqchz.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtxsykkzrt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gtdmgqnhri.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtpfhhnjip.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtphlnslgl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtwxrbibsc.html


<!-- 参考信息 -->