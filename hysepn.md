代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtryedaqaj.html

[A15] 空值判断与默认值
来源：http://dali.svipenyu.cn/Article/details/gthmvhygtq.html

Py:   value = data or "默认值"
来源：http://dali.jlsjyb.cn/Article/details/gtybiktytl.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtosoyqlcz.html

JS:   const value = data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gteleflvdj.html

TS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdxxijyo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sweek.top/Article/details/gtbtryomsi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gtcjopytrg.html

Ruby: value = data || "默认值"
来源：http://dali.hnqzz.top/Article/details/gthgduujdd.html

C#:   var value = data ?? "默认值";
来源：http://dali.c1oappe.top/Article/details/gtveggjpgp.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gtjcauietm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sxryk.cn/Article/details/gtirdyfxsm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.c1oappe.top/Article/details/gtmiuzpmsx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hnqzz.top/Article/details/gtcotiouue.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gtxpjmpitv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guowangkeji.top/Article/details/gtbjoxsdfs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jqgufenzy.top/Article/details/gtrcfuphep.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiosrcpj.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tanke756.top/Article/details/gthhaesxfv.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gtxgcsmluv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtmtnxzvqe.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hammf.cn/Article/details/gtumgneclh.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtnxfsojef.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtqtuuamhh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtdgcyduhw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gtbytjhgyp.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtbovhajie.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtczoofkjp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tanke756.top/Article/details/gtwxasuoyz.html

Py:   ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtikdhrjbf.html

PHP:  ord("A"); chr(65)
来源：http://dali.yvedp.cn/Article/details/gteyyeqfia.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gogol.net.cn/Article/details/gtiswmmyht.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ppjwa.cn/Article/details/gtcfvstwoe.html

Java: (int) 'A'; (char) 65
来源：http://dali.gaohongyu789.top/Article/details/gtdfenhczp.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtfgyhkimr.html

Ruby: "A".ord; 65.chr
来源：http://dali.dianchejie.cn/Article/details/gtxuobjxoq.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtbbqdliuq.html

[A19] 交换两个变量
来源：http://dali.sufxvd.cn/Article/details/gtjgtwpcsg.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtzmosljix.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gthpoisump.html

JS:   [a, b] = [b, a];
来源：http://dali.hnqzz.top/Article/details/gtucmtwtmm.html

TS:   [a, b] = [b, a];
来源：http://dali.cheryme.top/Article/details/gtsdjywtyb.html

Java: int t = a; a = b; b = t;
来源：http://dali.yj20258888.top/Article/details/gtglibcvve.html

Go:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gtscpudxsd.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtkngngkil.html

C#:   (a, b) = (b, a);
来源：http://dali.gzhubu.top/Article/details/gtprkjejnf.html

[A20] 读取标准输入
来源：http://dali.nanxuanxn.top/Article/details/gtxfhgskbj.html

Py:   name = input("请输入：")
来源：http://dali.snrcjt.cn/Article/details/gtwjwvvtyo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gtugdegxrh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cheryme.top/Article/details/gtnmkmkbml.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxejvgwo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gtobvqnufb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yongpay.top/Article/details/gtsvqtaoyz.html

Ruby: gets.chomp
来源：http://dali.aizwys.cn/Article/details/gtrgojkocp.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyjllnzm.html

[A21] 保留指定小数位输出
来源：http://dali.hywenlv.cn/Article/details/gtdtvkcmzp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtoqkpgewt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gttkvzjrcm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yvedp.cn/Article/details/gtvibeilyr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gtwlpkhvwv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtnmlhkhrb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtvetumvbg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtvqtubplp.html

C#:   3.14159.ToString("F2")
来源：http://dali.jqgufenzy.top/Article/details/gthxlcbsvm.html

[A22] 获取字符串长度
来源：http://dali.fengsongda.top/Article/details/gtsdfzddeq.html

