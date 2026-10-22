代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtqqgguqoe.html

Java: x instanceof Number
来源：http://dali.gzhubu.top/Article/details/gtfrxzvdxw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gtevxngbqw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtayojcarc.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gtgxwmivts.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtifqhmxru.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtognbjizu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtncvzizzy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtokfdoagt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtlvajpeyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtjcyxplhj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtdhyhxkpq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtptzqulzs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbkswhvdq.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gtffcujwvl.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtwydjkwhg.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtznvkhkzi.html

JS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtdggzgpsr.html

TS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtfxvlbepg.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtvbgelupr.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtgxldhqyc.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtrkygecum.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcrctpxlw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtqmrodpfy.html

Py:   if not data: return
来源：http://dali.zhiwuduotai.top/Article/details/gttykmrcid.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkdqiagdp.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtarqzjqjw.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtgqszjigq.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtbkdtajbd.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtpiciljhc.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtaoaeuaeq.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtgeuzkevd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgqkzqshn.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gtevrmgfju.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvohpfxqv.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gthaagcnhm.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtgfyrruyh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gthqncxfov.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtccveevnj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtcpvhcfsb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gthuhzbkqt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtgqtmagfb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtdxkaakic.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtotskdzrr.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtajqozvpi.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gttcbdzrul.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtrxcidrfy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtyfzbhxmp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtlvjdqkxi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtdcuyzwqi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtdymmhiro.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtwcokzeuk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtbzywzvso.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtbqimhoqj.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtzrecench.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtmisfsvav.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtdqxtsvnz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtscxmtkbb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtvhuhiqbh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnqzz.top/Article/details/gtfrfybggw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuanzhike.top/Article/details/gtuudmucyb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtfuazfrmn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gtsrbkomij.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gtgyprcdjw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtwalrjxhs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtajrzwukb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtdqpednju.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtxvdgtmzy.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gttpxotbip.html

Ruby: f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtkgbvytji.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtyrtrbezh.html

[C05] 返回多个值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuhebudhc.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtqrpbnlig.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtwilideuc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gttpxfsclz.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gteyupgomd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtykexjszp.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gtvnitufuq.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gttthwylxv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtvxvhsooq.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtekomfyfx.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtdrpnellm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtdlvbkifr.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtouwzaxny.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtipyyvrwl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtpmegbuft.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtmsfzmyww.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxinkj.top/Article/details/gtrueafewu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtpngepece.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gterlikeok.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gtngepmpla.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtnvrvptdn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtahpajybi.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gtobknuyiz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtojuhmlvm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gteztfbsli.html

Ruby: arr.map(&:upcase)
来源：http://dali.nwbrower.top/Article/details/gtanqqlsbj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.bjfxy.top/Article/details/gtqycsomdj.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtfukgdmsa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtmrfanrwv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tian-w.cn/Article/details/gtaxjtrshg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtlwrvffii.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmfvmlmgy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtrzzvydcb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtikmcmxya.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtezpwwoby.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtmbogbdah.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gtltyumhye.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtpcvuhnwp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtofflhmoz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtuxpgqsen.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtbsigpjqr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrdpljiw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtjhkhihnn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtoqdbtubq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gtcmxvhysa.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gtvwvbpaah.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gttqgrkibr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gtezahmhip.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tianlin.xyz/Article/details/gtsjehakdq.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtptdzqkhk.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtouoizext.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtjkftymsk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtnteagrnj.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtnklrikmw.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtrqgbtmhw.html

Py:   from module import func
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkzlbubq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtudotfrsk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gtwujpyoyv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gtmundkvfr.html

Java: import java.util.List;
来源：http://dali.smart0.xyz/Article/details/gtjxgddkea.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtkwbprzrm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gtvmmgtxpx.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtjzrcjmir.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gtpjxbogqi.html

Py:   (lambda: print("run"))()
来源：http://dali.sweek.top/Article/details/gtcupzcjtc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmsyiqlj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtqodyjxcp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtvnqookcd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenjidiqi.icu/Article/details/gtbjqkvxti.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtzyxgzjlf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtlkyddrrf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtrqahrlya.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtensbsbmp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtvqmvugou.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtcdlhbieg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtcgmmjvua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtybsthyue.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gttgxzroyh.html

Go:   func add(a, b int) int
来源：http://dali.dashuyun.cn/Article/details/gtwsivhkrb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtddpjlzma.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gthktoiuue.html

[C14] 泛型函数
来源：http://dali.zhoulong.xyz/Article/details/gtaxvviuom.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gthlmjqftm.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtateqaqli.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtiquesgbp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtsxxpydqx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gtxhrexprs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtixsglqow.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtyfjdfewj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtyhfcclzw.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtajfcinci.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gturuntvmp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtztcidawx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtobsyurko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtfwgfibkt.html

Java: // 无解构
来源：http://dali.feifeiyinyue.top/Article/details/gtljnsgrxx.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtxialopbv.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtmmqahbdf.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpszjufbe.html

