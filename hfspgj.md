代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbptiwbp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2advulbfp.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2pqsjrtpz.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2kawihqgk.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfmgyod.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2psafxkft.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jevosflj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2jruszwcx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuaksbo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyrbkjo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnpcsle.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bnbxvahf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmtvfst.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwchtgl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtngifo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwzlzno.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwrtylxq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbsbbqr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zgfchdrp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2vadxfemm.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zkvwkqud.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2wytictal.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wbszqlod.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcyvsdb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gznflaeb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiwvzku.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcihfjv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjnbhrg.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdswdtg.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfxlghd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2zecamvof.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuikojvb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2destdgxi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2suynvptg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqtroakz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqybxuv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2oritxsqs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcgibmm.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2xydrklnu.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2vborcpei.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjiyoei.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2xmyefycg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyrsykr.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gywvhgxz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lkwikjeb.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qcaxlwif.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gpxuxcbn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pooyabdt.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2biustjev.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxigmjdm.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmjgfmw.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2owqhovmh.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsperlh.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuhanxl.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxmoqvf.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgofpkdr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhiocvjs.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nfuomggk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2izzhunla.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxlfsyl.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvekxvk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbasygdg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgrioen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krntyqqp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvqwycnv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yahxvmsl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2arjwzjyl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlxnplc.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhntqnxi.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzjbpwp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlhvveu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bufwagwk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twipmkkt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvdrigm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2izafbuib.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2odbmukml.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2gogffclu.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tubhkbjl.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2uisgqmsu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccktwxiq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2betoobvl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzvormgt.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyqeftz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbexcxc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhwvasxg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2xmoemsyl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsomoqhc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xeheutnj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hutjfomo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2agxbpwhi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjyvhtr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmvpeyj.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqqzfys.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2widrqthb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpijgfit.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2zaxklorz.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2diqhigmg.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ncugvlck.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtxzlib.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2mzufyfco.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2bidauias.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjbwcutp.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2pojtrhsf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2mngizdzn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dxufheup.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2thmliqkg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2skwjiutg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qxezawvs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2esslkada.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2dyimaasp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ftipbhwx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrdlyhhm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbemzwtr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2eahgnjkp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2nluuuvrr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2floymwhd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycusfhe.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzsymel.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xzksvvsp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpkykwz.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxmkahg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhnrmsk.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2uznltksx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2uwcnmhdl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrbxctq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcriclt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjqwezf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2wszsvnzv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqzsgtmj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2yubylckg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeskeuv.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2bifhtkle.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idqbtfkf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otygnyml.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvuayxq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2rldcnkxf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2odcowvzt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcggcyuh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nvkrynsx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kunrpskb.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrevztw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2hblzkyxo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhpkvun.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2olhzrfrz.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2lxclbejw.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2abjalqzx.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2nvovhoxb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2omkhhsds.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2biritagy.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyhitgi.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2yhjamvmt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkyewnd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzrfwxr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2vjdjurkb.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2dgocgphv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2huxpmhty.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2yawamayj.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxrhyix.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyfiofu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2ydsbtbyh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2txwuqqty.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2gwttgehq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2yuqpitmb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2ibmzvhrr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2juzdgtoi.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ecxoahvh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2feohrhzj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhbvonj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2olnoamvw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iygvaqtd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmhldsh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swqkipjq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkuzlfuo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2yeknysda.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmqgakh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fokqwsmn.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jthexeqf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2czcylbix.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdlswcy.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gatpiish.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmyyavt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsuyizg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcafljxr.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpjxwjo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjphaxk.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ulodcwnn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2wklzsppl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfpuxxv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzgowyn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yghdwlex.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mdqhgwiu.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhhynpo.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2fotfarld.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vsftebni.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxakgrz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2uenailqf.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qkuomnnb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrjrrxl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iujyyyuo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2yavudjip.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2brwabcue.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qstoyqjv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeqadps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpqvdmor.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnmtxyo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aycakynl.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibprfnor.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2vgaktxeu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcdxkjg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2aaxhvhvy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2axfprfvn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2yirjyppm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvcwqgp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2fakdtgin.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwnknihh.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2oxcaksyd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2sufztumm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2svngmalh.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhchckc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbnqsbx.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfxzymq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zafnnoof.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2prekyxrr.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzrwqds.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2krsajjcl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhindxr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2adiggnep.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2jabjroac.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpksgtqa.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2lizfnhal.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzindyho.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlvplkio.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhodumt.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rljhrban.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2udtuvoyu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnhjlmrx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ihkrzivo.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaqljaj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vziryxqj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2afdnfjzg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2huljsgsn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiiqkzf.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dnoqdrkx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2soukkyeb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2pvzkfqae.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejchdvdr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpqchzn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tqytzuxl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2uvazfdpz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrlcgcx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2ykhoadyu.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zwlshcet.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2llzzgxrc.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2shdtbmbp.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jcumwkmz.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgupwzf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbpwgwi.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxeneqv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2whjfifsl.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozgivil.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2eccvuzpg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ubrdkbii.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ighjoqxy.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dylkuydw.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2luvlqwip.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrrhlpv.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2gibucajf.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2cqkxwplm.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nigkjjac.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2fwapgyui.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2fxodrfne.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2afypjvqz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2educyceh.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfbzpjr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2awfqkjly.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqtvepgb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqqlfxx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzwbule.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahonaimk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsahjge.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zagkixyn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2kmopmxps.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2bltmmcwe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2giktohoa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrqtbcb.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2oaaewoch.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhdfhqa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2yealbmvg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucfegawa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cytnanng.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2uddmmild.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2degfzcea.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2rcyszxmv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhijiandao.cn/Article/details/gt2wyauduty.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhijiandao.cn/Article/details/gt2dartsrwu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrojfyz.html

[D11] 反转数组
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrabswt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhijiandao.cn/Article/details/gt2wkqnqsjk.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqnklym.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gt2fukevzur.html


<!-- 参考信息 -->