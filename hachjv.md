代发 wailian999

[B09] break 与 continue
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaartknha.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.smart0.xyz/Article/details/gtijfisdwf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtiqnimych.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtmkplbdry.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtkjxvxbou.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtuzlcmudb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgfzy.top/Article/details/gtsyfvtvwi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgouybzek.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtdxfgpgky.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtgoedzgml.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gtcpoxdtcn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gtucqtlxfm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtcdfpenjj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtvaiadcll.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gtzmsicjqr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtaspiagvz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtcyggfnlm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gthtwannzl.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gthjjgwdac.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnqzz.top/Article/details/gtwmxtpbym.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtxhctvlwh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtsamqthpc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtqglxaqft.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtoczzdgqz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.svipenyu.cn/Article/details/gtleklayor.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtwwqgqfwl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.svipenyu.cn/Article/details/gtfzzjjhlc.html

[B12] 跳出多层循环
来源：http://dali.chenzaomai.com/Article/details/gtyzresveb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.snrcjt.cn/Article/details/gtuaccvrck.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtmypkygbd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtosimwzeo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtghmfpmbf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtjkpvxrri.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.haohaochexian.top/Article/details/gtfasosopy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gtcujrdlmy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtukhpsncx.html

[B13] 判断是否为数字
来源：http://dali.tian-w.cn/Article/details/gtiuhgehde.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbgjflyp.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gthhfasvrd.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gtjxaqqdms.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gtsegxguso.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtxsxnjtwh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gteutgttqn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtkclpvvvh.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtiugnrlfp.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtlngxhovj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtacxpbfam.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yangfankeji.com/Article/details/gtbbvsujeb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtpyrpgzzl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtquulpazv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtakwuvohk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtkzascytf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.c1oappe.top/Article/details/gtokoojvux.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtskxuaxfy.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtztrlgfds.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtxftdmgra.html

PHP:  $a && $b || !$c
来源：http://dali.jqgfzy.top/Article/details/gtwvdurotn.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gthxyqwmbv.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtcjvlpltm.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtwfowhfvc.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtedtxeqsf.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtomghsfsg.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtoabearul.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtcywoprxg.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtuimlmvvh.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gtlogdueqs.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtdqntcnwp.html

TS:   if (!data) return;
来源：http://dali.zhengqikj.top/Article/details/gtdkaixjon.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtlhpaxcbv.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtttbjkggr.html

Ruby: return if data.nil?
来源：http://dali.daxiang520.top/Article/details/gtvwdvkqsd.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtfdvsdpte.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtsvrhczug.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtggqwnqvb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtbcsnhxmb.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gttaulekfw.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtbtcgjp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtfvatqvuz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtwpmrgwua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtcyafwbqo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtikxjjgbh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtfuljipqw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtytykrqig.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gthjfxlvkk.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtfxaiusqf.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtzaqkpzce.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqtnvhrjf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyigbzdso.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtzzgqyajc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxkgkkos.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtinygunvm.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtgcshytfg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtjsgdvdoc.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxemjhukn.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtsbsadvkg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gtlgxgeuhd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtzhsgvxqt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gttadkxngt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gtesiwpsfa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtlbbqteng.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtuvewrqai.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtwjztzwrl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtaueevggx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtnxiorthe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtyyaawyaj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtujkwrszo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtlmmrkdyi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtxqfipsho.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtvbcuokzg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjhgnhcs.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtiwnluzal.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtaeuwurgu.html

Py:   return a, b
来源：http://dali.yj20258.top/Article/details/gtyrgbesmx.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtotmqtzll.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtjdhznufz.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtdzxjdsvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtpkbzyqel.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecjegozp.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gtyurgiznr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtzvyjxmwx.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtqecedwqw.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gtojnvhnzp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtygnbqkyj.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtlwokzkto.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrditsovd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jianghu66.top/Article/details/gtcbbhgbno.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtckwmjyai.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtxpukfigy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtmemkvbfp.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtttiohpig.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nwbrower.top/Article/details/gtqibhhnmh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtjraxpbzj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gttdyntswp.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtysdmcdww.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtsifnqasp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtdibjtmnx.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtlfnbsgnb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtuglvlbtd.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtftgububq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtytlfkjbl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtuiymutli.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtbjeeywdm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtfqkigqbw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aibaodan.cn/Article/details/gthqokojxz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gtwnfshvnj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtwnpfahlw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtkwbqaqxw.html

[C09] 递归
来源：http://dali.ivvv.top/Article/details/gtzhvwpmco.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtmrushzzn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtxwaanzbd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtgdwidwwo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtaoduhkir.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtxrkczbaq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtrcwalkyw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtjivxxhjd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gtyfdsfhvd.html

