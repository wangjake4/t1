代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.yuanzhike.top/Article/details/gtcjrisgyu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.xinyue.icu/Article/details/gtbtinwsfg.html

Go:   // 单行；/* 多行 */
来源：http://dali.sxryk.cn/Article/details/gtmnnkhbwr.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.hongshengwenyu.top/Article/details/gttvfbwbeq.html

C#:   // 单行；/* 多行 */
来源：http://dali.hfpthk.cn/Article/details/gtyvwbszzg.html

[A15] 空值判断与默认值
来源：http://dali.jqgufenzy.top/Article/details/gtuayqqkvy.html

Py:   value = data or "默认值"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaslqvso.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtxqciaxoq.html

JS:   const value = data ?? "默认值";
来源：http://dali.xinyue.icu/Article/details/gtzdmcxlqr.html

TS:   const value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtiqxqidwj.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hywenlv.cn/Article/details/gtfczwcdxk.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.gotoacloud.top/Article/details/gtgbdjmcxf.html

Ruby: value = data || "默认值"
来源：http://dali.ehwqpu.com/Article/details/gtlwyoqtdm.html

C#:   var value = data ?? "默认值";
来源：http://dali.havefunace.top/Article/details/gtnljxqecy.html

[A16] 真假值判断规则
来源：http://dali.zhijiandao.cn/Article/details/gtdpbmxuen.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtnzlhtvev.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yueranfly.top/Article/details/gtyxnsojah.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shuidangran.top/Article/details/gtkcbmctkb.html

TS:   if (!x) {}
来源：http://dali.xinyue.icu/Article/details/gtwalmyrau.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.xinyue.icu/Article/details/gtdjlwpumc.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.c1oappe.top/Article/details/gtnsskhfiw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yangfankeji.com/Article/details/gtrigtyzni.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xuanzx.com/Article/details/gtqfbccvui.html

[A17] 位运算
来源：http://dali.gaohongyu789.top/Article/details/gtrivqupww.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtzxwbazpv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yonumen.top/Article/details/gtrtpldqlx.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtekrrlgmx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.xuetiantiany.cn/Article/details/gtqmdvvrci.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtuncxvous.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtxetfyxjr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgufenzy.top/Article/details/gtvjmnlfey.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtoawovywj.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrwczecf.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgufenzy.top/Article/details/gtamhxvlpx.html

PHP:  ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gtleiglfij.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cashguo.top/Article/details/gtotsxygwt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gttivykgem.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtycltthan.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gtrscvfpfi.html

Ruby: "A".ord; 65.chr
来源：http://dali.shanyushiyangtech.top/Article/details/gtguoltjhz.html

C#:   (int)'A'; (char)65
来源：http://dali.9152youxi.cn/Article/details/gtzgfxyhbt.html

[A19] 交换两个变量
来源：http://dali.meibo888.top/Article/details/gtabtbuqgd.html

Py:   a, b = b, a
来源：http://dali.zhiwuduotai.top/Article/details/gtkdtauxyu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.andypj.xyz/Article/details/gtnajtvdow.html

JS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gtlbdfdpsu.html

TS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gtxawpuibh.html

Java: int t = a; a = b; b = t;
来源：http://dali.jlsjyb.cn/Article/details/gtctzljrec.html

Go:   a, b = b, a
来源：http://dali.nanxuanxn.top/Article/details/gtcvypyfuu.html

Ruby: a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtmyucxjtr.html

C#:   (a, b) = (b, a);
来源：http://dali.sxryk.cn/Article/details/gtyujwbovt.html

[A20] 读取标准输入
来源：http://dali.cashguo.top/Article/details/gtdlklyeqr.html

Py:   name = input("请输入：")
来源：http://dali.xziqi.cn/Article/details/gtlfrwznbk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fzhhl.top/Article/details/gtigkawpya.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yangfankeji.com/Article/details/gtruligcrh.html

TS:   // Node.js：readline 模块
来源：http://dali.fengsongda.top/Article/details/gtfzfgjesj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cqqwz.cn/Article/details/gtxsdgmrjx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gtbhevbafg.html

Ruby: gets.chomp
来源：http://dali.sysykeji.top/Article/details/gtsfiswogs.html

