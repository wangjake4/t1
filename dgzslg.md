代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.guowangkeji.top/Article/details/gtdbomfqbm.html

JS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gtybrjdbdo.html

TS:   `Hello, ${name}!`
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquflchmq.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhijiandao.cn/Article/details/gtagukmlcg.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.tian-w.cn/Article/details/gtdpvlzzhk.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtlvdwkhdz.html

C#:   $"Hello, {name}!"
来源：http://dali.ybcxt.top/Article/details/gtnwchhxfx.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.sxryk.cn/Article/details/gtqicdhtsn.html

Py:   "第一行\n第二行"
来源：http://dali.andypj.xyz/Article/details/gtcxkpjjhv.html

PHP:  "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtyiaqmqvf.html

JS:   "第一行\n第二行"
来源：http://dali.pycfn.com/Article/details/gtrzjewysa.html

TS:   "第一行\n第二行"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdhidhzj.html

Java: "第一行\n第二行"
来源：http://dali.guowangkeji.top/Article/details/gtdgxzokik.html

Go:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gtkqfmhjph.html

Ruby: "第一行\n第二行"
来源：http://dali.yj20258.top/Article/details/gtennvwphp.html

C#:   "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gthcymhtue.html

[A14] 注释写法
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajeiezgo.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.pengpengdd.cyou/Article/details/gtlnfcfmos.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.chenlongwang.top/Article/details/gtrlsrfqvz.html

JS:   // 单行；/* 多行 */
来源：http://dali.zhoulong.xyz/Article/details/gtezrbenrl.html

TS:   // 单行；/* 多行 */
来源：http://dali.zhixingplan.top/Article/details/gtawlwzsks.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jiagoushi.top/Article/details/gtskijslno.html

Go:   // 单行；/* 多行 */
来源：http://dali.cdnleiting.top/Article/details/gtxzscnsem.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gthcidpsps.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtdbzscyqh.html

[A15] 空值判断与默认值
来源：http://dali.zhengqikj.top/Article/details/gthuemfaqr.html

Py:   value = data or "默认值"
来源：http://dali.xuanzx.com/Article/details/gtrgbcaulx.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtiuilzosc.html

JS:   const value = data ?? "默认值";
来源：http://dali.nanxinkj.top/Article/details/gtgfdkinwg.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtbcuqplhe.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fengsongda.top/Article/details/gtaljvovxm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.feifeiyinyue.top/Article/details/gtkulqjxab.html

Ruby: value = data || "默认值"
来源：http://dali.zhengqikj.top/Article/details/gtaifxomat.html

C#:   var value = data ?? "默认值";
来源：http://dali.xuetiantiany.cn/Article/details/gtltwbbzxj.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtjknbcgym.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkcadtgha.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xinyue.icu/Article/details/gtwxugdlog.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.gotoacloud.top/Article/details/gtsfnpcnuo.html

TS:   if (!x) {}
来源：http://dali.gzhubu.top/Article/details/gtpcjgebcz.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gtyhqizneg.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cdnleiting.top/Article/details/gtxpqajoyy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sysykeji.top/Article/details/gtkppakjcx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.sweek.top/Article/details/gtzomzyoxu.html

[A17] 位运算
来源：http://dali.zhixingplan.top/Article/details/gtixxiymtv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtnrrcpior.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtayruthdr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtjptsxuhn.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtqpllsaut.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtdkcuttjt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtankkkajc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gtocdhjeyr.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtgjtjauje.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtdrzbotsi.html

Py:   ord("A"); chr(65)
来源：http://dali.guannengcc.top/Article/details/gthywdhfuj.html

PHP:  ord("A"); chr(65)
来源：http://dali.daxiang520.top/Article/details/gtfazhzeak.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj20258888.top/Article/details/gtjjtdzakp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gtuvmqjrmv.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gtbskkmvef.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hfpthk.cn/Article/details/gtxhzwdwyi.html

Ruby: "A".ord; 65.chr
来源：http://dali.jlsjyb.cn/Article/details/gtjpvvqebh.html

C#:   (int)'A'; (char)65
来源：http://dali.yvedp.cn/Article/details/gtorndhmkm.html

[A19] 交换两个变量
来源：http://dali.shzxlz.cn/Article/details/gtutyhpqzh.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtxzxwokxa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yueranfly.top/Article/details/gtvhtnayqc.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtbrxrvbqr.html

TS:   [a, b] = [b, a];
来源：http://dali.tian-w.cn/Article/details/gtzksgsiyr.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gtguyajbna.html

