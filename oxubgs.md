代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.dashuyun.cn/Article/details/gtovlersnt.html

JS:   `Hello, ${name}!`
来源：http://dali.yonumen.top/Article/details/gtnutolegp.html

TS:   `Hello, ${name}!`
来源：http://dali.yuanzhike.top/Article/details/gtnexagwxd.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.zhoulong.xyz/Article/details/gtlqsilxnh.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.gotoacloud.top/Article/details/gtbzgxeebr.html

Ruby: "Hello, #{name}!"
来源：http://dali.wangshuangyany.cn/Article/details/gtjvcnqbqp.html

C#:   $"Hello, {name}!"
来源：http://dali.cdnleiting.top/Article/details/gtsewlclib.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.jianghu66.top/Article/details/gtmpbousgh.html

Py:   "第一行\n第二行"
来源：http://dali.ehwqpu.com/Article/details/gthymhoskk.html

PHP:  "第一行\n第二行"
来源：http://dali.ybcxt.top/Article/details/gtpsjbchoh.html

JS:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gtslpokljk.html

TS:   "第一行\n第二行"
来源：http://dali.jqgfzy.top/Article/details/gtqgtdosuy.html

Java: "第一行\n第二行"
来源：http://dali.sweek.top/Article/details/gtipdzfpwl.html

Go:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gtuglgyesm.html

Ruby: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtogxoswyu.html

C#:   "第一行\n第二行"
来源：http://dali.kuanghao11.cn/Article/details/gtbpbvcecv.html

[A14] 注释写法
来源：http://dali.jinghuilouyu.cn/Article/details/gtqkrzkvcx.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.gaohongyu789.top/Article/details/gtdlynvfff.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzaioqqmb.html

JS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gtlnibkfsc.html

TS:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gtpalwagjf.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.daria6918.cn/Article/details/gtewernnyg.html

Go:   // 单行；/* 多行 */
来源：http://dali.yuxming.cn/Article/details/gtlpcmhemn.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.ybcxt.top/Article/details/gtkpdydygx.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtsxzufnlk.html

[A15] 空值判断与默认值
来源：http://dali.hnqzz.top/Article/details/gtjvkjlnlp.html

Py:   value = data or "默认值"
来源：http://dali.cucudq.cn/Article/details/gtorzqovqm.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.bjfxy.top/Article/details/gtsihoioeh.html

JS:   const value = data ?? "默认值";
来源：http://dali.gaohongyu789.top/Article/details/gtgwsyjtxu.html

TS:   const value = data ?? "默认值";
来源：http://dali.vqdsnc.cn/Article/details/gthflpfbex.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgbyjzfj.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258.top/Article/details/gtvzayurft.html

Ruby: value = data || "默认值"
来源：http://dali.vqdsnc.cn/Article/details/gtvcumgzpg.html

C#:   var value = data ?? "默认值";
来源：http://dali.tianlin.xyz/Article/details/gthhuwbuyg.html

[A16] 真假值判断规则
来源：http://dali.gzhubu.top/Article/details/gtjjmxiwcx.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrdgxnig.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.redwolf501.top/Article/details/gtkcysfauy.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.fengsongda.top/Article/details/gtugtchnzl.html

TS:   if (!x) {}
来源：http://dali.jqgfzy.top/Article/details/gtuanmqzyl.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yueranfly.top/Article/details/gtthmotdvw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtykjuqztb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.tian-w.cn/Article/details/gtzcyoeszr.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcucqgjab.html

[A17] 位运算
来源：http://dali.sxryk.cn/Article/details/gttbuuptwr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaigbnvsj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xylfe.cn/Article/details/gtsfmkepyn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtcpcjojwc.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtkknbdegy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsyzqnzst.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtmndpdanb.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtikswwtxs.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtidfjdmin.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gtvjqkbtaa.html

Py:   ord("A"); chr(65)
来源：http://dali.xylfe.cn/Article/details/gtugrtidot.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtvjwigzsd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhengqikj.top/Article/details/gthokofwyt.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gtextnoffi.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhongyouzk.top/Article/details/gtnksaykpn.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.vqdsnc.cn/Article/details/gtilbftvjd.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuetiantiany.cn/Article/details/gtzijkodud.html

C#:   (int)'A'; (char)65
来源：http://dali.ivvv.top/Article/details/gtcoisympr.html

[A19] 交换两个变量
来源：http://dali.c1oappe.top/Article/details/gtbqjmdhpn.html

