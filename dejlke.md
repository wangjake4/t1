代发 wailian999

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtzsgkaylt.html

JS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gthgwwfgmx.html

TS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtnvmxygdk.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtahhlimnh.html

Go:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtpoqlqqph.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtcvhjtpmy.html

C#:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtsdkclzjr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.aizwys.cn/Article/details/gtmqgtrvki.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gtzfuxcuns.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmtqjtfdj.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtszevoibv.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gthhbhbeow.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtjifdszbz.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtfysmuzuw.html

Ruby: return if data.nil?
来源：http://dali.c1oappe.top/Article/details/gtfhnoxkch.html

C#:   if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtogqjkkzw.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtjdzixfhj.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gtijxveyup.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gthbrsyzvm.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtdhzhahwq.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtirvzgxhe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtgrzplhyl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtaukqibmr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtdistuofc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtuilkywlv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtalkjrlay.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hammf.cn/Article/details/gtmgzdmbqn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gthxwfwlkm.html

[C02] 默认参数
来源：http://dali.nwbrower.top/Article/details/gtxnzknsre.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtiiuxhtwy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtvdyijebn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtomrequqh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtzfuwunxg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtsxvoraik.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtkibjemod.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtzjrqqxot.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvphsbsux.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtkreiulwx.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtnmcsgsqe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtfecvvxir.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtvakzflke.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtgcsqgyuu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtstzulcyp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtwhxmfdxg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtncqmvlan.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.iojbl.cn/Article/details/gtlzrdpttt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gteajwdkjf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtoipmukpn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gthfzibamt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtxyfycdxw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yangfankeji.com/Article/details/gtilsxrmoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhemdrhf.html

Go:   // 无：用配置结构体参数
来源：http://dali.daria6918.cn/Article/details/gtepqecsab.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtiwqgqzxo.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtekqgmzdh.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gthvierroj.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtxluwkuwm.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtyghrqtaf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtaiozhiwl.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtusrdrftu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtvhdnbxfx.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtoxgsrptz.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtwwpgqwrf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gttnutipxa.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gtmgvrdcgh.html

Py:   square = lambda x: x * x
来源：http://dali.chenjidiqi.icu/Article/details/gtfabmhjaa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtcoaissrz.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtcqtzxxkm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtsavpuhdx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtvkcddhkj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gtvznxsqtg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtwacjhniu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtuxsnlyzw.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtonzfgucz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtowfvkyio.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtgahdggdg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtixgjbbku.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuudtcurb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtjofwinqg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gtqqpirxkb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtuhxeldpa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gtdgduqyqa.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtqaaelqnv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtwkcezypa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtrqrkksov.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtbbujudhm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtvsekjliz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gttqvhdwtt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258.top/Article/details/gthsmrhzni.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtqfipogog.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtspwuhmix.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gtasxttsmc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtvlcskmqg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtkdkmwjrh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtkodqrlsu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtuvfogekh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtwbhkskwm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawfdsfmt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtcjqbsoei.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guowangkeji.top/Article/details/gtdwyvqyux.html

[C10] 变量作用域
来源：http://dali.yuanzhike.top/Article/details/gtecfesxbb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtjzjoudjj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtfflecymq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtdumrmiks.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gttlmciupz.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtpyittbxd.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gthwreibxa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtxgqbxscc.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtonokmtko.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gtghuhzwhm.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gtsozglblu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gtkzbqbknz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtmturnrvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenlongwang.top/Article/details/gthgwsjrsu.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gttycwtgzs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangdashe.top/Article/details/gtijhbkvgd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hywenlv.cn/Article/details/gtjktebznf.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtlkxgcztb.html

[C12] 立即执行函数 IIFE
来源：http://dali.hongshengwenyu.top/Article/details/gtvehgihsw.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtonxtzxgq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gtnsweukbc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gtfuetxzrf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gthagnduvl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtjotwcgqf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtzhayfojo.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtcbrljtcr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtehidcfhw.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtxlvvgbgw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtfkiemgoc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtylnggjyn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtuoktaniz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtmzhrdyoz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gticgpozuz.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtwhxwbtpt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtfnybqqqw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daxiang520.top/Article/details/gtuucglzhb.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtdtqshitk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258888.top/Article/details/gtbjljgcoy.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gthlqsxwon.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtfitnsvxn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckyfvifp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.9152youxi.cn/Article/details/gttqsszdpw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gtqpzbqjjx.html

Ruby: # 无泛型
来源：http://dali.cdnleiting.top/Article/details/gtzbugqqds.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shzxlz.cn/Article/details/gtebzlsoee.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gtbegnxyaa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtfciststc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sweek.top/Article/details/gtcylqajev.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gttgkvurwb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqchxukr.html

