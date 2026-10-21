代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gtafrjlaps.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtupepuqpz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtsauozbiw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtwmogwztk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtkzxxewri.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtrmkavqiz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtokvswvup.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtwsjywkwg.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtqarybbua.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtxkcversa.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtsltkdwfi.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gtxmbaoigw.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtxhnmvlmm.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtglsiudow.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gtmcmqacju.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtkvcirelr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgfzy.top/Article/details/gteittbbgr.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gtaotoetxs.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gtrptyjdrr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nwbrower.top/Article/details/gtexpwfbza.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoenuffp.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtmnnttplx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtlzykllff.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtjyivoecv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtxfygliuu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gthakobejp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtbeixmrao.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtrasrjzmq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtqizbpkgl.html

[C07] 把函数作为参数传入
来源：http://dali.hnqzz.top/Article/details/gtyxvojngn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtvraxbjvd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtlbbelgql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtuneqikkx.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gtwlghvmnq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtgekvguoj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtlruygcfg.html

Ruby: arr.map(&:upcase)
来源：http://dali.zdqjudy.top/Article/details/gtgyohacyd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtwrsqekuz.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtommcmjtq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtikwevwji.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtmopvqhxn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtbkknffjc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtkbcqtzcb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtviaemmcq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtgafhqdrv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtatljliuq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkvilzzvw.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtybzkrjzk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtkvaepslt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtsdpiwhoq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtasbjbsjx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtfixncser.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqdwswhr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtageiatne.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtzrisypbl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtxuvqoebo.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtxpgpvkfe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gtxxkmbzti.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtohqrcypm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtktqosnyy.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gtgawuasgw.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtmhiezxcy.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gtxoepahhd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gtedmthdwy.html

C#:   块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtgpgrzekb.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gtljzzwvjn.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gturqekzcf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cashguo.top/Article/details/gtvachrkum.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtcoqqrxyz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gtqmcfhjlv.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtjxcrabev.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yvedp.cn/Article/details/gtenksfief.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtyrrlthmb.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtlvfzgyta.html

[C12] 立即执行函数 IIFE
来源：http://dali.aibaodan.cn/Article/details/gtizvjvrrq.html

Py:   (lambda: print("run"))()
来源：http://dali.sufxvd.cn/Article/details/gthpgkccoy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxuanxn.top/Article/details/gtkynmltnf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtcmrvqsxa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gtussfsrqi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcohjrot.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtwiqnunij.html

Ruby: -> { puts "run" }.call
来源：http://dali.zycfv.cn/Article/details/gtnbvapuso.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtisnjpfdv.html

[C13] 类型声明 / 类型注解
来源：http://dali.zdqjudy.top/Article/details/gtkiigefvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtltvctqbn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtyyswkqxt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtvefcacpz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtcpjqvucg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtgxgvghtd.html

Go:   func add(a, b int) int
来源：http://dali.yongpay.top/Article/details/gtkbaqikqu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtoohmzrfd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtfpyfvgoc.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtohvybxwf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gtnsdjtpgs.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtomxefzyn.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbralhuj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtsgagrzbz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtmiwycpna.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtpbgjelrx.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdhunwjn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtqgjwvsmm.html

[C15] 解构 / 展开参数
来源：http://dali.0kj1m.cn/Article/details/gtzwqofphp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtechweygh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.9152youxi.cn/Article/details/gthxmofkiv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtepapwrrt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shuidangran.top/Article/details/gtelkhmqup.html

Java: // 无解构
来源：http://dali.sweek.top/Article/details/gtywsmzqqz.html

