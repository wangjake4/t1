代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtcjrwpxdo.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xinyue.icu/Article/details/gtrrixhgpq.html

Go:   // 单行；/* 多行 */
来源：http://dali.shuidangran.top/Article/details/gtlwevikfa.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yj20258.top/Article/details/gtupuqtpnw.html

C#:   // 单行；/* 多行 */
来源：http://dali.cucudq.cn/Article/details/gtsaohhhpz.html

[A15] 空值判断与默认值
来源：http://dali.xuanzx.com/Article/details/gtbiekyfqa.html

Py:   value = data or "默认值"
来源：http://dali.sxryk.cn/Article/details/gtgmyigjmr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtcitverci.html

JS:   const value = data ?? "默认值";
来源：http://dali.hnxiangtu.top/Article/details/gtkbkrigwm.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsxnybqt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zdqjudy.top/Article/details/gtxjzfsaye.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.iojbl.cn/Article/details/gteanwgqyy.html

Ruby: value = data || "默认值"
来源：http://dali.dashuyun.cn/Article/details/gtpwhtbfhd.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxiuaikk.html

[A16] 真假值判断规则
来源：http://dali.svipenyu.cn/Article/details/gtyftcqydp.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtieqdvuqm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhengqikj.top/Article/details/gtxbshsvim.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gtomrqoqay.html

TS:   if (!x) {}
来源：http://dali.shuidangran.top/Article/details/gtcmiiqaex.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jiagoushi.top/Article/details/gtofuopzuo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtuowkcwoq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuxming.cn/Article/details/gtzjicndta.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258.top/Article/details/gtzjetqmah.html

[A17] 位运算
来源：http://dali.smart0.xyz/Article/details/gtmnkrxxhj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtlibwqtlv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xuanzx.com/Article/details/gtocryjmcd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtrfrcpclg.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtyjezawmq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtfueczziq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtshpjhbhf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtnebhhmjo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtbmdtlcew.html

[A18] 字符与 ASCII 码互转
来源：http://dali.9152youxi.cn/Article/details/gtwbdvblbw.html

Py:   ord("A"); chr(65)
来源：http://dali.tian-w.cn/Article/details/gthwbmducm.html

PHP:  ord("A"); chr(65)
来源：http://dali.sxryk.cn/Article/details/gtqcjqbnye.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fzhhl.top/Article/details/gtchyqtfqw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiqolqbi.html

Java: (int) 'A'; (char) 65
来源：http://dali.sweek.top/Article/details/gtozlidhzb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ydzc1.top/Article/details/gtpjjtkcxr.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gtwgirhhbb.html

C#:   (int)'A'; (char)65
来源：http://dali.daxiang520.top/Article/details/gtcdygjssq.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gtsploupnc.html

Py:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtnzdlhwpr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.xuanzx.com/Article/details/gtqaeytcti.html

JS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gtocgkyvzb.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtykhiwahs.html

Java: int t = a; a = b; b = t;
来源：http://dali.yuanzhike.top/Article/details/gtwzaoeiic.html

Go:   a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtobgloywm.html

Ruby: a, b = b, a
来源：http://dali.jqgufenzy.top/Article/details/gtjjhplili.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtzxynixhx.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gtccccucng.html

Py:   name = input("请输入：")
来源：http://dali.meibo888.top/Article/details/gtzwfkqobr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shangyingyoupin.top/Article/details/gtsokyahqi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hammf.cn/Article/details/gtwubtpdui.html

TS:   // Node.js：readline 模块
来源：http://dali.gotoacloud.top/Article/details/gtlrmoimwi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yonumen.top/Article/details/gtmhancwps.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hywenlv.cn/Article/details/gtafuxgibw.html

Ruby: gets.chomp
来源：http://dali.zhijiandao.cn/Article/details/gtfrfwgxdr.html

C#:   Console.ReadLine();
来源：http://dali.gzhubu.top/Article/details/gtcnrjjpna.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gtncdysvzj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tanke756.top/Article/details/gtdduriqpz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtwhefiqdq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtxenpqhxt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gtkvvwslvk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtrsemcnuc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gtnbzdssuu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtignrmwcl.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhijiandao.cn/Article/details/gtkumodwaz.html

