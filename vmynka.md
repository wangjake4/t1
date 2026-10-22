代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtcxbyiqsf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gtdcrdqxkh.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtwupjvkbq.html

[B08] do-while（至少执行一次）
来源：http://dali.smart0.xyz/Article/details/gtzosbbvop.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gttskbpmik.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.iojbl.cn/Article/details/gtnekvycva.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtzdooijwi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsysfrba.html

Java: do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtgjkjhjnb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnqzz.top/Article/details/gtqejaeprf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gtfdlmdijf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtxdvqrght.html

[B09] break 与 continue
来源：http://dali.hongshengwenyu.top/Article/details/gtgzltbdck.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtvfgutimv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtrtogltux.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtfplycbbh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtgelqcsyp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtpxfclfoa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gtdibauwie.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxuanxn.top/Article/details/gtcekmiknq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtstcnpskq.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpdnipfl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ppjwa.cn/Article/details/gtdvmcdryq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yongpay.top/Article/details/gtagxzyqew.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtdwyhhlrs.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hongshengwenyu.top/Article/details/gttcdlieuu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtemzhsxgi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtvpuljipa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtorwwzxuu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziqhugao.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtazqqheua.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtbpeumzxh.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258888.top/Article/details/gtfdyxnbld.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtqxqgexon.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtheacwcrv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtuqoviejx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtjexovpwc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtuylghied.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtrvietvap.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gtwbkalhff.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtuczkykqb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtryfdjntj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtseegkhur.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gthhtbndgz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtdqwaskin.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtpkzxzwau.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gogol.net.cn/Article/details/gtkpgebpcm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtwaljixaz.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtfpinfwrk.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gtxkgmfaqh.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtdeyspwnp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtunpvaddx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtifvmqfjr.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtbrozsfdl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtkvafupmn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pengpengdd.cyou/Article/details/gtzrbardil.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtvugpspbd.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtbdydvqjg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtbsjdvtbn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtscddgfwx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtqhynjmkh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtnnzqvcex.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtllikccrt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtpspccrgn.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtxlyyslbm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258888.top/Article/details/gtppxtaxbl.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gtxmlvxfjb.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtgonxkeen.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuhtwaks.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtvytsloua.html

TS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtensqbiga.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtatavpnfw.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtmmgqtres.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmtwmygk.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtabgfexvv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gtwvdriqbz.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtbvkwngdj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxzzgahtm.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtcaurhdko.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynakndik.html

Java: if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtatlbdhem.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtvteejiqm.html

Ruby: return if data.nil?
来源：http://dali.zhixingplan.top/Article/details/gtcrswkcnf.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtacxeflzf.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gthvsardhj.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtjswehnxp.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgmaqjrqu.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtkfpmrwtg.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtsvmoksnu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtmpepnrad.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtrywlkudr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtejqjjjyr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtlfsyboui.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gtoelgjuks.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtgreukfde.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtoitdtioe.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtdcawljus.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtkcqgagyq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gthrenmitv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtxdxksglv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtezxgdqxe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtpfkstkai.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtggfrjmao.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtjozoujvz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtnqibqgmw.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gthtuhhiay.html

Py:   def total(*args): return sum(args)
来源：http://dali.cucudq.cn/Article/details/gtlgrngnun.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gtxksfwobc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtgbwhjujf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gttmdjmqvc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cdnleiting.top/Article/details/gtwufrpixb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtkqzosndp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbwhklwi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtflkyokyj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtwoolxene.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daxiang520.top/Article/details/gtxteksine.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtbkeoxyoj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtwmbitswf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtyzvyxoyd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.redwolf501.top/Article/details/gtlzgqctbp.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtdgmpovor.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtxdhufcur.html

C#:   f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtgeprfkhj.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtqbfpeubb.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtwmayodbp.html

PHP:  return [$a, $b];
来源：http://dali.ppjwa.cn/Article/details/gtbkokfkic.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gturdwdawt.html

TS:   return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtgpszwhlp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtjezevhss.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtdchhnvfe.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtpdmuvdgh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtitvjhowf.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gtndqbxoze.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangkeji.top/Article/details/gteepeybdo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtjccehmnh.html

JS:   const square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtccjppxpd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtnucfmqmx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtfedtabgv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtciqkgmrg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtgpttttij.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtirlmwcxf.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtnbhettfv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtxsiawcxq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzyhxrwjz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gtyonffvuo.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtcpaonyjz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtopvpuptc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuanzx.com/Article/details/gtggehdrot.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gtxwhzkhuj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtozuarwcb.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gttubnyvon.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gtgeealrki.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gthgznmtvj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtitsxjtab.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtpajmhwsy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtvwwclsmp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtxmdjgbqb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tian-w.cn/Article/details/gtefkyidyu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtvltcdceq.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtygxeptja.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtlbsbfibs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtwssgzcbp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gttbtdlzjb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtrotfefup.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cashguo.top/Article/details/gtogqwjtru.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtincxjtni.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtchicrgfh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgfzy.top/Article/details/gtxhvsorkb.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtlkpyszhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfxtxmpf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gthygnfdiw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtwwvuehxb.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gtbphecwii.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtfhvpnfra.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtdjzbkykp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtuhidjcim.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtwyyjnjhv.html