Go:   // 无解构
来源：http://dali.guannengcc.top/Article/details/gtxtejjpyn.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtbnjvoutt.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtqrruisqb.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gttiekkiys.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtvmqahsza.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtrndmlser.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gtyhwqzsag.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtfkgcphvo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtfvzxvzfg.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcnzvzjl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtscxnfpkm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtjtkjyjzl.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgtfxmzpp.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gtoedvvhfg.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtnttrsntw.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtzfsxucys.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtfehcptbo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.mhx1999.top/Article/details/gtgqvlscvr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtbvjmoqco.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtlbvnfylw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tanke756.top/Article/details/gtarmzkzvu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtgkxsfuio.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtkcjfenfh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.birdmap.top/Article/details/gtjclkfvll.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtigtetwzm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gtpomymyvu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtzlgcgsot.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtpszyeaee.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtzezfzkfy.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gtvwfdossp.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtlgqjebbo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtckomlgjq.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtnjtpkkck.html

[D03] 在指定位置插入元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqstgkom.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtaaewiuhd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gttxhyspvr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yueranfly.top/Article/details/gtbjccyajj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtbwpkpyue.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtzkvemojd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dianchejie.cn/Article/details/gtosapuhvw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tian-w.cn/Article/details/gtxwiysscg.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtlceusnwa.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtgeixikyv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtxbalfdwc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gterwdbpuj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtcsncvfzs.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtmodbfola.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hammf.cn/Article/details/gtdaiaeyxo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtekojdzmw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gtptazwzdc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtrqnuqskd.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtyhqebvkk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtkrmclfpn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gthbtblwcg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtsklzphqf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtjrzzonkg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtpwdsjiof.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtdsyoykeh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtpurvimdl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gthyeaxgpq.html

[D06] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtytrydspk.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtdaxrfwzh.html

PHP:  count($arr);
来源：http://dali.aizwys.cn/Article/details/gtqauwyclb.html

JS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gtldzvjwgm.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtamloqyng.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtgdknczes.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtfkrccqgc.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gttfkvuiop.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gtssqjjqxw.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gtlvfhuujv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gttqugawzr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtlgtkviwx.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtowtmyvqq.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtaqftbmhq.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtoaysrurf.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtxivcmqft.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gtcwqzimgl.html

C#:   list.GetRange(1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtmypomnyw.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtbyxzheco.html

Py:   a + b;  a.extend(b)
来源：http://dali.sweek.top/Article/details/gtgsnrjiqm.html

PHP:  array_merge($a, $b);
来源：http://dali.cdnleiting.top/Article/details/gtgzmmdpvq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gtkqtyflcn.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gtiqeibdct.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtgnzjbpfd.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtyxerztao.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxuanxn.top/Article/details/gtetugdnbv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gttbfgaofa.html

[D09] 排序（升序）
来源：http://dali.tian-w.cn/Article/details/gtzcngjxrt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ehwqpu.com/Article/details/gthgusglyo.html

PHP:  sort($arr);
来源：http://dali.nanxinkj.top/Article/details/gtrauiosho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugovhmfc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhiwuduotai.top/Article/details/gtdrytuoka.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtekmpffxm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gtanegqdgm.html

Ruby: arr.sort
来源：http://dali.guannengcc.top/Article/details/gtgzohslim.html

C#:   list.Sort();
来源：http://dali.birdmap.top/Article/details/gtotepxmoa.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guowangkeji.top/Article/details/gtrptjexlp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.chenlongwang.top/Article/details/gtvqpfzzsv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtrvadxwfk.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gtyyarycvv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtdjhmwcvz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jlsjyb.cn/Article/details/gthdkwoopb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtozmljrkp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hnxiangtu.top/Article/details/gtixojtzem.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.hammf.cn/Article/details/gtayywahcq.html

[D11] 反转数组
来源：http://dali.nanxuanxn.top/Article/details/gtumbhoabl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtzvvwxgqq.html

PHP:  array_reverse($arr);
来源：http://dali.9152youxi.cn/Article/details/gtetqltmyq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gtvlopllun.html

TS:   [...arr].reverse();
来源：http://dali.gaohongyu789.top/Article/details/gtlfgavdme.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtqceufobj.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtemisyywg.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtvzywzkpx.html

C#:   list.Reverse();
来源：http://dali.ydzc1.top/Article/details/gtvskjcqmg.html

