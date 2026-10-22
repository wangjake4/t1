代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtbddibdhd.html

TS:   const value = data ?? "默认值";
来源：http://dali.smart0.xyz/Article/details/gtyvfdkqjj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zdqjudy.top/Article/details/gtfpdptvmq.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gtpzycbxrs.html

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gtbxhzullq.html

C#:   var value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gteyjddzex.html

[A16] 真假值判断规则
来源：http://dali.pycfn.com/Article/details/gtdbyewpkp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.0kj1m.cn/Article/details/gtcyesnkvo.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.chenjidiqi.icu/Article/details/gtnwskyfpr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.mhx1999.top/Article/details/gteylqifpw.html

TS:   if (!x) {}
来源：http://dali.dashuyun.cn/Article/details/gtzruqganu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.redwolf501.top/Article/details/gtymwogqfe.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guannengcc.top/Article/details/gtmwsvrcij.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.316326.xyz/Article/details/gtarqixadh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.haohaochexian.top/Article/details/gtbgoyvpzj.html

[A17] 位运算
来源：http://dali.gotoacloud.top/Article/details/gtdazrphmc.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtdapgacku.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadckwbmw.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtzhtvzhgl.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtsvhrbezr.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtnirgfgul.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtcpidexhr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtxtjwrdnd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtifzpookn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jiagoushi.top/Article/details/gtpqklbwyz.html

Py:   ord("A"); chr(65)
来源：http://dali.tanke756.top/Article/details/gtfpclhthb.html

PHP:  ord("A"); chr(65)
来源：http://dali.gzhubu.top/Article/details/gtvzvcutcp.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shuidangran.top/Article/details/gtrissgwyk.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sufxvd.cn/Article/details/gtjlshomnf.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnhnmkrr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.svipenyu.cn/Article/details/gtnmbqqqlt.html

Ruby: "A".ord; 65.chr
来源：http://dali.nanxinkj.top/Article/details/gtwdempmsw.html

C#:   (int)'A'; (char)65
来源：http://dali.xinyue.icu/Article/details/gtuzrylsmd.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gtwtoxfobp.html

Py:   a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtxufsyzjy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gtjzbpjvlh.html

JS:   [a, b] = [b, a];
来源：http://dali.daria6918.cn/Article/details/gtjvymbcxs.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkmqpyxk.html

Java: int t = a; a = b; b = t;
来源：http://dali.yanxiufei.cn/Article/details/gtkdggqgvg.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsshwuzid.html

Ruby: a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtjtvikgli.html

C#:   (a, b) = (b, a);
来源：http://dali.sweek.top/Article/details/gtvavjtocx.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gtnpbmmnjw.html

Py:   name = input("请输入：")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvegxmvul.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtuwnozpgb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gttgciywbq.html

TS:   // Node.js：readline 模块
来源：http://dali.xylfe.cn/Article/details/gthkvtcrio.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.daria6918.cn/Article/details/gtbcvxfdjf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.quarkkingdee.top/Article/details/gtkzcgdzht.html

Ruby: gets.chomp
来源：http://dali.ydzc1.top/Article/details/gtfvgrewjo.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtqoeegqvf.html

[A21] 保留指定小数位输出
来源：http://dali.daxiang520.top/Article/details/gtyoyenfma.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hfpthk.cn/Article/details/gtlkobxull.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gteralcabz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenzaomai.com/Article/details/gtynuvveno.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhixingplan.top/Article/details/gtotdgyxhv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvyhldtt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtzqttnsyd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtcjatxdor.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuetiantiany.cn/Article/details/gtyirjnrlu.html

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtmfhawxgy.html

Py:   len(s)
来源：http://dali.hnxiangtu.top/Article/details/gtoaqosagn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtgitlgkei.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gteqhhrqub.html

