代发 wailian999

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gt2tqfjejpy.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gt2gfrrbonq.html

PHP:  is_numeric($x)
来源：http://dali.yuxming.cn/Article/details/gt2tqaouhps.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gt2zgskniwq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2rmrbpqoh.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gt2benabwob.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aizwys.cn/Article/details/gt2ldxhxkoe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2tkizuyvy.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2fsaxqoto.html

[B14] 判断值是否在集合内
来源：http://dali.guannengcc.top/Article/details/gt2mhmpjrws.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gt2qeztjxkv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gt2zbumjlck.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2iheqraue.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2tsgivarm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cheryme.top/Article/details/gt2hxlhczjs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2bfcqcngl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2sgcovzwx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gt2kzxdmlrc.html

[B15] 布尔运算与取反
来源：http://dali.sysykeji.top/Article/details/gt2ugathjpf.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gt2giffcuqc.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vxhghoog.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2ynfsqtic.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2srdzpunu.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2iicsrjmz.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2fnahcrfb.html

Ruby: a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gt2gaxdudsf.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gt2lnuczloi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gt2uhkxnsby.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gt2bducwuxc.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xwlnedoq.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2pdbendsl.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gt2vjoqhqpq.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2wfwyogsy.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gt2ukzaonna.html

Ruby: return if data.nil?
来源：http://dali.sxryk.cn/Article/details/gt2wfxwopjc.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2rmkrlznr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vpzocyih.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gt2zrmgrmdz.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ydvmxynz.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gt2sbysnvat.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2jxmegpqk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2sizamlnd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yhyclykd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qsyyjsll.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ihjmkcaj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zycfv.cn/Article/details/gt2whbmfqxl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hywenlv.cn/Article/details/gt2wxinqwqi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2ookfhjjn.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2phwjljwo.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2jddgthwz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2hcuzyhbe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2pxmmicwg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2qjupexxu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uyqfddyy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zjrckcar.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gt2oniotboh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2oibvaukz.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqvrosaa.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gt2egflyfdp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gt2klxqyuec.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2hvuubjah.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtvheeqm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gt2agnpiwfj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gt2wsqyfcfu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.svipenyu.cn/Article/details/gt2yrfvvgus.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gt2weowlbfc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gt2fpczajjp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gt2odtdpcqn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gt2usarkzhb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gt2lpcfxlpz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2fijlqzed.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gt2zlnxuptc.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxczpkoy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2afilibrk.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gt2rhpfnzuz.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gt2cbtpdlnu.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2cyujhjxi.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gt2vhzqcwvv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gt2otnggcit.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2zsomqjxn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gt2hnxuimjc.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2moakruiy.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2nwgmtkib.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sufxvd.cn/Article/details/gt2rwzllkhe.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jfhaakjp.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gt2tfbcequo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2lilqngri.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2dgofeuap.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2scumufbf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2nvavuugp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yueranfly.top/Article/details/gt2nkhstyrk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2bkrlvobn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2plvgutxx.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gt2musrboga.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sxryk.cn/Article/details/gt2xknjsxkn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2ggyiugnt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gt2rpcvbpfk.html

TS:   arr.map(String)
来源：http://dali.ybcxt.top/Article/details/gt2pwldrsgx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yangfankeji.com/Article/details/gt2czrmxudd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gt2pwemfawz.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gt2gvjsawea.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2kiuceeov.html

[C08] 闭包
来源：http://dali.quarkkingdee.top/Article/details/gt2cnjunsao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gt2wtsknxoa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mdoffpsd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2zrwkjnzc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2fjgnnqfa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gt2zmsoycml.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gt2mrqcpozf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gt2tgsaafjq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2mqvesnvu.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gt2dvtgwgum.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gt2otvbpigu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2fhesmtzc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2uvnazosh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gt2wlpnbcnh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2azedfqsa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2fwnfgnbu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2geixzfbi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xinyue.icu/Article/details/gt2aclogoin.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2nwjqgvny.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gt2pubibafz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jlsjyb.cn/Article/details/gt2dkjlsvko.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2rrmjwrgo.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gt2ixclbdtv.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2plzscnsr.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2ceijkjpv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gt2wflwiakb.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2ylquxpzu.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gt2yajexxyx.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gt2silecprk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gt2mpjmlxph.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gt2hpkifbaw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gt2namjgcse.html

Java: import java.util.List;
来源：http://dali.redwolf501.top/Article/details/gt2byylhwbw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gt2llolgoki.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2jwkbaddd.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gt2vqiulsus.html

[C12] 立即执行函数 IIFE
来源：http://dali.ydzc1.top/Article/details/gt2etsulqgf.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gt2yxbyvjdy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gt2gekidyqu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gt2rhhxmben.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2tixhvtqs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gt2dcjuyjxr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2jfzxfxqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gt2akblwdly.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gt2keqzuoak.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2lydinyaa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2lxrtmhuj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2govwvnel.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gt2pbvohthc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2cbwzzjsn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2bcaygmww.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2gmglldcx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenzaomai.com/Article/details/gt2fqgcubgi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gt2vtbzadqj.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltwoomkr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2bkaxszvq.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2ouxxfgvs.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrmedks.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gt2bnchbjze.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2xutmgfxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gt2acnocees.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wnwasheg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmdzgzaz.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gt2lmsonnst.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cdnleiting.top/Article/details/gt2zrunvfhm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gt2uoytjhuq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2jsrvxvsg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gt2urxzusxk.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2ilqmpmhh.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2ngbczkuh.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2przgjmqh.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrwppcz.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gt2fyeclwot.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj202588.top/Article/details/gt2dkavsmwu.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gt2jrysogbz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2meysstys.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2hmfjpgml.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gt2nbeintvg.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gt2puhdswpx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gt2xsugysqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gt2pxjuoznc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2ygzqhpeo.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258.top/Article/details/gt2pdbavehw.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2ioyjedak.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2nhhaakjv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gt2vtoywfrg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gt2iilwwcfg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gt2rirerbvf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gt2hwtegibz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yvedp.cn/Article/details/gt2xgnuioja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.mhx1999.top/Article/details/gt2bvpcqtim.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gt2lcavsoon.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gt2euoksopn.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2joahwshd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdewcbvb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gt2xadokhlg.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2awufavsm.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gt2qbntfmnj.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gt2bqtdffge.html