[D12] 查找元素下标
来源：http://dali.sufxvd.cn/Article/details/gttrlbpbrh.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtprkpmlwu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cashguo.top/Article/details/gtsqhxmkuo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtdueeiwcw.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtctjzyzrd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.dashuyun.cn/Article/details/gtmktzckoj.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvcbugxop.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtammapzez.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtidbftluc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtmzcuhdbl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtnrvrxjel.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sysykeji.top/Article/details/gtohsimkyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtwmtiwzfs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtqlejlcob.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gtawgsqgnr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sweek.top/Article/details/gtnnoeipop.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtcmezhqfn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gtiojpgela.html

[D14] 映射转换（每个元素变形）
来源：http://dali.smart0.xyz/Article/details/gtohatfbjg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtrlkafgsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gtujhbscle.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtcomvxnhm.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtwqxhdzzz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnqzz.top/Article/details/gtyxgxtfpn.html

Go:   // 手写循环
来源：http://dali.kuanghao11.cn/Article/details/gtjrkqrmde.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtgakpwevi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtorzzwapr.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gtuhlfjcgg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtqpufqryf.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtnktfjxfw.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtgekwzdqt.html

TS:   [...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtfhnojwna.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gtdgjvzqeb.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgajihqjw.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gtfkwoycjd.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtxqrvmbxf.html

[D16] 求和与平均值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktyjbngt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtewedqdza.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zdqjudy.top/Article/details/gtdbgnavue.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtpkycolyi.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gtuknajajt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xuanzx.com/Article/details/gtzguombbg.html

Go:   // 手写循环累加
来源：http://dali.smart0.xyz/Article/details/gtghhiwlbk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hongshengwenyu.top/Article/details/gtdqirdrtm.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtcuqxiwuv.html

[D17] 最大值与最小值
来源：http://dali.ybcxt.top/Article/details/gtdgnxsmhj.html

Py:   max(arr);  min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtzwggahdf.html

PHP:  max($arr);  min($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtdxwgzcys.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ehwqpu.com/Article/details/gtpfjzzzqb.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtkymhesjc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ppjwa.cn/Article/details/gthltsezuk.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtbzsubagj.html

Ruby: arr.max;  arr.min
来源：http://dali.sysykeji.top/Article/details/gtrtxspqta.html

C#:   list.Max();  list.Min()
来源：http://dali.jlsjyb.cn/Article/details/gtfztiqrkp.html

[D18] 扁平化嵌套数组
来源：http://dali.nwbrower.top/Article/details/gtcazredlv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jlsjyb.cn/Article/details/gtrbczrvyd.html

PHP:  array_merge(...$nested);
来源：http://dali.chenlongwang.top/Article/details/gtwpzjvmud.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.ehwqpu.com/Article/details/gtsvvxbgba.html

TS:   nested.flat();
来源：http://dali.hfpthk.cn/Article/details/gtqfsdsmuh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ivvv.top/Article/details/gtmkocldjq.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtgiucozqg.html

Ruby: nested.flatten
来源：http://dali.yueranfly.top/Article/details/gtjxsagbfv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.aizwys.cn/Article/details/gtoujnxtue.html

[D19] 按字段分组
来源：http://dali.sweek.top/Article/details/gtmrxwvtut.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtfrgffpkn.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhoulong.xyz/Article/details/gtobkxomlj.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yj20258.top/Article/details/gtxhlnvwrf.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gtddxyqcos.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtvooqvsxj.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtudsrkvgo.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtkwxvurlq.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fengsongda.top/Article/details/gtnefffkbo.html

[D20] 统计每个元素出现次数
来源：http://dali.jqgfzy.top/Article/details/gtqfexulry.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtpvftulut.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtlacfilpj.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tian-w.cn/Article/details/gtzssrlgsu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpgdluyw.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.nanxinkj.top/Article/details/gtwjcksvmk.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdshfjjbd.html


<!-- 参考信息 -->