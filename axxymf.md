代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcewmivig.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtstvvwqko.html

C#:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtjkgmlabm.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gteisvibun.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtlfdmxfsq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gteulqinkn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtsfksbigo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtuylsphau.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtjwipvpuv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtixpkjicq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gzhubu.top/Article/details/gtutqmixmj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cashguo.top/Article/details/gtvxqjomxz.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gtannjtbkt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtdolthxty.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtlkpkodpf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiawvugu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtogkrwfhu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtulzzxrxr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtznmtklbi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.smart0.xyz/Article/details/gtiavgpzas.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtfvshhsjy.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtybzprpql.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtdoginrhk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gthnppycea.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtciyhsamt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtnatppwaq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtyslfgfma.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtmmidrstr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.mhx1999.top/Article/details/gttaphczih.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtbdjkrqbk.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gtmivnrfgl.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtxfxixihr.html

PHP:  range(0, 10, 2);
来源：http://dali.guowangkeji.top/Article/details/gtlyrxqqwf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtcgacgdpc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtluucsnmp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtyyabxjzh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidwtgswj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jiagoushi.top/Article/details/gtaaadejjw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.aibaodan.cn/Article/details/gtyqdvgrng.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gttrenvrzd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtazdqyluq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtuhnomige.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtwbxfcfiw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtvtxqbvsn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtboivcnrl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtezpiwlio.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhixingplan.top/Article/details/gtuqawgcwe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtmgepksij.html

[B13] 判断是否为数字
来源：http://dali.hywenlv.cn/Article/details/gtvoiikzlq.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gthgqiatdz.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtaaznwjue.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gterhyusil.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtfdjlkeol.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiotzjma.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtsfhjxkju.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtgiaoudot.html

C#:   x is int or double or decimal
来源：http://dali.vqdsnc.cn/Article/details/gtaelubmor.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtosbitfqv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gtxlvkwppa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gtgkfnfusy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gtvuahizwf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjagurjcq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtqbsxylho.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhoulong.xyz/Article/details/gtsssmiljy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.iojbl.cn/Article/details/gttyzcejyq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gaohongyu789.top/Article/details/gtjqqjtewa.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtwqdmupgs.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gthjrcaqqq.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gttapblpkv.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgouyvpda.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtuwxuyeuk.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtumcsuqgs.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtbamqdere.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtnrhodjbl.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtmoajwswl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgfzy.top/Article/details/gthysulryz.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtbtziesqe.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtrvkxivez.html

JS:   if (!data) return;
来源：http://dali.iojbl.cn/Article/details/gtemieulyw.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtsoygnibs.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtyoslouoh.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtxrytepdx.html

Ruby: return if data.nil?
来源：http://dali.zhaomingkeji.xyz/Article/details/gthiigblca.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfyhulej.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtybbgxkye.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtougwxcks.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtdrzlbgbr.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtuqgecupz.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gtkuwibuii.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gthwxjjfrn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvrauwyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtajryfskm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtschaejnt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtxdopzotc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtdeegmvrb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaefjhpql.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtvbqxcnqr.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtrsylexzc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtldezmecu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtkguwdclv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtgknntmvk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtvpbrxkap.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtopnttikj.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtusikukxv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtgkydscka.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfgynmpe.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gtdvphhxfu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtorrihqek.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtrmrhwbim.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtyztzbzgt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gteekgfpsf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.vqdsnc.cn/Article/details/gtseatrcig.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtwisezxyq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtxrcmzekh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtbfxvsebg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtahutzedf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gthlqigdnf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtcmghtoae.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sxryk.cn/Article/details/gtzwpnshkq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtmlfdinvn.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtcozsfzyi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtgcxtglxf.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtkkkheeok.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gtdyvywmgk.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gthxjordha.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gteifhvmjd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtbjicerik.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtddnhzscp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtszdjrrjh.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtrynmwjrp.html

Ruby: return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtmsrupvqs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhongyouzk.top/Article/details/gtyalwaaet.html

[C06] 匿名函数 / lambda
来源：http://dali.cheryme.top/Article/details/gtlcekewew.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gtckljwuxj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxukocil.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtkookqlmg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtzuvowebn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtwnbvacty.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtdgqzltni.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtxugppint.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gtgtbrealk.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gthheuyjci.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtpkecaobf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtoqjdvrue.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gtvvgcpljs.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gttzdydvbc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtyvusbggc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtcngpdnhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gtuffyhsdw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtisirabzg.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtqiifmwuw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtkxrpmcru.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtrdmiskse.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtcbyefnme.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqzglpsvk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtfkzxzwdh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtrauhfnqo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtcwaxlrfm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtpeiaczfw.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtaatcxhmv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtvpvafjwu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdooekhpn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgdmvdfbx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aibaodan.cn/Article/details/gttjkqotsz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtvhndwdmi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.mhx1999.top/Article/details/gtbkbsqjps.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtgireaqom.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtbxsytaxk.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtjduycrew.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtuqpkcdan.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gtwmlsxpxx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.quarkkingdee.top/Article/details/gticmmrzcm.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtehaegjvs.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtkorkjmvq.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gtshtxgrko.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gtmnxqtvzl.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gttyondzgx.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtpcqbmpvl.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtsgxidizg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlszxdutq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtntegzgjj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtwiunhjni.html

