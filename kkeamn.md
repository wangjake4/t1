代发 wailian999

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtxgcixqux.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtpnqwqhbp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtybyihdlr.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtoxxkzwhz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcatzwvve.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtudpzmjgw.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtacvshqpl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtclydhtck.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtuumrnror.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gtpmcielwq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.c1oappe.top/Article/details/gtxxzprxrs.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtoallmrca.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtetsufonh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtfifidswr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtjrlgczkx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gtzddlphpk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtpulupqvq.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtrxmbuapk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtwoorynbk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gtbrupcufu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtjobjezkx.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtjabkqras.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaekzgfis.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gtdmatksaa.html

Ruby: arr.map(&:upcase)
来源：http://dali.sxryk.cn/Article/details/gtvidyrsgz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.meibo888.top/Article/details/gtgkvdzryd.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtqwkvbqpr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgfzy.top/Article/details/gtkofziozd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gttudvcjny.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmlokuhrd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtxmnpviau.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtlscxfbfa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtcyobzdnd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtmpfcnpvt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtgopzhtgi.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtljpgbgbf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnnmwamia.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtonjkrboi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtktpvgshy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gthjaupkvv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhixingplan.top/Article/details/gtxjytheac.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlunlemy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtdmdcpzkb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigfzy.top/Article/details/gtyomcegnd.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtzpklnoet.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gtneypcsvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtajcljlyn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gtwhbsobdx.html

TS:   同 JS
来源：http://dali.tianlin.xyz/Article/details/gtuuouvlma.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtuzkwzssc.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtptkpcgot.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gtziynltob.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtgakddden.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtczbtsgul.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtuvhtgxbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhongyouzk.top/Article/details/gthlhzzhte.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhaomingkeji.xyz/Article/details/gteromaqaw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj202588.top/Article/details/gtzrwojoep.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitiekfpl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtksuelbbu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtohapytwc.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtfdaypcns.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gtpvhvohwh.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtzkbquwez.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gttipabufs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtgwlinzqa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtpdmvfrxg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgfzy.top/Article/details/gttwktvvbh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtgphxceqs.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmafwuok.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtboqxvxby.html

[C13] 类型声明 / 类型注解
来源：http://dali.yangfankeji.com/Article/details/gttdpulabt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yvedp.cn/Article/details/gtvaffygpj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtknrlufac.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtasynkaqe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtbmspdcen.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gturipmqev.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrtsmezk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gtoezkccgl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtkzbpvsza.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtheebqkbf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtgkytkhkj.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtqznzwtbr.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtdxcfrrrh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gtknpkufnc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtjtmztkmu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gttljkbbvn.html

Ruby: # 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtcbsfkptx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gtvlrsklko.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gttsdunkff.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtfwdafaxa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gttevxzytr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtqhrrbovn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.mhx1999.top/Article/details/gtctljldky.html

Java: // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtxvkwksuw.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtqinzgppn.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtvzujmzjr.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtcrfskmhz.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtwlayodvq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gthnuzipwo.html

PHP:  // 无重载
来源：http://dali.shuidangran.top/Article/details/gtywdhajhk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtaghnropx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtznzcvxmr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258.top/Article/details/gtudprgmaa.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtwkxxckxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtzmiqhaiz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtdarfofms.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtirwjbjsq.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtmedbvhwf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gthskhknju.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtcotjuotp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtzhxlvdgq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cucudq.cn/Article/details/gtxoqlmjni.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtinkdjmcu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gteqfetsnp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtagqojesg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hammf.cn/Article/details/gtkrxbvoir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jlsjyb.cn/Article/details/gtsnlkggnj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhengqikj.top/Article/details/gtczgdsimm.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtmhzhcyki.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtljhisymm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtkysvsolk.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtdsodxikv.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtoafqdiqh.html

Java: list.add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtutyvhpum.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtthhcwsux.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gtjunitlzi.html

C#:   list.Add(4);
来源：http://dali.zhixingplan.top/Article/details/gtuaxeivva.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtbxzjabeu.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtamhnrkhv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yvedp.cn/Article/details/gtgwhhezvw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtdvdkryid.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gtsmkjzavz.html

