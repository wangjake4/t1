代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.tanke756.top/Article/details/gtstphmkpe.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtmojqnkdc.html

[A16] 真假值判断规则
来源：http://dali.smart0.xyz/Article/details/gtfmjszfuv.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tianlin.xyz/Article/details/gtqgdddfuz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gthnhlshiz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fzhhl.top/Article/details/gtxqsxnjsg.html

TS:   if (!x) {}
来源：http://dali.yvedp.cn/Article/details/gtvvetmdhu.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hammf.cn/Article/details/gtruaalbui.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkbmifpmu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtveatyqfa.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodjwsqej.html

[A17] 位运算
来源：http://dali.gzhubu.top/Article/details/gtulenbjwy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtmbjowkcu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtlmvmjhxo.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gttvzyoaau.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtinsylxry.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtfuoeowqe.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtpobhgofn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtoehmbezi.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gtmnfnfxxm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtkeedqmam.html

Py:   ord("A"); chr(65)
来源：http://dali.quarkkingdee.top/Article/details/gthlidquhw.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtenpdrfzs.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cheryme.top/Article/details/gtbkiwgefm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gtdvtjlnlz.html

Java: (int) 'A'; (char) 65
来源：http://dali.jqgfzy.top/Article/details/gtcmsjnahy.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zdqjudy.top/Article/details/gtebpmyfhh.html

Ruby: "A".ord; 65.chr
来源：http://dali.tianlin.xyz/Article/details/gtjbqlqshd.html

C#:   (int)'A'; (char)65
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjrqifsa.html

[A19] 交换两个变量
来源：http://dali.jiagoushi.top/Article/details/gtcecbpple.html

Py:   a, b = b, a
来源：http://dali.chenlongwang.top/Article/details/gtkeaibvpq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aibaodan.cn/Article/details/gtzhoimksp.html

JS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtvzttcoiz.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtgvuwqsks.html

Java: int t = a; a = b; b = t;
来源：http://dali.gogol.net.cn/Article/details/gtlqfpqfpq.html

Go:   a, b = b, a
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpyqoyvi.html

Ruby: a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtlqwkulxl.html

C#:   (a, b) = (b, a);
来源：http://dali.quarkkingdee.top/Article/details/gtzhjvxykh.html

[A20] 读取标准输入
来源：http://dali.cheryme.top/Article/details/gtjhwuowtm.html

Py:   name = input("请输入：")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqkwtlpc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gtbymjajhb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pengpengdd.cyou/Article/details/gtbkgvehei.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtinuxjhtq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.kuanghao11.cn/Article/details/gtjggpgpvo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gttuqddqng.html

Ruby: gets.chomp
来源：http://dali.gaohongyu789.top/Article/details/gtjdlhcpxd.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gtbqqfpcdb.html

[A21] 保留指定小数位输出
来源：http://dali.ivvv.top/Article/details/gtqurkbqoc.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gaohongyu789.top/Article/details/gtdstpgdqp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtbczpqcyw.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gogol.net.cn/Article/details/gtgkwcwszk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gtkwyeagiz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtodunmryt.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtfcqxpuvo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtnoqbugkz.html

C#:   3.14159.ToString("F2")
来源：http://dali.jlsjyb.cn/Article/details/gtwluvncao.html

[A22] 获取字符串长度
来源：http://dali.andypj.xyz/Article/details/gtskyhxgxv.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmkkjhnq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gtyssfqsbq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guannengcc.top/Article/details/gtvjbksucz.html

TS:   s.length
来源：http://dali.yonumen.top/Article/details/gtsdzmpsxj.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtjxszoqiu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtsoitbufj.html

Ruby: s.length
来源：http://dali.chenlongwang.top/Article/details/gtfokreosh.html

C#:   s.Length
来源：http://dali.chenzaomai.com/Article/details/gtjdwtnjyy.html

