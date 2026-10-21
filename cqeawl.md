代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gtksxnmpgv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gtbahbiqvi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.haohaochexian.top/Article/details/gtavvrpjjx.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtdixiglqq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhengqikj.top/Article/details/gtrijjggii.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtljemfswy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtyizogesi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtmmcaimct.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtcjujbwzu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gtgympqpbu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gttiwoqgoe.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtrwqezrsx.html

[B13] 判断是否为数字
来源：http://dali.ivvv.top/Article/details/gtnajxtbcq.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gttduzigel.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gttdtydgnb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtdvhzkjxw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvastlrm.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtotewvqdu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtlhpjapha.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtkwnjpmfu.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnyrorvs.html

[B14] 判断值是否在集合内
来源：http://dali.yuxming.cn/Article/details/gtfrjnsuka.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgfzy.top/Article/details/gtxphxqtjt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gthpkgfrhy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gttmmffibh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtxhaizknq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfqawlppa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgufenzy.top/Article/details/gteklldhmr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtkvajzvxt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtssrshggr.html

[B15] 布尔运算与取反
来源：http://dali.hywenlv.cn/Article/details/gtuhctpxhm.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtjbktpoop.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gthecnsnjw.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gthawgeuza.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtwxfxqgua.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gtvnygetma.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gthaacmpat.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtxvujhspv.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtlmifdhjj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nwbrower.top/Article/details/gtimdptcfm.html

Py:   if not data: return
来源：http://dali.smart0.xyz/Article/details/gtmxtvlevr.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnhiusavb.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtoplrjtxg.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtpgzgqzfv.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtplunxnue.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtoqujjehq.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtmkqtnwct.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtngexthyb.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtqjdibopu.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtewidbxvu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gttvoktbpy.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtjtmagfxl.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gteaqcxtud.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gttpsmtutz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtmrlumztf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtarysjusn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtjazmdesw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gttzjnsqfc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmdqnvsbb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtkaqfbniv.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gtltmceivd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhoulong.xyz/Article/details/gtfyxtgcwl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.iojbl.cn/Article/details/gtgqimlivp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gtazwgsotp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gtglmvyzyr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhengqikj.top/Article/details/gtklzpybda.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtnwjaeicl.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gtmfecuuqe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtlnxweefy.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gthcfdqhdd.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtxavliulj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtngdtgdbz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtcyglqdkk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcttbmne.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtgedtifhw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtrnptwqmp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gtplzeyhpb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtgonkprgi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtzwqvubox.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtqjdvwejq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtxmukvzwz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtijchixnj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtjszdnvie.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtdkoyphjt.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtqmhybdhg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtjcnyqbgn.html

C#:   f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtuxikzvhu.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtltjpzkkf.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtyvoyrute.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtlvtqobpd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtdggigkwb.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtdjffejso.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gtjnavoftl.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtowhobgxl.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtijomgtmk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtblhojacw.html

[C06] 匿名函数 / lambda
来源：http://dali.yuxming.cn/Article/details/gtclefhxrx.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtdakdxdxl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtcbmouwbt.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtcpzbglwa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtgjrhzjhq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gthxyqonnf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.birdmap.top/Article/details/gtscefmidy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsbxuhul.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtsqyhkjse.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtbfzfnyvh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtuaefmolm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtngvzhlxu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtiathogwv.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gtrrevlgwx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtshqagkxi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gtlzffnawl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gteocktzbq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtwrrtoluc.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvptycohi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtfefnabul.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtplmtpmat.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtdnpvxygk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gttaedjsxc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtohbapwdu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jiagoushi.top/Article/details/gtcymdrwcx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gtsoddthfe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtbrnmfofb.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gttvautyrj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtvlsinaai.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sweek.top/Article/details/gtduwvsqts.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtxfbugtky.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtnypxdeuf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtzgkaifvj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtzzofzgjp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtrncasdts.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gtlevjtrcm.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtnjyxixhn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gthhojrybg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtqubmunyj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtgsfzwpyw.html

TS:   同 JS
来源：http://dali.jianghu66.top/Article/details/gtwrfxlvfp.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtbmgxizbf.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtnuttwzbn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtlfaclepo.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtttlnwckd.html

[C11] 模块导入与导出
来源：http://dali.316326.xyz/Article/details/gtsmkrxupu.html

Py:   from module import func
来源：http://dali.feifeiyinyue.top/Article/details/gtonjhcagc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gtcdmnycbt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gtixgxuwdm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtheamxoyi.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtfanhokgj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtijzhkcag.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gtsmklcsyw.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtcczljfmn.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtugtiegio.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gtunyccmuv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtutupkhda.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtukcqwhup.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gturdwuwbw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtovboacii.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtzybsabia.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gtjcslopif.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gtrsqwtahs.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gtiuntfhga.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtvcezattv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtmmzntlis.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiychqzd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtwdpoujxu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtatrlwrqm.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtovupxhme.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtmnkhhoqb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.316326.xyz/Article/details/gtrnkfhltx.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtkadwzzvz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtwvgtmjvk.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtmaiqewpj.html

