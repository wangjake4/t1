代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtyfwvapdy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtxqxrzkro.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtwnrrlfcn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtuabmugbh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fzhhl.top/Article/details/gtmhjqrdfu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtkdpsqmqb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daxiang520.top/Article/details/gtjzfpidsl.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtxgowzxqf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gthqhujpmf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtpbotpdrz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtsthlojfw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtgsvzjzac.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtmlbpkkpe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtmfsravdu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtftlahmok.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtirjyspys.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gtllsbgatn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinghuilouyu.cn/Article/details/gtcvuxoavg.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gtoivysgfr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtbxqybtiz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtwivyaiuq.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gtsajsatbt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gtuzeqsvsd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gtnqjvkfed.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtztsldbzm.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gthoqwhzdb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gtpmujhiio.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gteibmqfxb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtbjbnzoyc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ybcxt.top/Article/details/gtuhxgtodp.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtsrchijvo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtkjbbhjrj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtqqcjhoop.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvtzrcws.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gtonuheejj.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtovmlfvuq.html

PHP:  $a && $b || !$c
来源：http://dali.sxryk.cn/Article/details/gtusdptblw.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtfnmrcepd.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtfcmuujuu.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtihfvqpei.html

Go:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gterphqaes.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtnppdnglm.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtecxzoqff.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtdetupzwv.html

Py:   if not data: return
来源：http://dali.gzhubu.top/Article/details/gtrefyauxm.html

PHP:  if (!$data) { return; }
来源：http://dali.316326.xyz/Article/details/gtqochqmxz.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtdoeaoone.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtktlolkgs.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gtlxsjisjd.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtpuluwntk.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gtkdpzmfdv.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtlsiybtub.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfuyaxxvd.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gtxexakdla.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqzujocdh.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtfysjegvk.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtlgdzqrkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtseguxjhf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtzblisgen.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtxxoczdeu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtbwfowofu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtunhiboqj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtqxjbbrdd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtviqfyjox.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtsinqclkx.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtadtoctrl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtoejhvhdw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtrvoabhtc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtqicafcst.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtpwkdsekj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gtaunaajdb.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtahqjkrlp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtcfxvrllv.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtaepqveco.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gthzvyrjye.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtfisjatmu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtuhjnlmuj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtymitkilh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gtdtjwihvo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gthxnqcoxm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtefcexgel.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtbjopsubb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmqczmxi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gtkkyrkwqt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtkxrbvaqz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxxfjvwkk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ybcxt.top/Article/details/gtrvsoydtj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gtrmwjsowv.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gttejjuxzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtzspokirt.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtnklurdoo.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtiynanbfk.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtxtgxjhzv.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtlqjoctpr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtjoyhuvwv.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtwewxtlom.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gtltrxxcfd.html

Go:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtevgdqjcp.html

Ruby: return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtlosvcxxb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cqqwz.cn/Article/details/gtcsrfqzjk.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtesrmpcgw.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gthpemeqpb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gticrqlqhn.html

JS:   const square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtpuednrmt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtkfaybycb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtetojklus.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuanzhike.top/Article/details/gthylzfxjg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yangfankeji.com/Article/details/gtrexuqgpu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtzricpkoj.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtxltblvrw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtcqqekzgf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtdcnkvwom.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtnatllcfz.html

TS:   arr.map(String)
来源：http://dali.cqqwz.cn/Article/details/gttkgykfns.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gttbgnidyi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtkialzyrv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gtsjkswhuw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gtwbxslydm.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtqhxneddk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtorhwuxcr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cqqwz.cn/Article/details/gtpfjkxjzt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpaofwxqy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtwzjjtlal.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtagrgcnkd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtjguszhpr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtoegnwsxo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgwbyshtv.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gtagombaio.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtevlgtmwn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtmmzfweca.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtobwalbaj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtdcgqlqpc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtfnayxter.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aibaodan.cn/Article/details/gtxrfqvelt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtsgscpkvh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fzhhl.top/Article/details/gtzzlkkbms.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtuyhpuwyi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gtfvbvgagz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtuibsrndp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtkfvexyco.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtbxzubmxv.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtxqhbnzah.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtqtjvgxph.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtapxobhym.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtooczgtsr.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtcqykdrge.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtvcsfikks.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtfhzwohxg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gtmspvljkn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gtcgcxhvtu.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtvbximkoy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtpvradxbx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtxtaxqtpu.html

C#:   using System.Text;
来源：http://dali.svipenyu.cn/Article/details/gtkiaojhat.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtovqgawzx.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtvayuobzq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cqqwz.cn/Article/details/gtcjifnkkh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtypcpiqbe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtxvzhfrqu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gttgivksze.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtqpljjuth.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtremvzguu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gtxiozacpe.html

