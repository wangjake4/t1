代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gtkedvmugy.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gtflyfbiyp.html

TS:   // Node.js：readline 模块
来源：http://dali.birdmap.top/Article/details/gtcdewaiuz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjemqpzi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nwbrower.top/Article/details/gtwxcujryc.html

Ruby: gets.chomp
来源：http://dali.xuetiantiany.cn/Article/details/gtushlocvi.html

C#:   Console.ReadLine();
来源：http://dali.jqgufenzy.top/Article/details/gtozywfkzd.html

[A21] 保留指定小数位输出
来源：http://dali.tanke756.top/Article/details/gtiqyjppxn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xziqi.cn/Article/details/gtnzuzpnch.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jiagoushi.top/Article/details/gtefhkqunu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtorvsuzuj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtywgeoxot.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtlkyptexs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtduajrvrk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gthgayewtw.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gtpdrehtnu.html

[A22] 获取字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtrlbilzum.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtbqhiewfi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnqzz.top/Article/details/gtgxbbdcdl.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gtfxjbsxjv.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gtmazrgtee.html

Java: s.length()
来源：http://dali.daria6918.cn/Article/details/gttzctysbh.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.sxryk.cn/Article/details/gtokvcmlgl.html

Ruby: s.length
来源：http://dali.0kj1m.cn/Article/details/gtxzlmdxit.html

C#:   s.Length
来源：http://dali.gotoacloud.top/Article/details/gtfwvwmhqm.html

[A23] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtuppbqerg.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinqigufen.top/Article/details/gtwrxucaat.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.quarkkingdee.top/Article/details/gtodxzzztp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.c1oappe.top/Article/details/gtkflezzxf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.iojbl.cn/Article/details/gtywvaivqg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sufxvd.cn/Article/details/gtuypsrsoi.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gtnvvmsmwd.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.daxiang520.top/Article/details/gtqsvcdpgr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.snrcjt.cn/Article/details/gtduvfxujf.html

[A24] 去除首尾空白
来源：http://dali.hywenlv.cn/Article/details/gttcagwapn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gtszhdnpjt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhoulong.xyz/Article/details/gthjcrsfro.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtmrouvpnu.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtipgivtmu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhixingplan.top/Article/details/gtnwmzotdx.html

Go:   strings.TrimSpace(s)
来源：http://dali.mhx1999.top/Article/details/gtumcrczva.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtavzkbrol.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gthhtbnpag.html

[A25] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gtamezxrcl.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gttmbzjuzk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtjqqkdihl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtrxhhwyqj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuxming.cn/Article/details/gtlgmdfwav.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtllapyhxd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hammf.cn/Article/details/gtedjtyuqr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.snrcjt.cn/Article/details/gtodgeszgj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtvkjmeyup.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gtkeunozej.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.kuanghao11.cn/Article/details/gtmmwnowvj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daxiang520.top/Article/details/gtzhsbgwwo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sxryk.cn/Article/details/gtshijnkoy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtreutnyor.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.guannengcc.top/Article/details/gtptowcedm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hammf.cn/Article/details/gtcbbnhtil.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gttqsclvdp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtzhnpckqu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijrcdmzh.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtdxlafxwo.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtalfnmvtt.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gtdmfmhxbf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwgfsdjy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cdnleiting.top/Article/details/gtsszfxnsf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtcybfftba.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtlllvpvjn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gthhkipxnn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hywenlv.cn/Article/details/gtgrzwtgho.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtsbfwleog.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtmhzfzoex.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gtrlftphyf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtbvuqqlpr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.sysykeji.top/Article/details/gtivfiluxt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtvrviplsi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gtwhyaqohd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtibaddxpp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.birdmap.top/Article/details/gtxhasemxa.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gtirpgbxnc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yongpay.top/Article/details/gtdviwmpdp.html

[B03] switch / match / case
来源：http://dali.cashguo.top/Article/details/gtdjzjsbmq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtbvhcnhwe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtrjvocssb.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtzlslckwz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtdbloprxf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtwxufbesl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yvedp.cn/Article/details/gtnbpfjolw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gtbuxxcjpd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258888.top/Article/details/gttnrsqsta.html

[B04] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtfozwrivo.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gtzluaappk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuanzx.com/Article/details/gtbhxjyuww.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtihbjsjmr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sufxvd.cn/Article/details/gtdrlkzdke.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtnplpjgyv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gtdyluvhnd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ybcxt.top/Article/details/gtjmykzrao.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdpgsceb.html

[B05] 遍历数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtuowqykhp.html

Py:   for item in arr: print(item)
来源：http://dali.zhoulong.xyz/Article/details/gtqhisnoue.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daria6918.cn/Article/details/gtgcaauqpt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gthaccaygo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzcefwdm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtdxdrtcsd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gtoptrunpz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gtontmwptc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbqlgcyr.html

[B06] 遍历字典 / 对象
来源：http://dali.smart0.xyz/Article/details/gtmnkkiqav.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtnyyeykbq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenlongwang.top/Article/details/gtxknqgujn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtkagyzjep.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtbkslpwtm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtrvuwmnkf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gtfecptpbe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gtrxwpqnqq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuxming.cn/Article/details/gtjashggev.html

