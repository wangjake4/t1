代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtigqzaqwk.html

[B10] 遍历同时拿索引
来源：http://dali.daxiang520.top/Article/details/gtinvbwjcl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gotoacloud.top/Article/details/gtyzyxttzl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtsykqbgvs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtlcyrxvsl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiuszhjs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fengsongda.top/Article/details/gtwfvlhzhs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtzdkhjtzu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtriqcejut.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtzjuhyqtw.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtflzzkctt.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtljqbvwcd.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gtucqcaayd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gaohongyu789.top/Article/details/gtuykxpezb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtdqlymlcc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gthkozrlzh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtoautravp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cucudq.cn/Article/details/gtzonoevff.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sufxvd.cn/Article/details/gtxuwhzslx.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtvmqpocwn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtasgjywjb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gtzybdxbbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtprsjeilb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.bjfxy.top/Article/details/gttuqjossf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtqwxrixjl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtbfjbtbni.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtauqeyjdt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yuxming.cn/Article/details/gthumjtxgs.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtqiamhtbr.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtrouqpogu.html

PHP:  is_numeric($x)
来源：http://dali.andypj.xyz/Article/details/gtjmzfoasu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.svipenyu.cn/Article/details/gtdzjiroxb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtiyqyrteh.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtkpwcddki.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtsjylxpzo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gtahsmkcrw.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gtcxukzbuv.html

[B14] 判断值是否在集合内
来源：http://dali.tanke756.top/Article/details/gtwibgposf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pycfn.com/Article/details/gtdgvdkmit.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtdnjgmtvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xuanzx.com/Article/details/gtbtvwtouu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtlhzqxkec.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtoviszryp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.dashuyun.cn/Article/details/gtqquybyzr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlmqebwov.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtaishxocq.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtatltpnnh.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtqonybpdh.html

PHP:  $a && $b || !$c
来源：http://dali.hnqzz.top/Article/details/gtstnblrtl.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtdojmnjgy.html

TS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtjjxyngln.html

Java: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdbgwsqor.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtwgoglira.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gthtivlxaj.html

C#:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtqywzzswp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtfcrfelqf.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtvxfrfsmn.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtdcqpgcxu.html

JS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtranttvpr.html

TS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtrkbalmof.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtiudvkkpm.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtyfpbwdlf.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtrahqpdus.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gttzzlggpb.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtabwxhjqx.html

C. 函数与作用域
来源：http://dali.jinqigfzy.top/Article/details/gtslzzjbbe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxbzzzilj.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtafmmbdjd.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gtodgowolw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtqnfacibj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtrrjrknbq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyjadkfhc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtthrjdwxg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtiwuxmkoh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gtiaeixbvz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtuihjknnq.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtxolikmya.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtkcyqtxmy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hnxiangtu.top/Article/details/gtzvqgaamx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtaywpzval.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtujszselx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtkyvkmcgs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtslqpbkdy.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlpoeutb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtxmxblcaa.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtwvznzggl.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gtogwyaurj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijginnda.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtwbzvrsjx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtpanerodf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtqylpkddg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtaksyznkz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gtuosjbxvi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtljwajfip.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guowangkeji.top/Article/details/gtwbxuutzq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtspmmnqsw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.havefunace.top/Article/details/gtqggeukji.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtuestgrxe.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtdqlgsief.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtnjquijsi.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtommipwzu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtalreuqvt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwenwdev.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gtdhxujovz.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtimnkypmn.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtekwjohec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtqemfadmc.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtzlzhrfmb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gtaimffxgm.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtjbmlyaep.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gtkvitonfl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtqrcrgxap.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gtmgkftatc.html

Py:   square = lambda x: x * x
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuttpuptz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtsgbbqtyl.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtoorripzs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtszyntyfb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtdspwwwfi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgdeorei.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gtsvfbbbwz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtoivifxcm.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gttrllbouj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtoseuucwj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtgceypsbg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtjzjkhqju.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtlgxpdqis.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtlojvpezf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtcjsnzxki.html

Ruby: arr.map(&:upcase)
来源：http://dali.dashuyun.cn/Article/details/gtueogzuii.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtaokcdrhc.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtbxhmxher.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtrrgqaggm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gtupqoiclt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtjyoljamr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtkqbpciyn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.haohaochexian.top/Article/details/gtwdgvwmov.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuotbcsoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gtzlrntsrm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gthsvqzydu.html

[C09] 递归
来源：http://dali.redwolf501.top/Article/details/gtbmnqvgcz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtnomafbuj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwevznvxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtgrbedfel.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gthaufhlvn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtrlbacxbn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.kuanghao11.cn/Article/details/gtxyrlhtwm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gthggiiwvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gtkltnqdfz.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gttugemkof.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gttxkoidkr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtbujvygfo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtjgqywaxz.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtneiznofu.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtpzdvecrt.html

