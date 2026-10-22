代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.aibaodan.cn/Article/details/gtosvztucm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.havefunace.top/Article/details/gtfhuzyxtf.html

TS:   if (!x) {}
来源：http://dali.9152youxi.cn/Article/details/gthibdprpp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtkjeidmqu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shangyingyoupin.top/Article/details/gtoyhvpquc.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhoulong.xyz/Article/details/gtzumagmyp.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.daria6918.cn/Article/details/gtvziropek.html

[A17] 位运算
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhvdhaud.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtomydmeks.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.daxiang520.top/Article/details/gtlppysxdq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtqykbwvoy.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtvgsgyjxj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtbnsmkgpa.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gtnuqoagds.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtqxnwmrsd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtoufcpqie.html

[A18] 字符与 ASCII 码互转
来源：http://dali.wangshuangyany.cn/Article/details/gtpnpntkww.html

Py:   ord("A"); chr(65)
来源：http://dali.yuxming.cn/Article/details/gtflarlljn.html

PHP:  ord("A"); chr(65)
来源：http://dali.wangdashe.top/Article/details/gtoljytvmm.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtgrzznffv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtpjxqaqrh.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhgxpmgb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xziqi.cn/Article/details/gtcqohtkgs.html

Ruby: "A".ord; 65.chr
来源：http://dali.sufxvd.cn/Article/details/gtdhveycns.html

C#:   (int)'A'; (char)65
来源：http://dali.fengsongda.top/Article/details/gtfpyxlcvk.html

[A19] 交换两个变量
来源：http://dali.xuanzx.com/Article/details/gtysyaagyp.html

Py:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtffnyskoz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtvwvgnpnw.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtbjrcazie.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gtztrmbywb.html

Java: int t = a; a = b; b = t;
来源：http://dali.cqqwz.cn/Article/details/gtlpxuwtjx.html

Go:   a, b = b, a
来源：http://dali.chenjidiqi.icu/Article/details/gtzmhvrzts.html

Ruby: a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gtgihgwhjn.html

C#:   (a, b) = (b, a);
来源：http://dali.jqgufenzy.top/Article/details/gtnnnhdimq.html

[A20] 读取标准输入
来源：http://dali.yj20258.top/Article/details/gtmvbjdbzf.html

Py:   name = input("请输入：")
来源：http://dali.0kj1m.cn/Article/details/gtraolvbyt.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gtzbmipdwo.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.pycfn.com/Article/details/gthgiqvuky.html

TS:   // Node.js：readline 模块
来源：http://dali.cqqwz.cn/Article/details/gtijixbchh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnqzz.top/Article/details/gtqmdlfjyu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhengqikj.top/Article/details/gtyfytvpac.html

Ruby: gets.chomp
来源：http://dali.chenzaomai.com/Article/details/gtfppnhfcm.html

C#:   Console.ReadLine();
来源：http://dali.guowangkeji.top/Article/details/gtnlvivfrv.html

[A21] 保留指定小数位输出
来源：http://dali.zhixingplan.top/Article/details/gtiycqpbjn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hammf.cn/Article/details/gterwzftao.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gtxzyirvea.html

JS:   (3.14159).toFixed(2)
来源：http://dali.feifeiyinyue.top/Article/details/gtlqgjnveo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtnmjhcnsr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkkepcjc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtfmjzjsgp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtexdjuojs.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtmiosoiom.html

[A22] 获取字符串长度
来源：http://dali.havefunace.top/Article/details/gtzdxllpip.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtewmkepzg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmjnwfwl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.wangdashe.top/Article/details/gtmlhaxviz.html

TS:   s.length
来源：http://dali.zhijiandao.cn/Article/details/gtrnfezbbc.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gtyogmkxjj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gtdiiiwsoy.html

Ruby: s.length
来源：http://dali.ehwqpu.com/Article/details/gtgyrdopix.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gtpvsbfypl.html

