代发 wailian999

[A22] 获取字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2hjgjtgpp.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hogttsua.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aibaodan.cn/Article/details/gt2ywwzjnma.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hfpthk.cn/Article/details/gt2jcbysjan.html

TS:   s.length
来源：http://dali.xylfe.cn/Article/details/gt2kojclomw.html

Java: s.length()
来源：http://dali.sysykeji.top/Article/details/gt2ryvvuprp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shuidangran.top/Article/details/gt2lhbpbmkx.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gt2rtiacgur.html

C#:   s.Length
来源：http://dali.yj202588.top/Article/details/gt2wfhyrcto.html

[A23] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gt2vihdwybo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gt2ihljfdzt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gt2ntsnppfv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gt2eeajksbn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258.top/Article/details/gt2swjnjfbv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gt2anuafyhr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenlongwang.top/Article/details/gt2ubotzylf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinqigufen.top/Article/details/gt2qzrvmcao.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gt2ttpvhvbo.html

[A24] 去除首尾空白
来源：http://dali.xinyue.icu/Article/details/gt2uscthuob.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gt2ddfgfjws.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gt2yxlovmdu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2qwtrhvkm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xuetiantiany.cn/Article/details/gt2znodvfbg.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.havefunace.top/Article/details/gt2qewfppsl.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gt2zcgvgkif.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shangyingyoupin.top/Article/details/gt2gbmklync.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dianchejie.cn/Article/details/gt2xnbwjanh.html

[A25] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgflcjut.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gt2swpfmgch.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gt2pfbzjckc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2loxdogcg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2vgvpxgko.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sweek.top/Article/details/gt2uoammuea.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnqzz.top/Article/details/gt2dbclqesb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gt2amcybsze.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gt2vmtnkizo.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gt2uthnjnsi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gt2ekkvikyf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gt2dosjuxaf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hongshengwenyu.top/Article/details/gt2fbxqcode.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhongyouzk.top/Article/details/gt2iqsojhqi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gt2tepcrexk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gt2uqeztkgt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.redwolf501.top/Article/details/gt2syaneody.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2fzxdkiag.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2rrrjmbeb.html

B. 流程控制
来源：http://dali.nanxuanxn.top/Article/details/gt2ivdumrmq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ovceacdb.html

[B01] 条件判断 if / else
来源：http://dali.daria6918.cn/Article/details/gt2pnhthdkn.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jlsjyb.cn/Article/details/gt2wmgdykuq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.haohaochexian.top/Article/details/gt2spglmmhp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigufen.top/Article/details/gt2cqxzgajw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2amufetfj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2ikifobea.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shzxlz.cn/Article/details/gt2pvrzbvty.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yangfankeji.com/Article/details/gt2rivodcah.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2boyqukux.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gt2ydtuujwb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenlongwang.top/Article/details/gt2rlvluvcf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.smart0.xyz/Article/details/gt2tnqgzfgl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gt2konhuqte.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2tyagunid.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2dpnrgxde.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jianghu66.top/Article/details/gt2strgwkkh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cheryme.top/Article/details/gt2crgczbhg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gt2sagdfodw.html

[B03] switch / match / case
来源：http://dali.yongpay.top/Article/details/gt2rfbznyve.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gt2smbudwdz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2ritbhzvc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2fwzipmoh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gt2zhneoaad.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gt2alasyjop.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sysykeji.top/Article/details/gt2sxrqhbyb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hnxiangtu.top/Article/details/gt2cyshwqlq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jiagoushi.top/Article/details/gt2fdjzunzj.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2xykhxslf.html

Py:   for i in range(10): print(i)
来源：http://dali.chenlongwang.top/Article/details/gt2ceqrpsjc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zcsoupyg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gt2jbgxfrib.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2hjuiyioi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yonumen.top/Article/details/gt2mogpvjgh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nwbrower.top/Article/details/gt2ictxpudv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zgtauxde.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cheryme.top/Article/details/gt2lqduqvyb.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2bwokkqns.html

Py:   for item in arr: print(item)
来源：http://dali.mhx1999.top/Article/details/gt2ptifwrtc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.havefunace.top/Article/details/gt2lksfhxpu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2yitzpcor.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gt2feuxzzos.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2rmnhlaxh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.meibo888.top/Article/details/gt2hgeyzxqc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gt2ybhekopt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xziqi.cn/Article/details/gt2jtgjjjwr.html

[B06] 遍历字典 / 对象
来源：http://dali.pycfn.com/Article/details/gt2uzpyocby.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gt2ibbosqqa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gt2gurinyqj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gt2mbqodgyl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gt2fjktmexq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwtupek.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sxryk.cn/Article/details/gt2vhchhpxj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ldxrcyls.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gt2pklyvflq.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gt2oomdcknq.html

Py:   while i < 10: i += 1
来源：http://dali.ehwqpu.com/Article/details/gt2ktdmjsgu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gt2qfhitnei.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mqcretvq.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gt2ziovossz.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2eeweqrpz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pengpengdd.cyou/Article/details/gt2shfnjzzt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.snrcjt.cn/Article/details/gt2zidbxepn.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gt2ltblrizy.html

