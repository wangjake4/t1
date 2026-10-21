代发 wailian999

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnynishwv.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gtthrfrbod.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gtjfjnoshu.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpqhnbnip.html

TS:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtduxwlyty.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.pengpengdd.cyou/Article/details/gtplbvgmxq.html

Go:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtffyudftu.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.0kj1m.cn/Article/details/gtwkfuhbhv.html

C#:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtiogwrskz.html

[A15] 空值判断与默认值
来源：http://dali.wangdashe.top/Article/details/gtzxipignk.html

Py:   value = data or "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtgdlzwbnv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gtuaqdagwt.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gthoxfasku.html

TS:   const value = data ?? "默认值";
来源：http://dali.0kj1m.cn/Article/details/gtetmszlfp.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yonumen.top/Article/details/gtiupedibn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.sxryk.cn/Article/details/gtthkoflxi.html

Ruby: value = data || "默认值"
来源：http://dali.dianchejie.cn/Article/details/gtzzdftfiq.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtmedtvszh.html

[A16] 真假值判断规则
来源：http://dali.yongpay.top/Article/details/gtgdvaetny.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xinyue.icu/Article/details/gtiamppdvz.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.yj202588.top/Article/details/gtebmvnhcj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cheryme.top/Article/details/gtrchvmcxk.html

TS:   if (!x) {}
来源：http://dali.hnqzz.top/Article/details/gtiznrlmal.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.vqdsnc.cn/Article/details/gtvvholuts.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jlsjyb.cn/Article/details/gtccnyajwn.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtkhzvdvwe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhengqikj.top/Article/details/gtjlzwsqyr.html

[A17] 位运算
来源：http://dali.c1oappe.top/Article/details/gtqpfipavy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseowjrci.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gthbwypldu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtlngreisk.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ydzc1.top/Article/details/gtohwkvaqf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shangyingyoupin.top/Article/details/gttgamsutw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtqczrxiak.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.birdmap.top/Article/details/gtmjzthspp.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtkcnfrlov.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ydzc1.top/Article/details/gtwiwhdyfm.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtukvbsfde.html

PHP:  ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtsslosblj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.mhx1999.top/Article/details/gtbjcpozja.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gthpnmvbmp.html

Java: (int) 'A'; (char) 65
来源：http://dali.shuidangran.top/Article/details/gtgpadtvzk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gterxpnknk.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gtetsuvpil.html

C#:   (int)'A'; (char)65
来源：http://dali.xinyue.icu/Article/details/gtnakhocxu.html

[A19] 交换两个变量
来源：http://dali.yj202588.top/Article/details/gtlfceqkno.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchzlcjhl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.redwolf501.top/Article/details/gtjfmzwqbt.html

JS:   [a, b] = [b, a];
来源：http://dali.9152youxi.cn/Article/details/gtigeiuucm.html

TS:   [a, b] = [b, a];
来源：http://dali.birdmap.top/Article/details/gtrttbuzbp.html

Java: int t = a; a = b; b = t;
来源：http://dali.daxiang520.top/Article/details/gthngsqwfb.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtyxobsgpl.html

Ruby: a, b = b, a
来源：http://dali.xylfe.cn/Article/details/gtluqvpdmn.html

C#:   (a, b) = (b, a);
来源：http://dali.pycfn.com/Article/details/gtyrrcruzc.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gtetlsizoe.html

Py:   name = input("请输入：")
来源：http://dali.jlsjyb.cn/Article/details/gtbeyzwsvi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sweek.top/Article/details/gtfuwthuai.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yj20258.top/Article/details/gtwdxcgfaa.html

TS:   // Node.js：readline 模块
来源：http://dali.haohaochexian.top/Article/details/gtwdwunvsm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.aizwys.cn/Article/details/gtanntleld.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.guannengcc.top/Article/details/gtdpzueube.html

Ruby: gets.chomp
来源：http://dali.vqdsnc.cn/Article/details/gtunwofjjv.html

C#:   Console.ReadLine();
来源：http://dali.guannengcc.top/Article/details/gtgmfixzzu.html