Java: // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtlwfmbqrz.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gthrxpkegs.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gtvuywfrla.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gteeuwjugs.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtfhhhyjat.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gttdgizoug.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtbhvxogjy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gtkitaycqr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtwolpsgna.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dianchejie.cn/Article/details/gtfrxvrltw.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtgmiasqro.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtcayuzzrp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnyjpsmo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbtrxeumc.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtrnwikcdf.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyytsedwz.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gtpylygmob.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtkxdyqpjl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtuymzmaad.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gttnjlfxus.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gtkfanbgse.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtlvfmhdgz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtzdleznpt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtpgoipbyt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gtiivadaen.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtthckixgv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gtpafoiees.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtyxqjkknd.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtelsnqtwu.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtwmurlnsq.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtitnuenhl.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gtusclwkbd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtzypfjtse.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxrtfmpur.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyotqxmlq.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtgeowcjvx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daria6918.cn/Article/details/gtwajtgrqe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gtdxuktfiz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gtqnlshkbi.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtfgtuycjt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtbnehsczz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtouoocfdo.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtikshokoo.html

[D04] 删除元素
来源：http://dali.sufxvd.cn/Article/details/gtmxcskile.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtdbeybklo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenlongwang.top/Article/details/gtyzlpwxip.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shangyingyoupin.top/Article/details/gtwdxbrpvz.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtcqlfevho.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtobvkdhsk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yonumen.top/Article/details/gtjwcivlpm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtxmfhpxfs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtkweduysy.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gtqiqsxkkl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtqwhafcdm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtpofnmoiq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtefhbqczz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjtiaqiku.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gtyrzcqttc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gttammcmuj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gttlokpkfx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtqzfonyss.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gttwdswvlw.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtuelkxcta.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtfxyljnbc.html

JS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatkcnvfh.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtgecpjlye.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtpfuigleb.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtxsabgarq.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtkxfvfqbm.html

C#:   list.Count;
来源：http://dali.iojbl.cn/Article/details/gtqzethbtg.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtzwkeigct.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gthdggywsr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gtkvwjdkpk.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtyngbfmez.html

TS:   arr.slice(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtoyogclrz.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtayxakfsz.html

Go:   arr[1:4]
来源：http://dali.tanke756.top/Article/details/gtqvszhfud.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gtenscjjsg.html

C#:   list.GetRange(1, 3);
来源：http://dali.yvedp.cn/Article/details/gtgrplrivx.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtxeslflvr.html

Py:   a + b;  a.extend(b)
来源：http://dali.kuanghao11.cn/Article/details/gtrqfnwbut.html

PHP:  array_merge($a, $b);
来源：http://dali.gotoacloud.top/Article/details/gtcrexvhog.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gturisdvyc.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtponzgeci.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gtkabfiqum.html

Go:   append(a, b...)
来源：http://dali.daxiang520.top/Article/details/gtmbzihvoo.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtforgymmn.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gtnmussquh.html

[D09] 排序（升序）
来源：http://dali.zhongyouzk.top/Article/details/gtqenydycf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.iojbl.cn/Article/details/gtmzjxcdks.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gtqfsuwpli.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvjklzwv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtibqrkkoj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtcyipnavh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gthujmfqsu.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtyguzshkk.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtoxdbqoxz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gtdvzstmat.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtenvunona.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenjidiqi.icu/Article/details/gtodlabemw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gthhdnznxn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gtpyehfzox.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtvrgmwcgh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtretdssfr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.meibo888.top/Article/details/gtjcqfxwyk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hongshengwenyu.top/Article/details/gtzexduucw.html

[D11] 反转数组
来源：http://dali.tianlin.xyz/Article/details/gtascwrybh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtdswcdtrs.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gtlmuhrkkt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtuisqmwxg.html

TS:   [...arr].reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gttrkkhmmr.html

Java: Collections.reverse(list);
来源：http://dali.zhixingplan.top/Article/details/gtjazgtgfp.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gtajwhdlfo.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtjmycrkaf.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gtpzoiromg.html

[D12] 查找元素下标
来源：http://dali.gzhubu.top/Article/details/gtaybjrken.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcvzrlwyb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gthiulpvpx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gtofylerhj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtmnmpkjfy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gtbqgqhjiv.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtwdxambca.html

Ruby: arr.index(x)
来源：http://dali.guannengcc.top/Article/details/gtubdsllkh.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtokujwdmz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthlzfrqj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daria6918.cn/Article/details/gtxomrqats.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxinkj.top/Article/details/gtcwhjslzp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtlsuyzjyu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ybcxt.top/Article/details/gtfchukhfa.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ehwqpu.com/Article/details/gtjhuatkou.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtcpkbcffh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jiagoushi.top/Article/details/gtlumwwltv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gtzsgauvoy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258.top/Article/details/gtyqokkmhf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gtnnehrghf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gttuateiks.html

JS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtsdfiaaup.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqelnbdp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtgpplwgqx.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gthtofnajn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gttktiqomw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtfrsebuse.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtajcmgwuq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtawlieuox.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gthyxqjdix.html

JS:   [...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtjdeuvwij.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gttzkacdzn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtpybcqvyi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gotoacloud.top/Article/details/gtavysjpxt.html

Ruby: arr.uniq
来源：http://dali.jqgufenzy.top/Article/details/gtnzcggphb.html


<!-- 参考信息 -->