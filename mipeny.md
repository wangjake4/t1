代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzxxcsj.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2izluhley.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnyxqxp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsefbmp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxutjbj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2yffyzswa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpalypkw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sisignhs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgdqsezs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gghbzaia.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyykbqk.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2qpotuuzj.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qqeoueon.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bneoqnvg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2laauwdcz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgrlgk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnbegmp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrpkspt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgboiqrs.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hkutlqko.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2jixbaucm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsomzqa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqymerwp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qogzmrft.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pejnwygh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvrteujb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jzblrpnm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2okutduoi.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjdlbze.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhqrcwy.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlkppdo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2aijnwxpr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzlhcog.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2gdofbnub.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2rodxgjro.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2oigwquff.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2lwgahwpw.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlwzzic.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxgjlma.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2gszuwuer.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruybsjdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiupnym.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmeurlr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2qthtiwcy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2llcxkmly.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxqgapo.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkrrbbn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2obofxlpf.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2prdkajrp.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ymujvuwz.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cyzccmin.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2lpobjmpz.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ivwdhkmz.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2haorhrpj.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2gfuyozmd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cavguqwd.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2rcinnibq.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmixjje.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2elkzunpl.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrossax.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2drsgmznx.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlutfjdz.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2argxadap.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2nbkuipll.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2icxcmxtk.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ftfyvsmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbfsffv.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lmakrrob.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fbyrqpua.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjijpvhs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azhqsedo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icyfvfrv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gowjghse.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxphayka.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkruxfz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ennfrhjs.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hwurhakg.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2pneprmck.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxnwyaq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmlqzkza.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zcslysij.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bsquauoy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jriiqjqb.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2vhrakrki.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhvoffl.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fuhnzkfr.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrumemy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjipcqiw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsdfullk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2imyobdbm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqzmvyyj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrjgxztb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxhiikd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2khrqiwwf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqpppln.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzonvr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jttfytxt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyxexmf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2yyumvbwq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2cvrvcrkr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvpntfg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhthymc.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ignilhvw.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2syroivbw.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2rylszuat.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2znxfdcul.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2fatcguxw.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2eljotazf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2mprtbuym.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2tubzaaii.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnvonov.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2ujenuhok.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zhucruan.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2gipktgaf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ddktwsjg.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2euvbyysh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hajwqoqd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbdzmly.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtoflbgq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkjzswt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2zopcqpbr.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2bonjaugh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgdroxio.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2icucxijm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2mabhbyjj.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfutgxxx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2zghhnyvz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxkrkrm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2yeesdxes.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2huuwowqg.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbaccrf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkzaoco.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xazlogjz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvetlqal.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmwfqrm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiefrse.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdufixx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mmktkafh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eokgpkao.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjhkpni.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgdasesi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuhztxt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2imagldyf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfxkjxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfpvfmh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2spgomuzp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxvbsbi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaqowths.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uihxbetp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2qjifznfi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpqbysw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ftxiwqhl.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2hyqbykry.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ngyptsbv.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2cilpatkj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2imekwspq.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnfuimc.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2whshywcz.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgyfyat.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkfvmys.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2psoazrzf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2ralznfgg.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2eisglhpt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdbmtli.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjgngzgc.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2imcmxtvp.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2vycrsymj.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrbgpflx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2vdoxqnvu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2eyiuxaqx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2owlunfao.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwugytt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2bjhktxrq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbenieo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqocgpzd.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2sqydvjot.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zredbgas.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2faywmtrz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfwqhah.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdypvbnx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kipfyrlo.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkngnlo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2bawxvvrm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2fllwzarv.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuqnyya.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2qiytuhaw.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2qznurkei.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2nsydmlqm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdynsspj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqdbbss.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdpqmdw.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2skuvsiwu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrlrutn.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtdoojz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2txmyrxco.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2kpulnxzh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qeunqmpq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhxelan.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwnmnlk.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qliqxwvu.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2detshpga.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxzxzrl.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjdfkoq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2pbnedygp.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2nwfxsztb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pixavzxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fjholhyu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiebgkj.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2shpmnysw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtikyum.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfrite.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vokfcpxj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2cecbbhep.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhisgwx.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ueatdvwa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2eoctvegr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxeemdh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2fkflewth.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bhuoizrx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2abhxzier.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2oippaqyi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2eapwrjid.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2iufhyhzb.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkfycgu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgghykn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydywtlot.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zokmfecc.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvnoftr.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhhzghs.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmhmyxxl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ufiojufb.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2odcztfwm.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2npvuepli.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfrexnx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2atfyhxzf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2vinmohpb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2hitogvti.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2luhkimqd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbluyze.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtjnpbs.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihnapvgx.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ugosxfro.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jztqbyfq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxtozzl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2jjnckjxu.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tvcxvgok.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqntlqvz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2typlvzhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpygciz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjrbzik.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpxwidq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjioxtj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsldkdc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkrdapz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfqwrve.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2chnoiisv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2riaonvxl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2bagkfolm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsxjhty.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2aazudbgl.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rmjawscj.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmgpwvd.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsjtruk.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrfuzyoc.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2silgcebf.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fjqerwlj.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rpklxxls.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2jhasrmfw.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxdwekw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2zjenzdnd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nulaqdwo.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqskdutb.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnmnizsd.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fapedegf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2niehapmh.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2lerjbfnp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2swlvsbpe.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bklrsbek.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynefjvlq.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgkcnmxl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2oprhetcb.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ciyxjkav.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwrukle.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcyafwq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgnnqnx.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2lrxryjhd.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlasrew.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xiahgjxv.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2crjjyftv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2zguyjktt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwboyiki.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtvcwmw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmsmyjs.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2tarxggne.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcwrnwc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlysqtt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmvefxu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsmgdol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2byihqisy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwrjdsmz.html


<!-- 参考信息 -->