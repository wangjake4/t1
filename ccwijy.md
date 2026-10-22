代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtbzcvopau.html

TS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtxnjppunt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.gzhubu.top/Article/details/gtskrvohdm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtvjccniun.html

Ruby: value = data || "默认值"
来源：http://dali.hysaishi.cn/Article/details/gtialubybm.html

C#:   var value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gtaeyaikku.html

[A16] 真假值判断规则
来源：http://dali.hfpthk.cn/Article/details/gtkmbhllin.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jyoumei.cn/Article/details/gthtenzczh.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.tianlin.xyz/Article/details/gtptmkxean.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.aizwys.cn/Article/details/gtymtzfccz.html

TS:   if (!x) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmoljjba.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.bjfxy.top/Article/details/gtinlycegz.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhengqikj.top/Article/details/gtfdhipmln.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xziqi.cn/Article/details/gttiqdzkzk.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgdvetwpo.html

[A17] 位运算
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfeuxqwvj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtuqozdmql.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shuidangran.top/Article/details/gtwuiipdzq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gtbuwesmac.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gthaenuipz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtfxqcoxvi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtmpezdreb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtuvljewhd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtzrtbcnjk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gtroiveckw.html

Py:   ord("A"); chr(65)
来源：http://dali.dashuyun.cn/Article/details/gtxrelimjw.html

PHP:  ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gtxfwqppkc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxinkj.top/Article/details/gtjkhoevma.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gtdwgtnqzs.html

Java: (int) 'A'; (char) 65
来源：http://dali.shanyushiyangtech.top/Article/details/gtyeukmxaz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ybcxt.top/Article/details/gtggiodyjq.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhijiandao.cn/Article/details/gturjnwmum.html

C#:   (int)'A'; (char)65
来源：http://dali.ybcxt.top/Article/details/gttclmkasd.html

[A19] 交换两个变量
来源：http://dali.pycfn.com/Article/details/gtevcitgem.html

Py:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gthwturxpx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzottjcx.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gtzddicbys.html

TS:   [a, b] = [b, a];
来源：http://dali.jianghu66.top/Article/details/gtgtgsiwyb.html

Java: int t = a; a = b; b = t;
来源：http://dali.jlsjyb.cn/Article/details/gtmkeyocgy.html

Go:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gttrislerf.html

Ruby: a, b = b, a
来源：http://dali.ivvv.top/Article/details/gtyukwzhra.html

C#:   (a, b) = (b, a);
来源：http://dali.ehwqpu.com/Article/details/gtjfxulvrg.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gtkzohgbyw.html

Py:   name = input("请输入：")
来源：http://dali.yanxiufei.cn/Article/details/gttexdmykq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfoikyafy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xuanzx.com/Article/details/gtqjqcdgyl.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gtludzjpel.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.andypj.xyz/Article/details/gtuwdcrfwp.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgufenzy.top/Article/details/gtvwfhkeyo.html

Ruby: gets.chomp
来源：http://dali.xuetiantiany.cn/Article/details/gtsdeybbjh.html

C#:   Console.ReadLine();
来源：http://dali.zhoulong.xyz/Article/details/gtzzatlidr.html

[A21] 保留指定小数位输出
来源：http://dali.chenlongwang.top/Article/details/gtxlmuppst.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yangfankeji.com/Article/details/gtvvpwujhl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gtenkbtvuh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gtsvhybzrp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtsbcwhfdp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtcibzfjvw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtzttvrcvz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdteirqb.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenlongwang.top/Article/details/gtkpfemgkq.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtmnqrklps.html

Py:   len(s)
来源：http://dali.pycfn.com/Article/details/gtjjlotcgb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jyoumei.cn/Article/details/gtrhgbmesm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtowsbbgew.html

TS:   s.length
来源：http://dali.jlsjyb.cn/Article/details/gttttyoajm.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gtxitnlpih.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtkabdcyce.html

Ruby: s.length
来源：http://dali.andypj.xyz/Article/details/gtljgjhynx.html

C#:   s.Length
来源：http://dali.shzxlz.cn/Article/details/gtvarmretp.html

[A23] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtcsaqolmw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhiwuduotai.top/Article/details/gthcmkjyga.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gtlobiugak.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtmemhfzot.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtwlutvuvp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtnapzlfjb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hammf.cn/Article/details/gtnmzgwtvu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangdashe.top/Article/details/gttskaonty.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.haohaochexian.top/Article/details/gtkateptow.html

[A24] 去除首尾空白
来源：http://dali.dashuyun.cn/Article/details/gtaffmopug.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guannengcc.top/Article/details/gtfycywhfj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtsexrdtlr.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxfdbspi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtlhhwjspu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yongpay.top/Article/details/gtnudhvvwx.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gtmbkwnhee.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtdzhmjfnx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtcdreamjr.html

[A25] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtnhuainae.html

Py:   s1 == s2; s1 != s2
来源：http://dali.vqdsnc.cn/Article/details/gtkcgdttwo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yuanzhike.top/Article/details/gtcikkthvy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gthcrouhml.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.guannengcc.top/Article/details/gtwrpexxuf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtogofqmok.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtglskkwlw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cucudq.cn/Article/details/gtldcgrtyf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtpioyyikg.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gtvzykkauq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gttnbnncme.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gtvbajmjrq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj202588.top/Article/details/gtohfcdzgt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nwbrower.top/Article/details/gtnsgsisnq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddvxqtej.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtksgmdtvr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cheryme.top/Article/details/gtavkyszlq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hongshengwenyu.top/Article/details/gtrmhertwn.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtecwlquwp.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtusikbehh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgmizmpcn.html

