代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.ivvv.top/Article/details/gtryodbukf.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtfxjkrcza.html

PHP:  ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gtdkuqzves.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtxyidekij.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jqgfzy.top/Article/details/gtvjhewrpr.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gtrstlvpxk.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.gzhubu.top/Article/details/gtxpeokibz.html

Ruby: "A".ord; 65.chr
来源：http://dali.hongshengwenyu.top/Article/details/gttvinwunx.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gtglwozgea.html

[A19] 交换两个变量
来源：http://dali.fengsongda.top/Article/details/gtmhgyrvlm.html

Py:   a, b = b, a
来源：http://dali.feifeiyinyue.top/Article/details/gtxjknecso.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gaohongyu789.top/Article/details/gtujfwvorf.html

JS:   [a, b] = [b, a];
来源：http://dali.xziqi.cn/Article/details/gteqdqslau.html

TS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtustqfahm.html

Java: int t = a; a = b; b = t;
来源：http://dali.redwolf501.top/Article/details/gtfmawttro.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtfrbyrlna.html

Ruby: a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gtjsmwsfwb.html

C#:   (a, b) = (b, a);
来源：http://dali.zhengqikj.top/Article/details/gtgtmnzorq.html

[A20] 读取标准输入
来源：http://dali.gogol.net.cn/Article/details/gtbredtzip.html

Py:   name = input("请输入：")
来源：http://dali.yueranfly.top/Article/details/gtwmphucvu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.tanke756.top/Article/details/gtdypnywnz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppjbgkng.html

TS:   // Node.js：readline 模块
来源：http://dali.dianchejie.cn/Article/details/gtbmzdwxwn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.birdmap.top/Article/details/gteepwvwxt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sxryk.cn/Article/details/gtkwnqznmi.html

Ruby: gets.chomp
来源：http://dali.daria6918.cn/Article/details/gtayttlrgz.html

C#:   Console.ReadLine();
来源：http://dali.yuanzhike.top/Article/details/gtqqveltwv.html

[A21] 保留指定小数位输出
来源：http://dali.yueranfly.top/Article/details/gthbzcxwgr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.svipenyu.cn/Article/details/gtnorcnusw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtbizksjpv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtefrbmfbp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagqlytid.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtzxylfied.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtqbegigco.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtwckaquni.html

C#:   3.14159.ToString("F2")
来源：http://dali.xuanzx.com/Article/details/gtwckruhvt.html

[A22] 获取字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtwcrwonid.html

Py:   len(s)
来源：http://dali.daxiang520.top/Article/details/gtjbxrcbva.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zdqjudy.top/Article/details/gtzzvcuglb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.guannengcc.top/Article/details/gtgpkxwvko.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gtkyqktski.html

Java: s.length()
来源：http://dali.gzhubu.top/Article/details/gtdlxzdczu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtiuxaxero.html

Ruby: s.length
来源：http://dali.bjfxy.top/Article/details/gtrktwbheq.html

C#:   s.Length
来源：http://dali.yueranfly.top/Article/details/gtkbeoqeqk.html

[A23] 大小写转换
来源：http://dali.cheryme.top/Article/details/gtnwghfgjg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gtmuqgpyoo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.mhx1999.top/Article/details/gtfnrylhcz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.bjfxy.top/Article/details/gtsxzrfcfx.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ppjwa.cn/Article/details/gtoylplbjh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ivvv.top/Article/details/gtdzqijhvv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gogol.net.cn/Article/details/gtonjbcqeb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shuidangran.top/Article/details/gtjwbnqvzx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guannengcc.top/Article/details/gtjlquymsx.html

[A24] 去除首尾空白
来源：http://dali.hnqzz.top/Article/details/gtwwkqsjes.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dashuyun.cn/Article/details/gtlbjiafne.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zdqjudy.top/Article/details/gttpafkijv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shzxlz.cn/Article/details/gtcnilhilt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtpirygouy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hnqzz.top/Article/details/gtuouborrb.html

Go:   strings.TrimSpace(s)
来源：http://dali.jinqigufen.top/Article/details/gtyetwayha.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fzhhl.top/Article/details/gtweqlsvsl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtpohfhcxc.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtyirxsdzp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hammf.cn/Article/details/gtskdaorud.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtbwrvhvzc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gtjuycdviy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gtdvbspbmh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dashuyun.cn/Article/details/gtxuroglxd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtpcfrroge.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gotoacloud.top/Article/details/gtslyfcgcq.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gtbuqbtweh.html

[A26] 类型转换总览
来源：http://dali.yuanzhike.top/Article/details/gtucgmzilj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkklaovws.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.gaohongyu789.top/Article/details/gttpblgqie.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.pengpengdd.cyou/Article/details/gthfhkdmjk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtsolnadeg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gttxcnoypr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gtysiutqpe.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hammf.cn/Article/details/gtceragwnh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtfktnyzpn.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtnzybaben.html

B. 流程控制
来源：http://dali.fzhhl.top/Article/details/gtqhgxhdpy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtoupnexyk.html

[B01] 条件判断 if / else
来源：http://dali.pengpengdd.cyou/Article/details/gtduytuspp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cdnleiting.top/Article/details/gtpsdswsan.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gtjcdztekq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtpkhowrdv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweerscly.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtqdznbief.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gtvckkpwtr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtwfftejot.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtewqrwkqo.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gtetvjsxym.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ehwqpu.com/Article/details/gtjbjayuet.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhengqikj.top/Article/details/gtfpddpfus.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpelpfek.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtaivplhqj.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtnyiaidzy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.316326.xyz/Article/details/gtmlsrlrmw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gtzgsrinnc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtnhqwhtcc.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtwvclarvt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtdcpqacaa.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxggravqr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmjylcwd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtuupwkwng.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtxwowerwc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tian-w.cn/Article/details/gtqykohrnc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xinyue.icu/Article/details/gtqwfhcobb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtixxxftes.html