C#:   Console.ReadLine();
来源：http://dali.cheryme.top/Article/details/gtiufditmx.html

[A21] 保留指定小数位输出
来源：http://dali.hywenlv.cn/Article/details/gtqarhqtal.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gtdqssovxx.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtyxlhclcb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gtmjnimhud.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtmezurgup.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtfakyripl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtvegrtgnf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtwjbvmupd.html

C#:   3.14159.ToString("F2")
来源：http://dali.hongshengwenyu.top/Article/details/gtnnjxagoy.html

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtpkktptuk.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gtnmtogwim.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gtvyhlwlij.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gtoxfgowov.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gtdvtnicly.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtjetqswmf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nwbrower.top/Article/details/gtddxfkqgc.html

Ruby: s.length
来源：http://dali.sufxvd.cn/Article/details/gtbdoixtdm.html

C#:   s.Length
来源：http://dali.sysykeji.top/Article/details/gtebzggvzr.html

[A23] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtfqnixlru.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.feifeiyinyue.top/Article/details/gthjhncdso.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.316326.xyz/Article/details/gtbuuddavv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnqzz.top/Article/details/gtgjvluzyr.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzplawujk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtoqkyfdbu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shuidangran.top/Article/details/gtaayydtxr.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gtwycwwiro.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shangyingyoupin.top/Article/details/gtvuwuebtw.html

[A24] 去除首尾空白
来源：http://dali.meibo888.top/Article/details/gtmxigstbl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.andypj.xyz/Article/details/gtivivbvff.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanxclsdo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shuidangran.top/Article/details/gtavjrmamx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtphvssqoc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gttndeurny.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gthyrdntqo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxdmjuw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnqzz.top/Article/details/gtnealbnhp.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtwtysqkpm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtrejrstdy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gtdiarzrxl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttotjnlzh.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gttykojkzs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gtrkpsmrvc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gzhubu.top/Article/details/gtpcbttxkx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtsvwfetdq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtamlbnkec.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gttvrzayyv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnvdktmp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gtmpjtmymo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.bjfxy.top/Article/details/gtrasmwgzr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guowangkeji.top/Article/details/gtmaiyvnil.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sufxvd.cn/Article/details/gthsnydmdh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gotoacloud.top/Article/details/gtdlnbgvsd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gtffivihrz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtvxektvin.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtkklzceku.html

B. 流程控制
来源：http://dali.yj202588.top/Article/details/gtpforpkor.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtgdlpusli.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gtxfrfvqei.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtwcdgsebc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jianghu66.top/Article/details/gtcjpuvipu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtoouhrgcl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfprflzw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtsomhkbze.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gtgubopbbi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gtknserahd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtxufuynrr.html

[B02] 多分支 else if / elif
来源：http://dali.cucudq.cn/Article/details/gtkstwgzgs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hammf.cn/Article/details/gthibjcghw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhongyouzk.top/Article/details/gtbtfdvblk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtnvwldoid.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtvpwaeofz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtpduskhmu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtwphpdhlq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gtngmkyjno.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtaryzmjcr.html

[B03] switch / match / case
来源：http://dali.shzxlz.cn/Article/details/gtbhbrlhen.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.316326.xyz/Article/details/gtjqyebsqq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtnjzzyzjy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gttomexvbx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtouzggsbv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gthwegxuri.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtukzccrff.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jlsjyb.cn/Article/details/gthhdbjuyq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtmcssdmro.html

[B04] for 计数循环
来源：http://dali.jqgfzy.top/Article/details/gtaoluzaof.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtsebfhegu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgfzy.top/Article/details/gtjkwcrkbj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtzihuduyj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gttqwkwirj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtetnmasdh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gtyxdzjcic.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtnmviaajc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gthzyfzmcc.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtmnaoixqv.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtomhfhvyb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtiojixynv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtjaeqxwyp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtijydsmxl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gtgdiffbbq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtociftvcl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gtkurzgcdc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.0kj1m.cn/Article/details/gtqgryheal.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtabexlhoo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cucudq.cn/Article/details/gtkoyalded.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtzqoytzxe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtqidcywau.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtgokibsnk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtyhjwlueb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenzaomai.com/Article/details/gtxerghxdw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gtpqzeuwst.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gtstgacuyv.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gteqhxirer.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtdnemyyac.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtjujayuch.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtcoonewbd.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gterywayka.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtelurwxvj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gtsatfrlrd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmdyaiwu.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtzsdwdrdu.html

