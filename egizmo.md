代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gt2sjmjafuz.html

Java: (int) 'A'; (char) 65
来源：http://dali.jianghu66.top/Article/details/gt2cgnjzkku.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.cheryme.top/Article/details/gt2vapmtwed.html

Ruby: "A".ord; 65.chr
来源：http://dali.kuanghao11.cn/Article/details/gt2dlepqula.html

C#:   (int)'A'; (char)65
来源：http://dali.aibaodan.cn/Article/details/gt2qembdsfd.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gt2cmgwpctv.html

Py:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gt2uiedbzvq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj20258888.top/Article/details/gt2vnyhmigd.html

JS:   [a, b] = [b, a];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwzvoyzs.html

TS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gt2vehjsslh.html

Java: int t = a; a = b; b = t;
来源：http://dali.cucudq.cn/Article/details/gt2etnmkcex.html

Go:   a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gt2rorudmps.html

Ruby: a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gt2emslumae.html

C#:   (a, b) = (b, a);
来源：http://dali.guowangkeji.top/Article/details/gt2zoxvzieh.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gt2tihqmivm.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gt2rnjanygr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hongshengwenyu.top/Article/details/gt2wrznrorr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.ppjwa.cn/Article/details/gt2hrmxyazv.html

TS:   // Node.js：readline 模块
来源：http://dali.shangyingyoupin.top/Article/details/gt2rqlcdkyu.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.mhx1999.top/Article/details/gt2saiwkoaz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gt2prfgzvmf.html

Ruby: gets.chomp
来源：http://dali.kuanghao11.cn/Article/details/gt2jshqrejz.html

C#:   Console.ReadLine();
来源：http://dali.wangshuangyany.cn/Article/details/gt2ppyfhoxi.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gt2ntoptvhq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shzxlz.cn/Article/details/gt2efqnjene.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gt2glyvtidy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.mhx1999.top/Article/details/gt2zlymwhkj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj202588.top/Article/details/gt2opbcoptv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gt2rhzliqqc.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gt2wnxfqniz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hecraqhw.html

C#:   3.14159.ToString("F2")
来源：http://dali.chenzaomai.com/Article/details/gt2wyveyqvg.html

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2lstywhos.html

Py:   len(s)
来源：http://dali.yj202588.top/Article/details/gt2zxecwtkm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daria6918.cn/Article/details/gt2rhkyieqe.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shuidangran.top/Article/details/gt2uvfhmtsp.html

TS:   s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ickznugy.html

Java: s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hidwsdxq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmahvvsf.html

Ruby: s.length
来源：http://dali.yuxming.cn/Article/details/gt2bbbocwsi.html

C#:   s.Length
来源：http://dali.xylfe.cn/Article/details/gt2uwqreern.html

[A23] 大小写转换
来源：http://dali.yongpay.top/Article/details/gt2qgnanycp.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dianchejie.cn/Article/details/gt2bpnqyhju.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuanzx.com/Article/details/gt2psionsbj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gt2dbnmmknt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gt2cxrymitt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenzaomai.com/Article/details/gt2zxykyadb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jyoumei.cn/Article/details/gt2zrhyuimv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sxryk.cn/Article/details/gt2gcloqdrn.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gt2jmvyswqv.html

[A24] 去除首尾空白
来源：http://dali.fzhhl.top/Article/details/gt2eqmhjdzd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gt2wczzompp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.iojbl.cn/Article/details/gt2adhlcppw.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gt2vavlzmsx.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbuujpbg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj20258888.top/Article/details/gt2ggmgxufl.html

Go:   strings.TrimSpace(s)
来源：http://dali.xinyue.icu/Article/details/gt2udwpbero.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gt2hjscorql.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gt2pqlliyor.html

[A25] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gt2udgiiqek.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gt2ybsjayrf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2skihnqun.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2ldgegyao.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gt2vmplxemp.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gt2ovnoxusq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gt2wetakvlo.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmtuwvcu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.iojbl.cn/Article/details/gt2rchxlzmt.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gt2kyqzvldb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jyoumei.cn/Article/details/gt2senvxwuw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ppjwa.cn/Article/details/gt2xmebpxrg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gt2jveuzdtk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jiagoushi.top/Article/details/gt2mhygwwha.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gt2pmmcefnz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gt2srkrzpcz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2saclrarp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuaqwqfd.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2amlvphnb.html