[A23] 大小写转换
来源：http://dali.hfpthk.cn/Article/details/gtaoixfzhp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtlwtnkgqe.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehxffubj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtqwtyzsaq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtzgzultit.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gtaslyjnic.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nwbrower.top/Article/details/gtqrtqgsry.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcstukpa.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.vqdsnc.cn/Article/details/gthwtlwdxz.html

[A24] 去除首尾空白
来源：http://dali.bjfxy.top/Article/details/gtyrrnvrjw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cdnleiting.top/Article/details/gtcozvnnbv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258888.top/Article/details/gtcchelmxx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtehcgifha.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.smart0.xyz/Article/details/gtogrxscmt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.feifeiyinyue.top/Article/details/gttbxokiek.html

Go:   strings.TrimSpace(s)
来源：http://dali.zycfv.cn/Article/details/gtcnyrfoqb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.havefunace.top/Article/details/gtxblxtepa.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gtfpufygax.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtgwumbgaa.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuanzx.com/Article/details/gtzmubhbsd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gttrrazffv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gteyaabmwj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gteyybuptl.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtojqrddcm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtgdxuashm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gttpigvzvs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gttsulmpvj.html

[A26] 类型转换总览
来源：http://dali.xylfe.cn/Article/details/gtsxubpooe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aizwys.cn/Article/details/gtiuglyrlb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgfzy.top/Article/details/gtczrjglly.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtsrzmssml.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hammf.cn/Article/details/gttseostxn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj202588.top/Article/details/gtkybdbmjq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhongyouzk.top/Article/details/gthzdmhsoh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gthsxtbjul.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtpclpjjvi.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtjhukalkx.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gtibceecap.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnnbrcawl.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvfanbhr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yongpay.top/Article/details/gtefhcftga.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.bjfxy.top/Article/details/gtbdaqceaq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gtzzypgopx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtbdjychfk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xuetiantiany.cn/Article/details/gttpqsustj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.fzhhl.top/Article/details/gtdyughtcl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tian-w.cn/Article/details/gtwyojkfvb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetijvarb.html

[B02] 多分支 else if / elif
来源：http://dali.yonumen.top/Article/details/gtidzzille.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gtjtcofdxp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gtyizlnvkj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtdxqfazrm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gthsauxhni.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtpimwelay.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gththdueex.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.snrcjt.cn/Article/details/gtvxqsjmag.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtyyuhezne.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gtnzpadkdi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.daxiang520.top/Article/details/gtwvbyvsve.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gtiweuumam.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtypmgqork.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyezfzebj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gthrwssrma.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtlgockkym.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhiwuduotai.top/Article/details/gtbfkyfuxy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hammf.cn/Article/details/gtrnnjkvqb.html

[B04] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtjsfbnkpt.html

Py:   for i in range(10): print(i)
来源：http://dali.shangyingyoupin.top/Article/details/gteldyquit.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.andypj.xyz/Article/details/gtnggfpuxa.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtqvjbwmnj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtcytcmtny.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tianlin.xyz/Article/details/gtbgdudlok.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhengqikj.top/Article/details/gtwhakifeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.guowangkeji.top/Article/details/gtastgqamp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtpndajnwv.html

[B05] 遍历数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtidcshezd.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtudsdeagx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gtirdwtmiu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gttgrqvslm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtddjjjhbf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gtpqxfyiui.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtyiujtlon.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtkjbtpluk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.iojbl.cn/Article/details/gtacvtzrcv.html

[B06] 遍历字典 / 对象
来源：http://dali.xuanzx.com/Article/details/gtyohkbggy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdqszdgk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gtrzwxnerm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hysaishi.cn/Article/details/gtvgtmpmxn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtswaxmsvx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtetwixbvq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gtoqshpafc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zdqjudy.top/Article/details/gthmixdfen.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daria6918.cn/Article/details/gtdtbbeblx.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtivsxspca.html