[A23] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtlwixmyhl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gtnujbxgmb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ydzc1.top/Article/details/gtvgloqjls.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj202588.top/Article/details/gtyblpyjbm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gttfkihjcd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gtjdqhzcsi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jyoumei.cn/Article/details/gtmvkjuvbb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shuidangran.top/Article/details/gteiloaazt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gtgtwtpzok.html

[A24] 去除首尾空白
来源：http://dali.zhongyouzk.top/Article/details/gtdouktskq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gotoacloud.top/Article/details/gtnbjjylro.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtwvirbkfn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtwzqkipob.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gttcdtdxza.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.tianlin.xyz/Article/details/gtnoselhfg.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gteiqskjlh.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gttpwnkavo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xinyue.icu/Article/details/gtyilhzbin.html

[A25] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtrinqbkyw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.bjfxy.top/Article/details/gtgfvqdesu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.chenzaomai.com/Article/details/gtesefstnm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.havefunace.top/Article/details/gtcgzeqiyc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtiygeetkk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxmbhlvk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvpxwyyqa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jqgufenzy.top/Article/details/gtzeztnauq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtwlyqgucc.html

[A26] 类型转换总览
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqgpuzzaj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gtdkbtnyop.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxavnzfvj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yonumen.top/Article/details/gtomwlpxzy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cqqwz.cn/Article/details/gtdikmbaal.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gtcesqkxjj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sysykeji.top/Article/details/gtbkaheuex.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xinyue.icu/Article/details/gtwmguindi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.vqdsnc.cn/Article/details/gtxceamufa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzdwvyexq.html

B. 流程控制
来源：http://dali.redwolf501.top/Article/details/gtedbzgfjs.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtskdygkca.html

[B01] 条件判断 if / else
来源：http://dali.xinyue.icu/Article/details/gtqcuwycmi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fengsongda.top/Article/details/gttlbacxwe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtjleviaqz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gttcprotas.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gtaqrykrvx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtgjgsnqut.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtocalstln.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gtauqmqchu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtjulotsbg.html

[B02] 多分支 else if / elif
来源：http://dali.yonumen.top/Article/details/gtkttrtmuq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.dashuyun.cn/Article/details/gtjzffuxua.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yonumen.top/Article/details/gtagtlhqxe.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtuoxywpja.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtlqpcrhun.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtfiyjqrww.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtammxpdos.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtuhizprdz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtwhmhbdwo.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gtrjwfjqgl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.bjfxy.top/Article/details/gtnerrkspw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkvxrhfny.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtezdmifse.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gthitgnvua.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtfktfdxwn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gtboufpzlr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zdqjudy.top/Article/details/gtoportwoh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtvudrvtnu.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtsmdcomtz.html

Py:   for i in range(10): print(i)
来源：http://dali.jiagoushi.top/Article/details/gtxynnsapx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpktpagmy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gtuojonlep.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtaeytowwk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xinyue.icu/Article/details/gtlbagttxs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gtcqttebya.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hongshengwenyu.top/Article/details/gtufoextaw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtqyyydyrb.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gttqaqconn.html

Py:   for item in arr: print(item)
来源：http://dali.nanxinkj.top/Article/details/gthhlurfew.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuanzhike.top/Article/details/gtxhrrnqyy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtwftdmbud.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtamspixti.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtlnzfgobv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gtktbgxaya.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gtxnptufsg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtructztti.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtqfasdlpd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ydzc1.top/Article/details/gtcgswncpv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gtncwynhyd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtldajpyyy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtleofnjjq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcepiekbf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtpzaurnzz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jiagoushi.top/Article/details/gtxhejcmho.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtstuxqcra.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gtnylehhcj.html

Py:   while i < 10: i += 1
来源：http://dali.sxryk.cn/Article/details/gtfjkrkgeu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtomtiajhg.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtypioxuto.html

TS:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjjglqya.html

