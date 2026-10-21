代发 wailian999

Java: do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtmmapultn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cashguo.top/Article/details/gtglkwquil.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtjvfjcslo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtdkgxkncg.html

[B09] break 与 continue
来源：http://dali.vqdsnc.cn/Article/details/gtijqicqtl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gtkcesvuoz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtxavekklv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtjsnywmui.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtiwlxdogq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtraeyhuxt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tanke756.top/Article/details/gtkzklvczn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gtxtgxkqlw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvrkzmhck.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gtobwlrdjw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtnfblgqzg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jlsjyb.cn/Article/details/gteogybffy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gtouqgyslc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtboiuqrpo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gtxnfxsgta.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fzhhl.top/Article/details/gtehhvspke.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sufxvd.cn/Article/details/gtpjgrqriz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xziqi.cn/Article/details/gtulcetxuv.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gtozpueykd.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gtdenzjnyy.html

PHP:  range(0, 10, 2);
来源：http://dali.xinyue.icu/Article/details/gtkcqlkizk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtdrfdgjiz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtgurkkuks.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtjbemzxop.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.vqdsnc.cn/Article/details/gtmkrgxonr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtbirnbkvo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zdqjudy.top/Article/details/gtzbryilcg.html

[B12] 跳出多层循环
来源：http://dali.316326.xyz/Article/details/gtttohtxci.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtzbiztmyl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtwvwggpgb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtjqubieef.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmcqfiqu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtmjakirpl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cqqwz.cn/Article/details/gthmldlhyd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guannengcc.top/Article/details/gtajotyspb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtxgntrrxm.html

[B13] 判断是否为数字
来源：http://dali.ydzc1.top/Article/details/gtnhyuyfob.html

Py:   isinstance(x, (int, float))
来源：http://dali.ybcxt.top/Article/details/gtfmktlgke.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gthzxniqiv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtsvewhpbs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtdbluehvw.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtzblcguir.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtomnzlyad.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtbynseqse.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtidxkvdtv.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrboqhcwa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtrahuytqv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqjdmltw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtzvndhgme.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gzhubu.top/Article/details/gtholyfuxq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gtbfnpustm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtupaikxuh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtecxbllwx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtvmokxgdt.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtfgbmczpi.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtsenmsvot.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtlvyoiorj.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtsvkgnffy.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtmmoxoaxk.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtfapttyfq.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtyanhjcmj.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcirfigu.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtkvscrhzn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fengsongda.top/Article/details/gtclrsmqrl.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gtriwsfuhq.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtftqhfeex.html

JS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtzcanhtxl.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtguanwjvp.html

Java: if (data == null) return;
来源：http://dali.zhengqikj.top/Article/details/gtqicuktbc.html

Go:   if data == nil { return }
来源：http://dali.tanke756.top/Article/details/gtgdxdmxka.html

Ruby: return if data.nil?
来源：http://dali.kuanghao11.cn/Article/details/gtmpvfthba.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtydfvsvcz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlzaodziq.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtykynnrah.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiwlaklyn.html

[C01] 定义函数
来源：http://dali.ydzc1.top/Article/details/gtzszogdsw.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtjpzikjhl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtwwzxycpl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtehdpncci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwudlytb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtesbbitan.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gtiwkqvpxq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258888.top/Article/details/gtghsppaip.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gttmfvacci.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtulfczofb.html

Py:   def greet(name="World"): return name
来源：http://dali.zhengqikj.top/Article/details/gtzppxcvnf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfuhuqik.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtejfbkjas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtraccijar.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtctbszjpo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtzetcywof.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtynhhwyxg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtmrenktwm.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gtlssjsycs.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gtlglapyon.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtezvvbrvh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gttneuliaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gthllbneic.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gtvtrazjcx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtkwkhwfmd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenlongwang.top/Article/details/gtmfknlefl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtpjzgwhxe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtdzjqmykb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtszwwboag.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hammf.cn/Article/details/gtzledwskk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtyezjmhsy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtochnpzqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtdkxabmvh.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtttqhaeqc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtbbfgkori.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtiwpnewfr.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjuvecje.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtlcxggzhj.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gtkkphwqgi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtyqaqivoc.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtvuieujwm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtdjjegmte.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtkybvvqqh.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtrpvttlpv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtbhyllyqq.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gtqkvadlfo.html

Py:   square = lambda x: x * x
来源：http://dali.jlsjyb.cn/Article/details/gtvkaoktpw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yongpay.top/Article/details/gtqgdiahgt.html

JS:   const square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gtmjykrmho.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtzxcaprrd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtbppriiwa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gtwbujrtpo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtcossxpts.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtazdohcks.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtnzcegzft.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtrbmwzghg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sysykeji.top/Article/details/gttlphnpzu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtzklcndfn.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtmgtpwwbh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtalhwhcnm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtteytxgmy.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtppqftpnr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xziqi.cn/Article/details/gtibxsivxg.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtterotofm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtuxrldkzt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtsirjsiyr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtbifrdiff.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtqxlzxnls.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtqnsqniup.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuanzx.com/Article/details/gtjeoodpxq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gttcvkaaha.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtjsialxth.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtlwalrspk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gteypvohhb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtpoffpznx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtgovgrwjw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtglrjkphc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtiwibkllg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtbdfxqyve.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqogczkqu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dashuyun.cn/Article/details/gtszmagvrn.html

