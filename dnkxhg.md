代发 wailian999

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gt2vmstlbht.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigufen.top/Article/details/gt2lercsqaq.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gt2yhdrvxym.html

TS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gt2bimyslgq.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gt2fjtldyzn.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gt2qiwxespp.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gt2voxmkytx.html

C#:   if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2kqtmbyyr.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2xfaxutay.html

C. 函数与作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2qwzrjcly.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2cvrlvxtm.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2crychxnt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kuhcwccw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gt2rdtijxbb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gt2ajvvoslp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2yccxkhkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2evhmtmsx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ybcxt.top/Article/details/gt2tscgppyt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gt2lqnwiwzm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2dtmmankd.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2ornqgblf.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gt2bexfqnqq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gt2vmzmmujw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gt2uudjykhw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gt2yrdegiry.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gt2mvsvvlwz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2scqsyvpb.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gt2eheppywz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ybcxt.top/Article/details/gt2xssnzspo.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gt2lbmxdqua.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gt2lulveazo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gt2sliyhbxp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2ygkwbndb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gt2iwsoappr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gt2yonzxvzx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fzhhl.top/Article/details/gt2ntzpzwly.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gt2mjxvkmtq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgrxbwxq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qohyxpgi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2xqdvbnwx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2evfjbuol.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2yaghnlyo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yzltagqb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckleipmm.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gt2jjwpwqty.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbwpqdkh.html

C#:   f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bvlgikvb.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gt2pzilhvdr.html

Py:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2xlkaprgn.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gt2zybbrggs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gt2odomqezq.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2wsbyrjvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2fuhukgry.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2ltgijnnw.html

Ruby: return a, b
来源：http://dali.havefunace.top/Article/details/gt2wwinmjca.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gt2hwvmyiqg.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2snjuwkcp.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2epzdzgqy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tanke756.top/Article/details/gt2zmabeaas.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2yzcisqwg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2ytsbfhvc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gt2nbbaccei.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2tklkrstg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gt2lsnoiykv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2jwigiajm.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2gqdoviki.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gt2wwdoyzbq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2yggayqyi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gt2jynpiuuh.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gt2sknwdtrh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2oobseslz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gt2eirzpyop.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gt2wzbkghof.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gt2vtnzvlmi.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gt2gvgsluol.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gt2issuhbor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgfzy.top/Article/details/gt2khoolmxm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2cdcaflua.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2xhzueaqr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gt2rvqoapyj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj20258888.top/Article/details/gt2khsjukmz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtphhspz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gt2yllhkhsw.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2qrkirchz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2redfwbyf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gt2sbmxejsg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gt2sjquszbt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2wzzqacxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2oihewhby.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj202588.top/Article/details/gt2qlxqjibw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gt2ixawuaxu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shuidangran.top/Article/details/gt2zhogxmoi.html

[C10] 变量作用域
来源：http://dali.xziqi.cn/Article/details/gt2sbhorcxx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gt2yxvxwjxy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gt2lfhcsgrv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pycfn.com/Article/details/gt2ofgfqkmc.html

TS:   同 JS
来源：http://dali.nanxuanxn.top/Article/details/gt2imwhxqtr.html

Java: 方法内为块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2ovtmmsdk.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gt2ewaooeah.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gt2makcwrsh.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mrxfwjhu.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gt2mqeufuzx.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gt2wkbwoxjs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ujajoxuq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2aadzigqi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gt2vrznxnrz.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2wvtyndoy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxbxfqzq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2ndoryjrs.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2hrzgrddv.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2jeoxmoar.html

Py:   (lambda: print("run"))()
来源：http://dali.jianghu66.top/Article/details/gt2dmecztqf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfppbhwv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvolwnxt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2wzoqvkub.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fzhhl.top/Article/details/gt2yehvexve.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gt2xongqkan.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2zdmvnljj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2fdxvbcgy.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenlongwang.top/Article/details/gt2akmnepma.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gt2uayuelji.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2rqskdgyf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gt2dalcdnii.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2jpgcpgvj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2qwbtwvlj.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2parwxjuy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2agqzoldq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gt2jjrinmnh.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gt2qocnuajc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gt2jkdlcjjz.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2mfocyvmp.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ebhnsszc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cddvqihd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2ozyasnmj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2tdmdctre.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gt2tbxnvrxg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gt2cpviwheh.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2aiydanvk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gt2wswhzeal.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fzhhl.top/Article/details/gt2texvkffx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2pswquxgr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gt2ydylpjck.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2grkfyows.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2gzsfvgbw.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gt2bhvmdudm.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2wmrfourp.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gt2icdupdul.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2jausvlpg.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2nwoprchl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gt2frpfwlsi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhixingplan.top/Article/details/gt2dknbmcpp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2blareiox.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2gsactufd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gt2wlmqkfjv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxmodrtu.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hhxgllqh.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2xruzlpil.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2ufonjnjv.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2dvnjvqmj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jyoumei.cn/Article/details/gt2tyulaybr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gt2spwqjsfu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gt2gybzqlzt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.meibo888.top/Article/details/gt2hyfbvude.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gt2osrawcub.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gt2hfmgidyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcayfdhl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gt2cwxatrys.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gt2wsdwziid.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gt2ubpajdmt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gt2bciftjwx.html

JS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2fcnzsdwv.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2akjxhpvh.html

Java: list.add(4);
来源：http://dali.guowangkeji.top/Article/details/gt2mdhsdqox.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jrxmdphd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hfpthk.cn/Article/details/gt2krduanor.html

