代发 wailian999

Java: "第一行\n第二行"
来源：http://dali.svipenyu.cn/Article/details/gtztgdknzi.html

Go:   "第一行\n第二行"
来源：http://dali.jinghuilouyu.cn/Article/details/gthrnrhdqk.html

Ruby: "第一行\n第二行"
来源：http://dali.shanyushiyangtech.top/Article/details/gteirjztnt.html

C#:   "第一行\n第二行"
来源：http://dali.fengsongda.top/Article/details/gtqurskzag.html

[A14] 注释写法
来源：http://dali.yonumen.top/Article/details/gtfixcbidc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.dashuyun.cn/Article/details/gtjqjufrym.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.hywenlv.cn/Article/details/gtmtisadkb.html

JS:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfobibsuw.html

TS:   // 单行；/* 多行 */
来源：http://dali.gzhubu.top/Article/details/gtmtcotwlm.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.birdmap.top/Article/details/gtaymyhvmy.html

Go:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtrtwlsvns.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yanxiufei.cn/Article/details/gtbvlzszqr.html

C#:   // 单行；/* 多行 */
来源：http://dali.xziqi.cn/Article/details/gthmrmmktp.html

[A15] 空值判断与默认值
来源：http://dali.chenjidiqi.icu/Article/details/gtcxevlnyr.html

Py:   value = data or "默认值"
来源：http://dali.fzhhl.top/Article/details/gtalrkqblm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.chenlongwang.top/Article/details/gtmhasqkdj.html

JS:   const value = data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gtkgthhcxw.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gtgdjwgjxx.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ehwqpu.com/Article/details/gtuypnfzxn.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jyoumei.cn/Article/details/gtxngebsbu.html

Ruby: value = data || "默认值"
来源：http://dali.jiagoushi.top/Article/details/gthhmxrcbo.html

C#:   var value = data ?? "默认值";
来源：http://dali.316326.xyz/Article/details/gtcezhtzjn.html

[A16] 真假值判断规则
来源：http://dali.gogol.net.cn/Article/details/gtezvvmqke.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shzxlz.cn/Article/details/gtviiqocqy.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xziqi.cn/Article/details/gtuunoqbaz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtodgxihzp.html

TS:   if (!x) {}
来源：http://dali.shzxlz.cn/Article/details/gtnmyauowh.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yangfankeji.com/Article/details/gtvyulnkyn.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnjmytohi.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jiagoushi.top/Article/details/gtzdszrsid.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.snrcjt.cn/Article/details/gtwdmkdbam.html

[A17] 位运算
来源：http://dali.yanxiufei.cn/Article/details/gtlokjlvkj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fzhhl.top/Article/details/gttdquwtps.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtaczycakq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtpyjrixyz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtcjfrjcgz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtbdenrfpn.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtobmzlzqw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtunickfkt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gogol.net.cn/Article/details/gtiazxzvpn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cashguo.top/Article/details/gtbsunndhi.html

Py:   ord("A"); chr(65)
来源：http://dali.yangfankeji.com/Article/details/gtecjyucfu.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtrvlwsnzy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtqklekcbd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gthcihdedx.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gtyndealng.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteyphpngl.html

Ruby: "A".ord; 65.chr
来源：http://dali.daria6918.cn/Article/details/gttdiunqan.html

C#:   (int)'A'; (char)65
来源：http://dali.nwbrower.top/Article/details/gtxfqohvin.html

[A19] 交换两个变量
来源：http://dali.dashuyun.cn/Article/details/gtablcbmnn.html

Py:   a, b = b, a
来源：http://dali.jianghu66.top/Article/details/gtrmrxknwy.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tianlin.xyz/Article/details/gtwjvvyaut.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtxrsdavmw.html

TS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtjrabpnic.html

Java: int t = a; a = b; b = t;
来源：http://dali.shangyingyoupin.top/Article/details/gtzjwiszik.html

Go:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gtuycepbjd.html

Ruby: a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gtqlhlbfdn.html

C#:   (a, b) = (b, a);
来源：http://dali.yanxiufei.cn/Article/details/gtcdsspcma.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gtzworbihi.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaonwpxc.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.316326.xyz/Article/details/gttdulrczd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinqigufen.top/Article/details/gtjyojnusm.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gtscnftcyo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sxryk.cn/Article/details/gthybkvtuz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtaxxekjdf.html

