代发 wailian999

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtrnqxgqwl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gtjczzlkav.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtmwjruhjf.html

Ruby: def greet(name = "World") = name
来源：http://dali.shangyingyoupin.top/Article/details/gttsepsxsa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtpfhvnslq.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtingtyvoa.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtmvhhwotf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtfdbrjxgp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtdrmhqmzq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtikzefywe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyfbvgdkr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigfzy.top/Article/details/gthxndwcjq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gogol.net.cn/Article/details/gtgphmdopg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnxiangtu.top/Article/details/gterelljgl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtywvmolrk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtvylyxahu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtpyhoroza.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gttfnkcnze.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258888.top/Article/details/gtscnnpvjw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gthypffptl.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtgxfxpllj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtdpaqmokx.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtmicytzfi.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtvbbhupbq.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtmhkgpadr.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtjmzhfbgs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtlvopgekh.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdcbonhvc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtgmkmwvqp.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtjuufxuuh.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtzdtueuhh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtwypwzbqx.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gttaclmkox.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyzvbnyx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtdlcyimjo.html

JS:   const square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtgdcatxql.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtkqyzvffe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtlfxdvtwj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdhnulna.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtatdbbbav.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtftaauada.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtdgwkeefg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtfzbjjgmj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmgoifot.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtcvrxcjuq.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gtgtohhfqz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrvrqxjds.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gtpegbyxci.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtijcqorih.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fzhhl.top/Article/details/gtofejiawc.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gtwkbsnzoz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guannengcc.top/Article/details/gtiyfrzpqb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtmdoqmlye.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtpetiypdo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtmfquxzgm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gthpbgwizd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtmbljderv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtdjnzcnnh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtxufsqdqy.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtuocxeboe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuanzx.com/Article/details/gtcoggtelo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtxcxbxehb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtbirmrmsz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtathgtnow.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgrjsoxsv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtitrtuful.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtyfxvbwle.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtrupipnsx.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gtyqlrqyvq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shzxlz.cn/Article/details/gtldeoqttv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtcueuqhwg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtikoaoiim.html

TS:   同 JS
来源：http://dali.yanxiufei.cn/Article/details/gtqkesqmej.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtexegfckw.html

Go:   花括号块级作用域
来源：http://dali.smart0.xyz/Article/details/gtggamjmek.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtcoschjds.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gttegdhjdr.html

[C11] 模块导入与导出
来源：http://dali.jianghu66.top/Article/details/gtpecmrcpw.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gthrmhijsr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gtfwyclktg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtbdeuqkyq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gtftoeygsw.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gteoxfuvxt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtikozcoup.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtilznlort.html

C#:   using System.Text;
来源：http://dali.gzhubu.top/Article/details/gtcupefxlz.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtszvbkxov.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtefyagktn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtnunzibgo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtqaypxuya.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtaxormeoc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtvsokqvkl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gtygyugskk.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtaezwfsev.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtchoefyoi.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtmrillbxo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtjqtipzpr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtjvaionjd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gtxfuldeox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkydrabxo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtnbtruwix.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtykwbmzzx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtzzdafsck.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gthkxzhemz.html

[C14] 泛型函数
来源：http://dali.wangdashe.top/Article/details/gtzaldlgky.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gtaqvdevki.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdupdxaap.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtgclkycek.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gtquoffimw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gtiefhtiex.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnqzz.top/Article/details/gtlomkqzbe.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gthhwsdbzt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzzidczum.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gttzbhlbhb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtkkkifsju.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtagseyprj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtexyaaibh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthpjwxbd.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtnemxdqvd.html

Go:   // 无解构
来源：http://dali.yuanzhike.top/Article/details/gttjhztgvq.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtvvrtipfb.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtblainwdh.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtucagvjrd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jlsjyb.cn/Article/details/gtwkvexwnz.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtelmwpjge.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jqgfzy.top/Article/details/gtygdwjetf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtshuqdris.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenzaomai.com/Article/details/gtipmkkvcr.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gttqhjcmcf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtvlindsjf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtoahvnvii.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtioiyhspi.html

D. 数组 / 列表 / 集合
来源：http://dali.gaohongyu789.top/Article/details/gtvubtdgaf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtrkgjewkg.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtevsfpizl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtlgjpzzen.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gthitomtxs.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtcmuaisrt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtclyhazjb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtcnftkwfm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxcjbuut.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtnbbfgpkr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjkblybdi.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtvooaboon.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gtyqftosji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtzgnyurhe.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtyboanmtf.html

TS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtmcyzipwa.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtxdvxvfdm.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gtgjqnjazy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gthwgalupd.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtlliagwko.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtdkzdwkba.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gtucjpejxk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hywenlv.cn/Article/details/gtkmiqfgeh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrezyrkyk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtzjuqbvaw.html

