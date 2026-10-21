代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.shzxlz.cn/Article/details/gtytlqtobu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xuetiantiany.cn/Article/details/gtxpxffcha.html

Go:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtaozegnzl.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiaxvgdzs.html

C#:   // 单行；/* 多行 */
来源：http://dali.hysaishi.cn/Article/details/gtmbeeajlj.html

[A15] 空值判断与默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfciadtrv.html

Py:   value = data or "默认值"
来源：http://dali.yuxming.cn/Article/details/gtnrucdqoo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yj20258.top/Article/details/gtgwnwcmht.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnqzz.top/Article/details/gtctrihqma.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj20258888.top/Article/details/gtmnwtofzc.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gotoacloud.top/Article/details/gttlrgaxkx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aizwys.cn/Article/details/gtfizhirmn.html

Ruby: value = data || "默认值"
来源：http://dali.haohaochexian.top/Article/details/gtoopidynx.html

C#:   var value = data ?? "默认值";
来源：http://dali.yvedp.cn/Article/details/gtnxxcaaby.html

[A16] 真假值判断规则
来源：http://dali.feifeiyinyue.top/Article/details/gtvicabdwy.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nwbrower.top/Article/details/gtmiiweryi.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ehwqpu.com/Article/details/gtxkvgdsgo.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenzaomai.com/Article/details/gtpikynmkq.html

TS:   if (!x) {}
来源：http://dali.zhongyouzk.top/Article/details/gtffzubgqx.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlfuxmrww.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ehwqpu.com/Article/details/gtdjpqueby.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gtcnjurddy.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtbpoypfek.html

[A17] 位运算
来源：http://dali.pycfn.com/Article/details/gtkehqdygr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtystaiaal.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhijiandao.cn/Article/details/gtlxlaqtft.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtxggudcng.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtpcmbppsp.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtofgggzpt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gteccaszjj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtdembpyxr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtgrdrkhgp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nanxuanxn.top/Article/details/gtqhaimhiz.html

Py:   ord("A"); chr(65)
来源：http://dali.yj20258888.top/Article/details/gtdcpaxjil.html

PHP:  ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkennzozk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtsleywswv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258.top/Article/details/gtnpqfxmcd.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gtswzaxsaf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xuanzx.com/Article/details/gtkynaglje.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangtech.top/Article/details/gttirqymbe.html

C#:   (int)'A'; (char)65
来源：http://dali.mhx1999.top/Article/details/gtudjkygrz.html

[A19] 交换两个变量
来源：http://dali.gzhubu.top/Article/details/gtxywufnts.html

Py:   a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gtauyexemz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.zdqjudy.top/Article/details/gtbpktrdxv.html

JS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gtjleviqbl.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtepttshrw.html

Java: int t = a; a = b; b = t;
来源：http://dali.hysaishi.cn/Article/details/gtojhgtesb.html

Go:   a, b = b, a
来源：http://dali.jinqigfzy.top/Article/details/gtlvymmzhe.html

Ruby: a, b = b, a
来源：http://dali.zdqjudy.top/Article/details/gtegntfvew.html

C#:   (a, b) = (b, a);
来源：http://dali.guannengcc.top/Article/details/gtqiwyigjt.html

[A20] 读取标准输入
来源：http://dali.gogol.net.cn/Article/details/gtntldmqoe.html

Py:   name = input("请输入：")
来源：http://dali.aibaodan.cn/Article/details/gtitzqsclw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangdashe.top/Article/details/gtdfyamqqu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.aizwys.cn/Article/details/gtkpwattdm.html

TS:   // Node.js：readline 模块
来源：http://dali.snrcjt.cn/Article/details/gtiqcjmxzc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xinyue.icu/Article/details/gtanezlchp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.birdmap.top/Article/details/gtpvoyzaxd.html

Ruby: gets.chomp
来源：http://dali.haohaochexian.top/Article/details/gtjleittjp.html

C#:   Console.ReadLine();
来源：http://dali.fengsongda.top/Article/details/gtdiwlolsw.html