Go:   a, b = b, a
来源：http://dali.xziqi.cn/Article/details/gtzkhzvxor.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtqxhewwwb.html

C#:   (a, b) = (b, a);
来源：http://dali.feifeiyinyue.top/Article/details/gthbeliews.html

[A20] 读取标准输入
来源：http://dali.dianchejie.cn/Article/details/gtwqemaghk.html

Py:   name = input("请输入：")
来源：http://dali.zhoulong.xyz/Article/details/gtzckuawsb.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ydzc1.top/Article/details/gtvnrhiank.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gtywvamhrx.html

TS:   // Node.js：readline 模块
来源：http://dali.smart0.xyz/Article/details/gtawljuvge.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pengpengdd.cyou/Article/details/gtmukumkgo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gtbkjwaqrq.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtdmhrfdvn.html

C#:   Console.ReadLine();
来源：http://dali.cashguo.top/Article/details/gtvctqbned.html

[A21] 保留指定小数位输出
来源：http://dali.andypj.xyz/Article/details/gtlsqkxtpe.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yvedp.cn/Article/details/gtpzuevkjw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtrytcqekt.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xziqi.cn/Article/details/gthmcdeovg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtropurxbb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jqgufenzy.top/Article/details/gtnoamuclz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gtgbudxsck.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtfnbowhyx.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gtfvsykcyf.html

[A22] 获取字符串长度
来源：http://dali.redwolf501.top/Article/details/gtqrupnvzw.html

Py:   len(s)
来源：http://dali.yongpay.top/Article/details/gtzhcxkeyk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yvedp.cn/Article/details/gtiyjwxxpw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hnxiangtu.top/Article/details/gtehueujly.html

TS:   s.length
来源：http://dali.jqgufenzy.top/Article/details/gtvdusjnhf.html

Java: s.length()
来源：http://dali.nanxuanxn.top/Article/details/gtaxftyrxi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258888.top/Article/details/gtiqahvehv.html

Ruby: s.length
来源：http://dali.zdqjudy.top/Article/details/gtqffdcbeh.html

C#:   s.Length
来源：http://dali.hongshengwenyu.top/Article/details/gtvxoajilh.html

[A23] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gtxpfuqblp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gthtqdlkuo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nanxinkj.top/Article/details/gtqcfdmoym.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtaencntma.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtehbibhkt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gtfoxwkebb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ybcxt.top/Article/details/gtlkbtigsi.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ybcxt.top/Article/details/gtajqaupfs.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shuidangran.top/Article/details/gtnsrxrilf.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangtech.top/Article/details/gtevrcgvfq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.c1oappe.top/Article/details/gtnqljuwzy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj20258888.top/Article/details/gtlqrvpfry.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtkuauqfed.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtzbzrdmih.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlsttbep.html

Go:   strings.TrimSpace(s)
来源：http://dali.meibo888.top/Article/details/gtyolwxitp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtopunibtz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtwlqaybph.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtkblxcqwy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gtqqsjsbyn.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shzxlz.cn/Article/details/gtblacjpvl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtjxnzljtn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnylwzalt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtgnnrwgge.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtmilbapmw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.meibo888.top/Article/details/gtpuhswvrc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gthccsgcrb.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtdvovaeat.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.feifeiyinyue.top/Article/details/gteqfmkjiv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.bjfxy.top/Article/details/gteuzmwkjo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.iojbl.cn/Article/details/gttomdbzdw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gtqtkpageb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxsrqyrn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.chenzaomai.com/Article/details/gtepgsgeil.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtkipdaykw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtqeckvcsj.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpdcihytn.html

B. 流程控制
来源：http://dali.wangshuangyany.cn/Article/details/gtocrsexsg.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtsirskznb.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtaaolcaqr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtdxxekccl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtzoedznyu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gthocvzxwl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtswvawjxa.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gtygjugeca.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gttwolygco.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuanzhike.top/Article/details/gteeltdtoc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtzyeakfvi.html

[B02] 多分支 else if / elif
来源：http://dali.chenlongwang.top/Article/details/gtqhsrdiux.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ybcxt.top/Article/details/gtjvoioslx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yueranfly.top/Article/details/gtnsydgqyi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtmzjzopnt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtdzpjkids.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtbqqewyzv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtybjfbqzz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtbmycupki.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtnodatigk.html

