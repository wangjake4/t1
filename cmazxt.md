代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.haohaochexian.top/Article/details/gt2nhelrlgv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2anlntdsp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gt2ybbgczgy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2dwzlspty.html

Java: do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2rsjumhwg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gt2fvxzrejr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zycfv.cn/Article/details/gt2mnepgqpt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2nhqjsiev.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gt2bimsqbsb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xziqi.cn/Article/details/gt2hepbaqjo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2ourlkqfx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2yliapppz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gt2dudralpi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2elyhmztw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenlongwang.top/Article/details/gt2bzxqozvn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2inhvhjam.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2nddqrcbh.html

[B10] 遍历同时拿索引
来源：http://dali.zhixingplan.top/Article/details/gt2uhlbiwyx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gt2ybluhppu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258.top/Article/details/gt2fuagtwjd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gt2wgqgzilu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gt2fnhqxkze.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cucudq.cn/Article/details/gt2zgfyvdnk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gt2zijhzlbi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2hqegwmge.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gt2vktszntj.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gt2ogfoaajv.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2voztjfac.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dlgnvagv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2mfvoossy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2htqdrugz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gt2qyvaosqr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gt2cmewdroy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ndjdztgm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gt2omhijpnp.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gt2hylgense.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gt2qipynmii.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2njzqeoym.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gt2oelrofot.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gt2bxfhrehs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gt2pxwezblv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gt2nfejhiir.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gt2sdytfilb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gt2jrpxrxwj.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gt2bmflvjai.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gt2vrgykokh.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2unctxmkk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2gfuyuzxd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2dfcstqor.html

Java: x instanceof Number
来源：http://dali.sweek.top/Article/details/gt2wodwudyi.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.smart0.xyz/Article/details/gt2yeizsobn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hkjrtnmz.html

C#:   x is int or double or decimal
来源：http://dali.xuanzx.com/Article/details/gt2vxiyovvu.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gt2kotlgpmu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dpjavmdu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gt2rzesldof.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2licnvjzh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mgughqkt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gt2bdjptnjy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gt2jaiyqdly.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gt2tidxfiwf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2jbmohgyc.html

[B15] 布尔运算与取反
来源：http://dali.hysaishi.cn/Article/details/gt2xlncukgh.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ehuuxdcx.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2aspitcas.html

JS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2gifxcydx.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gt2vbpfvgba.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2czmvjiux.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gt2bohhxrqe.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2irwqzgpd.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2jfhtfqpr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2yfvkbasj.html

Py:   if not data: return
来源：http://dali.andypj.xyz/Article/details/gt2noxpegpo.html

PHP:  if (!$data) { return; }
来源：http://dali.gogol.net.cn/Article/details/gt2fwtryove.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gt2wimrykvk.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2jjlvksvp.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfnkgje.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hondasbp.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gt2othymjgj.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2agfcmoso.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2wcclcdrk.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gt2sbburknl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2txararip.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tdfontdm.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gt2hfqtksbg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nfzwvuqt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2vrykxanc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2xhphntyy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2udebrtcg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2uqpoqekp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gt2lapdbhhd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2tbxtfxru.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gt2mguryfkj.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gt2jwnyldgk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xkcqawuc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2vgkloxnd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2uxkcmpte.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hongshengwenyu.top/Article/details/gt2wkqjnccw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gt2mcavyczp.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gt2yjrxvenq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gt2ttysyxaa.html

[C03] 可变参数
来源：http://dali.cucudq.cn/Article/details/gt2ksfudieu.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gt2ekpdqctd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ezesrjse.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vrjhsyhi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2bvshpboq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gaohongyu789.top/Article/details/gt2qzojuxwp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2jshalont.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gt2phedyrwg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2xknlduwi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gt2rkcrmhis.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gt2sycifnus.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gt2hnibxboz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gt2jtwezkzf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gt2abpkvzii.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gt2lwbvrlyd.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2cjsxyvuz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2ntokkvwt.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gt2zlhnqxry.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gt2ksmqnawl.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2bclafjuj.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gt2ckobpdtp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2ihutlcgm.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2vxogycmk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gt2wzdcsmag.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gt2kkvkotoy.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2iitnkrdt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shzxlz.cn/Article/details/gt2zlilvllr.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gt2uzopmvgc.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gt2mxyipmzq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zycfv.cn/Article/details/gt2wzgzzxjd.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gt2gwjjxlgt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2afqnlqax.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2khtvmuvo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2vckcqhii.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xrwndzgf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2nxezrcfx.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gt2mczhsoam.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gt2dvlhokwi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2pgrtocuu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2pdcslgmx.html

TS:   arr.map(String)
来源：http://dali.jqgfzy.top/Article/details/gt2actauhoj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuxming.cn/Article/details/gt2ypquhaoy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gt2omjcdnvb.html

