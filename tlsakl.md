代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtpwuyipan.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqclzlarh.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsuzwevk.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gthvyubdjs.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtpoiakswk.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtjhgquyhy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtmbneeavd.html

TS:   return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtnsvwdtmh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtrqrtbcrm.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gteosgrdxc.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtmhsbredn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gttvuxkvab.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtcsyxuycv.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gtvshpnyae.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtgshmjcmq.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtywowjgyn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtsodchkgy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtpooiczfm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.0kj1m.cn/Article/details/gtkdaowfbu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtpsuzgjsh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtiwxgpghp.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gttatyhhkh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkypprfuy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtdjyoxkvo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtzfinzyoo.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtghyecyos.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gtbhcyhjxd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gteeoihbam.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gtixcsivpy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtfihjiqvm.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtzxjqqptz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtobqjvevf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtnfbedikp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtguqrbxhn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxinkncpb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zycfv.cn/Article/details/gtirhqxpdn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtidvabpro.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtlcrbtihr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gticdmhrgb.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtcnxbhovg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtxdynqvvv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtmqandski.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtxmucipcy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtrnrptyuk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtaencoxlr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gttsdqdnvz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtvjbfiqqo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiemiwemw.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtyuofezhg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tanke756.top/Article/details/gtcgvgcvtp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gtjsqihebb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gteisgmzaf.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtwvupnhff.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtyrfbyrhs.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtveiqomyk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlzqrusw.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gtxinjcpog.html

[C11] 模块导入与导出
来源：http://dali.guowangkeji.top/Article/details/gtihkfptgv.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gttoxcgaff.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shzxlz.cn/Article/details/gtalaffsmv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gttycycgyw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtdajkfwuc.html

Java: import java.util.List;
来源：http://dali.zhoulong.xyz/Article/details/gtckiokgtd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtodzttdlu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cheryme.top/Article/details/gtbcjhtzka.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtwvcwsxlv.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtyhgmljxl.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtxezkndln.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nwbrower.top/Article/details/gtdiezyfly.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjhvwbuoy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhimjbhj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtpiewojlj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gtcnwxenrg.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtqpkwtoos.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtzkerhndn.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtboeulsmc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtfkljqagu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gtnoqufnxu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.havefunace.top/Article/details/gtrfiohzjt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtxtbiqfyt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtuqotsitw.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtjqpiichi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtuwmbirdq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gthwlcfixj.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtvqnhkmks.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtkycijckz.html

PHP:  // 无泛型
来源：http://dali.ybcxt.top/Article/details/gtmjgnugot.html

JS:   // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucgdaash.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gtdfnrjikg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gtfusjgvwq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtyningugv.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtodqmisab.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gttutsrgju.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtthpxlmqs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtatjjutns.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuxming.cn/Article/details/gtsjtlxxqd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gtqjxnxini.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtfbslbqah.html

Java: // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gthasvgech.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtqejryoya.html

Ruby: a, b = pair
来源：http://dali.316326.xyz/Article/details/gttikfgoms.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtlarghsbr.html

[C16] 函数 / 方法重载
来源：http://dali.cdnleiting.top/Article/details/gtyspktplb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gtvypxnhly.html

PHP:  // 无重载
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjnsljlr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.birdmap.top/Article/details/gtfqfahbdu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtzlpeyidm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cucudq.cn/Article/details/gteylwkbcm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxglxikh.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtmomunp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlvuyrxkg.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgozfpbwc.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgufenzy.top/Article/details/gtxdozmjcy.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtldrqgpkr.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtwrsmvnxv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtjujqsagz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtermjjvvh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtycytzlgo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nanxinkj.top/Article/details/gttgtzqamz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangdashe.top/Article/details/gtpfsufbto.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cheryme.top/Article/details/gtyoxhdfkc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuanzx.com/Article/details/gtsicprtcw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gtyxwasswr.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gttrptgyls.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtppzwvjph.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gtddafuppu.html

JS:   arr.push(4);
来源：http://dali.wangdashe.top/Article/details/gtlhbftlqj.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gthrhpufbe.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxakjifgy.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtnemeoayx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtldqocwda.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtfmtkntfa.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gtexjskqdo.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258.top/Article/details/gtuaftduzt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xziqi.cn/Article/details/gtdzsrocbc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.316326.xyz/Article/details/gtuemdzgic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtotdjfkrr.html

