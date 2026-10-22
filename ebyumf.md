代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dianchejie.cn/Article/details/gt2lmemjvas.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gt2ywihludk.html

TS:   if (!x) {}
来源：http://dali.yj202588.top/Article/details/gt2rkmdrsfq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.andypj.xyz/Article/details/gt2tzybqjyw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.smart0.xyz/Article/details/gt2gvodxsgx.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhixingplan.top/Article/details/gt2afjxmlgm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aizwys.cn/Article/details/gt2eijaucbl.html

[A17] 位运算
来源：http://dali.jlsjyb.cn/Article/details/gt2vwjbsdgk.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gt2qgekeavn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.birdmap.top/Article/details/gt2kpsehqra.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gt2getkybnu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.9152youxi.cn/Article/details/gt2gjkxqcrq.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gt2slyahvnw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wervtcus.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gt2wocwltsz.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gt2ykiuljyp.html

[A18] 字符与 ASCII 码互转
来源：http://dali.andypj.xyz/Article/details/gt2ofzguplh.html

Py:   ord("A"); chr(65)
来源：http://dali.xziqi.cn/Article/details/gt2oyfdiqkb.html

PHP:  ord("A"); chr(65)
来源：http://dali.shuidangran.top/Article/details/gt2mcybicdn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2dxpgkntv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jianghu66.top/Article/details/gt2aljhiegx.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigfzy.top/Article/details/gt2pnecjszk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.ehwqpu.com/Article/details/gt2jhvddgpa.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gt2gwihxntt.html

C#:   (int)'A'; (char)65
来源：http://dali.jyoumei.cn/Article/details/gt2ljoegvmc.html

[A19] 交换两个变量
来源：http://dali.aibaodan.cn/Article/details/gt2amqyuvhy.html

Py:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gt2bouxjosq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sysykeji.top/Article/details/gt2exjkaksv.html

JS:   [a, b] = [b, a];
来源：http://dali.dashuyun.cn/Article/details/gt2vtalouvu.html

TS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gt2wbpnnsmw.html

Java: int t = a; a = b; b = t;
来源：http://dali.gotoacloud.top/Article/details/gt2emeixsxt.html

Go:   a, b = b, a
来源：http://dali.hnqzz.top/Article/details/gt2mcrhauvw.html

Ruby: a, b = b, a
来源：http://dali.zhijiandao.cn/Article/details/gt2yzczjvzy.html

C#:   (a, b) = (b, a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dhhpdwds.html

[A20] 读取标准输入
来源：http://dali.hnxiangtu.top/Article/details/gt2qcltsngk.html

Py:   name = input("请输入：")
来源：http://dali.bjfxy.top/Article/details/gt2goxwcpgj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.haohaochexian.top/Article/details/gt2pkdhfmnh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gt2qdbvdpsr.html

TS:   // Node.js：readline 模块
来源：http://dali.gaohongyu789.top/Article/details/gt2ehultpir.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258.top/Article/details/gt2djodghpx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yj20258.top/Article/details/gt2eaezrbrj.html

Ruby: gets.chomp
来源：http://dali.cqqwz.cn/Article/details/gt2fbotpknb.html

C#:   Console.ReadLine();
来源：http://dali.tianlin.xyz/Article/details/gt2tldpyxef.html

[A21] 保留指定小数位输出
来源：http://dali.sxryk.cn/Article/details/gt2wzzvsqbw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gt2zbadphji.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2fqdhxnat.html

JS:   (3.14159).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gt2cuufuzjf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.nanxuanxn.top/Article/details/gt2cuwowhse.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gt2bgzxiqbh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.c1oappe.top/Article/details/gt2zvfhauwc.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gt2xtwckfdc.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvuhhojj.html

[A22] 获取字符串长度
来源：http://dali.sufxvd.cn/Article/details/gt2iagvzybl.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gt2ikojpnhw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gt2rckwezef.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dashuyun.cn/Article/details/gt2fwpurgoz.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gt2sdbhfnqm.html

Java: s.length()
来源：http://dali.redwolf501.top/Article/details/gt2uttvlqsx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xylfe.cn/Article/details/gt2txegwagu.html

Ruby: s.length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2izxmyzdn.html

C#:   s.Length
来源：http://dali.hammf.cn/Article/details/gt2hhcxdtsu.html

