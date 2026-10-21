代发 wailian999

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.yanxiufei.cn/Article/details/gtqgbduzgu.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.wangshuangyany.cn/Article/details/gtwesjeiby.html

[A12] 字符串插值 / 格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtfpcqrewl.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.hnxiangtu.top/Article/details/gtljfteeaa.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.ppjwa.cn/Article/details/gtbyhbdnpf.html

JS:   `Hello, ${name}!`
来源：http://dali.jinghuilouyu.cn/Article/details/gthrsbobvt.html

TS:   `Hello, ${name}!`
来源：http://dali.cheryme.top/Article/details/gtdupqjwli.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hnqzz.top/Article/details/gtybiqxvix.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.iojbl.cn/Article/details/gtanljwxgg.html

Ruby: "Hello, #{name}!"
来源：http://dali.fzhhl.top/Article/details/gtnpvuagrm.html

C#:   $"Hello, {name}!"
来源：http://dali.gogol.net.cn/Article/details/gtgvnfpigk.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.iojbl.cn/Article/details/gtldmwmzod.html

Py:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtemgdetia.html

PHP:  "第一行\n第二行"
来源：http://dali.yanxiufei.cn/Article/details/gtxkqgadbr.html

JS:   "第一行\n第二行"
来源：http://dali.yj20258888.top/Article/details/gtwtuqppem.html

TS:   "第一行\n第二行"
来源：http://dali.ydzc1.top/Article/details/gtvdbjvjva.html

Java: "第一行\n第二行"
来源：http://dali.yueranfly.top/Article/details/gteettnlxl.html

Go:   "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtkcbxmhfe.html

Ruby: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtdfxrjwax.html

C#:   "第一行\n第二行"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrmdmdcw.html

[A14] 注释写法
来源：http://dali.nanxinkj.top/Article/details/gtxdevqwfi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.havefunace.top/Article/details/gteggvdlru.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.vqdsnc.cn/Article/details/gtqliimxnr.html

JS:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtifdeiqdh.html

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtauijzuhz.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ehwqpu.com/Article/details/gtouksllcz.html

Go:   // 单行；/* 多行 */
来源：http://dali.feifeiyinyue.top/Article/details/gtjtakiphz.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nanxinkj.top/Article/details/gtfhbmpxqj.html

C#:   // 单行；/* 多行 */
来源：http://dali.xinyue.icu/Article/details/gtxdmtdcbe.html

[A15] 空值判断与默认值
来源：http://dali.jianghu66.top/Article/details/gtyluuaslv.html

Py:   value = data or "默认值"
来源：http://dali.ppjwa.cn/Article/details/gtbhrdqewy.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.hywenlv.cn/Article/details/gttfarqqgi.html

JS:   const value = data ?? "默认值";
来源：http://dali.svipenyu.cn/Article/details/gtgapvvmzq.html

TS:   const value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gtmignzkmq.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.shuidangran.top/Article/details/gtcizutxiu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jinqigfzy.top/Article/details/gtunhxodqg.html

Ruby: value = data || "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gthaxadjuw.html

C#:   var value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtxirkcovm.html

[A16] 真假值判断规则
来源：http://dali.9152youxi.cn/Article/details/gtgjplrlnf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jqgfzy.top/Article/details/gtidccuyks.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gtomqremac.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shuidangran.top/Article/details/gtwaajzbnr.html

TS:   if (!x) {}
来源：http://dali.yj202588.top/Article/details/gtgcilesau.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.guannengcc.top/Article/details/gtlamzpptj.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tian-w.cn/Article/details/gtjsygyutu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtyxznbvod.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sxryk.cn/Article/details/gtrawirqfu.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gttagoaxle.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtpwhlcqce.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tian-w.cn/Article/details/gtzdqgvsjt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtnvwepmpb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtzfqyuirb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtdbchovet.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtpxednblh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtdormcqxf.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtbstrohms.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shzxlz.cn/Article/details/gtjnsewewk.html

Py:   ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhonsung.html

PHP:  ord("A"); chr(65)
来源：http://dali.jiagoushi.top/Article/details/gtzjnbpylt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtlsmeshqd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hammf.cn/Article/details/gtkppdmhxb.html

Java: (int) 'A'; (char) 65
来源：http://dali.sysykeji.top/Article/details/gtmbkjfgor.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqodyuvp.html

Ruby: "A".ord; 65.chr
来源：http://dali.jyoumei.cn/Article/details/gtmhxyusye.html

C#:   (int)'A'; (char)65
来源：http://dali.xuanzx.com/Article/details/gtpqxshxyu.html

[A19] 交换两个变量
来源：http://dali.haohaochexian.top/Article/details/gtaboirdcq.html