Java: list.add(0, 0);
来源：http://dali.tanke756.top/Article/details/gtkmhydtsp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtvlrbyxzm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtjdgtayhj.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtmqcsgstz.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtglqqlacq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtrgvgpyqv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtrrexspjo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ivvv.top/Article/details/gtyvnrywoi.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gtccxwfmjd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtqakyksvv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhijiandao.cn/Article/details/gtnjrthkil.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtrqtqmymy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtvggbbjxz.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtzmfygmnt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtfpalveja.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gtezvqrlat.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtnjtewwrd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guowangkeji.top/Article/details/gtyxgsbrkq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtkhalrqck.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtnjimsglk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtyvhiaqfq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfskmroax.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtunwppmfa.html

Py:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtxvslahwl.html

PHP:  count($arr);
来源：http://dali.sweek.top/Article/details/gtbgyhzvjx.html

JS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtyeluvmmt.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtbjkcdtfd.html

Java: list.size();
来源：http://dali.andypj.xyz/Article/details/gtlmxipuxe.html

Go:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjjwixmqs.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtubzdmoah.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtdpiqxwrr.html

[D07] 切片 / 取子数组
来源：http://dali.zhiwuduotai.top/Article/details/gtldobbbnt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtziemomwv.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtsofzljwm.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtsvcsgedu.html

TS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtqadvpvny.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtxwfshkqr.html

Go:   arr[1:4]
来源：http://dali.gaohongyu789.top/Article/details/gtnrmnlklu.html

Ruby: arr[1, 3]
来源：http://dali.aizwys.cn/Article/details/gtomfrymno.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuanzx.com/Article/details/gtfuocvaah.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gtpgkxbrcs.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtakuhdrws.html

PHP:  array_merge($a, $b);
来源：http://dali.birdmap.top/Article/details/gtmhmmywmb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtubpqwqfk.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtvclcsfbr.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtgpfkaich.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gtgszsybhg.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gtrdyoweot.html

C#:   a.Concat(b).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtcsvmacto.html

[D09] 排序（升序）
来源：http://dali.ehwqpu.com/Article/details/gttluinfju.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtsvzlntvy.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtcpuidrli.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtawmslrza.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtpqetaphk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tian-w.cn/Article/details/gtokvtakig.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zycfv.cn/Article/details/gtxefqcqvc.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtaljvzmbi.html

C#:   list.Sort();
来源：http://dali.0kj1m.cn/Article/details/gtzysrrhxs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtvgkqkfvi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jyoumei.cn/Article/details/gtbybvftsx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtzqmlmuol.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwpuhmjn.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtmmvstfzi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.dashuyun.cn/Article/details/gtptvuyocp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gtmwcpgvsk.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.smart0.xyz/Article/details/gthekayqlf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jyoumei.cn/Article/details/gtdrmsytbf.html

[D11] 反转数组
来源：http://dali.haohaochexian.top/Article/details/gtgdwemnyo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtqntekgxg.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtzepaxips.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gttqbnvvjo.html

TS:   [...arr].reverse();
来源：http://dali.jinqigufen.top/Article/details/gtpenpkgbf.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtjntlpagh.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbguqwll.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gteozvndkd.html

C#:   list.Reverse();
来源：http://dali.xuanzx.com/Article/details/gtaixfoxeq.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gtpalxlbmw.html

Py:   arr.index(x);  x in arr
来源：http://dali.yonumen.top/Article/details/gtxoqfjbwm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yvedp.cn/Article/details/gtvntmvykz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkqofsshx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtpozldxfd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtjnyiabbr.html

Go:   slices.Index(arr, x)
来源：http://dali.gzhubu.top/Article/details/gtgcnmthev.html

