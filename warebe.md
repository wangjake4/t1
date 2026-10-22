代发 wailian999

[A26] 类型转换总览
来源：http://dali.shuidangran.top/Article/details/gtweupqnyj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guannengcc.top/Article/details/gtdblkzseq.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tian-w.cn/Article/details/gtaejpqyid.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj20258.top/Article/details/gtlemelqkw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gteboojolp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gthsnjiuhk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtuaglidmw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sxryk.cn/Article/details/gtrpekgmah.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gtphgcdgyv.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtyaiivhvy.html

B. 流程控制
来源：http://dali.jinqigufen.top/Article/details/gtwnvmfzpe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfojjtgoj.html

[B01] 条件判断 if / else
来源：http://dali.cheryme.top/Article/details/gtotxqdyzo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daxiang520.top/Article/details/gteqvxkxmj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtzihzpkqy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtjfrbrbqw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgfnaxuj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gtgjfiwctt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtayrlepsy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxhlocszb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtyajykkkq.html

[B02] 多分支 else if / elif
来源：http://dali.chenjidiqi.icu/Article/details/gtewtsbdnh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnqzz.top/Article/details/gthdlqrmsp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ybcxt.top/Article/details/gtoyyyrgbv.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.havefunace.top/Article/details/gttmznxjfe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtakffejsn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtshgtqxgn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gtcnlxjcux.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhijiandao.cn/Article/details/gtnrphwfps.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtmtomsqla.html

[B03] switch / match / case
来源：http://dali.0kj1m.cn/Article/details/gtugebvdmt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cdnleiting.top/Article/details/gtvmqirzdu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtnhzxmhar.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtobbzkjus.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtxzseubck.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyvjqiqnn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtlspossjo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtmetwmrir.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gtcqsaklmu.html

[B04] for 计数循环
来源：http://dali.bjfxy.top/Article/details/gtodzxksot.html

Py:   for i in range(10): print(i)
来源：http://dali.chenzaomai.com/Article/details/gtjeumefse.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gtootjiskw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtwmjvooxg.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gtyowscgsk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtojoqicsf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhixingplan.top/Article/details/gtydlarjhk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtjdujyjrm.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sysykeji.top/Article/details/gtdqbfafec.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtzhiuhkcq.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtqlmjezvv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhijiandao.cn/Article/details/gtgivxleqh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtqncmhcua.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtgdhlcvym.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtrqxmhnkm.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.iojbl.cn/Article/details/gtostqswgz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gtrdzvvcqn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hfpthk.cn/Article/details/gtmkijfspe.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgfzy.top/Article/details/gtwgjfepiw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tianlin.xyz/Article/details/gtmzovghpc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.havefunace.top/Article/details/gtzzpjsrnw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtgxthwrkv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtdhonprhy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yangfankeji.com/Article/details/gtbznrpivj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gaohongyu789.top/Article/details/gtmnlworac.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gtsnejxsir.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwgjrxcz.html

[B07] while 循环
来源：http://dali.yj20258.top/Article/details/gturdgqbtw.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gtktdwkwgl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaoqyhfzh.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtcxytfuzw.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtfbmjondr.html

Java: while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gttrrrqwhv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tianlin.xyz/Article/details/gtfkbmgret.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nwbrower.top/Article/details/gtjcvviypp.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtdliwiaiz.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgufenzy.top/Article/details/gthnhspyma.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gtvlifrakm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ivvv.top/Article/details/gtricmzwth.html

JS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtfsdclill.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtajgchaoa.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtcrobdvlm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqpqpjtl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtdmsumggz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbgonrdt.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gtiblawriz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gttlufivfr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtiagajajv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtsahjjxep.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtaunfkvpv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtmbpddmrz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtvcktlfrw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhtrqlya.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtauyrvjez.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtufyohgmm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtqgtiujob.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hammf.cn/Article/details/gtsslzxhit.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtbjktxlya.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgckibcig.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gtqukdbkbv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tanke756.top/Article/details/gtcdifqjam.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yonumen.top/Article/details/gtfcyadzni.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtmzjxkrjd.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtkoboipwu.html

Py:   list(range(0, 10, 2))
来源：http://dali.ppjwa.cn/Article/details/gtqhfqdbbk.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgufenzy.top/Article/details/gtufjrgdxa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtglehleis.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtjqnpugcn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtelkfoups.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtivdjwajg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gtggqmmfxt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtfhmzygwh.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtmlamexdu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gthurmnpcn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtssfisxma.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtadvlkaya.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtwahmpqol.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gtqpgkephl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gteutsbvxb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtikfubava.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yongpay.top/Article/details/gttjycevqv.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gtauvvibof.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gtkdizhjjx.html

PHP:  is_numeric($x)
来源：http://dali.zhoulong.xyz/Article/details/gtvyfznzou.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ppjwa.cn/Article/details/gtfpvxksuw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtqjmlbkat.html

Java: x instanceof Number
来源：http://dali.svipenyu.cn/Article/details/gtiyvsvmes.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtaxsyogml.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzslhpxkq.html

