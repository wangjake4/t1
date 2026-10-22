代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgencyhm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2riivzgkv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uodegsvf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrutrkn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2kqakbygh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2fiapyxqd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfuuxafs.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wvscrfpw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2hypopxah.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqwvbj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2koimwejh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2usdiesda.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvfiaek.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dxfkjnva.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bnvkyleo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2syidrkxy.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qkghesru.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2rucvbjaw.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssltylbs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ngubkpem.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ligkzdgz.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlmlsmd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebzfbyet.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2naumqvuh.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkyusgk.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfdxhjt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmvkxlu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2iepcuarq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyabxhlj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaotmdop.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvgnghe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sghxecsx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwsidww.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tayqwavt.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2bgynodiv.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2kmopsxtj.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlxmnkx.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rguvxjyb.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fjzmzodz.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqqnzux.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxtfofx.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2eluutmql.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmdwwvt.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cfppyvbe.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2windujuw.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rasvhqae.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2fngppomn.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjlzjmd.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2mzwzyqdc.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2djadkhig.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2zxguepcr.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqksqshe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ruassqhv.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwgwdhr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qcmtjose.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdksnbz.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmvmyld.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqvjkebh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxzkgvb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpgfcvim.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfebswfe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfafmlv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrtazxk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiayhpoc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zhseptwq.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfdedwg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aftwqsjk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eixkqfrd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqifduyb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwerier.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bicbbzrp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtkcosb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqdnnrsn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2frwmuzvf.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2blhhjjpb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfqpfsy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2njwdyppd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2taoolrbi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aafurnzf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2qciyntfi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2auibxeib.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2zyexmdea.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtpfijev.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnftnyg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vuiwiilk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ybfvghmk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2avswqqsc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2ruooevsf.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttyfeexj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctthwfas.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2znkloyvr.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkobfuy.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2szdutuvo.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxkwnqm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxnhcax.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2prummwyi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2dyynzklz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqtnixdn.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2omnvxnva.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoskqut.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2adiavwqc.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwwtkrf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkdszrio.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpokpfwe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynicnglu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hahgwavc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqweipnk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqwranq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlreaoc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsvtjur.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cknvfrln.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2usogcffx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2udxdvusk.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgszste.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfrevce.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgybkvg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmgwucok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2skuoobyy.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2smpybjog.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2kshlgdgd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvlpshvz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeltckfi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utvqlsct.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2htgjncrb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxnsadp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2fbhrhhei.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkfcyia.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2tgypwswl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnakdkc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oduogyuq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2ongbmkzw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhhvhhc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2slruksxg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxjmfeb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrrknvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2utddhnew.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jxustxlz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrnpwpi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2yevdzfwr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2jyakvxkx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvlvwwq.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwegpci.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vonlmyzf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ajfhnair.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ulzrtwel.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfdajku.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2etnokaup.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgopgwb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2tpelowha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkiwymf.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnvblvn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2bgakdaxu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2urefwqoq.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hazbnrcf.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nzygiwub.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ogyxmgtc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xqdzrnog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2uipznfxe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxgyxcu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2btikpsqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuynpgl.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2fogzbcng.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2guzzqydq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2flpzjdzt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2karvsepd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjcotpj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpufjsjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiyfiiex.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctdjyweu.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxspbrk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2abtzqrlj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnvfhri.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcuaaag.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2emtdlxge.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2jkcrlayj.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2dzansgfy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouonehmv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2priqrmfe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2cauhuubc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioavzmye.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2cijwdktp.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ardbpzfj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ppezshdc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrrklqw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2clomlsxa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2byulvhrc.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cohpnaxi.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vryuipxi.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2uyxkncuu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ntondyfh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2htcaygzv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2dihswogb.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2lbyedxdz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2qidvbhdo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xisogcyx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrryzjf.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgwydcz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzpdjcb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwsyljm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kyiyghof.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2zafsuvwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wmybjncd.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvgpcsn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2ygudtqux.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zsgojazh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdcbtby.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2qbobfets.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2sjadfear.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2puwdrajv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbsenav.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pcnznnyj.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oqdhizgw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbktufa.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuscueyd.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uazmtrnv.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kkrxuvka.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrcxtlz.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xasnqeqm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpamzcda.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdrvcmf.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fcbebhtz.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vchyxtsf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjwkhue.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2pddqcgxa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cpexlfjt.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tteuxvrq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbcfkks.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2rfqngssd.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2refwjgbl.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhklahw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2iioxqbus.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxradcha.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2hczsyfgo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyueqscp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfucwew.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzidnzip.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ezemrzwu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaibmei.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2anrgduqk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2tybocvxa.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmclbbay.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkvixci.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxikxyx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzxuqsb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ozexqgvv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2gnutcgpb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdyfjguo.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxmgqrr.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dunfptde.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbiotbvp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lknqtvhw.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoqixhh.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ghosmkcg.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blrsyqcw.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2subelvvm.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2kltszmep.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkmypzu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wbmhgoqw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kefvqplu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2otlqdejd.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuhkhat.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcgcfpsi.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2myapjusd.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2yucqmwvi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvlxijd.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdisolz.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwdccyg.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhjcejq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2heljfewx.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2gcipbrhg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajnnqvpc.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbnotpe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2izytgqgp.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiogzpzg.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bmamnexe.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2eebqhhlx.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xovmuhnt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2fioedyyn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzkxevx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrxyook.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2npukpfzp.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2skeqqztu.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2jttkrkys.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxhfkwl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxwtxgv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbajqbo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwykpla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2zykkqgyh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqtxuyz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhfvxpm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2smtekphi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqdrbfw.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2upydhohi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2jaokdhyl.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2pghvyvij.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2zaaxxxep.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2scelmpii.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2kplfwdcd.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgajkmq.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmbdhgh.html


<!-- 参考信息 -->