[A21] 保留指定小数位输出
来源：http://dali.hnxiangtu.top/Article/details/gtkxjtjltg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gtxxbsikrr.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtefhwalwt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhengqikj.top/Article/details/gtxydexiix.html

TS:   (3.14159).toFixed(2)
来源：http://dali.haohaochexian.top/Article/details/gtucyxpdjt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtrrnwndqa.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtqlsieusk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtvoggccqq.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gtcqiyxthv.html

[A22] 获取字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtowigxohx.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gtejkibzki.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinghuilouyu.cn/Article/details/gtypathgpw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yvedp.cn/Article/details/gtbvfsmurb.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gthlrguryr.html

Java: s.length()
来源：http://dali.shzxlz.cn/Article/details/gtbjwfutch.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.wangdashe.top/Article/details/gtlsjyhfar.html

Ruby: s.length
来源：http://dali.dashuyun.cn/Article/details/gtzxrbztuh.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtrvoaqefq.html

[A23] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gttxppqyyy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqrvgtgd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yuanzhike.top/Article/details/gtqusmnrtc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gthfhvpmdz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.dianchejie.cn/Article/details/gtgfopzzwv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmeyozqbo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ydzc1.top/Article/details/gtwlxoduso.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxhdeakh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhongyouzk.top/Article/details/gtrgdxglxr.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gtotmvlfkg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigfzy.top/Article/details/gtqvmnmfpr.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gtjbtxvzep.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtrniniimw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.pycfn.com/Article/details/gtdcalmunn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtglolpflw.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtmphqytbw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aizwys.cn/Article/details/gtqlihrbdb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakflmxvw.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtgrygjggu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyaqxnssd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtbzlrscxs.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.redwolf501.top/Article/details/gtqpefikeq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtjoritjzo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuanzx.com/Article/details/gtnleqopwk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttyhsafcy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gtsljpwfjz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gtxybjlsoa.html

[A26] 类型转换总览
来源：http://dali.haohaochexian.top/Article/details/gtirevscrx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cqqwz.cn/Article/details/gtenedwsmm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gtvaqjsdqq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtscwjaeww.html

TS:   Number() String() Boolean() x as number
来源：http://dali.bjfxy.top/Article/details/gthufpxghg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.meibo888.top/Article/details/gttqnndpuq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtozshicig.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiuzqlhic.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtgbkoiaxt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtxzcgstod.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtrvmsvpqj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqclfzuan.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gtylyjoctu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuanzx.com/Article/details/gtjvcamrwm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.c1oappe.top/Article/details/gtbtdnqvlq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtxglkliby.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtjuqhvtuy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtgaugnpvk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ppjwa.cn/Article/details/gtaagctzfu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shzxlz.cn/Article/details/gtkvvijzcp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gttybmumzl.html

[B02] 多分支 else if / elif
来源：http://dali.svipenyu.cn/Article/details/gtxrlqwtga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gttxhavvul.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxfftfwyp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtcvaqeayp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gtjcomrpks.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiydoklp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gtfjzfccww.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.9152youxi.cn/Article/details/gtizfgcjpg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtlwunorkk.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gtoyblzevb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtlclgfv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gtibtffujf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtqyjexndd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqrbrgdwp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gtzdhlwwbj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtztvxbqhe.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ivvv.top/Article/details/gthmcilvyg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.fzhhl.top/Article/details/gtdkglxsnu.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtzjiysmui.html

Py:   for i in range(10): print(i)
来源：http://dali.guannengcc.top/Article/details/gtkgmirras.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtolhwobjv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtebhjjxrw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shzxlz.cn/Article/details/gtveqssqoe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gtzcswrwzi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gtcbcaiymw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtrffuscko.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guannengcc.top/Article/details/gtgxugmhkl.html

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtygyyfqyd.html

