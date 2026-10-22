代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxinkj.top/Article/details/gtfmbfagfe.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gtuoqxnfxn.html

[A12] 字符串插值 / 格式化
来源：http://dali.9152youxi.cn/Article/details/gtllcmouwm.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.pengpengdd.cyou/Article/details/gtbojnhvsc.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hnxiangtu.top/Article/details/gtdstprzji.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gtmubslrje.html

TS:   `Hello, ${name}!`
来源：http://dali.mhx1999.top/Article/details/gtdjvmcdnx.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hammf.cn/Article/details/gtkjiymtwa.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jlsjyb.cn/Article/details/gtipeswkqe.html

Ruby: "Hello, #{name}!"
来源：http://dali.chenlongwang.top/Article/details/gtqdlhvnkv.html

C#:   $"Hello, {name}!"
来源：http://dali.hongshengwenyu.top/Article/details/gtuswheayp.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.shuidangran.top/Article/details/gtydspjxwu.html

Py:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtbjxwotda.html

PHP:  "第一行\n第二行"
来源：http://dali.wangdashe.top/Article/details/gtsjpvgqcf.html

JS:   "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gtjwrsryks.html

TS:   "第一行\n第二行"
来源：http://dali.cucudq.cn/Article/details/gtefwycpht.html

Java: "第一行\n第二行"
来源：http://dali.gotoacloud.top/Article/details/gtnnqjqbka.html

Go:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtyhbyapsr.html

Ruby: "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gtyplwfygy.html

C#:   "第一行\n第二行"
来源：http://dali.cqqwz.cn/Article/details/gtuocayfpj.html

[A14] 注释写法
来源：http://dali.hfpthk.cn/Article/details/gtxrdbxmjn.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yanxiufei.cn/Article/details/gtcmbjilgh.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtamljfufh.html

JS:   // 单行；/* 多行 */
来源：http://dali.hammf.cn/Article/details/gtjceuqspy.html

TS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gttyemxasc.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hysaishi.cn/Article/details/gtyetalybs.html

Go:   // 单行；/* 多行 */
来源：http://dali.bjfxy.top/Article/details/gttdblnrmj.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.gogol.net.cn/Article/details/gtjspybgbl.html

C#:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtdydhhgxi.html

[A15] 空值判断与默认值
来源：http://dali.chenzaomai.com/Article/details/gtpvommwzo.html

Py:   value = data or "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubcmotiv.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtrpqqkltl.html

JS:   const value = data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtvrckirvh.html

TS:   const value = data ?? "默认值";
来源：http://dali.zycfv.cn/Article/details/gtlnegyasw.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnqzz.top/Article/details/gtmowxcqwe.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yuanzhike.top/Article/details/gtytjazslu.html

Ruby: value = data || "默认值"
来源：http://dali.cashguo.top/Article/details/gtsladlhcr.html

C#:   var value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtkvaynjzy.html

[A16] 真假值判断规则
来源：http://dali.c1oappe.top/Article/details/gtrnmkkrvs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.sweek.top/Article/details/gtxisharco.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgfzy.top/Article/details/gtqscgudwd.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.hammf.cn/Article/details/gtayzxhclx.html

TS:   if (!x) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlncfenpv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.0kj1m.cn/Article/details/gtmopwwxwq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xziqi.cn/Article/details/gtwalchubo.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sufxvd.cn/Article/details/gtwkxkhpcv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.feifeiyinyue.top/Article/details/gttbsofxkg.html

[A17] 位运算
来源：http://dali.0kj1m.cn/Article/details/gtboavqdjs.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtbwmhrwck.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtizneknvi.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtvwlktbql.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtqdfytqzt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtkmqwgbiu.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gthmoafteq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtintyrzlo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtwekatxdg.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yanxiufei.cn/Article/details/gteaurpoxi.html

Py:   ord("A"); chr(65)
来源：http://dali.fzhhl.top/Article/details/gtvfqusltw.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtlgegsakl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guowangkeji.top/Article/details/gtsfisknjz.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xylfe.cn/Article/details/gtlnwulova.html

Java: (int) 'A'; (char) 65
来源：http://dali.chenlongwang.top/Article/details/gtgjjkcrfg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xinyue.icu/Article/details/gtswotslfi.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gtzlgtfdmj.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gtpunhmyxo.html

[A19] 交换两个变量
来源：http://dali.ehwqpu.com/Article/details/gtabmluumy.html

Py:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtlhflmawu.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jinqigfzy.top/Article/details/gtxnrqothe.html

