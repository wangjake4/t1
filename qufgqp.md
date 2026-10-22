代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gt2lhfogwci.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sweek.top/Article/details/gt2wkkpsmqk.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gt2ipfgimwv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxuanxn.top/Article/details/gt2otdpttew.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sysykeji.top/Article/details/gt2irhseiqd.html

Py:   ord("A"); chr(65)
来源：http://dali.cucudq.cn/Article/details/gt2zsfjocns.html

PHP:  ord("A"); chr(65)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpbsohac.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2bdrlmobh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.9152youxi.cn/Article/details/gt2zbonewcv.html

Java: (int) 'A'; (char) 65
来源：http://dali.bjfxy.top/Article/details/gt2cuueglkr.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhixingplan.top/Article/details/gt2xhypbxzf.html

Ruby: "A".ord; 65.chr
来源：http://dali.dianchejie.cn/Article/details/gt2nqaoqtos.html

C#:   (int)'A'; (char)65
来源：http://dali.guannengcc.top/Article/details/gt2nnfdtmbj.html

[A19] 交换两个变量
来源：http://dali.daxiang520.top/Article/details/gt2haujzqlc.html

Py:   a, b = b, a
来源：http://dali.hywenlv.cn/Article/details/gt2ogctwdml.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jianghu66.top/Article/details/gt2aguifshu.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2udzqgfqb.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gt2mufoplnr.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhixingplan.top/Article/details/gt2rxfmymwm.html

Go:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gt2qbdnswdp.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gt2chkwckxt.html

C#:   (a, b) = (b, a);
来源：http://dali.bjfxy.top/Article/details/gt2jksjrbqj.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gt2yhzczojg.html

Py:   name = input("请输入：")
来源：http://dali.yuxming.cn/Article/details/gt2zzwowfnj.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ppjwa.cn/Article/details/gt2qipbwjab.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.yueranfly.top/Article/details/gt2xbrhqkpv.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gt2vzsxcxhx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hongshengwenyu.top/Article/details/gt2azythfgs.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hywenlv.cn/Article/details/gt2umzafrnn.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gt2iwxqjphm.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gt2klljyrwm.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gt2fwoxcbuj.html

Py:   f"{3.14159:.2f}"
来源：http://dali.redwolf501.top/Article/details/gt2bzpekfcv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gt2wlphsvkz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hysaishi.cn/Article/details/gt2lygyqcnr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gt2srvvfkmf.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2alffjewe.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gt2tuyokfkm.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.dianchejie.cn/Article/details/gt2rafsqhuh.html

C#:   3.14159.ToString("F2")
来源：http://dali.daria6918.cn/Article/details/gt2ekhgfhpm.html

[A22] 获取字符串长度
来源：http://dali.aibaodan.cn/Article/details/gt2zpyegwnm.html

Py:   len(s)
来源：http://dali.xinyue.icu/Article/details/gt2wtrhjtbf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gt2rmuxcjbw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cashguo.top/Article/details/gt2jjrhxmge.html

TS:   s.length
来源：http://dali.kuanghao11.cn/Article/details/gt2hnccgcko.html

Java: s.length()
来源：http://dali.aizwys.cn/Article/details/gt2djkgafym.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.cucudq.cn/Article/details/gt2vmvrroyb.html

Ruby: s.length
来源：http://dali.ehwqpu.com/Article/details/gt2orysedjl.html

C#:   s.Length
来源：http://dali.chenzaomai.com/Article/details/gt2cisfhdyb.html

[A23] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gt2nzkijhli.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuanzhike.top/Article/details/gt2xjhirfhz.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gt2fbmccjdi.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fengsongda.top/Article/details/gt2rbaamcue.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gt2gpvvzfvm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.mhx1999.top/Article/details/gt2fkunjphp.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.daxiang520.top/Article/details/gt2eazmbsfv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ehwqpu.com/Article/details/gt2kcmqvckv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangdashe.top/Article/details/gt2hwmmtcwv.html