[B07] while 循环
来源：http://dali.9152youxi.cn/Article/details/gtoksigpak.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjawqyut.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.mhx1999.top/Article/details/gtpzyoguac.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtcxueygis.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtxkojledz.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtblwrzqxf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jianghu66.top/Article/details/gtqsstykyy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtqncvjqgx.html

C#:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtldxcrkzk.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtcwnpikus.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gtkmtblpfq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtuvsidmkr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtqowsvrow.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybhqpkmw.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtpxvejttw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtnfvhgdko.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gtgftcduet.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtueptexps.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtmuzhixox.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gthmnyjtrb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqyxemagn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtoufeykec.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtbfhpvcff.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtruwzgrlo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtctfusfhi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cqqwz.cn/Article/details/gtbfxhqngr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtnnbkbyih.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrjivvcc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhixingplan.top/Article/details/gtymppmyir.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtdtirbrlv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemyktogk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtlqzhxycl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtckcifawi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhyitcpe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtgeibvxja.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guowangkeji.top/Article/details/gtpehvtgjy.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtbzdgodrj.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtbkcogeei.html

PHP:  range(0, 10, 2);
来源：http://dali.jyoumei.cn/Article/details/gtfapgwmdg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtjggtlkmx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaohclyg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gtuneztyxl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gtmvrkswur.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gtxtvewpyh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtjvgljyss.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtceldwosm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjchrwed.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtcbjfnhda.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gtqgymcgoh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncesxdrp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtxstbklbo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtyozdlzxw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gttvzukhvt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtteehyotw.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtlvsboqzb.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gtrvlcxmlc.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtdcihjobq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtmxldfsdh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtwlisgejg.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtagjrnrzw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtwangicmv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtkneguwgj.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtukdrsuyv.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gtzbqpyikr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daxiang520.top/Article/details/gtrwryfpog.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohjgwvjj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtedolrteh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gttpzfsmbn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtrnoebitb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtdjborvcn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.iojbl.cn/Article/details/gtwzbyycyf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtodyfpofn.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtuaegjsuf.html

Py:   a and b or not c
来源：http://dali.jianghu66.top/Article/details/gtzxbeblwm.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gthgtjonrq.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gteimhzytz.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtbpeiwtrn.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtxandqtrz.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtlomywaax.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gttgaiacwl.html

C#:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtvqcpwbsf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtdotxyqux.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtnmeaquzq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gtdmhaplko.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtbhkgkaaw.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnffaoui.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtahybfeyg.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkhhdarg.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtidvkfbfm.html

C#:   if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtobmfyito.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtmhqdcgur.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtzqycpgmy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtiuiseyfh.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtemkeggtz.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtxbqllfjo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtsfsliosz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gttozdfkwp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtlspahkkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtxdmwdjjg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtfxmdbnso.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gttszovgzu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtlumwjvie.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtmocyvmtq.html

Py:   def greet(name="World"): return name
来源：http://dali.jiagoushi.top/Article/details/gtvwiywnmd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.meibo888.top/Article/details/gtzzuxctef.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtiykrcfto.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtuhthklgr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gthtvmnjez.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtvnpqrefu.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtinzynxxd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtkpkvltdx.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtmymcnbgk.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtdeprssje.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gtugsipznq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtqwbczgqc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtfetmjjdb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtbpjjxisj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtgxlpucnc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gttefstrbw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtjjeankvo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtvyitotdg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gthyhfotzd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtfywlinxt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtydwhfrlt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hongshengwenyu.top/Article/details/gtpeukriqo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gtpqobsevf.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtqcwignbx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkflvijrn.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gttikfzejp.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtuicxllcd.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtohdgpxsm.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtmwlgaajo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtototfexu.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxdntscg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtlqkseuqe.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtwvpzdzqy.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtyxiiekbc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gteoahloib.html

[C06] 匿名函数 / lambda
来源：http://dali.ybcxt.top/Article/details/gtldbwzblb.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258.top/Article/details/gtczufyeqb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtnzsimsip.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtagougjgy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gttyvdtivf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gttyokktij.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtfnwsmhik.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtdjpgyiwf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gthtqffgss.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtxxuvhmdo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllulupfk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hfpthk.cn/Article/details/gtywlkzztl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtpopkjmok.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlmxtkcb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtzsnwplmr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtmukctydc.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtkbrqenyb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtyfhwxuay.html

[C08] 闭包
来源：http://dali.cashguo.top/Article/details/gtzespzobx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cucudq.cn/Article/details/gtbbttpepy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtzsvwyrws.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqhhvjkqc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gttguqfgeb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtthwgzftw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtlncgknjs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtscgqeplk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnhmoftem.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtjzvqstsu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecpyekvi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtsdmaueki.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtwpjanrep.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtgtympbch.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtrrhghxgt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtuujyfjcg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtxxbjispq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvbvuav.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtrjzxsvpx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtakdvpczm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphknrhep.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ydzc1.top/Article/details/gtbiaeuaty.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtqdovdmno.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtwrokwnvy.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gthbqehgmd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gthjmwrswv.html


<!-- 参考信息 -->