Ruby: arr.map(&:upcase)
来源：http://dali.dianchejie.cn/Article/details/gt2vzgrttlj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gt2bggxioez.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gt2hwrgrzaa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gt2kplabmsq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gt2uiibjnlu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pttnyzih.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gt2wwysbtzx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gt2gqgzpmln.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rjniicdl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jlsjyb.cn/Article/details/gt2bfsqpfiv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ogkbcarh.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gt2nscfngjb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2jugyycyn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gt2nytylcak.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2gxjftjui.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2hnzmowgz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.316326.xyz/Article/details/gt2rudtrrnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gt2luqsyyek.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gt2zmxqever.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gt2uulvsqms.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gt2ehpligkt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2wtdtsrad.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gt2bjzmaksi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2giiehwpd.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gt2wyuwdvsd.html

Java: 方法内为块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2kcigrtce.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2ocfdieyx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nwbrower.top/Article/details/gt2oqyvbcao.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2hbjspmdo.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gt2eiwwqiyy.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gt2syvytsua.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shangyingyoupin.top/Article/details/gt2maxkjyep.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2pidkjtrx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gt2hhoduavm.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gt2dangdbih.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gt2kujtqgwq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2zhanbwmv.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gt2fbqvsmhc.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gt2byevdesn.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwdslmvx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gt2veunwqgh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2wgxtcrke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2ulytffks.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gt2ncuinrty.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sxryk.cn/Article/details/gt2bnegaqeu.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gt2rnmuzpie.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gt2zqibeomd.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2ilyduwqe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gt2niycjiqd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2qpfbarnt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gt2depoosul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gt2olpescif.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2duqagzsy.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gt2agtlpola.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gt2kzsdjrvq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gt2lwbpfwhz.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gt2sgcsnsgf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gt2bdgmhtyx.html

PHP:  // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2uxjkomff.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2gfwncsqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.smart0.xyz/Article/details/gt2ejyrbxxf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jianghu66.top/Article/details/gt2yocptcpi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gt2nticuhsk.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gt2nrxwibwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpdgbzlr.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gt2liwhzlhd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gt2zfbcmuas.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gt2bzvztuhn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aizwys.cn/Article/details/gt2ctxafjkg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gt2pwkmpsmd.html

Java: // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2bxbruoji.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2hwcgxpoe.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gt2cqzcnhen.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2bmhbjrxv.html

[C16] 函数 / 方法重载
来源：http://dali.iojbl.cn/Article/details/gt2zyiwtisf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gt2onzdmhbo.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gt2qzmthist.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gt2cmesbrnt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2sdylccvu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2pdczabki.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2wcaultdp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xylfe.cn/Article/details/gt2fvapclwm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2ygfxurgn.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2gkwntpti.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gt2hkinkebk.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2ilqppuea.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gt2rpsusfqy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gt2hzeqjova.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gt2nlmvkxor.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2sejbthvt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gt2rkcqjada.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.havefunace.top/Article/details/gt2npruwdkd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gt2kpuolatn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2ksdghypl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gzhubu.top/Article/details/gt2aaefbfua.html

[D02] 追加元素到末尾
来源：http://dali.shangyingyoupin.top/Article/details/gt2wvduhyya.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gt2ovkbmbqz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gt2hfuwxdri.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zkhhetsm.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2lpcqrpon.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2fhkhfyeh.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gt2pdcusglo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2vlmgnzvi.html

C#:   list.Add(4);
来源：http://dali.daria6918.cn/Article/details/gt2tgqrbwki.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gt2ucxtmvpe.html

Py:   arr.insert(0, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2eluwwydi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenzaomai.com/Article/details/gt2suznuboc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gt2ralipuvp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gt2tcuwlrsx.html

Java: list.add(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2vwkoahrn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gt2glsveyit.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yvedp.cn/Article/details/gt2lrucwqft.html

C#:   list.Insert(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gt2mafuhlmi.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2pvcumcod.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenzaomai.com/Article/details/gt2vagvmsat.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gt2oieenrpy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.redwolf501.top/Article/details/gt2ojrbowcx.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ukoctkir.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gt2zxvscaga.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gt2pijezeyz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2winmkyxm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2ffinhqgr.html

[D05] 访问与修改元素
来源：http://dali.gogol.net.cn/Article/details/gt2vwcfsuvf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gt2stkaslkd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gt2nzrxgoyr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2jbdjstfr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sweek.top/Article/details/gt2qgzbptns.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gt2fwqeprlw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2gcabakiw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2vghqapux.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gt2aqxsmkmj.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gt2zmosbadm.html

Py:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gt2fwpnfsav.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gt2mdddkyvv.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hpulhnkx.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2pureyamb.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gt2pjgzxsro.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gt2hwfhqtmd.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gt2lmwauraf.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gt2wbftlskm.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gt2jvrmovax.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gt2exfkeckc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gt2tqwxbtyn.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2uqdwqrmr.html

TS:   arr.slice(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2rwxcicle.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2ibufwmlc.html

Go:   arr[1:4]
来源：http://dali.316326.xyz/Article/details/gt2kothtauy.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2ewrvrqzq.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gt2vtdgvnvn.html

[D08] 合并两个数组
来源：http://dali.jqgfzy.top/Article/details/gt2wrvpvbwj.html

Py:   a + b;  a.extend(b)
来源：http://dali.cdnleiting.top/Article/details/gt2lgiukure.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxmxpabp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xylfe.cn/Article/details/gt2vkydgaam.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gt2znfxbtjs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2cmmczutm.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2urfhvibi.html


<!-- 参考信息 -->