B. 流程控制
来源：http://dali.9152youxi.cn/Article/details/gt2cnssplin.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2fzjrcerl.html

[B01] 条件判断 if / else
来源：http://dali.xuanzx.com/Article/details/gt2qrmxfqzv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hammf.cn/Article/details/gt2ojxsozgp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2hzoabxar.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2xkmpfczt.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sysykeji.top/Article/details/gt2rbuthrjg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2wyppylnt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.andypj.xyz/Article/details/gt2qikvfkbe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ydzc1.top/Article/details/gt2hlumtvtw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2dkwytzbx.html

[B02] 多分支 else if / elif
来源：http://dali.smart0.xyz/Article/details/gt2qrkzyslz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.smart0.xyz/Article/details/gt2kmxesrhl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yangfankeji.com/Article/details/gt2yrqylkmr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2ivekvbfu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2giejlcil.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gt2hxczwwef.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gt2zfqdafyj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.redwolf501.top/Article/details/gt2xkdrhbth.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2kgrpuked.html

[B03] switch / match / case
来源：http://dali.quarkkingdee.top/Article/details/gt2tgnnexoe.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gt2vowntaqb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ifyalxlp.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yzhmehnc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2drczzsaj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2lozfnhpg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gt2ezapsahh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnqzz.top/Article/details/gt2razzisdk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gt2urifwgqt.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2lowiyzgj.html

Py:   for i in range(10): print(i)
来源：http://dali.ydzc1.top/Article/details/gt2htbvpiau.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gt2dfpjoqkk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gt2xfficzfd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2iddfehzb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2dzpjpixb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgufenzy.top/Article/details/gt2oogdinkd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gt2vfepguce.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2unirkzry.html

[B05] 遍历数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gt2xterdbwz.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gt2mfadlfug.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sxryk.cn/Article/details/gt2zimvkvxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gt2mkeqwdvt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gxmevbjc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhoulong.xyz/Article/details/gt2xdsrjfrw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2sckatawh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gt2smfdsblm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fzhhl.top/Article/details/gt2bxuprqae.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gt2wnjkvbmh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.iojbl.cn/Article/details/gt2vdqsxxzi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hugknmif.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2qogdesiu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cashguo.top/Article/details/gt2kkqbfqga.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gt2augtpkfo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cdnleiting.top/Article/details/gt2kwapqqlr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lomgjpvp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gt2mzrffhvm.html

[B07] while 循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jhtaiglp.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eelxvbpd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuanzx.com/Article/details/gt2uetuisme.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2loyhzmrk.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2vauworgs.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qjqhqrou.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gt2asotqjno.html

Ruby: while i < 10; i += 1; end
来源：http://dali.smart0.xyz/Article/details/gt2zifpqwud.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2whevluqg.html

[B08] do-while（至少执行一次）
来源：http://dali.smart0.xyz/Article/details/gt2tbbtuubv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gt2pytaucpj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2kcmjmgyb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2yvaekakv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2penojatj.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2mehtkfjz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2oqghudps.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jyoumei.cn/Article/details/gt2wajfbssy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gt2kqvzigcc.html

[B09] break 与 continue
来源：http://dali.zhiwuduotai.top/Article/details/gt2nubrjkyq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sxryk.cn/Article/details/gt2shvqukrf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gt2wogiadml.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbbwbjnv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2gumxpukn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2cpddjxkg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2oogsfzuh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jdudeing.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2cxxaaztr.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ptsqdqhm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gt2pzouxolp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2epmpjkdk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gt2xbvtgcrw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gt2uvtttlnp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gt2vfnywtgn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yuxming.cn/Article/details/gt2xhkjtpxc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gt2sngtnyhd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gt2lssdelid.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gt2mulcjllf.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gt2sqxxdphv.html