[A22] 获取字符串长度
来源：http://dali.redwolf501.top/Article/details/gtottjrikf.html

Py:   len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyigdqmmr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jyoumei.cn/Article/details/gtzqobfqpl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.fzhhl.top/Article/details/gtkmgniuvp.html

TS:   s.length
来源：http://dali.jinqigfzy.top/Article/details/gtfkxkpjmf.html

Java: s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtxzrzzkoj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gtyolhbpbo.html

Ruby: s.length
来源：http://dali.hammf.cn/Article/details/gtmiopfbqx.html

C#:   s.Length
来源：http://dali.tian-w.cn/Article/details/gtsgvksitc.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gthamzckte.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtetkratxv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gtyiyuvjzs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gtxaaqrkcv.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtbszzjkbw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtyulfpyof.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gtoyuzmqor.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnxiangtu.top/Article/details/gtrhtsvaol.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gthaukusdb.html

[A24] 去除首尾空白
来源：http://dali.zycfv.cn/Article/details/gtalxzjfho.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtjghfflsb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtuabqzzbo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtyzyhdsee.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtfupxbsps.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gttbhcwznl.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtrykovzmd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtpoouqaay.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahvukrno.html

[A25] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtubvdibna.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuanzx.com/Article/details/gtfxrnagpy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgfzy.top/Article/details/gtecflging.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtvukyhawo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtjjtiuaei.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.bjfxy.top/Article/details/gteotdmobw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jyoumei.cn/Article/details/gtfeicftaq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.sufxvd.cn/Article/details/gtkjlapnjc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.feifeiyinyue.top/Article/details/gteppqzwsu.html

[A26] 类型转换总览
来源：http://dali.havefunace.top/Article/details/gtdticpfme.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfqdiepn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.0kj1m.cn/Article/details/gtqawfsbrv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.mhx1999.top/Article/details/gtmfaogjqf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gtfqgeffch.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtjxjitskq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gtwfsmdzcp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gtjcbjewpy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yonumen.top/Article/details/gtqeppdvsp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtvfaqlzro.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtqksnquzi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrtjsvhag.html

[B01] 条件判断 if / else
来源：http://dali.quarkkingdee.top/Article/details/gtdptphcyf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtmodikppd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtlqpdyycd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtukzkwqfy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtvihzoluv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gtaindnnox.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jlsjyb.cn/Article/details/gtfonvirlr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cqqwz.cn/Article/details/gtxehvrfzl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtqwdofozy.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gtmkinozxt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xziqi.cn/Article/details/gtiatxxrdl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hammf.cn/Article/details/gthnhayxyd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtbwqcyxqu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gtprciwjif.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovgfcfhe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuanzhike.top/Article/details/gtjzgjqcll.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cheryme.top/Article/details/gtnqkemhjh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsykhhwd.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gtahltfgwa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cqqwz.cn/Article/details/gtgrzqeotg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtridetuof.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtppeakiqq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtjgybybjz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtxzvjgani.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gtylidxzwz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnmhuykm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtqyrjahoj.html

[B04] for 计数循环
来源：http://dali.yanxiufei.cn/Article/details/gtnnxipthd.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtlswqoswa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhoulong.xyz/Article/details/gtgsfgimkq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gtajjpbyyu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gthyuriyqb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gtvuejtots.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhoulong.xyz/Article/details/gtijvgcbjm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tian-w.cn/Article/details/gtwobpzlen.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zycfv.cn/Article/details/gtoivdmafl.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtjsabpqqu.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtxocijoha.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gtcielxrif.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtfzhjeoly.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtawbkhfzt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gtgakzywqq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhixingplan.top/Article/details/gthjgjepvi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gtrsatuski.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtadyjmafq.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtydgqagwd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gttayeyqvp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xylfe.cn/Article/details/gtdzhopjda.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtghukihuo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtymatgjjv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtacgzcnlx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtkkgrhymz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtdzbzcaig.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtbzuniknu.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gtetfuuqqb.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtnccmilio.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtgchksutr.html