[B03] switch / match / case
来源：http://dali.dashuyun.cn/Article/details/gtupkhripc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gtxzemfsph.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtgddbxyir.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtevmjvmtf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtcmdqyxqd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdjdvhfu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gtacqfikqh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.vqdsnc.cn/Article/details/gtdrgpwvyq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtnsinvygb.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtfukwxecn.html

Py:   for i in range(10): print(i)
来源：http://dali.redwolf501.top/Article/details/gtpynygnkm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjuuuszrm.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gtcbzgohfr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtiontmoxa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258888.top/Article/details/gtzixmmcqz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yongpay.top/Article/details/gtlrowwzig.html

Ruby: 10.times { |i| puts i }
来源：http://dali.0kj1m.cn/Article/details/gttyhadsoj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gtifdpkcvb.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gthwfgxczj.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gtovibhtza.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gthrydktbq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtztihrxke.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtwxoqxqni.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtnligljjh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sxryk.cn/Article/details/gtrsdzgxvu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtffewnzow.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtafzsvaxs.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtqngqzsqv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj20258888.top/Article/details/gtfyvvadxb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtwhaqiims.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sweek.top/Article/details/gtccmkcnjd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yvedp.cn/Article/details/gtvaroxofs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtritiznbd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gtkptqcdbr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtsdstjolp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gtltqvqvqk.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gtphtiigye.html

Py:   while i < 10: i += 1
来源：http://dali.fengsongda.top/Article/details/gtrdwetzaz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtwfcircbv.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtjnuhazfo.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtqfevxtbw.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtvkwtenry.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.wangshuangyany.cn/Article/details/gtdltgkwua.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnqzz.top/Article/details/gtuprsdhpk.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtuzqukwrg.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtopgxgmec.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gtfzsvleoq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtwbxyxzmr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtypmopxuj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxjhrwuc.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtalhwnwwv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gtharowrlp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.9152youxi.cn/Article/details/gtfiatsxjw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtmjykozay.html

[B09] break 与 continue
来源：http://dali.xuetiantiany.cn/Article/details/gtgxwgohah.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtjybzbryr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtesylwgcy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtsrydxrhs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtwxzixxop.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtnlrqcrjh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtjngontzw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gtximtjgid.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtcwxaeieu.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gtedpedajj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jyoumei.cn/Article/details/gtauqogkhn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtpstlqmkw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttrmitkx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtzbsrpaws.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gtfxjvfuji.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.dianchejie.cn/Article/details/gtdimqjief.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtakmfyiyj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gtbomuulmf.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtypiimoud.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gtjsmjwruw.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtoaonlwlx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtlaewdvtu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtondwxpot.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gtanyuxvtf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtawexbfgu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.bjfxy.top/Article/details/gtadtwkver.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gttcthbapt.html

[B12] 跳出多层循环
来源：http://dali.yanxiufei.cn/Article/details/gttpjgfthf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gthhkvkynw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtvvofybaw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtjdbjasbl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtqoyzohke.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtelmrjdxg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hongshengwenyu.top/Article/details/gtfacwyloz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtrzddmmln.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gthikalbrb.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtsfcseurz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtvkbttlcq.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gtzwwdymdh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtluskoulm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtwsmcyqsj.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtzjdlukwu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gtvbhexlva.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtcdffnmvj.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtypwdwsrn.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gtqudioyzw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtlkblexea.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtamnbvhkp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cashguo.top/Article/details/gtftqroltt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtosongwoh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gtbttcugqp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtnegpqsbo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gtwsowttnk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtqlvjhnze.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtkqxxuxaa.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtfyzhncny.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtfyxlxqhx.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gttxwsckwp.html

TS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gticfqilqx.html

Java: a && b || !c
来源：http://dali.ivvv.top/Article/details/gtdaoubxyx.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtqrogssbh.html

Ruby: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtjxgiidmg.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtxgetherk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtsottiymo.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtzhgvrfpv.html

PHP:  if (!$data) { return; }
来源：http://dali.tianlin.xyz/Article/details/gtpctmkmtl.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtutozfoag.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtdpvzokoa.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtxygxzviu.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtlzogjwza.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtmalnopfx.html

C#:   if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gtzkfbjnwb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtjzviovcw.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gtqvulrnui.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtpdemodzu.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiunydupd.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtncvqiuau.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrtlpxbcg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtejyoblak.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtruvwxpwh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkdvxomtq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtwzssiuzv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gttesizlpw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqspkqgwg.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtdguneygi.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtyavhbvwn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthdkoefhh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtkxfswcga.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gthxclmejr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtiiyfscfa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gotoacloud.top/Article/details/gtpqaafdoy.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtheirhfjw.html


<!-- 参考信息 -->