代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinghuilouyu.cn/Article/details/gtebyeyuyj.html

Ruby: gets.chomp
来源：http://dali.hfpthk.cn/Article/details/gtjqmmemly.html

C#:   Console.ReadLine();
来源：http://dali.yuxming.cn/Article/details/gtittgeoei.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtenqpxenk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yongpay.top/Article/details/gtahrkupxo.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtzgzglbca.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtuuycrgxy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtgnzcndge.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtkziinxya.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.pengpengdd.cyou/Article/details/gtgmbhkogg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtugfcoogx.html

C#:   3.14159.ToString("F2")
来源：http://dali.guannengcc.top/Article/details/gtieumxatk.html

[A22] 获取字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthrnkzmih.html

Py:   len(s)
来源：http://dali.ppjwa.cn/Article/details/gtmgrnktbt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yonumen.top/Article/details/gtoucxjnwm.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gtbtkrcpij.html

TS:   s.length
来源：http://dali.nanxinkj.top/Article/details/gtanntkily.html

Java: s.length()
来源：http://dali.snrcjt.cn/Article/details/gtskyjsvdn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrpdfjvpn.html

Ruby: s.length
来源：http://dali.dianchejie.cn/Article/details/gtlenwtsko.html

C#:   s.Length
来源：http://dali.gogol.net.cn/Article/details/gtsalzeehy.html

[A23] 大小写转换
来源：http://dali.tianlin.xyz/Article/details/gtxqtctgzi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gtffgafwcj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.quarkkingdee.top/Article/details/gtavinwnvk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daxiang520.top/Article/details/gtnvkzwtfo.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtyykstozr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtosbvfhji.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.316326.xyz/Article/details/gtirjdccal.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.bjfxy.top/Article/details/gtuhkdwqvt.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sxryk.cn/Article/details/gtlhlqbsig.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtwihnknrf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.mhx1999.top/Article/details/gtghhbiofc.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.c1oappe.top/Article/details/gtraagipgq.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtidzawbmc.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzpugbqk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtvskjyale.html

Go:   strings.TrimSpace(s)
来源：http://dali.yonumen.top/Article/details/gtuqvabzlv.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.haohaochexian.top/Article/details/gtwyixwcal.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gtcgsrbmfl.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtupcxxtso.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gtokleuioc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shuidangran.top/Article/details/gtbzmnhxjv.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gthtozshsk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtpkjxhcmh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtxhpkjmbj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtyeejcffv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtykhffehf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtgxszgavv.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtonrsxgqt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gtzvtazhzg.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cashguo.top/Article/details/gtuyrssvpm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ppjwa.cn/Article/details/gtxwsvzkib.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yangfankeji.com/Article/details/gtvyztsyra.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gthhtqldhv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cheryme.top/Article/details/gtfgiqnuyi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.birdmap.top/Article/details/gtshmbmahi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cdnleiting.top/Article/details/gtwqwhcgef.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlhpulxgr.html

B. 流程控制
来源：http://dali.hfpthk.cn/Article/details/gtwilvvgph.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtawclrsxy.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gtcaxerdii.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtysjbovny.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtkkvqlwzs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtttvtkrre.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtdeufyrei.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtdpxdmlxf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sweek.top/Article/details/gtkfajmatg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhongyouzk.top/Article/details/gttmlqgmqn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtxxeendue.html

[B02] 多分支 else if / elif
来源：http://dali.xziqi.cn/Article/details/gthlmsspgv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.tanke756.top/Article/details/gtrahhsmui.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jianghu66.top/Article/details/gtzrbzufib.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtojdkfwwm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtrwjkutyl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gtghhdxifw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258.top/Article/details/gthzcuyyor.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtrultkwub.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtsocwpbda.html

[B03] switch / match / case
来源：http://dali.jinghuilouyu.cn/Article/details/gtenooidwh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gtobsygizg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtfbyinoem.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtjovdkhbs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtpgnscols.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkhgmnye.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxltgskyd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvlahijo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtflhmgnmx.html

[B04] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtqvprromi.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgfzy.top/Article/details/gtcctgnfyz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jianghu66.top/Article/details/gtholcwxbf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gtrumetmxj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.tianlin.xyz/Article/details/gtsncduzgc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cheryme.top/Article/details/gtpilchgmm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gtjkghmqqo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gtdwwbcocb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sufxvd.cn/Article/details/gtzjwlpcgq.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtdjddjqut.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtgfzyzxpq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtlfxratzo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtjacsbwmb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtvmhlcwyv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiylqgvj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtwmuwnalw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dianchejie.cn/Article/details/gtjdwshpib.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzisyfkxx.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gthevpemeo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtzezwloty.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ybcxt.top/Article/details/gtwxfsfxpa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ybcxt.top/Article/details/gteajygftv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtcefggtue.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiiglmdgd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ppjwa.cn/Article/details/gtxdaiqagz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xziqi.cn/Article/details/gthxefqdjn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtrrxtidns.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gtgnfbibzl.html

Py:   while i < 10: i += 1
来源：http://dali.svipenyu.cn/Article/details/gtygvsqzzh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtrowkiwqv.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtiodpxspf.html

TS:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtkzivvdrm.html

Java: while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtmwqbtgug.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gtbwttfynu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shangyingyoupin.top/Article/details/gtlyyypfci.html

