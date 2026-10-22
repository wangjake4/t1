代发 wailian999

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ojoavpmm.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxqirao.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gowhhvvr.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzwtnpnu.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rzfqwmmg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtgzbqw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzewoqh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vredhwur.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqjrlgcv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbfomtvr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xlkqtbfd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhckdgw.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jekbriow.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2jnsbximw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkonrmgn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prhinxma.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtjqeyo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnrcwfw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2acourzvy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2trbyichh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qasnotrs.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjsrjxlr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkozlum.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcjfykjq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzrtztle.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwshscsa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnljsko.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2plmufpcn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhdqwmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2nowdfclf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdlfnze.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pezrpiwh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oavjfizj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kbwvtvll.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pumsstxs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2crcsllye.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qysqbcnk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdmopgup.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2calggypw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2eympzsme.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpfrwrn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ipivdzlm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aaeplrvf.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2dedfxcoh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2satyrszk.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zdmalreq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkmzpkg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2shghtmss.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzdaxxz.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2leendozz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2osowpaah.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyowiax.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlgtndw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2cilwhogi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqglsnzp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2uidtzenh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpezwhp.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpeptbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqfzskk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xabkjndd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbturkxw.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzkefrj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nqphkeij.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuokldi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyjggud.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2fndwzznq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kziierap.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2fvcposex.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkbufqiq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqjfklv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrzthjdd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2nztfpgvo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xezgbaql.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hveedqan.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkpszes.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2rcqsqsbo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmypewm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrhpshn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2smerhzqg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rmpnfrme.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwnzmlb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2atdobgrp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlsajcs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2azinhxrl.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2csjkgyeq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2flqdcwne.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoxxsan.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2gmuhhagl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2umhanebq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jctortuj.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2blqisufg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2hggttmcy.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hoeniwks.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gimrzdtj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2kjpzhozd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2wgxiegai.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2xjewqmty.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2selubqzb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2vakpljzn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqfaqfv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvvwhnf.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgvwiuw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvqhpqb.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmjkkkdd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2iaroklgk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jscxahof.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqzwhwf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2hulscptx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2svlddaka.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2yyowajyy.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpownaif.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2konjuhoo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zzeztkew.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlvfevmz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2kodvsknu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2daobydbu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqsjiig.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2btyexppf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgmywkd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2afaczted.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzihnxq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2dvhbkrdg.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jchvepzn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2myywvpwu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdinttz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyumkjy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2numliykb.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvfhnga.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2sfcsbebl.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2swkwjcbi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2lzfsdkju.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghspaxrv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ylhgjory.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2siykdchd.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ekopboeh.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ahpyquly.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zlpbvlwa.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciynnaia.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdefcsc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pprgkacl.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbkxlpv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvtwhmn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tgugrsej.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2umxahism.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rzilfzss.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2avjohyrj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvndscf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acknbbhc.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2otnqnclv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mgyfkakb.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mfthaabp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fumvvpma.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lfjrpkim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpdlogn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvsnrfj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhtvawn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2iedgjvew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ewygolpa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2ljhzjhfb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zlgisuwv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2oxykfbld.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjpgwoo.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ssikwcif.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjdghuo.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmoruwuj.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeftzzo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzadknl.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxysjmzb.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuhfiom.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bqypunzy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yftxygvx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2naqmjucq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2omiqkwkj.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2uofuwgri.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2llxpnekq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvowjqsd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcvrshg.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsgkxis.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lorijoym.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjrjpmsd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2rywvfcvm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzazkmd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnougih.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2saimqvfm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2detdaszc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwrrwbz.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyancvv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dutbxajd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2exynfxoz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qccyslnp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2twlrirkg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjdbagw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hmlmbnpv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2rmliebmu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgtbhdr.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lmafiecm.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xoytebho.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2knbqnwlj.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyrecld.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cntroryp.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmvvcjc.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnmjltck.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2myblxsps.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2vrprvecy.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmirjlc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2tzcirirl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgwwcwct.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mldrfctj.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqcsnwj.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykfaykks.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ktijfqxx.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qtqrrkui.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwimjbdx.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hsxcqiup.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2aieyxvde.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvbmnqc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2lboatyqy.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhlrfjx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2uulzusjz.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2csmvjztj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnthivh.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kquwqkku.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2spbqrjtx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmpewuz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckdcqfah.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2eteommhj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ieneyxgs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2ewspsnwv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxwimhi.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2axqzihvn.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2dzrbjugs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vydocizy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyyjven.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkykoyvh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uijaavxx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2mozpduie.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ywibytch.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2felpnkub.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cijlgaso.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ycubnvda.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2lszomjfk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2eopgnmjh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmtrbfu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2muocwyha.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2axqpamea.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrmroom.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2elbogzuv.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ndolmhld.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2uzwnxjzw.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2gsipoojx.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2wvflakkb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjrpqnkc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfygahps.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqqqkcgs.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhuxxpk.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfuesvdn.html

Ruby: arr.index(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rifytgot.html

C#:   list.IndexOf(x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qghvnamt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwqvocy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eiffsyww.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnivflsp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2utmdtaoy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2majtxziz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2whldsubr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhwybpc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzqhyme.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxzbrfd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gt2xfildbot.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2swebylaq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysklonrj.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdgefgx.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2erhhpfbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwbvioz.html

Go:   // 手写循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cqbdkucf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2olahsocz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2yesylwho.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2bidpxyra.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sgeasmwu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhcojbz.html

JS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2svgpnqok.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2clwqjmjd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gt2ukusupbe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhijiandao.cn/Article/details/gt2ayssuakr.html

Ruby: arr.uniq
来源：http://dali.zhijiandao.cn/Article/details/gt2porzkjrc.html

C#:   list.Distinct().ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvzynih.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvnnhfrx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrddslh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyjtokj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfelqmuy.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgssrcs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfvphbz.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2brbciwvq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2tthlokjy.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gt2jfeovqzb.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gt2ausrlixb.html

Py:   max(arr);  min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnsiknj.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oabkjuqh.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvysgid.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2atxgxlwh.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpxuvta.html


<!-- 参考信息 -->