TS:   s.length
来源：http://dali.xuetiantiany.cn/Article/details/gtzyekumhj.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtetzccqjo.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.wangdashe.top/Article/details/gtxjgjwtfc.html

Ruby: s.length
来源：http://dali.fengsongda.top/Article/details/gtcflktiih.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtpxymlxaa.html

[A23] 大小写转换
来源：http://dali.pengpengdd.cyou/Article/details/gtfheoyvdi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ybcxt.top/Article/details/gtiulkxhhi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtjripnnzr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gtuverzpfd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtgghjmsgn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yueranfly.top/Article/details/gtbkqagezx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tianlin.xyz/Article/details/gtfqvxlgkj.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtdrpymeen.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gtxzprpwlx.html

[A24] 去除首尾空白
来源：http://dali.mhx1999.top/Article/details/gttgyjkcau.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jqgufenzy.top/Article/details/gtupwbbrrb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gtcncmprvo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gtkywgyvit.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtgkubiaar.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzziigajb.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gttlquwywc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gtdvyryuwb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtgxwgtcan.html

[A25] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtflaywsfq.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gtxqpjmuom.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhengqikj.top/Article/details/gtbzybpxnk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtxahxsgcz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gtimpuowlr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ppjwa.cn/Article/details/gtzguofrrh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqodrdtol.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtsecrstbg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtynhgznab.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtzqyapyda.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gtfdgkrkpw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daxiang520.top/Article/details/gtorbvtswk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtbwswlzvd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gtpfhpxbdb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gtunfitzgq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.smart0.xyz/Article/details/gtavhjmpou.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtqssepcux.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtipgwwppg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtipmfjxwe.html

B. 流程控制
来源：http://dali.chenlongwang.top/Article/details/gtkqsvcfrj.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtvqslywqh.html

[B01] 条件判断 if / else
来源：http://dali.xuanzx.com/Article/details/gtpbntyfuv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtnvowscst.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtgdosnyvo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnfldxie.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtoimrrcrn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtckhsowqm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gtrhpvhtjz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dashuyun.cn/Article/details/gtppcstrlz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtlsxzdqjb.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtxdqkooxt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sxryk.cn/Article/details/gtbamwubaq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcigkexg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtdtxsyzdy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hammf.cn/Article/details/gtwywlonlo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtzuzsijep.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtdcgwcutr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.vqdsnc.cn/Article/details/gtvmplrobp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtleymleor.html

[B03] switch / match / case
来源：http://dali.cdnleiting.top/Article/details/gtrwirpzyj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtuehygeue.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtcnuppdja.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtgueswgvu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtfkicchei.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtmvvdmzri.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hywenlv.cn/Article/details/gtkinugeru.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdnvhdob.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shuidangran.top/Article/details/gtrerjvscb.html

[B04] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtfzunguqs.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqketyxb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gtoywixjql.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtthdhuxxk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gtstyikips.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gtozkuonip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gtzeldxufe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenlongwang.top/Article/details/gtkypzdauf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gthfebqohv.html

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtzncrmczg.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gtcqssblgc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtiuvywetr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxmilsoq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtoyuvdykl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gtpsubezkk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtpyxxfnbk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gtswygzsgj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hywenlv.cn/Article/details/gtkvosrgno.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtnjgcyrnr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtyhcfohoj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gtvxzujanw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtfpmnecub.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtoytvtbcp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtoapbewrc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtpjlvzdvl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtjtkpfopx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gtuuzrzcyi.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtvexpknqy.html

Py:   while i < 10: i += 1
来源：http://dali.guannengcc.top/Article/details/gtlenigkpy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gtcuxqvdnu.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gteuckokls.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtawfkopdp.html

Java: while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtqaghcryz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtsuulibrw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtncrdgzad.html

C#:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtuagumgpj.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtvfxqeksu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtcjprvqid.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtzfypafxi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtqxfxyiim.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtoqxidbed.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtpukorala.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttksythld.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtjzvemhaj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtlnzstene.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtemnuamvz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtonavlkyj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzumofjs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtpjqspeks.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtoksmwqfl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtjtmpouwk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtboycpete.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gttdqineco.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtnmjughvh.html