[A24] 去除首尾空白
来源：http://dali.chenzaomai.com/Article/details/gt2mohescao.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gt2lpprziin.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gt2fjaiktbl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gt2taehsazd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gt2zjnacmiw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ybcxt.top/Article/details/gt2tidmsduy.html

Go:   strings.TrimSpace(s)
来源：http://dali.sxryk.cn/Article/details/gt2pwmdxyvv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangdashe.top/Article/details/gt2ejsscfnm.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gt2mtlvshtx.html

[A25] 字符串比较
来源：http://dali.pycfn.com/Article/details/gt2zjxdxyat.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2beefgapu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gt2mvqquurc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2ayialexy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2pxduulmn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hyseggly.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tian-w.cn/Article/details/gt2iqetazoq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zycfv.cn/Article/details/gt2uievqmij.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gt2qiinbsvz.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gt2tekbmypl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nwbrower.top/Article/details/gt2evpvmvvc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gt2egdlduhr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gt2dyswdmkv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tianlin.xyz/Article/details/gt2wrczhtdy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sweek.top/Article/details/gt2qchdjgys.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qdiekyly.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2umdxrzqq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gt2beatvdfk.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bbryvqro.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gt2jrlqdgrl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ahvgvune.html

[B01] 条件判断 if / else
来源：http://dali.sxryk.cn/Article/details/gt2uncglwgn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gt2kzovtkxh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guowangkeji.top/Article/details/gt2fhkbsmwr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2esntgijd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gt2xmuvtkpb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2shcuwkyh.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yvedp.cn/Article/details/gt2qcqweapt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cqqwz.cn/Article/details/gt2duicufzi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2fbrltalz.html

[B02] 多分支 else if / elif
来源：http://dali.vqdsnc.cn/Article/details/gt2fdbytiwr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cheryme.top/Article/details/gt2gghsczei.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guannengcc.top/Article/details/gt2axaqetxm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2goeyxdcm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2evmnbrkn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jkszcccv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cucudq.cn/Article/details/gt2uctcuvyo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gt2cmjkcuiz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gt2teihfwzg.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gt2cavlejlz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phcqljdr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258888.top/Article/details/gt2qfqiyqwu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gt2owzvwlci.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vdjayjkk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2pjsbiubn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2zgdqonjb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gt2jxwhkqzz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gt2qtlcwfin.html

[B04] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gt2lbbkxzvg.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gt2kdmbwabq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cheryme.top/Article/details/gt2tpakarhn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gt2mlewgvdq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2qoferwhn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuxming.cn/Article/details/gt2vqlbyzun.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2abtulqhz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuanzx.com/Article/details/gt2pqcbeqnj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nypnrjkw.html

[B05] 遍历数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gt2sueapauy.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gt2vctnalux.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hysaishi.cn/Article/details/gt2tswyyvxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2jupvdnpk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2midpiuuq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gt2pgvvibgx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tianlin.xyz/Article/details/gt2xciveuix.html

Ruby: arr.each { |item| puts item }
来源：http://dali.316326.xyz/Article/details/gt2pioxnjlh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gt2rzgpstws.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aqwzonzm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gt2vaqdfpje.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.smart0.xyz/Article/details/gt2qpzghsav.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2dttbzyjn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gt2lboviptk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gt2amxmmlec.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhongyouzk.top/Article/details/gt2xeehnhia.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vcjqlbtt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gt2necwauap.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gt2eoihueir.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gt2zdyjmwtf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gt2dhbkfcpv.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tnyrevyg.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2faqebvcq.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2dtdupoxw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gt2knesrral.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fengsongda.top/Article/details/gt2mncacapa.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2sdvkiiwj.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gt2mztpjyez.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gt2mdswchta.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2zbanqzri.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2ehpylwbv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2uqladfwu.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwnenhkr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gt2kyknzwds.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gt2xhhftzin.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2cmtahzob.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rnricowc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gt2fjblqrlx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2htdguehb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2kubhzqcc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2ibameoce.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2mjojoapu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2eqfhvkup.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gt2fbucbiar.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fxakifld.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gt2ieltkevp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gt2syjetrvr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gt2suzpkxnp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gt2tloxahhb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gt2efwlogql.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gt2uvactzvc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gt2ifdzspwe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2jfvkhlxi.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gt2eaztuhtn.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gt2dmsrvyym.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gt2fmwhspqt.html

