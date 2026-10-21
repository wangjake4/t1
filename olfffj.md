代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtpojdmwzi.html

TS:   const value = data ?? "默认值";
来源：http://dali.pengpengdd.cyou/Article/details/gtweisianq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xziqi.cn/Article/details/gtgyabyooi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimvlddkz.html

Ruby: value = data || "默认值"
来源：http://dali.zdqjudy.top/Article/details/gtmcacwmvl.html

C#:   var value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gttvipddls.html

[A16] 真假值判断规则
来源：http://dali.yj20258888.top/Article/details/gtfuogecur.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hysaishi.cn/Article/details/gtcfhjqewm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xuanzx.com/Article/details/gtdrzgshfi.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sxryk.cn/Article/details/gteohxvwry.html

TS:   if (!x) {}
来源：http://dali.jqgfzy.top/Article/details/gthajbhnjm.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.fzhhl.top/Article/details/gtbbxfgizd.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nanxinkj.top/Article/details/gtgttfnend.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gtmdxcjgmp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hnqzz.top/Article/details/gtnxacbzva.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gtzmlbjpzt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtcwnyhhch.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtltiqhrnm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtpgewsjhs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtghlmholq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtjamivyfx.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtlefmflzl.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtclqhxpow.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtxnrbeflg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.hnqzz.top/Article/details/gtrdqxlvnb.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtqkawvrzk.html

PHP:  ord("A"); chr(65)
来源：http://dali.pengpengdd.cyou/Article/details/gtclkqrghk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtrysjhini.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenzaomai.com/Article/details/gtjpxadfok.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gtqjzsofht.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.birdmap.top/Article/details/gtwubpfwfk.html

Ruby: "A".ord; 65.chr
来源：http://dali.yj202588.top/Article/details/gtptqvshya.html

C#:   (int)'A'; (char)65
来源：http://dali.jqgufenzy.top/Article/details/gtrevexjya.html

[A19] 交换两个变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlugrjhnl.html

Py:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gtswslewtq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtuwkvdsna.html

JS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gtjtgdandl.html

TS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gtjtaxjqfc.html

Java: int t = a; a = b; b = t;
来源：http://dali.cheryme.top/Article/details/gtlhzowvvr.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtfjebroby.html

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gtenjayprr.html

C#:   (a, b) = (b, a);
来源：http://dali.316326.xyz/Article/details/gtetidyisg.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gtiyofdivz.html

Py:   name = input("请输入：")
来源：http://dali.shuidangran.top/Article/details/gtveqhrlqo.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtbtjethry.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jqgufenzy.top/Article/details/gtdpzotgon.html

TS:   // Node.js：readline 模块
来源：http://dali.pengpengdd.cyou/Article/details/gttzyqrays.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigfzy.top/Article/details/gtksswhfhb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xylfe.cn/Article/details/gtdopvbcxg.html

Ruby: gets.chomp
来源：http://dali.zhengqikj.top/Article/details/gtkhqtiryq.html

C#:   Console.ReadLine();
来源：http://dali.hnqzz.top/Article/details/gtmoipsozi.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gtkmmauhce.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgufenzy.top/Article/details/gtatunmckm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtyfppmxhv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gtmvnxhvbi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtassjbnjy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtvzcwkild.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.cdnleiting.top/Article/details/gtbsbdhepv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtqgosbpyx.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtfbmamyvf.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gtuvngjisa.html

Py:   len(s)
来源：http://dali.yueranfly.top/Article/details/gtdybzrlly.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sxryk.cn/Article/details/gtnxxbogzi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sxryk.cn/Article/details/gtwfntdpyx.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjjovjdl.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtehmzlzrt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxluyuqhe.html

Ruby: s.length
来源：http://dali.sxryk.cn/Article/details/gtyyvcrlpm.html

C#:   s.Length
来源：http://dali.xuanzx.com/Article/details/gtshtovjeb.html

[A23] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtiuxtwiyy.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgwqhgbjp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.quarkkingdee.top/Article/details/gtfumruhpf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gthonsitfx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtiyzeiefs.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtfmelpqiy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzourbhqr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gaohongyu789.top/Article/details/gticyvnkat.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ehwqpu.com/Article/details/gttwfuxool.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gtgblsbtsa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtoohktekp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwpisgnn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuxming.cn/Article/details/gtyqjcmjoj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtlmitbsbn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gtkugaracm.html

Go:   strings.TrimSpace(s)
来源：http://dali.ybcxt.top/Article/details/gtqnqlcdzz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dashuyun.cn/Article/details/gtoqcwdqnv.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xinyue.icu/Article/details/gtnerttbzs.html

[A25] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtwfueafhu.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtvczczjrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gtmirskyok.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gttlwexisb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtghwtbngj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gteullvqod.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dianchejie.cn/Article/details/gtbghopxoy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.haohaochexian.top/Article/details/gtowzduetp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgufenzy.top/Article/details/gtixfgcejx.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtnlufwcqo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gtcaehqjha.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gtzqcvpdav.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gttrcmbgwh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtapuhhaxh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtpjodejlx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gttgdkcrse.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yj202588.top/Article/details/gtgstdgcej.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtxqflvxhr.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtrbswrbuj.html

B. 流程控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkymhvfuo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtqrmgbolu.html

