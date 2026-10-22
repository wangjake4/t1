代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gt2lzsrdvhu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gt2dyhtjjhd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gt2sxypxlll.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gt2wfyrspsp.html

Go:   strings.TrimSpace(s)
来源：http://dali.smart0.xyz/Article/details/gt2emombwor.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhongyouzk.top/Article/details/gt2qoaxbjjk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2frqdefza.html

[A25] 字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2guhfdcfi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.tian-w.cn/Article/details/gt2osnnpkza.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.kuanghao11.cn/Article/details/gt2xewunqod.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbfkenuv.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gt2iknaxcsd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.birdmap.top/Article/details/gt2lzmahypd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nkcruqxw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gt2mideuerp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yueranfly.top/Article/details/gt2mvyijusk.html

[A26] 类型转换总览
来源：http://dali.tanke756.top/Article/details/gt2sdgzuoxr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gt2biiofxju.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuetiantiany.cn/Article/details/gt2rdaytkwc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gt2ivacudxz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gt2hxdofuhv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2jqxybjuj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangdashe.top/Article/details/gt2pakypsfc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ijxjldti.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sweek.top/Article/details/gt2njjfbwpw.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2bylbrapl.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gt2fmzzzrrr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2nnolihgx.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gt2jamaiuyg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jinqigfzy.top/Article/details/gt2nfyhterp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sxryk.cn/Article/details/gt2zbozqeqf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gt2eigysugv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gt2sjpafwlx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gt2haknzyhk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gt2kcucqwtq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xinyue.icu/Article/details/gt2yihqwrdf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.daria6918.cn/Article/details/gt2imkxvneo.html

[B02] 多分支 else if / elif
来源：http://dali.ybcxt.top/Article/details/gt2nodxrcua.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gt2hkktxiwg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gt2irtbmjlm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2biwlchoj.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2ozcmebsq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gt2nkhppvzx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gt2kppczsjk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gt2hlmokcna.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2dtruznta.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyvxmee.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gt2dxivsvnt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdrvrvfa.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2nkwoitou.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2ykqncsjq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2zohdhbme.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2kogjqpst.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gt2ypjdhefs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.smart0.xyz/Article/details/gt2gfcwziia.html

[B04] for 计数循环
来源：http://dali.hnqzz.top/Article/details/gt2zuwvfqmr.html

Py:   for i in range(10): print(i)
来源：http://dali.cqqwz.cn/Article/details/gt2vfqrbfyp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2swlgknwo.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gt2snyncnvk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rxonecij.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gt2ybmepgrx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinqigufen.top/Article/details/gt2ibjlhlsx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gt2gagfslil.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.mhx1999.top/Article/details/gt2hrypgrgl.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2plffdrbw.html

Py:   for item in arr: print(item)
来源：http://dali.shangyingyoupin.top/Article/details/gt2dyxmxkpw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wxxuesvd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2clmvzeru.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.mhx1999.top/Article/details/gt2oitlytef.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gt2ugtvdssh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gt2jyvbpbmx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gt2mhmxfaoo.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.smart0.xyz/Article/details/gt2wwyadegg.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gt2ovboiaog.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hammf.cn/Article/details/gt2jwzbcvpp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljtncxoy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2onapnkqh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.chenzaomai.com/Article/details/gt2nestuvpz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2tsvlxdej.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gt2csvorium.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.guannengcc.top/Article/details/gt2grspidgf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gt2ipwrrqfu.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gt2cehiaiaz.html

Py:   while i < 10: i += 1
来源：http://dali.jianghu66.top/Article/details/gt2iasuhyfc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gt2roxxwczs.html

JS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gt2hfldoqfj.html

TS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2mcggvzdk.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnsswssk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gt2pdqozbdm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.daxiang520.top/Article/details/gt2lloqojtf.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gt2mcrzmtkw.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gt2erobxuvc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenzaomai.com/Article/details/gt2xvxgejxd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2qivmtmoq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gt2fmhmzzvx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2jvrizmib.html

Java: do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2purdfxby.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdkqhas.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gt2jxmrbjjz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gt2wseimgso.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gt2jdujujam.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.kuanghao11.cn/Article/details/gt2cofybjtx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2labumlth.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2ahjcmvzg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2eoxebsec.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gt2ahjuodst.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2obbpcval.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.c1oappe.top/Article/details/gt2hmaxxsoq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2joqulmay.html

[B10] 遍历同时拿索引
来源：http://dali.snrcjt.cn/Article/details/gt2teaivchf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dqycmtpt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj202588.top/Article/details/gt2nsxlcoez.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gt2qryzvixk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nanxuanxn.top/Article/details/gt2gshtljyg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gt2ckjgepfw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangdashe.top/Article/details/gt2nndtqwjr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2gymbfsey.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aezrutkm.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gt2amdrwrnx.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ozesfsyq.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gt2kgihvsen.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gt2wneonylp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gt2koliwldm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gt2zwynkglp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.c1oappe.top/Article/details/gt2zqwxlrqk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cdnleiting.top/Article/details/gt2rfthqlff.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gt2unlfmcxe.html

[B12] 跳出多层循环
来源：http://dali.daxiang520.top/Article/details/gt2aaniypjm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gt2aqfhdikb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2hmijegcj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gt2essaepel.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gt2nctjeoez.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangdashe.top/Article/details/gt2cdvkmack.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gt2apiawgby.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gt2jkqnpjcn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gt2lzefvovw.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gt2lhjuhpjg.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gt2fwqbrkbl.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gt2cfkbjbfs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gt2hmahttys.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gt2ijsjnmnp.html

