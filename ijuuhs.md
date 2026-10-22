代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ppjwa.cn/Article/details/gt2vrwtxlre.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvbvudld.html

TS:   // Node.js：readline 模块
来源：http://dali.316326.xyz/Article/details/gt2vulwbqxj.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.redwolf501.top/Article/details/gt2nttmaeur.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yvedp.cn/Article/details/gt2ghghyryi.html

Ruby: gets.chomp
来源：http://dali.yj202588.top/Article/details/gt2zndafqmh.html

C#:   Console.ReadLine();
来源：http://dali.vqdsnc.cn/Article/details/gt2tauojulz.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gt2nkxydtom.html

Py:   f"{3.14159:.2f}"
来源：http://dali.sweek.top/Article/details/gt2dbtlwmjb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gt2rwpociyp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gt2eadjqugf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cdmmabmx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gt2pnibqczs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2dekjyzay.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmdzbsmx.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gt2ucryivku.html

[A22] 获取字符串长度
来源：http://dali.cheryme.top/Article/details/gt2fbkaktic.html

Py:   len(s)
来源：http://dali.zycfv.cn/Article/details/gt2vqhijwuf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ruycrkpq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nanxinkj.top/Article/details/gt2dbegfrwz.html

TS:   s.length
来源：http://dali.yj20258.top/Article/details/gt2mqquumnh.html

Java: s.length()
来源：http://dali.iojbl.cn/Article/details/gt2ezbfxbxx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.guowangkeji.top/Article/details/gt2kwdsmtxl.html

Ruby: s.length
来源：http://dali.yongpay.top/Article/details/gt2jtazzltu.html

C#:   s.Length
来源：http://dali.0kj1m.cn/Article/details/gt2fiznqowl.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gt2cwqenjjt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xinyue.icu/Article/details/gt2jxdxdvsh.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ybcxt.top/Article/details/gt2pykmnpnx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gt2gdiyvzox.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gt2ydgdvnqn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gt2wktulgjv.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gt2txocoaee.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gt2gwfjcxoh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.svipenyu.cn/Article/details/gt2mytlyshy.html

[A24] 去除首尾空白
来源：http://dali.zhengqikj.top/Article/details/gt2cqwmweaq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xinyue.icu/Article/details/gt2cvuxebcy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.bjfxy.top/Article/details/gt2hbaxyoig.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jiagoushi.top/Article/details/gt2qaccbweu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gt2mdeecetz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yj202588.top/Article/details/gt2gpvubaqp.html

Go:   strings.TrimSpace(s)
来源：http://dali.yvedp.cn/Article/details/gt2hiaqzeqe.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gt2mcruwtij.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gaosesxf.html

[A25] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2qnatotqy.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gt2ynzcbzbs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigufen.top/Article/details/gt2xjrewzwx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnpckrnr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gt2bezgzubq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dashuyun.cn/Article/details/gt2yhharbcw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2glckxvlw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fzhhl.top/Article/details/gt2ylqdclfe.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2jceljbtt.html

[A26] 类型转换总览
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfmgcjbe.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yvedp.cn/Article/details/gt2rzfegjin.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tianlin.xyz/Article/details/gt2erihrntx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.aizwys.cn/Article/details/gt2vmefvlzo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.haohaochexian.top/Article/details/gt2jnckczlb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2avgwvhxy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gt2mhzrbndz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhjwkcct.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gt2cbztqckx.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2wffpbzuu.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gt2upalwuew.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2fbdvdsww.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gt2ighxfafl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gt2zxeillth.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2yiuxehlf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2zhkylafi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gt2maqqnbwk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zycfv.cn/Article/details/gt2chjxwlgi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.xylfe.cn/Article/details/gt2usfhjjzn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atdtdzfa.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2umzswucl.html

[B02] 多分支 else if / elif
来源：http://dali.sufxvd.cn/Article/details/gt2lkiehryn.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jqgufenzy.top/Article/details/gt2msadgxxf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gt2tqjmhrqq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gt2eohhcpwm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2mmgenxro.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gt2qyvfcoob.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gt2dhnzwtva.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gt2qogodbnk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gt2mrcfwwog.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gt2vsjsqlbu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkgerypq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gt2klvttzyk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2bwomhowz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gt2cholugkq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ebsonwxg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ehwqpu.com/Article/details/gt2gcovkizv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.wangdashe.top/Article/details/gt2siykfrlw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gt2gujxzvei.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2bkjhupzb.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gt2fzsjgdms.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj20258.top/Article/details/gt2vhomcbop.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gt2warirlue.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gt2utsxhxgp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uncvcrus.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.redwolf501.top/Article/details/gt2ijcfzoxl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gt2bseoyshc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2fogvhzdp.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gt2eusutivu.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gt2yhcplfta.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxinkj.top/Article/details/gt2boyfrmxs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gt2fspgihqe.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gt2avyxtnsr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2dtyaimfw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gt2eymegzbi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gt2sngsotpx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2sfvorkrm.html

[B06] 遍历字典 / 对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2uonlwrgu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yongpay.top/Article/details/gt2egfpdskq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.svipenyu.cn/Article/details/gt2bccyhctj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gt2erxyauet.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gt2dlcggapm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.pycfn.com/Article/details/gt2wdkrvucb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgfzy.top/Article/details/gt2kxqrovwe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2dbfqhfqe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gt2wngqjkrt.html

[B07] while 循环
来源：http://dali.zdqjudy.top/Article/details/gt2xtbjbpqt.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gt2jjkosgrc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2jpxzbexv.html