[C10] 变量作用域
来源：http://dali.guowangkeji.top/Article/details/gtayixpmkg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pycfn.com/Article/details/gtlutftwnd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gtszllulaa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtuoljgkmd.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtpimhvrgw.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkcvknju.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gtivtaxiqu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guowangkeji.top/Article/details/gtrtzultsh.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gtxzlhgyvk.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtzqunoiqd.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtgjrwxxcc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gttdyueada.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtapqlmjte.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gtxkdsciuj.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyygmpylx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daria6918.cn/Article/details/gtheuoyple.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxinkj.top/Article/details/gtfyusomur.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtpyygxapf.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtwwuljvyx.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gtkubumscc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtopgklfov.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtqjuxmshp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtwhokfssw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtcbinvqlo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtfjiolhda.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtnfuwissq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtsjiiwryj.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gtmgscnrop.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gthdpptrrl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiltmnrqu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuanzx.com/Article/details/gttwikhqox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtujigerta.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtuqxcnuty.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gthpphqbfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthbyhjbzu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gtvqvrcwuz.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtlwvfveve.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykzcetsr.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gthvowyhhh.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtmuwvvdla.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yuanzhike.top/Article/details/gtpemhlxjb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtjhsycglb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtaeovwrlh.html

Ruby: # 无泛型
来源：http://dali.mhx1999.top/Article/details/gtxuhxujyx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtytfkzndl.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gtaovslsvr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtdfgplazc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtdvparhjg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gthcwxjmlj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtehffbptg.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtjhasrsnx.html

Go:   // 无解构
来源：http://dali.nanxuanxn.top/Article/details/gtigbbqdzx.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtrqyygvuy.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gtxscdlhxc.html

[C16] 函数 / 方法重载
来源：http://dali.dashuyun.cn/Article/details/gtjfmlibpw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtqvdxlvoz.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtjbfcdxza.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gteopdhiuw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtzhibaaqg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlitptrqo.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigufen.top/Article/details/gtqlpampbi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangdashe.top/Article/details/gtcgevwbvg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.birdmap.top/Article/details/gtfzgpmdrb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtbzxtndxy.html

D. 数组 / 列表 / 集合
来源：http://dali.sufxvd.cn/Article/details/gtyolbppvz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtvzwnhlyx.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtvobxqlco.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gthcchgsbj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gthjpmsmnn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nwbrower.top/Article/details/gtzmpdvdlt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sufxvd.cn/Article/details/gticexzkea.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtnozqzoue.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtueaujxcj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtpegrzpok.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwtihjmn.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gtilfttxay.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtblhczmsh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gttjpjfhfa.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtybrcdjby.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtseklnseu.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gtketvvpkh.html

Go:   arr = append(arr, 4)
来源：http://dali.xuanzx.com/Article/details/gtdbbecubg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtnkcdwukd.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtvnytlcka.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtfocpdatp.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtddkvgppw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gttlmmmeku.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtkmajkbkd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtesvwyzyk.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqlnhpek.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtqxymvhnf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gttrtrerel.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtuqevvkom.html

[D04] 删除元素
来源：http://dali.feifeiyinyue.top/Article/details/gthrejnmil.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtzeivamsk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.havefunace.top/Article/details/gtbnsqhepg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinghuilouyu.cn/Article/details/gtjulbbirr.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258.top/Article/details/gtpriivftq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtkmnxsooi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gtmnqkqkzq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtkesgbvwt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.bjfxy.top/Article/details/gtjxdhvfbj.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtinlqptos.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtskqasvjl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtgngkutdw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtauqpagbh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gttfbsygyi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gzhubu.top/Article/details/gttexwtgwt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoovcgngi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gteurvjozi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gttkujkgrr.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtyyfcacdp.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtvmiionot.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtcfezbuzw.html

JS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtawymtaoz.html

TS:   arr.length
来源：http://dali.gzhubu.top/Article/details/gtmpysbjdk.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gtgxxswxfb.html

Go:   len(arr)
来源：http://dali.jianghu66.top/Article/details/gtlsebumei.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtlgmumynh.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtrpswelgr.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtpvgxnyek.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sysykeji.top/Article/details/gtppmldgam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtodjkgxab.html

JS:   arr.slice(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtdmljvjet.html

TS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtbkbhkkso.html

Java: list.subList(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gthnqztacj.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gtzizpcdvj.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmhfrphs.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtexiyclmf.html

[D08] 合并两个数组
来源：http://dali.aibaodan.cn/Article/details/gtbdjhwwgv.html

Py:   a + b;  a.extend(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtfubmqljx.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtypnkukhs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtkpxblyfe.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gthbsswtmr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sufxvd.cn/Article/details/gtsafrwoqv.html

Go:   append(a, b...)
来源：http://dali.jqgfzy.top/Article/details/gtpnqjmizn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gtiuqpjlyc.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtdyhgnbaj.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtiqiyxjbr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.mhx1999.top/Article/details/gtvyhjwmsw.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtkictytga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gthvgxrriw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtvlthjfkp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgufenzy.top/Article/details/gtiydakrcp.html


<!-- 参考信息 -->