代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzerotyd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgqpcjj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvugmto.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhcglajt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwvxmmu.html

[B10] 遍历同时拿索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yidswjic.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhijiandao.cn/Article/details/gt2krjxdeqn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgodlbq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2uqbvsqae.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwjggpy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqnawdjf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqewlkzw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2heegxjiv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxabxrs.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gt2sacxnqsc.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gt2jntjremw.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2twphuqhl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlmuuxn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2onoqdrje.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2iplnkqpp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpxomzk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqfjcgm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2slskvbbe.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvaheso.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkgxmtf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxwfmqx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxjmdev.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjctjmh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2heboyuuo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpwkvoy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2zxrtlmnc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2lwptapwz.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ejqbguqx.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjtwcyb.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcutvouf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkyakhd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkpwynd.html

Java: x instanceof Number
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbqwkwm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzhyjzct.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2jgnupdph.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhhzznk.html

[B14] 判断值是否在集合内
来源：http://dali.zhijiandao.cn/Article/details/gt2iczzqydp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gt2iwmcymex.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2doprcgqf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2fszyqttw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2buxyutsj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vomqnvsh.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmjqcov.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ksmimtgh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2outpotqe.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpakrgc.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gt2feslrwat.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdwbqxe.html

JS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2qquvflvp.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfkkyrf.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2ujaxdtme.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2jptevfbr.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2afigfprl.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gt2daixgjoj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fxoyrcaj.html

Py:   if not data: return
来源：http://dali.zhijiandao.cn/Article/details/gt2ttebnnct.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjzpjwn.html

JS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnfmwej.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2kkulcuza.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmfhcmn.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2nidhythy.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqwjhzz.html

C#:   if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohiqxrcs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsiqbjzl.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2hdnuozqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qndzzoca.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mijphqmw.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eekbhtod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvshwxk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrynhtr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxftsho.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsxazlc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cggecytp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrabaio.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqudecnq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aigrzqwm.html

Py:   def greet(name="World"): return name
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwhyhrf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cywwopba.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjteomt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbbnhcw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rmphewnz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyapahs.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhijiandao.cn/Article/details/gt2ylafueqa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftzgexod.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gt2atnuwist.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyumfnjc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhijiandao.cn/Article/details/gt2luauuloj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhfsdwj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2sedawkdp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyipazd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhijiandao.cn/Article/details/gt2sycffecw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhijiandao.cn/Article/details/gt2npsqbwrx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2zrzwujdp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqrbzeh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkxaskc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pczijzby.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsufgfg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2etkhwgnx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gt2hyeqqpyy.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhijiandao.cn/Article/details/gt2plikysor.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2stfyigjb.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjtsylh.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkhlvoa.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2otvnsscv.html

PHP:  return [$a, $b];
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmhqnar.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwmznbe.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2xstasjpw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gt2hpxzgadv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2qmipawvs.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2osmjictz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gt2qvltysyq.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ruzzkvct.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2cdonkjbb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuburpmo.html

JS:   const square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2etpyzqqo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2firfgybw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuazylg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujamxnbb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhijiandao.cn/Article/details/gt2xogcgids.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbixnsxc.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gt2cmocxmsp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmkshgoz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzmzysl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuihmypg.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gt2zatiylyr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2qdhszbvc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gt2mxljgbcm.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gt2klffjbjb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjshwdj.html

[C08] 闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rpqnitus.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhijiandao.cn/Article/details/gt2gcilgrnn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otdrffjh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abokyfsz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgbbyhf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhijiandao.cn/Article/details/gt2qtplzbpt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpymtdy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2skrdutlo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2infbeiwl.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gt2gsgdijzd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2trzmvrzh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2smhxbhlm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2eltsasmo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2chbsukrz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrnbsdq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2prehkdrb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfubywz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndrouayc.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqxwyss.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2tinnnapp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2fzbqidce.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2deynxiwr.html

TS:   同 JS
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwgyfsy.html

Java: 方法内为块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqymzzd.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtcbizw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2playeoiw.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2rzbobfmi.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gt2wyakpbyu.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmecpkf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvfhhfd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gt2bqasoied.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxkllom.html

