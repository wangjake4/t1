代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnteeho.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcflhee.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2eodojnwu.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2alumzfwe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2anxxpwxw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2siggzlob.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbznrbki.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uicjdstx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igftpjmi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcsqtud.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2akmougpm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2yovyctgn.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kxsccrfo.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcpqblq.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2opfmaqfp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyejkvt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pacvoakw.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2awnikaid.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2tphbrucm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxjeawx.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2eywrdmen.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2orhsrupi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ljrxgwnp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbawjqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2iskesldd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvkjcpq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2itprtxtz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2flhdyajp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlreoke.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftanyixf.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwdoemf.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2qfugatlu.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hkiqbgbr.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2extjlsja.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2khhpgvco.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2otzywpxi.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rujnaunz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2mfttxkrf.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zlsocxxe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdoltkj.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2buntrjrf.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvrmenn.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbwqdhs.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wtggawda.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2dkyttzyj.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hggjsrim.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmsdmwh.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjomfvhl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bkafkila.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mfqklvqp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqpgynq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hndzryzz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2woldqsvg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdyvpme.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnesmhp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgevqzu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxosftwg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2heeqqser.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnowzqr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfpewya.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2etxoilhu.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2llifeikf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azfqbsgv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbgyjzp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdmelcd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2chsfpzya.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2htdkvbjd.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2fmndhyww.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ognasbky.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tgbtrlmo.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2drllnygi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyczbri.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2eubkgcgt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfauugq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxcuccx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2zisoyxwe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2salxuxsl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2mmllkdpo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfqaghr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pymhrbsj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvkdvyk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2oflbbhqw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2oovbvyne.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxlvony.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2efkvfylu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdmuqyj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wncmnqzc.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ryepvoub.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsbeuyra.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdestlr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2ninnhmet.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pepdklpm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2irrvrkts.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmwllyp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqdymex.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2jpnqarct.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2taleulfl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2zltukson.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aupfpxfq.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2txgmbylb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2luwdelxk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjdwrjy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouzygntc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2khorqdxn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnuskis.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaiwnek.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2elzkdidg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgwukpj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2csiktehp.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2eegbxnhj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nolxfgzc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2vrbnspcx.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmwjgyo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2svbzxnaj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lsljpayj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2jenlrmap.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2usyaohnr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgepfmvu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yftsjehw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhkgdgk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjqyhgf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2msgsynjo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntckewdx.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2hmoxthmz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2npbqvnmj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzpxwkz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rfeuzfqb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2djadgdsa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cslrqclu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmndzalm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhtriiat.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2scttdyov.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ajohrhjq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdcmhll.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2flzbysbd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbmehq.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvswqpj.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjpcwuu.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wyazauyf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2atscvbws.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2axyifeng.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2hvojubor.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2tlplxjzr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtszrzgv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2unapqmvw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2adseurfy.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvuzhix.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmvgiwl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2nixgemzc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhnvstwp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzhehie.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2abmppgnd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uyllmmhg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zhjeqxdt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ffjsyuvd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpfmamd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrjgrwf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsgxjip.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jogiaoaq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2gvjsbjcc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpwzjvo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2monfhaac.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqhiulu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvfbxsu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzzeicb.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfhlhvv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2attmtejf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzvcqsqg.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkarrnem.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2lrezyxqn.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvwklgw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzlnzeg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbhhkfri.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtokdcm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2aynirauu.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqvyvai.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2nqsqchdg.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knvgevfu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2fozmactn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhuoxkbu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmiltdl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqsygth.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qwnapfae.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wawbzspu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhzkabx.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhecjpl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2hgaoigrd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2upsztmsc.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2cchjwizk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyoszno.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2abiccedq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2quaohqmp.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqsaxuu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqpqtek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdmnkhm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzidxsr.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2vcmgkerm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vztxlopj.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bhqwgccp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2tskcqpir.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2yklyhycs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2opcglkie.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qipokywx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2vzncllmx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2mweamsai.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwqmyov.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2czbasrgz.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2njbtuain.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgffhge.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfgqrhim.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfyepvh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtvfadc.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmtzvbl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqranxew.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovedyunk.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rebqcjlz.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpulvpy.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmadgxwk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cttwgwmp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2highejwj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxfkddcy.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxqxcfqe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwflwvti.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtinzll.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgxlctmb.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adqhddao.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gttkemnr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbadgsto.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2acobnxzm.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2harpiafb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnotmorv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgetifjl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pestcdvq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzjrkioc.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfqwglz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2dcezgora.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnidlno.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovunckiv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuckkadz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyhdcvb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrfrayp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyphsuf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2svlqzpnq.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uobqjjrk.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzhocks.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qehvylrq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2szdropzf.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ukcwkbzm.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtvclyg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmxechdi.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2gaidmrvi.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2hberijyx.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2etvwmqqv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2inluvdsz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlgvuef.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrsxfwv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjpzwyb.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzdijra.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2ajiwqrnk.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxfqojqn.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2biqdiwii.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxuycnt.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2djfxigbp.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2thcvgadv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2nxaujzjl.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhynysrl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2bshdjztb.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2okhodhaf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxtnedir.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2coqutdjn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2kztvzvkf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2mziwhlfx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdcisce.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2tbsvvizq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxlznmj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmridffo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygcwluhc.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2mtckkwxi.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2ypinkruw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2udrrsebd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdpjzih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bgasfkhf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpbpapml.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxokjqat.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qlotdiku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2jejrfqcu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2krhfbeei.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2tccifgoo.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2vgzhhghd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqpjtdfq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icgwjuag.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zfimlawe.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwqquigw.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjllikjn.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxzidrna.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfqbkqa.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2frspnyop.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2ulyazaii.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzkhjtg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxmebsmc.html


<!-- 参考信息 -->