[B08] do-while（至少执行一次）
来源：http://dali.gotoacloud.top/Article/details/gtgodgzfkm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtdaekcrpo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gticaxgpcv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtdwvqnaae.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gthcnwgwkt.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gthmazwfhz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtbqkpyusw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gtnwxsjmzw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gtcaoxtkhm.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtrhwdewag.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtnninlmjg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigufen.top/Article/details/gtzkcqrckj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtybqnucsq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gttzzzvwuy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtprgyevbo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtwndnsnui.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtlilzufok.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtstfokrbw.html

[B10] 遍历同时拿索引
来源：http://dali.0kj1m.cn/Article/details/gtfoxvofkn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtwgdcpwxd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjdidqsqb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtxpecaocm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtcuvggtam.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtupjjkibp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtjasvbjkm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtybtcdkyi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtzizpgxov.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gtzpgyftwv.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtmvpmhkmp.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtdfzpufvs.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehyjnffn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtmnbnqkbi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.daxiang520.top/Article/details/gtbasqdnmg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtmcecvool.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtzfcruume.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtkdekqdok.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtzbqyfanm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtspqpqvus.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gtnkkukrmr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtjvnbijyc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjllujxb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtwjfwburh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hfpthk.cn/Article/details/gtkwibqmpb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gttwlzzqyg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gtjyylwjrg.html

[B13] 判断是否为数字
来源：http://dali.havefunace.top/Article/details/gtwrmghkai.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtuulprfnr.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gtmofvcuav.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuplgwdev.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtppblmoep.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gteffqzexh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gtbllfihfz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ybcxt.top/Article/details/gtisjvghto.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtdhqvkzmc.html

[B14] 判断值是否在集合内
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzthdnpez.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gtvvxeorpo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtftzueffy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtxsyleluq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtxjdiosbm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gthfawsxis.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yangfankeji.com/Article/details/gtrkadmhbb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtrpahlutk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtyjsolljj.html

[B15] 布尔运算与取反
来源：http://dali.tian-w.cn/Article/details/gtppcezktt.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtxxwjijek.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtekseoaet.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtvosdithu.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtoiomhifa.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfskqzwwm.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtcbohvjzy.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtglhmrkyj.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtkdocybwr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtvygmckkg.html

Py:   if not data: return
来源：http://dali.cqqwz.cn/Article/details/gtxqhkqjbz.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gtkcdbxemv.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtbnyvxkyt.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorycrisu.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtydrtinwx.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtcatjkrmk.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtgluttnul.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtretlicxx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtynnxohts.html

C. 函数与作用域
来源：http://dali.nanxuanxn.top/Article/details/gtkkabgfft.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtccctqtuq.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtndoyvtmf.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtmgseitjq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtmkifmzne.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhcsfdpg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtdqsuklch.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtqwiwqeol.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtstyzfpcw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtrumuegoz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtuurnkqfd.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gtvjfowuka.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtlezagkry.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxvndyrep.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyrzsmzm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtqzjfbcug.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gtigkexzor.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtxrdftykq.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gttnbcfufy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhixingplan.top/Article/details/gtpnlqtgmw.html

[C03] 可变参数
来源：http://dali.yanxiufei.cn/Article/details/gtlhnlbyjw.html

Py:   def total(*args): return sum(args)
来源：http://dali.redwolf501.top/Article/details/gtxyeluipu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gtgmruinyv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtcrcpuuyh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.redwolf501.top/Article/details/gtsmwhjaxr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtwmxdmrlr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtxnpsvrug.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtnigunuyw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gthympvcxw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtpugfpoun.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxinkj.top/Article/details/gttjntikol.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtudsbpqzj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtvvjguqfg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gthuvahnfz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtqfrblrsr.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtldxweieg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtzvecyqss.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtisejwieq.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtvksvroaq.html


<!-- 参考信息 -->