JS:   // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtyahidhhr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtdnwjvvas.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtfzaarvvi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtxkrlahio.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtwqanviez.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtmutwjrhc.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gterfulhof.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtjoyfquqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtsotxtofq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtyemkvdyy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtjsugyqxm.html

Java: // 无解构
来源：http://dali.hfpthk.cn/Article/details/gtfyqyuotf.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtfpsrbzcd.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtdnotgfpf.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtdytsuvcm.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtmvzedepz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtjkdrgrju.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gtqdywpwis.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.andypj.xyz/Article/details/gtpdfcyqds.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtactmfyuu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtbjlpxygq.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtkbbqngtz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtbhgcdtxg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtutmpyiau.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtyvptntov.html

D. 数组 / 列表 / 集合
来源：http://dali.gogol.net.cn/Article/details/gtyrzsgbpj.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsscvivv.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtefwzhqam.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cucudq.cn/Article/details/gtezibnwul.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtxopkpklv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gttvbngvai.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtvbgvfbpg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nwbrower.top/Article/details/gtwfrnlkex.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtwlvynibs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gtsontaroz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gogol.net.cn/Article/details/gtiaoujltb.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtnzlrgnmn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtbhluzvnl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gteodyiiix.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtcrtvybqm.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtrqroxldn.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtbcexjivl.html

Go:   arr = append(arr, 4)
来源：http://dali.iojbl.cn/Article/details/gtjgzbpefg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gtsztxsirl.html

C#:   list.Add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtyogblxls.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtrmpwtxbm.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtufuizzrm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtnaamqkrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtqptxyvoh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtcwnpflxv.html

Java: list.add(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtqynrpwvr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yonumen.top/Article/details/gtekyftpib.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hysaishi.cn/Article/details/gtprjfwzyl.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjughjed.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtztzktttc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtlmozrbuk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtijbbnyne.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtkxnufhxs.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtvhdsefwk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pycfn.com/Article/details/gthpknxyvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xinyue.icu/Article/details/gtsjvbfuxu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenjidiqi.icu/Article/details/gttfngsuix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtejmkecun.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtgxvyieyg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jlsjyb.cn/Article/details/gtxvavbnly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtpmnqcsii.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtaiayjity.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yanxiufei.cn/Article/details/gtvuthwtce.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tian-w.cn/Article/details/gtalmxseze.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtbkrbclmm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtlrsczwvr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtqpqlugrx.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtiiqcjqnq.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtlgoelihq.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtwhsktxhj.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtaiehlpii.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtnfunnupp.html

Java: list.size();
来源：http://dali.jqgfzy.top/Article/details/gtknvgshon.html

Go:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtrjokyctk.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gtgimlgfkv.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtoaetraul.html

[D07] 切片 / 取子数组
来源：http://dali.c1oappe.top/Article/details/gtlbwlrovx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtidrhfnzv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtxcjayqph.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtpzkafzep.html

TS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtnxnudfcq.html

Java: list.subList(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtfvmcxrqw.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtokzspmyu.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gtimekhere.html

C#:   list.GetRange(1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtlghrbkyx.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtcnlaeaqn.html

Py:   a + b;  a.extend(b)
来源：http://dali.yanxiufei.cn/Article/details/gtegwlhwmq.html

PHP:  array_merge($a, $b);
来源：http://dali.hywenlv.cn/Article/details/gteqqjamke.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangshuangyany.cn/Article/details/gtkwatnqsi.html

TS:   [...a, ...b];
来源：http://dali.meibo888.top/Article/details/gtmgvsymxr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtwjxopyzk.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtoplyhyjz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtlpajpzbo.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtvttxyswp.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtcfdjqpqs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gtbtateoef.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gttjspfmyt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenzaomai.com/Article/details/gtappxswey.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gtjrdyrxih.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gthzdlwcdw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtxnemoabm.html

Ruby: arr.sort
来源：http://dali.birdmap.top/Article/details/gtmophgklj.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtbaihkfcr.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sysykeji.top/Article/details/gteufmqqai.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zdqjudy.top/Article/details/gtzfgkymyb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtdbpvsirq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtmmaychia.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtnnaydhuj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgnpzlkz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj202588.top/Article/details/gtnogbyeka.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tian-w.cn/Article/details/gtekmxmuul.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtnhxqhgon.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtdqmnohco.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtrfhhutwk.html

PHP:  array_reverse($arr);
来源：http://dali.tianlin.xyz/Article/details/gtserkaozm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.aizwys.cn/Article/details/gttvsgczhh.html

TS:   [...arr].reverse();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstpmalqc.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtgjglrgga.html

Go:   slices.Reverse(arr)
来源：http://dali.guannengcc.top/Article/details/gtlwtzrttz.html

Ruby: arr.reverse
来源：http://dali.fzhhl.top/Article/details/gtbnfbfmkz.html

C#:   list.Reverse();
来源：http://dali.tanke756.top/Article/details/gtzeabityk.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtwgojptqy.html

Py:   arr.index(x);  x in arr
来源：http://dali.sysykeji.top/Article/details/gtsrzyxqme.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtldhqxffb.html


<!-- 参考信息 -->