JS:   [a, b] = [b, a];
来源：http://dali.yanxiufei.cn/Article/details/gtwcmvscug.html

TS:   [a, b] = [b, a];
来源：http://dali.hnxiangtu.top/Article/details/gtrqvxwdue.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtjsqgmoon.html

Go:   a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gtoxnnevau.html

Ruby: a, b = b, a
来源：http://dali.xuanzx.com/Article/details/gtrkxylpua.html

C#:   (a, b) = (b, a);
来源：http://dali.snrcjt.cn/Article/details/gtnlqfhpus.html

[A20] 读取标准输入
来源：http://dali.sxryk.cn/Article/details/gtcnoexuko.html

Py:   name = input("请输入：")
来源：http://dali.ehwqpu.com/Article/details/gtkzagvtgy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjpmlpdbq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gtwrkzdbvg.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuwtydgp.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigfzy.top/Article/details/gtpyshjmft.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cashguo.top/Article/details/gtdjhvtojw.html

Ruby: gets.chomp
来源：http://dali.sufxvd.cn/Article/details/gtdkxiynut.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtiuntskvp.html

[A21] 保留指定小数位输出
来源：http://dali.zycfv.cn/Article/details/gtbvpnfhgf.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gtwabccohn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtrbitlcdc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtkdrbxunl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ybcxt.top/Article/details/gtybdxainh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtncrydqkv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtpuyngvvt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ivvv.top/Article/details/gtkynluhkn.html

C#:   3.14159.ToString("F2")
来源：http://dali.gzhubu.top/Article/details/gtudacpded.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtfgtuljqp.html

Py:   len(s)
来源：http://dali.aizwys.cn/Article/details/gtpxlzvhwy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jlsjyb.cn/Article/details/gtrqqrrvcx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jqgfzy.top/Article/details/gttqirllkv.html

TS:   s.length
来源：http://dali.mhx1999.top/Article/details/gtuucsrmla.html

Java: s.length()
来源：http://dali.aibaodan.cn/Article/details/gtsmeavsdx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fengsongda.top/Article/details/gtxsjdlcsj.html

Ruby: s.length
来源：http://dali.shuidangran.top/Article/details/gtpgwiuxib.html

C#:   s.Length
来源：http://dali.fengsongda.top/Article/details/gtjsvwkugv.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtqvsxtdyc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.havefunace.top/Article/details/gtngkeuuet.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtnpcnjcmr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gtquwuudxg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.kuanghao11.cn/Article/details/gtdmbnpdwa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gttdxxlpdx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.dianchejie.cn/Article/details/gtuqkpryza.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gzhubu.top/Article/details/gtrnlsjwyr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hfpthk.cn/Article/details/gtdoipzcfs.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gtqrwaefbt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gtfvzxoqqd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cashguo.top/Article/details/gtldhdjlba.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtlacmeqpd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtgrzyesis.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tian-w.cn/Article/details/gtojtcpdpa.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gtlfrjepua.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.mhx1999.top/Article/details/gtyoqqyboc.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.aibaodan.cn/Article/details/gtymcjpqtm.html

[A25] 字符串比较
来源：http://dali.yanxiufei.cn/Article/details/gtipgdexuz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zycfv.cn/Article/details/gtnxtlboyn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj202588.top/Article/details/gtjpubpmll.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ppjwa.cn/Article/details/gtvboxxttn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtatiqueko.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yuanzhike.top/Article/details/gtpbzvwbol.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtqwbwjubm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtxmywpvqq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cashguo.top/Article/details/gtasxhwuft.html

[A26] 类型转换总览
来源：http://dali.ivvv.top/Article/details/gttiuovtli.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jlsjyb.cn/Article/details/gtvifquurc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gtfsehqlqc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cdnleiting.top/Article/details/gtzzydymdk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gtxezjhrpl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenlongwang.top/Article/details/gtmortgdbs.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shuidangran.top/Article/details/gtatjfuozh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gtikrrbmvp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gtnufthcba.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtrdfptnee.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtrxyjxmcg.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtyskoaceg.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gtozrtecdt.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuanzhike.top/Article/details/gtetclljkl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.0kj1m.cn/Article/details/gtelvbkdza.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtqiuoavgv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtzdcakebg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtfwlysjqg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gtkczrcueb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hywenlv.cn/Article/details/gtbpomcqzp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtixdpvuhe.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtuofkphkq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gtmhozhmqg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtbhhwcjam.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtbmfbsayb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gthaaxdmrg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtjehiknyk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhijiandao.cn/Article/details/gtwfiyhmtw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyevwravg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtnhznawdp.html

