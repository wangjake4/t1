代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yangfankeji.com/Article/details/gt2nrpugsho.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gt2nwwpjtcc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gt2nktamtrk.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gt2nerroxme.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2vqodcxro.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yueranfly.top/Article/details/gt2ptyljlmc.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pgvhjssv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gt2nzsajshw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2qaukmitq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2bcqxgran.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrzimweh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gt2fjpdqmih.html

[A18] 字符与 ASCII 码互转
来源：http://dali.bjfxy.top/Article/details/gt2jlrvkgxc.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gt2epjtuvxh.html

PHP:  ord("A"); chr(65)
来源：http://dali.shzxlz.cn/Article/details/gt2zbzxairo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwlcbwoh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gt2fcralsfn.html

Java: (int) 'A'; (char) 65
来源：http://dali.fengsongda.top/Article/details/gt2dgxshuhw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.meibo888.top/Article/details/gt2idwztkid.html

Ruby: "A".ord; 65.chr
来源：http://dali.smart0.xyz/Article/details/gt2hgozikvh.html

C#:   (int)'A'; (char)65
来源：http://dali.aizwys.cn/Article/details/gt2fdejdtgj.html

[A19] 交换两个变量
来源：http://dali.cqqwz.cn/Article/details/gt2fmiyjbap.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gt2xqxjjzbd.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangdashe.top/Article/details/gt2kpvqjjmk.html

JS:   [a, b] = [b, a];
来源：http://dali.shuidangran.top/Article/details/gt2dbqjlfrn.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjdhmnwh.html

Java: int t = a; a = b; b = t;
来源：http://dali.smart0.xyz/Article/details/gt2zyaaduup.html

Go:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gt2fzhvoevw.html

Ruby: a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dciktfrf.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2mgrksfyo.html

[A20] 读取标准输入
来源：http://dali.jiagoushi.top/Article/details/gt2alyfcgrp.html

Py:   name = input("请输入：")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlctadbm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.iojbl.cn/Article/details/gt2uzclakkh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj20258888.top/Article/details/gt2ehuvlion.html

TS:   // Node.js：readline 模块
来源：http://dali.yuanzhike.top/Article/details/gt2gmpsauxx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.haohaochexian.top/Article/details/gt2xbktndix.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gt2jnaakitb.html

Ruby: gets.chomp
来源：http://dali.tianlin.xyz/Article/details/gt2xcfnpzut.html

C#:   Console.ReadLine();
来源：http://dali.birdmap.top/Article/details/gt2vshcfswn.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gt2xxfowums.html

Py:   f"{3.14159:.2f}"
来源：http://dali.cheryme.top/Article/details/gt2qsbarqgs.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2frqxxjuc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tian-w.cn/Article/details/gt2rsshpqyq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2wwjoadct.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gt2ovcgcotj.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258.top/Article/details/gt2qpunvjyi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2koecyvzz.html

C#:   3.14159.ToString("F2")
来源：http://dali.redwolf501.top/Article/details/gt2xocgvqwe.html

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gt2onelfmut.html

Py:   len(s)
来源：http://dali.yonumen.top/Article/details/gt2vaqnlwmh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2qfndnwml.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.316326.xyz/Article/details/gt2ncnqyika.html

TS:   s.length
来源：http://dali.shuidangran.top/Article/details/gt2dwvudsnn.html

Java: s.length()
来源：http://dali.chenzaomai.com/Article/details/gt2gbtfuitv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnqzz.top/Article/details/gt2gyemmmfl.html

Ruby: s.length
来源：http://dali.cqqwz.cn/Article/details/gt2otelwlho.html

C#:   s.Length
来源：http://dali.feifeiyinyue.top/Article/details/gt2bygbvgcx.html

[A23] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnuhpltp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gt2yolyksfx.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gt2fuiqtnxa.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gt2sezlaskx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gt2bhebvssi.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kejqygts.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hfpthk.cn/Article/details/gt2mizoiquq.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2ixshtigb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hywenlv.cn/Article/details/gt2wfznqfsb.html

[A24] 去除首尾空白
来源：http://dali.yj20258888.top/Article/details/gt2ionlxroo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hysaishi.cn/Article/details/gt2dazdxnbf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ehwqpu.com/Article/details/gt2ltzlaqle.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cashguo.top/Article/details/gt2ynlmjqhv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gt2gfuhhlwh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.redwolf501.top/Article/details/gt2xkirijll.html

