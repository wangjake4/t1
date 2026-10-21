代发 wailian999

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtzfxriglh.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtyypqvpjw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tianlin.xyz/Article/details/gtrnlczgny.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangshuangyany.cn/Article/details/gtzahjxfju.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gthdijuapi.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtshqlswto.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnqzz.top/Article/details/gtmfynarsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtpnynpprv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtwxbuolzq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfuewntsf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtkqxyonzq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtejtzvaxa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtxpughlgm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtzgbdxczy.html

[B15] 布尔运算与取反
来源：http://dali.jlsjyb.cn/Article/details/gttostmbyc.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gttmrpttjw.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtasandsky.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtmydkrkwq.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtsalidway.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtwannvsok.html

Go:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtufhcbujc.html

Ruby: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtzkzvsvmp.html

C#:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtdrejiazw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtvelgybxx.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtqudlkwxa.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gtnigvuqvn.html

JS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtcxsdkfyz.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyrmdbni.html

Java: if (data == null) return;
来源：http://dali.zhoulong.xyz/Article/details/gtciplzktb.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtzyatarqj.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtfxdjzonz.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gthncvyfqb.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtnxbtnojg.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtjnnesosv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtclcmvvpl.html

[C01] 定义函数
来源：http://dali.xziqi.cn/Article/details/gtwqeutwly.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gtiampyowz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtssrxxorb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtjxbdmxvx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtxcgesqsy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gttohggqnd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtfsltfjmk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtgrihvxft.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtgeozlrtz.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtusqlpqwb.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtspzdasaq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtucryukyx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcgasfkvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtcifphsou.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtnobwoias.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtovsbwlxv.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnqzz.top/Article/details/gtrpbmsxqi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtvlrfzsxv.html

[C03] 可变参数
来源：http://dali.zycfv.cn/Article/details/gtahbwlqew.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtgrdgasaz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtvdfqxqfa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtzcojriyg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtfobdrazk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoreivnyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtylpvjcxn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.kuanghao11.cn/Article/details/gtyitowfvy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtjwcdwrnm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gtnqvcuqsg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hysaishi.cn/Article/details/gtgzqbohhi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gthotzausk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtczlpwvaj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtsykodbxo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtamnjyarv.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gtryuhjgiz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtymxncqrz.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtwbthtaxh.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gthleovwca.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtungyzldr.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gtokelaeel.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigufen.top/Article/details/gtwtmlehhu.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtmeloxnwb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtsnkmerhe.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtmohrufko.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtklpfcojp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtxvilcqav.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpksyvqw.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtlesrojwa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtkaepfaip.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyryyfbdx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtaiabbhye.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gtwjdpiwlw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtzqjlinlm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtdibqfmvy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtinsidblg.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtngjltztm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdtefxzhm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtikesirlp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gthkwoiyiv.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtpvzveaen.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtubvzpxln.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtejrkgzdu.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtrjpskqfj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.havefunace.top/Article/details/gtsavqnjir.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gtigmojibf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gtnjpclzho.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gtmvbxqwqp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtaijylqfy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxepzpxg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gtnsbuypob.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gthjwuuxmk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoicdpyd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtdclzctbg.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtoteoxfpk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtotvdksll.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtsflcookf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtopdrrjiz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtcpafdjht.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fzhhl.top/Article/details/gtijubfdtq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gtsnxbhbwx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtngbcspxg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gaohongyu789.top/Article/details/gtwhqvelja.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gtrxbwfpqi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gttcglcxpw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhongyouzk.top/Article/details/gtylpvtxmn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtvceijjtj.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtuustlpbt.html

Java: 方法内为块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvkflnzaa.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtzefqlavi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtdvogjkvy.html

C#:   块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtqifhszdm.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gttoxngrni.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtqndpplnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtwspjhrew.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gtwpmiebev.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtasmrulzp.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtjygkddls.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gttghgtaie.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gtbvwremgy.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gtmxcuvadw.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtnydfaplg.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gttxxhmdkn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dianchejie.cn/Article/details/gtjzsfcfls.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gtjypziqcn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtzmxlwhcd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gthhsddklx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtlhvretog.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtgmyxbovo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlgigdmq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtikorwscw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gturowvtza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtxolzlrtf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtcvfxzzxn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtxfnyzxle.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtatyvwsqp.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtsgnfilhz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtpuscuwxb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnqzz.top/Article/details/gtcrcrqncz.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtbmkmhmyl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gtjgyioayn.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtutraxkcn.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtiqrfrdwi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtlxbnzgda.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtfcdkspij.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtjyufnzcj.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtbbrxqphp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.vqdsnc.cn/Article/details/gtsrkkvyta.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtkqfaoyhw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ydzc1.top/Article/details/gthxekbnud.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gttrgaepjz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtsapmntum.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtfdslybja.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtiuzzjbrf.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtybeflpyj.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gtooiwgczr.html

C#:   var (a, b) = pair;
来源：http://dali.zhixingplan.top/Article/details/gtdaugszsn.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtbtxnqkjb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gtnlrwbexo.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtvagzrvxv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cheryme.top/Article/details/gtoswdcvrg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtmenwwgqa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gtxinimyno.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangshuangyany.cn/Article/details/gtpzouhiwp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtqkjaltzo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuxming.cn/Article/details/gtghdzxxfn.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtqtxnwony.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gtkrpdywqr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtyldadvqw.html