[A23] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gt2qvexnndw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigfzy.top/Article/details/gt2ynejwloi.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2vsjoabvq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gt2hrabfmbs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2yjnbsglm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gt2rkbqmbbb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mipsxupf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.cqqwz.cn/Article/details/gt2vowzvpro.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hnqzz.top/Article/details/gt2biwswifl.html

[A24] 去除首尾空白
来源：http://dali.yongpay.top/Article/details/gt2mangwgrw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gt2mizeehlz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gt2gwrkvkks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gt2nwxtltlc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gt2jjaknifl.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nwbrower.top/Article/details/gt2yblfbmto.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258.top/Article/details/gt2jtvexzdi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gt2ealigree.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.nwbrower.top/Article/details/gt2tctqpvkd.html

[A25] 字符串比较
来源：http://dali.cheryme.top/Article/details/gt2agfeeldx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gt2eigyyzto.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yhveefgx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aibaodan.cn/Article/details/gt2sqmmkheq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2seyfpcez.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2vnncgwpt.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gt2xnbkgzhl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gt2bktxrnnc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2tohqvgdg.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gt2bnszpzua.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhoulong.xyz/Article/details/gt2tdtblzte.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qagmltto.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wjwjvpmh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhoulong.xyz/Article/details/gt2dmivbwtb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gt2bewfkxlr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gt2mvtviyak.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sufxvd.cn/Article/details/gt2zdgvodjx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gt2xnxbcfjv.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2jsivympx.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gt2gnugmbco.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2wqyzyydi.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gt2bgeylaxm.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sxryk.cn/Article/details/gt2wmdiloyx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2nhihuqid.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2lowghwop.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258888.top/Article/details/gt2vxyznxdd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2ehgxlumc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gt2wsdvvjlf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gt2bsvsdbtc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2bdykldag.html

[B02] 多分支 else if / elif
来源：http://dali.tian-w.cn/Article/details/gt2gjeatzwk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgfzy.top/Article/details/gt2zspudios.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258.top/Article/details/gt2yrraadkh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gt2dcihclob.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2srlxjaiw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gt2ioiunvpz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gt2htcpkrup.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gt2mivdcfre.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2hfrkiaht.html

[B03] switch / match / case
来源：http://dali.cucudq.cn/Article/details/gt2qbvyxlwi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenjidiqi.icu/Article/details/gt2hiixqvhu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2kegrjibr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2suigsghv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2xpwosqad.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlfxwpxz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2fekyezyf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2byoxipsl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gt2ewidqrdr.html

[B04] for 计数循环
来源：http://dali.jinqigfzy.top/Article/details/gt2swaujjzq.html

Py:   for i in range(10): print(i)
来源：http://dali.dianchejie.cn/Article/details/gt2bentahau.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gt2qxtkyzqk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2trxqewcx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.mhx1999.top/Article/details/gt2xqfscbzq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2uxyaooci.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.bjfxy.top/Article/details/gt2uiwaxpbd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gt2npegwrma.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gt2mogexvwn.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gt2xdivqyge.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gt2smdirlcu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gt2ecxctypu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cqqwz.cn/Article/details/gt2trzfxewz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.iojbl.cn/Article/details/gt2obujvjip.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nqqxabvf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gt2kwgiqmie.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xinyue.icu/Article/details/gt2ufupdwgp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hammf.cn/Article/details/gt2virfqqwy.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hqurayml.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gotoacloud.top/Article/details/gt2cfxccmyg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gt2fpjywsap.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2rkxkwavi.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jianghu66.top/Article/details/gt2njqaoqav.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpmkybxj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gt2nlfxunfv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gt2aenudxpi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.fzhhl.top/Article/details/gt2xzwfqlyn.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zxrfllgv.html

Py:   while i < 10: i += 1
来源：http://dali.jqgufenzy.top/Article/details/gt2figdcjdy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2umucltcx.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2rspcoolz.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2hgxjupea.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgpwslzh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqfcxqvz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.bjfxy.top/Article/details/gt2pftwazsv.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2lyvzwqvi.html

[B08] do-while（至少执行一次）
来源：http://dali.hnxiangtu.top/Article/details/gt2tzidpjkm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2nlemjbng.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugqhwffb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2swfvbiiy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2xngyahpy.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2zhebpkur.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gt2qhytqlfk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hongshengwenyu.top/Article/details/gt2olbcwigm.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2ulqgdwjn.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2nwxtooag.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gt2wcqnczig.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2olktxdys.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2lhaavtcl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2lqzzuycd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2khrczegy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jyoumei.cn/Article/details/gt2djfwxwzz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2qfunhedg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gt2oyonpltx.html