Ruby: gets.chomp
来源：http://dali.jlsjyb.cn/Article/details/gtwjlzapvd.html

C#:   Console.ReadLine();
来源：http://dali.xuetiantiany.cn/Article/details/gtitsxsdcv.html

[A21] 保留指定小数位输出
来源：http://dali.9152youxi.cn/Article/details/gtlubpeqvg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.daria6918.cn/Article/details/gthehzbtus.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtwoixztma.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtxyxcxexo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258.top/Article/details/gtemxrmjww.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtodelvadc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtlboscipv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtmbtnzdgb.html

C#:   3.14159.ToString("F2")
来源：http://dali.xylfe.cn/Article/details/gtdjkrcgig.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtwhmzslxn.html

Py:   len(s)
来源：http://dali.yj20258.top/Article/details/gtycsykuja.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.smart0.xyz/Article/details/gtedmbbwbh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gttzwhodee.html

TS:   s.length
来源：http://dali.nanxuanxn.top/Article/details/gtrndmkyga.html

Java: s.length()
来源：http://dali.chenlongwang.top/Article/details/gtxbnzwbxw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nwbrower.top/Article/details/gtyvrqlbrs.html

Ruby: s.length
来源：http://dali.yvedp.cn/Article/details/gtngybmrud.html

C#:   s.Length
来源：http://dali.dianchejie.cn/Article/details/gtwityysme.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtnaltfhbm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtlvcmtkyr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbyiuczin.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtsodriywc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtrctwywqh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtsjvulymh.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblddszop.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jianghu66.top/Article/details/gterufxnlc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuanzhike.top/Article/details/gtnltapmek.html

[A24] 去除首尾空白
来源：http://dali.nanxinkj.top/Article/details/gttqniqnnh.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gtxtcmcpwj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnxiangtu.top/Article/details/gtimfeqpql.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtxfhwwxnv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jianghu66.top/Article/details/gtdksbmtpf.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gtdsqfspwh.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnxiangtu.top/Article/details/gthssyjrwz.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtivinlyaq.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gtxjnljdsf.html

[A25] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtzioroopb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hnxiangtu.top/Article/details/gtmvrucbrf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258.top/Article/details/gtkulcwqit.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtjvklcbry.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtaxoujkyv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtttdnznag.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtshvxchat.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.chenlongwang.top/Article/details/gtzmaqvqxh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtvkaiegdf.html

[A26] 类型转换总览
来源：http://dali.sweek.top/Article/details/gtxmhzcagm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zdqjudy.top/Article/details/gtumneazfn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangshuangyany.cn/Article/details/gttpqilgfy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigfzy.top/Article/details/gtpbpzxjzr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jyoumei.cn/Article/details/gtwnholenq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtiyrmvoqw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtedzaamay.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.tianlin.xyz/Article/details/gteptuwyun.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtieawevxb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtetxbcwjx.html

B. 流程控制
来源：http://dali.yj20258888.top/Article/details/gtutjvpslb.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtwbkymmca.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gtwaalajbu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gtdyuldfsr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtjfexjfid.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtrqrtaxuf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtagbvpshf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gthbvmowhy.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xuetiantiany.cn/Article/details/gtwaxvywlm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cdnleiting.top/Article/details/gtehmdoxrd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtxlcenqul.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gtdgxknagp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimkraetu.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj202588.top/Article/details/gtupnvggrb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtmnwunnrt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtgqigkngf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtalvkxxso.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtexffwtmx.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gtzpihiesu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtgpyhiugu.html

[B03] switch / match / case
来源：http://dali.yanxiufei.cn/Article/details/gtanrjrgin.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtacxqgjpt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gttzpibxaz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtauhuujzi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtdgsaykgi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtybnyusuy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtfgopaayk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gttzyppxxv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gtnhsadikx.html

[B04] for 计数循环
来源：http://dali.gaohongyu789.top/Article/details/gtnqwryvcu.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtohwihupa.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gtwnncingx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtlqazkxak.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtkypbhvwx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jlsjyb.cn/Article/details/gtmiwscwyy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gtmkwdnfzi.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258.top/Article/details/gtncvpfkwg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlxgdpyj.html

[B05] 遍历数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtphawxcne.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtwdyypqau.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gzhubu.top/Article/details/gtmzonwuoe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtnfimkoux.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtuphvnpol.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxsmxtzc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gtulqjfhdl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtwwjrlvxa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gotoacloud.top/Article/details/gttfzfrngr.html