Ruby: arr.index(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtbnprjrof.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gtkmmlyrtg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuetiantiany.cn/Article/details/gtrlinokjw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.wangdashe.top/Article/details/gtalmhtkpp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.andypj.xyz/Article/details/gtyfyrzfov.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gttomjjlms.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258.top/Article/details/gtwyuovkoh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.andypj.xyz/Article/details/gtqytutyhy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtqdcfvtux.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtbgcijdxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtjzsjsbdv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtylydyiqp.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhixingplan.top/Article/details/gtmuaiqjku.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtqjswaqxu.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtxakimzox.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtqlqzriub.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtklztjhnu.html

Go:   // 手写循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgbrckdl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gteklcxsun.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtidtdorql.html

[D15] 去重
来源：http://dali.zhiwuduotai.top/Article/details/gtmaopedge.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtzqvrymiz.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtvfoqdlcu.html

JS:   [...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtdqotefwr.html

TS:   [...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gtkubrlvko.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtwvdgvclc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.redwolf501.top/Article/details/gtptuojldh.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gtmmtonmis.html

C#:   list.Distinct().ToList()
来源：http://dali.ydzc1.top/Article/details/gtlaakeftg.html

[D16] 求和与平均值
来源：http://dali.tianlin.xyz/Article/details/gtddoqcymw.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.mhx1999.top/Article/details/gtboiaymtz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xinyue.icu/Article/details/gtwuphzcad.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cashguo.top/Article/details/gtweuklims.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cdnleiting.top/Article/details/gtdsuzfdsk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gtotfgxhrm.html

Go:   // 手写循环累加
来源：http://dali.hnxiangtu.top/Article/details/gtzabrsxoh.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gteurjbcqj.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gtegtthjgy.html

[D17] 最大值与最小值
来源：http://dali.wangdashe.top/Article/details/gtfsdwvuzr.html

Py:   max(arr);  min(arr)
来源：http://dali.c1oappe.top/Article/details/gtutgxdbnp.html

PHP:  max($arr);  min($arr);
来源：http://dali.snrcjt.cn/Article/details/gtyhtqnznb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yvedp.cn/Article/details/gtgoeyixsh.html

TS:   Math.max(...arr);
来源：http://dali.mhx1999.top/Article/details/gtewzkarug.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ehwqpu.com/Article/details/gtmnrcrhlr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.cdnleiting.top/Article/details/gtxfkiknou.html

Ruby: arr.max;  arr.min
来源：http://dali.jyoumei.cn/Article/details/gtwcregesv.html

C#:   list.Max();  list.Min()
来源：http://dali.0kj1m.cn/Article/details/gtsizdsnye.html

[D18] 扁平化嵌套数组
来源：http://dali.ydzc1.top/Article/details/gtcrxmqkyv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.daria6918.cn/Article/details/gtdunkiizc.html

PHP:  array_merge(...$nested);
来源：http://dali.dashuyun.cn/Article/details/gterngntvb.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtgtfixafs.html

TS:   nested.flat();
来源：http://dali.zdqjudy.top/Article/details/gtjqoxnqgc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtcjwxyege.html

Go:   // 手写双层循环
来源：http://dali.jianghu66.top/Article/details/gtyocmxiop.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gtczxkugkd.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.nwbrower.top/Article/details/gtazrrtumy.html

[D19] 按字段分组
来源：http://dali.yuanzhike.top/Article/details/gtyzbznkll.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gogol.net.cn/Article/details/gtwqsddwey.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.svipenyu.cn/Article/details/gtqcfpitgm.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hnxiangtu.top/Article/details/gthvqpibci.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.wangshuangyany.cn/Article/details/gtxsuvjaoo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhengqikj.top/Article/details/gtincwmigm.html

Go:   // 手写 map[string][]T
来源：http://dali.sysykeji.top/Article/details/gtxhxevmyb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.hnqzz.top/Article/details/gtjfgzzcpb.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tanke756.top/Article/details/gteyteoitx.html

[D20] 统计每个元素出现次数
来源：http://dali.xylfe.cn/Article/details/gthdcxmiuc.html

Py:   Counter(arr)
来源：http://dali.ybcxt.top/Article/details/gtdfolxeaz.html

PHP:  array_count_values($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtpxljsbqo.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtarxthgvg.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtjbfhmmef.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.pengpengdd.cyou/Article/details/gtyascvoyt.html

Go:   // 手写 map[T]int
来源：http://dali.cheryme.top/Article/details/gtxqbrvtij.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtynaosxde.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zycfv.cn/Article/details/gtpljtfpcu.html

[D21] 判断是否包含某元素
来源：http://dali.pycfn.com/Article/details/gtqlwiegds.html

Py:   x in arr
来源：http://dali.jiagoushi.top/Article/details/gtgbeyqjnj.html

PHP:  in_array($x, $arr, true);
来源：http://dali.sweek.top/Article/details/gturrudtlv.html

JS:   arr.includes(x)
来源：http://dali.tian-w.cn/Article/details/gtfgkjgvwn.html

TS:   arr.includes(x)
来源：http://dali.sxryk.cn/Article/details/gtrmkjmwcj.html

Java: list.contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtlipbdwgc.html


<!-- 参考信息 -->