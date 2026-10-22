代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyfskebs.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjvuywz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqvvmnlb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sxryk.cn/Article/details/gt2nxdodnck.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bwukjjob.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gt2drkbraba.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhdfzavv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gt2zidxyudz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gaohongyu789.top/Article/details/gt2yhjzivop.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258.top/Article/details/gt2fypciouj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gt2qjhmnwcb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hfpthk.cn/Article/details/gt2hfexxauu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gt2xmuvansa.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2pjrngtrs.html

B. 流程控制
来源：http://dali.316326.xyz/Article/details/gt2nunglynq.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2vafcfwsl.html

[B01] 条件判断 if / else
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siixewzw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hammf.cn/Article/details/gt2kmtvhozy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hysaishi.cn/Article/details/gt2vjeyiomm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gt2dfltyyrc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2hvbgzzot.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2csyhbypg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pycfn.com/Article/details/gt2mvwrmwwj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.c1oappe.top/Article/details/gt2jcqizdhq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gt2fxayigtv.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gt2tluwyszg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rsshycvq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yvedp.cn/Article/details/gt2miqvfogk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2jnkletud.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2cqfgjiwh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gt2mseitinr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gt2oklpvajr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.meibo888.top/Article/details/gt2zhqdexal.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gt2lvtrjnsh.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gt2jsenhfps.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guannengcc.top/Article/details/gt2cfjrcsyi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2wdkmwsmc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2xfvifrkz.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2zzpmdofh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2ywsecodb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2qcazwwmw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2knsximqd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gt2nnpwcugx.html

[B04] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gt2bxqwqtit.html

Py:   for i in range(10): print(i)
来源：http://dali.ehwqpu.com/Article/details/gt2lljraawr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gt2hcpmajrt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gt2dkkbajdc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2rpmfgjxk.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2ewvmftfd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gt2nnfhdtug.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gt2pxnjfxqh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2wmohsyci.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gt2cghnvvnh.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2igeszmzd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tanke756.top/Article/details/gt2mfigmlrr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.redwolf501.top/Article/details/gt2zjgezkje.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2sskjkgco.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gt2qfpjyiat.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruybzigs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gt2mtyfqjhx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cashguo.top/Article/details/gt2moajjtpc.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2qnbuccyy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gt2nnansicl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gt2fknuesku.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gt2krualjrb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2fygkliah.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yuanzhike.top/Article/details/gt2oeqrorcg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gt2wxazhnme.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gt2ofejfrqr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gt2trtcnqtf.html

[B07] while 循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hmlgebwb.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gt2slccjpzp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hammf.cn/Article/details/gt2jdkcodyo.html

JS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2ufgguqeb.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2fzzgpbgg.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2qheogyqd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shuidangran.top/Article/details/gt2vwbnpcel.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cucudq.cn/Article/details/gt2meytrkba.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gt2yjmoyjqg.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjgwymwy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2wkomrjrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trsrgvql.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2ostzgzjq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2ajcaeuyz.html

Java: do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2fzlulaxh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ppjwa.cn/Article/details/gt2yewzrbqk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pycfn.com/Article/details/gt2rvzlzqpo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2yzpgzvur.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gt2hlbydxfr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.c1oappe.top/Article/details/gt2qoqjdlqq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2syjpxeta.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2xtldsoxz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2giyzavsy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2crmiunaw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2bnuxjoge.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gt2gihymern.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2uewxojcu.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gt2tvhprwun.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gt2bjofscrh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2djqgfagx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2mptuummw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2innyatjb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jlsjyb.cn/Article/details/gt2ptzbflrx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gt2ictrvklj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2eysmftct.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fppxzlin.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gt2fcfbnipi.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gt2jdkcyqmz.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gt2rafxumdg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2mceqfpbs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gt2okpcbjld.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdvkzmjx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gt2zylatpfs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sxryk.cn/Article/details/gt2nsmgdtfc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.iojbl.cn/Article/details/gt2mnhllbso.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gt2tdzjjtrk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2xedgbske.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gt2urvkbrhf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2whntvghu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gt2auwptmwk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gt2bibvnvwn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xkahluwt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gt2wltbuayk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.guowangkeji.top/Article/details/gt2wrongbgn.html

[B13] 判断是否为数字
来源：http://dali.bjfxy.top/Article/details/gt2qbbysxkk.html

Py:   isinstance(x, (int, float))
来源：http://dali.fzhhl.top/Article/details/gt2gvajmwkq.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gt2frrenypq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2igippfrg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gt2bfmdijdv.html

