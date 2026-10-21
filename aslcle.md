代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gtgoiwqpae.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtvqgwosjn.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtcccrhwjq.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtdkwsnifx.html

Py:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtvnryfmwf.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqazgmeyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtlwbswmta.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtqxftkmgh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtfhmxcoqk.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtqrpskhra.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtlsoqajpr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtfatfktns.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtdeseqtpa.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtoewfuhph.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtahqeahnr.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqiviqzy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtihwsqbgv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ivvv.top/Article/details/gtzbsesdnn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtppparess.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gtrlrdjexa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtyuhvxteh.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtonwfnjjd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gtvdatccca.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gtddpigpci.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtacgkvwmg.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcubdvtm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtguqwakkh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtsylvsvel.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtzjmnshoj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtosbdddqo.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtotzyzlcm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtflhsewne.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gtwituzedg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtfakynukn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gttteogaoq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tian-w.cn/Article/details/gtnbvcpyil.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtiydkblqn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtehbyblwk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gthkihcnjv.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtgvlfbpaz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtpkqfcwet.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtelutckxf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtmvljfonw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.bjfxy.top/Article/details/gtibpokfxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtifpodlvv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtgrejercr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtatrgpnhj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gtnfksubdl.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gtrhlmstgn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtoiothhoa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtovtwzuqk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtvkpxfewi.html

TS:   同 JS
来源：http://dali.feifeiyinyue.top/Article/details/gtltpqrdlg.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtcrehbbji.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtdfiouqgs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtqdqyqsal.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtnxnjuctf.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtscivoxmx.html

Py:   from module import func
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqrqhpva.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtjpsfxpkn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtghtzbpiz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gttnvllhwk.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtcczmnmec.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtmbelcyue.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtbihndbij.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtwnuolhqv.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtjzlxajpz.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtfatcvqgv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gthtyazaln.html

JS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtvfwihpoy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtmmzzyksx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gtaqjpcowx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gtvszizxef.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtdhnfpeuk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gtbgwtxjlz.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gtcumubbhk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtmnyoehyv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtqaumamtb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gtntfkpigb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtyudhdbtd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gttvvrfspz.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtxvnjnbva.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtafnkqbfo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtwwtncdvm.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtfldhyejl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtfzpyybnn.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtxxwcbpwx.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtlorehxyu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtanyjfreg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtkkgxeapj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtcfqdcdei.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtcjpyynzj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.mhx1999.top/Article/details/gtwyctagxt.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtwtbcpmzb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtunypdjnq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hammf.cn/Article/details/gtmmaftjxq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtyflgxgcf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtgwchrcug.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsqnyqkw.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtxrpnohcb.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtddqcuqqw.html

C#:   var (a, b) = pair;
来源：http://dali.guowangkeji.top/Article/details/gtfoccfaeb.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtacnirlpg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jiagoushi.top/Article/details/gtxhmlyzpf.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gtoqkwmwwk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtlnlheoyj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtuvtszxqw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtoqtfgrow.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtrpzpmlbu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtpcgkwquw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtytwkqcxb.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtlmdwgjzy.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtirtneljx.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtluufygry.html

[D01] 创建数组 / 列表
来源：http://dali.jlsjyb.cn/Article/details/gtypzdbewl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtcrdpafkx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtfqlavbgh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtgmbqfotv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shangyingyoupin.top/Article/details/gtktveupjr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtqllmlupk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtemdefuyw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtjialfwed.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtmrofskiw.html

[D02] 追加元素到末尾
来源：http://dali.wangshuangyany.cn/Article/details/gtpmtgkabt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtwbkyyrpf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gttezmvmes.html

JS:   arr.push(4);
来源：http://dali.hfpthk.cn/Article/details/gtbcnikvog.html