Py:   for item in arr: print(item)
来源：http://dali.yonumen.top/Article/details/gtumphrecu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zdqjudy.top/Article/details/gtapdrkovs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtstobyhaq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtfzosvhky.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtkbuzgjot.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtheoisday.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnxiangtu.top/Article/details/gtheesruvp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenzaomai.com/Article/details/gthknrpfwh.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtykbozuzd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hammf.cn/Article/details/gttwctyxcc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gtglrqzxxn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtiqozghuh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gttizfqrrc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtjkecyrxf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gtftehklfv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gtnmnyzwlz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtkedbrkqv.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gtkjpbrchi.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gttcdkupdm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gtbjktohxx.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtxuhygjqs.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtgwftiprc.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtphqdchbf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gttyfyoskg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gtyxtpalgk.html

C#:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtodrgmoji.html

[B08] do-while（至少执行一次）
来源：http://dali.dashuyun.cn/Article/details/gtsjxbrgrl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gtdxckzbcm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gtuutgsqqp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtchaqbsya.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtisvxydzc.html

Java: do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gteurgjctz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shuidangran.top/Article/details/gtaietjimq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gtjbcnnjyx.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtlhvscxcy.html

[B09] break 与 continue
来源：http://dali.zhongyouzk.top/Article/details/gtvahdjdqi.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigufen.top/Article/details/gtdrutfdtn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtvndeusne.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtmynfuipx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtpfnokngi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtbeqkimma.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtlfiynyrc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.kuanghao11.cn/Article/details/gtatubsvug.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtrmygjaum.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtiiqabtbg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gthnbxbzkq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cashguo.top/Article/details/gtvnptsrbp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtdblxgros.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gttwkexyqa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gtgngpnyqf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuanzhike.top/Article/details/gtgplnxljz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gtgmgnxfzc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yanxiufei.cn/Article/details/gtbdzwmftd.html

[B11] 生成数字序列 / 区间
来源：http://dali.dashuyun.cn/Article/details/gtvatdstaf.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtqbsolsie.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtvqjqkukj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gttvsdnifg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtalorlkqa.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtttrsdgpx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gtxkexovpz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guannengcc.top/Article/details/gtwrbabwuu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gtpdorhopu.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtpzpagzdm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zycfv.cn/Article/details/gtlgayuqyz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtmjubrtvr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtdlocengo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtijaeorug.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtfeukcotm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jlsjyb.cn/Article/details/gtkfchafle.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtseypilbw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gthyzplojv.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtzwvudtug.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtdppkcalm.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtawrskqcw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtqyvmuwks.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrlmqkwv.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gtztuqsahd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtdclcriht.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtzlrcbucs.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtxzqiyzdm.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtboodyirl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtyrzpfjob.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtshpdnpcw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtmycifdcb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtsvsestna.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpkoukzqf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gtzdkdexvz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdcointpm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtsxebcdwj.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtybvasxte.html

Py:   a and b or not c
来源：http://dali.ehwqpu.com/Article/details/gttcdudluq.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtfxfqocba.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnvdauer.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtuowrevrw.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyrkjtym.html

Go:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtrgsfsinq.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gttsepnksf.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtldevvgsz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtwirinhns.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtoroecetv.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtmwaggjav.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtmjamkild.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtophydlyq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtwiphgsgp.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtaleykvid.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gtwfmqgebv.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtbganjbhp.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtttbxdexa.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtoafofdvu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpetevvzg.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtehayjcpo.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtmjtxvnfr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtlmhvfsfj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtjkuqrwff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtwlulnyhv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtrxfiuaaz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtwwqjkycj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gtqlqwfnpg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwjztsuee.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtgkbpfjvl.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmjnaakb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtinilpktc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtajgbeysq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gteaflczil.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gthzzvybky.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtijluzjvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gttmhveixe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtunfafzys.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtmvrsexmz.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtbzeqlbjo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxmurvovt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtpzjqdxmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtuxkletsg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gttdaczzxl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtlxoynlsc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtigxwvtvr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtpghkwtnx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtnzswbtzw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtftwwqzjn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtxrvetnil.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.snrcjt.cn/Article/details/gtjzlfjyry.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.316326.xyz/Article/details/gtxpxrgkim.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gtabrpfgek.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrivgdry.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtxizkvceg.html

C#:   f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtbgmtnoyk.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gtqkxdrroj.html


<!-- 参考信息 -->