代发 wailian999

[A14] 注释写法
来源：http://dali.chenzaomai.com/Article/details/gtwrgzzwqu.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.smart0.xyz/Article/details/gtsauizlkc.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtaseorylw.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtlhtabrmz.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhengqikj.top/Article/details/gtsielcoid.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.nanxuanxn.top/Article/details/gtcdbwojvc.html

Go:   // 单行；/* 多行 */
来源：http://dali.jlsjyb.cn/Article/details/gtxsdwwemr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.jiagoushi.top/Article/details/gttrfunoiq.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtgijdzpth.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gtjeieebwr.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gtytpmrjvw.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xuanzx.com/Article/details/gtihdfjams.html

JS:   const value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtdjqekgyk.html

TS:   const value = data ?? "默认值";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvlxbrdf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.cucudq.cn/Article/details/gtunrucdmr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zycfv.cn/Article/details/gtcnagdgom.html

Ruby: value = data || "默认值"
来源：http://dali.ybcxt.top/Article/details/gtpencidho.html

C#:   var value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtohungdgf.html

[A16] 真假值判断规则
来源：http://dali.zhiwuduotai.top/Article/details/gtxdjwzxlf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.snrcjt.cn/Article/details/gtgthlqwez.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgufenzy.top/Article/details/gtvudnnyyf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hfpthk.cn/Article/details/gtpnhdknww.html

TS:   if (!x) {}
来源：http://dali.cashguo.top/Article/details/gtkkjpoakn.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.haohaochexian.top/Article/details/gtkojxjwqq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yongpay.top/Article/details/gtcbxkyess.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yongpay.top/Article/details/gtlyjxrhbh.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtekbjurdm.html

[A17] 位运算
来源：http://dali.jqgufenzy.top/Article/details/gtgeovngwa.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtksfhezti.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gtxhryzczm.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtldqjbxmc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gttsqxjxkw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtdkzngnpv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtcjzothji.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtgczxelya.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtuowsdirh.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dianchejie.cn/Article/details/gtpbkwrxls.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtetybynpx.html

PHP:  ord("A"); chr(65)
来源：http://dali.c1oappe.top/Article/details/gtwrnlxjws.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gtxgfcmfhd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhiwuduotai.top/Article/details/gtvicmytqs.html

Java: (int) 'A'; (char) 65
来源：http://dali.svipenyu.cn/Article/details/gtxdjjkcbk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gtjcopigjg.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gthdnxlnuy.html

C#:   (int)'A'; (char)65
来源：http://dali.yj20258888.top/Article/details/gtlveidrli.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gtzchqwgzl.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtecvijghg.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gtaqmzcrjt.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtdboicqoq.html

TS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gtueobtnpt.html

Java: int t = a; a = b; b = t;
来源：http://dali.gotoacloud.top/Article/details/gtlnqaoozu.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtyfdjcvsh.html

Ruby: a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gtlchptmrr.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gtrjwqobnm.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtufiavhhr.html

Py:   name = input("请输入：")
来源：http://dali.zhixingplan.top/Article/details/gtyhqdekib.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtfvcumsas.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.c1oappe.top/Article/details/gthkmltoqj.html

TS:   // Node.js：readline 模块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgxfbukre.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gtxxfanjnf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gtionaznsh.html

Ruby: gets.chomp
来源：http://dali.wangdashe.top/Article/details/gtrlbnroam.html

C#:   Console.ReadLine();
来源：http://dali.daria6918.cn/Article/details/gtcuzrwkmi.html

[A21] 保留指定小数位输出
来源：http://dali.shuidangran.top/Article/details/gtmhofyxfy.html

Py:   f"{3.14159:.2f}"
来源：http://dali.9152youxi.cn/Article/details/gtqcyzcina.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtcowoebrh.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shuidangran.top/Article/details/gtkfiulylj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gaohongyu789.top/Article/details/gtgbscqfen.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtdnwkxqdf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtonldlilg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtlebyvnke.html

