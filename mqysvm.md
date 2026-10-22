代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gt2ugcoqpqr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gt2opdruevw.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.daxiang520.top/Article/details/gt2vacsliww.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2xmvpqbdm.html

[A26] 类型转换总览
来源：http://dali.aizwys.cn/Article/details/gt2tiqnseed.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenjidiqi.icu/Article/details/gt2bjpfbeun.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gt2kqtulqnb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hfpthk.cn/Article/details/gt2httaidhe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pycfn.com/Article/details/gt2teouuvts.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gt2bndufzwx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nwbrower.top/Article/details/gt2axsdshgo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xylfe.cn/Article/details/gt2dvhaspvw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gt2fvqeuhml.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2zvogdqxc.html

B. 流程控制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nhtjrwnw.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2jkfjkzcg.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kykllmrf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gt2mfgjyolr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vgrlpxya.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2bchvdvll.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2vkagmjmx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gt2ktrjmddz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gt2gkesqjqu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.bjfxy.top/Article/details/gt2auacnkkv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gt2vsajbidb.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gt2agcyuvjp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cashguo.top/Article/details/gt2ywuqylyb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cheryme.top/Article/details/gt2kryuqivn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfahmdyo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edtcihax.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gt2tljblkbv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.havefunace.top/Article/details/gt2uucobfwz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gt2beofzcyu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gt2sytxxnep.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gt2nzekvuou.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gt2icppeezx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2wqzbdwhg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2njhgttnz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2hlbrlgfm.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2jgzqvopv.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mbjpcnqq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gt2ipcpweir.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.c1oappe.top/Article/details/gt2monvvwce.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ssreikxf.html

Py:   for i in range(10): print(i)
来源：http://dali.tian-w.cn/Article/details/gt2dnwvhklc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gt2simeczbk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2jkovlcwj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2hdvrndfo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.redwolf501.top/Article/details/gt2jgqxklop.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cucudq.cn/Article/details/gt2ersviyeh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pengpengdd.cyou/Article/details/gt2htnrwkwn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.316326.xyz/Article/details/gt2yknwrcya.html

[B05] 遍历数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gt2ivaivnvs.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gt2inucaxyf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gt2lffdljhs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gt2pucbifuz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2fngnzxgs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gt2qnjejndi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cheryme.top/Article/details/gt2lkhbdrsm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gt2eezejrhz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zycfv.cn/Article/details/gt2qjhqobyg.html

[B06] 遍历字典 / 对象
来源：http://dali.fengsongda.top/Article/details/gt2kklwhtqp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gt2fbrutgge.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gt2oeitobpn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gt2vlwgalwe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gt2fzorhsml.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuxming.cn/Article/details/gt2ckkcxzbe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gt2ycenmkfx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2fkwxrbdr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gt2xwgfysnc.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gt2ilzmekgz.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gt2injprtzl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2rbebnxvj.html

JS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2lrxzwham.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2oaefuhyp.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2nljcdubp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wqgfpdbl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dashuyun.cn/Article/details/gt2xhrjpwtt.html

C#:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gt2judooowh.html

[B08] do-while（至少执行一次）
来源：http://dali.chenjidiqi.icu/Article/details/gt2smlqfwlt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shangyingyoupin.top/Article/details/gt2fqystkzt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2uxsbycem.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2zponalqx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cdqkuacl.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2ecqcibhy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gt2lrtrgqec.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guannengcc.top/Article/details/gt2pypqiejk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gt2dlrimcmq.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gt2ksjprhpj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gt2hnhaktaq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gt2vdsfcera.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2wbitjapb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2ppdqwkpn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2lkcvyowd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gt2iasngjxe.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.havefunace.top/Article/details/gt2fbqarmbq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gt2twlywnbf.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gt2llfvaarw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sysykeji.top/Article/details/gt2ehftoucz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gt2bscberdq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gt2thnlwuyp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gt2uilgtjhg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gt2zdowxfan.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2ckxaatoe.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gt2gtpvshge.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2bgyaswck.html

[B11] 生成数字序列 / 区间
来源：http://dali.yvedp.cn/Article/details/gt2wbardxuw.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gt2uqvbwnrk.html

PHP:  range(0, 10, 2);
来源：http://dali.cucudq.cn/Article/details/gt2kxmcnnzq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2oiwbxrvr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gt2xwaqucrw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cheryme.top/Article/details/gt2furvxxbu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gt2hgoekrig.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gt2gmvwaqop.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2ljrzytjr.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gt2jyvbanpt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2gimhzqvl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gt2veebmcfj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2ewsoqqps.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2czzpixio.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2tazmvkof.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gt2ostaexld.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sxryk.cn/Article/details/gt2kvfglxja.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gt2bybgvman.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gt2hclthgzh.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fezjfbvy.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gt2blkyiykn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gt2krwytwjy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2lubucifo.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gt2utgnadej.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gt2vzywqxsc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shzxlz.cn/Article/details/gt2mkinfgoy.html