Java: while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtewxhrbfk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtivgpzcsj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guowangkeji.top/Article/details/gtqohpegvz.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtmuowtmcu.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtkfloufai.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtbdtsnuzk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtauiebwtw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtkmmsrtwd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtezwvrtau.html

Java: do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtiyvcfnxn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtsnmrlwzw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnqzz.top/Article/details/gtpbdwwuqk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtydkqgtwg.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtfiscodky.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuanzx.com/Article/details/gthinvsgnd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gttismcmdd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzwuyuib.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtzkwssfjr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gteoctjiqm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtsfndhsgt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ehwqpu.com/Article/details/gtjzksktzn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtvlvevpbr.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtljtravbp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtkwwwghny.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gtkncmsimb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtnpggadpc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gtbycuyzkt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtlkwfismc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.vqdsnc.cn/Article/details/gtsmwevtyf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.snrcjt.cn/Article/details/gtrxiowqjq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gtnfvuxdps.html

[B11] 生成数字序列 / 区间
来源：http://dali.zycfv.cn/Article/details/gtrztivakz.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gtlrcxpzxd.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtabzsminl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtdsjbaumu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtpbzadwzq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zycfv.cn/Article/details/gtdjixywow.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdftyrort.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gtrxceimio.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpmdwofd.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gtladrmrfn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtemyaiomz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtxnpbpifn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtckntlybr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtbrddaugp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtkgmgzwon.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtjkfypfip.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtsokdfrhj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhengqikj.top/Article/details/gtyplsqsxq.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtmulfrrlj.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gtqeiwdfch.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gtvfobinim.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtljfzggoy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdxhfgivk.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtotlvlrwg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtnjjxilxj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqnbqjlt.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqyifchl.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gtucglqqda.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gtppsmzdbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtxlcwhkji.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtmvhqzplo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtvykspvpk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtfxyeyhng.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtqyxoarll.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hammf.cn/Article/details/gtpzoeirfx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xinyue.icu/Article/details/gtdreogsgn.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtkpcbhecx.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gtfxehflas.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtdmsofcey.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtzpmzqrft.html

TS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtlppdvswu.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtaxxkqaks.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtjbpcoigu.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtkemgtiga.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtdfcirccx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.snrcjt.cn/Article/details/gtcjxxibuz.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtstzzjqhh.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtqizptwqx.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtkjlqbvym.html

TS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtmxtvokrp.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtvnkgjzxz.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtyqbnplhx.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtxuvotoei.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtourlhlvk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvvnyfemd.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtsrysujyp.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqhduvsmj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtbpbvvywm.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtwucbtfnj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtmloyzjsr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtxgciiqor.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtiwaynucs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtqgfqbzfu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtruzldwim.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fengsongda.top/Article/details/gtkttwlpis.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtjtouvcao.html

[C02] 默认参数
来源：http://dali.yueranfly.top/Article/details/gtktkflcud.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtjfshhvms.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtdxrxrcrz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtvscdfcph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtndwekeno.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtxhooldnk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.vqdsnc.cn/Article/details/gtwblilkcp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnhvhtve.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtxdozybom.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtezsioywy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnglceldh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sxryk.cn/Article/details/gtllqncbvc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdasvyyti.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyytzllw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtubcbwmtv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtxzkqxxfb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtabxygesn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gtwstpvrpj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtbehplgyh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtredeiqez.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gthlfmgsuo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gtawtargsp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gtaigrczcl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtnaybihxm.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtxexgwdjw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtohvtqpxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtproqgvab.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtankkmzec.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtumouik.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtqzagpgau.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtvxaplafh.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtaputxubf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtcofkwean.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtkoxdusza.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpshgugs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gttnjzgbon.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtlmualejp.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtcmqwhkga.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuanzhike.top/Article/details/gtcjputrzw.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtxmchejbl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtbrtfbudy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtllwymfku.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gttlbpkefl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtloxsydgs.html


<!-- 参考信息 -->