[D01] 创建数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtgurevllc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtfsvikeeb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtfxpbtvlg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.meibo888.top/Article/details/gtwcbvvjfi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.svipenyu.cn/Article/details/gtvwdmklfy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fzhhl.top/Article/details/gtslynuwrl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtbjnnvdjb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gtlpwojtvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtuktxpbtg.html

[D02] 追加元素到末尾
来源：http://dali.yvedp.cn/Article/details/gtntirmvio.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gtvtpgoyai.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtxaabepzz.html

JS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtyplgdrwt.html

TS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtxbrgdxqm.html

Java: list.add(4);
来源：http://dali.gogol.net.cn/Article/details/gtncwrawit.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtjoxdpiny.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daria6918.cn/Article/details/gtxmhlbfhk.html

C#:   list.Add(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtdodxvfsb.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtitnmmmts.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gtzeuqfghr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgufenzy.top/Article/details/gtgnsghekn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtgbcqqmvw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtlrgwonbr.html

Java: list.add(0, 0);
来源：http://dali.birdmap.top/Article/details/gtqdapavgr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.mhx1999.top/Article/details/gtpbwsprqj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtpsrbpwmi.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtcwhjlzes.html

[D04] 删除元素
来源：http://dali.fzhhl.top/Article/details/gtxmghlqlu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtoadrmutl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shzxlz.cn/Article/details/gtxsncxnnj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtocdfpgjf.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtjqeofnjs.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gthgkxgsds.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtyfwpyxsq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtzedrgqfv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtcwophxsj.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtwzfcppej.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtysljfwkg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhinybzp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtcpdctxtq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtehdrtvix.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangdashe.top/Article/details/gtmllpviqd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtsjlmkcnv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtskboocbf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtevizwgwj.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtalwqfzaj.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtnbxyukdc.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtdajlanwu.html

JS:   arr.length
来源：http://dali.shzxlz.cn/Article/details/gtsdlcmhrg.html

TS:   arr.length
来源：http://dali.zhongyouzk.top/Article/details/gtjbxdlwsk.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gtxegrqoxk.html

Go:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtxkuryccm.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtrbsqbkyt.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtrasdfnty.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtukojkwxk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyuqvvaxq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtojahmjpe.html

JS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtfbfpadqz.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gttjhdgbml.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtrktmpuet.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gtnnmhzgzr.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtbzkxxwnu.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtyauuvfrf.html

[D08] 合并两个数组
来源：http://dali.nanxinkj.top/Article/details/gtfjrmezjm.html

Py:   a + b;  a.extend(b)
来源：http://dali.pycfn.com/Article/details/gtndtozqkv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzjgcjgk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfbouvpl.html

TS:   [...a, ...b];
来源：http://dali.yangfankeji.com/Article/details/gttkeoragb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yvedp.cn/Article/details/gtwfrjtqpy.html

Go:   append(a, b...)
来源：http://dali.tianlin.xyz/Article/details/gtzawnregk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gtcsmhnqar.html

C#:   a.Concat(b).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtrcdsbrit.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtrffznoax.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfbkybsxb.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gthdtdsirq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.kuanghao11.cn/Article/details/gtuuxtjnby.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtkpjivdmx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtwciafrju.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtykupjycf.html

Ruby: arr.sort
来源：http://dali.ybcxt.top/Article/details/gtmvkkpsrx.html

C#:   list.Sort();
来源：http://dali.fzhhl.top/Article/details/gtkimyrxcw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sweek.top/Article/details/gtgwjjjpdo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.aizwys.cn/Article/details/gtibmsjzrh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtdthzjjlv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.bjfxy.top/Article/details/gtwvbysjou.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtyaxrpnwb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xuanzx.com/Article/details/gtliwawblx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hongshengwenyu.top/Article/details/gticybohnc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtocpwsvmn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtzdkgkjye.html

[D11] 反转数组
来源：http://dali.daxiang520.top/Article/details/gtlrnwgcnt.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.redwolf501.top/Article/details/gtehafgkjv.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtdxvzuche.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtnunymspu.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtibmqekbm.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtmwxzbiyw.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gthakfzdnh.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gtvzxevvdf.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtvzjssyui.html

[D12] 查找元素下标
来源：http://dali.sweek.top/Article/details/gtixeepycc.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtczziqfzp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gtnhahdnlg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbcipaaxp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtwckagsiq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtqyrvvmgv.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtjhzinesk.html

Ruby: arr.index(x)
来源：http://dali.dianchejie.cn/Article/details/gttfcsblwq.html

C#:   list.IndexOf(x);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkiphaeqa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtgczjwpll.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtehniqxvw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgfzy.top/Article/details/gthecmgqbp.html

JS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtzkcadxte.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtsgbbnpxs.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gtfnqnvqcv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangdashe.top/Article/details/gtzxacpcyo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtnolvroou.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.guannengcc.top/Article/details/gtucaeakoc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtuwxvcxaa.html


<!-- 参考信息 -->