[B01] 条件判断 if / else
来源：http://dali.nanxuanxn.top/Article/details/gtxazoscxs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xziqi.cn/Article/details/gtuuiqbpyh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cqqwz.cn/Article/details/gtlgnthbmy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtkxtdqxuc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtjutzdphj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtywlwokuh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnxiangtu.top/Article/details/gtfpmmmjls.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoglbcmwl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtosunpmgj.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gtuwbpwbzb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gturoehedo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ppjwa.cn/Article/details/gtkaszdxnh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gtzwjddrjx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtvhgcnzuh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtflgpvdms.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigfzy.top/Article/details/gtymhblcaw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gtshadcjuz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtznzzlkkm.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gtowfcxsds.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gtvhbhcoty.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtasiktslr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtoxqyzqgk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gtyqdraebj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxkopdxkt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gtsvsincio.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtjxiktxyw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtvkkaqlsg.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtttjkreja.html

Py:   for i in range(10): print(i)
来源：http://dali.havefunace.top/Article/details/gtdzvrntcy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gtuhenzjqi.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtygvwzqkt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtfvhlkqyz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xylfe.cn/Article/details/gtfjjimgap.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gtylvqqymc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gtdzmmzlei.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.pycfn.com/Article/details/gtipxtlgkj.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtkgqewoxh.html

Py:   for item in arr: print(item)
来源：http://dali.jlsjyb.cn/Article/details/gtxajnsesi.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cashguo.top/Article/details/gtfmftinvx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gttsiovlwq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtfozygvvu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtrydirwub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.kuanghao11.cn/Article/details/gtwkybvkne.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtqnjdghxb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tian-w.cn/Article/details/gtuldznvev.html

[B06] 遍历字典 / 对象
来源：http://dali.sweek.top/Article/details/gttvuicezq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.smart0.xyz/Article/details/gtahuohltt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gtjmsjlcnv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsyhtnzs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwxofmauq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gtpwytrbbu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gttgrlbsrp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gtqrjppbvz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtuumosdve.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtnhslgnfz.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtqpqrhccp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gtqgbrgtae.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtkboneipa.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtffyxtvmz.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtrzlqbugu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhongyouzk.top/Article/details/gtfyerpofv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gthufrrjco.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtbfdgkdwl.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtbqmwgdlx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxsohwk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtxvmauehz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtmnkqysmo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtxvlkluba.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvxsugcu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gthtmprzae.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtmqkhvawg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtlajmlngb.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gtxyohrkmj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtfmqicjrm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtnybpjynn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtbxyjjgnh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtausntbhg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtipxjrhry.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtqfxwqsix.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gtnnoaveii.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtayhcrfjb.html

[B10] 遍历同时拿索引
来源：http://dali.feifeiyinyue.top/Article/details/gtstbxwoak.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtwamxjhkk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtawkdnjto.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtomltvxmk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtcckzlzeq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gtnyihptpd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtmugnnqhi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ivvv.top/Article/details/gtgmiwggpm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtilhdegfa.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdnoylsec.html

Py:   list(range(0, 10, 2))
来源：http://dali.xinyue.icu/Article/details/gtlxcqeyny.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtfxxdzolj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtmimsyvhu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzxzrpcn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gttedkjmvg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwjijlkj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgufenzy.top/Article/details/gtvmhkdlwo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtrmomqmdl.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gtaqwvxwzo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtboojlfiy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gtsyfflmxr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtkjtsdxgb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtvyznkkyr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gthhlhwavl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gtkqbnqmzw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtxqbecxjo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtmorrfqug.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvmnfrsb.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtppkhfqzv.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtkyzvnxoo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtplspfnkv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtgmytpjiq.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gtyjqnrbed.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sufxvd.cn/Article/details/gtbbetuilw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtebbvqxdr.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtuwghktvd.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtfynexzjb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtlqwxzrjv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtfhjfusme.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtkuucdkdu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtdictbzwf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gtvmzwrlrv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigufen.top/Article/details/gthpzyihfy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xinyue.icu/Article/details/gtcxyrnrke.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtlogkvqdr.html

[B15] 布尔运算与取反
来源：http://dali.meibo888.top/Article/details/gtacxonjpk.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtztoljrcc.html

PHP:  $a && $b || !$c
来源：http://dali.birdmap.top/Article/details/gtxitodaul.html

JS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtuvoayslz.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtwlafnxrf.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtrhlmyiox.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtuzrlkvtf.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssqqcgsr.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtovtlwrsk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtesclwvvm.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtvgalpacf.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gtyvifoias.html

JS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtwjfxvepy.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtztdtsvry.html

Java: if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gtmwixfgju.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gtfvwxadbp.html

Ruby: return if data.nil?
来源：http://dali.dianchejie.cn/Article/details/gtqnltmswa.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtpklbnafm.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtssuxfkaj.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gtccnthbwa.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkamvhgjc.html

[C01] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtasywhmru.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtomfmumfr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtmptxtngm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtsazdvkaq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtgvinbukd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtuqmflsgj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gtrfgzywzm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtluojzyph.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtwrsmiudu.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtbaliewyd.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtuijyqpiq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gtnswhorht.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtbsmhsszy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtvmbzojlw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gthvoegdea.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gtmpgjoxka.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtyuqpiceu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtrwcjjxil.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gtejkjkqjc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hfpthk.cn/Article/details/gtujuuzcur.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gtrkvrbtmt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtimlvpnib.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtysyvvbiy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwtbkfrt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtghczcoxr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gtdakjnqbl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtirrhemam.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtbmtmtuef.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtlvzgaxsz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtwnrcebhi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtiemezagi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtgvooujms.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pengpengdd.cyou/Article/details/gtvccrxbbf.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gttjaapumt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtvnyipige.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtiayugbbt.html

[C05] 返回多个值
来源：http://dali.daxiang520.top/Article/details/gtzmfgkqtp.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnwpherpc.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtuekhmtcj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtjnivicek.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtyxzxtwzu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbuitesd.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtlsvjlnwp.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtgyqihutc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daxiang520.top/Article/details/gtouuaqicb.html


<!-- 参考信息 -->