Go:   strings.TrimSpace(s)
来源：http://dali.snrcjt.cn/Article/details/gt2mypwwzbb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sxryk.cn/Article/details/gt2stzmnnbp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guowangkeji.top/Article/details/gt2abjfszrt.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2vwofuoix.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gt2pkpcwlok.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tanke756.top/Article/details/gt2xwswmdgs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgfzy.top/Article/details/gt2tyrgawuv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gt2zkzyedjf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gt2pzqrfdtp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gt2bdvnovwi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hysaishi.cn/Article/details/gt2nbbtxggz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cucudq.cn/Article/details/gt2enelhgnd.html

[A26] 类型转换总览
来源：http://dali.gzhubu.top/Article/details/gt2hrixsrgo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gt2tzlqhade.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gt2niqydnao.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gt2uozfjowu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.feifeiyinyue.top/Article/details/gt2irdgbbxw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gt2owrsavap.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.snrcjt.cn/Article/details/gt2qlibimhz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gt2kvqacgpy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.daxiang520.top/Article/details/gt2mpkgredy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2jqivmnzv.html

B. 流程控制
来源：http://dali.snrcjt.cn/Article/details/gt2hrfotdee.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2mmoqcouh.html

[B01] 条件判断 if / else
来源：http://dali.tanke756.top/Article/details/gt2gqyhdqxp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gogol.net.cn/Article/details/gt2ubtetxrt.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2ifurlcfx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2ndgxsnbu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2fcobwrqq.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2mxapiuaz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.havefunace.top/Article/details/gt2xpyymskz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gt2vopcrhyr.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2zyblgeiy.html

[B02] 多分支 else if / elif
来源：http://dali.chenlongwang.top/Article/details/gt2odcqdfer.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxinkj.top/Article/details/gt2vzcvdvpm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.birdmap.top/Article/details/gt2cukolvmj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2ndtyofug.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gt2kovrpkcg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jdtpokqs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zdqjudy.top/Article/details/gt2bjbcuvso.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gt2iezdjkyc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gt2rzikjuql.html

[B03] switch / match / case
来源：http://dali.hnqzz.top/Article/details/gt2wxhxltqd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gt2lpckkkvg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2xcrvzbok.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2xxcpgvoe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gt2ybjbqufw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2ojqctpcd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2imetvlkj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2ntdbooat.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zycfv.cn/Article/details/gt2eanjofta.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2yflfzclw.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gt2imtvudin.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.aizwys.cn/Article/details/gt2hiogzcpd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gt2fntckgyo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gt2hcwpafrs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sxryk.cn/Article/details/gt2syaqhlcc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gt2fnovzusy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2idrrcftr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gt2bxrewfjc.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2plrnxinj.html

Py:   for item in arr: print(item)
来源：http://dali.gotoacloud.top/Article/details/gt2uohhslgj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gt2fhcyzxnz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2oozfhibj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gt2mitmkrxt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gt2sonfaimc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gt2dmwmvbbr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ybcxt.top/Article/details/gt2unfavrir.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gt2rebqtcwq.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gt2inxzncie.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.kuanghao11.cn/Article/details/gt2lzjuqtou.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2bvzefyyk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gt2cduaqfqa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gt2rchfajud.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.haohaochexian.top/Article/details/gt2gapngdxg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gt2zwpncgta.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenlongwang.top/Article/details/gt2wphxvffj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gt2poleyovc.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gt2vwgruwnt.html

Py:   while i < 10: i += 1
来源：http://dali.aizwys.cn/Article/details/gt2ajbrksks.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xylfe.cn/Article/details/gt2lkqpleoy.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xhaczzwd.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rybtcgix.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2qbazhbru.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzzyuao.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gt2hkesytcf.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wlmrleoj.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vpviznvw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gt2yelvdxqr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2gxdxardx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2narmjsay.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2wsvvvrsk.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2boluwlzx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2neszlzdl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hysaishi.cn/Article/details/gt2tjfxobhr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2wolollvv.html

