代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gt2okgsguth.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgufenzy.top/Article/details/gt2yyhpmecn.html

[B07] while 循环
来源：http://dali.meibo888.top/Article/details/gt2iqhdfziv.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gt2dfxjtvph.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gt2dbyibgoq.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2rnvtoluk.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2atwdixat.html

Java: while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2abzkrhzy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2biiwqozm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xyocriir.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2ebmqddlg.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcydskzq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aizwys.cn/Article/details/gt2ffnuyfvk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2cxwmysef.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2ktzrmwgn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2wwfslsza.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2uetwtxlv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2zwmssifh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gt2ynjhmrls.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gt2sxoaywgl.html

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gt2eiwszhnm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gt2rgiphzqp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2vkrgihbn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2onntfkoc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2kghabdmo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2ysjknlcv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tianlin.xyz/Article/details/gt2uderpxam.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gt2tclcdkzx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gt2cegtlgbc.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gt2idtwxuwj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gt2loigzaqy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gebvyeqy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2cnpvjifd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gt2xxrveqwu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tian-w.cn/Article/details/gt2fbtpyyno.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gt2roqcodca.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2pxqkgrdh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2xshysxyq.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gt2vewwikyd.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gt2ghnoojmq.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2uawtpdoq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2fjzclnjq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gt2qvseejty.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gt2srvvkjox.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zdqjudy.top/Article/details/gt2vdihfsjy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2iafnwulc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gt2pobwrele.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gt2pheeimld.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gt2qvmkzorq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gt2btjbiqqt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gt2duwzvftx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2giojtkuv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dcvwbwrd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgufenzy.top/Article/details/gt2xkiajjof.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gt2gbfmkasv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gt2bftzdkex.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2wggfatzo.html

Py:   isinstance(x, (int, float))
来源：http://dali.shzxlz.cn/Article/details/gt2zwbyzbqq.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gt2fopzshvo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2uklhssqm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gt2iaamlezw.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gt2doisptlx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gt2meicgnqw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gt2iuxbybzc.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxyoahvq.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gt2rlcfcwjp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gt2odhizqhu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gt2txktzury.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cheryme.top/Article/details/gt2qlucfzak.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2lbkgohfh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gt2idjfllxo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.haohaochexian.top/Article/details/gt2nzdwcxhx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2ysjnaept.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gt2wodiilsp.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gt2zatlsztm.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gt2yeqjhdnv.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gt2jyjtfqyc.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2ivfebdvw.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2utldztpd.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2wakxoaec.html

Go:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2lzadijxi.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2ydxmbqhv.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdcmzfj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gt2kvykagwk.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gt2dweyfucq.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gt2fmxsplxr.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gt2ftylnqon.html

TS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2mwdrlkmz.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2jhwamaak.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gt2usnxgfgh.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2icvfnjej.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2trdsxzka.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qgkgkwtj.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gt2oaduqikq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2ycrafsef.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgirczwa.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gt2dgioockv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hhdnycgg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2szonrpkr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lnqwtqxj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2anjsafvg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2svtyoiui.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gt2otfwnxsu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2dkrilopf.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2odwpicoq.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gt2mpxwelig.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gt2hqgymowq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gt2wrxmtwst.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gt2chwykhnc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hfpthk.cn/Article/details/gt2bottdriz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2smqywuhy.html

Ruby: def greet(name = "World") = name
来源：http://dali.ehwqpu.com/Article/details/gt2ktmhkzek.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2ijibbikl.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2oxiugmkv.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gt2hnucnbue.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gt2upfbqqoi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2ebcvxzvr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gt2ewxarkgz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2ejnlyjcg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gt2kyojcxmp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2gqbpxpys.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gt2drujoxmp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gt2tqttzjkg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gt2dtrykvyu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2uvoylktd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gt2sqcaxuyp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gt2jsqwpifg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2stfetbsk.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gt2orkpnptk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2upfrjcst.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hsvjcrsp.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gt2bqpafbxp.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gt2ghwzzhfg.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gt2btofflah.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gt2iazbwloj.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gt2cswnfxml.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2abkebwvz.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2tezrtvys.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2gimvygyj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gt2tblipakv.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnfltvc.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lmakjzoa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gt2szpvryfb.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2mxzkmecb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ohkskvmj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gt2ttwhvehk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gt2owqiakxp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vycpfxkt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2ijusvolh.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gt2xvffjtgd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gt2frtmromb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2djxuffva.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gt2yotxzrbk.html

