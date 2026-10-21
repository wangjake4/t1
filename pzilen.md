代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.yvedp.cn/Article/details/gtrbnlcqsk.html

[A15] 空值判断与默认值
来源：http://dali.cqqwz.cn/Article/details/gtsiimgdot.html

Py:   value = data or "默认值"
来源：http://dali.zhongyouzk.top/Article/details/gtuvagxlry.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtluiqmbvj.html

JS:   const value = data ?? "默认值";
来源：http://dali.wangdashe.top/Article/details/gtcmeuhmos.html

TS:   const value = data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxbuudla.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.sweek.top/Article/details/gthumtvkla.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangdashe.top/Article/details/gttuzlehwd.html

Ruby: value = data || "默认值"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuocqknmo.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtcopusppo.html

[A16] 真假值判断规则
来源：http://dali.xuanzx.com/Article/details/gtclvecuoo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.andypj.xyz/Article/details/gteedxulvw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hywenlv.cn/Article/details/gtsoxktbkc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zycfv.cn/Article/details/gtaskoqcpt.html

TS:   if (!x) {}
来源：http://dali.yanxiufei.cn/Article/details/gttpnmisyv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yonumen.top/Article/details/gthliqfmur.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.snrcjt.cn/Article/details/gtaktuvebs.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.gotoacloud.top/Article/details/gtcccdpzwu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtghdqjrsi.html

[A17] 位运算
来源：http://dali.sysykeji.top/Article/details/gtgduxjztl.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtlhytecxv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtlkzziygs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtpoatztrv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtujcwbcek.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ehwqpu.com/Article/details/gteiqpqowp.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtrnqehfml.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtitejllue.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtoaczbuzz.html

[A18] 字符与 ASCII 码互转
来源：http://dali.meibo888.top/Article/details/gtiqnmlpen.html

Py:   ord("A"); chr(65)
来源：http://dali.yj202588.top/Article/details/gtpeurgmdx.html

PHP:  ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gtyrklllmt.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmasnxbb.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gtkizwzzzm.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gtvzokhmau.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gtetblfhhj.html

Ruby: "A".ord; 65.chr
来源：http://dali.316326.xyz/Article/details/gtamygcaxl.html

C#:   (int)'A'; (char)65
来源：http://dali.hywenlv.cn/Article/details/gtwocgjlgd.html

[A19] 交换两个变量
来源：http://dali.xylfe.cn/Article/details/gtwyjtyjsi.html

Py:   a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gtwtacktmx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gtpcfvfxxm.html

JS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvthznwq.html

TS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtjjodheeq.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhijiandao.cn/Article/details/gtpbfbzvsk.html

Go:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfgmizml.html

Ruby: a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gtimehhgbu.html

C#:   (a, b) = (b, a);
来源：http://dali.fengsongda.top/Article/details/gtrdzbfcqw.html

[A20] 读取标准输入
来源：http://dali.dianchejie.cn/Article/details/gtdowjkmig.html

Py:   name = input("请输入：")
来源：http://dali.nwbrower.top/Article/details/gtkyqkskfv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.shuidangran.top/Article/details/gtwuqsmelk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jlsjyb.cn/Article/details/gtjczaovxz.html

TS:   // Node.js：readline 模块
来源：http://dali.zhijiandao.cn/Article/details/gthyoylzsr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258888.top/Article/details/gtrkenhwvi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjslsakdp.html

Ruby: gets.chomp
来源：http://dali.ivvv.top/Article/details/gtwwmffydr.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gtadimxsta.html

[A21] 保留指定小数位输出
来源：http://dali.sufxvd.cn/Article/details/gtnvsxsrds.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gtpxmabeqd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sweek.top/Article/details/gtfvqvuphb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gtwsazzbok.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtwrghoanr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtrkrgxtqe.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtzdzobebe.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gtqnfldefn.html

C#:   3.14159.ToString("F2")
来源：http://dali.smart0.xyz/Article/details/gtcldhzbtp.html

[A22] 获取字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtpjhoholv.html

