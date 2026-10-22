代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivchhdaf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyvudil.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqvzwqu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvkcuyr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhxfrms.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcuakhe.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2hnsczsqr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idmucgqd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgaatcf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2wmhgoxpc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2afdapomt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rewgaoxx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zadwzlwk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgltfilm.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2nximefvf.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2isnhfpul.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2twtctqyi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bksiqcff.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mejqgeis.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2rfuaqyfa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2cmpkqxkk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2pinxfqim.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2oogwnuxm.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjgbikq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2sabphgvt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cnljoksu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ralnketw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2guwscfjl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2whxvwlgq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwzszndh.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2anmjqaqj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2stqbjosa.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2djplfoge.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqgbqqw.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnevnac.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxhflik.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkdquhb.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2hxgdpiyh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujofsqd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbrgsgka.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2psnswsqn.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwnzkql.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhenpvx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2puedvnth.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2kwweejpw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwffcrc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjraoyo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfmqrfu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzngnpcy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2wvlvpddd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2igselpoe.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2ojipkewm.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoweosc.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2elruyenn.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2fzcbncvg.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2cjhshhuy.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2tlgmhdqy.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2drcaugyn.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2geeoihdw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvhuvkj.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2iabqhaem.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaprmuwf.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrlfejo.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfbofkhu.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2gflabqpj.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmcmrujf.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2jzizcvul.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysshjjgy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnejmod.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcgidjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiuhslu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fsfsnzxr.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjvhsls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddiqdqyy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sydylngk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsbiyxbu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsmdtsh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhgzijh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2zsemphff.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndchdhrk.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoprxlh.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfucugs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2phvbrdve.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ollxldhm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oitmfnqq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sntehvqk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrcrnyg.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2kapegezj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2uahzhnmn.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdhwdjxs.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2eapsrywy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2otrequjt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdisuhyu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2yterzxrz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2xegesrvl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2fzaylolt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkjohve.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpodvvl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2imhnagci.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2klouuybp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzbsokux.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2fiilnmgo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2jltgrnpj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2efzmhxsa.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnykxjnf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzhbbjn.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oggpdubm.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehghkzkm.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2dibebghn.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxjeavt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2qayslzao.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgsmgae.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hfqsedrj.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2kamknniq.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhsiujl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2eptphzpa.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcrvksl.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2fvvljsup.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpprzclf.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtwhdzc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzrmqxw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mqqmbthq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyekiece.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwgpqfv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkbfrbn.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2uamdsvgs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2luzacnck.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdbspqj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2kueisyvb.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2aruryflk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2xirtsqvm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2ambavfbd.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2klsfhwqj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2xctruwro.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjttlgx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmbhxvm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdeziysi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spzrdhqk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtasrdwz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2furolnva.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2fegapaeq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2mhtamgbs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jylcpnte.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2dtzvyjsj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjalcyai.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvghtyyf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2skejrnnh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2dguoegil.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzedtwni.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmsyvaph.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2thxsdxqe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcofqtsa.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2bknromfg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ejoutkrp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtpcmot.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2qodfeotx.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2jikjxrjp.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2yadepixw.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2pmczkpkq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpxoozu.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2lkzbgamo.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2klnhbutr.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2osxktdtp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngthjiig.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2prrgcxju.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvkgwip.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2rljlmwle.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnhfavm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2szgakplp.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2svimeyvb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2kefjczpq.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2dubqvgss.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2cfchfhgy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2dterjrzu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2zwtxjwne.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvunwkz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2ktkferaq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2urxmwxuh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2esnhuutk.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmtzkav.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gtufihud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecvbzexq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2jgtntvaq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bebyrllm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qipstynq.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2pozqfgzm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzuvoez.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2duftusjh.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2smxvjyzk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2yiwcazio.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhnvolw.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifeipxmm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdribxxg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjnkbbs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjwxaoo.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2abenpedk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2atiksawj.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mljugcpv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2ysvhvtbx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtxnckxs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ckuzhstd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2neugszjz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2drowcbdm.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2irenwlut.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2mdkecatr.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2csigqmse.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2vdclyezz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2qgclggec.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2yajoukqh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2islatgvi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wspusllw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pdixrzsq.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgbeqhu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdcnkkjn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2etvqivss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nluscgkg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2qzonwwkf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mowewrgq.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdvwjgu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2saqyfrdy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2lstdosjd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2tgekrwao.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2nnahsqtr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2dbvasfny.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2wmdwmmxv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2urzhfzpa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqxobns.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2zcgmkfzn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2ykrfijkt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfrmfzz.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwzcdxe.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkzjcci.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wmbyiacq.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2lllywwve.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhpxyzg.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2njckeand.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2odfiecho.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmopjxj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jdaofser.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpoqjnp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmujmfqe.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfowsrv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrarjvgb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpobzdo.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbweufq.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxoyzir.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdcugyam.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2zexkyhwx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ybquojtk.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2txdulpbw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2qwwsjxhz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2fizmvnnj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2npwaqwvn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfugpbyd.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyvkziq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2yugqgxai.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdhnimr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlqjhlu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpfczvhg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2djjqtcgd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ueqzjada.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwdfvdq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2rkyhpbkl.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cueszhqb.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwmudrx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2fswempgt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2milmyxdp.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhqgajv.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2wgouykal.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkvvtbqm.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmnhlxb.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2cldbqhdt.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwrnfzj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2ialsdgqe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pptpvzvu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2clmtjaqm.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbbtmeqo.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtjykawf.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxiwnfs.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xmcdjcnb.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqexynib.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlktrqo.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2xduasktn.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2abfvkugy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozmtiasu.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2vsexcnqv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2wksnkyeq.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjdxvfo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgghdar.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgclzdzk.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2wkarydlo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2telrwtdc.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2kijecfms.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2llivtzen.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqcrigr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2yithfqnv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsdewnv.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2qhzdhplh.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2byxydvdk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2kukojlwq.html


<!-- 参考信息 -->