[B04] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtgdecamss.html

Py:   for i in range(10): print(i)
来源：http://dali.hysaishi.cn/Article/details/gtwahsnkcl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtxuidhnkc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gticoekbbx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtuoxjzksb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtliikcewh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuanzhike.top/Article/details/gtodddwous.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yueranfly.top/Article/details/gtwuoxmuuc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gtjzuvcxou.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtvbcnyadx.html

Py:   for item in arr: print(item)
来源：http://dali.gaohongyu789.top/Article/details/gtrgyzhsbm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtksumlimu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtqztbyizm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtginozyda.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.havefunace.top/Article/details/gtyctdypbl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gtevncxfdy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtgsjdugnl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gtmnkrmfic.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gtmrmsxusj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhoulong.xyz/Article/details/gtofkmazef.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkwbndfdl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gttofmndbv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtzoynobxy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gtjbtycdlg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhoulong.xyz/Article/details/gtkthszulf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gttsoknsmd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gthprdjqad.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrtkvflb.html

Py:   while i < 10: i += 1
来源：http://dali.yvedp.cn/Article/details/gtmcivaauk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtmhgsdvaq.html

JS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtwjlymqqf.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtsxpxyhpi.html

Java: while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtnjtllwjw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtgwvjiemd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gteinumwmh.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdtsgmjd.html

[B08] do-while（至少执行一次）
来源：http://dali.chenlongwang.top/Article/details/gtnavkazle.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtnknoguag.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvdnxyzn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtjplxfinp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcxlkpffx.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gthgyyeogz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.c1oappe.top/Article/details/gtzmeunyam.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hammf.cn/Article/details/gtuwtqkchs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtxfgckudb.html

[B09] break 与 continue
来源：http://dali.vqdsnc.cn/Article/details/gtkyspsrrh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.vqdsnc.cn/Article/details/gtrbmoaegc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtreqqqtfh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtdjwqiwvu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtkropofti.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtfjwhjthb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gtqfavtkpx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gttrolazrb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtkbjfaqrl.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gteuplsbhr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtqwdghcfj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gtsfpitukn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtriduykzf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtrikgzhni.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gtafskddok.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gthiztwdwn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.9152youxi.cn/Article/details/gtubglnwii.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenlongwang.top/Article/details/gthqcalgal.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzazsxjkp.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtkeujsoca.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtzdlusmqr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtvprdhmgf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtlooooatk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtyewwgbam.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtranknobo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtmyjxjvsn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gtmeskgmpc.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtzfyhubdx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gtvguledfy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtniupfoxa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtsvtdxxvw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtqrrawhrs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtubfypame.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtvfwqvuyh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtrlkpafpe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtxonqhlnt.html

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtvhdkhbpi.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtfnofqdhk.html

PHP:  is_numeric($x)
来源：http://dali.cqqwz.cn/Article/details/gtrnwbvczq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkawurzlg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtaakuwvvd.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtmfojxzyr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtdolphuqz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gaohongyu789.top/Article/details/gtzzxaywfp.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtvjxjjwcl.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gtjxawixyp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gtyytgghen.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.redwolf501.top/Article/details/gtqugmcpgj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtqnlhpiqv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gtyzlzawvn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtqtpasuvr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gtzwchrsno.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhongyouzk.top/Article/details/gthirvirtp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxwobrxg.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gtuelplvyt.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtzuqmkjhv.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gtrkxcqmtr.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtmsvpbjwa.html

TS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtxfpgovaf.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtpmublpee.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtulfrftds.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtltupftyq.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtvhwadmsx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtqegytckl.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gtimxtljbi.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtdhbtecwi.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtgdjlstwm.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahhajrkv.html

Java: if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtuksmmtox.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtiiukghbr.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gttulowoeh.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtxopmcokd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgceqnxzl.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtbnnfvfqx.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtebkeawgi.html

[C01] 定义函数
来源：http://dali.316326.xyz/Article/details/gtpjxybldd.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxuatrxn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtoidjplaw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtajmskezn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtmlvywgzz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtecynazmm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtjufwcrde.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gtcrnfozvl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtytfkcqza.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtkhmnqskq.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gtvadizhiw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtbehqabyd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtjykwwpza.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtgurctgnb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtnimjdtyj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtxqkhshug.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtytkoogxw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jyoumei.cn/Article/details/gtweonhdzl.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtjrvakloy.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtildjslcs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkswjdujx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtibegqice.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfluuzvva.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtlcizaeaq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gtyglxhqvn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtryticaic.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtltyffvki.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtdcokivol.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gthxxvhmxg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtzqljkdug.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtssdgpmbu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtcrgtgjuv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gthxfcqvlo.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gteekjhzqe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtvjefzvmc.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtqamoziyt.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtdhpuwvsh.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtmubvattc.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtwcmobqeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtwjraaqdj.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtxogkcahn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gtxfiilser.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtbraglldg.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtwwnfyswo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtdpssyxqe.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gtdhtyquxl.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtpizyicnz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtrqrpilrw.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtrqjpkbni.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gttwevyzfs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtbwazwxgg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gtfjmajlca.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtgyuszmyi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtppiqopeo.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gteotajnee.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkeqqfxv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtvsfqykei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tian-w.cn/Article/details/gtjpnqtztl.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gtbiuweuir.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtjbeakrou.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gtbmgifngt.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgbiclmn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrtyoyqvw.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtfilfvuxq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gttbwyjxkh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtmpboprzw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtfygrmedb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtapavwkcm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtqkvlifxs.html


<!-- 参考信息 -->