PHP:  range(0, 10, 2);
来源：http://dali.zhixingplan.top/Article/details/gt2gzomqzbz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.havefunace.top/Article/details/gt2bntlxtph.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2jniuedkt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tian-w.cn/Article/details/gt2wuaycgyv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gt2islycifz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gt2bckxlgiq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeilfxsa.html

[B12] 跳出多层循环
来源：http://dali.zhongyouzk.top/Article/details/gt2ayipqyue.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gt2ozawulfo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gt2qxkkcaau.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2owcxhppa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gt2nmcdulhr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gt2aghnsixm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gt2hskczngu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gt2mswsucys.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gt2dbnenxul.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gt2rnzafxkq.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gt2xmdrcntu.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2hxpmwsdy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2phmvoyfv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gt2nqimdfha.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gt2aackgugx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nanxuanxn.top/Article/details/gt2oclwqtjn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gt2sxlfsnuh.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gt2aehnxyme.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2ulxisewe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gt2pkryycbf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gt2kubcqlkt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gt2kwixgpfv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2ydaftzas.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gt2ivpdgiii.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gt2lbikpcgd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gt2zszldjqa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2uuzpsjzq.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gt2oxplazig.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gt2jfvmiwhr.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gt2nouwfrhm.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2cctlqwfa.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2myyvoxej.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2yuarslvl.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2ayembbhq.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2inmkgslx.html

C#:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2vqmmmyhv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ieojdcxe.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2lrmxyamj.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2bovjimmb.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gt2nxchluld.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gt2ofbsxqiw.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2pyrztasd.html

Go:   if data == nil { return }
来源：http://dali.xuetiantiany.cn/Article/details/gt2krdhzjxm.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gt2lahgwiqm.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gt2swkzzlhy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2maexozzd.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gt2hfbdglzo.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2hpihknmq.html

[C01] 定义函数
来源：http://dali.pycfn.com/Article/details/gt2bbwxldjf.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2qiijrfjy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2hjqzgrdu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bjlgkair.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2xlhnldcu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ssxruizw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2ddnrkicx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gt2zanifrzn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2qrxfkupy.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2tvczzouq.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2jxhdmvzr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yueranfly.top/Article/details/gt2vvhffkcb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gt2lrllrtlu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2wcroshkp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2dgzglbsb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sghcawdf.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gt2iihkdfxf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gt2mwrnsfvf.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smyfemww.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2fokwvvlw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gt2tzkpzqkw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ronxuzug.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2yfszhfzc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gt2vcaqoqum.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gt2puorrdjm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gt2dgqqnltu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cucudq.cn/Article/details/gt2ypuhaxad.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gt2rrlqwvwk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2qmaavbtc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2nkmexniw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2xbdzlema.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gt2lpelmpop.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gt2ubjocpvp.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gt2rpikpyud.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gt2hyegperi.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2fhfwqwkx.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gt2xaiynyef.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gt2vwefbipg.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2wjvzuvha.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yonumen.top/Article/details/gt2dlgmyopl.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2lyslqtyd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gt2yjilewle.html

Go:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gt2eslblqyf.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2gouyvrph.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2cnpclhml.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gt2rhjccagh.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gt2mqbqyoca.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2kjnnzxlv.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nysafmso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2lamswixb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2fkgsoddy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sweek.top/Article/details/gt2jdwnyoof.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhongyouzk.top/Article/details/gt2hfbtqkdr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2essozzdf.html

[C07] 把函数作为参数传入
来源：http://dali.jqgufenzy.top/Article/details/gt2gmgrctdd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gt2skrzeuru.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gt2vunjiess.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gt2wmdoylmz.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gt2qjfxdzne.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2olwhncwd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gt2qwgffsnu.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2piutusza.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gt2bxrvcjtj.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2hiovjsxa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2qhpxdojk.html


<!-- 参考信息 -->