Py:   len(s)
来源：http://dali.bjfxy.top/Article/details/gthrhojmsf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gtrcrkekhd.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtmiljyfmf.html

TS:   s.length
来源：http://dali.chenlongwang.top/Article/details/gtfrseiqvu.html

Java: s.length()
来源：http://dali.quarkkingdee.top/Article/details/gtuveegnzh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtcywazeou.html

Ruby: s.length
来源：http://dali.ppjwa.cn/Article/details/gtgwvbyucf.html

C#:   s.Length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcalimhfe.html

[A23] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtykvhhrql.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cheryme.top/Article/details/gtmygwtnvd.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fengsongda.top/Article/details/gtfurzbots.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtipzavadz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtexlulzyk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yongpay.top/Article/details/gtyhyfvrsd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gtqquhalyb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tian-w.cn/Article/details/gtucxaooux.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cheryme.top/Article/details/gtphqhjlxu.html

[A24] 去除首尾空白
来源：http://dali.ehwqpu.com/Article/details/gtmnkqzdzr.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.chenzaomai.com/Article/details/gttqartrod.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.nanxinkj.top/Article/details/gtizpgxmyx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gtdrlojaca.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtsyxiacfz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.guannengcc.top/Article/details/gtnwrpxxqo.html

Go:   strings.TrimSpace(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdfftvod.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ybcxt.top/Article/details/gtztizfmab.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guannengcc.top/Article/details/gtjzcprbcq.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtaomlngoo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangdashe.top/Article/details/gtsgmwgoyd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yanxiufei.cn/Article/details/gtzaxemtpo.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hysaishi.cn/Article/details/gtocmgfors.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtmznyoano.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gogol.net.cn/Article/details/gtgrxbmrqw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtwnxkfoqe.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.redwolf501.top/Article/details/gtadfsgnxe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtjwzssypk.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gtszvydylj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.smart0.xyz/Article/details/gtfzkmrkid.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hammf.cn/Article/details/gtzilnywub.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzqmqnmug.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gtptrltbsw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtwiqnbtsj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nwbrower.top/Article/details/gteuhxfznj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gtgiwkxrru.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtyrnsbaox.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtretosdln.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gtaxphgjmv.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdpnatjen.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtybxxdwpk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xziqi.cn/Article/details/gtgwwvuadb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gogol.net.cn/Article/details/gtbsvtrevm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtwtyoxtxn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglrypodn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtwsnjqqya.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gthyyoxtvu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigfzy.top/Article/details/gtyznowgbw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtwpeenufh.html

[B02] 多分支 else if / elif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzfxfsvj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ppjwa.cn/Article/details/gtpxsmhbdk.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gtoftdxqrb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtffaavrxy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gttdtpvmmm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtznxbxhsn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.c1oappe.top/Article/details/gtmcfsejql.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gtfiuvxpmy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtqfrelufb.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gtwtvawxir.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gttczbkpav.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gthoneewry.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtekydithb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtxqfoplxt.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtfauadvqr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ydzc1.top/Article/details/gtufhrushi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gttfiwvfhs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gtdarljhia.html

[B04] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gtmlcadrxq.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtgkulkils.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gtskxwvwrp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtiyhcdypj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtkezbpdwy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zdqjudy.top/Article/details/gtglbztcnb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gtlztsidtm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.wangshuangyany.cn/Article/details/gtulyupgrw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsxknbry.html

[B05] 遍历数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtlkfljqhh.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gtgwaplelf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxvbsjzwe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtykndwzsb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gttgpognaa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gtkdflvazv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gthrjeygyu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtaeqzocso.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtooneqpcz.html

[B06] 遍历字典 / 对象
来源：http://dali.iojbl.cn/Article/details/gtijbubjth.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtrcidykua.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gttefmtbrf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gtltjfwskh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtxsqnnomc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yanxiufei.cn/Article/details/gtuzinwdgi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gtuqrlbqcs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gtlcodywqa.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ehwqpu.com/Article/details/gtahdunsyc.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtapityqin.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gtecziokcu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gteilftxei.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtkfulyotf.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutyhouxu.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzcrzwukx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gtwtyxiwhv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuxming.cn/Article/details/gtkjmchrfs.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtqpvjefqk.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtavlqzvsb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gtbunzildl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gtefuxztkl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtnpfmleod.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtlxondzqn.html

Java: do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtohemoffp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtezwubjry.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gtatxnlalb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gttldhxywt.html

[B09] break 与 continue
来源：http://dali.hysaishi.cn/Article/details/gtpvphqxaf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtoqnrcikh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtlbdgwavy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtgkglpkqv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtahgltpag.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtpzvysmfh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtnnkbluzg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtipefznyk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtnyqwkhvk.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnvwifcrm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtujucheqa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gtzhevegpj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtnmzvulay.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxinkj.top/Article/details/gtkiuktrha.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtkiihfyho.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkatweewi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gtraseerpn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.aibaodan.cn/Article/details/gtjgudslwz.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtnbsegqam.html

Py:   list(range(0, 10, 2))
来源：http://dali.shzxlz.cn/Article/details/gtvnxhxzyc.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtgmlolftn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtvuccpmlm.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtkmyjdcmf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jqgfzy.top/Article/details/gthbirnrsq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gtnhiuzxrj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtmamkmlar.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yangfankeji.com/Article/details/gtoqjdosnz.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtthzrbcai.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gtrhjjpifg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtqmtieinc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtblazowmg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtofgvtobp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtwyjiokcb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.pengpengdd.cyou/Article/details/gtglegzqdq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtcvguaysw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtmhenfdas.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtainsnsom.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtyabzbnee.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gttmxaknux.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrpjjtiq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtkqdhhakw.html

Java: x instanceof Number
来源：http://dali.jiagoushi.top/Article/details/gtjlnhcmki.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gtlvggalno.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtmndwjixo.html

C#:   x is int or double or decimal
来源：http://dali.ybcxt.top/Article/details/gtrtcdjhbv.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtydrtdyjm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtrkuxopyp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gthbxoxwda.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtvulaxucc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gtfauaxnzz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gtnkdyxtkb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gthgkwtlxg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtjitlfcda.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtnehbfixv.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gtxqavpvem.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtvjolreas.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gtenyakgyr.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtjeszjzcq.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtztiafdlf.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtxmrruktv.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtmvpuofwg.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtncoyrmvu.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtmfxvwgjh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtgwghlfko.html

Py:   if not data: return
来源：http://dali.sufxvd.cn/Article/details/gtuoswtgrh.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyjfxpixs.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtqblzdlww.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtmxmdsdqe.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtweyokbyc.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gtojmojetm.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtjroszbjw.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtdjqpitoq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtvbnzduyr.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtrmkzodle.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbpvmhtub.html

[C01] 定义函数
来源：http://dali.zycfv.cn/Article/details/gtzfcvzrux.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtzoqssnyz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtbbcqfkys.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtuznmdahb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtbyjwdxgw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtvrulgvym.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtahtfygqf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gtvgfvilrh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtnzjpugnk.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gthiuqkizi.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtbgwkwvzr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxuanxn.top/Article/details/gtljpwnriq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtfxjfeqbg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtypgagvti.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gthsymeblb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yvedp.cn/Article/details/gtpckpiehe.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtfgdkqzap.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtnucaphhu.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtduybokjw.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gtbfxuugxt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gtjngvzasy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtjiyhmvyu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtbtbrojoe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtuzfgeaif.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtzcacrlic.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gtrtpkifnj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtawvarofa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtcundgqhm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtwrocfqxr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtxpjtbdfd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtdilqqmet.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cheryme.top/Article/details/gtkzyekwms.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtazjdwaay.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtvzoosziu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtxretthfb.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtyrkeekwh.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtlnrguubc.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtupbrwsyi.html

PHP:  return [$a, $b];
来源：http://dali.cheryme.top/Article/details/gtkylqkgdl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtuesmrlol.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzzszxlc.html


<!-- 参考信息 -->