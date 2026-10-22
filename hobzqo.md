代发 wailian999

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyudvrd.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqshtrl.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdljarxt.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvcgdcl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfjbfmx.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2kirjrfbn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqhyodo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnnspjpc.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2ocetrusn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2wnznjtzp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcirenq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqujztlb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaqrbwe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2plavkqoc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2voacqbmn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2denskvvm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzzvhex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrwjpfq.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrmsrgd.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfzjbzf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2oycjmulc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2whwuqhgm.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhrwhqw.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rpatstcx.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2srzazmuo.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gotyujca.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yqomlwan.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ndysenkg.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ampkjycf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsycakm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhqsxmz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gaztecud.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgsmulrg.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnwxgjky.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmwxtoi.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykvzazie.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zgeotxjq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vinvcgid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnnegzzj.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2absiukty.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2esdndlds.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdpubgc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2coqazswx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkenbumt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nifizxvs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwpticeh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2prsrxfgk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2emtsqlly.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2htkqikcq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2peebqtjo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2crrymtdh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpxhfdf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2naoyglrj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkdqvei.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2edbgidze.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2szzmxncj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvxhcns.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2naisefpc.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhtnxtj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjmmwrfd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2htomakej.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifkqgjvv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2evwarloe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntlatmlf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcxhkujr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2klzpzafy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpotveb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgtoava.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pckvvgyb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ywrwgysf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ubkdfyvf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvrvlhw.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2guildmxa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vudzdjgd.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xiyypnhk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2feacsldt.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zqiumuwr.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqohwmf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2waoxqlnt.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqnxuka.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2niyboscr.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqpacta.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2owmlhukn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2gojukdkp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cirongek.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2bevnymbm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tctduvcm.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dejreder.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2judhirac.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzhjfanq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlqpixob.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2peysjony.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxfppnq.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2dachcicp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2wfsppach.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivxvoqxg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2bscfyypq.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfamniv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2myzbhzfi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyihhtn.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsydtzl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fmtpqzus.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ldufuepy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwaqbyj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avnxlene.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txjpommn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knjbigqj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2kypinsrn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjesdyto.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2opymnhyo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zilqwnon.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2elfwesep.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxvncqx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaxwlsn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2pzcrpxbj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vmqabwsl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvphylry.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwypdnps.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfgodpk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjygkkxx.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gctotkzx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsebnyc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkgtuyv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2zkklumss.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2frzydcwj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2aynibenl.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2extoqckc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2bsgcoibw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yizipucg.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2cboxfxfh.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2ussqnxly.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2eobykmod.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2yeddwxbn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2itlqoyba.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ndjgjiro.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqrcrxu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmonzhm.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvgsyfa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2jpykjpqx.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwxtqmt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmstqsrh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ynogjqgs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2rtktobzt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzcxowk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsjmvxs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnbwzzm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfudmqi.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rahkxwew.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzxfqbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcvbpyzs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kczqzpos.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmiawcz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuogqnye.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2unzougca.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2dzloawtq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2moweitnj.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoqgigo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2ngscaoxx.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhwldsh.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2sylqsunh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyvuexkc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgepsorx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxyueyk.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcuurtv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2htuvcudi.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwismsd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdwikew.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wevbqrwo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2peuervqw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uxxzcukv.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2iszsavzi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjuireg.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgcwgia.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdnydmj.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2opjrdnni.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvpnawz.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdurloz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ekxhhowd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tomtxuiq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bibkgwfd.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjhtwwq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuwlpez.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gsuinykw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yeaxfaim.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vknfretb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiqxepm.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vyojvjtu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ttavzrgn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeliugf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhegwxu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2alytthgm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxxujma.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2aasngzrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2giddndfp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2yljkruuu.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2uchinonv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2dgliagsw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifporpoo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsuqkrfo.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnkczriw.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsftvyje.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zpdckgiw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2smjpoqbu.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2guoyubfc.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrsrlgd.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntjladr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggqsbcql.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2gijpridj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdzapmu.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcgifztm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhtitjw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmuczqk.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhadoysy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2orwdrzwl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdmskky.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kduqhqrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2pcphhzff.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2glwfuoot.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2agkzdoth.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ownripng.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xscuxmor.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxierfhs.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iebeypce.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dhurkwpv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmprmwuw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2grlhsxrm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzogmrn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmmkwtjt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxvoiys.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yugfvnkr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2urkehlzi.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tfxywmme.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpifaas.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsswkcs.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jbasosmd.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fjrnoapl.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qeybueoe.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wglngcsu.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwmzloc.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptfovzlm.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2urdehnen.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tuzsprig.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkpiomh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndiicnny.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvnwvpvg.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uplagqif.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2wggrekdw.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyretxdi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbtxixc.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2mefvnhkg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhrlsev.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsukvnau.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2txzakeqa.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2nxrfjlxh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjswozfk.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2crtkhjup.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnkkoba.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2frdaqqts.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2netrjkls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2uhynlcid.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fglxpjlx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wwnrmyoa.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebdmemzi.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2anjodfnr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2msnytzsb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2etbkpudh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2difdzofo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2updlgfxn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bipdtzpk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wdcmsnce.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfpkcuek.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqbwvtge.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2luvqrjio.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaarsfv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2kputnqra.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2douqrjwu.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xonhbjfa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqqupvn.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjngxsds.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2owuajmti.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gamipfca.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2krvozxtp.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqeovvw.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2lndkckxe.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzolevr.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeddjco.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2voneptux.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2opauouys.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2djtcfokz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlngost.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2bybualwe.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxquwfaa.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbecvlkp.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmpuoek.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjdejik.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2aqleavzt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psxzdorc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vblcyygl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmnumkn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqimvhma.html


<!-- 参考信息 -->