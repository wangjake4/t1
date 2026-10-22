代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2svhjqjoj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dashuyun.cn/Article/details/gt2nvnsyazk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyxvgxks.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gt2ttqdamwe.html

[B13] 判断是否为数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2zdhcsrov.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gt2dvqugnpg.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ytnculfl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tyctzyxj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2tlhyxyku.html

Java: x instanceof Number
来源：http://dali.yj202588.top/Article/details/gt2uqnpqcvn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shuidangran.top/Article/details/gt2jvvogltp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gt2ijppgwpd.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gt2nlrxwulk.html

[B14] 判断值是否在集合内
来源：http://dali.cucudq.cn/Article/details/gt2zkpmucbz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gt2abqbqbma.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xsfqsotx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2sgzxinmm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ebhfailt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tianlin.xyz/Article/details/gt2efllcunc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnxiangtu.top/Article/details/gt2mvqhhcsk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gt2mocrfahb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gzhubu.top/Article/details/gt2wttlyuns.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gt2jmrmwfoo.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gt2ealbqarp.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gt2winomttn.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gt2rdgnifrb.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2ihaxnaoa.html

Java: a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2xejlcvxg.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2lckqanoa.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2exgrwgba.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnnwynxi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2ynkbpgyh.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wxtlixuy.html

PHP:  if (!$data) { return; }
来源：http://dali.ehwqpu.com/Article/details/gt2rvehtuoi.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gt2eigmfxjz.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2pdrqgonn.html

Java: if (data == null) return;
来源：http://dali.c1oappe.top/Article/details/gt2mdnxqwlb.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gt2axghvxvd.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2pislprgi.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2ihdaqznf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2bkpctgla.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gt2afnmdkjl.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2ioleblzm.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2agatawit.html

Py:   def add(a, b): return a + b
来源：http://dali.chenzaomai.com/Article/details/gt2urcjthwe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2kozlstwl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2hucjlhdt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2hbevgbtw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2jpucyvwj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2uksbplhh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.andypj.xyz/Article/details/gt2divcjqke.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2mymuhljw.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gt2cljpdwaq.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gt2siqtcvmf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uwihpwvp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gt2ouwpaehs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2xguephyj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gt2ngeiufqd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gt2nudnqovm.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gt2tckumpkk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gt2yhuxdrmu.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2tplmwplz.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gt2tiitxcyb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gt2orfyjtof.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2jdlltadw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2pwgqwjrk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eaowkqsm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oufpwzwv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2hmecoehm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2lxwqkrbo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tian-w.cn/Article/details/gt2keskhqsj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gt2mzdowvxu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gt2qlaltwib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2lcabspem.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gt2gicayupi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gt2kwufcxgg.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gt2pmqinyti.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gt2wsxvksuu.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gt2ktpcvehm.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gt2ewktikba.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2favaxkza.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2doturbwb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gt2klhcptbd.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gt2jaecfpxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gt2nycgqeeh.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tanqvjck.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2qmxghlxx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2uenogsvm.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rrjyplwh.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gt2eixvuoxm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guannengcc.top/Article/details/gt2ppiyxrqp.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2hijesvee.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2mtlutjzw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daxiang520.top/Article/details/gt2czcksoms.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2zgzmnnfx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gaohongyu789.top/Article/details/gt2neryhwkc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gt2fwhflvkk.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gt2rxornmso.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jejxevqt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2bhxtopbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gt2qqolxugr.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gt2ypdwstig.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2wwjlrtqe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gt2mhamhcoz.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gt2whiiuzsv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2ajgyvern.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gt2kvhrqzcs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gt2orbpkqyu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nwmzcjas.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gt2serfbiix.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ebvsrffn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gt2ucjppzew.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gt2yjzpqmnb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ulqxhukh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gt2enwdomwy.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gt2sppatwhj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gzhubu.top/Article/details/gt2valmjdwm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hilercho.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gt2zgzwwtos.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2tircztzv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2euynwohg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gt2jymaiixi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gt2wmvkceop.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhixingplan.top/Article/details/gt2rxucbqyr.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2wimqnhhq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gt2erpkohwl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.feifeiyinyue.top/Article/details/gt2xydakyab.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2zepawesx.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2ywswnikr.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2poawdtxh.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2hedwvdgk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gt2psotqgnz.html

C#:   块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2kcbhycfi.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gt2nxoqzsax.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gt2wsktebul.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2ruzbxulo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ayduzhbf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhijiandao.cn/Article/details/gt2sxrrftgy.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ospctkdm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gt2imtuxddo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gt2bgjtprnt.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gt2crwjnybr.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lucojkoh.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gt2hefmwrap.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gt2skyueoly.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjmgbokp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2kojckjuu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exafzctt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gt2tndtoyue.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gt2otqmvvbb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xinyue.icu/Article/details/gt2dqaazpws.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gt2oirhhoyw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gt2eehwfqxs.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2psnbogpw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qzhjarsf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gt2ihpiehvs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2uzdtigbq.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gt2fwwxdfwm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xziqi.cn/Article/details/gt2kembnjpx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gt2lycbcnha.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2glbcrxux.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gt2vbjwqcfz.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2pitcfhns.html

JS:   // 无泛型
来源：http://dali.havefunace.top/Article/details/gt2jqekfjyt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gt2ihlifnmh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfyxvkow.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fengsongda.top/Article/details/gt2pzvukrin.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gt2nmlmelfx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gt2trhaauta.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2iaucunoo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenjidiqi.icu/Article/details/gt2jroqtdzx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2buzudavq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2isclryxk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gt2rjhppshf.html