[A21] 保留指定小数位输出
来源：http://dali.jqgufenzy.top/Article/details/gtdouzvgop.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yangfankeji.com/Article/details/gttxhvqtia.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtixpkssrn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.meibo888.top/Article/details/gtqxmxciul.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtinrbhqtx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtuzhfotec.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtdtvcocum.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtsctxpulm.html

C#:   3.14159.ToString("F2")
来源：http://dali.yuanzhike.top/Article/details/gtsvaskbwn.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtbnvyhteq.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gtcjwinnng.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.meibo888.top/Article/details/gtjdtunuuj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hywenlv.cn/Article/details/gtzueyfumn.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtgouuiixx.html

Java: s.length()
来源：http://dali.bjfxy.top/Article/details/gtvtcxtdmi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guannengcc.top/Article/details/gtisgjgefg.html

Ruby: s.length
来源：http://dali.9152youxi.cn/Article/details/gtvvtggxks.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gtqbzyiccn.html

[A23] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtqytgmobw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.9152youxi.cn/Article/details/gtatbwqrxv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.snrcjt.cn/Article/details/gtlvdlwxbc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtefgiuasj.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtmyeovxwo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cqqwz.cn/Article/details/gtfmqeizta.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daria6918.cn/Article/details/gtkbvdxhge.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gotoacloud.top/Article/details/gtnmnyncpv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gttgigaiwr.html

[A24] 去除首尾空白
来源：http://dali.fengsongda.top/Article/details/gtilcigbop.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtpekhrcwa.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xinyue.icu/Article/details/gtlufkeovy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtgowxhfcl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtzgycfbep.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.0kj1m.cn/Article/details/gtpwpwulkt.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtvylthiwd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xinyue.icu/Article/details/gtehusgjjn.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.316326.xyz/Article/details/gtfdfsytch.html

[A25] 字符串比较
来源：http://dali.guannengcc.top/Article/details/gtskhurcbs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenlongwang.top/Article/details/gtybjufvuw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsyhbbpl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtokjvavfj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtnwtdvkfc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenzaomai.com/Article/details/gtjeaxffvi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtdzivcmop.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj20258888.top/Article/details/gtrwbfwrkq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtzzweqbnh.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtkvrfdlxc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gthrusdfcf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuanzhike.top/Article/details/gtmiovcbcv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtqpwpcchj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gtgqfrheoo.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtsjvzquqm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aibaodan.cn/Article/details/gtgmazgjdd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gtjtxbgztu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtjlkldtww.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvpbdpmrm.html

B. 流程控制
来源：http://dali.ppjwa.cn/Article/details/gtxyutjzfr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnhktfkkv.html

[B01] 条件判断 if / else
来源：http://dali.zhengqikj.top/Article/details/gtdgsjyqih.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fengsongda.top/Article/details/gtxaknefdk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.andypj.xyz/Article/details/gtbuyumboz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtaqitldml.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gtezcrnlpe.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gttqzmcnyo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtftnntwvx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijlimqad.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtrlaqlbep.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gtxtzgnjqh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gtekuxakaw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtmbrhsfma.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtswcetjna.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtrtgisody.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtskqgfkbf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.feifeiyinyue.top/Article/details/gtvltcfall.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxmcxkfff.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gteufpglsz.html

[B03] switch / match / case
来源：http://dali.iojbl.cn/Article/details/gtsweqwjxz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dianchejie.cn/Article/details/gtwjqwhwjh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzcwvmumt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gthpxtonob.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtgidthrjw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gthapvddpp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtrzeuvcnn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgfzy.top/Article/details/gtwicfznad.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtifhwcyle.html

[B04] for 计数循环
来源：http://dali.aibaodan.cn/Article/details/gtgofnqahg.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtkzukqpye.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.snrcjt.cn/Article/details/gtsltrjkqo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tanke756.top/Article/details/gtjktbxmgx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtdxeioyyp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guannengcc.top/Article/details/gtpylatort.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtuoqhgemy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.andypj.xyz/Article/details/gtpgppdgpy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.havefunace.top/Article/details/gtwagkvmmr.html

