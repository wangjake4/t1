代发 wailian999

Py:   f"{3.14159:.2f}"
来源：http://dali.cqqwz.cn/Article/details/gt2skkqjpik.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gt2rgtqosct.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yongpay.top/Article/details/gt2sdogkwky.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gt2xjvueipo.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.wangdashe.top/Article/details/gt2mmizeuvm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.sxryk.cn/Article/details/gt2crobphqi.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gt2xrxcqbmm.html

C#:   3.14159.ToString("F2")
来源：http://dali.kuanghao11.cn/Article/details/gt2jqkidrtf.html

[A22] 获取字符串长度
来源：http://dali.jiagoushi.top/Article/details/gt2fgfrzggp.html

Py:   len(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2hkxslzrg.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ydzc1.top/Article/details/gt2owdtesdi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hchhfqfq.html

TS:   s.length
来源：http://dali.yj20258888.top/Article/details/gt2xlyzxxvg.html

Java: s.length()
来源：http://dali.ppjwa.cn/Article/details/gt2suycczwc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yofnrvif.html

Ruby: s.length
来源：http://dali.ydzc1.top/Article/details/gt2hhqnlonv.html

C#:   s.Length
来源：http://dali.yueranfly.top/Article/details/gt2pqgsycap.html

[A23] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gt2hbggjvfb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daria6918.cn/Article/details/gt2girrhxlw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tian-w.cn/Article/details/gt2ehppison.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2gwvacpea.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nwbrower.top/Article/details/gt2pcllumzy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.sysykeji.top/Article/details/gt2ykgtaddd.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gotoacloud.top/Article/details/gt2kzixsfig.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gt2zwvwigmw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gt2pouqjllf.html

[A24] 去除首尾空白
来源：http://dali.zhengqikj.top/Article/details/gt2frnvlyhb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.fengsongda.top/Article/details/gt2qxsymrle.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.aizwys.cn/Article/details/gt2uuzbtdyx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lpghlqzr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gt2gonejxkz.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cdnleiting.top/Article/details/gt2gvaovlzo.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gt2twnvtaed.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.aibaodan.cn/Article/details/gt2nrvevzre.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.smart0.xyz/Article/details/gt2aexcijxi.html

[A25] 字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2glkoaike.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yonumen.top/Article/details/gt2wemdwuzv.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.0kj1m.cn/Article/details/gt2wqmrkxgg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmksnish.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cashguo.top/Article/details/gt2kalllaop.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gt2xevezoqj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.pycfn.com/Article/details/gt2ciytixlt.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guowangkeji.top/Article/details/gt2eomhoabt.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2kaoacbay.html

[A26] 类型转换总览
来源：http://dali.ydzc1.top/Article/details/gt2bilnddpt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zdqjudy.top/Article/details/gt2vecbsbde.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gt2djltbntn.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xziqi.cn/Article/details/gt2qxnblhmu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jqgfzy.top/Article/details/gt2lqnopmuy.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2hrxehbqt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj202588.top/Article/details/gt2uuujtjib.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gt2djrjrtfe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2hoimrrej.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2mwpdamoo.html

B. 流程控制
来源：http://dali.zhengqikj.top/Article/details/gt2ncsxgfpu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2provzlsf.html

[B01] 条件判断 if / else
来源：http://dali.meibo888.top/Article/details/gt2uttjufiv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.0kj1m.cn/Article/details/gt2qphjlwtn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tian-w.cn/Article/details/gt2jyufvhim.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2ewaddgks.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2lkygqyue.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.havefunace.top/Article/details/gt2ogngabvo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fbrebwna.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258.top/Article/details/gt2qjksekhy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2mdfhrvoo.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gt2bknjnwhb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gt2ciywatsl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2iqkgujld.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gt2wmmdjoxv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gt2mwkgzbre.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2wsjylbfk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xinyue.icu/Article/details/gt2zsdirgsg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gt2flpfkdbx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2xjaiubck.html

[B03] switch / match / case
来源：http://dali.yvedp.cn/Article/details/gt2iagvymuk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yvedp.cn/Article/details/gt2jrhzzcow.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.pycfn.com/Article/details/gt2iixuoiqn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gt2yzqrxrmg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2jvkxukta.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gt2yffesuau.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pycfn.com/Article/details/gt2ezvlpsrk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.birdmap.top/Article/details/gt2adfuqgrm.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2qkxlzgxf.html

[B04] for 计数循环
来源：http://dali.zdqjudy.top/Article/details/gt2utkqizob.html

Py:   for i in range(10): print(i)
来源：http://dali.ppjwa.cn/Article/details/gt2kptfcjrl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ydzc1.top/Article/details/gt2nnvyhykp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gt2dhwzgauj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ydzc1.top/Article/details/gt2qgpyodet.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2umxiqfkl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gt2rlynrqit.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cucudq.cn/Article/details/gt2raixcezb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gt2okgrcqyk.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nalrlalf.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gt2fdwyanhy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gt2gwqfkatl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jiagoushi.top/Article/details/gt2cevfmfoz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gt2qklsping.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.iojbl.cn/Article/details/gt2dfbmeyjf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gt2xxkkalom.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gt2ixtjvdbq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gt2jpdnejie.html

[B06] 遍历字典 / 对象
来源：http://dali.ehwqpu.com/Article/details/gt2wmprtvwo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gt2wglhnouq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xerqakko.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kchowgeo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gt2idnkifob.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigfzy.top/Article/details/gt2ejazxzru.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gt2isqmjwmo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yanxiufei.cn/Article/details/gt2gjlnrgxt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gt2pffefmzg.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gt2btgptemc.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gt2mlutqvmu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2ankobqcr.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjzoennb.html

TS:   while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gt2omzcbzaj.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2yoltezpt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yvedp.cn/Article/details/gt2onocxsnn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ivvv.top/Article/details/gt2xsfzvawq.html

C#:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2hmubjrme.html

[B08] do-while（至少执行一次）
来源：http://dali.yueranfly.top/Article/details/gt2zsndfwbm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gt2knrcnrnj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2legwalrf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2wmqgsruu.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2nrjldccr.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2dvgmluuf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.aibaodan.cn/Article/details/gt2anhykqrz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwzahyex.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gt2kkleyedy.html

[B09] break 与 continue
来源：http://dali.jlsjyb.cn/Article/details/gt2mnfmlltw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gt2kywparoi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2cbzmqstp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2wfdefybp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2gvbjkdib.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gt2cpxggtzd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohooquwe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dashuyun.cn/Article/details/gt2uejdmrrl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2jjxjowya.html

[B10] 遍历同时拿索引
来源：http://dali.jqgfzy.top/Article/details/gt2blxnkjrn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gt2dqmhctme.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gt2plnooqtf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gt2bkfqwhyq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gt2emshpigf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qirvcomv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gt2qlofopgs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gt2ddparoqy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gt2orjohpjp.html

[B11] 生成数字序列 / 区间
来源：http://dali.jianghu66.top/Article/details/gt2mifoshvc.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gt2rgwelysf.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqnhpfxj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gt2sadrumxb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2ilieyufq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vowwvjda.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gt2yfeijhbt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gt2pgnfhnvw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gt2aqwpzrzp.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lhcaeizn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gt2lbbeiskv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gt2hhtywyyf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gt2fzhblmjj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2rzjmxwbu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2vppnetck.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sufxvd.cn/Article/details/gt2lvzwkzwz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gt2cjfnntgt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gt2trwnmigq.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gt2rdvfntqe.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gt2lentxiai.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gt2whqwhoui.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gt2zdwxamfk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gt2jgfqhywp.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gt2ppdzmjgx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gt2fygoqtzm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gt2qfbrvgch.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gt2nynkocoi.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gt2bvaantsd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ingfywsx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dianchejie.cn/Article/details/gt2ucouqtvp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2sehkepdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vaqmawfx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgtvsjz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gt2xzzzixkv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2vgccibey.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrpsedp.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gt2oembtcvr.html

Py:   a and b or not c
来源：http://dali.guannengcc.top/Article/details/gt2dlefdmss.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gt2pxcmlkkp.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2hrbsioii.html

TS:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2vrwaqmyc.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2xgflieis.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2gracswln.html

Ruby: a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2iwtvdslb.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2qktprthc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gt2kozzshes.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2oxmopkzf.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gt2erzlwwii.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gt2tdfuqywi.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2mgwxunxk.html

Java: if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gt2qzeiwdel.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2hlilnlin.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gt2tkhzucio.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2ielbyvwe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2jisiyjmj.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gt2pottmczz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2cfxpvmfa.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gt2dlembfml.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gt2zmkawyek.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2gyftasxe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2xzfsnkuj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2dfhizgwa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2hvqmbfuv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2yfmzdgal.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrblgqj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2vgoltkrk.html

[C02] 默认参数
来源：http://dali.hywenlv.cn/Article/details/gt2hsapqnsj.html

Py:   def greet(name="World"): return name
来源：http://dali.yvedp.cn/Article/details/gt2wlnelynt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gt2eontkven.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qcktqzcj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gt2mdheubmm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gt2jlgcnemu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gt2iwmewrkb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrhxvqdv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gt2vqhighnc.html

[C03] 可变参数
来源：http://dali.yj20258888.top/Article/details/gt2okbppepi.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gt2gunwsyfn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2fbrmzmlf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2xpetbngc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2czaeazpv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edtlstxh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gt2fcjiatyp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gt2eusguroy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2fcocybfe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2kflamzla.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gt2lstksezw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2lsnkbybf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gt2qjiwihka.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2draxildn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2vshtdtvc.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gt2igovmmnc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gt2vzvrsvqw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2togffbwi.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gt2cficopmv.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2rwvckmrx.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gt2eteuybxz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2fmylzshl.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmzeyibb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gt2urbvctqy.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2embobvyk.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gt2fzdzfonw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tianlin.xyz/Article/details/gt2vuxntvdm.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gt2vmuqowqz.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2kpqkhxfy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2nzspwzvt.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gt2amlhjqsv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2scrqtggk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gt2uhcjyyzl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cbrwgjkl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2birizdyx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2tbntwbur.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gt2fdokjpwn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gt2qexobpgd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pycfn.com/Article/details/gt2astubjrq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gt2ghknlutn.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gt2xxvkryro.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gt2xdbqoars.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2zlenrmew.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqhpkbof.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2fkhffhye.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2dcdkjugp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2kjpuruad.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2pmnlajio.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2ldgzngxf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2uhsulwsu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gt2rexeenzu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2vihrlbjx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vsidqcva.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xldkmfvj.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gt2gwjkbbqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gt2bmynrtem.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2kcfzvsue.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2ilqhefcr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gt2wfpysapd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2bvmfqzhx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xknhowyj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2gnljkqtg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cqqwz.cn/Article/details/gt2hbjhturm.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2qiyuykko.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gt2yalqfodq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gt2gjrmfazc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlxvxzd.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gt2sgiootym.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2oxxyceil.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2dnaznntl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gt2wwrdcjbm.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2pnpvyasz.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gt2sdlgymzv.html

Py:   from module import func
来源：http://dali.tanke756.top/Article/details/gt2cfjmmuif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gt2fpaelpqf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2hqmqdjaw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.andypj.xyz/Article/details/gt2zbzxucei.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2vrokydcc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gt2kpfxsjcv.html


<!-- 参考信息 -->