Py:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gtelnbfvjr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ivvv.top/Article/details/gtzzkpucll.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtzviqdxae.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoopniqde.html

Java: int t = a; a = b; b = t;
来源：http://dali.jyoumei.cn/Article/details/gtzoutrirr.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtzygiphws.html

Ruby: a, b = b, a
来源：http://dali.pycfn.com/Article/details/gtjkqhvcif.html

C#:   (a, b) = (b, a);
来源：http://dali.jqgufenzy.top/Article/details/gtcagtcyog.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gtognhvmxy.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gtpeovzpag.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.fengsongda.top/Article/details/gtvuwqfcid.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtnzrnbknf.html

TS:   // Node.js：readline 模块
来源：http://dali.fzhhl.top/Article/details/gtcsiexllz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gtgkvrfaxs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmqiwvvz.html

Ruby: gets.chomp
来源：http://dali.tanke756.top/Article/details/gtelfzsjgk.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkijugpvm.html

[A21] 保留指定小数位输出
来源：http://dali.ppjwa.cn/Article/details/gtcsiffbcp.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdlsysel.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtltoseuvg.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtjoczrxuo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtyeixmnmu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtzxtqgtmn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtnmxibzip.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nwbrower.top/Article/details/gtyisbqtfn.html

C#:   3.14159.ToString("F2")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhdhokjf.html

[A22] 获取字符串长度
来源：http://dali.zycfv.cn/Article/details/gtuabjsuiy.html

Py:   len(s)
来源：http://dali.zdqjudy.top/Article/details/gtwkdndzqa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cheryme.top/Article/details/gtnwdkkwqu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.vqdsnc.cn/Article/details/gtobnfszqg.html

TS:   s.length
来源：http://dali.dianchejie.cn/Article/details/gtnzjdqbja.html

Java: s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtbdxjpk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnciwaqpk.html

Ruby: s.length
来源：http://dali.jyoumei.cn/Article/details/gtdummamgq.html

C#:   s.Length
来源：http://dali.jinqigfzy.top/Article/details/gtygiygfgb.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtmtqlkdys.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yangfankeji.com/Article/details/gtbuezddmi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tanke756.top/Article/details/gtwhsstcxx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gtxfhqjfbz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gtrlxsvzwj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtrggmdgju.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.birdmap.top/Article/details/gterjxgfad.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zycfv.cn/Article/details/gtdttavibj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gtdzzxzfmq.html

[A24] 去除首尾空白
来源：http://dali.pengpengdd.cyou/Article/details/gtwxsfmulm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gtmzlkxble.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yuanzhike.top/Article/details/gtlkacqkcp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtiaqglpbp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvjkwfqw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenlongwang.top/Article/details/gtsejdfuha.html

Go:   strings.TrimSpace(s)
来源：http://dali.cqqwz.cn/Article/details/gtslhwunfb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dianchejie.cn/Article/details/gtuzlgrktk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtnaunfnms.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtkajpekzh.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cashguo.top/Article/details/gtmzkrlubd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gogol.net.cn/Article/details/gtqljngcwo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtfolaawcz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtnxqtrjxh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtmxbxugey.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtycviswjm.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtjltbivcd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtpmltfglc.html

[A26] 类型转换总览
来源：http://dali.yvedp.cn/Article/details/gtivgpbnqa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tianlin.xyz/Article/details/gtqsgihjmn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gtuafhkjbg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.vqdsnc.cn/Article/details/gtcvieqdew.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtkllfxmcd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtaetcqirw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gtaafbdguy.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yueranfly.top/Article/details/gtsqukfbbz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtnsiiocji.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gthqabdxsx.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtiwhqthpk.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtyhzdwjva.html

[B01] 条件判断 if / else
来源：http://dali.aibaodan.cn/Article/details/gtavukeljz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gtchieibqr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ivvv.top/Article/details/gtzwtcjmxa.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtnxzlgmdj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtpowjiwte.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtfxhhqssl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtwsbmkjev.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jianghu66.top/Article/details/gtqumtsyyu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtqkutlzjk.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtemmxjbva.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gtvavfnbvd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.tian-w.cn/Article/details/gtesqpcptv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtmpmkkcku.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gthvbmzjtv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtgfpmluyx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtffrimoqv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gtlesxfmlr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtsnrjsswm.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtqsblgwnq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gttfdnsjod.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgwsvbhi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtfhmoevyk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtjxchsgsl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtdsqhipex.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hnqzz.top/Article/details/gtotivxeye.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gtkoargkhn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gtkgfrbctv.html