Java: // 无解构
来源：http://dali.birdmap.top/Article/details/gt2naqyakaz.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gt2rbkhahbw.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2wxwtltim.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gt2wumqsgla.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2agsboiwu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gt2qnqobpnc.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gt2pukxwruv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tianlin.xyz/Article/details/gt2pfmcokve.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gt2hslbmrbs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2keketgib.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lguxeslv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gt2rzeidiux.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ofuksqpn.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2hgfcgwlr.html

D. 数组 / 列表 / 集合
来源：http://dali.sysykeji.top/Article/details/gt2cxqbprxd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2uxsrkecd.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gt2lyawwsqj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2csppkhmn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gt2nkptwdiw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xylfe.cn/Article/details/gt2dmfeldjt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gt2lemlyijz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gt2vdkkgoqc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2zbtchhxs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2ylkgulxg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gt2xktvzvzx.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gt2rdrjoquz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxuanxn.top/Article/details/gt2afytxryr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dakhcmig.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gt2tdrdleaf.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gt2rgnlumzd.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2rpxbpurq.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gt2lqcincfl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zycfv.cn/Article/details/gt2fkieztui.html

C#:   list.Add(4);
来源：http://dali.yj20258888.top/Article/details/gt2zundxjdc.html

[D03] 在指定位置插入元素
来源：http://dali.fzhhl.top/Article/details/gt2gikzttbd.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gt2kubybrev.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gt2oeqahbds.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2rvwruaei.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenzaomai.com/Article/details/gt2mnruynlp.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gt2axvvbfuy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2yrqbvtnw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gt2rxqyoljs.html

C#:   list.Insert(0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2vxzhsdys.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gt2qrwpfncb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gt2qgdydhac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2bywlanji.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangdashe.top/Article/details/gt2afncxohv.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gt2ipfusmgy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gt2llgaaouf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gt2sjjnraxy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yj20258888.top/Article/details/gt2cyljxlds.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gt2usipazfi.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gt2fgtdcnsk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2lzgktfvz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2vxqtkvcj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2ycdkpqpi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cqqwz.cn/Article/details/gt2snritamy.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnxiangtu.top/Article/details/gt2tdgqxlqr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2lwcweakz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gt2vjljypuo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gt2oanrbcjl.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iptuynfi.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2fcmwzmxx.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2fcgimbjg.html

JS:   arr.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkeyjbqj.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2agbvzbuj.html

Java: list.size();
来源：http://dali.zhoulong.xyz/Article/details/gt2uaichqpp.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2fsdfxtxj.html

Ruby: arr.length; arr.size
来源：http://dali.dashuyun.cn/Article/details/gt2xmnuubtq.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gt2knzredaj.html

[D07] 切片 / 取子数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctoavbrr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gt2saxwftas.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gt2gfpvaukk.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2eskqzvya.html

TS:   arr.slice(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gt2zcuwnzeh.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gt2fotawysi.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gt2vnhtyzmr.html

Ruby: arr[1, 3]
来源：http://dali.yj202588.top/Article/details/gt2iwmwmquv.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gt2nvdufqlv.html

[D08] 合并两个数组
来源：http://dali.shzxlz.cn/Article/details/gt2kqgpdbre.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2drqgvhof.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gt2lpdzwdsx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shangyingyoupin.top/Article/details/gt2cipwwdqe.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gt2ooppqdyb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2fyzhsofl.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdasiuhj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guowangkeji.top/Article/details/gt2yqlnupdb.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gt2dppzbnns.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gt2wzrwgixb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.havefunace.top/Article/details/gt2veqfgxtr.html

PHP:  sort($arr);
来源：http://dali.chenzaomai.com/Article/details/gt2jaaweapo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2kkglaiae.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.316326.xyz/Article/details/gt2lewhsoly.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shangyingyoupin.top/Article/details/gt2twrlapzk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.smart0.xyz/Article/details/gt2oztzsrpx.html

Ruby: arr.sort
来源：http://dali.hnqzz.top/Article/details/gt2xzhdrkwq.html

C#:   list.Sort();
来源：http://dali.aibaodan.cn/Article/details/gt2gcmmqqno.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yonumen.top/Article/details/gt2jtdnscwv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jteqnsjy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gt2lwcefnnm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2ghomgtlo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ywcblppu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2xdvdwszv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gt2nttucvus.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gt2eoogbaza.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmibjcgi.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gt2kzhbksbh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gt2jxqexyzz.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ztsppbff.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gt2ckcvozko.html

TS:   [...arr].reverse();
来源：http://dali.yj20258888.top/Article/details/gt2ieeekzff.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2cvhitbup.html

Go:   slices.Reverse(arr)
来源：http://dali.yueranfly.top/Article/details/gt2dryovimq.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gt2usyyobgq.html

C#:   list.Reverse();
来源：http://dali.ivvv.top/Article/details/gt2ucqyklpg.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2hzctufcu.html

Py:   arr.index(x);  x in arr
来源：http://dali.jyoumei.cn/Article/details/gt2gimygxod.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2nujumjvt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gt2wyoumtrk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.daxiang520.top/Article/details/gt2knyqdhmf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.316326.xyz/Article/details/gt2msygvhdr.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gt2igebhqgw.html

Ruby: arr.index(x)
来源：http://dali.jqgfzy.top/Article/details/gt2toirewll.html

C#:   list.IndexOf(x);
来源：http://dali.jinqigufen.top/Article/details/gt2bsrpthms.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sysykeji.top/Article/details/gt2atvkwfai.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gt2wvkunlrf.html


<!-- 参考信息 -->