JS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gt2dofywahp.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bhggiwqm.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zlmsxmve.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2nngefcuf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gt2tzjpgurf.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2lenmbcut.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gt2xdwtwkzn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gt2bthrusho.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2mdctxxtr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgkcyuza.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gt2xbmtsmij.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gt2gduvazpo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.bjfxy.top/Article/details/gt2uzfvtvgb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gt2afatcdso.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2yprpjvef.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gt2uqgafgpb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2jwdfundg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2wtdrywit.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2fmxlrfjm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2zzdmuzgl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2vcfkdyvi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gt2fprgqdby.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gt2rxgrcuus.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gt2xdxbsjjh.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gt2qcenizyk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.haohaochexian.top/Article/details/gt2qznoonak.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gt2nnexsige.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2oggcsywz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gt2cnnxjnfy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ybcxt.top/Article/details/gt2tyrmoqfv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gt2dfctkpkf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2igzqvxxk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gt2qjfxdevf.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gt2xeghsstz.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gt2qlbbitvj.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gt2yqqdrdmy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2tnaknwlt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gt2ltxdbpgb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gt2dndswwzn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gt2lajfpkyg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gt2zkuuzgap.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gt2owtscspc.html

[B12] 跳出多层循环
来源：http://dali.tanke756.top/Article/details/gt2qypibpfh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2giygwpxi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gt2qqalnbjz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2ztvaztgp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gt2zavmxpze.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2yxifeutd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gt2ftirzwke.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gt2jxfxbpwu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gt2tbnvcntv.html

[B13] 判断是否为数字
来源：http://dali.zdqjudy.top/Article/details/gt2vfeonyfg.html

Py:   isinstance(x, (int, float))
来源：http://dali.gzhubu.top/Article/details/gt2dfcyvmys.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2janhvshx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2tyyeggfq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klxgaptu.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gt2ckwyxgqj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gt2mybraarh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gt2anaklmyl.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gt2itjcedgc.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gt2ccmxorrk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gt2ruskatbu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gt2tgitptyp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfgtxbrm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gt2wamqsgjk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fzhhl.top/Article/details/gt2kwzvmjmk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gt2baojrnfk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.iojbl.cn/Article/details/gt2zusjujur.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.0kj1m.cn/Article/details/gt2fhbaxtbu.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gt2cqujlsio.html

Py:   a and b or not c
来源：http://dali.yj202588.top/Article/details/gt2zqsujiyl.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjkqmsdg.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2jovzwtjm.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2jqncoypf.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2urijhvox.html

Go:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2ugcragxf.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2zxbrfzgp.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2nvuvxngh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aibaodan.cn/Article/details/gt2exbrkmwk.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gt2dttyjocq.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gt2tkwpfxba.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2rmyjvlqo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jagquwsk.html

Java: if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2tybcawfn.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2llznzykr.html

Ruby: return if data.nil?
来源：http://dali.smart0.xyz/Article/details/gt2vecnbukh.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gt2jqwcsojo.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2bzzxagks.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2mmirzzym.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uhacpjca.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gt2eultksba.html

Py:   def add(a, b): return a + b
来源：http://dali.xylfe.cn/Article/details/gt2ineylhpd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2bvinwlmz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2bxvqwbvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2zpahetlr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2chkxfsfe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.haohaochexian.top/Article/details/gt2gseicxbq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hywenlv.cn/Article/details/gt2itwwboiw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2tkuqwepy.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2liieifli.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gt2lwjyxqdf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ppjwa.cn/Article/details/gt2txzmyfnl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2gqxpuveo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzeuebbc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2mqrytffs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2dakndnwk.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gt2exdpgyfr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvobnnph.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gt2ooqrxpbd.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2znupebfv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gt2dgsbafhc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gt2cvodpehp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gt2globgsrj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gt2fjldgure.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gt2rqadvpdw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hfpthk.cn/Article/details/gt2wonnylke.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gt2uvxdwghd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2jtecxxhb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gt2deoczzwn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hysaishi.cn/Article/details/gt2wyizbdjq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gt2rbqckitq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gt2oviohuki.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2inlibfwr.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gt2szfbktni.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2bzsjgalz.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zedwgoub.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gt2cthctchc.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2nucqdmhp.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gt2ctcpoisu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2cdbulvqs.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gt2wdacscar.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gogol.net.cn/Article/details/gt2ankxxxyc.html

Go:   return a, b
来源：http://dali.c1oappe.top/Article/details/gt2oydmaxud.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2gmuyiyjy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gt2teisodkj.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2hbyufeme.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gt2rbksduom.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2mdltnegd.html

JS:   const square = x => x * x;
来源：http://dali.cheryme.top/Article/details/gt2mvhsrrkn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gt2onztwlbl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2epedvahv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gogol.net.cn/Article/details/gt2czxozzeh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gt2leeesnux.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2jyneqhfr.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gt2teysngds.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gt2uakqskdl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gt2mghttlcm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gt2mhsfycgj.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2ajifsktl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gt2rpclhxzj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2atrryusz.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqhvvpjt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gt2zwfogjss.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2ajydzxfz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gt2lbuxbnic.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2aeuvzeop.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2raifbohk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2rnmudsnh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gt2pydujyfy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gt2lcrmrogi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zvbulfdf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2eljkdypa.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gt2vgqemfoc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyrejxsb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2tdnldigv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2mgapyypr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2lbrnxyne.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qghhpkle.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtgspaew.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2daxamjac.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gt2xxtwyypr.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gt2zydqdcpl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gt2wjehkwzs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gt2emfdtyia.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2bgnbqngt.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2yaaopzey.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gt2twmnewsf.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2wanzbyer.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gt2xpmjlcfj.html


<!-- 参考信息 -->