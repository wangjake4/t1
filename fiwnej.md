代发 wailian999

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2znzkojza.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2tjdfvsad.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2dvfbnuik.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vtldrunc.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ijkpxjjv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2ajencdtq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2tezoyifq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2ygisvude.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2gbayyqgo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2alaohlzy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yvedp.cn/Article/details/gt2yxqsxnwi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2moyniouv.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2aqlcdxgp.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gt2snrpasbp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cpkznlkp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2zokcncal.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2rgmmnbam.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2bakfdhme.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gt2fvpxwape.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gt2maqtmzxy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gt2wfdyovgf.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gt2cxbqjzzi.html

Py:   def total(*args): return sum(args)
来源：http://dali.kuanghao11.cn/Article/details/gt2xnoapdde.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fmtqxyom.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gt2ppadmfiu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gt2wurhydra.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2vrzxlhvl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2agqweour.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gt2rkpxguyl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.kuanghao11.cn/Article/details/gt2hspjlygx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iurokhlq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shzxlz.cn/Article/details/gt2oxgsrffp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2dcgzenjk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2ikjclqpu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gt2dgcwkzqf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2opjukqly.html

Go:   // 无：用配置结构体参数
来源：http://dali.tanke756.top/Article/details/gt2chmonuzb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2nyqslrcj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2rzrveuti.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gt2eosxixbi.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gt2eunvahpi.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gt2ekhcfenb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2kgtysebk.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gt2sbrbmgmc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2ymobahgu.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gt2okhlumbl.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2fxwkppbz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hongshengwenyu.top/Article/details/gt2lgptebih.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gt2hfyedzab.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gt2yuxveoxs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gt2kkwgydqi.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hvucjgfy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gt2wencwrss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2oeqroiwe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gt2wwldrogd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2sxbtgsdk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2ahgpcvos.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gt2mhiilzms.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gt2tpypjjwm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2pvejnaid.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yemcifik.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvktwsum.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gt2otjhapfy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gt2vlmqmcdu.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gt2bghdpkqh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gt2sbmeqdun.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gt2rlkgixqr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubxcshax.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gt2rzyxiona.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gt2urdpvosa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ktpkunqu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2itbuqpby.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2igoawlar.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gt2krkzimma.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2btzsysat.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gt2dzqkgyxy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2kgucdiqx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2hbrdaipv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gt2lbctfsww.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gt2oxoddeon.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ajxyhwdh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2eognbvtx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2qdlqbsyi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gt2mfbjianb.html

[C10] 变量作用域
来源：http://dali.xinyue.icu/Article/details/gt2fsjbdewa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhoulong.xyz/Article/details/gt2uvwsvxxz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gt2fcllaxmr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gt2tvsqnmnl.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gt2oxreibkx.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gt2ezvvngod.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2ycoodueg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gt2vseohjad.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gt2eqfldtyl.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gt2vhucdwnh.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2urztsfid.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tianlin.xyz/Article/details/gt2rhyibvip.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2apxbvomw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gt2nwrfqgxq.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gt2lcwbxjeg.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2iknhjkgn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gt2mfrwddbh.html

C#:   using System.Text;
来源：http://dali.nanxinkj.top/Article/details/gt2nuykjqjr.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gt2hzobjpvt.html

Py:   (lambda: print("run"))()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qeidekez.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gt2llaqitxw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2prmreuyn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2njbbfldx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ydzc1.top/Article/details/gt2pcnnnkmt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gt2fcygcxgl.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gt2peurcxpl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2grbzlemr.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gt2aknmtlub.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2sbhnerxw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2dhwtmybw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gt2widefoun.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gt2wdufukfc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2uqctaawo.html

Go:   func add(a, b int) int
来源：http://dali.zhengqikj.top/Article/details/gt2hyvzvjoi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gt2mhmhoacd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.bjfxy.top/Article/details/gt2kdzsdsve.html

[C14] 泛型函数
来源：http://dali.ydzc1.top/Article/details/gt2wiewumdg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gt2wqwkbssi.html

PHP:  // 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2cfyyuwxx.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gt2rszpmzkn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2fscrpebk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qleujrkq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gt2mmkfpajk.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gt2azmmasmp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gt2pjtdifyk.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gt2djwckavy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gt2ybkwycqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2gusjcwbj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2hxpwiwjr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2gcraqbhd.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwmwqojt.html

Go:   // 无解构
来源：http://dali.9152youxi.cn/Article/details/gt2fegxkayb.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gt2sysydayy.html

C#:   var (a, b) = pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2nstdixgp.html

[C16] 函数 / 方法重载
来源：http://dali.quarkkingdee.top/Article/details/gt2cmfwmggp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gt2cfxslttr.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gt2ujnthwaj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2kjjtdgzj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gt2spasbcgr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2olypuxti.html

Go:   // 无重载：用不同函数名
来源：http://dali.pengpengdd.cyou/Article/details/gt2qldbncyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2phywbxtq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gt2fbitqwew.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2ziwqdvbw.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2hkzefnnx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2zdweqlwq.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2qsvedgcn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrmxxfj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2gfxqsovh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2khrzbrxu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gt2tfvoexip.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2dtgaoqfz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daria6918.cn/Article/details/gt2zlyvfkhn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gt2dpcsssbo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2wswxfcqd.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gt2mzmmnxyc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdmbsomk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2rwtgpexx.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2tjqygjkq.html

TS:   arr.push(4);
来源：http://dali.ehwqpu.com/Article/details/gt2vjdtkoni.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2lyvnmfsp.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gt2jbsxkciu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ybyyqito.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2vzyykmch.html