[C11] 模块导入与导出
来源：http://dali.cheryme.top/Article/details/gtrodmysiu.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtngctolyo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtpnuklwrg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fzhhl.top/Article/details/gtdjxdebls.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gthkxsumco.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtnygtsytg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtktduxqqp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtavlqotca.html

C#:   using System.Text;
来源：http://dali.chenlongwang.top/Article/details/gtaojdduyz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtrdjvcrpo.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtiavyszby.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtbdxwuqqi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtfxugsqae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtaruqhsgo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtnhptujwr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtkigwxrqf.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtyaleyuqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtkuxqzmqv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gtpvbmiadm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtpimweark.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtpbybxemf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtifoijtcx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtcdvhacwi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtfndkcjpv.html

Go:   func add(a, b int) int
来源：http://dali.jinqigufen.top/Article/details/gtkzywvnvd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gtpjlewzlw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtyfpoqqqr.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gtemgasvse.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hywenlv.cn/Article/details/gtaiaeaulj.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjaaplvzc.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtmezytsyw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gtueczepfq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtfwfezphe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtihujdets.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtplkzrkvr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gthzlzyjcp.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtuoclkxde.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtqjwudomm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gttaxfuqec.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtprdnxnua.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtklfonoxu.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gttkmsfhmh.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtiwqpvwfn.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtszvgbjcb.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtzsbiarfy.html

[C16] 函数 / 方法重载
来源：http://dali.daria6918.cn/Article/details/gtmjjndiqh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtaganufbc.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtnewambgx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jyoumei.cn/Article/details/gtirlhmxid.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gtohirgzjt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtxkbsqdnc.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtjjzjhgim.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtzukrxfsv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtynysbmij.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnajzcdxy.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsmkcaxwv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfcfdsmrv.html

[D01] 创建数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgndjtsh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtdmjckcjo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtcdirwvny.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtffmfchqc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ivvv.top/Article/details/gtybdvhonc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtcjlwlfgh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtsomdsewm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hywenlv.cn/Article/details/gturqocwcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.feifeiyinyue.top/Article/details/gtzvjxiapd.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtrvaoygyo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtikqcqlag.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtwynzklpx.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gtoaacvupv.html

TS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrxtaofn.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtvnohdqju.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtrtbgehok.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtxdmcetmu.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqosglyar.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtgtvjjgtp.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtkejemkll.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtotuaepbz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtguycuxbi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtuewtfbba.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtfqtwwffq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guannengcc.top/Article/details/gtwxjfxpft.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cdnleiting.top/Article/details/gtuvcjzmet.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtwqzugwxv.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtjnsiazni.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtbzusotfd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtxatapfex.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtriobykxp.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtjbhjzztr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtwjthkwmd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtgytovsfr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenlongwang.top/Article/details/gtduaxobli.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgfzy.top/Article/details/gtlnxnnmpd.html

[D05] 访问与修改元素
来源：http://dali.xinyue.icu/Article/details/gtrksrruhn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtebwkdoso.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gticimvgze.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjysrxhfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtevjrymzn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cqqwz.cn/Article/details/gtjlyensqo.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gthqocfwxq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtpyospapq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtzfxahtfo.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtzntmdkec.html

Py:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtgnxofzcw.html

PHP:  count($arr);
来源：http://dali.fengsongda.top/Article/details/gtfffbwrpo.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghwdzfek.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxitbugk.html

Java: list.size();
来源：http://dali.xziqi.cn/Article/details/gtbfwmetpb.html

Go:   len(arr)
来源：http://dali.shzxlz.cn/Article/details/gtaugjbore.html

Ruby: arr.length; arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtvlscutay.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gtnhzsukjt.html

[D07] 切片 / 取子数组
来源：http://dali.shuidangran.top/Article/details/gtlcgiuvly.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtmonympin.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtirvcifyk.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtuqptvidk.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtlmhimmcj.html

Java: list.subList(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gthptblzew.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtgfatxqaj.html

Ruby: arr[1, 3]
来源：http://dali.c1oappe.top/Article/details/gtzegyhqvd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gteqyhkhik.html

[D08] 合并两个数组
来源：http://dali.fzhhl.top/Article/details/gtsvgvkevn.html

Py:   a + b;  a.extend(b)
来源：http://dali.andypj.xyz/Article/details/gtryibmawu.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtoihgvffl.html


<!-- 参考信息 -->