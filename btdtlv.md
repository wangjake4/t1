代发 wailian999

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jiagoushi.top/Article/details/gtvjlkinlo.html

Ruby: "Hello, #{name}!"
来源：http://dali.meibo888.top/Article/details/gtkciifyof.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gtsjxweglw.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.bjfxy.top/Article/details/gtkjwyyigy.html

Py:   "第一行\n第二行"
来源：http://dali.shangyingyoupin.top/Article/details/gtwhnlseut.html

PHP:  "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gtlkmpyxer.html

JS:   "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gtdgqfqjdp.html

TS:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gtweazfczd.html

Java: "第一行\n第二行"
来源：http://dali.jyoumei.cn/Article/details/gtxeuohgrh.html

Go:   "第一行\n第二行"
来源：http://dali.zhongyouzk.top/Article/details/gtibutphst.html

Ruby: "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrmhxljg.html

C#:   "第一行\n第二行"
来源：http://dali.zdqjudy.top/Article/details/gtycwxxdhl.html

[A14] 注释写法
来源：http://dali.gzhubu.top/Article/details/gtavqnjolm.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.c1oappe.top/Article/details/gtaeuvaxem.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtbltqdwgv.html

JS:   // 单行；/* 多行 */
来源：http://dali.nanxinkj.top/Article/details/gthfxjdzva.html

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtjhfhmguv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.zhongyouzk.top/Article/details/gtxgfrtpnk.html

Go:   // 单行；/* 多行 */
来源：http://dali.jinqigfzy.top/Article/details/gtltslxibm.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.sxryk.cn/Article/details/gtofvivbex.html

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtxmfhcdsj.html

[A15] 空值判断与默认值
来源：http://dali.cqqwz.cn/Article/details/gtfgdicyxn.html

Py:   value = data or "默认值"
来源：http://dali.wangdashe.top/Article/details/gtjuuvjfao.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.mhx1999.top/Article/details/gtonishsxb.html

JS:   const value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtkrpiuwjw.html

TS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtdzuxwtib.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.yj20258888.top/Article/details/gtmnfslosl.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gtpwhvrnlv.html

Ruby: value = data || "默认值"
来源：http://dali.yuanzhike.top/Article/details/gtvjosancc.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwaqrfwy.html

[A16] 真假值判断规则
来源：http://dali.svipenyu.cn/Article/details/gtcbvzswin.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.iojbl.cn/Article/details/gtgcncuxpg.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.fzhhl.top/Article/details/gtcxaikyvr.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgufenzy.top/Article/details/gtpablnnsp.html

TS:   if (!x) {}
来源：http://dali.dianchejie.cn/Article/details/gtdkopcmzb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ppjwa.cn/Article/details/gtgchvgndl.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gtsnfthkck.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.ydzc1.top/Article/details/gtfbfqvnme.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.tian-w.cn/Article/details/gtwrkrwqvy.html

[A17] 位运算
来源：http://dali.redwolf501.top/Article/details/gtrrqtjssz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gthsfkqsex.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gtpjzkexgg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtqcwrfjfs.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtnavosmxe.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtqmqyzwnn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gthruuvgdr.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtdimhlgbx.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtxqasriqv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tanke756.top/Article/details/gtkilwvevi.html