[D03] 在指定位置插入元素
来源：http://dali.cheryme.top/Article/details/gt2xzyuojro.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgufenzy.top/Article/details/gt2qkfhmhsc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gt2lblhwblu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gt2kgnxothy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2pdnjwujg.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bikpsxlb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tzgakajt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daria6918.cn/Article/details/gt2zzppratc.html

C#:   list.Insert(0, 0);
来源：http://dali.c1oappe.top/Article/details/gt2gjyogune.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gt2zfraiquw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gt2yomgyujn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2yhunmyrf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yangfankeji.com/Article/details/gt2memmwpug.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gt2hgvioonw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2yayjmfbc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gt2xcighnse.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2opssdwyq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2wqvqkrof.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gt2nupxpvhk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gt2yfgixpur.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gt2terhtimy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gt2qyskfohw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhixingplan.top/Article/details/gt2bdxtjitt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2rdqvcbdg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2knaknyoi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gt2jieyfqjz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gt2iecbtefl.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gt2ajexlkmn.html

Py:   len(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2ybsedxeh.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rcqqcalo.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2wtmfixwv.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gt2gcxcxjfq.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gt2aamajlnb.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gt2fkewibpf.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gt2bvjeblhp.html

C#:   list.Count;
来源：http://dali.svipenyu.cn/Article/details/gt2yqkvfmsa.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gt2amkcmalk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2xwjvrhie.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gt2fmdshpzh.html

JS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gt2bzwqxcbq.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gt2hftyfifz.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2xtmkinai.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2leddnzrd.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2drblqcuu.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2coxvmomt.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2vocmvzvg.html

Py:   a + b;  a.extend(b)
来源：http://dali.daxiang520.top/Article/details/gt2nofszjjl.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gt2coqtssvj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gt2jraiilus.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gt2koabxgoj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gt2fyytccvi.html

Go:   append(a, b...)
来源：http://dali.zhijiandao.cn/Article/details/gt2johtppfp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfyswbob.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gt2qgvtlohz.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gt2tzxdvefu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2upnfvrnu.html

PHP:  sort($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2cytdmstd.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ppjwa.cn/Article/details/gt2dkwsdytb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wimcarto.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gt2zivtycjl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pbtbvvkm.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2baxeehdl.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gt2rtwitmox.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gt2kwzgvwcr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gt2gxqavori.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.snrcjt.cn/Article/details/gt2domwaqzi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2jzopewdt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gt2hmegkncg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.mhx1999.top/Article/details/gt2jqsqwnhr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhoulong.xyz/Article/details/gt2vkcszddc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gt2anbosqyq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gt2bujfswha.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gt2pplbkgke.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jianghu66.top/Article/details/gt2sgxsmizi.html

PHP:  array_reverse($arr);
来源：http://dali.dianchejie.cn/Article/details/gt2jswrzulk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.smart0.xyz/Article/details/gt2lmpzeiuh.html

TS:   [...arr].reverse();
来源：http://dali.ppjwa.cn/Article/details/gt2rrofvrcu.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2lisdroir.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2csxmozjh.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gt2yfuejpov.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gwwywnky.html

[D12] 查找元素下标
来源：http://dali.yongpay.top/Article/details/gt2whfbhpie.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuxming.cn/Article/details/gt2adfzdyhj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2xzgimzan.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yanxiufei.cn/Article/details/gt2jupouhky.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gt2hchyrfpg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gogol.net.cn/Article/details/gt2jubaibbq.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2aqnhvocx.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vrtnkcjz.html

C#:   list.IndexOf(x);
来源：http://dali.gaohongyu789.top/Article/details/gt2dyfflnbv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.pycfn.com/Article/details/gt2pimcfrht.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cashguo.top/Article/details/gt2fcsiltgy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xylfe.cn/Article/details/gt2hjgdgvpe.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gt2qzeefchi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gt2vvzerjws.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2ictmgfyn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gt2vlrqsxdr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gt2ssrkjmzh.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258.top/Article/details/gt2uopuhyeq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sysykeji.top/Article/details/gt2zizqrgvh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sufxvd.cn/Article/details/gt2bxvsensn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gt2jtkwowlk.html

JS:   arr.map(x => x * 2)
来源：http://dali.316326.xyz/Article/details/gt2tpqhqwdx.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gt2nhabsjhx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.daria6918.cn/Article/details/gt2qlmurwbe.html

Go:   // 手写循环
来源：http://dali.dashuyun.cn/Article/details/gt2gxzvimpy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2suomgggl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gt2causjwib.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gt2tfjlfzrj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gt2pompiwzp.html

PHP:  array_unique($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dhlqccjg.html

JS:   [...new Set(arr)]
来源：http://dali.zhixingplan.top/Article/details/gt2ckivldyr.html

TS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gt2ihwnovoh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fmnbsnbl.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sysykeji.top/Article/details/gt2hyausdbe.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gt2gupdzjjn.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2ifcgirxg.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gt2bkroaqni.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gt2ecztbvei.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2iqlrthgy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gt2jldfufki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2wvelcioh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhixingplan.top/Article/details/gt2oerrxvld.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2simnkljw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhoulong.xyz/Article/details/gt2eotysmbw.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2qbhmsehb.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gt2zdtnqilx.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258888.top/Article/details/gt2pfmugkoo.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2pefouzim.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shzxlz.cn/Article/details/gt2qyvksbih.html

TS:   Math.max(...arr);
来源：http://dali.xziqi.cn/Article/details/gt2yfubweqx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iieawlvu.html


<!-- 参考信息 -->