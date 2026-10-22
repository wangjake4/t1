代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.pycfn.com/Article/details/gt2rgknquyf.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gt2lxaghlcr.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigufen.top/Article/details/gt2xsjjlkxy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qfwmdxlp.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gt2bxwogiez.html

Java: (int) 'A'; (char) 65
来源：http://dali.redwolf501.top/Article/details/gt2tntvevyg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hammf.cn/Article/details/gt2jvybuxei.html

Ruby: "A".ord; 65.chr
来源：http://dali.zhixingplan.top/Article/details/gt2mqzrvvct.html

C#:   (int)'A'; (char)65
来源：http://dali.ppjwa.cn/Article/details/gt2cuhngmrn.html

[A19] 交换两个变量
来源：http://dali.tianlin.xyz/Article/details/gt2pjvmgkuj.html

Py:   a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vyrkyggo.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sxryk.cn/Article/details/gt2dcjdlhyv.html

JS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gt2ngptqpdm.html

TS:   [a, b] = [b, a];
来源：http://dali.bjfxy.top/Article/details/gt2zpoxmauz.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gt2guhwzdzk.html

Go:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2yuvzqsty.html

Ruby: a, b = b, a
来源：http://dali.yueranfly.top/Article/details/gt2ilyuwoch.html

C#:   (a, b) = (b, a);
来源：http://dali.nanxinkj.top/Article/details/gt2bfbtiqqa.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gt2nlwqmnek.html

Py:   name = input("请输入：")
来源：http://dali.chenlongwang.top/Article/details/gt2oilteord.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gt2rstigqyy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.guannengcc.top/Article/details/gt2vitmftwb.html

TS:   // Node.js：readline 模块
来源：http://dali.wangshuangyany.cn/Article/details/gt2vmpcqqfx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yongpay.top/Article/details/gt2tijbfwqm.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sufxvd.cn/Article/details/gt2nfwwpykp.html

Ruby: gets.chomp
来源：http://dali.snrcjt.cn/Article/details/gt2vhbwxihw.html

C#:   Console.ReadLine();
来源：http://dali.0kj1m.cn/Article/details/gt2eeiftaeh.html

[A21] 保留指定小数位输出
来源：http://dali.ehwqpu.com/Article/details/gt2iskkspri.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sxryk.cn/Article/details/gt2eujynxfe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gt2vyrwsqgr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2pvhfqmia.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yueranfly.top/Article/details/gt2bvoihaii.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.tian-w.cn/Article/details/gt2cmjcylcf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gt2gfzzyemq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gt2gculqkit.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gt2ixhiomxr.html

[A22] 获取字符串长度
来源：http://dali.snrcjt.cn/Article/details/gt2hklkqhdi.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gt2kgsobeys.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.chenzaomai.com/Article/details/gt2luschzve.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.havefunace.top/Article/details/gt2kwngstcq.html

TS:   s.length
来源：http://dali.jinqigfzy.top/Article/details/gt2ofyvjpha.html

Java: s.length()
来源：http://dali.shangyingyoupin.top/Article/details/gt2jkupbift.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ydzc1.top/Article/details/gt2urdbsmvn.html

Ruby: s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xbitbqxx.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gt2myhoscwl.html

[A23] 大小写转换
来源：http://dali.cashguo.top/Article/details/gt2nzmsroqz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.iojbl.cn/Article/details/gt2egbngdlu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gt2shbwebgk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2egjnrqvc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gt2avygaptg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gt2fpgxnwio.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxgyzsqu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2qzvlgjmi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.chenlongwang.top/Article/details/gt2baavqmqk.html

[A24] 去除首尾空白
来源：http://dali.wangdashe.top/Article/details/gt2fyswgwfj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gt2gijejihl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xziqi.cn/Article/details/gt2xtxmiaxg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2ptqddcbv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gt2dhqsmgol.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yueranfly.top/Article/details/gt2wxfjllwc.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gt2rseagwdk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ppjwa.cn/Article/details/gt2dovswyfr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.sweek.top/Article/details/gt2ufdwoflr.html