[B08] do-while（至少执行一次）
来源：http://dali.vqdsnc.cn/Article/details/gt2qdogfeih.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigfzy.top/Article/details/gt2hfmxixer.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gt2wttodikb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2xtopmqaj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gt2dxbluoiu.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2sxxeuwlm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gt2lyrreifk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lweuzlud.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2rqiaszzt.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gt2vraqitij.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gt2hydfprby.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2zhcygjqc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2ulteinjd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gt2awdvznpt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2crwuiyrv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2qqsothov.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gt2amgveqhq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2yzdszfls.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gt2keevojfx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gt2jyqumvuc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gt2qlyqgxjs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2cymplunt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpxiztpo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ujypegpu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2sexuwncz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2vwbtiyis.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gt2regplukh.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2kejrnapp.html

Py:   list(range(0, 10, 2))
来源：http://dali.guowangkeji.top/Article/details/gt2txiccjpg.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gt2yrpczyvn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2hohlhkeb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iirsjsci.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jlsjyb.cn/Article/details/gt2zuaglapv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gt2xlqclirj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2ilrmsidd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gt2konqydkq.html

[B12] 跳出多层循环
来源：http://dali.tianlin.xyz/Article/details/gt2lttsvijt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jlsjyb.cn/Article/details/gt2lgfphcki.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuanzx.com/Article/details/gt2jvqzrnzf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2snbyvfik.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2gvntowdd.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2iyfcgeqk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gt2emqlvmaf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gt2ouxcedjm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2rfylxybu.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gt2mdmlawsc.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gt2prxpijlh.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gt2eeujdlet.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2iksxiwdj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2adccimba.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hqcrhaby.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gt2vybkrcvk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gt2fcubwvqw.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzjmeag.html

[B14] 判断值是否在集合内
来源：http://dali.cdnleiting.top/Article/details/gt2amixypjk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aizwys.cn/Article/details/gt2nyjhbdqb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zycfv.cn/Article/details/gt2gznbhrmk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gt2zbazltpn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2yobbghrn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2dwuphiei.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gt2bqmyrujw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2svwiksvi.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2nhqyqbcm.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gt2apxyjlev.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gt2jjkdwxua.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2sjpmwvvx.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2bmpqatxu.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gt2zcgekykf.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gysaoyom.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2jwtlkavr.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2dbnadmom.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2azrrizfm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gt2onkwnals.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gt2edcjqmlj.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gt2aayuckyf.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2rldiznat.html

TS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gt2qlinitoz.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2akjljlhc.html

Go:   if data == nil { return }
来源：http://dali.jiagoushi.top/Article/details/gt2jkfjrqhk.html

Ruby: return if data.nil?
来源：http://dali.zhongyouzk.top/Article/details/gt2zakohtwk.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gt2ptnynjjp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2nvlkavyb.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gt2vkwgtiev.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pgmdgeyo.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gt2lzfrvknz.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gt2wyesrewo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2yllopitj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2kidtbvsz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2wksrziss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2ugfcbbet.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2pytozfhb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gt2wfzyycdr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wornubtg.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vlnddodz.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gt2xhmtmazv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gt2uxrjsmjc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2ykhfkbdc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2eyrboigg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2iwwxaqji.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gt2kimoptfl.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gt2bgboxolf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gt2kxkhliga.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gt2obfuzxxn.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gt2jditzaax.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xmhbnseq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lhxjyiyd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2hvikkjqw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gt2ussuukbb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqfrnsnw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gt2tdxizuiz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gt2kagsniyq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gt2qpqddnwp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zdqjudy.top/Article/details/gt2mthcucfw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2ugzmcudp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2qtmqkyhn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gt2rakmadlw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guannengcc.top/Article/details/gt2boxekkmf.html

Go:   // 无：用配置结构体参数
来源：http://dali.yueranfly.top/Article/details/gt2bzmxdyhb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2hvibuvfb.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2pkmeghfg.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gt2hyghcyap.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2xmoxcamx.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gt2rosqxoce.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2cvtloows.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2gzcxevou.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daria6918.cn/Article/details/gt2cfvqdcah.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2vcimlcda.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2zktrsakr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gt2egftotai.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2arvthlph.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2jkkrqcqn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gt2vtefutnc.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2yisfiwjg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2jieyrlzy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2hxbexcyi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkccygzz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2rcklusmz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2wuptwffz.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gt2qkzqtdhk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlhpnkbt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guowangkeji.top/Article/details/gt2vbffhzzp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gt2rehfgcqc.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gt2cwwdnyrm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2ybejbwbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gt2afifmjuv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhaehsdb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2vithmwwu.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gt2iahzkpaq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cheryme.top/Article/details/gt2bayplvyy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emihlumv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2ndjhplxm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2zgaqdeyu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2szderlnp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gt2erxhsfya.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gt2rjrvudvb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2tzphmamp.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2zzencdok.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2yzswvyes.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gt2efdufczy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2sjfsdphr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gt2gzkqssmn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2msdqjbtj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2pdqpcxqs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2mjbwprou.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gt2bpmkgbvf.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gt2bddhzztc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gt2ztktyefs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gt2gnifmfvt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2skatvoob.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2qoledmon.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2szbinkrn.html

Go:   花括号块级作用域
来源：http://dali.hammf.cn/Article/details/gt2muatmnrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2fxwwvdun.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2jjihnqhh.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gt2fplikupf.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2wpyhsdpl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gt2cubqufab.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxpvuubd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yjdwqgry.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gt2jbwiqizj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gt2sipgigoe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2gvkkvgyu.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gt2bappyobd.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gt2jdduzwlh.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2igadsjyx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2bdbikghl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2abeizgno.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hfdvsomm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gt2lujqsjng.html


<!-- 参考信息 -->