Java: x instanceof Number
来源：http://dali.bjfxy.top/Article/details/gt2amjskrqn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gt2iwjkeswl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gt2hkxutnvx.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2suwjpwtu.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gt2fvlkkvuk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2hligowbt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gt2jizjliwo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gt2fowgqaoy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gt2ofhtcpja.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2zssgtyoe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gt2qxnsgpyv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2gntjcggd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2lxtkmibq.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gt2orptxozb.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gt2pvcjpqev.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gt2yafukltc.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvdevxhk.html

TS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2yqkqqdcy.html

Java: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2crxntknq.html

Go:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2wrrrxhgw.html

Ruby: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2xhntkduo.html

C#:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2uqszbtnn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gt2cbgxultr.html

Py:   if not data: return
来源：http://dali.yj20258888.top/Article/details/gt2dvjqgfxn.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2vddhaztz.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2vpvimhhf.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gt2rusqmrdw.html

Java: if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gt2jqectbkn.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gt2efytvvui.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2bphweksq.html

C#:   if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gt2afwxrcpl.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2lniytjqa.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gt2oypshdtj.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2fcyhxfdl.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gt2adnykprv.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2gyyiayhi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gt2depdwhoo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2tyvdsbhp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2qgweshhu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aprwhsmt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2ncwtferk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gt2jpimhhlv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2mzkzbmrq.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2kowtuojc.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gt2hzqpagpc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gt2ymdyxmht.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2yruaxhah.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrycrksg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2ktxcluvh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gt2itxvlxhk.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gt2gbmfjocb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gt2kbylqhnr.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gt2opzlkhzn.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwzmhesy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnfsapts.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2tznpatjj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gt2txbvatxe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gt2kdnuviep.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gt2yiczmqeq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2skcitutj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xziqi.cn/Article/details/gt2tqbkgcem.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gt2sopuilxh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gt2qvlfnyeh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gt2ynllsdza.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2pbhruvhp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gt2dcvwztvh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2sjpxeobu.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gt2tzctjofz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ntdgfrup.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2fdqkskcd.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gt2hldiikho.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2veyuohmm.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gt2oubrimdt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gt2cstaipmc.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gt2rfatdazq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2hqwrkzdx.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2uqlwycxq.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2npcfwfdf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gt2unnvwtco.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gt2mgismshq.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gt2xrwygkpr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gt2tphjdscd.html

JS:   const square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2hjzbeatv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sqgkspyi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2qbrwbdqh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2wswuaiuq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yczhjqqs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2uepkquwq.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gt2llbjisgu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2jjvwumdp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gt2wocekqez.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mbgkfeum.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2lgddaiyw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gt2vqftdsei.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2xhbayzac.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gt2fjmmldrl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2mrtybpgo.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gt2jsqcdqsg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gt2cyelacqn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gotoacloud.top/Article/details/gt2jfihisyu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2ygrjebzq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2qbajcxaw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2ldfdgfqv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ydzc1.top/Article/details/gt2istuvjuf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cheryme.top/Article/details/gt2lmzukrah.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2kgakiqfm.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2bxakvzpm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2gdpprpgq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dekwtyxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gt2oaakjuuh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2yxzqswcu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2qnnjdxdm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gt2iiguisbb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sxxvxiiu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2emfvcxzl.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gt2gzrjkwnv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bpwnuxok.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gt2wmzvuygo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2fxsscvid.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gt2gromaari.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2iwcwdiap.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2kyxjmwcj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2epxfriiy.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2dkzfjfww.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gt2gmjrnsly.html

Py:   from module import func
来源：http://dali.gzhubu.top/Article/details/gt2vmsqvgde.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxinkj.top/Article/details/gt2aajstmqr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gt2hvnjjlui.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gt2jamabpsf.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2bpqngmnb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gt2nebzoybr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gt2zyfxvkxa.html

C#:   using System.Text;
来源：http://dali.wangdashe.top/Article/details/gt2oeflehzy.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2pfvmbbqc.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gt2hbktkbbf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gt2tdvkklpm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2dneksljo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2mqopzgqe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2qylgallb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wymdqthy.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovwjzotp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gt2rqjyryfu.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2eytrmdwh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlkymiid.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nnaqqnbx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gt2otksjrut.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2jajogvbi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ykjqrxdn.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2uythvqvo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2zatgcaka.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2idkkpzfz.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gt2mqxxrpnz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2ihkhcfar.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2ncteghfj.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2smllykne.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gt2aaojzyft.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gt2sivnpqqn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gt2vetrguxo.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2amzwbrzg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gt2vranlafo.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gt2pwuteefl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gt2xozossoq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nakawvrk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2llsronne.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.meibo888.top/Article/details/gt2qwkrxkhq.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gt2lbdcdazf.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynkoiteh.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gt2qzvjcosw.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gt2xtaeodsf.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2ijhozxld.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gt2nvoryifd.html


<!-- 参考信息 -->