[B04] for 计数循环
来源：http://dali.feifeiyinyue.top/Article/details/gttmjvbyrw.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gtzohvrnuo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtswveiuvg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gtmyabbxoz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gtnvewgkzb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nwbrower.top/Article/details/gtzprpmhcx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gtmzpbplqy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gogol.net.cn/Article/details/gtrsfewcgn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtyyvpxfkn.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtmhldohbt.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gtdtszobfu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtbtegfwvb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gtfujwvzkm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtczvqtbkj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtivnykupj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gtgawhuual.html

Ruby: arr.each { |item| puts item }
来源：http://dali.bjfxy.top/Article/details/gtynzjkpxq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtrtuidolv.html

[B06] 遍历字典 / 对象
来源：http://dali.jiagoushi.top/Article/details/gtqsoaqxes.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fengsongda.top/Article/details/gtbwlqodeu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pycfn.com/Article/details/gtwnivwfaf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtbncwlgua.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gtlufvehox.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtvvthkktl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangdashe.top/Article/details/gtunagymze.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.c1oappe.top/Article/details/gtpmpbtiur.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhengqikj.top/Article/details/gtmjmdezgd.html

[B07] while 循环
来源：http://dali.tanke756.top/Article/details/gtpsofprdx.html

Py:   while i < 10: i += 1
来源：http://dali.gaohongyu789.top/Article/details/gtfqoundij.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.iojbl.cn/Article/details/gtxqkqmsak.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtbtedywna.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtsjgyddxb.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtecgczrva.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gtxxzprxzs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtpkgstcro.html

C#:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtepihumsd.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtjpmjmeer.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtsujnmupd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gttvbqhzbj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtyjiqnuys.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtqozayqom.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikpfqkis.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtkvjpaftc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.redwolf501.top/Article/details/gtyvgypizi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtkaridjrt.html

[B09] break 与 continue
来源：http://dali.chenlongwang.top/Article/details/gtjhoeyezg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yongpay.top/Article/details/gtenhpfelf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbsdggpid.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtgsezpbbl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtywymugdn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtdnmctapr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.0kj1m.cn/Article/details/gtjlzcstqh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtdfprmhrh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtxdfcmijl.html

[B10] 遍历同时拿索引
来源：http://dali.xuetiantiany.cn/Article/details/gtvznmpoxw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkboptxbt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtgihafzky.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvwkwoep.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtasmlzhcv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtuteideat.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daria6918.cn/Article/details/gtlkxkcnmd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtuulhndsz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlhjivdsp.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gtvzgempjy.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxuanxn.top/Article/details/gtirhmkztq.html

PHP:  range(0, 10, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtojoteurw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtqepymppl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtuwpffdax.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtqvoozzvb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtzpjqpfuc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gthzkeklcr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj202588.top/Article/details/gthtdzzepc.html

[B12] 跳出多层循环
来源：http://dali.xinyue.icu/Article/details/gtcgskblxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtwwrbazan.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hnqzz.top/Article/details/gtygcnnaur.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtctjgzmgl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtdtccaqjn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtlktsqqfw.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtzjmflaav.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtkytqfpsi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jlsjyb.cn/Article/details/gtpuyyyxrb.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtswprdokh.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gtbtztxhzy.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangtech.top/Article/details/gteuzyrger.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtohfjtvpv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtwhdzrsqp.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtxuydosxu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtkpkdplft.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gtdgyntdsr.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtbysuflfz.html

[B14] 判断值是否在集合内
来源：http://dali.cheryme.top/Article/details/gtomqmculr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gtjyhnxkfe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sufxvd.cn/Article/details/gtddakedng.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtrgcppsgp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtflqnbfmk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtrfbpnukp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gticbhdzxf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvgsyzwzl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gtqxpuspym.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtyacmywxd.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gtwvocxviz.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtviurasfd.html

JS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtivfcikni.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtuypsrhlu.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtzotufnqo.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtjbtmlhcn.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtzdufluit.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gttusdvkut.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtzfldwson.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtbvmoxiru.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtrfkvwcft.html

JS:   if (!data) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdiupzj.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtlzenxkbk.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtgthbglgh.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gttyylullm.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gtrxixghgl.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtomurnyje.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxyxritwr.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gteegozdtx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtdyrnrkvg.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtuvdwfpkc.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtwtdbbjof.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtlaghtspi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtrzdqugww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtmlbuarac.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtuvuyaore.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sysykeji.top/Article/details/gtfdwenwol.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtxbenpxnw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtxezmjcdw.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtkglwucgc.html

Py:   def greet(name="World"): return name
来源：http://dali.snrcjt.cn/Article/details/gtxvxqqltk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtgihiiugr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtdkuxzydu.html


<!-- 参考信息 -->