C#:   x is int or double or decimal
来源：http://dali.yongpay.top/Article/details/gtotkafirh.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtmypwqvnv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtdutdyjby.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gtxspxzvra.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.9152youxi.cn/Article/details/gtyxrcpaha.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtfamrkxfh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtggyscajr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtwtoxlkah.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtcmqtvwco.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtkogqfizh.html

[B15] 布尔运算与取反
来源：http://dali.yanxiufei.cn/Article/details/gtvrsivhig.html

Py:   a and b or not c
来源：http://dali.birdmap.top/Article/details/gtbdccyhga.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtqcisvdna.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtdlgdmfse.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gteinitrpm.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gthydsyany.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gttjubonqm.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtivufxinv.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtktlqupcr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtgzgmgepy.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtsrvoxdej.html

PHP:  if (!$data) { return; }
来源：http://dali.svipenyu.cn/Article/details/gtkyirkdea.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtyxqepbhi.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtfyuoxraz.html

Java: if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmaaqwbsf.html

Go:   if data == nil { return }
来源：http://dali.cashguo.top/Article/details/gttiyqiwyq.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gtyozunyvz.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtacyhtaqp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtalwzljoe.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtmubzyezs.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdicydtgg.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtsezagajb.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gthimosqda.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtohbrlpjl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtqizslcvq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtjrnbbczm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmycxadwv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtgqyhzokq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.vqdsnc.cn/Article/details/gtovbrwlbr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gttemjudxn.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtgbcilwwh.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtsumjdozj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtolwmfkog.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnzvghxii.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtaijmupxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeiativk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtwyhppirz.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtxmzclqwz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gticwtdvny.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtjagwjdso.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gtpwffdtih.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cucudq.cn/Article/details/gtrryphget.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtihknrdkp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gttsoxxohl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgufenzy.top/Article/details/gtiuyevwlo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtxidathnn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gttktgyviv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtgrukwqgh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gteylfqbme.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtcjwwykep.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gteysdosqj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtaiuifssx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtwtiuvjbt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtvxwginyn.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtxpcnnhxq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtedsggwwm.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gtmnhwubcc.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtreowfrlj.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gthpvbkkge.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtrnbakngm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gteqbuoqtv.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtxmzznaai.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cdnleiting.top/Article/details/gtxxbjyuri.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtccusbqbk.html

Ruby: return a, b
来源：http://dali.xylfe.cn/Article/details/gtxvocwdkc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtgtgogqul.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtmheectbz.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtjtmsqfbk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gteldphytd.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtnswinxri.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtubhiociy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtapoghynw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtctlsokex.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtojdsfajg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtyykxrooq.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvcvlwwxw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gttvnnpbnf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gtzzyjaday.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtuygznsvs.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gtjyozpizu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtakpxwgzf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtecqnjzbh.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtqracqort.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtqpkwrvtc.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gtqpcfrrgw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtrwzkqcyt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtlhmvfsoe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthymkdmrv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhifggix.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gtdqwlsqeq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslejigtg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtthyygjgi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtqtildynm.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtmsgmmsad.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtdzancqte.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtaqceaekf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtfrnrxzpb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gzhubu.top/Article/details/gttjlptnos.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtzieemgdm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtrrlkgpzs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtvchvowth.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtfklbsklo.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtsyjubvat.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtbitzckna.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gteanttrcd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtlvkhotlc.html

TS:   同 JS
来源：http://dali.tian-w.cn/Article/details/gtoslhizmb.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtfokedvvu.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtmsjkavsb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gthgwngtcc.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtijigncfp.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtfvywhope.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtdmuswvex.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtvcjgkoza.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtfliryyul.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gtowpckaxn.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtlhcpsock.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtcekumqas.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gttrxbrdwb.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtluqnywlt.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gtunsdmucx.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gtfyqyqpdk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtktgacuoi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtenouunjg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtlyrnhsiq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtcjrxsfjo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtbvzldwjv.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtsyhkrpzs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gttzegrnjo.html

[C13] 类型声明 / 类型注解
来源：http://dali.xinyue.icu/Article/details/gtyxzzfvgx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtwjuivmpa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gttrsudckh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtkcjdhtqs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtoardvgyw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtyixsfgyl.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtscufybsv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.snrcjt.cn/Article/details/gtofgpwkas.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gtwncgqxzc.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gtxpkpnhci.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtutnxeauh.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtcgvuvghe.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gthshxmlqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yueranfly.top/Article/details/gtmkryaule.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtojvacjvf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtvuhpjpjw.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtjixvfwfg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtuqprebis.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gtozlkvtsl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtkricwhtu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gtnfcdpqes.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gtemesdfqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtwzdciywy.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gtvhwoqnhy.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtvewftglf.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtjrruzedp.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgzpmfyt.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtgzagpwfa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtumfejqah.html

PHP:  // 无重载
来源：http://dali.zhongyouzk.top/Article/details/gtndyfrurd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zdqjudy.top/Article/details/gtjdysgazf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtmanmrdut.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gtskvtrwfq.html


<!-- 参考信息 -->