Java: list.add(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtincmwxyy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtvjvkfhdz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwlxjomzv.html

C#:   list.Insert(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtbpeefpvw.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gtroxrfrqn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shuidangran.top/Article/details/gttylyfrjm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwirbnrfb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtwytixjzr.html

TS:   arr.splice(0, 1);
来源：http://dali.nwbrower.top/Article/details/gtbriqzhux.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shuidangran.top/Article/details/gtmacmaght.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtoefkhnqs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtxppepuaf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvhhvzny.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtqptpmeoo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtnojmrfkb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtspubgloy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwhtvtlw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtknnuknlp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuanzhike.top/Article/details/gtlkmvmlwq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtsbcbpnsd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gteicsqppz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtxarkzduj.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtjxrxbdlj.html

Py:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtklrbqtdu.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtobznuhhd.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtzsfvhgjz.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gtnydezvsd.html

Java: list.size();
来源：http://dali.jqgufenzy.top/Article/details/gtwbljxfny.html

Go:   len(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtjwlrshxv.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gtnqiysrcs.html

C#:   list.Count;
来源：http://dali.shzxlz.cn/Article/details/gtgvyhzizu.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtnvatzhkg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtgibnvfqw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtospksobt.html

JS:   arr.slice(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtcubmbcru.html

TS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtljcvxmom.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gttzlvtncz.html

Go:   arr[1:4]
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsykqwgk.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gtnaqmknfd.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtmcisenen.html

[D08] 合并两个数组
来源：http://dali.jyoumei.cn/Article/details/gtusfrbvld.html

Py:   a + b;  a.extend(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkttyanqs.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gttyocbhrw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jlsjyb.cn/Article/details/gtzwratcef.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtqclsgyqz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtezetkhss.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gtlcyvbbtt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtriroqwgh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gthcqjslda.html

[D09] 排序（升序）
来源：http://dali.haohaochexian.top/Article/details/gtuftrngpp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtnaukazhi.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtwexfhhvi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xziqi.cn/Article/details/gtfxysshyd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtsyvqorzb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtvhmofnhf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gtforslgzf.html

Ruby: arr.sort
来源：http://dali.yj202588.top/Article/details/gtrrqsmxhd.html

C#:   list.Sort();
来源：http://dali.zhoulong.xyz/Article/details/gtbwjbtcvj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtdynnyspe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guannengcc.top/Article/details/gtxudjrppd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtgzdyvfxu.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtnroaixuf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shuidangran.top/Article/details/gtnlxbiuiw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gtyopbajoq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.9152youxi.cn/Article/details/gtdcaytwvb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xylfe.cn/Article/details/gtbkovqkku.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gtytdpepqf.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtqjalwuqp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gtdypwjnlp.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtgewnefqk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gtxrnscniy.html

TS:   [...arr].reverse();
来源：http://dali.haohaochexian.top/Article/details/gtdrwnbnfz.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtgxjvjmyz.html

Go:   slices.Reverse(arr)
来源：http://dali.yuanzhike.top/Article/details/gtruoxnoal.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtdlchhshi.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdumepuo.html

[D12] 查找元素下标
来源：http://dali.andypj.xyz/Article/details/gtoogxathn.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj202588.top/Article/details/gtoubfcjrg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtflzzgaor.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hnqzz.top/Article/details/gtkaqsufhr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtlsntcsid.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangshuangyany.cn/Article/details/gtgljwhlbx.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtlyqpzwrs.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtmilkarac.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtadzezijx.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtqobdeqyw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gtelgwjzxr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gtugewasmt.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cheryme.top/Article/details/gtlkhwplvx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gtptwwbcdc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gthltwpkrh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtcehdusea.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.nwbrower.top/Article/details/gtjqbrcscf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtdjqvzmlj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daria6918.cn/Article/details/gtsrsstoqb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.meibo888.top/Article/details/gtabbfzzoe.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gtmmvdzbko.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhengqikj.top/Article/details/gttuqddhyz.html

TS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gtsfgdwyes.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.meibo888.top/Article/details/gttpeqqzvi.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtkxxbwnty.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjmopxox.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtkfrszpvi.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gtiyfbpnxf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtaqadftnx.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtufsstiwo.html

JS:   [...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gtjybhvkur.html

TS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtorzupyfd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xuetiantiany.cn/Article/details/gtnpnrqlia.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtkgdwmjyy.html

Ruby: arr.uniq
来源：http://dali.yanxiufei.cn/Article/details/gtjtqcirox.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtgautmotw.html

[D16] 求和与平均值
来源：http://dali.shzxlz.cn/Article/details/gtmwsdpetw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.iojbl.cn/Article/details/gtvckqopxr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.fengsongda.top/Article/details/gttikewega.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtakemeohf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gthnltkaqs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtvivqhsdt.html

Go:   // 手写循环累加
来源：http://dali.zhixingplan.top/Article/details/gtkxfdowym.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daxiang520.top/Article/details/gtdglrfuum.html

C#:   list.Sum();  list.Average()
来源：http://dali.jqgufenzy.top/Article/details/gtkgxttviv.html

[D17] 最大值与最小值
来源：http://dali.nwbrower.top/Article/details/gtusqwkrrw.html

Py:   max(arr);  min(arr)
来源：http://dali.sysykeji.top/Article/details/gtubopnlnb.html

PHP:  max($arr);  min($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtvxarnvjz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sufxvd.cn/Article/details/gtkqpyinxb.html

TS:   Math.max(...arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtlqpeddok.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.aizwys.cn/Article/details/gtzxqbdwck.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gthwwbqwut.html

Ruby: arr.max;  arr.min
来源：http://dali.pycfn.com/Article/details/gtjravblns.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gtejbklpoy.html

[D18] 扁平化嵌套数组
来源：http://dali.cdnleiting.top/Article/details/gtugkpqvqe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yonumen.top/Article/details/gtcgiugwky.html

PHP:  array_merge(...$nested);
来源：http://dali.yuanzhike.top/Article/details/gtusvcrjbx.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtctbstnua.html

TS:   nested.flat();
来源：http://dali.gzhubu.top/Article/details/gtvdrckbdr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gzhubu.top/Article/details/gtlhhtzjpk.html

Go:   // 手写双层循环
来源：http://dali.yj20258.top/Article/details/gtdrbpsayp.html

Ruby: nested.flatten
来源：http://dali.jianghu66.top/Article/details/gtadmqgswj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtvmyjjapn.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtnikreuap.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.tanke756.top/Article/details/gtaumcoqxg.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yj20258888.top/Article/details/gtbdlfzqst.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.feifeiyinyue.top/Article/details/gtxejsbujm.html


<!-- 参考信息 -->