Java: list.add(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtidyoxvku.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gtrppmhexm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gtzuihvsdu.html

C#:   list.Insert(0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtfimoxfeq.html

[D04] 删除元素
来源：http://dali.jinqigufen.top/Article/details/gtzjgogrxe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtdhwxinyx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtzbzhhksi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hnqzz.top/Article/details/gtgtgamxsg.html

TS:   arr.splice(0, 1);
来源：http://dali.0kj1m.cn/Article/details/gtmfrccpfi.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbvbktfg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtogffngah.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtibyejnpp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gtvobghguu.html

[D05] 访问与修改元素
来源：http://dali.xuanzx.com/Article/details/gtdusltsnz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtidwomswh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtdmvmwaam.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsxdzuou.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.havefunace.top/Article/details/gtoxtilqhq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtyuugnlvr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtjzkgssrc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtwppwehpk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtcxodbnhe.html

[D06] 数组长度
来源：http://dali.wangdashe.top/Article/details/gtalgpbfsk.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtoweapgvj.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtcuwxupzr.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtkddunkla.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtsyxkckhp.html

Java: list.size();
来源：http://dali.meibo888.top/Article/details/gttdfjtjjr.html

Go:   len(arr)
来源：http://dali.mhx1999.top/Article/details/gtbbdykfmw.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtzjvwakng.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gtnzuisoyf.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtoapwfolj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hywenlv.cn/Article/details/gtbomphaai.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hammf.cn/Article/details/gtdkdkfmqh.html

JS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtiqcwgfdw.html

TS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtogkdyuck.html

Java: list.subList(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpgqyyki.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtncxpbanp.html

Ruby: arr[1, 3]
来源：http://dali.xziqi.cn/Article/details/gtznsdqqwg.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtaxzyli.html

[D08] 合并两个数组
来源：http://dali.gotoacloud.top/Article/details/gthwjieplz.html

Py:   a + b;  a.extend(b)
来源：http://dali.cqqwz.cn/Article/details/gtkbudmlme.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtpeznrkoi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigufen.top/Article/details/gtpkyugsat.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtolueapvf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hfpthk.cn/Article/details/gtrvkmluqq.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrgrxkga.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpmwmhie.html

C#:   a.Concat(b).ToList()
来源：http://dali.yueranfly.top/Article/details/gtutqflgxv.html

[D09] 排序（升序）
来源：http://dali.zycfv.cn/Article/details/gtrcqsfyvm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtwsivzbfd.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtvmoqpole.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gtjzjbmedz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hongshengwenyu.top/Article/details/gtoiiaxljp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ppjwa.cn/Article/details/gtlwewztrr.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.wangdashe.top/Article/details/gtappcunzi.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtwfeoujlp.html

C#:   list.Sort();
来源：http://dali.cashguo.top/Article/details/gtnliqudug.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgfzy.top/Article/details/gtelbomlxi.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtnegzvcor.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtsxtpezpn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gticnrdlzr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtjoqgeqyl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtilfkdxtc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hammf.cn/Article/details/gthdusdqdc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gtwspmbjig.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtulzlfmpc.html

[D11] 反转数组
来源：http://dali.hnxiangtu.top/Article/details/gtzlytenwl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gtrmurjrhx.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtssbbdmfu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtkncvmhdw.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtcatfgyib.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtvhzepytd.html

Go:   slices.Reverse(arr)
来源：http://dali.xziqi.cn/Article/details/gttfxbhskp.html

Ruby: arr.reverse
来源：http://dali.cucudq.cn/Article/details/gtvujtujxq.html

C#:   list.Reverse();
来源：http://dali.0kj1m.cn/Article/details/gtkgtqbpsh.html

[D12] 查找元素下标
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmygugnew.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkcxrojs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtwpdzwerd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhoulong.xyz/Article/details/gtdjjzneda.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtobjmhtqc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhoulong.xyz/Article/details/gtvgjfzyhy.html

Go:   slices.Index(arr, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtxocohibq.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtkjilmixb.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gthtifwjug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtlsplblbu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhengqikj.top/Article/details/gttthboksn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gtqvgfmqvd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nanxinkj.top/Article/details/gtsjjyuata.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhixingplan.top/Article/details/gtkwrcdpuv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.316326.xyz/Article/details/gtibuzgpmv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cheryme.top/Article/details/gtqgrreqok.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aizwys.cn/Article/details/gtnhcsfzgx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzzpdyyxw.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hnqzz.top/Article/details/gtigpbrlzz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.shuidangran.top/Article/details/gtbofmioqb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtdbhulaag.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gthoskpcsr.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtxxwcwgmh.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoykrutmh.html

Go:   // 手写循环
来源：http://dali.hywenlv.cn/Article/details/gtwsytbapb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtlazwprev.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtdqwctwbx.html

[D15] 去重
来源：http://dali.haohaochexian.top/Article/details/gtogdmsfpr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtnbchoxgb.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtjtgtessa.html

JS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gtuurvfziz.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtrgwhgoav.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtagqelrzm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gttofvpuct.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpdwtlzg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gtgktrhwer.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtqehxiwtn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtmfjtkhrs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gthogzkffe.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhixingplan.top/Article/details/gtbpywlefj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuxming.cn/Article/details/gtxlbpwffi.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangtech.top/Article/details/gtclxasmkj.html

Go:   // 手写循环累加
来源：http://dali.svipenyu.cn/Article/details/gtmbucspqi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cdnleiting.top/Article/details/gtmuowmndz.html

C#:   list.Sum();  list.Average()
来源：http://dali.mhx1999.top/Article/details/gtjmcryqzn.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtfgmqarkc.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtycmkbiji.html

PHP:  max($arr);  min($arr);
来源：http://dali.hammf.cn/Article/details/gtpncweftl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gteudakdnl.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gtjxvlpmyl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztszfoxh.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtppyvcwos.html

Ruby: arr.max;  arr.min
来源：http://dali.jinqigufen.top/Article/details/gtqrfiteah.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtyrdpvswm.html

[D18] 扁平化嵌套数组
来源：http://dali.xziqi.cn/Article/details/gtocqztalp.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.wangshuangyany.cn/Article/details/gtrjajvpeo.html

PHP:  array_merge(...$nested);
来源：http://dali.quarkkingdee.top/Article/details/gtkckkajsd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfghqioxj.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gttetxnbpa.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zycfv.cn/Article/details/gtnoprhkmf.html

Go:   // 手写双层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrhsbmho.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtabtzirls.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtuyqwcrkc.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gtelhkxhhy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtupbpzulj.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.pengpengdd.cyou/Article/details/gtsyeakfzs.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.meibo888.top/Article/details/gtkairglvp.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yonumen.top/Article/details/gtwcqqpmyi.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.yuanzhike.top/Article/details/gtfnsrrleh.html

Go:   // 手写 map[string][]T
来源：http://dali.hfpthk.cn/Article/details/gttcqcpbuq.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.havefunace.top/Article/details/gtfkyzlhbl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hnqzz.top/Article/details/gtydudztky.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfukgmegg.html

Py:   Counter(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgndnnuao.html

PHP:  array_count_values($arr);
来源：http://dali.bjfxy.top/Article/details/gtdwtjofnx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yonumen.top/Article/details/gttotltlln.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tanke756.top/Article/details/gtyzvserqh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhongyouzk.top/Article/details/gtinvvruqf.html

Go:   // 手写 map[T]int
来源：http://dali.sysykeji.top/Article/details/gtajgrkrzy.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gttgcembeh.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtwmbfxelm.html

[D21] 判断是否包含某元素
来源：http://dali.gaohongyu789.top/Article/details/gtareucffe.html

Py:   x in arr
来源：http://dali.sxryk.cn/Article/details/gtiokijwba.html

PHP:  in_array($x, $arr, true);
来源：http://dali.dashuyun.cn/Article/details/gtrtqugwbw.html

JS:   arr.includes(x)
来源：http://dali.iojbl.cn/Article/details/gtngpvjmug.html

TS:   arr.includes(x)
来源：http://dali.sysykeji.top/Article/details/gtctptptpt.html

Java: list.contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtkazrpelt.html

Go:   slices.Contains(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtxsyfoima.html

Ruby: arr.include?(x)
来源：http://dali.pycfn.com/Article/details/gtqvvtlhle.html

C#:   list.Contains(x)
来源：http://dali.sxryk.cn/Article/details/gtnupawhdo.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gttdxwezln.html


<!-- 参考信息 -->