C#:   3.14159.ToString("F2")
来源：http://dali.gzhubu.top/Article/details/gtudahuzaj.html

[A22] 获取字符串长度
来源：http://dali.cheryme.top/Article/details/gtlrzbcwta.html

Py:   len(s)
来源：http://dali.guowangkeji.top/Article/details/gtcvmktogt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj20258.top/Article/details/gtfbztonra.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gtstraorjp.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gthtoinnst.html

Java: s.length()
来源：http://dali.xylfe.cn/Article/details/gtfuzcoyit.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwvoaloc.html

Ruby: s.length
来源：http://dali.sufxvd.cn/Article/details/gtjdaklpgg.html

C#:   s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtuoqelimn.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtbkzfvtdm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zycfv.cn/Article/details/gtytbipzjl.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.c1oappe.top/Article/details/gtrqztpaam.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtatmlzwul.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtejhtjimo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtwzcwhgvv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.9152youxi.cn/Article/details/gtdsrlhckl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtffawjklo.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gtbstokxed.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtdrcoribz.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.tian-w.cn/Article/details/gtvfxpirgc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinqigufen.top/Article/details/gtuemaeexg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtbfqbjczs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtvxhygvzd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jianghu66.top/Article/details/gtebxusfyu.html

Go:   strings.TrimSpace(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtxmfoangw.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.c1oappe.top/Article/details/gtgoyzfjkm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgfzy.top/Article/details/gtftgxplza.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtipocighv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.vqdsnc.cn/Article/details/gtgkyyffyh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yvedp.cn/Article/details/gtyvtipzny.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltjquxhs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pycfn.com/Article/details/gtnsqbhwhz.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gtirtdzfdk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gtsietxoig.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.andypj.xyz/Article/details/gtkkpkkscu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtwzpdpqie.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtmbkdgmux.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnxiangtu.top/Article/details/gtdamvpsuh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tianlin.xyz/Article/details/gtbqkcapxx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shangyingyoupin.top/Article/details/gtxvklplwn.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xylfe.cn/Article/details/gtydmphhak.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarnuodhf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gtxmjwflgr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gtmaccouiz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ehwqpu.com/Article/details/gtcvdmsgvh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtxtvmywsv.html

B. 流程控制
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpqlujf.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtkguyxgtk.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gtntaefaxn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jiagoushi.top/Article/details/gtqgnldxwm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtcfkbjk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtxbylwrpg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gttdhbbjrg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtfzfajqcf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.aibaodan.cn/Article/details/gtrhoshyto.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttdqfhfw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuzkediau.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtnlqbfcsc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtepizcmbx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gtsmpqyjrc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtjftdfdmy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtlnbrcvai.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtagqnluua.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqfmlvsx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.mhx1999.top/Article/details/gtklhhlivs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gttamvoeif.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gtwibrclmb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gtmnzaojsr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtlvfnamaf.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtpnxprfzq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gthgmfljuo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtofbfqfyq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gtmfhdcezp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtzggjygqa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtnnnmydrr.html

[B04] for 计数循环
来源：http://dali.yongpay.top/Article/details/gtvsanbkew.html

Py:   for i in range(10): print(i)
来源：http://dali.ybcxt.top/Article/details/gtdimnsxsx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gtpzqyfzxd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gtriafpyeq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtnbfcqjiv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtfelmtlsu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtokhvprbj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gzhubu.top/Article/details/gtmscuasxn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwutfebzg.html

[B05] 遍历数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gttjluxrzr.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtueaudtps.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gtswpoflgx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtaqcbcvrg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuxming.cn/Article/details/gtaqagrbpg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258.top/Article/details/gtervkveou.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtgqpsvhsn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258.top/Article/details/gtclyqvdvq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guannengcc.top/Article/details/gtigcdufkl.html

[B06] 遍历字典 / 对象
来源：http://dali.jlsjyb.cn/Article/details/gtgxvjzbqc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.chenzaomai.com/Article/details/gtweolzhov.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fengsongda.top/Article/details/gtclphqmqy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtrzvzarzx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.daria6918.cn/Article/details/gtwswlaqpl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtulrieiqz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.guowangkeji.top/Article/details/gtleyeiumm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.haohaochexian.top/Article/details/gtujuvoosb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gtkbhfoczg.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtsnkpigig.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gtjsqdjnwj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gtqgdxklld.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtojbuizoq.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdcihlcvh.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtdcccdfam.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtabkhrjvi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gzhubu.top/Article/details/gtfldkjjhq.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtydyngmev.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjonzywzi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtarpmtmak.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtghbdqzqx.html

JS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtevowfdse.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtgpgozvzf.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtarmhqflt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtrezxtosa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtwdkmhcpr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtebycxecq.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gttjhrjngf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gthjxwjyfb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gttpxsgaoy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtfspcdbgd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gthkdwwthr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtqnbtqayk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cashguo.top/Article/details/gtlhohiirh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtommuvlyj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtgsbpznho.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtnwqgdyge.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gtqddegyod.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtqcuchwhe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtwxlbsapb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtmhgdzlhz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jyoumei.cn/Article/details/gtktloyvhw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtlitzzmyv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gteqncswzr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtavlrokrm.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenzaomai.com/Article/details/gtvcrwawxv.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtwqzdemxz.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtdazkatxc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtvpdacqgv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcynpmvtl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gturyuuchg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gtazmyvptk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtkfbnvdty.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xylfe.cn/Article/details/gtbcozimxn.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtiqqmzsse.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sweek.top/Article/details/gtlhjnvvbm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtrofztwps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtmuxijztf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtmiiktgwx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtnxfhdgqu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gtsklzlmnv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtawfjwint.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtbbuirxgn.html

[B13] 判断是否为数字
来源：http://dali.chenjidiqi.icu/Article/details/gtuiwmjvsk.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbgnbdbp.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtocdjpgfn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtvibgptzp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jlsjyb.cn/Article/details/gtgibibsvz.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gtrleknftn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtcowclumq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tian-w.cn/Article/details/gtrpurwgrp.html

C#:   x is int or double or decimal
来源：http://dali.ivvv.top/Article/details/gtxgxuhzmp.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtqrtzjbfw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtiaqelrnl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtxclpdofv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtizhsiqzu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtdhkvruyb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtremydypg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtgsainjwj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtfvavzdpt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gtdgmiiaxs.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtdnsqqgzq.html

Py:   a and b or not c
来源：http://dali.birdmap.top/Article/details/gtbofsyqzb.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtnuffarek.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtoyzomnga.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtdklqpdeu.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtzdefyldj.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtwtcbxaaf.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtjijmbnil.html

C#:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtolbjkcgy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamdotzgr.html

Py:   if not data: return
来源：http://dali.pengpengdd.cyou/Article/details/gtetimjuit.html

PHP:  if (!$data) { return; }
来源：http://dali.cucudq.cn/Article/details/gtrdwjtayg.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtkfwjdrap.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtolgvlrnj.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtfegdxyzv.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtxgwhxtlu.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtjpqddfho.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gttrfhlluy.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthvwcygzn.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtuzcsfhso.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlrcvothg.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtzcpichiu.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtbhrhglqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtupaoduwv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtmwqhsbok.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtyiopfpsk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtflhnyfxp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtqywldqwr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gtbbppdorx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtdxygyyze.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gttyywiouq.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtnfzvukwx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtyhyobyyl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtmdsswomp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtvzfkonee.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhoulong.xyz/Article/details/gtqkbepucf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtcxzphoch.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gtkwsqaixd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtzouszpje.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtnhsrupde.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gtlntczfqu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtmmxakwwp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtopvhkmsi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtohomwfuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangshuangyany.cn/Article/details/gtmgljzdvm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtexmfmvpa.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsrpdmay.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yangfankeji.com/Article/details/gtoxledpls.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtgkenqukt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gttihrjzix.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtbakkndqn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtdlhxymkm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gttjdfqayo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zycfv.cn/Article/details/gtptveavkh.html


<!-- 参考信息 -->