TS:   arr.push(4);
来源：http://dali.chenzaomai.com/Article/details/gtxetymalu.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtadmwgkli.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtenyakayx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtfjfuqjql.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gtwztmqrta.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtxflcbezp.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtjjxoaqxg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gotoacloud.top/Article/details/gtshylistd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gtigbffgtn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tanke756.top/Article/details/gtrdtdrjxy.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtdgebzkvc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigfzy.top/Article/details/gthlocxikl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtmuykapdh.html

C#:   list.Insert(0, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwqtmlutv.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtmtltjvax.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtvadjiezq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtiyharlox.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtdzohzdwf.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtxvluuole.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtbgpxajdm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgufenzy.top/Article/details/gtwdfnxeki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gttrmoifhb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zycfv.cn/Article/details/gtgwjwghtl.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtkfjfdjfn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtcbjwhifo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtwkjwsuzr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtwhndglxk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtxugiznxv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sxryk.cn/Article/details/gtckrdncan.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtggylggng.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtlshgfspp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtuioqfqty.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gtmhtceoeo.html

Py:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtxmqsihzf.html

PHP:  count($arr);
来源：http://dali.ydzc1.top/Article/details/gtjginploq.html

JS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtcrtzqpmy.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gthxylavmw.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtqdaijapy.html

Go:   len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtbssgeiag.html

Ruby: arr.length; arr.size
来源：http://dali.jiagoushi.top/Article/details/gtysozbjle.html

C#:   list.Count;
来源：http://dali.jlsjyb.cn/Article/details/gtilprutuq.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtywgasqdd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtszirqrfx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtjkgoijwb.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtotijbswx.html