[B01] 条件判断 if / else
来源：http://dali.zhijiandao.cn/Article/details/gtksserlnk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtsmzqvown.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cashguo.top/Article/details/gtwdkwsqwe.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtprudjjpr.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtlovwgbsy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtqgvhjjdc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gtnhvyeelc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shuidangran.top/Article/details/gtemapcyqv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtsodwuhhj.html

[B02] 多分支 else if / elif
来源：http://dali.shangyingyoupin.top/Article/details/gtokcewtmq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ydzc1.top/Article/details/gtnqwoqxlo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvhtbpqrt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtrtdwsazt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtxdugyqov.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xinyue.icu/Article/details/gthjnzrbxk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gtlporxnfk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gtpwkgggwt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtgmqqadci.html

[B03] switch / match / case
来源：http://dali.wangshuangyany.cn/Article/details/gtjbgpndyd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fengsongda.top/Article/details/gtwxnuvrjg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtshbvezic.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtfpqydagm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gtaxnzdxvw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtvuyihuld.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daria6918.cn/Article/details/gtytttbfao.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gtrnidbywl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtqvcdagro.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtmgftdcdf.html

Py:   for i in range(10): print(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhoppxwe.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ivvv.top/Article/details/gtungbmipc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtzagamwfi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtskixqszx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gtlpggkfau.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.mhx1999.top/Article/details/gtdhjzqvjc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gotoacloud.top/Article/details/gtuoxjgymy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tianlin.xyz/Article/details/gtgyhidfsn.html

[B05] 遍历数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtudnzmfkq.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gtzfgqhteh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gtugnthehq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtuydsrfzs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtzserttjv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtbhupzzlu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.quarkkingdee.top/Article/details/gtvnayjttd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.kuanghao11.cn/Article/details/gtwfyohqvq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zycfv.cn/Article/details/gtkpkmlvzk.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthwntqnr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hysaishi.cn/Article/details/gtybfqdnxl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtocqkdfhi.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtvspewgcj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtcwnqmpse.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtopjtzckf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmqptqony.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gtquzfgoaa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbdrjoenw.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtklxyhect.html

Py:   while i < 10: i += 1
来源：http://dali.cheryme.top/Article/details/gtadgskust.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gthwbeorsm.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtojqmpwtm.html

TS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gteznrvobe.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtviggznma.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtrbypmzsg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.vqdsnc.cn/Article/details/gtdstnanbs.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtfdeadtnw.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gtyhvtoqfz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtqhexvwlc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtywxdfkws.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtkjdrekft.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtwjacdjsf.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtzzrsrxnx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.redwolf501.top/Article/details/gtiwjovesg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhijiandao.cn/Article/details/gtpjuikedt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtbvosyflu.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdqpeggq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtdnnmyipa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtarzcpwih.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtfilhnjcv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtqhzotlng.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqcdrynyy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtwkludpqh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gtvfqiyqff.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtklupdvzp.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gtvmjtmcnu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtlvcdyqwm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gthlzarvlf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtnsltgdaf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtbinaxdle.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtwmbpypmo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhixingplan.top/Article/details/gtmpngpcsz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtxddxctig.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtukjleikg.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtapjzpend.html

Py:   list(range(0, 10, 2))
来源：http://dali.gzhubu.top/Article/details/gtswjizvhb.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtuxgdxdya.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtyvrkhrmu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtebrcxhgo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtzcdfkowe.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtfxxmnuui.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtykwtfdzc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbxpiylu.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtoalijecn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gtezrhivyf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtgmlgamjv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtpqysvrsy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtmfezulxv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtzmhczhft.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aibaodan.cn/Article/details/gtliwejzbk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gtgdbzzmxp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtcnxtvxfq.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtbrfcifyf.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtsueyawdg.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gtlqwtpmwp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtwufraffi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtldrgwpyi.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtsawymepl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hongshengwenyu.top/Article/details/gtnpwaspno.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkawiqmt.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gtckmisydf.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtojljjvuz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtbltyedun.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtfnrazyas.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtxgedkmhk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtxzttlkwk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtjhxzhfro.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtqiylmhrm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtcrmhnvii.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpuxsxfh.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtnuvuausl.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtjkpeeybo.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gtdfxdjymh.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtkrjjmhmf.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtxyrxxryn.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtmuyvxttr.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtstufzzye.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzheirovv.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtctjaizrl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtgqicoaze.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtkminqtdp.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtbdtjigpm.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtkgxtlxfe.html

TS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gtntqpubzy.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtptuguzja.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtwywksdfy.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtdvejpkya.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtxauqoddj.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttkfgvdez.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtpopemjit.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmukheguo.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtapesywdr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtnjabxipw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gthgxsmhvf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtpdvbefde.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtksogdqzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtnyjygpkh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtxqsdocnv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gttnqnmrgy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtnkdkkkjr.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gtcynnnllk.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtcsvdcpgd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.bjfxy.top/Article/details/gthnuirqdr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtmkyfidpm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtzctzxyan.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.haohaochexian.top/Article/details/gtmrdppayp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtqxclsrnr.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gttrtcslss.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jiagoushi.top/Article/details/gtrkdoifde.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtemqiaaar.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gtonoijbpx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnxiangtu.top/Article/details/gterjdoubr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtpfsgcdch.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtlkohoyyt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtipdidnqv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtsuytlvzk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtrkwvpwax.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtvmucxiui.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtzgicgmis.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtqrnliowv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gthzbpdkxu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbnoamltm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.meibo888.top/Article/details/gtkwlhsszg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuvwjlmm.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gthlnzkfuy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtevfcxwkj.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtarxervmo.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gtxpkwalwi.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gttkmfehoi.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlnnufoa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtvqehgemr.html

TS:   return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtibsncmko.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gtnhrjzxyo.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gttjgvmfcz.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtztabmqlk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtaikfohqk.html


<!-- 参考信息 -->