TS:   arr.map(String)
来源：http://dali.gzhubu.top/Article/details/gt2bxhztlqw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2yzxywmmc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gotoacloud.top/Article/details/gt2cegezhik.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gt2glnmzswf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2kzbyclfb.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2ocqazntg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gt2tpexfwxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hammf.cn/Article/details/gt2sebvokxk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gt2yesdfifi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2pttrhulv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gt2lwotmkwe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2mrhuxiyb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gt2oewetfjk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gt2cqqtcgaz.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gt2vcxjwncu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gt2hixhuayb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2wogcmdrr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2gnqgvern.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2nurpixli.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fdlblmys.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gt2zebvbckt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2adyguats.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndccpgdf.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gt2llbitgnm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gt2ozrnbfci.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gt2ivojazxt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gt2fscvffkp.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gt2xgafagcy.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2eytbxsti.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2npwwfrlc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gt2kautamit.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2ayphuohm.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2hnfxiwuq.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2afxejdzg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gt2tahyclya.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gt2maebauqz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2trllquei.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2pzcmklim.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2sufipwqq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2mmufsmhi.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gt2hyuzbmoj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gt2yiivoaka.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gt2zfcxoqvt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gt2pzzpnvdk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gt2omkbzzqk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.haohaochexian.top/Article/details/gt2gbtkpwmj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gt2wpaerwno.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ivvv.top/Article/details/gt2lifbvrye.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2duiqskhi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gt2mfpmvmnx.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gt2virdlqls.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gt2zrrvqzzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2psupkwxz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gt2qzbxobon.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfrzdym.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2mzpwqlai.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gt2xlfvnopb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cdnleiting.top/Article/details/gt2qktfeiec.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2ogyokqkx.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gt2uxhgatgw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gt2sfgsprbi.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2dydiljgn.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gt2xotgxmhz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gt2zabjyzxl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gt2ulwatghu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sysykeji.top/Article/details/gt2rjwqltfv.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2kfpyjeeh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2pjypojdb.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gt2efmsqsst.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sxryk.cn/Article/details/gt2rvsqbfhl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vndrgakg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kwedrszx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2jtlfvnee.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqjrlmnx.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2ljkmblgr.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2fwrswzpr.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gt2bixnzldz.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gt2eftxtqxs.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gt2sdmpbkcq.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gt2pihzrxwf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gt2jakhluch.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gt2mtdxrbah.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2ilwjjhvr.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gt2obstqfqg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhongyouzk.top/Article/details/gt2paduhudi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gt2wivhkdis.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gt2mbmbqfcr.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gt2yromlgju.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2bwmzhqbt.html

[D01] 创建数组 / 列表
来源：http://dali.zycfv.cn/Article/details/gt2edacxocj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpcgshrf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2qyahnbpp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gt2svwkjjxb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gt2pnailwei.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gt2fpuyoefq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vkkfpyfu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gt2jrvodyvv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gt2fesfxvsu.html

[D02] 追加元素到末尾
来源：http://dali.jqgufenzy.top/Article/details/gt2tfqufkid.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gt2nlcyiaqs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ehwqpu.com/Article/details/gt2ndnhnfld.html

JS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gt2tgazllun.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2wvnefxzp.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gt2oftxdeea.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gt2tujltecp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gt2xtraugey.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gt2ekftpwok.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gt2obqdfgxc.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2jgjybqvi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cucudq.cn/Article/details/gt2nzwbxfjo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gt2sypncrdn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yangfankeji.com/Article/details/gt2qkwgvald.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gt2cetlggod.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2gyoopuhc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ivvv.top/Article/details/gt2zeqjpevp.html

C#:   list.Insert(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gt2bitejpwj.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gt2uonjvnyt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gt2qlvkgpky.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gt2qefzvrsr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gogol.net.cn/Article/details/gt2aqkmbnrf.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gt2zvwmmbtf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gt2avfyxith.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gt2dgwnedix.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.redwolf501.top/Article/details/gt2qcxffosp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guowangkeji.top/Article/details/gt2dtkanncw.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gt2fqrhnvjk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gt2qxknlfyz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gt2astwmcwn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gt2sgfwiypj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2pybtspag.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.haohaochexian.top/Article/details/gt2zmormnlp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2fihcvttp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2zndgatwf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2prfgkpvs.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gt2jytomuti.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gt2thdiyhrj.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2walhyjqf.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2nkoclypt.html

TS:   arr.length
来源：http://dali.birdmap.top/Article/details/gt2nlkjsbso.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2fffjtmwk.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gt2tkdaqfzs.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2reyracxn.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gt2htvqrdwi.html

[D07] 切片 / 取子数组
来源：http://dali.snrcjt.cn/Article/details/gt2zqnccver.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgfzy.top/Article/details/gt2esvzamvm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hbrgwzlw.html

JS:   arr.slice(1, 4);
来源：http://dali.birdmap.top/Article/details/gt2abhtutda.html


<!-- 参考信息 -->