C#:   list.Add(4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2unwinmkv.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gt2xlmcvfxk.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2kzyyflba.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2ighufqnd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gt2qefikpku.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gt2udlrinzc.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2djlqjgmy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gt2lhqetioy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gt2mnnutxgm.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2qshgxcck.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ewxolcth.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fmvtrtay.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2ryewcrtg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.316326.xyz/Article/details/gt2tknjmhpq.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkqfrwmr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gt2tshdfdcw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gt2euguyrph.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yangfankeji.com/Article/details/gt2dujqimqe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gt2yblnikmz.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2knkjshdj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2tgukgfnh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xttxhkdw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2nvwpsnfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2egoowkhq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aizwys.cn/Article/details/gt2zuuijplc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2butelrhh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gt2zavervza.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2nrgmarlk.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2tncyqzle.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2flafcvvn.html

PHP:  count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2oohdzmiu.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2oticzswz.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gt2ykohlups.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2prgrzlkt.html

Go:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2qijzbxlk.html

Ruby: arr.length; arr.size
来源：http://dali.guannengcc.top/Article/details/gt2zcmeasgy.html

C#:   list.Count;
来源：http://dali.0kj1m.cn/Article/details/gt2appvdsct.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gt2itxhghfn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gt2bjqdpfbr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gt2jqwuftzx.html

JS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2murdqwti.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2bzwkphiz.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gt2tbvivvxl.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gt2fraokafa.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gt2gcqdumnm.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tefbfphq.html

[D08] 合并两个数组
来源：http://dali.ehwqpu.com/Article/details/gt2mfmthdhl.html

Py:   a + b;  a.extend(b)
来源：http://dali.ydzc1.top/Article/details/gt2oohwbapg.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gt2ajpsbpka.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sxryk.cn/Article/details/gt2hqgmkgno.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2adttwccb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnmliryz.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gt2pzvqztcb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenlongwang.top/Article/details/gt2mmxsmtgd.html

C#:   a.Concat(b).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2bpxxpjnf.html

[D09] 排序（升序）
来源：http://dali.hywenlv.cn/Article/details/gt2lfschpfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hammf.cn/Article/details/gt2gqpaqtsm.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gt2nzbvdvku.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jianghu66.top/Article/details/gt2ducixbrs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tanke756.top/Article/details/gt2xbpfkrnh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gt2whxjlfce.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2ijnqbxri.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gt2wegcigob.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gt2tuherrdu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gt2xijhsmjj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuanzx.com/Article/details/gt2zglimuak.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2xefngagh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sxryk.cn/Article/details/gt2iirlnohr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gogol.net.cn/Article/details/gt2yogptksx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gt2iuywnwch.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gt2kcdeemta.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2nihuhrbd.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gt2mjxrenmf.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gt2bfgmujxd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xziqi.cn/Article/details/gt2rgzdodzj.html

PHP:  array_reverse($arr);
来源：http://dali.sxryk.cn/Article/details/gt2dxkjppsi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ehwqpu.com/Article/details/gt2vqambnnv.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gt2dweitalk.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gt2gkripmpu.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gt2iajqmlca.html

Ruby: arr.reverse
来源：http://dali.jinqigufen.top/Article/details/gt2arvsqnos.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gt2polymwph.html

[D12] 查找元素下标
来源：http://dali.ydzc1.top/Article/details/gt2pnbbrahm.html

Py:   arr.index(x);  x in arr
来源：http://dali.xuetiantiany.cn/Article/details/gt2hkcnylgs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cucudq.cn/Article/details/gt2rmuqddfp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2obcwibjs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2upjjezjd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xinyue.icu/Article/details/gt2tvglyjeg.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ndcnkhgo.html

Ruby: arr.index(x)
来源：http://dali.gogol.net.cn/Article/details/gt2cioygaql.html

C#:   list.IndexOf(x);
来源：http://dali.yj20258888.top/Article/details/gt2syuogjcr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.cqqwz.cn/Article/details/gt2hefceqty.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gt2akkmtdjb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2eudfdphn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gt2onzzpwpf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gt2bseebmce.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2itbkwqcs.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tanke756.top/Article/details/gt2brbxakcs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.haohaochexian.top/Article/details/gt2ocmtyicp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2zxgfahco.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dianchejie.cn/Article/details/gt2snjnpcwq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fzhhl.top/Article/details/gt2pjyxljkh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2dkvaytnz.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2hlspjfbp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2segdlgwf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2xiayakla.html

Go:   // 手写循环
来源：http://dali.gogol.net.cn/Article/details/gt2hepveiyq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lzhmcppw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tian-w.cn/Article/details/gt2ariyimjj.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gt2uuqtklsg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gt2eytaemwb.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzrbpjky.html

JS:   [...new Set(arr)]
来源：http://dali.svipenyu.cn/Article/details/gt2bzekrlrg.html

TS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gt2tcbcftar.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jianghu66.top/Article/details/gt2fonhvubg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2qhqsyssi.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ediadosy.html

C#:   list.Distinct().ToList()
来源：http://dali.cqqwz.cn/Article/details/gt2nhxrwxae.html

[D16] 求和与平均值
来源：http://dali.gaohongyu789.top/Article/details/gt2gjuqfind.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cucudq.cn/Article/details/gt2nkqdnsto.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2ymgsgiqb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2mxvkfjdh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kkqxogxw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pycfn.com/Article/details/gt2uusrttqq.html

Go:   // 手写循环累加
来源：http://dali.xziqi.cn/Article/details/gt2ngrdjjwa.html


<!-- 参考信息 -->