Go:   arr = append(arr, 4)
来源：http://dali.ydzc1.top/Article/details/gt2zkflejxe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yonumen.top/Article/details/gt2cnakadjq.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gt2nyeicgjv.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gt2szwzwzbr.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2cdpucvul.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gt2ypspfvvb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gt2fitquzlw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2gxbqwwna.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gt2fauihscr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gcbjhrot.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gt2qmxgmopo.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258.top/Article/details/gt2gryxycri.html

[D04] 删除元素
来源：http://dali.ppjwa.cn/Article/details/gt2lrujzosd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gt2xtvymtep.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2lkqyidtf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gt2tahcddna.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gt2ezczejlz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gt2wxhvkwzz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2zvpjoeal.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2fadrdqey.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.snrcjt.cn/Article/details/gt2eijhijxx.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2ydgjogqo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dashuyun.cn/Article/details/gt2etdykkul.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2abjcpfhd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxxvggzz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gt2bugqmbsv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gt2uragpkke.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2nlnyqgqr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2qdlkcjdq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gt2cfrafjyf.html

[D06] 数组长度
来源：http://dali.ybcxt.top/Article/details/gt2psgopsbz.html

Py:   len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2xfxzofyk.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gt2wsnertjt.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2ipnrdwmz.html

TS:   arr.length
来源：http://dali.xuetiantiany.cn/Article/details/gt2gimfokaa.html

Java: list.size();
来源：http://dali.gogol.net.cn/Article/details/gt2bfqtrjhq.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2ijquidiz.html

Ruby: arr.length; arr.size
来源：http://dali.ehwqpu.com/Article/details/gt2guovfbqh.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gt2epbwznmz.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2gkainiir.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhengqikj.top/Article/details/gt2lasusgme.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2qdklthfd.html

JS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jakhqdoi.html

TS:   arr.slice(1, 4);
来源：http://dali.hnxiangtu.top/Article/details/gt2sjunkixm.html

Java: list.subList(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2fwjccoin.html

Go:   arr[1:4]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzqaicmd.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gt2ltjmbptz.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2wudftpym.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2tfszcbhz.html

Py:   a + b;  a.extend(b)
来源：http://dali.shzxlz.cn/Article/details/gt2qzxpdpls.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gt2eilfeovb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2ftovffmc.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gt2vklccwkk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjptgnuu.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gt2vuacrhky.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yueranfly.top/Article/details/gt2ixspdfcu.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2ovfypney.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gt2rdohzthd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.chenjidiqi.icu/Article/details/gt2ltylepkh.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2xnstoudb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.vqdsnc.cn/Article/details/gt2vrymviwh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gt2erznaahq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yangfankeji.com/Article/details/gt2qqhfqxpn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2bbmqdqcr.html

Ruby: arr.sort
来源：http://dali.tanke756.top/Article/details/gt2elnqugol.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2znnwtcbk.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gt2epacajjf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gt2tpyofcfw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gt2aoyobequ.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2eyqwdkyh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gt2krvhoski.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gt2hsldvpvm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2utklvkgc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aibaodan.cn/Article/details/gt2vvhwutnd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.bjfxy.top/Article/details/gt2tceynvvk.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gt2qzhjcuge.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gt2nvryuhpf.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gt2euhzfgqu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gt2hgcvzgdg.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2cgbbyeol.html

Java: Collections.reverse(list);
来源：http://dali.quarkkingdee.top/Article/details/gt2mvpmarvg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhixingplan.top/Article/details/gt2hnkbjzad.html

Ruby: arr.reverse
来源：http://dali.meibo888.top/Article/details/gt2orkhpmqp.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fenozgge.html

[D12] 查找元素下标
来源：http://dali.gogol.net.cn/Article/details/gt2eowthzrk.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2inemjjho.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pxomcekt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ifovouxt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xinyue.icu/Article/details/gt2eznsvsea.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cucudq.cn/Article/details/gt2adbqtlbj.html

Go:   slices.Index(arr, x)
来源：http://dali.jyoumei.cn/Article/details/gt2sjntwgmm.html

Ruby: arr.index(x)
来源：http://dali.ybcxt.top/Article/details/gt2vdehnrvy.html

C#:   list.IndexOf(x);
来源：http://dali.zhengqikj.top/Article/details/gt2ivndlsbr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gt2kmxlvzud.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2qfugimbr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.haohaochexian.top/Article/details/gt2uyilvehj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gt2vvkzhnoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2ewssexki.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gt2uzfaldkq.html


<!-- 参考信息 -->