Py:   a, b = b, a
来源：http://dali.shuidangran.top/Article/details/gtixsexfir.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.kuanghao11.cn/Article/details/gtynfcfzvd.html

JS:   [a, b] = [b, a];
来源：http://dali.sweek.top/Article/details/gtpgsnsvte.html

TS:   [a, b] = [b, a];
来源：http://dali.hywenlv.cn/Article/details/gtuojwkzuj.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenzaomai.com/Article/details/gtjcqyfalm.html

Go:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtpupjljhf.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtwlicofgb.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gtkekiiygn.html

[A20] 读取标准输入
来源：http://dali.mhx1999.top/Article/details/gtplzbvlyu.html

Py:   name = input("请输入：")
来源：http://dali.shzxlz.cn/Article/details/gtmrectoir.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yangfankeji.com/Article/details/gtngkwfjex.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gaohongyu789.top/Article/details/gtjlwzkzxs.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtvktseafa.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ydzc1.top/Article/details/gtjnvwglkb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.havefunace.top/Article/details/gtkdjzdhxt.html

Ruby: gets.chomp
来源：http://dali.hysaishi.cn/Article/details/gtzitjkdjp.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gtqpqoorda.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtlobtojis.html

Py:   f"{3.14159:.2f}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdnorvlsc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtogfhdnmi.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqkxfsng.html

TS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtfnmycvxa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtdrhnlmfh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gtqoplklih.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtpxkyusvi.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gtfdswpjek.html

[A22] 获取字符串长度
来源：http://dali.fengsongda.top/Article/details/gtpwibgrxv.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtdvgmqfdk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.cqqwz.cn/Article/details/gtvgreqjwj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tianlin.xyz/Article/details/gtjihquajo.html

TS:   s.length
来源：http://dali.nwbrower.top/Article/details/gtxchygskl.html

Java: s.length()
来源：http://dali.yj202588.top/Article/details/gtqmtdgyks.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gtkhyjsowt.html

Ruby: s.length
来源：http://dali.zhijiandao.cn/Article/details/gteawbcdta.html

C#:   s.Length
来源：http://dali.zhoulong.xyz/Article/details/gtmvhtcyau.html

[A23] 大小写转换
来源：http://dali.0kj1m.cn/Article/details/gttwyoyvjz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtgohfguqa.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yj202588.top/Article/details/gtxvfqtedf.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gttvrbpcgd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtllprpumb.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.meibo888.top/Article/details/gtnfgjdhen.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ehwqpu.com/Article/details/gtissvrdkp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.quarkkingdee.top/Article/details/gttsmfdefj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gthglzmaty.html

[A24] 去除首尾空白
来源：http://dali.jinghuilouyu.cn/Article/details/gthogjltdg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.snrcjt.cn/Article/details/gtojpdiisl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jyoumei.cn/Article/details/gtvwwacbmd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtrwkwzdzv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtiqtimepe.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gtcijbpvah.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gtgzruhfov.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gtnoiblvon.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hysaishi.cn/Article/details/gteihwgyas.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtbcrcyugs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tanke756.top/Article/details/gtyxygokbv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gttcbufhpy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtaugnqhxa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtaxlxhetr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtkashzjiy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtpdydfhab.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gaohongyu789.top/Article/details/gtabvzogyc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtqzjgodrt.html

[A26] 类型转换总览
来源：http://dali.wangshuangyany.cn/Article/details/gtpekzkbmi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cucudq.cn/Article/details/gttygnsksy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gtxhmwdbrr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhijiandao.cn/Article/details/gtdvcpvird.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jyoumei.cn/Article/details/gtftvecgms.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtcmyvprdq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.svipenyu.cn/Article/details/gtzirvizdp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtdutrvsbn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangtech.top/Article/details/gthbmohoan.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtjnqapvwp.html

B. 流程控制
来源：http://dali.yj20258888.top/Article/details/gtdxlysjne.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvefqmdvm.html

[B01] 条件判断 if / else
来源：http://dali.cdnleiting.top/Article/details/gtsxplcwoi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xinyue.icu/Article/details/gttqgmgeqw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtflyozpjx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtdhrojeig.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtmiddpqnn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtlnulhrna.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbwxopvt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtcdrtlnpl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtwevexoqo.html

[B02] 多分支 else if / elif
来源：http://dali.yangfankeji.com/Article/details/gtptzqlvsl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xinyue.icu/Article/details/gtfagzoavi.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.nanxuanxn.top/Article/details/gtzihrapdm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gtpmqhxhvp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtekckoitg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtravpkuky.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gtehshffvn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gtfstyhdqs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtjrktyxhh.html