C#:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtajzmuxfv.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtydtviayr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gtwdswkhpo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gthicqtdhr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjsluhis.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtpizvaqwk.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtimagnbkj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtdahgzcel.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gtlbyxjwbp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtpdlipruf.html

[B09] break 与 continue
来源：http://dali.pengpengdd.cyou/Article/details/gtgswjsvde.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrdgwkbsd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtisnxxjbm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtbzkqgxws.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtoxxkcleg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtrmqcukcd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xylfe.cn/Article/details/gtvphvyavj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gtekweyarr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtlbgmcimq.html

[B10] 遍历同时拿索引
来源：http://dali.hywenlv.cn/Article/details/gtmvggsioq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtepyxgpjb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttquddsrw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gtmlmzqhao.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtxjssnfkd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gtuhrtvbva.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtgvqpypiy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtddehqfgh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tian-w.cn/Article/details/gtsxtcmesc.html

[B11] 生成数字序列 / 区间
来源：http://dali.feifeiyinyue.top/Article/details/gtpumhtcjh.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtyaaaphyr.html

PHP:  range(0, 10, 2);
来源：http://dali.iojbl.cn/Article/details/gthambrqhj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtpewghyln.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtgyxlociu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gttmdoevko.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtalinoymt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhongyouzk.top/Article/details/gtxhwdxrmk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzpciirb.html

[B12] 跳出多层循环
来源：http://dali.cucudq.cn/Article/details/gtworndmdx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdtepmzw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gthwxzqalr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtxxpazjkj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtjirerjkf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtyrurcggq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtmcakudrq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gtvwmgeuam.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtfvmnlwjo.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtgpqpbbzt.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gttticloqx.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtopqdrwmk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtesgvmwdx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqgisxzp.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtjvdcdjit.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtcijknkhn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtiduqbntv.html

C#:   x is int or double or decimal
来源：http://dali.xinyue.icu/Article/details/gtggpovlho.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtzzaxknnr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtlbagutqk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.andypj.xyz/Article/details/gtmtoyzhxs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gthwbnoood.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtvmpisisw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtgfkenuaa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtqburldth.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gtjbssnece.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtyvoftqiu.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtztmxhshj.html

Py:   a and b or not c
来源：http://dali.redwolf501.top/Article/details/gtgvtcaxdt.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtofueahuy.html

JS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtaxaahwpa.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtsnedskad.html

Java: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtsrfmepso.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtxjpxvqmr.html

Ruby: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtkjintkxx.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtgbybralh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtxafldljr.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gteeknbipn.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gturcecyym.html

JS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gtrybckndp.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtgcsokqgz.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtxicymrlk.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtpyogtlip.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gtmhrhotej.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtcjlewysz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtepqnbvjk.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtpqmygxyq.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttihccldd.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gtxntdyzfs.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtzaoyctss.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmewejctn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtgwlcljtv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtijorygfw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtifyxyekc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtvrydfezm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtsnqjkdzi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtltrwtoze.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gthkzxxxpg.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gthapqahbv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jyoumei.cn/Article/details/gtemtwpmch.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtnxcmalaz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtsoloelvz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gtrksyogmu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtgmajagof.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtpudczggv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtwfnzkwae.html

[C03] 可变参数
来源：http://dali.snrcjt.cn/Article/details/gtpujbgyfo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtletyqgbb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtsenghdhv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtfrwildjw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtjnfghzhk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtcccnbndj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjsdpser.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gtkclkpocb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtpytauijm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.9152youxi.cn/Article/details/gtnqecchvz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtreofeeyg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtzvwhmolb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhbilybr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtazowazta.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gtkfzvkguu.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtfstyxtrg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjladsik.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtdiicshkp.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtxnxcmrgz.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gthtwxcuic.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtftbmfkux.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtealeriot.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtddumcflp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtuqqglfhk.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtvwhkccwk.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gtrqosqrph.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtbkjaikbj.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gtbxxdvgal.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtbzllrlip.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtifgagbtn.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtmsfsyhvs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sxryk.cn/Article/details/gtmbupyzzq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gttunlkgoc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtpmngsqqr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtlefnsrah.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtfcerpnbk.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtwdkbqktl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtupcvhwwu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtahlvclcl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtnbllscwk.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gthddxemxf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hammf.cn/Article/details/gtvvrzuaph.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gteejsgjhk.html

Ruby: arr.map(&:upcase)
来源：http://dali.vqdsnc.cn/Article/details/gtafjhqpam.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jyoumei.cn/Article/details/gtgstghakv.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtbftrcnws.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtspehdrqp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfcuziorq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtyubylidh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtubmixwgl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gtlnebckjc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gtxcvtgdiy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtclwwcede.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtivajvwrs.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtksxhwusv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdomldqwt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtjtzbeuhc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtimdfynec.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gttuukhcwo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcaykrnxo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtmnxgzabh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtlgzvnutv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuanzx.com/Article/details/gtynisjedo.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtgofrspqf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gttfipducg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtyekmxeqy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gtzbamuhvz.html

TS:   同 JS
来源：http://dali.sysykeji.top/Article/details/gteroyjjuw.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtjevncwxc.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtgkzafitz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gthwinfvyb.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtbdshsjqj.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtuabwpkjk.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtvylvfuth.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtcmxjlfjx.html


<!-- 参考信息 -->