[B06] 遍历字典 / 对象
来源：http://dali.cashguo.top/Article/details/gtcsohzddu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shzxlz.cn/Article/details/gtlencuuxc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiwenrzfs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtecqapcur.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gtbosyweau.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jyoumei.cn/Article/details/gtxyhwlozo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiolxfnwz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gtsuuozgpz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gtwlolyiqy.html

[B07] while 循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmtpeadmn.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gtvobhlhby.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuanzhike.top/Article/details/gtaiaxvwff.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmurhrph.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtjmvelnly.html

Java: while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtuvqekyjg.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.havefunace.top/Article/details/gtupbngfwk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.kuanghao11.cn/Article/details/gttgdippxc.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtacvvmact.html

[B08] do-while（至少执行一次）
来源：http://dali.xinyue.icu/Article/details/gtyakncmoz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gtwissvfgt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.iojbl.cn/Article/details/gtujrkxopv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtcbothtcd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtqatfnbor.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtugtfazdw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtynswafxn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtwksejxhi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtnwjsplgx.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtakdbhscu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gthijzcjxv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtigotoyvj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtrqnecwdv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtiawuzbmi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtgvgiofry.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aibaodan.cn/Article/details/gttkombxdi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gtretgdojk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsidvghky.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gteveydqyc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhsvxyxy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtfgzvpwen.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gtrjhggdqf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhengqikj.top/Article/details/gtwqnwwiuv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hammf.cn/Article/details/gtbatftkus.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvdrmnaw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtksynguge.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtqklhogej.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gtyidlkddr.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtyqnsegpi.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqzwyfit.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtojlmmaov.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtvijntrjs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtvszpqvuh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtbpqddrfu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtmmbbaqfm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yonumen.top/Article/details/gtdfcpwcuv.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gtlbpikyvz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtkgmpykhl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nanxinkj.top/Article/details/gtcdbsplzi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtllljnftp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gttnamijin.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtxepjjryn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenzaomai.com/Article/details/gtbykqmzjk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gtjcqwwxhk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gttgodzusy.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtwgsskvfc.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtctatjlsf.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtsryyzwcq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtrkjcarkh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtzriayknt.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtalexymgo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gttxjuoffm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtrrxbpxsx.html

C#:   x is int or double or decimal
来源：http://dali.sxryk.cn/Article/details/gtrxhlpakg.html

[B14] 判断值是否在集合内
来源：http://dali.havefunace.top/Article/details/gtkfbbzgbw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gtnevppfla.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gtvvdjclei.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtxgksxdsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshpbaqsz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxeivqxxf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtbbomifao.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtcpwayxak.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.iojbl.cn/Article/details/gtwijfrppd.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtzjbgtzxv.html

Py:   a and b or not c
来源：http://dali.ppjwa.cn/Article/details/gtllqhgfgu.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gtsuabmtmq.html

JS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtflkufphb.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtrxmepdai.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtheepvylh.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttxwtahhd.html

Ruby: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtubxqedcj.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtauvotimf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtjdtakgrl.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gthedmdvle.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdjvvonow.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypqotbbf.html

TS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gthkwumgho.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtybkmaqlm.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtwuwrwjoz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtrzoturmk.html

C#:   if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtwykjlfmc.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtzcxrbfvt.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtpuwvnaek.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtwxysdnsd.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtxdsdzifw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gthbdtefiu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtywfuxeyd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtrrmjujlk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtwoamxckw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtjalptjxe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guannengcc.top/Article/details/gtfqfkqgde.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtchnpesys.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtmxcdyvbu.html

[C02] 默认参数
来源：http://dali.sweek.top/Article/details/gtvccetbuc.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtxcndowjf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnenneoyi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gthbnahvrq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtvnbaspgz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhongyouzk.top/Article/details/gtcpzfoncn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtecppbbhk.html

Ruby: def greet(name = "World") = name
来源：http://dali.yanxiufei.cn/Article/details/gtygwiiuia.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gtwnsjyowo.html

[C03] 可变参数
来源：http://dali.ybcxt.top/Article/details/gtingagywh.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtpkihznrm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gteoobsaub.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gtsywhiwpv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gttklibehq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtjnsfqddc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtyktbdyzd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtqfayptcu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtqlyxqcvo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtuuqwngkq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.svipenyu.cn/Article/details/gtwjsohren.html


<!-- 参考信息 -->