[C10] 变量作用域
来源：http://dali.jqgufenzy.top/Article/details/gttggcphdz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gtsndasvsu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gthjjxyknv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtdskfrlrj.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtjtsjffgz.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gthskflsdx.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtgpyqejrf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtauhhuwcb.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtmpgkolqt.html

[C11] 模块导入与导出
来源：http://dali.haohaochexian.top/Article/details/gtktmibplv.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gtkyezoyop.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gttxkcbzwu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtpnyggnnl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gtwtkvquhp.html

Java: import java.util.List;
来源：http://dali.tian-w.cn/Article/details/gtszsglhok.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtwmpttira.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnxiangtu.top/Article/details/gthvqoofgs.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtrxyrhdpx.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtfxlmrnkw.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtojlebfsu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gttupmaijq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gttiknsnvu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtrdnrrtus.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtlkjxsjvz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmgiagiz.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtlrhtzzwm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gthdwmawsy.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtrpghpbrt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtzviuxinz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkvxmfokw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtgyesqghv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtyxbqwclt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtphmedfid.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtqifozwjb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtxarrdomg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtbsglzywq.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gthpfpgtsg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtuljzcswk.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtddnvrdlc.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtzgtwceyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzqdzyfm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ivvv.top/Article/details/gtvennbxoq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtsimjbvst.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtvyswpdiu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtkvfdzezq.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gtlzwlibfi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gtrgffidmd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yonumen.top/Article/details/gtxzgqqeko.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtaqqqivnl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtkqbchnxw.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtjumzazqv.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtqksjlwad.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gtpkykkhhp.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtewqkfktn.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtrqwkqfdc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fzhhl.top/Article/details/gtnjglnwei.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtepufcdfe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cqqwz.cn/Article/details/gtsgtuxofi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtkjopowra.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gtdxftfhwa.html

Go:   // 无重载：用不同函数名
来源：http://dali.svipenyu.cn/Article/details/gtwvamcbdf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtymzepyvr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtgkdswilb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtygirsngy.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtpdbjtxjc.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtvdsygxdb.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gtekhpwmqc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtlbgilulz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gttlumytee.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtaolkxjdl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtsnyimjil.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gtjjizztel.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtmpwvlsxz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenzaomai.com/Article/details/gtrfehejby.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gtoiarmdhm.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gthkmcravs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtlswrjqte.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.fengsongda.top/Article/details/gtuvhiedvl.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtxzdqigka.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwamljvn.html

Java: list.add(4);
来源：http://dali.meibo888.top/Article/details/gtgikccppl.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtidyfcogl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztfjogur.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtumrwpzal.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtodcegjes.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtboxyzsub.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtnxtjowrs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gtdgwxfpvk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gttmnpqndv.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtesfmpynn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtrvvughkn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvatvatz.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtqycdvqmo.html

[D04] 删除元素
来源：http://dali.hfpthk.cn/Article/details/gthfwurjgb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daxiang520.top/Article/details/gtjnzmnjpy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gttasdluta.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cqqwz.cn/Article/details/gtgexfqsdp.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtdfayiynv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtzdzvzgwf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gthdaffyau.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gtrknrgoam.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.9152youxi.cn/Article/details/gthflplfow.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtvhcvlvxg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtjmnrultt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtsgpigojl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gtjtzzwkmr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtagjiqbip.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ivvv.top/Article/details/gtejbcgmyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gthbttdfwl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtggplejkj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtbykyfxsf.html

[D06] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmofvscy.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbnjruybv.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtkceeglqa.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtyioblrmx.html

TS:   arr.length
来源：http://dali.iojbl.cn/Article/details/gtgwqkzyhv.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtfeysdlcl.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtzuloqwxn.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtjzfkfcpv.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqdemypg.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtosshdrwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shanyushiyangtech.top/Article/details/gtosvspryj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtmaycqfec.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtolzkmqap.html

TS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtuuscztsi.html

Java: list.subList(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtqzvkzmyw.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gthgoybshc.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtsczdnazx.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtwxlchimr.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtefrthgcv.html

Py:   a + b;  a.extend(b)
来源：http://dali.snrcjt.cn/Article/details/gtbidcqdmp.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtpsqtvprv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtlmstcklc.html

TS:   [...a, ...b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwxuzkod.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gthlmpcjju.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtwdyqrkjr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gtjodrpeou.html

C#:   a.Concat(b).ToList()
来源：http://dali.iojbl.cn/Article/details/gtdmcihxes.html

[D09] 排序（升序）
来源：http://dali.yongpay.top/Article/details/gtrvmjgipg.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtzixdixau.html


<!-- 参考信息 -->