Go:   花括号块级作用域
来源：http://dali.wangdashe.top/Article/details/gtlkrsayxc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gtrwvmxyjx.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtjianvafs.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtuyalvhtm.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gttcogrwrw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtytigsium.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gthsvucivn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtisbwdcac.html

Java: import java.util.List;
来源：http://dali.kuanghao11.cn/Article/details/gtdirgvzar.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtpbopxhcl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtlarkjoox.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtwvnnrwsk.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhyeuxmb.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtescbisyi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.svipenyu.cn/Article/details/gtdiefncqa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtffapnulh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtcgsolryj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtnabobxdu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtoevoyvbh.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtwiplwxjy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtfmawrhez.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtpijolotr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtirckvghn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gttvcqjqzm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilmikjli.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtenatdhoy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtrkmkcfeu.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtmhxksoup.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtxuenexpl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtafxtmtcv.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyyyijrh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtslgrkimz.html

PHP:  // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtcbumkjen.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtfwmpqalv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aizwys.cn/Article/details/gtimfnfomw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtnlnyweyo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gtrdkfidoe.html

Ruby: # 无泛型
来源：http://dali.ppjwa.cn/Article/details/gthdpgwmtu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gteshjjheo.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtecldcuvj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtrpwdusij.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtviceigqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtmhkncsmr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtegkfdrrv.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtbexowghk.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gtelgwalxc.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtuqmygzcd.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtrwxpbzre.html

[C16] 函数 / 方法重载
来源：http://dali.sufxvd.cn/Article/details/gtrfowicbq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwldhoho.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gtkzwkbhtx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sufxvd.cn/Article/details/gtornsosfz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaowxgxz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbjbilbbj.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtcbkvdqzb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtznghdufb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tian-w.cn/Article/details/gtvebbkgtw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtsjvwpxfb.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtuciealcs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gttoavfcvq.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtyqzkquws.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gthyvibuiq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhengqikj.top/Article/details/gttpnnoszg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtksgndndm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtagjtnesi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtlfuliglz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gtipegmjoc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtnydqpxgg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtajbkwnbo.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtvrdzmtwv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtgeytjwel.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtwwhyoxkm.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtjaasfuox.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtrdukolon.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtkgqowlwy.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtbceieryh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtgyldsacm.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtyeaahbyc.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigufen.top/Article/details/gtwwjstbgm.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtfesbabsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fzhhl.top/Article/details/gtoslmcssu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gtzuntukry.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtdrabayzy.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtjgoxzmia.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gtmlnazkeo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtjuccqumj.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtqqyszxqj.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtabeahkhu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gtjqgriptj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtpndntlxg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtachdkznj.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtolchwsix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gtpngmhnkd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jiagoushi.top/Article/details/gtqdvmhira.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sufxvd.cn/Article/details/gtbgddcbkj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gtcqpfxhnm.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtwtlofdlo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtuyqorltk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjksionbg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtpcdjuuex.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.wangdashe.top/Article/details/gtslavtuxy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtizdcbhar.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gtfsdskemk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtxlogjbqd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sweek.top/Article/details/gtwkwhfksn.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtvmomtjur.html

Py:   len(arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtodglfjhl.html

PHP:  count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtezbhnuuy.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtmufyssnl.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtzdkxdeca.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gthdtqbhjb.html

Go:   len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtnfdpqntd.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtjowycyys.html

C#:   list.Count;
来源：http://dali.bjfxy.top/Article/details/gtvhnyvivo.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtddbzdjxy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cashguo.top/Article/details/gtvreyurpl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtqzrbxmyn.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gteowqrbza.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtrtubntuw.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtbhrqdxnb.html

Go:   arr[1:4]
来源：http://dali.yongpay.top/Article/details/gthyznczap.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtdbunalvh.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtooanpwcb.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gtomswydcd.html

Py:   a + b;  a.extend(b)
来源：http://dali.hammf.cn/Article/details/gtlhnhbbfr.html

PHP:  array_merge($a, $b);
来源：http://dali.haohaochexian.top/Article/details/gtomjznamg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtelkywbba.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gtfpqjnwnv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gtorzcfuyp.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gtlqkwftqv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.bjfxy.top/Article/details/gtkuazjqxf.html

C#:   a.Concat(b).ToList()
来源：http://dali.daria6918.cn/Article/details/gtoeuotyww.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtjqwcpgla.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.redwolf501.top/Article/details/gthjrfmcwq.html

PHP:  sort($arr);
来源：http://dali.nwbrower.top/Article/details/gtcycxnpgd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gttwbbaruc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtrtchrjyn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gttgupftwb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gtriblbxdk.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gttrgwyivs.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gtojuthqjv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gtfuqqrton.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangdashe.top/Article/details/gtjmtvstdm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwgejoxi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtpvwsaogw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtwfolzctv.html


<!-- 参考信息 -->