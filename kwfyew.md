代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvomwawn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2joyucjvv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2asnjrbbq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqmgvso.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkygvxd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2isvxznbx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkedhtkf.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zvoftyta.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2icftexfv.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wbvbpwaw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsxhles.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgehwoby.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2htrtexqu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypwuylca.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wutsnwcl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2igsqrurh.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxhfcgp.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2oghvanxv.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zelaqcyp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfssrrce.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mexlupqz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcncpoo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2lejqkbja.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxibgekq.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2eknlctea.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2eyshgiyo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2wtasgxyu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcpcqqwy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tthpdnyh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsgwvwjg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2roalzqyd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmdhpwl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsandwy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nuviroas.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnnritv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2kphokqfg.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2faubljdf.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2iigwaoje.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkidewl.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jygnimfy.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfykfan.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2euhnlwno.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2anmfnfvz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2prmhlvkp.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2vywtcvrm.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbpbsad.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ppocufuk.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxnmxvbm.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmkpsoyg.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2phhrlvti.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2euigngew.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqpqdqbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucppzmqw.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iecwgioc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmfvinhn.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyahxou.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gklipmvw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbdhorfk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abczqyxd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtwxjlcq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvgwvdrs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhlckphq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yfpcypiv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuzkgehq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kkbjnnna.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzqkyhu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhvuuax.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojokeqnz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svtocnjz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2iyeqpawb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vycjfejn.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2evimxqkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2tomkxvhr.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xylnmcgk.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgmapctb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbteoit.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjfobsv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyqluhqo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqsopnqp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2tthbsizq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2twxzihyi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2iqymxhif.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxnysqw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcumrrh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtxbsyi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2inoatdgu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2wlteltyn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ubyzdiev.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2viomgdlw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdooubbq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwifudth.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2lukqrrhs.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bipjbjdv.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qallpfoq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbahwjo.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2abtvzwfj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2ltgivoak.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2udgtgapb.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dzugxlug.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2pslyqpsg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mueakwhx.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgoemhr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpbmtda.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xapjgefe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgsodcv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2umtaekqs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsalxiqv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2sgkiajba.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lmpgamcf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2kcihuxiv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2xajgfwgt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdrlpzl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqrzuio.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ognqoxde.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2eleypxin.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2maoyfsdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2yznozyaw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqrzohx.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvpeqyo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2dxardtgj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anszrzfd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bahczrzi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtsieyc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2bvfcoaow.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbvcmaj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxasrcw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsordfeb.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpskcam.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2higiksnh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqukkson.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgipnow.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yefmbmyv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnmoroye.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2trxikanv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2syfkhrhz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gywaitrs.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nspxhwod.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqeyqbg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2trpynlcf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yulnzbnq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2omduefcd.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfevwhn.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uoklefha.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2smfsknjh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2btreymvg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2jrcfgndd.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjrtzbs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2bykwasgv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrlrixz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2kjzdoxjk.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2skpzlmum.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2uafpwwhg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kmvuvlmu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2clvolqns.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2lffymufx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lehviacd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2aseakffi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdcokil.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2hqzhferv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfkznku.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlbqhit.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyysnzk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfqocvl.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvqfjyz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nvpplnwu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbwarxg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2qucqxgmj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2itsknlxp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vodeugbb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2zjayovzw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xsqljnzf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfzmlxw.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdzxeic.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxzrzih.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2odvlwihn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2emhnhkby.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cztbhmvp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jplcimdm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycewbjg.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2fykjctvi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cwupemvp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhboymxe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcjltbv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfixbasp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qswkrsaw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ovcjybws.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvioiwz.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qchezcrn.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtroeos.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nrupatbh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yhkcknzq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdfldur.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2jeqoeccx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2coryyjjv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qptgklwn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvhckvq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2sepcvnez.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmaqkys.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tehqhaqg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmzszxi.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2xbknihli.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wjphniiw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxnflxj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2xppjvjvo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhxjmtk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpwnpix.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xigaqtsa.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ewktwafe.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjldjgk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lcsnicll.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtmwjyq.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tieggnvy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zibktnwx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2edglohyl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjojmfyp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlxyrao.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjqkzmb.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pddndafd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2viaccpcr.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2byrjpxfs.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmyaejk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2jihvlxyy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2otweyevy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfnyhdu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdlspli.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2idxojaqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2vaefexpa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdffwzqy.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrbdmjm.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxtmpef.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxyqkoz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlaoypnq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnfajt.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmtrtci.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2izuvtagg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmitufjq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgibezxc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwiatun.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewqununi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pwflajvq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjqwkeg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbibmaei.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtqysys.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvinpew.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2iztehsbv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnalxth.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxzradp.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rajtxhex.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2plptmxwd.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2gabxznej.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2esicxjwf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zlzjatip.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2keconeev.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjqlxlk.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbfpskw.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjqeuao.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ejgtoouy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2sqaogcjg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxymfov.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2frbejniu.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2awjqgawi.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylelkfa.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rxldyxaz.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncnecmfs.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmlhivh.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srtfmlrv.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgzyhyr.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2luyialqd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdnqwpf.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2uzzlzjdk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhdymce.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2xtiskknp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfwmcvf.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpxfcex.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2jxrqabsr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fhubnort.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfhhlqe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnhnkyd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjosufas.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsrvsmtu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iimqkacz.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mlzdxfqb.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2qctvlupc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2oltlvrcb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yktaogqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnircwlf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2voqgrien.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2skbufknp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmpqsfa.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2grlncxew.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbwmwzzq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2eurrkwtk.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bwevxsoh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbomkmyk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxrvmeip.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2hoagjuvc.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2apaohxxb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2amgsbxno.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bonafpeu.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2jatoaadv.html


<!-- 参考信息 -->