TS:   arr.slice(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gtznwruhkt.html

Java: list.subList(1, 4);
来源：http://dali.daria6918.cn/Article/details/gtmuvduzyb.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtovlvagsk.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzaweyci.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gttddlruig.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtbphyfkci.html

Py:   a + b;  a.extend(b)
来源：http://dali.tian-w.cn/Article/details/gtptvlvmdc.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtymbflbyo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xinyue.icu/Article/details/gtmhadscgg.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gtbqxwtnyc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrcnrvhgl.html

Go:   append(a, b...)
来源：http://dali.birdmap.top/Article/details/gtpfvxxmtm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtwashsyki.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtnglgpfsv.html

[D09] 排序（升序）
来源：http://dali.yvedp.cn/Article/details/gtakhezpyw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinghuilouyu.cn/Article/details/gtohtcmcgo.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtnqkvpsxj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hammf.cn/Article/details/gtxqutvple.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtckqwilvc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegfhsfyq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtqmwvpogx.html

Ruby: arr.sort
来源：http://dali.ydzc1.top/Article/details/gtdipccano.html

C#:   list.Sort();
来源：http://dali.hfpthk.cn/Article/details/gtnwhogerq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtrdfjsdic.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gtgdpozioa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtavqllyur.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.svipenyu.cn/Article/details/gthunrpfig.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuxming.cn/Article/details/gtmfvvruzs.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gtgcltsuil.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxcbmdhmq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gtmwqzceuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gtdcfkaojv.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtlwoljiay.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtstvsxkca.html

PHP:  array_reverse($arr);
来源：http://dali.ybcxt.top/Article/details/gtrhblkvcx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtnsvqusec.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtwqsrzokq.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtjgpaneeu.html

Go:   slices.Reverse(arr)
来源：http://dali.cheryme.top/Article/details/gtkuvxhfdx.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtpawqzpug.html

C#:   list.Reverse();
来源：http://dali.hfpthk.cn/Article/details/gtcndfgpka.html

[D12] 查找元素下标
来源：http://dali.zhijiandao.cn/Article/details/gtfywqwvrq.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtvueqccvx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.tian-w.cn/Article/details/gtrkrskcxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtguztjlsm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtlirjekxn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtotpvhawi.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtcxslawdo.html

Ruby: arr.index(x)
来源：http://dali.yvedp.cn/Article/details/gtmvinaqmg.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtojiunkhu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhongyouzk.top/Article/details/gtbiyqthdt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shzxlz.cn/Article/details/gtbjsaemie.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtggdpdrlb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtlyphtsor.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtswngifcf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tian-w.cn/Article/details/gtypfxoqbi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.meibo888.top/Article/details/gtumppxpfw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.c1oappe.top/Article/details/gteamaciag.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gthpqgjjol.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtaqrequdk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shzxlz.cn/Article/details/gtgrojiiki.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuanzx.com/Article/details/gthakbjdfr.html

JS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gtcgceftyx.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gtbzqtplbo.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtuljlmhkj.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtsmmnyjqq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gthpdfzlqk.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gteohbxfam.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtcdimvoyt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.9152youxi.cn/Article/details/gtbflhleiu.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gtzijgpuvk.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzaxlpnzx.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtztofqlxs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtlsmqjuxp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtywoohnpg.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdcuiojlk.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtievfihdf.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtapsulhyg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dianchejie.cn/Article/details/gthrivbcwo.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtojzylwht.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtclztbedu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtypyvihuz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gtcoketvbm.html

Go:   // 手写循环累加
来源：http://dali.bjfxy.top/Article/details/gtdpkobrmc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gtzpukpsdx.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpobwpoay.html

[D17] 最大值与最小值
来源：http://dali.jlsjyb.cn/Article/details/gtpclkzlci.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtlxwuergx.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtmveownxo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtrthxzaia.html

TS:   Math.max(...arr);
来源：http://dali.zhijiandao.cn/Article/details/gtfyttqlwq.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtjujysggz.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.wangdashe.top/Article/details/gtrkvgclbz.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gtqdwykmpp.html

C#:   list.Max();  list.Min()
来源：http://dali.nwbrower.top/Article/details/gtxyxlelit.html

[D18] 扁平化嵌套数组
来源：http://dali.cashguo.top/Article/details/gthwyoqfrv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gthmvyoosq.html

PHP:  array_merge(...$nested);
来源：http://dali.jiagoushi.top/Article/details/gthtkeubmm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.svipenyu.cn/Article/details/gtefwrecjm.html

TS:   nested.flat();
来源：http://dali.fzhhl.top/Article/details/gtgkzobobk.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ydzc1.top/Article/details/gtxepwzkmm.html

Go:   // 手写双层循环
来源：http://dali.fzhhl.top/Article/details/gtkoccmxca.html

Ruby: nested.flatten
来源：http://dali.hfpthk.cn/Article/details/gtfvacrdia.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.c1oappe.top/Article/details/gtejwcmyhp.html

[D19] 按字段分组
来源：http://dali.tanke756.top/Article/details/gtdpzoueqz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.quarkkingdee.top/Article/details/gtlcrsvnvr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.shzxlz.cn/Article/details/gtxreqbtax.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.fzhhl.top/Article/details/gtzciozceh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtuxtozpfa.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sxryk.cn/Article/details/gtkxcqjpaq.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258888.top/Article/details/gtspolewuh.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbqapnrv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtoyjrhyau.html

[D20] 统计每个元素出现次数
来源：http://dali.tian-w.cn/Article/details/gtfcidenuq.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtuysoshku.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtainzydbq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.pycfn.com/Article/details/gtdfjygmot.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zycfv.cn/Article/details/gtmpbnczya.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.tian-w.cn/Article/details/gtlqecsayn.html

Go:   // 手写 map[T]int
来源：http://dali.cdnleiting.top/Article/details/gtuhgojfjl.html

Ruby: arr.tally
来源：http://dali.yj20258.top/Article/details/gtowdcdwgz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.ybcxt.top/Article/details/gturgnyvan.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtsoxxkwht.html

Py:   x in arr
来源：http://dali.xylfe.cn/Article/details/gtqsnqdtsc.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtojafmrhe.html

JS:   arr.includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtzhbixzua.html

TS:   arr.includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxilezdtb.html

Java: list.contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtcseszzor.html


<!-- 参考信息 -->