PHP:  range(0, 10, 2);
来源：http://dali.pycfn.com/Article/details/gt2gyzykkbv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2csgfugnf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gt2hzyjvwub.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2mvguvsaf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gt2drkjdfww.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cheryme.top/Article/details/gt2nhcprlga.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gt2vzcxnnkf.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gt2qoqgqbzg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guannengcc.top/Article/details/gt2dqdgfthv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gt2jzoapqms.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gt2jkvhovui.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekmewmpk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2owawecoo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gt2dmsvwcoi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gt2ehqthlks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gt2eaickziy.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tihitugf.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gt2gshcpirr.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gt2jhebehxp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2srrgczwn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2iuwpqyew.html

Java: x instanceof Number
来源：http://dali.jqgfzy.top/Article/details/gt2nyzixoji.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gt2qujdwzfe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gt2cznqybxb.html

C#:   x is int or double or decimal
来源：http://dali.guannengcc.top/Article/details/gt2qozahafr.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gt2ruesngnw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hammf.cn/Article/details/gt2kqzfnzzn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gt2tlxoqrml.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2txkscxyo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gt2tbaniaid.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2njuralvh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.andypj.xyz/Article/details/gt2ogliknum.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxinkj.top/Article/details/gt2scuxsofq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtuwkgai.html

[B15] 布尔运算与取反
来源：http://dali.yvedp.cn/Article/details/gt2utrhbuzm.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gt2yfvgutzh.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gt2lbxedxja.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2byheyyfp.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fdrwnlhm.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2iwobzeyd.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2cmlnvzbl.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2rgchfchx.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2lhhoblqn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gt2jsgkciri.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gt2klxpfiko.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhjunosj.html

JS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2yhtlupqw.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gt2ekhewdfw.html

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gt2ksizjjfa.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gt2cfckyyva.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2xbtbjbmu.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2jldyubka.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bdidckoh.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2osbtwqyi.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2dtnuwddx.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2gyefsqhv.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gt2jmzoclai.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2fkddwzli.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2xxwuwrva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yfqhethr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2xzzxutzw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gt2hnmdbryy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.dashuyun.cn/Article/details/gt2vzzeektm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2ahbeakpt.html

[C02] 默认参数
来源：http://dali.xuanzx.com/Article/details/gt2bmimhdgo.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gt2gslbhyuk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2rnkvyxtj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sglgsdib.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gt2uqawusgu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gt2kwkoprbk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gt2zbfporon.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gt2pexzbmkm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shuidangran.top/Article/details/gt2xlyigthk.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2dcznntwn.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gt2tgwujqbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2cnowkuew.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2gcwdwsgb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dufsmykh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gt2pojmkhku.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gt2onmuctnl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gt2vimqwkfm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gt2pzgjggew.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2skwnthnk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dttkmlrn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2uvqeruqg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2peigghmn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gt2ugokrfsd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gt2mlouwhww.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gt2uggxhxtj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2xcrpcmjr.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2bsxypuwz.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2ugvuqtax.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gt2awskvsor.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2mvhlcysw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gt2pbwkjeml.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2vmldrmep.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gt2lyhyiqsp.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2kcyppajh.html

Ruby: return a, b
来源：http://dali.vqdsnc.cn/Article/details/gt2pavtuvto.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gt2ljmhlsjm.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gt2vtbspuqp.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2xmkbjczo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2azpgzwvq.html

JS:   const square = x => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lbbiuqmo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vucstgan.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ctadevjb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.mhx1999.top/Article/details/gt2rmiazcse.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2mqncmpaf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2cyfkbsvb.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gt2kbyyeaaz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gt2viyluhng.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gt2otccetlj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gt2erofgegl.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2rtdgpiwc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gt2youwqnoh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gt2mgcwuwrz.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2prmzavcb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gt2kdwukelf.html

[C08] 闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2jntzwmyy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2uobrlaak.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gt2edfpmaua.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2ssxwkywg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2muuegthm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gt2thqczckm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gt2vgideamc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2grybwgcq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gt2zmymnrkz.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gt2hmeibcxx.html


<!-- 参考信息 -->