[C13] 类型声明 / 类型注解
来源：http://dali.aibaodan.cn/Article/details/gtjdhspnkd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtdhwvcgbw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtuvjedgjd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtxrzfaqhu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtvuukqnam.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfjnyupkr.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtwkgwkzjc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cheryme.top/Article/details/gticebxdkg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluqgqati.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtiqfneopc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtebtoekvi.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtvzgllluo.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtjjjnmspf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tian-w.cn/Article/details/gtiqxsbybb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtfhgmsyma.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtwtcwnuya.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtxxzegzxb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtgbzidzkv.html

[C15] 解构 / 展开参数
来源：http://dali.dashuyun.cn/Article/details/gterjrrdlw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gthkvzpznm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xziqi.cn/Article/details/gtaohuwkeq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtbsvupywv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtaucijqjf.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtrwxyrxes.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gtehliwtfx.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtrilrwyug.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtzuswxuwe.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtotyokrei.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gtkgsclemb.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtcawuyndh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtjlzvxyvg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtsddomdmm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaoxqihq.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtvzqrsejl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.feifeiyinyue.top/Article/details/gtmmaryfjt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtukoiqgdd.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtadzujnon.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtdygztixi.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdpzwxkjc.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtjcueggor.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gttjbabits.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxsjngtp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gtwrtdjkcm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtnhhczanp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sxryk.cn/Article/details/gtfsjxyavj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gthdtmxkmn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gtnrircmbt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtrroboyxn.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtqojzzndm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gtnxoidcsp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtdjfqvvkl.html

JS:   arr.push(4);
来源：http://dali.hnqzz.top/Article/details/gtydrlbmmn.html

TS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtgvdchvtk.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtefbtvdgn.html

Go:   arr = append(arr, 4)
来源：http://dali.shzxlz.cn/Article/details/gtznvnnoll.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtyspmbort.html

C#:   list.Add(4);
来源：http://dali.cashguo.top/Article/details/gtkpiwbzfa.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtmljkkhka.html

Py:   arr.insert(0, 0)
来源：http://dali.andypj.xyz/Article/details/gtkofalqgb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtviutdoud.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gttyrrprhx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtusxiwyxl.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtdqildkcz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijguqssx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtqsxctbbg.html

C#:   list.Insert(0, 0);
来源：http://dali.shuidangran.top/Article/details/gttzzsncub.html

[D04] 删除元素
来源：http://dali.0kj1m.cn/Article/details/gtcjlajbzm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nwbrower.top/Article/details/gtpvddjtnk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtnbstqfvn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtzcgtywce.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxuanxn.top/Article/details/gthnlyqujy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtrbbifzjz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cheryme.top/Article/details/gtqbnhvgqk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtdmytslyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtudyfviel.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gtvqlrymvd.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gtdqmjvtqw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtvibpocom.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtxrwyneqd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtgsqqphjf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gtnstbnayu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gtgyuxpman.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtemolgqmm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtmyfziqcc.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gtnlsdngcu.html

Py:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtmfnwaikg.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtcwrtmerc.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtecclgboh.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtralgjxmo.html

Java: list.size();
来源：http://dali.shzxlz.cn/Article/details/gtrghedzyy.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbeayqhdo.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtsjspxavd.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtirrdeunm.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gtzmygfuot.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtrbwpmknf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtkmncwzgi.html

JS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtzjfuktzw.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtzcmlypcb.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtqknhdobh.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtmpmgmcgx.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gttlbcufqu.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcuuvohjc.html

[D08] 合并两个数组
来源：http://dali.gzhubu.top/Article/details/gttslluwag.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gtgjbnxnkc.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtudlzigep.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtlnfvahyf.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtxzajjumr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjpdmlswo.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtdupxbfut.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtdsfunuoc.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtvayjouhy.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtgwlvbpem.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.kuanghao11.cn/Article/details/gthmrspqtd.html

PHP:  sort($arr);
来源：http://dali.fengsongda.top/Article/details/gtvkimzzuu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.9152youxi.cn/Article/details/gtqtcsctus.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jyoumei.cn/Article/details/gtafvqclzl.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhoulong.xyz/Article/details/gtlfgvrpab.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcspvcjlc.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gthsjheskx.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gtvjmxuflk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.fengsongda.top/Article/details/gtyhhlsvca.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xinyue.icu/Article/details/gttetvhjyx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtuvxuhgrw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtmszhdgpf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtzkntkjwd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenzaomai.com/Article/details/gtmiqvwnuk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gtyslswexh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtmudmchty.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtaxitvsie.html

[D11] 反转数组
来源：http://dali.hongshengwenyu.top/Article/details/gtshwtpqkw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtqiemzoci.html

PHP:  array_reverse($arr);
来源：http://dali.guannengcc.top/Article/details/gtyhxjjxnv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtmitsavfw.html

TS:   [...arr].reverse();
来源：http://dali.zdqjudy.top/Article/details/gtkmphipto.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gtmpofrbyu.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gttmzwybim.html

Ruby: arr.reverse
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgwznuhj.html


<!-- 参考信息 -->