[B10] 遍历同时拿索引
来源：http://dali.yvedp.cn/Article/details/gt2eczskjxe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gt2ntukxtsv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gt2tdwylsal.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.pycfn.com/Article/details/gt2ibqgdjfd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gt2ewfnbjab.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gt2nftllksk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yanxiufei.cn/Article/details/gt2vovjctep.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2igcscbfd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gt2avbwdunx.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gt2yggdjbon.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gt2cpvvsbpb.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ixnowdyb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gt2dolbfvao.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2kedwqujr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2twapvjap.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gt2qfnvtzla.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2ayahjhjm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xvktkoxb.html

[B12] 跳出多层循环
来源：http://dali.jlsjyb.cn/Article/details/gt2stcgppwo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gt2lpqgonrx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hysaishi.cn/Article/details/gt2yggflaxa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2vzrbfhqi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gt2lptwcpco.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zekrcwoh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gt2ygubgqvy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gt2rryccthx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gt2ljpxndlx.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gt2shjtlmls.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gt2fsjykuqm.html

PHP:  is_numeric($x)
来源：http://dali.daxiang520.top/Article/details/gt2icxkekxl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gt2mnceojve.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gt2pehijmlj.html

Java: x instanceof Number
来源：http://dali.dianchejie.cn/Article/details/gt2rtajiuqu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fmrgzqzx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.quarkkingdee.top/Article/details/gt2vqbuabxm.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2htrdjesi.html

[B14] 判断值是否在集合内
来源：http://dali.sysykeji.top/Article/details/gt2ruaexvid.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gt2dggbqsyx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gt2ftdahinq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gt2rxqjotis.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2nyohfycr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2uofdoagc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gt2gexrsiuv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gt2gljctkys.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2yywlzrfo.html

[B15] 布尔运算与取反
来源：http://dali.jqgufenzy.top/Article/details/gt2jrmjpdds.html

Py:   a and b or not c
来源：http://dali.cqqwz.cn/Article/details/gt2ttqngipx.html

PHP:  $a && $b || !$c
来源：http://dali.jqgufenzy.top/Article/details/gt2cdkyzxan.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2hkqxfjcp.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2zkjtabjx.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2tparwoyf.html

Go:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2qsinnrdn.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2xpccnwbq.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gt2gswofaga.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gt2djjigxip.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wdtzkpxc.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gt2qmrjdiea.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gt2bqayjqnk.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2xpuilhbu.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gt2zeclvpjq.html

Go:   if data == nil { return }
来源：http://dali.gogol.net.cn/Article/details/gt2cracetpv.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gt2zxkiasct.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gt2yltstqxb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2mtljsbzi.html

C. 函数与作用域
来源：http://dali.zdqjudy.top/Article/details/gt2vgqkfoti.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2vuagbgzk.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2qmbwrqlg.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2gqmhhepo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ytiildst.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2nyltotdd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2pvelnwad.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2cmsslqhy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2aljxpcqm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gt2sccudlee.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2oseoevdh.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rzselqfw.html

Py:   def greet(name="World"): return name
来源：http://dali.kuanghao11.cn/Article/details/gt2zugzjqiz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gt2yodgfctk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2soepvcws.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guowangkeji.top/Article/details/gt2drskunuu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnqzz.top/Article/details/gt2ncyfhgov.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gt2aacducal.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gt2bbaspypn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxwgsmgr.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gt2sdpdpfwj.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gt2eljlsznq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2swvognjg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gt2fwlzektq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gt2nvhizzxn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gt2sbeopnoy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2byucbzgj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gt2wccotwws.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gt2voqpjtuw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gt2gnzivmif.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2piupqxnc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2lmeoakvt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2fpgqodyy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2qdihklqe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gt2zzcowsoj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2qxfvgvjt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2fzxbizaw.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gt2vpsngpqp.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2uzswbgmg.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzcqkyqg.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gt2hptpvhmm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2iroweotd.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2qvjwzwga.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gt2fjlbvgvc.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jwegozke.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2wvdoofws.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gt2jpavxeuw.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2biadsiuj.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gt2ovwfhvkh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gt2drzkhtgy.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2yjusulon.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljomavjz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqgjmryf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gt2hyqdzset.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2libfpuig.html


<!-- 参考信息 -->