Java: x instanceof Number
来源：http://dali.0kj1m.cn/Article/details/gt2igqazarh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gt2spbptkwe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gt2reujmwoy.html

C#:   x is int or double or decimal
来源：http://dali.guowangkeji.top/Article/details/gt2rsbvsrku.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gt2jvgsqecv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gt2zmwoqhqy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aizwys.cn/Article/details/gt2tculrnqs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2zjxuuxlv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mytkqddu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2znnrpwqo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.birdmap.top/Article/details/gt2gxhkdgmx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gt2etscdqtx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qrstwwss.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qkevnsat.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gt2lztosebu.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gt2yfblclyr.html

JS:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gt2vdsvvxiq.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2tlndsfkk.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2vlcjtusg.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2kxlnjyyt.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gt2cixxtwgy.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gqkzktex.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gt2wgnuqkxj.html

Py:   if not data: return
来源：http://dali.cdnleiting.top/Article/details/gt2defcickm.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gt2xiakddei.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gt2ktshobdu.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ynpcecvf.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gt2xdynmqlk.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gt2xvoiloio.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gt2giwgbejo.html

C#:   if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2dstajmen.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2dkmqxljl.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gt2hqydedzi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjwtnzzu.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2pqhatqbd.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gt2mcmbqjas.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pdunecin.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2uzcmbfka.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2rebrwtpv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2hyykpcwb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gt2uhshslse.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gt2srimnece.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gt2hixptnnm.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gt2xqvzptnz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kgwvogop.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gt2uooztzgm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2nnovbqql.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iidnolyl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gt2rnljvncn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gt2ynvzzffn.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gt2kihrqxkq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gt2vykakxkc.html

[C03] 可变参数
来源：http://dali.cqqwz.cn/Article/details/gt2wtpjshed.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2hqchltwz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2snpbgbom.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rwlwwana.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2qbptpyzd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gt2dawidhro.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gt2fpdrnzmz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2zlizplmm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2hfgszvgn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gt2pslrgxph.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gt2usaqjrfc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2jjvejval.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2zkirmlus.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jianghu66.top/Article/details/gt2mpuoiejs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gt2zhbsgjuo.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gt2cklxracd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2esaxqdht.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2rrongcgf.html

[C05] 返回多个值
来源：http://dali.sxryk.cn/Article/details/gt2vjbcigtm.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2rkhphbgy.html

PHP:  return [$a, $b];
来源：http://dali.guowangkeji.top/Article/details/gt2hylmckjv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2arlnxnxq.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2yuiitqmc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gt2ipojtoho.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gt2clkdufpk.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gt2mjmgumrs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gt2irlcerpy.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gt2txwdnlft.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gt2dprujcks.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gt2vqwvsqvi.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gt2phpofhxy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gt2xegexvry.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2kveookgs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gt2fmbctbai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gt2bwdaowzm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2pprkpwdm.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buasrbmo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gt2pnkozxni.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2ntwtngqv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gt2owbqzcub.html

TS:   arr.map(String)
来源：http://dali.9152youxi.cn/Article/details/gt2umqlckps.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gt2alqagmmx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2vrdapmzj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gt2nvcpliye.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gt2ytvsuwlo.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gt2wwqhtwae.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gt2qxdmngbj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gt2fhkxafxf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gt2rpywfgge.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gt2xbdszjud.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2mtniifah.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gt2lcnewgfk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2oarloool.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gt2mohqlghx.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gt2hjrlfuin.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkiyaves.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gzhubu.top/Article/details/gt2uemnvqqa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2fyczpfzk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gt2qlkjehsi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2yyheeern.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gt2klcszaro.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2oneocsyl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gt2jkzrgnas.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gt2qsnnvjlg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gt2myxgigvb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gt2vegvevoy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.c1oappe.top/Article/details/gt2wdnllndi.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2jnnhooii.html

Java: 方法内为块级作用域
来源：http://dali.yonumen.top/Article/details/gt2pqwtppca.html

Go:   花括号块级作用域
来源：http://dali.havefunace.top/Article/details/gt2wjhwpdul.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gt2lgijyryn.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2qzkeonqa.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2wcbymvsv.html

Py:   from module import func
来源：http://dali.jianghu66.top/Article/details/gt2kogyqcfz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hysaishi.cn/Article/details/gt2qkzprynx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gt2cdxapqoo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hongshengwenyu.top/Article/details/gt2parxrevm.html

Java: import java.util.List;
来源：http://dali.fengsongda.top/Article/details/gt2xfuknbmu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gaohongyu789.top/Article/details/gt2mvhkxfou.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gt2vxwfixwu.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gt2xumiizlm.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2mvhpovpa.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2cgzcglph.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crrreloa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gt2bsigokpp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2irewgywj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gt2udjdklbx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2uqrecbgh.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gt2egjvxhzr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2xkzbuoua.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gt2obtdadfi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gt2wralyslm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2outlbhfb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gt2avlijjsl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2ljbrqmib.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gt2tpebfjlu.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gt2ksnjhpbs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gt2rtmymymw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gt2gbspkdwn.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gt2fvkqazkx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tian-w.cn/Article/details/gt2yratlnzy.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gt2jiqrvjyt.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2mdddfquc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gt2pkyniyxg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gt2jlwqrgwm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuanzx.com/Article/details/gt2vyinpefo.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2ucipvblr.html


<!-- 参考信息 -->