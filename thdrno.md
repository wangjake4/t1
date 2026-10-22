代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2cwaxqxil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2efotcwor.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vypzcwyc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgromvs.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2mymxymgh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnjpcdz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjxxrzzm.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ymemtzlh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2qydurkgb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ienaipjg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sztxarxf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ircuiaux.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmadgjq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aufrdklw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2uxranuwn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2gwrgmpid.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2txuuwbpp.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2otveovbe.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2htkcpvnm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sukfrunh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxvtmbbb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfjklow.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgaglbg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbukprrm.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2jyfqwuai.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2pvgsdlec.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2cszqtbyx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpixfzqc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hofsluvc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pudklaac.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyulatu.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmyrowor.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2eixcbada.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzyysuy.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2znrjnljr.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2fzmwhmue.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2oyawkprd.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kphqstfj.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjafrxu.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfgsoxs.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjjrcqe.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2letvwnpi.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2couvdsam.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rndebsgh.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2qbaekpin.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzayrxnd.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuvvzra.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbkcntq.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tdiyilne.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbodlbcb.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2tyxoyeez.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2eijipwdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nocgrggq.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2amxxeztx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pokasroz.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alhqztsr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yibzegld.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrecwek.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpwzkxo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mczwpteo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joieorik.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcykqyjl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrqtaoap.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbmqzue.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqypznni.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2djxhvccs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwqiwqt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbzgimkc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2innjufdu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyeqdiu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwikrmwg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmrgemr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmuqptn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2twxpfkmu.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2wktmzbyp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2wozxrmgk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2vubeucxj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyapbwh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeuonvi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmfpuyv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbfuzin.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2aedzuvzg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2isoynghp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxmswqiy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwmzuxd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdidocr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2gihjwgop.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2vtdxefem.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqpujgc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxzobwq.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrwvend.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsnzljw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2wzobevdn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2bnaxpxra.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkymwtyq.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwwlwaz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2rwueztwh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvzvbrc.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2hnkcpyzl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2cqmdxtab.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xcftzhft.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2ysreaitf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqeblac.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkturehr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbwgcsjy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkpaxqui.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbuznne.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpqqhfb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2noihbket.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlcqunb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2uppoacce.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzxatgq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbmtwax.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjnmvuwu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iaiwqrme.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2tbapuyda.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2itxobbyy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2jagmzggq.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2typiorty.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ercswvxc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzwgwpzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpfnfcz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsegkcgf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzksyeo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2simwggfx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsjtnza.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbtavwpd.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2fmolhbqo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gjikswue.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpvwjry.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqqcbrq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2suigatpg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvfbieyi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioawfrac.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2phauongo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhsemto.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2kccvjyjp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2rcpsrpaz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2dgsvkgao.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wuusukty.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2uapdecyw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2wypkttkb.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2occuwhrk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2sffklxib.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nsotnsqf.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2fidlddsz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2umcyozaf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2vgsvedsr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2iifhdsep.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmllvtw.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2aautkuyw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfrbfdv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzruxfqa.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2nlodxwxe.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2lrkdsqla.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnphzycc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrknwtc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xkothcgt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzgydik.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2eltcpgle.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2prdqmwcd.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkmkbbu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjtpwur.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsjlaox.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ebtxfeum.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvomsoip.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqmpfzs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2przsygtu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eidwemho.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2jxexuhaw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2etdqgzgz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2prbkamwr.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xizaesal.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2tyeonncz.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgcwuty.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gounqdjb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpzbzich.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbetjnji.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2etdslgqd.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2soodhibx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2whyudbsj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjrwznz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2xupqkasq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2bebeiixr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgawyqum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2sxuygiru.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgumfaxg.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyirnwz.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2vlfaskhj.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2drlovsew.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bwclzzng.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2acrqhhfw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxjseux.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2gbjvwfke.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmkyqlh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2swnhkbfz.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwrzfgx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjdagzy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zwymhtiv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2epywxpfw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gvmzytcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqiecvf.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2msitmkgd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwcbrql.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpmyzrf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2xakwiulv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bizymbzk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2ginvslme.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwkhorux.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2ohbhlnko.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhfkrlr.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzsqggn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2mhxersyl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbxsyiqe.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lflbdrzg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2glhkpobu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtwglad.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxiogtb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfegmoq.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gddlnuyt.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtiapmj.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgmebjd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsopluzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jzquszpu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvswuuxl.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsxumre.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2trkhkuac.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwqzawo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkyrwso.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxzkyde.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkkskiqy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkmuyuls.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbzlbfa.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrefjfz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhnpizn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2ojdnnhuo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfgdsjr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqevzpy.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmpkukd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2okzbccts.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2khgpzfji.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqnsfzh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bbgveqil.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtiwral.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wnxupjzo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrjirhx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2inceyjhg.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmbupdz.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctahioaq.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2occwcmqc.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2josqoepy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2gsupyxkz.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysfkkjyr.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqftpqzg.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2vvuzgbpk.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtegzyb.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsrbbgj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2pszduumn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2reykqpwr.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cklbgumo.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2udzfdzls.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iywgehwy.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqotwcu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2qntitkka.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwpxeye.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2iqlibfui.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fllwplwq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzivfkf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rilplrat.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2djbmuecc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtcpvmt.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwvyatmr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkychhkm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2virnytoh.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxtihet.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2fvxseavf.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhidqchm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2crkyeaph.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxpsbkvo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2wkdkxqdo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwsrktg.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2avtcyvnd.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2cjnxnazb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxusygb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uropdztj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2krfcvoqq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2thfrgfhj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpvanhj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xujlwnzl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbywbvu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2lanhmasf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2xdriloaz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nlnukbat.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnszbrh.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwygmjkt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fddkiasb.html

TS:   [...arr].reverse();
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxsexfb.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxlqsmsk.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunxezjj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gt2tkjtvyjr.html


<!-- 参考信息 -->