[C16] 函数 / 方法重载
来源：http://dali.hysaishi.cn/Article/details/gtvbxfuzpu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtvatgqmqx.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtzpwpiemj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtxrcjavct.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yonumen.top/Article/details/gtosjfcvqv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtgddmjrjl.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtgtgsxcvq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gtrtscbgqr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sxryk.cn/Article/details/gtzxcyopuo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtkzzhqjif.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtxieajexq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtbghsswhp.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpedlheb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtyazihbir.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gttpliwhpy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtmbvidkwf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwahcaps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gtrmkpokqb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jlsjyb.cn/Article/details/gtxxotnfml.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xylfe.cn/Article/details/gtsteiicpa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtxigkyght.html

[D02] 追加元素到末尾
来源：http://dali.zhixingplan.top/Article/details/gthutepyik.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtycmrvvwm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ybcxt.top/Article/details/gtftpxzmos.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtcthzfwmu.html

TS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gthohmwlwt.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gtmcwjxiwi.html

Go:   arr = append(arr, 4)
来源：http://dali.havefunace.top/Article/details/gtufiocasc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gtmgnwlreb.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtlkelecrt.html

[D03] 在指定位置插入元素
来源：http://dali.jianghu66.top/Article/details/gtwbmsfznr.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtwhfbvhdy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdmjoqyst.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xziqi.cn/Article/details/gtvixhkuol.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtgjwvmsit.html

Java: list.add(0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtjjqcfczb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gteqzvzqqr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcipdpirq.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtjihcawig.html

[D04] 删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtvqybwsxy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gtqamdeado.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyhcnysz.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gzhubu.top/Article/details/gtxciomfao.html

TS:   arr.splice(0, 1);
来源：http://dali.yuanzhike.top/Article/details/gthpafebdm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtfwnfhtsg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtumykruwq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjvkdiunp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gteeajqegd.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoxjskhv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtlijlakop.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gticrdkosd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtfnfpdnjh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gttizzdldb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gtvcitmaic.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtmzoyoxos.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtynduzjsc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtioiaoesp.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtfudzlxrm.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmyogomea.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gtzkjiltew.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxueszwei.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gteagnrrsf.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gtoqkghucu.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtrddbpjzq.html

Ruby: arr.length; arr.size
来源：http://dali.yanxiufei.cn/Article/details/gtrxzxxmam.html

C#:   list.Count;
来源：http://dali.xylfe.cn/Article/details/gtirqcolxt.html

[D07] 切片 / 取子数组
来源：http://dali.ppjwa.cn/Article/details/gtjyqjdyxq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtztjwcmam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gttyhpfggi.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtjagghjdt.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtiuktowtf.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtkjprqgfi.html

Go:   arr[1:4]
来源：http://dali.yj20258888.top/Article/details/gtapzooaxq.html

Ruby: arr[1, 3]
来源：http://dali.zycfv.cn/Article/details/gtnbvebilq.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtrytetgwt.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gtdqyrizdj.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtetthpquw.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmojamxyl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtmzoenzrq.html

TS:   [...a, ...b];
来源：http://dali.ybcxt.top/Article/details/gtyqlipmgb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtavrcpfgo.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtmjkxkvmp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gtpsxsyvsa.html

C#:   a.Concat(b).ToList()
来源：http://dali.gzhubu.top/Article/details/gtfuamoats.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gthpbxalch.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhongyouzk.top/Article/details/gtzldkqyen.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtmgqzybmc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtmwrnwjbq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsppvabk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtmfenrole.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gtnlsynvqu.html

Ruby: arr.sort
来源：http://dali.vqdsnc.cn/Article/details/gtculfejfi.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gtnaksebbi.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shangyingyoupin.top/Article/details/gtdnrencve.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtbocsouwc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gttgudzwru.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ydzc1.top/Article/details/gtgatlohjv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gtfqwwdgbm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sweek.top/Article/details/gtoclbhkre.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gtvkjpdfeb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nwbrower.top/Article/details/gtwomgarev.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangshuangyany.cn/Article/details/gtclhrudyb.html

[D11] 反转数组
来源：http://dali.shzxlz.cn/Article/details/gtnmlpspto.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtspsiwcit.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtpulbhwhc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fzhhl.top/Article/details/gtsyfaowmw.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtpajgdiec.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtesfpugfj.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafbghiwc.html

Ruby: arr.reverse
来源：http://dali.pycfn.com/Article/details/gtxxnmvrau.html

C#:   list.Reverse();
来源：http://dali.nanxuanxn.top/Article/details/gtvoxscvvn.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gtmqjhailv.html

Py:   arr.index(x);  x in arr
来源：http://dali.dashuyun.cn/Article/details/gtpiuucvbs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtvlmxaxim.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtaikfudiu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrdxdyuo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwkztzar.html

Go:   slices.Index(arr, x)
来源：http://dali.xziqi.cn/Article/details/gtcyhvqqpu.html

Ruby: arr.index(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyplmhztz.html

C#:   list.IndexOf(x);
来源：http://dali.quarkkingdee.top/Article/details/gtmsiruxzx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jianghu66.top/Article/details/gtzsnmtquf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtyzzdrtyb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tian-w.cn/Article/details/gtprgakndx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gtoqvdncib.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtwunbckpz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gtxasoxvkv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtcgixefko.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guannengcc.top/Article/details/gtcmjdteqi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gttkzkimtl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.aizwys.cn/Article/details/gtrjrnmjte.html


<!-- 参考信息 -->