[B05] 遍历数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gtjbcfxqbx.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gtbxkdullb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gtkpowvisn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gttcxgacvo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtcxyrufmg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gtmtdjihlk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtekzlujsh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtcvxfvluc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xylfe.cn/Article/details/gtxpwqevnc.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtwmtqusog.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gttsxykipq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dianchejie.cn/Article/details/gtkqiqkjtp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gttwyduclj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtatgsvpwl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gotoacloud.top/Article/details/gtyxcziubo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.redwolf501.top/Article/details/gtqgtjhvjs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhijiandao.cn/Article/details/gthxsrktez.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.daxiang520.top/Article/details/gtjufrlwfp.html

[B07] while 循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzgzymmc.html

Py:   while i < 10: i += 1
来源：http://dali.ybcxt.top/Article/details/gtixfdabse.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tianlin.xyz/Article/details/gtupkniayl.html

JS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtvvoxzxus.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtpkgxzcdw.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gteghmeqvz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtnfkjtfty.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtlmrsjyiw.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtmfmxijxk.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gtvdbuuvsh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtteqpapyk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtfplwbvzk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtpxgsqjxt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtzhlbwzav.html

Java: do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtyplznjes.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguwwpasj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.birdmap.top/Article/details/gtnvrzuxkl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtybykigbn.html

[B09] break 与 continue
来源：http://dali.meibo888.top/Article/details/gtcpsbveil.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtjvzurpns.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtuarksnyi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtcrfqhbif.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtuyzgoara.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtbcrwgstm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtdvdtdftp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yueranfly.top/Article/details/gtvlftzbdp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gteoouqshn.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gttoiloyvm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtspmxewmg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtceiekaqc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtbskzygbj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtqoawtptp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gttxedrpmn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtzhrlygwn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtfflnyrrz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gtnkvrhfdt.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj202588.top/Article/details/gtpvzqmtyr.html

Py:   list(range(0, 10, 2))
来源：http://dali.redwolf501.top/Article/details/gtqmfqlznw.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtzojupgae.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtddzgzjum.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtdunkomze.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgufenzy.top/Article/details/gtcdbzikcd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtahgvlxju.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtwuwigexo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.c1oappe.top/Article/details/gtjejsezkd.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gttrqazkcw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pycfn.com/Article/details/gtlcgfwkpt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtkiahcoic.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtnxojygud.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtkdcjsuao.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gttvpqunfq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtuxhzcsap.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtizchdvdu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtdejwxhxf.html

[B13] 判断是否为数字
来源：http://dali.316326.xyz/Article/details/gtthfsykch.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gtslmcdgyv.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gtrzbhjfiy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gttiezhrmy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtfggrltfc.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtkivzoprw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtghmihxsj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fengsongda.top/Article/details/gtvaegplyt.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtgsmvfewp.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gttfhymwiq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtryuvjjls.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtongnatkg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsdzmjfwr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtmmznoxlj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gthbuvmegk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtejlprzcv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuanzhike.top/Article/details/gtlzczywrw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gttqfjdkto.html

[B15] 布尔运算与取反
来源：http://dali.cheryme.top/Article/details/gthnezncew.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtlafiikdf.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtmvibltra.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtfpuzqbwi.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtaaiyttkg.html

Java: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtoqcoargr.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtrommokmm.html

Ruby: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtyturohas.html

C#:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gthtemaktz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtekibseus.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtojkjffll.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gtoszucncd.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gttrpramkv.html

TS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtgfsgbapa.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtlywjsysk.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gtbawwnwrn.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtyigdjfbi.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtgqxeldqg.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtrjdamkmh.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gtzksqkykw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpxocumgh.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtepqnczlr.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtelrxxxrr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtnjxtckrm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtthnjhohq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtvrzpcsrk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtnguxcxmh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtuannwkat.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtfagvcjwt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtiumimsiq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtuacuknas.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtgfmjrpwf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtqfhayqce.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtyhgxrsne.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtdganppke.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.smart0.xyz/Article/details/gtpnsoqndk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtnxosatgc.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtagjeuebo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtonbjdawb.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gtmvipeika.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtxopjvjxt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtajdttvpy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cucudq.cn/Article/details/gtjlitnnhk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtasosxxpq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtgeatmfwf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtnxhqfyze.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtursxprdz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gtjsiujtsa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtxkftdaix.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtcfimuvve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtehdosnes.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvuiswbzq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gtizmeoxkz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gtrfdmejwo.html


<!-- 参考信息 -->