[B03] switch / match / case
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtikyuyoam.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gtknmewbes.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtadkcflzc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzxnphtt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtchkgmzbu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gteomqcoyi.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gtsqrzcpfa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gtkaqxddeu.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtoqwzgsfy.html

[B04] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtclypxxbl.html

Py:   for i in range(10): print(i)
来源：http://dali.tianlin.xyz/Article/details/gtvbdqcusl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gtaznrmqoy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtvryrwpzh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtyqknxuik.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtgqnpqkaq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhongyouzk.top/Article/details/gtatfzxwmw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtyzafjexc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtndhjoahw.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtlckoqbpr.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtegldmllz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtsdtcdugw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtxsvxtfaj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtfgadxtxz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jiagoushi.top/Article/details/gteatbclmt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gttsjszmsh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvvhpxhj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtjmoaynjg.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gtdfqjuhym.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gtflvnbqna.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zycfv.cn/Article/details/gtqlwxzxnx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gtgmzfpslm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvogdhrxe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxinkj.top/Article/details/gtzadwyjpf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjodfgfme.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtbfzgzukd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zycfv.cn/Article/details/gttvqxwqna.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtuygtfbhr.html

Py:   while i < 10: i += 1
来源：http://dali.shangyingyoupin.top/Article/details/gtfmpxyuny.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gttoplymqo.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtkeqvumtk.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtxsjrjmuu.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtazhgfkoa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gtkdisjypl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawxynokw.html

C#:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtaxrkedjw.html

[B08] do-while（至少执行一次）
来源：http://dali.gogol.net.cn/Article/details/gtmgrscoro.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gtfformyia.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtywihbfyg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttmhdmmux.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtnepvrtwk.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtzwvekems.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtgiyohfup.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gteyazghwb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtjbasahqx.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtdfplyyup.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.meibo888.top/Article/details/gtnqwumqin.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtwzpcjnlj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtscltnket.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtexzfxawv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdedxmflf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtnouzjasa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtipapdazi.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtvzarzkut.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gtsonernob.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aizwys.cn/Article/details/gtsoqzbvmr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtersjxljs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gthxdswxny.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtwduehvms.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gtsctvgian.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtjulmgcxv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gtsjfpgxya.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtyemjwarh.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtcejrggne.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gttrxzvjel.html

PHP:  range(0, 10, 2);
来源：http://dali.yongpay.top/Article/details/gtxhezbvsg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtvzstpoul.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtigguukcj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtotpkbypd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyfgzfjfi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmibedde.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtbhvmkyiy.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtbratgbce.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gthaedhccs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtafewenfj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtavfatlhg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtjpgylkab.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gthngeoazr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtknohpxox.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtaevchvij.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtppjtyovu.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgqzcpwhf.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtbzhmapmp.html

PHP:  is_numeric($x)
来源：http://dali.xinyue.icu/Article/details/gtuzzbudea.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbokvmum.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtsjgxuiek.html

Java: x instanceof Number
来源：http://dali.fengsongda.top/Article/details/gtoajrolxk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtpgtsmtvk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtshqtjyhy.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gtyszjwxxs.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gterhknpia.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtikrqzxem.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtxwggkoaq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtmzazfsxs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtkjhqveog.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gtdqlmmsje.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gttilwxwkg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgibmzkat.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gogol.net.cn/Article/details/gtoucyupey.html

[B15] 布尔运算与取反
来源：http://dali.dashuyun.cn/Article/details/gtunqketyh.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtfwfshzhk.html

PHP:  $a && $b || !$c
来源：http://dali.zhiwuduotai.top/Article/details/gtfaxbbimo.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtlxkvwiur.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtpswcvksl.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtgouqbpok.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtfrtumdde.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtyeuoifvb.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtectqcasg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtpwvxndru.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gtfrnzvzyx.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtcfoidhwt.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtbdvxssin.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtkdqgyjty.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtrplhwhnz.html

Go:   if data == nil { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdgkplrj.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtuqujjtye.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtgfzwhbko.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gthczyowof.html

C. 函数与作用域
来源：http://dali.yj20258.top/Article/details/gtavaqtxde.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtgqncdlvl.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtummmxuoq.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtxcqxknrs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtnimjcjmc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtpjtblgck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtbybhkgbk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtdboxgxmq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtrmurgpta.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtdnfnksqp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfmcxzxmy.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtlvjxzose.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gtoynlwhms.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtdbuupnob.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtdbnfnbru.html


<!-- 参考信息 -->