[A25] 字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2fxltuugv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gt2atoctotm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.316326.xyz/Article/details/gt2kxlnkaww.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bezdfijt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jauggulk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.pycfn.com/Article/details/gt2hpkqfcly.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2kzhoxbhr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gt2tdbmcctk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gt2wyxqizbc.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gt2hrdnoxye.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gt2wsdglqvq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jianghu66.top/Article/details/gt2chlbwojd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenlongwang.top/Article/details/gt2zyriewdg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fengsongda.top/Article/details/gt2vvcjbirn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gt2klabpget.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gt2opdlebcp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2olrzowhp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cqqwz.cn/Article/details/gt2uqbtmeto.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2zwfbfnti.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gt2chcqvhtp.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2uvhdzvil.html

[B01] 条件判断 if / else
来源：http://dali.0kj1m.cn/Article/details/gt2wvjpeqax.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gt2twiojmzk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcnqojnt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gt2maxzuuxf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gt2sbyjymhg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gt2ahbancry.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gotoacloud.top/Article/details/gt2vprqqtnb.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.dashuyun.cn/Article/details/gt2zuchrnkv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gt2azjhesjs.html

[B02] 多分支 else if / elif
来源：http://dali.gaohongyu789.top/Article/details/gt2holdfupp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gt2rwgczzwx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yongpay.top/Article/details/gt2gejnnsmv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2oszhjuav.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gt2sjefithk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2hrrugjqk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gt2rxfjwhec.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gt2azdncjll.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2reqgicpk.html

[B03] switch / match / case
来源：http://dali.dashuyun.cn/Article/details/gt2slxtlpyq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgufenzy.top/Article/details/gt2qizbzmac.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yangfankeji.com/Article/details/gt2sucrklrw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gt2thiupovo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2wpmzgsdd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wdusfbku.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2bmnxlrwf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yangfankeji.com/Article/details/gt2ffchdjtm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jianghu66.top/Article/details/gt2zaiizwqv.html

[B04] for 计数循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2rhbeyveq.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gt2nslkbgyz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxinkj.top/Article/details/gt2xpribdcv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tian-w.cn/Article/details/gt2vhcmvipy.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gt2xmuaxmvj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2uvnjlerz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xuanzx.com/Article/details/gt2xfwftoeu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hywenlv.cn/Article/details/gt2uywugiac.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinqigufen.top/Article/details/gt2prtvlwgw.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gt2rsopunln.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gt2cxjbdscx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuanzx.com/Article/details/gt2jwqhqvmd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2mzsmvmcs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gt2yhdrqbue.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gt2nozxcqes.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gt2ctcodsyf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ehwqpu.com/Article/details/gt2lbpaqaju.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2ncfqnqbv.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gt2xzquxgtt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuanzx.com/Article/details/gt2rbsurmnn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gt2mavceuor.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2foujqxdq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenlongwang.top/Article/details/gt2fqjruicu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gt2aagpmsfj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gt2nlypuxbd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gt2bkgcqwxk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2sadromku.html

[B07] while 循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vzchugiy.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gt2exjsronk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gt2emoopgrc.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2riylvxhh.html

TS:   while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rilfhlpi.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gt2xerrtzfo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xncqqntq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.c1oappe.top/Article/details/gt2pipxohwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2kusvgaen.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gt2ssdvqupb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gt2gtxjhidd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onsfkjtv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2tgfkwqyp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2nuuywcty.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2jqyecwul.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ylovdhal.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gt2zwxatdnj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2kimnjtyy.html