[B03] switch / match / case
来源：http://dali.jinqigfzy.top/Article/details/gtefwascjl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gtlsvhttii.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtzbygjqgm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtolzsruju.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtgpbwvvut.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtuvsieqhb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtljslslti.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtdkvqxutz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtvieimznc.html

[B04] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gtobmykdxj.html

Py:   for i in range(10): print(i)
来源：http://dali.zycfv.cn/Article/details/gtxzzvglkd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gtdpksvlvl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgfzy.top/Article/details/gtkquuwgdu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtdcrmrlct.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gtnlxiguov.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gthmcroaej.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jyoumei.cn/Article/details/gtntmfocym.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtwqfyouyp.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauaoqhyl.html

Py:   for item in arr: print(item)
来源：http://dali.yj20258888.top/Article/details/gtvtkbwrrl.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gtwnlnvlob.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gttpkkegdb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtwbiptlov.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtaubfjgbe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtdbmhmbay.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtfcxidvxm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gtzwkrfbyo.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtbshthjhq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gttowhpubc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ppjwa.cn/Article/details/gtzndaydgp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gtovwwyexk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtjatcbfrl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgzfbfdf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gtaqxoyybv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtwhbgyuci.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgnkhegff.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtgfagtoqb.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqjnhyyy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtqjbijeol.html

JS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtxthnfbsv.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtnhpyssnz.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtxfbofxlh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gthxrhqdks.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtjnuxnjsr.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtxjpmjdsr.html

[B08] do-while（至少执行一次）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvxoigcq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gtravwkxee.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtzhgldowj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gthdahnzpk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtssljxwky.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtpyuamfxk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsmzywnjt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gtezfhwfgu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtwciijvbz.html

[B09] break 与 continue
来源：http://dali.c1oappe.top/Article/details/gtrlwmvliv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtpolivrke.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gthgdffxzu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtimgxdqtw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gthukwolwa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtsrfedgmh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gttopepoam.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhixingplan.top/Article/details/gtlbfeddmd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtsllogtvp.html

[B10] 遍历同时拿索引
来源：http://dali.bjfxy.top/Article/details/gtnxopeabn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakcqsxoy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gtuyifqpvg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtotnoluwf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtlqddmwon.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtsmeieudd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtvibgreau.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenlongwang.top/Article/details/gtryihxyai.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gthvyujcdw.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtznmzfyqc.html

Py:   list(range(0, 10, 2))
来源：http://dali.nanxinkj.top/Article/details/gtlddokhdc.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gtkrzpmrzw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtmndpbelk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gtormxjoyw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258.top/Article/details/gtgizzqwci.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtxnxynkwj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtsnjnzwhu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtudkxpucw.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtwqliufig.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gttqgpcgcn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tianlin.xyz/Article/details/gtdljrzxgj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtvtmmebpw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtxcseaisf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtuwwszwqb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtvfsynltq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtlieyheuh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtilvjkriy.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtfuqipggw.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtjdecvgha.html

PHP:  is_numeric($x)
来源：http://dali.ppjwa.cn/Article/details/gtypvhnvnq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtkorvgwgt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvfbukus.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gtbkoygmyc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtdytiweqp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtrugkyubg.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtwaykmjzm.html

[B14] 判断值是否在集合内
来源：http://dali.nanxinkj.top/Article/details/gtcmwunvmq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gtiegigfei.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtmnvtsuzv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtirardcbu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtjmfmhmic.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttazwtunh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gtzbsyfggw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtzrhaiagi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtlnvkecgy.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gtmysligbf.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gtugwutrnp.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtwbpsemsd.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtxupswsxv.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtgbjalhaa.html

Java: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrdiyjhg.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtdqyslbqe.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtlczwkmok.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtduzuexpd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtkdsqhrpi.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtbphbkiaq.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtjrhnzwoc.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtwwhhjizf.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtajfjeiql.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtfxpujuxx.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gtupskdnzc.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gttytrdjzn.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtdokenvsv.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtexjuabbf.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtjeleqetb.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtlxirvqcb.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtsqclapmz.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gtumdoiilh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gteocldzaq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtbqiqnnru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtoqsrwmwf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtxlqwizax.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtvuvnkjlh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gtvxhhnmva.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtgjmibnqf.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtfneokecg.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gtsdzitkoq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtopwfuecn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtvexuucyn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtmdydrjfo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gthxihzjhj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gtfseekgse.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gtwxfxizln.html


<!-- 参考信息 -->