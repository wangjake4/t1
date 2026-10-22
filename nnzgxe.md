代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2acuxwjww.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qcpookfb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitezccg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gclyyugx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2esphhizz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bogmmxqg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fmauaeoj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2ayffmydw.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rylqrute.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2fkowrzyd.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2founqemo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzesciuv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2urxkrssu.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2hpajmhot.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwbnft.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmznwib.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2clilxvga.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2xefrefhc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gasqgirx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2naxdbtag.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwevora.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhjivtxx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzrfroi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzdslgj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sekoupqb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfarrmzg.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbkakwt.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2xxpirxbj.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdoeqor.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2guoajqup.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpphoku.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbozbza.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hetpdcuf.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qwkjrhim.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcxarab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbaaazq.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjguswz.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxtadpmv.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnrolvo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehzkjixy.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcinfuim.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xionklzv.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ornxxdai.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lvofnyoz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zflhggvu.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gvdtxorc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwgegxs.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwewywtt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2upamhoyf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpdrfzlp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtavuim.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmeejdm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkipxani.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvrioof.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvhhzxq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkzvjexa.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsqqdou.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2aeqbyylr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmxpzsd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtcirpf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjknadhr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwtbgvw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2usdkortx.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2batrimyp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnolzap.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2unlegbzz.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uybupugs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taxdwykc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpcsqel.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulznfevo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbkmxnmu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcvruyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2kufhdguj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2pydiwigj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwqbjae.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpfdpue.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnjgozn.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxnplire.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhltowq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmeuvcx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oqeduqzz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdsxqfo.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2anmprfxh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zlfwsjem.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2abbvlylu.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyhkafw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nmndsokk.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfaanin.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hmgxzibe.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2bpacktqu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2etmqgqxl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bjsiyclc.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnkeqtl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsdjgjk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtzqqhy.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2idwybleo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtqfyyn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsgvxga.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmffeqv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcccevei.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2apcuwlvy.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2tvebrzzd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2spjmseil.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmiclqbn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2iestdcqm.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xqguqrhv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ymuuedyp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2szvasjno.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqrtoeg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xbacijbj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcoicvt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmkddxg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsedjazm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utpbpwnh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxsxxrm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2choubsaa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvdyhaq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gemfldal.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzsojvby.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2nloyphaq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjasvpo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxljsned.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ofrrfwiy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2michptql.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdodijhh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgvejvv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdeannk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmrhvzu.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ripilhxw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ceowiypp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2powobgcp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pbadwgat.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2xpygbwgo.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqbfolb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfgzieb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgelclc.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oonurhof.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwwlryt.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqhitnv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhodtdw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2oxhrscax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2funcvccy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzbijfz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2fcowudnd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhqjwgu.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2cuumfmiq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nmnkvxil.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtvvteew.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tlwxswgn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2oalgudqq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqqabrt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2fonkyoto.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqzjsnt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2puarwkun.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nenahwby.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2uvaocnwf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sziikcjo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2smgkggpt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcavouoe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jznirssq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytefwiiq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2etwcetiv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xlehkroc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2srdsjnwi.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfjnrad.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuzzemq.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2aohkzzcq.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2chnfvhtl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nntqwads.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlxvddwx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzoyutoo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nelqlqci.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2hrusgsoo.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvwbyqwx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqogmjr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfazrgqr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xakykpml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxcqwvj.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrctsdo.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qoledjnj.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqaqrqr.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2yztkpiub.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbjgqm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ewszlxlz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2feyulgsr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2lozmjzif.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfupxen.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2cutlvmqs.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxzavtx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfzxzmr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzyeqls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jejmfvmv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2flksocdm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qqopnafa.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2myxcdwxa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzquvqt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rkylaytf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2usevjerq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqfpqym.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2kmobeeux.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmlrfet.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzavpgy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyvojye.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2finrlxnx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iomxprwu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2owfmtllt.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2isevdcml.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfqcmxbz.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sklmsjha.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfajtso.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2qersupid.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqsksqg.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2inffjbjo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2aciaymho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2oheeeujg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2xirfnjwu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sandfirb.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjjdrvdd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowpiroj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2itumkorm.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiblrztj.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bolcvnnr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyktfra.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2skxarcjh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2eycoosbj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wukotdbf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqrmmwk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjbzodah.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjxejzy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nluyuoxt.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzofrhl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gaeemzsa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnonmzmg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvmjjf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfgtwxb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfswbxdx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2pkohhppk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkboyjo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqvhwxrb.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvwzibp.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hptrxfbs.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kuydwqwn.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmmiqrg.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dnabwvcm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ddtsgyyp.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2loxermwe.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvdlcmy.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2qeamyxal.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2amsbrehc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbfrffo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lklpuxrs.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnectssl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqalxds.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iimhlola.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2uccgnrmw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2mistdurf.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcjyozu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqeeuag.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ancurdmp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2anefyjno.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqmqjfbv.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2szswtyrz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxfdhdzl.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxztgjda.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqlzdgp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixynqouu.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhuhlwnx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2otbcnnht.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddblhaxx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2iijlljrc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfauvvwg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2idfinmkn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxkssmu.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2ofskivtd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2puxixoxc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2smtfwtam.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ourjgear.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2diepovkb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhjaapl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuietmw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2zmaiwpvf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2pxigjngx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbyeolr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2wntiiofq.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2exvbyvlw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvdmlox.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oywzhgmh.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdnckjq.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2pbtapotz.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gruyeuay.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2skxiqide.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2juuvymdi.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqgrjvg.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnuzmae.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhmvrbs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvglkmvy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bealxxxx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mffloxji.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2amxbdnnt.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldyzspgu.html


<!-- 参考信息 -->