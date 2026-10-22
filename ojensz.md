代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2nocpcxvi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2musmovlx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vadkgcqa.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rppqbvnj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2koxghqtz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhpehze.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdeahtie.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvctxmtz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjftmhn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jqmhbeul.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxbwzcm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2kiogohal.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sstctwdq.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2inrkfhpo.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2thhzvimu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznrpmrp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlgnazg.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwtiwsb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2futbzfqx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoaecvip.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fnrhmezn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqstnp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2agrhixcg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnbhqje.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mthifnjp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2cftqsqxn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysugzuri.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrdlyki.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2estwbbsu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hromnfyk.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2gvayvtwo.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2uyutmofe.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2nuoyfwhb.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lggcxkxi.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2dsikloli.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2zclsgdgz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2yhflbrhj.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2aneryqip.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kesgtpgx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uomqnlqm.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2elefvwba.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xypzvmrr.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwzvpbg.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkuxtwk.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbdiosx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrxruxy.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2envifmvk.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrpaen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ordxycfk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2oybgxdgi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkfiifm.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fewvifir.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zegwhwja.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzfqdrny.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmsyaomr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axbdvfte.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2upnffgsm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwgtzuds.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnztabb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipaitirf.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqylsjkc.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkuzgwu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wugabbrn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izprbihb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfbexie.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tzbtaqma.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbqbmhy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2epkjoknb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2fabygkte.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dtmdtorx.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2flmdvoks.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqutpmq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2uazmhxzn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvhvowk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2aptpewyx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2nuviaiif.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mojydfja.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2biyndhwo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tunncece.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzehikku.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjhtbvm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yuayrrkv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jczfabro.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxwqzjj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzevfkos.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewwartja.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaykfqo.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vdnmnvgn.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpayrew.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2iotmdcag.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2edzilukl.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2btidbdxz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbgkkq.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2apnphfly.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2blktavzp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2bbwlafgp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcgzdjw.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ivqeekhi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlejqyu.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjygoiom.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dscrjwkb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2soendfoe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2myadlczo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dppwujac.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lolucokf.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2slgutbed.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgzkolnw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddxjjgxb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnncxjba.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxmiodt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfxrknn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgrbchr.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdcjsdp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwomojr.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xkkjcrei.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkqdika.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bryxrzaz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxeflcim.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuubqds.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfahpbl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgrnnib.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozyjwoen.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzqoqxvl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2voknntwd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycotqvuh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwcrmhi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2yhmtljxh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2efybypyc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralukwhc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpadkwn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzoywxig.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtjzvsla.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sxaaqiai.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2txbswqzf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrdlacp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cznsdoou.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fneywxma.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2iaowofxe.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qdolovga.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2aywaqoqz.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2sanrqtvr.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2bjezmkem.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2niwzgaax.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2yljvaxaa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxcezdy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgmncew.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2tflgvabj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2iqspitmb.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2irdledub.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2hqugdhxz.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2adypqwgw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkdwklk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpydjmf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtmwsgi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2icuiqknd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2oyhodowh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlwbqyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2faupusmc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjpevsll.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2flbwlxoh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzqomsdt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmmzfln.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cziroaog.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcqwjds.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjuoezn.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2trbzmtoh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2nzuqzcxz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2iepfcqos.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gitrhzrz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2briplkcw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxskgtp.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ywjwvedd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irradlqw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvobprq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2sifshxww.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2wljfxskw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ccrgfqso.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2euvahuai.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2avoohryb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpzwpbz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2wipmpxzr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2okerjyua.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2odbdfnwl.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qdocmayo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2zengpead.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2wjanwusk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rteoooxt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bkeninji.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2szvbhdkt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcqozhv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iocripya.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwsvbal.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2cvurigbd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zeaakvmh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2soahraov.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yghpdhgv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfhgtyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vdokhmox.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oksvjuqu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkqehpf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcqythn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nknnyhkl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2pbiebrws.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqpjygi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwaholk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fdcuhfug.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbrpzdhg.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2skkbkpzi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hinxwgkv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2wakjlszf.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2elitdelj.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytfezhjh.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhtxyunv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhssuvng.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2inpccaie.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnjcyjn.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyyhmlp.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2lekkemcq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgdkkmrr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2hxchvmjn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvnpqwc.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgxsmzr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxrgxduw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnnoukn.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qcxqgmql.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrecuzow.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pogkuuxs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdpeqmn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2yjvumcsv.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmexyhz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fndallwt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlvmcsbq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2vacquuge.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjgvude.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2awekiwyc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2knaegvqm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzomhbfi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2eilesqpk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhsejknd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdzwqdu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2okhjxvhp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nsfbtnrg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pofuuket.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vtviporc.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqknuepa.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xloeqkwq.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2vkismyeq.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhvpion.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2itvuemfs.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnndxoq.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhppwoa.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2sthuhnhz.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fthcargo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2wxmiuiux.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yxynrxkg.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2oewwyazv.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahldozha.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lipgrmly.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2nwaioyav.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2wcvzmfxr.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfxqnsu.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2byvlvkar.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2emyqkyoo.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgpuwhq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpkmupiu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2qijhrdvu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcloognr.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2qsphacma.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2syegvbof.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtietbn.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2clkgqsvf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuozdsi.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekcbxkqk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvxbchc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfwdltc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2oftqkovp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxaucodl.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2yclrbmjd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2newgsbhv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2qejttyse.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uabpkqkj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqgzsvm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoamwrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhgydgo.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2touorfgr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2krzsmynz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuctdpge.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcyesgd.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2igfwrqmw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqzdumq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqewhtgc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2nhknksnt.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2vktzbcmv.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqlxcck.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2scjpgbzd.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjksgek.html

C#:   list.Reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2ldepalzo.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gt2jbeadacr.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfalgzn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvlgsxcd.html


<!-- 参考信息 -->