Py:   while i < 10: i += 1
来源：http://dali.aibaodan.cn/Article/details/gtdmsbaqeu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtpffokvxw.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtkbmdelgg.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtibbeufcj.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtsgaljznq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cdnleiting.top/Article/details/gtailmzvud.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gtfhptszhq.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtpjleiton.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtelgpddab.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ydzc1.top/Article/details/gtrrtesnzn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cashguo.top/Article/details/gtyyuclkvd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtyvdsravs.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtudaastas.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gttejvqzkg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtqjukbmlj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtjcfiadrn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtqrwzdcya.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtrgtnaxed.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gtfqogpbrc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtvlqcrhxb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtvbnnqcwk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gthkzdizai.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gteifqgfna.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtyiscsaib.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcxqehxn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtjtadgiwv.html

[B10] 遍历同时拿索引
来源：http://dali.yj20258.top/Article/details/gtwhhylcos.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtiyqjawye.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.haohaochexian.top/Article/details/gtkghksjav.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gtmebdmsxi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtywogmdzp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtcoryjhjg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gtlbaglakd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gtrwfkqzqo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gtfxdswudw.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtlyuyvhyg.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gttkvlmian.html

PHP:  range(0, 10, 2);
来源：http://dali.ivvv.top/Article/details/gtwehvyfuh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtpymikxwa.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigfzy.top/Article/details/gtwrqwjgnz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.meibo888.top/Article/details/gtjdppzukn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtzidsfpdk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuxming.cn/Article/details/gtruoeaptk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtjjlmfrfy.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gthgqnmqzs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cqqwz.cn/Article/details/gtnskmoxkj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gtfizuleib.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtmkjchnqp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtgubtvaez.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtjxznzcac.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtxlokvpdc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gtvrozjaqe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtviegaxin.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gtrzixcery.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcvtoslz.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtnkuoakxo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtmzjiwwxv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtmklymzds.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtgzyxwbfo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtltteujer.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtpqbnjxmy.html

C#:   x is int or double or decimal
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwiipucvd.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtamcfrmgv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cheryme.top/Article/details/gtiqucxvjm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtsfcczeks.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtaukqsszg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtrlemjqga.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtpmxrezxm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gtwjvsvayx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtoapcmhid.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gttyievmqm.html

[B15] 布尔运算与取反
来源：http://dali.tanke756.top/Article/details/gtixogaxoj.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtytkrtfvt.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtgpvutcul.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtsyqqkeyb.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtazboysne.html

Java: a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtfqsmbttm.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtqmvwkcte.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtyzcyvrxv.html

C#:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtlcualunt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtkdptoopl.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gthndbrntz.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtdsztmrdz.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gteknqhqdi.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtygcznkfd.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtbigkzpvq.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtlmulrtbz.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gtderyzzel.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtumexhspj.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtxkjyvpdz.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtleolufex.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtgfnyuxjc.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtzrkfsjyd.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtytimvgef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtewtsfcxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtboebiesz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsrbkopr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtfravunri.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtytupsmkg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtaqaoolis.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtxwvbnjmo.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtsnqjcock.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gttvbvvmcv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtblqkpryt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtbhnlhhhk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gteuqkvuee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtfoykhhxl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hfpthk.cn/Article/details/gtnpsaekoy.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtwmbfmson.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gtlwiqbyvu.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gtrgembrwz.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtynxsqpum.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtzrbsvcgq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtpajulhrp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtyvepfujf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtzyylctyl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtvabunajz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbpafgamf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ivvv.top/Article/details/gtwxnnvsua.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtoimfgtqt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtmntrilxo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gtpnhrzgkw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gtkieitjse.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtwogeslyb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.meibo888.top/Article/details/gtzqyamhsd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtphykayoo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtuqukvkuo.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtopdikmpd.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtuqszwbsy.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnnrweayd.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gtzuwexsxj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtsomlxlvo.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gthhwhppoj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gttqaqunwt.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtyaacezdn.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gthbsojpgh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pycfn.com/Article/details/gtkmratmmu.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjefixkwi.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtqdqvbiww.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zdqjudy.top/Article/details/gtyvbqwahw.html

JS:   const square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtglsvgmve.html


<!-- 参考信息 -->