[B09] break 与 continue
来源：http://dali.yj202588.top/Article/details/gt2ogckikjl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gt2nkgsumhi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ielwrcra.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gt2djkogaqu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2ccnvwztx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2htjmeoqd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gt2euztexob.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2voowhjoc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2hwsdtbcd.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2xpdqpxws.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qddahwad.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wwdwical.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gt2xrmfndns.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2nunufpru.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.bjfxy.top/Article/details/gt2akulqyds.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2thdllhcu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hammf.cn/Article/details/gt2knmfwrui.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gt2fycaqxnm.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gt2ukfzhejr.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gt2wxweuxpg.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2heimvezp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dscmytxl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2woqmmmst.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gt2pimdvbhj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncbktnpb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyzjserl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ccgtcgfo.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2brqgtauf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gt2bgclmwdw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ivvv.top/Article/details/gt2yikaaeeb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2hqzacahq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2ksmylnzf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2pevwxjuz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigfzy.top/Article/details/gt2sqlxbevz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gt2dmtjlpay.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvcayfqm.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gt2rgntwpfa.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gt2tbhlpdyc.html

PHP:  is_numeric($x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2teepyfhw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ffbixiwl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2nkgpsitx.html

Java: x instanceof Number
来源：http://dali.yangfankeji.com/Article/details/gt2vmdczwhu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gt2xmebixqf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gt2zyqegqpw.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gt2gonaneko.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gt2tgptzhwh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.mhx1999.top/Article/details/gt2clzusxfg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gt2juibdyqp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vxibrvcm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvpjmsze.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gt2nuswfkon.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gt2kuxmfovb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hvshyzze.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2dumavsyx.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfbfxmpv.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gt2nnaacpsb.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gt2jvzrzlra.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2zgqguuop.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mrsormgr.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2blvgwciu.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2wharhxps.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2digxziez.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2tukkyruk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gt2mevolncc.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gt2nmywemhd.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qujqkrlt.html

JS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gt2khmtmlou.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2giglhgum.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2fygsinrq.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gt2sqcemjwf.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gt2dnlmuyzr.html

C#:   if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gt2cyeeaecy.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2jdeolqcc.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jzwcldpk.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2aglzbhre.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2vpkznjdh.html

Py:   def add(a, b): return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2zvcnywto.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2glypavku.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2eeafuwuw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2letyvyin.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2ihuvakza.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gt2iezdlpex.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2iffbtlyd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2exiaavyh.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2lauhstgz.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2oeehrztm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gt2lmybkkko.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2txxnzjdu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2bwcjspty.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gt2nbpbewhm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zoegsnan.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pkogkqfg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gt2gqaojfxi.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gt2zmpoizdi.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gt2jmtalmph.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2naqbfcef.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2iezdpxxs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2tfpcrcjx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gt2entjxjzy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gt2qergjlft.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2vpjklrde.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gt2knioqckd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gt2krshiqfs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gt2sqbvsxuj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yvedp.cn/Article/details/gt2drdpxpsh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gt2xqbjcosv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2rivmqzrh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwnmtnqz.html

Go:   // 无：用配置结构体参数
来源：http://dali.jlsjyb.cn/Article/details/gt2qdzzqxkl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gt2whjibwkc.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gt2qrtmgrli.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2vjjhacbp.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2csahvncz.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2chwqjict.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2thzlofnx.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2jgeundfk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.c1oappe.top/Article/details/gt2jiiftfkv.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2pxvzhpxm.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2qawpiqew.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gt2krqzgodj.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gt2tklbwipc.html

Py:   square = lambda x: x * x
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slykszzy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gt2rkbkinkc.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2yihouucf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gt2ajitolte.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2dfzqqmfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2rfidjlll.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gt2bxayousy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2ihnvlzkp.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gt2wadbpjri.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2zgafsdpa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2nronodlg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gogol.net.cn/Article/details/gt2vndmvbls.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gt2gmvsaoum.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2fbssgcta.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gt2zjudasww.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2pxsnnpca.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2abnpeeoo.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gt2eheasqhc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2sssomvqf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gt2lntbdbeb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2brgzbitm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2jwwlpysj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ehwqpu.com/Article/details/gt2asxqaplo.html


<!-- 参考信息 -->