JS:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtlnkmfaah.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtvtwuvqvq.html

Java: while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtrqsxpwvw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gtenaqfunw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtxnvzlqgo.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtotbaocam.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtfpgbenht.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gtblqffxpj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gtclszvqmi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzgrrlill.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnfsfpeg.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtoorqxyrn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvrtknxlv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gtgdtkdqju.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gtdcezaema.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtpqjdubpz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gotoacloud.top/Article/details/gtmpgrvfmb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtlryhcpua.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgayluzrs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtsqafkovu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtorxmoqtt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.mhx1999.top/Article/details/gtdfxkfxzg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtohylmmdb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtodfncagw.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigfzy.top/Article/details/gtiqtytxfv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gtpfacenda.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtgvnefzwo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtievfxpio.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtzrahbjps.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ehwqpu.com/Article/details/gtppnyxtht.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtsbfhcgao.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gtvuupwwov.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cqqwz.cn/Article/details/gttvbxywdo.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gtjimnrbta.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtbvdwgnie.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdlkuikq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtyuuvqvvq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtzlejwerx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtiqggdaxk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtizytvayz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gtqlcqtogl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jyoumei.cn/Article/details/gtarosnamg.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gtmhtzxiuk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtavbxlubm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezovxsfc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtkgmkgupi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtgtfcfpfo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsiinfxw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gtbnflatov.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtspqvsoja.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gzhubu.top/Article/details/gtzcosubhg.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtswxyrceu.html

Py:   isinstance(x, (int, float))
来源：http://dali.mhx1999.top/Article/details/gteuxycoap.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtmygjgaqp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtlqjnjrgs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtzsuimmgs.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtpwsvbrjg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gtxwiffumb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtbtttrxex.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gtlblvdyjf.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtbbjriexp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhengqikj.top/Article/details/gtwmhhxbgi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtskxmftut.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtawsqaldt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.haohaochexian.top/Article/details/gtaxwvqzgn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnqzz.top/Article/details/gtxlmpahff.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtkqkjqpqu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gterlmlfin.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlyrnaoeo.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtwwvpcdcf.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gtfzgpybet.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtvimwvnxc.html

JS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtbclcalcm.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtynancomq.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtkcywfpvo.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtshzrplvp.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtoyfzvcaq.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgywxifw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtjrhmdrzy.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtphfsgruu.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtpsbtyjbq.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtgiqhnrxc.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtooumizez.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gttwylhivq.html

Go:   if data == nil { return }
来源：http://dali.shzxlz.cn/Article/details/gtwdwrnnrk.html

Ruby: return if data.nil?
来源：http://dali.gotoacloud.top/Article/details/gttlvwomgj.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtunesjams.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtdaoucl.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtcxppydqe.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtzqhafdeb.html

[C01] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtirzjtwlj.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtsdoausls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gteyxbcrhz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtqxbdemrr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbuinnslz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtdfwjegkw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gterpsoikg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtdxsfrnws.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtstmqkafg.html

[C02] 默认参数
来源：http://dali.hammf.cn/Article/details/gtrzwxicqe.html

Py:   def greet(name="World"): return name
来源：http://dali.cqqwz.cn/Article/details/gtkmyovtdc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagcdklcs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtfjfftccy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtgxcwzvoy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtoqxasyke.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtlbfwvaoy.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtlhmfdnbs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtnikkhlsd.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gtglyejyyh.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtddmvnfyd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtxmszuefg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtdubgxssu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtxmjljdei.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dianchejie.cn/Article/details/gtxhiullja.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtknbakeet.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtnpizcwmv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.birdmap.top/Article/details/gtczrxlplz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtmgxqhhna.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtocatrxfe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtdxmszhji.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwelwvgar.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yueranfly.top/Article/details/gtmqzbfujf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gtgaqqywkp.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtskflxomi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtiilcsuee.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtraeelojo.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtrecikxdd.html


<!-- 参考信息 -->