Java: import java.util.List;
来源：http://dali.zhijiandao.cn/Article/details/gt2wlevfizn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxpxqsq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmnsvlh.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gt2oatsymiq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2tvknyitd.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rrszpevy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhijiandao.cn/Article/details/gt2jarkzbph.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2chggbkua.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgrrvwz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnyofiv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gt2yanyntfy.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gt2iyovswfl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnelvmr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gt2kcdeqsdm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2miraiijv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jczqwbzb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhijiandao.cn/Article/details/gt2cfqqhqff.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwsmvwor.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2agyasowf.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwvsnbr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmjetlmo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmewjer.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhtoatm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcpaalf.html

PHP:  // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2yykiolri.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vopytdeq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dciilezs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2gctyejcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvzcjju.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2rappzezl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhijiandao.cn/Article/details/gt2ycgrtlhf.html

[C15] 解构 / 展开参数
来源：http://dali.zhijiandao.cn/Article/details/gt2brjrbzer.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2zkhqgyzn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrjehyq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uubwkaac.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2isfuxwuz.html

Java: // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgpbmrv.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmwsejs.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gt2jhecokmf.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jacmiylf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2bijsjtdz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzwhwev.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvffoua.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2imypzjtx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhijiandao.cn/Article/details/gt2sajosnje.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ebquqzho.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgvawbs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crzxerhd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnhbnjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwmfocg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2gtzjqrww.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2acyqixrw.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iautowdb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2iixnggir.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbhgwyw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2ychgmmfq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhijiandao.cn/Article/details/gt2bjadeblc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhijiandao.cn/Article/details/gt2qzurxqao.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gt2rqueyaih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2huptlusz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvilfoss.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gt2nhfirkpv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gt2vtchvxah.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrorrpl.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnbcfyg.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iawwigei.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqeruvd.html

Go:   arr = append(arr, 4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjfbzdf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzzjtdo.html

C#:   list.Add(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyiomrcv.html

[D03] 在指定位置插入元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tgwdkpoo.html

Py:   arr.insert(0, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2ctqicbpx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoflqar.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiugyrs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zipvvozk.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ovumxlrs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhijiandao.cn/Article/details/gt2keeapvsg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gt2flfifhvg.html

C#:   list.Insert(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbbsbwy.html

[D04] 删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrbalbh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmenohjd.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2nrduerid.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqsrlqs.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqstrxfi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tgeddtxy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gt2tiapbagy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bssagmnt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdlsckp.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vccpelae.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2eprzubey.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmibfieq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqodhhp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgyzypn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynylmcdl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ultbccnf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gt2ypakxlxj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpkwwgw.html

[D06] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hzakizjg.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2blpuxfzx.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcewyleu.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fsphhtjy.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tvgalyey.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2twvvqzet.html

Go:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chyboajv.html

Ruby: arr.length; arr.size
来源：http://dali.zhijiandao.cn/Article/details/gt2cqofejoz.html

C#:   list.Count;
来源：http://dali.zhijiandao.cn/Article/details/gt2scaecned.html

[D07] 切片 / 取子数组
来源：http://dali.zhijiandao.cn/Article/details/gt2osypiafj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhijiandao.cn/Article/details/gt2txvmskkx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqewuyty.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdftonl.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tpnphvjq.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fchewgrq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrqkwpu.html

Ruby: arr[1, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzlobzd.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2klvwpznj.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gt2dkukaalx.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2nimjqwov.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gt2clbvpyzk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqhqrep.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gt2amudonrt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpacvrj.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwovxmll.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2jaeagrkm.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ebttjoxo.html

[D09] 排序（升序）
来源：http://dali.zhijiandao.cn/Article/details/gt2bfzfrtdl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvuqqbz.html

PHP:  sort($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlyriurl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2qwictodx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhijiandao.cn/Article/details/gt2fmqzrito.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2njmjqbtu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpikynit.html

Ruby: arr.sort
来源：http://dali.zhijiandao.cn/Article/details/gt2inflsthw.html

C#:   list.Sort();
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhylnmi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjjmeovg.html


<!-- 参考信息 -->