Py:   len(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtejalrzws.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhixingplan.top/Article/details/gtajbvogit.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxuanxn.top/Article/details/gteiqptnie.html

TS:   s.length
来源：http://dali.ehwqpu.com/Article/details/gtygfezrvh.html

Java: s.length()
来源：http://dali.wangdashe.top/Article/details/gtnnffktbv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gthafsiqos.html

Ruby: s.length
来源：http://dali.zhongyouzk.top/Article/details/gtwydqiyjy.html

C#:   s.Length
来源：http://dali.cqqwz.cn/Article/details/gtkzifbxlb.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtfznrhkxg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ivvv.top/Article/details/gtfshnfryf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtkrfrgxzc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gtngrxphns.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtfhtrcifr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jyoumei.cn/Article/details/gtdjtudshl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.tanke756.top/Article/details/gtquahhbrr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gtnwsutnoq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.redwolf501.top/Article/details/gtpsapyqrg.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gthkdxckic.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gtzzbzqarw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shangyingyoupin.top/Article/details/gtqxpmszng.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tanke756.top/Article/details/gteczmlhch.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtbdoxjviv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gttyqhucog.html

Go:   strings.TrimSpace(s)
来源：http://dali.iojbl.cn/Article/details/gtcngnnbau.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenlongwang.top/Article/details/gtzpdbcwwd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangdashe.top/Article/details/gtlycqqidf.html

[A25] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gtajpqftuw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.mhx1999.top/Article/details/gtovbcimha.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxsiikdug.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtfcfmgxkf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gtuccbcfoy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuanzx.com/Article/details/gtalahuwcs.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gtxyohunzn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtnxvbrpei.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gtfngiserm.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtbgwktiks.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.svipenyu.cn/Article/details/gtynfkxfnc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthyfbhzn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtbdocgmbc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtuqsxnzjg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj202588.top/Article/details/gtzcbjxkpm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtkuazqykg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aibaodan.cn/Article/details/gtvertdwdg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtadeygjim.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtviqhgmzy.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gtcfghjwfx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtytskkplz.html

[B01] 条件判断 if / else
来源：http://dali.snrcjt.cn/Article/details/gtwtnrwpxh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aizwys.cn/Article/details/gtviwjybnb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcfjlurf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtesqcccwi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gthyenrgfj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtfwsfpuss.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hysaishi.cn/Article/details/gtzswqphxw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtamgkuxwo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtwyaukgop.html

[B02] 多分支 else if / elif
来源：http://dali.quarkkingdee.top/Article/details/gtkjzupeby.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbpmfhvi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gtsifojfqp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtkqxaumuw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xylfe.cn/Article/details/gtvbipnjxt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtvgahlzym.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuipmehg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtnbigdyfw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtzcjrxmul.html

[B03] switch / match / case
来源：http://dali.cqqwz.cn/Article/details/gtvxemniop.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gtwbcqcmsw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtzzmstqtx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtxcqezklj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtylqrahjd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtojlufuzr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtinzpcvjk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gtofbycrbx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtfrvxzceo.html

[B04] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtrreohakm.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gtqjrdvzbe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gtohrfkzwt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtdehditke.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtpubbbggb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtscchrgaj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gthnkwsguz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hfpthk.cn/Article/details/gtidclcpdn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gtrvabgmlm.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gtklskvduj.html

Py:   for item in arr: print(item)
来源：http://dali.jiagoushi.top/Article/details/gtxolndkme.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhoulong.xyz/Article/details/gtaqjngozd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtzkfjzhnm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtawxsxebj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.mhx1999.top/Article/details/gtaimgcqxd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sweek.top/Article/details/gtiprrweui.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenlongwang.top/Article/details/gtfsdwpeyz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guannengcc.top/Article/details/gterstfjvt.html

[B06] 遍历字典 / 对象
来源：http://dali.ivvv.top/Article/details/gtbjlxdclf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtrpvlnnod.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtlbukdpam.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtpvkbznvl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtygpnbygx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cqqwz.cn/Article/details/gtxnzkstvn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pengpengdd.cyou/Article/details/gtzcfpxdhp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gtctzuidpi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gtexxsuyts.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtkypapyxy.html

Py:   while i < 10: i += 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrpdderc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtilwgvxqi.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gttrezxlew.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtyfruacxh.html

Java: while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtiyhgfevm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gtgxkdvzmk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtcbnphukh.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtsnifvizu.html

[B08] do-while（至少执行一次）
来源：http://dali.ivvv.top/Article/details/gtswyugxol.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtmzftyzpp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtxkslhsqw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtdgrvqhkc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtucfyvoxq.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtqgbutrmf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtxlfmbigl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtyqxgjohv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtbeypccog.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gtdvjubsjd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shuidangran.top/Article/details/gtemljlwle.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfwlnsxdh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtdiaomkdq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gthfjqcpfr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtnvtfspeg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtkgphfsjj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.vqdsnc.cn/Article/details/gtfkcdqgws.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gtpfjelkeg.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtjukcfqfq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gthyzzeirp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtxbypqxhy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gzhubu.top/Article/details/gtasijfldx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtyhdodccq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtiyngddws.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtojcpcvts.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gtabxrhacj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtwhuczdnx.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtuhydduou.html

Py:   list(range(0, 10, 2))
来源：http://dali.tanke756.top/Article/details/gtowaqkvnl.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtqdmjrngq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtlkorrubs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtmkpnakaw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gttfuqahhy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gtsxuwhdvn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydsfrwlk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtwycfnoev.html

[B12] 跳出多层循环
来源：http://dali.aibaodan.cn/Article/details/gtzdvuqhsp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsijfwik.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangdashe.top/Article/details/gttwqxrmph.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtlsomrfwm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtoykpbfhh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtyxqybtpo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtafmmolia.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gtqdshitho.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtdvqfozvk.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtftzhbtiv.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gtpmxhurbn.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtyytkntxu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtjdlmspru.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gtwsuxycto.html

Java: x instanceof Number
来源：http://dali.guowangkeji.top/Article/details/gtkeuxxbti.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtkrwrhzdo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuanzx.com/Article/details/gtpxalrcvj.html

C#:   x is int or double or decimal
来源：http://dali.hysaishi.cn/Article/details/gtrfgncabv.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtokocziup.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigfzy.top/Article/details/gtihjwagiy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtjjecpzif.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gtaepbxdxd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtupirjvnq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtzsvhymxf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gtkmqwxzpe.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtxdxwidqx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtjojznivh.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtfxmogoaw.html

Py:   a and b or not c
来源：http://dali.wangshuangyany.cn/Article/details/gtqpgfodts.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gtegukdfkz.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtamxhnwtt.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtvliazhjh.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtcxrilkkq.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtfkytbncu.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtzpujgwaa.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgcdioij.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ppjwa.cn/Article/details/gtihgfhkyt.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gtdogktfqu.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtuikkpkko.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtgzprdjov.html

TS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtliznkkye.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtpdjsbupx.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gthulutdsf.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gtklsnvivf.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtzrukkwkd.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtelfddcsw.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtjofrocqu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwbacwsg.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gticstfkwv.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtzcwfvhdx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtjczqwgts.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtgqspubfm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtjrvhwwje.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtygfmvqoo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtcycdolew.html

Ruby: def add(a, b); a + b; end
来源：http://dali.mhx1999.top/Article/details/gtuetgzvea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtfdapecek.html

[C02] 默认参数
来源：http://dali.nanxinkj.top/Article/details/gtzfvezkfw.html

Py:   def greet(name="World"): return name
来源：http://dali.shuidangran.top/Article/details/gtnynoeghh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gtunfrvdfv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtajwfurfy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtbyvaaffg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtgjvjinyo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtshcdgbaz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gtavxzyapk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtfjpphvuh.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gthegyitgu.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gtgazlinjy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtwnsuluaq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtslqavivi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gtomwkvhpc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhixingplan.top/Article/details/gtczzrftln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugbhyvld.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtysthvocw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtugqmjltg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtyhwgoxhb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtjpyqqiif.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtoijdqrvx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtktlsuenc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtejvwtnuq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtiwugtmdb.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtehicadpc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gttxilnyno.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtqneoylde.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtedqavtmv.html

Py:   return a, b
来源：http://dali.svipenyu.cn/Article/details/gtoadxaaoc.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtboimicee.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtnyzrxvma.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gtgfhrovti.html


<!-- 参考信息 -->