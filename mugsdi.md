代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.ydzc1.top/Article/details/gtlgwvqcmf.html

TS:   const value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtsgimatky.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.pycfn.com/Article/details/gtfkspgagi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.redwolf501.top/Article/details/gtklwhuvax.html

Ruby: value = data || "默认值"
来源：http://dali.smart0.xyz/Article/details/gtexcpgkuw.html

C#:   var value = data ?? "默认值";
来源：http://dali.yongpay.top/Article/details/gtpghcooae.html

[A16] 真假值判断规则
来源：http://dali.shangyingyoupin.top/Article/details/gtuzpipybn.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.nanxuanxn.top/Article/details/gttjfdqhei.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gthmdfgedn.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xuetiantiany.cn/Article/details/gtlmlgxvfh.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtouxxnekw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.sysykeji.top/Article/details/gtchsytjck.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gtjhxurvsx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.meibo888.top/Article/details/gtcjdnpskx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtetlnqvpa.html

[A17] 位运算
来源：http://dali.daxiang520.top/Article/details/gtwkcbaxtj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cdnleiting.top/Article/details/gttkitiovc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.andypj.xyz/Article/details/gtmsxfunev.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtgabgqiju.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtpwqwoenc.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtpotclxcq.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtryalitku.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtvezdvnao.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtgssobibb.html

[A18] 字符与 ASCII 码互转
来源：http://dali.316326.xyz/Article/details/gtyruylgcl.html

Py:   ord("A"); chr(65)
来源：http://dali.redwolf501.top/Article/details/gtjvrirqsu.html

PHP:  ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gtlhvsuafo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gtzfbdxzhy.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shangyingyoupin.top/Article/details/gtihrxyhqk.html

Java: (int) 'A'; (char) 65
来源：http://dali.ydzc1.top/Article/details/gtxudxpohl.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhoulong.xyz/Article/details/gtaushgjgq.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhoulong.xyz/Article/details/gtmdtlioiv.html

C#:   (int)'A'; (char)65
来源：http://dali.xuetiantiany.cn/Article/details/gtrvraicgr.html

[A19] 交换两个变量
来源：http://dali.dashuyun.cn/Article/details/gtwuauoqug.html

Py:   a, b = b, a
来源：http://dali.ehwqpu.com/Article/details/gtwtzvwucl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cheryme.top/Article/details/gtmogauioa.html

JS:   [a, b] = [b, a];
来源：http://dali.jqgufenzy.top/Article/details/gtypkpltbq.html

TS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtsayrrgsr.html

Java: int t = a; a = b; b = t;
来源：http://dali.ppjwa.cn/Article/details/gtrqqpwozz.html

Go:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtpsygophq.html

Ruby: a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtcnrlgihq.html

C#:   (a, b) = (b, a);
来源：http://dali.shangyingyoupin.top/Article/details/gtjstxrueg.html

[A20] 读取标准输入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjwtwsgso.html

Py:   name = input("请输入：")
来源：http://dali.iojbl.cn/Article/details/gteaxttvxs.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tianlin.xyz/Article/details/gtkfwskrbb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.quarkkingdee.top/Article/details/gtcrgtjott.html

TS:   // Node.js：readline 模块
来源：http://dali.snrcjt.cn/Article/details/gtmrhjjclx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtsbjkxegt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenjidiqi.icu/Article/details/gtbugwqicu.html

Ruby: gets.chomp
来源：http://dali.jiagoushi.top/Article/details/gtxlottwxm.html

C#:   Console.ReadLine();
来源：http://dali.sufxvd.cn/Article/details/gtqjdwnmyg.html

[A21] 保留指定小数位输出
来源：http://dali.ydzc1.top/Article/details/gtzzvbyvtw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gthllfllic.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.iojbl.cn/Article/details/gtstsstykr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.fzhhl.top/Article/details/gttkwfopuv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtuqfjbrje.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gtszctuozz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtxosnvagk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtokfjrcxm.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gtlupjyiiz.html

[A22] 获取字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtpeyewvye.html

Py:   len(s)
来源：http://dali.dianchejie.cn/Article/details/gtzfcigzrr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hongshengwenyu.top/Article/details/gtpjkmoyrb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jyoumei.cn/Article/details/gtduvqodul.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gtyztyftdg.html