[B09] break 与 continue
来源：http://dali.zhixingplan.top/Article/details/gt2cuoolprn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gt2tmohmmro.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2trtqsmdz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2uhuwmhsr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ajlfjfci.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gt2iegrwkud.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gt2cuzbzwvg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ybcxt.top/Article/details/gt2lwxuyjpp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2gkheoqni.html

[B10] 遍历同时拿索引
来源：http://dali.dianchejie.cn/Article/details/gt2bvsdaawn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.quarkkingdee.top/Article/details/gt2hpjtgtiz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cheryme.top/Article/details/gt2cqhapadq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fvhcrjjq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2lzhymevz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhoulong.xyz/Article/details/gt2thmncknj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxuanxn.top/Article/details/gt2swjdbxpl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gt2eqsafrti.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gt2wctdlumk.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gt2okpsqyhg.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gt2nofwrntm.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkapxclh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gt2hudxjgub.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gt2ppsigzla.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gt2fkxyttkp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxnexkle.html

Ruby: (0...10).step(2).to_a
来源：http://dali.fengsongda.top/Article/details/gt2tfufyndg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2zzxtsvqt.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gt2zqtifzea.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gt2yokhpbta.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gt2zsvnvbwr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2otnoeqhn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2akofhwgz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2elmtomsz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gt2lsemvlxe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gt2okzacnbu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gt2wkfjzawm.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gt2ofalpwca.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gt2tywnitnk.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gt2tetxczeh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gt2avbmwuyr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gt2igojahis.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gt2vzmkgjgd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gt2llfxsihn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shuidangran.top/Article/details/gt2cxtuzdmo.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gt2jmgfgsyy.html

[B14] 判断值是否在集合内
来源：http://dali.yj20258.top/Article/details/gt2lanltzwo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jiagoushi.top/Article/details/gt2uiommphf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gt2yqdqxcxh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2cissxjey.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2nfmdxpti.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bihuoyuj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gt2pzozdshq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gt2vrgtlrkp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gt2pdytywlg.html

[B15] 布尔运算与取反
来源：http://dali.tianlin.xyz/Article/details/gt2yflilmqd.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gt2woomqqsj.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gt2hfzinxxn.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2zebgnkdg.html

TS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2brykueuh.html

Java: a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2kindtxyv.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2kdhfqrar.html

Ruby: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2wfacgpkr.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zholvwzr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rugclbif.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gt2zkjgaild.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gt2nqsvwnag.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gt2jazhxibb.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2psceevft.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sjbzsonn.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gt2grkvispo.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gt2niiefrjf.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gt2nuxcwghn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2eabeejoe.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2drtcooxc.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2yvdtuccx.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gt2acverfra.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cliplkti.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gt2edyeajxv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2orobsuhi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qciaiedk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2siofjqlh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gt2hvcwvgex.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2nbcrpbbc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2vsfvbtis.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gt2rurzjmph.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxuanxn.top/Article/details/gt2globgvdj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gt2jvmrlbkq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2tocngcmp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gt2ktoaklbg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yffybllc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gt2vslrubrt.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gt2zwckxxuf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubfazsha.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gt2kutqumpc.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gt2xkgwgjrj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gt2epyugdwv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gt2upoaqjtz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2scwunxcb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajnjowex.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2imlekcra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gt2nrgcwaaj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2hqtbkyhu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daria6918.cn/Article/details/gt2uclchlvo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2ljlsqnwz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gt2uisfjozl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gt2itafaobj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gt2ohisevyh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gt2rvmciouv.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gt2gdahhzdc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2oscttryf.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2gjyclnyp.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gt2yavuvhov.html

Py:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2bumshdqf.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gt2clxolucp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2itbnttwj.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2xzwcflhr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gt2unanevig.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gt2qahmnfeb.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2bozhjfnc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gt2ovujyzya.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2pephdwgb.html

Py:   square = lambda x: x * x
来源：http://dali.zhiwuduotai.top/Article/details/gt2fttljxhw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gt2qaywtrth.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2offtvewq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2vkoddrjd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gt2nbinelat.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gt2ayeepkkz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gt2rgofasov.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2xjnhzlhd.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gt2tpqcntef.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenzaomai.com/Article/details/gt2hidrmiju.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2kupkhkgy.html


<!-- 参考信息 -->