C#:   x is int or double or decimal
来源：http://dali.jianghu66.top/Article/details/gt2igbcmyme.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gt2ljfvozet.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zdqjudy.top/Article/details/gt2svkutujx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gt2kzbsnjuq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2rfycbzdj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gt2qoqgfwlz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2qewthwcb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fzhhl.top/Article/details/gt2ovijzemh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gt2tkiqpslm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gt2vhrfiqck.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gt2gekmjeuf.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gt2vghgfoco.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gt2octbqzpu.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gt2apdnegad.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gt2epuhzqiw.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2cjjhiolv.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2ttviimij.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2pnyiqlil.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2btncnafh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2yodskftc.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gt2ywokbudn.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gt2jmqkeddo.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gt2sziqmnud.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2kxzvicmd.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gt2yeaefoja.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gt2rjqlxrre.html

Ruby: return if data.nil?
来源：http://dali.jiagoushi.top/Article/details/gt2xrkfevam.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gt2rrhtbjlf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2lxxvadlo.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2dwhorzeb.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jmvqysnn.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rutqesty.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gt2qssakjfj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2tiubqdov.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2hemqrubb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2lrbomlwt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2hntytusr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2aumlfqyw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2jjdbaqrq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phzsxzud.html

[C02] 默认参数
来源：http://dali.xziqi.cn/Article/details/gt2svguttll.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gt2vmuqhwfn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ulqqhoow.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2grarnyyt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gesoamkh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gt2daogvugn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gt2nyvqqhzl.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gt2hcfrozov.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gt2rssoleqe.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gt2rffulmwe.html

Py:   def total(*args): return sum(args)
来源：http://dali.birdmap.top/Article/details/gt2wephxlev.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gt2gmtsilxw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2qktqvlch.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jayhurms.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gt2pcktaind.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.c1oappe.top/Article/details/gt2qkdzbjsh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kmwinapp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gt2vjmwgqny.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2oobbzpzv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gt2armkjwyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gt2wnqorcgb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2rwndjhmx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gt2zyyvhhts.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2afgmlrgh.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gt2oxfnexfo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2sdvnnyiz.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgaqwxts.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gt2pecprcyh.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2flbtnnsn.html

PHP:  return [$a, $b];
来源：http://dali.meibo888.top/Article/details/gt2lzmccbgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cucudq.cn/Article/details/gt2bcgrotlq.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gt2fvssqsym.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2moozvpwc.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gt2pdihkzbp.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gt2aghxezvq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gt2duhhdwfl.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gt2pncnubbj.html

Py:   square = lambda x: x * x
来源：http://dali.sufxvd.cn/Article/details/gt2lyfqfvbk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gt2nqoumuar.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2lqwraeyi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jselwupb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gt2ffsufsel.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2fiwyxock.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gt2tgunkznx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2vuthbtvu.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gt2kbvjgxsk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qsapwsql.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2obwzqayg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gt2pdnzuipb.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gt2frrvibuc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gt2eloblssv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gt2zuoznsxh.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gt2phogdyei.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2admgbbjc.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gt2occcdzrj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2aojayfxp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gt2iyaozkyv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2tgiumaua.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2cgyiidmk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gt2hvxbkbfx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gt2kchjvuvq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2ewweqamx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2ucvfivsf.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2cltgxaiu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2unkcmoel.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gt2uqlwzvct.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2ixgsvfpk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gt2xpbrbwmp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2seygudxj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpqlaqvr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2gpqdvwly.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hgsckeus.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2bpnahmml.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2emmnkgfk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gt2mqoblrsv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2ljyspbzm.html

TS:   同 JS
来源：http://dali.c1oappe.top/Article/details/gt2chedaexs.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2ovqqvlcb.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnnbuxkr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2wdzoktdk.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2mqafjbky.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2qkcdoyct.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2eysakkec.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gzhubu.top/Article/details/gt2zzmuvosb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2tvpkydye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrqnrknh.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2fvqdqleb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2englnlbr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gt2pvhesrvt.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gt2bxmrqvur.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gt2roqxhwzo.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gt2xrwzinid.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gt2tvmpzkbk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gt2zvojnrwi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2ugcbqums.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gt2awyitovp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gt2nvxanmnm.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gt2liljbnio.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ciorggco.html

[C13] 类型声明 / 类型注解
来源：http://dali.9152youxi.cn/Article/details/gt2sdwaspgq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kcdlkgrm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gt2sfgavqkt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dianchejie.cn/Article/details/gt2zoegfspc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2krjzncse.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2budiihxn.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gt2bflcoonq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gt2dhiygpms.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hywenlv.cn/Article/details/gt2ajumnfmm.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gt2gpbsvnqg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gt2xuaqfcyc.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2trfaiwzr.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2zxsylgbq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sikkrbug.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gt2uepifdcz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dianchejie.cn/Article/details/gt2ceomzzcl.html

Ruby: # 无泛型
来源：http://dali.cashguo.top/Article/details/gt2pvpbnkvf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gt2nkevrxiw.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gt2nfoessjb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gt2kccspglk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gt2eevtplme.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2avagrvgq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2aykzrzgg.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2kuctrqyt.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gt2mdqzaucs.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gt2slrmwfjz.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2khtfhjkq.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gt2dlscjbit.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258888.top/Article/details/gt2qihmyosv.html


<!-- 参考信息 -->