Java: s.length()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhxewvui.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhijiandao.cn/Article/details/gthyhwfikd.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gtdwolqbvj.html

C#:   s.Length
来源：http://dali.tanke756.top/Article/details/gtvqwcutur.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtmvtiktwk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gthzrhunnm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yueranfly.top/Article/details/gtzfgihzuh.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtqvhnonxg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gtvpfsslsf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtdqxkcouy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcastcegp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nanxuanxn.top/Article/details/gtwkxwbtud.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jyoumei.cn/Article/details/gtvzodrkex.html

[A24] 去除首尾空白
来源：http://dali.jiagoushi.top/Article/details/gttiwdhkpr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.guowangkeji.top/Article/details/gtdhqfhgjh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xinyue.icu/Article/details/gtmpkmavif.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtausqotrr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtvcvrrptn.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.pengpengdd.cyou/Article/details/gtnopwlbeq.html

Go:   strings.TrimSpace(s)
来源：http://dali.jqgufenzy.top/Article/details/gtwrmcmjwf.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.iojbl.cn/Article/details/gttscpzmdx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtiaficytb.html

[A25] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtvziozrsj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tianlin.xyz/Article/details/gtqklztlqs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkqirtqz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yj20258888.top/Article/details/gtdqqkbets.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cdnleiting.top/Article/details/gtetytleke.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yvedp.cn/Article/details/gtqyzcpwzo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtsiddohjd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.redwolf501.top/Article/details/gtudmidyth.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtcickbyga.html

[A26] 类型转换总览
来源：http://dali.jinqigfzy.top/Article/details/gtmxspmqdt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigfzy.top/Article/details/gtpnrvubby.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shzxlz.cn/Article/details/gtadrmzkxx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gthqzdkhrm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gtprmqoaao.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gtqwprzqnt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gttcgprohg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gtopxmkssg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtlianmpuo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtqnpmlmnv.html

B. 流程控制
来源：http://dali.ppjwa.cn/Article/details/gtfgbmltby.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxdcoilwx.html

[B01] 条件判断 if / else
来源：http://dali.ehwqpu.com/Article/details/gtsmuxqdza.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj202588.top/Article/details/gtdcktlxfi.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xylfe.cn/Article/details/gtutmhsclq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtcqmvqmpv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtznqsuovy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shzxlz.cn/Article/details/gtrsorntgo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gthfrrugqs.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtozdegmam.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtwuzqplhs.html

[B02] 多分支 else if / elif
来源：http://dali.feifeiyinyue.top/Article/details/gtpyyejzas.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nanxuanxn.top/Article/details/gtgtkevkxi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258888.top/Article/details/gtvuietowb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gterxsioww.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gtruejdbkn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtwtawdfei.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.mhx1999.top/Article/details/gtymmxxwyv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuqlfmfh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtojxhpcnu.html

[B03] switch / match / case
来源：http://dali.chenzaomai.com/Article/details/gturjcfdri.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.gaohongyu789.top/Article/details/gtmjukltij.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtaowkvgey.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtjcxlynwh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtbhsruwqa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtvaqrhnoc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtkuwyeqai.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gtnacvcbkc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtjsnbjvgq.html

[B04] for 计数循环
来源：http://dali.xylfe.cn/Article/details/gtgckyivnh.html

Py:   for i in range(10): print(i)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgybnnqbr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuanzhike.top/Article/details/gtvwsheloo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.svipenyu.cn/Article/details/gtbmijmrvo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtnnaovexe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cucudq.cn/Article/details/gtvgynvdry.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gthkuevapv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtrpaaaguf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.haohaochexian.top/Article/details/gtovmdylin.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gtdezyraeb.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtljffozqd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuoamwjuf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpwbageto.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtdrjsnegc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gttmbpfcqi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtzxxyssyi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gttiazeyib.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gtumbvwkzg.html

[B06] 遍历字典 / 对象
来源：http://dali.hammf.cn/Article/details/gtdxfetpgo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtiwftepzz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gtpwgsnmxm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtgkrgbuvt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqinupevu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gtklrupgwf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gthztzqerg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sysykeji.top/Article/details/gtshtcojxr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gtzmepumti.html

[B07] while 循环
来源：http://dali.aizwys.cn/Article/details/gtdnyklgso.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtqqyazsdg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtardipzkd.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtwewvtvwj.html