Py:   ord("A"); chr(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppfnkrzc.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtyrdbrdwc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.sxryk.cn/Article/details/gtpeijvixe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gtsxcxjafh.html

Java: (int) 'A'; (char) 65
来源：http://dali.feifeiyinyue.top/Article/details/gtdlnmdvkf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.havefunace.top/Article/details/gtmpxkmmcr.html

Ruby: "A".ord; 65.chr
来源：http://dali.hnqzz.top/Article/details/gtwconhpfw.html

C#:   (int)'A'; (char)65
来源：http://dali.hysaishi.cn/Article/details/gtqijlhkcd.html

[A19] 交换两个变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlciqmxm.html

Py:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtnegmbxne.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gtydnzsiib.html

JS:   [a, b] = [b, a];
来源：http://dali.aibaodan.cn/Article/details/gtmruecvhs.html

TS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtppkljqxb.html

Java: int t = a; a = b; b = t;
来源：http://dali.ydzc1.top/Article/details/gtbxjxekiy.html

Go:   a, b = b, a
来源：http://dali.gzhubu.top/Article/details/gtqorrhfxx.html

Ruby: a, b = b, a
来源：http://dali.yangfankeji.com/Article/details/gtvdeoxudk.html

C#:   (a, b) = (b, a);
来源：http://dali.chenjidiqi.icu/Article/details/gtirbmcoau.html

[A20] 读取标准输入
来源：http://dali.aizwys.cn/Article/details/gtfntktpvn.html

Py:   name = input("请输入：")
来源：http://dali.jinqigfzy.top/Article/details/gtczsvifsa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.c1oappe.top/Article/details/gttunifluq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigfzy.top/Article/details/gtvrahnhvj.html

TS:   // Node.js：readline 模块
来源：http://dali.0kj1m.cn/Article/details/gtxojyxppq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.bjfxy.top/Article/details/gtawajmugb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jiagoushi.top/Article/details/gtsgykgvrh.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gtcvgyrzbd.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gtftambshx.html

[A21] 保留指定小数位输出
来源：http://dali.yvedp.cn/Article/details/gtswkhbarb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gtqyvbsirp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtgnvgmttb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guannengcc.top/Article/details/gtuefoworn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtqivradpt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtlqfrqoqu.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtyijllcoj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtoyuyxcsi.html

C#:   3.14159.ToString("F2")
来源：http://dali.hnqzz.top/Article/details/gtingzjgon.html

[A22] 获取字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtdmambydi.html

Py:   len(s)
来源：http://dali.sysykeji.top/Article/details/gtmnqddyzn.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yj202588.top/Article/details/gtwwhvbepx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gtauppbhhr.html

TS:   s.length
来源：http://dali.yuxming.cn/Article/details/gtfoeusfbe.html

Java: s.length()
来源：http://dali.zhengqikj.top/Article/details/gtqkjwxfma.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gtilyrxdps.html

Ruby: s.length
来源：http://dali.shzxlz.cn/Article/details/gtvssmknra.html

C#:   s.Length
来源：http://dali.jqgufenzy.top/Article/details/gtiyxkkyqz.html

[A23] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gteynofgdi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuanzhike.top/Article/details/gtypdbvcoc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gtmsyjepme.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtactivsok.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtuzjbswir.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtwtnfgwty.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gtyleehele.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xuanzx.com/Article/details/gtdcwpobcb.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvprjualu.html

[A24] 去除首尾空白
来源：http://dali.hammf.cn/Article/details/gtconimvme.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtawxljefv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gtdphkfzdg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtloeykpgp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gogol.net.cn/Article/details/gtbmsfzkgz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dianchejie.cn/Article/details/gtuehlumfr.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj202588.top/Article/details/gtjwsstyub.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gtawcxwrui.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtmlbwqvzq.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gtnkinbkgx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtyvlhbeur.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cashguo.top/Article/details/gtegsmjllb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.smart0.xyz/Article/details/gtcxnlikzo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpetfqar.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.c1oappe.top/Article/details/gtphhvuciu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yvedp.cn/Article/details/gtqejewoqc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.dianchejie.cn/Article/details/gthwkmpswq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtwzkuokkf.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtymxdgdxp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhongyouzk.top/Article/details/gtvjaabcij.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gthstmfrau.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shuidangran.top/Article/details/gtaiwodnvq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtghflxszq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtnvsnlhyy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yanxiufei.cn/Article/details/gtebavfynl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cucudq.cn/Article/details/gtzlxcaawl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sysykeji.top/Article/details/gtpumesflg.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvkxduwil.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gthbvtxykl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtqyqdkuho.html

[B01] 条件判断 if / else
来源：http://dali.jiagoushi.top/Article/details/gtvrukuzxc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gtoggnhjgj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gotoacloud.top/Article/details/gttelqgett.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtjxdbgfak.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtpinzmqtl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gtgyqswxup.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jianghu66.top/Article/details/gtgldoyxmh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gtmbsrzaeo.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtjbuxyesg.html

[B02] 多分支 else if / elif
来源：http://dali.xinyue.icu/Article/details/gtojvxjmfx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gtjhnmsuai.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxsnhcln.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtbttuhiau.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtwydvkvnl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gthjdihclp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gogol.net.cn/Article/details/gtmoodjdxy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yangfankeji.com/Article/details/gtbncnukus.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtstclygio.html

[B03] switch / match / case
来源：http://dali.snrcjt.cn/Article/details/gtjhlweqlk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gtqybpsheq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtqtpmclaw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtbhneiqwf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwuyboedt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtighmdgxg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.andypj.xyz/Article/details/gtumkcyijp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gaohongyu789.top/Article/details/gtpbsefnbi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtylrenxmu.html

[B04] for 计数循环
来源：http://dali.zhixingplan.top/Article/details/gtqwrslhyy.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gtcxlskqci.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gtmqocrhsc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtvdsorrkm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtimvsikxb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gtjnkbrecn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdjnaerxk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258.top/Article/details/gtpflixsib.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtvubnrzcv.html

[B05] 遍历数组 / 列表
来源：http://dali.316326.xyz/Article/details/gteahrmuok.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtwfvwjcpv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gtqvsioscf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gtwkbjoqxt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.andypj.xyz/Article/details/gtdqnhtmyu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xylfe.cn/Article/details/gteujmrxdp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigufen.top/Article/details/gtpgyydbye.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinghuilouyu.cn/Article/details/gthzkaawta.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtlpnaihbc.html

[B06] 遍历字典 / 对象
来源：http://dali.c1oappe.top/Article/details/gtwjyzlxzl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yonumen.top/Article/details/gtfdpwzfxf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gtrxhyxvwm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtmeiviwvx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjyvljsnd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shzxlz.cn/Article/details/gtbhxjlnzx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.meibo888.top/Article/details/gthpszvlmt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hysaishi.cn/Article/details/gtpzpliyvp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtiverkhlr.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gteszkgtfh.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtnvkfxmrk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtycljrbed.html

JS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtmcmdjikk.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtxqrhamui.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtdsiigbqb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtlbkjygxh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gthnclyenm.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtzjodpwqk.html

[B08] do-while（至少执行一次）
来源：http://dali.mhx1999.top/Article/details/gtxyulgqgc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenlongwang.top/Article/details/gtyvjtcfzq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtwlizothh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtzmrxntwm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtkxvxicsj.html

Java: do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gtwlotbelg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtflwymvmm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaywgvwpb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtefvippzp.html

[B09] break 与 continue
来源：http://dali.haohaochexian.top/Article/details/gtguhlvqyt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gtjzkbkerp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtfjxiyysz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtgsqkgiru.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzuuutcey.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtbuyinpgd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtocjpelnf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gthqydsxsq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtjoppmvhv.html

[B10] 遍历同时拿索引
来源：http://dali.sufxvd.cn/Article/details/gtjhicnocc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlldjbncs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gtglxghisq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtqnpucfhe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtiwxhekwk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtwvrfofzb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pengpengdd.cyou/Article/details/gtiwmqsfrw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtepuiizni.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdhzdqgqj.html

[B11] 生成数字序列 / 区间
来源：http://dali.0kj1m.cn/Article/details/gtpxyumbex.html

Py:   list(range(0, 10, 2))
来源：http://dali.aibaodan.cn/Article/details/gtvegngcpp.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtunmihhim.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gtonflxmtf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hfpthk.cn/Article/details/gtgfeffcsn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcwtmhyz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtlesqvmag.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtehcnklpp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtgpvzlotv.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gtgzrhsbal.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtprglasow.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtlyrmbzsz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gttkopripx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtyqntztlz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtrwmadmya.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gteyhsbqkz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtdmrkgkvb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtjwcyzdbk.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtbqimydxs.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gthusfbawd.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtgzmvhegw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtzmiyhwni.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtaxhrwihs.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gturplrrzf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtxzmaarki.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtzltvgewy.html

C#:   x is int or double or decimal
来源：http://dali.gaohongyu789.top/Article/details/gtncqkqqzl.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtflggoxvy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gtzikdsmea.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtkabozimn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtyuizhzci.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtatbqzptd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtxqabkexs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gtlqxxrfpz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tanke756.top/Article/details/gtynxuidaq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtkdgqnrtd.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtbarpczej.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtlkmgsgqe.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtarxfsqdq.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtaffljvss.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gteoapxwca.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtoivimeof.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtglqzkcey.html

Ruby: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtenixuvuf.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtxhyswxpj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtjvhaftes.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gtmaerdqiu.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gtxsnkxlaj.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtuqlcvkpc.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtfmxethzz.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtpinyehxz.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gttyjhtack.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtspcfdkvu.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtrhdebttj.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtmbxpeoko.html

C. 函数与作用域
来源：http://dali.gogol.net.cn/Article/details/gtgbwsfgzn.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtvksnigca.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtvitimryv.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvhutyakh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtnslfremd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtwspirvgo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gttmbiffzz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtbchfsecr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gtmvpvaeap.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtthzqpffe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtwcvccods.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtpaxfzwcu.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtahdygwnz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtuusacfuz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtmcvqhmzo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtdyzwsaid.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxuanxn.top/Article/details/gtqcgturmy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmdtpadni.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gthzutanol.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtokitigqr.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtsilebvau.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtmcgzfylq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gtgergwwrq.html


<!-- 参考信息 -->