[B10] 遍历同时拿索引
来源：http://dali.jyoumei.cn/Article/details/gtzsbzijcz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gtnurqcaxb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtqludjjtn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtzhzkbpbo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtzdacflst.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gtngaseemk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhengqikj.top/Article/details/gtyqsdgxhg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shuidangran.top/Article/details/gtvelvylef.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gtxxzgdyhj.html

[B11] 生成数字序列 / 区间
来源：http://dali.sysykeji.top/Article/details/gtjwybvzdj.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtaocokqou.html

PHP:  range(0, 10, 2);
来源：http://dali.cdnleiting.top/Article/details/gtcsssotvp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gttioqiyqx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtydexmrku.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtwjrnpiei.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtzgpdjifk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gtahxlkmda.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gtvensclki.html

[B12] 跳出多层循环
来源：http://dali.feifeiyinyue.top/Article/details/gtfyyuwbnf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtmzmvuzxc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcbfjrga.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtywuhivky.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtnehlauch.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtxseibqec.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenlongwang.top/Article/details/gtwyzohrzk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtwzaaqobd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gtycjfgzsw.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtxxawczsg.html

Py:   isinstance(x, (int, float))
来源：http://dali.sxryk.cn/Article/details/gtzwfhjayq.html

PHP:  is_numeric($x)
来源：http://dali.xylfe.cn/Article/details/gtvssarjok.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtzolmfcld.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtseknxvul.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtzofktctp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtqhjuhqea.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtuqkellpu.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtdulebgxh.html

[B14] 判断值是否在集合内
来源：http://dali.wangdashe.top/Article/details/gtqwlfvyaz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtmzfpmtqm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtortbgdir.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtttizklyx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtvtwtlnet.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtiwhufdix.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtajqmzcva.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtndzasyjs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtwweixxuv.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gthpyhotmy.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtyrhbtmrv.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gtazexakee.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtjwkqeffr.html

TS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtlvkqvajv.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtvgvdzytf.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtqgdfqvbj.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtyjpznppo.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtrnqdghlc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtwzgexhoh.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gttqighmfp.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtkjlzipzf.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gteypzfizt.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtgsproxwq.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtkedxrdoa.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtbprlcgif.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtcrlfvtvx.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtfrotxwfu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmnisphll.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gtbwskytol.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlxqccgkq.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtoucbriou.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtjrmqtuuz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtkpzzpcdu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtjcjanbhu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtuqrbatqq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtpnpskcgw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtusjdwghp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtuleljrwe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtdsaziyml.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtkxqzyefh.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtexijdpvg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtvfnvogfx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpdonzqat.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gttcywxksm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sweek.top/Article/details/gtotsqkffk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtflgtfiwn.html

Ruby: def greet(name = "World") = name
来源：http://dali.daria6918.cn/Article/details/gttnrffzjt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtjqabfybx.html

[C03] 可变参数
来源：http://dali.quarkkingdee.top/Article/details/gthkvnugyq.html

Py:   def total(*args): return sum(args)
来源：http://dali.daxiang520.top/Article/details/gtilqkcbxu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtevidvwqr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtazzquwah.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtbiusvrvz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtfufqfecw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtotbhlmpp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gtrktrcrkv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtlcdflzqu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtgrxayglc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtmwfasawn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gtxykilsre.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtvalpimsf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtoiorbfps.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gtroguzqld.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gtafpiusnk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtzwjzmdat.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtjiqydbzd.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gtxmeaoscq.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtpcjkadlh.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtjmsrwhfm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtqvcbusrc.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtqczxpnsq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtmbwozvqx.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtwdgnhpwj.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtdziywxfc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtidqcbgnr.html


<!-- 参考信息 -->