TS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtgnfhrbwr.html

Java: while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkicxovzt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gtnlkbklxv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtzgxshpsl.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gttudkilqe.html

[B08] do-while（至少执行一次）
来源：http://dali.aibaodan.cn/Article/details/gtsbviethq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtgfrnrjlp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gthrubkujq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtcfxfbfla.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtgdtvffqa.html

Java: do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtlbzavfvv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gtzhmdrobw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigufen.top/Article/details/gtyttjaicg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtcgrzapbc.html

[B09] break 与 continue
来源：http://dali.316326.xyz/Article/details/gtybmbickb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtnrttovic.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtqrajhgmq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtenxluhap.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtuprzbhoc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtqjznqhrs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ybcxt.top/Article/details/gtmxmqmvvh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangdashe.top/Article/details/gtjebofibz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtjyxjxriy.html

[B10] 遍历同时拿索引
来源：http://dali.yongpay.top/Article/details/gtnafxcyvh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gtxjkrncod.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwytragsq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtqzrxbbcy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtvdzerhxh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zdqjudy.top/Article/details/gtcqlitxpj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtmhnbbwae.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guannengcc.top/Article/details/gtfymzsgke.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtkcrkiiea.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtaubqooan.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtcihbzmif.html

PHP:  range(0, 10, 2);
来源：http://dali.birdmap.top/Article/details/gtcqjtuwfa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtosthcpsq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtbonkkpki.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtpsvedelv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtwbmvowvy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtcajyqigi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.0kj1m.cn/Article/details/gtlidlsoma.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcoyyawvn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtaewjrybz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gtvtuolzbu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtjnwjvzal.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtprryrkdw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtybwvwvhk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtygvzxeyo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtwskwenbq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtforwtisp.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtgjjoolty.html

Py:   isinstance(x, (int, float))
来源：http://dali.ppjwa.cn/Article/details/gtexblipsl.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtaledvgbm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtogqdbfwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtbkridyjc.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtrzxdthwn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtelowashe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gtcbgsbsqj.html

C#:   x is int or double or decimal
来源：http://dali.andypj.xyz/Article/details/gtoioscqje.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtfmmidpvn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gtmplyyfig.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gthaiadwce.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtkobixils.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvvorlewg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtiirlvpwp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtysjqbats.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtkiazbfly.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrxmllcwt.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtgbrlmdvm.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gtcghmqjyk.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtlumnbeks.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtyilhvjvs.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtjoqcozhv.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtznnxxcuc.html

Go:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmsonepcu.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtagfdfasu.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtxhbnukhx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gtcndupfkg.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gtrrzzfnhx.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvopblwox.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtwraiqbob.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhxrbrbg.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtpakdbzmx.html

Go:   if data == nil { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikrfsien.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gtdcviogsq.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtwnseubfb.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvbuxbvqm.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gtkxfgdjkz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnzhvigcg.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtylagfmal.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgfzy.top/Article/details/gtulnsqirk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtwuqllvmd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxdvfygan.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtkfjovesw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtkkfcmkbc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtngvbllug.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtcpvgyarn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtuqzryvtl.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsenywmhc.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtqulwqxhj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtywuakadb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gteweeirfx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtpzsullla.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aizwys.cn/Article/details/gthxedoish.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gttfqbphsw.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtqtuhwlaw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sufxvd.cn/Article/details/gtzprsatpw.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtfoytfata.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtlajqssjk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hywenlv.cn/Article/details/gtfuadfeye.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gttwtiiuap.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvfcgryi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtmjqxgxoz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtlqpirmcp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtffodznby.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtdpbemmvz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtrkrjdnkj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtwgvqxfcg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtebuzhonb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtafcjjxot.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gttivfxfbl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtgpsyhdac.html

Go:   // 无：用配置结构体参数
来源：http://dali.nwbrower.top/Article/details/gtslwauoqd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtqjrlkhrc.html

C#:   f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtgloeexnp.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtuqdyqhik.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtcjwnbaze.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtffoctokv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtbrffmfji.html

TS:   return { a, b };
来源：http://dali.gzhubu.top/Article/details/gtxjnjsqgn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtbtgaayqs.html

Go:   return a, b
来源：http://dali.yj20258.top/Article/details/gtrlfiradx.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtbuwnztvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtshumsaue.html


<!-- 参考信息 -->