Java: import java.util.List;
来源：http://dali.yuanzhike.top/Article/details/gtnkpbgghf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtgqpuxorc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtorrndkod.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtktplqyha.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtzeahfgkh.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gtvfihffyl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtrwjtcarw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtyekehlum.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gttbhallvp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtjhaexmcy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtoppucvgu.html

Ruby: -> { puts "run" }.call
来源：http://dali.gogol.net.cn/Article/details/gtihkiagiv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gtkcsgxpoa.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhongyouzk.top/Article/details/gtbabpprke.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtdhgqnpif.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtqgbydmkb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtqfqnnluv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtzwmznext.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekxxjgov.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gtsguxdjbw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhixingplan.top/Article/details/gtbwgbmhls.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtsiujixaw.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtrfotehte.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtasiotzxe.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtxuvuzlxl.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvicwwqo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.mhx1999.top/Article/details/gtdiqmugjw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtjnukptxh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gtzbmtksdn.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gtwhqwpnpj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtalqumlgc.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gtvwqaljjd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtbhkhssid.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtbsqstxnv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtknspgcql.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtxsgkqfnp.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtkfscacgr.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtqxuzkamt.html

Ruby: a, b = pair
来源：http://dali.shangyingyoupin.top/Article/details/gtycbgozam.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtxddhkgps.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gtbuwuiukw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtnuliozjd.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtvccmhzsz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtlztwimip.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gtwggegrnb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtgagnjorb.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtauorhkqo.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtjexvgyqc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigufen.top/Article/details/gtjolbawsz.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtuahgulhg.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gtdfemjvvr.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtbqzpdvaq.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtgbdbnsqz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cheryme.top/Article/details/gtkflunrtl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtsnmcrpta.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtlicoveuo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.kuanghao11.cn/Article/details/gthyygcogg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtfbcjxhxl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sysykeji.top/Article/details/gtxbpjewvb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pycfn.com/Article/details/gtxhajmgyi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsilduuny.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gttcsoaitf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtocsvoleh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtuhiqiobu.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtppyfcrsy.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtnceleqew.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtlvroxbkx.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtjbpzbmzi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxeebqsk.html

C#:   list.Add(4);
来源：http://dali.ybcxt.top/Article/details/gtxfgroezs.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtnrmibddy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdgklylzd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtycoescoc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtmikbomuv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xylfe.cn/Article/details/gtfecgblxq.html

Java: list.add(0, 0);
来源：http://dali.yj20258.top/Article/details/gtpqiuniyl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtpgmfdtum.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gtgjueyhfa.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtlwdrtjwh.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtexvpffni.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtglbykgzm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtkoxlpxjl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ehwqpu.com/Article/details/gtgbmoocdd.html

TS:   arr.splice(0, 1);
来源：http://dali.tian-w.cn/Article/details/gtoummviex.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gtkvkacdpi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gtgogpebsl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gtpkmfvzkz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gtmezczfvp.html

[D05] 访问与修改元素
来源：http://dali.zhengqikj.top/Article/details/gtkssgbkgh.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtbsptwuon.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtugkqajuy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtjuoqfkks.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gtifeupafq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtnupzzgrn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtvmvqugou.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gtuxllnqcn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtvxqjoluv.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtbtcuftkm.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqdryfnt.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gtqrixbuvk.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtmhgltlsz.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gtmaeulivj.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtyfzqgero.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtghljylhy.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtmqrejizj.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gtwvjxacfv.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtrnqjwodw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenzaomai.com/Article/details/gtgjybuupx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgokdiotu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtlmqsvqvk.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtvypxynfa.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfabmprlp.html

Go:   arr[1:4]
来源：http://dali.feifeiyinyue.top/Article/details/gtoyqpmbim.html

Ruby: arr[1, 3]
来源：http://dali.jinqigfzy.top/Article/details/gthhfjjtif.html

C#:   list.GetRange(1, 3);
来源：http://dali.andypj.xyz/Article/details/gtmvmvsbmt.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtcqarrqkw.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtdlsgwpzr.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtwdtyxhcy.html


<!-- 参考信息 -->