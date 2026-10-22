代发 wailian999

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtcxjjcfrt.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtounuxlfi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtupsuotxd.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtvpldgbxp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gtqmfwlrrl.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtltmwtayx.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtwkbpscxw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gtciywidoy.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtcvzbbhja.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gtipdvfnef.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhixingplan.top/Article/details/gtahwijsxt.html

JS:   const square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtzkmuqefs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gthbszhqju.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtubuurbrd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzdqgjit.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtcjufswvi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gterfiwhug.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtcrmtzsys.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnyqxmqo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gthttpctud.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtptdhzprs.html

TS:   arr.map(String)
来源：http://dali.c1oappe.top/Article/details/gtvzoaggdn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtomejsxvn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gthcjspfxn.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtoysijvbg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtxmrpvjtz.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gteuviayyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258888.top/Article/details/gtofagfzfz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gtksyyqzzz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtflfyvtcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtibpfmxnx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtocnlyodx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtdclfcnoo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtfttybauh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtlrpsvlkr.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtnyhwfjiw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtpdwqmyqx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtwdposoim.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtimmebhvq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtpslfecqn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtbrkjxrpb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtafbhyolc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtjurvviyc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.c1oappe.top/Article/details/gtsevoersf.html

[C10] 变量作用域
来源：http://dali.bjfxy.top/Article/details/gtfkfjirbp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtcrbleiqv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gtzjfuubpa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtysvdwnhj.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtzgmqdvxu.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gtyweddina.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gtkmnxiigx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gtlncldfst.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gtevirjdvn.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtzwmrkymt.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtdligbgyi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258.top/Article/details/gtjomzzgbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtjybeksnh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtbiawbxlm.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtindivetn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgufenzy.top/Article/details/gtfcrogkho.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhiwuduotai.top/Article/details/gttsqojhnc.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqmelghb.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhoulong.xyz/Article/details/gtdzfdafev.html

Py:   (lambda: print("run"))()
来源：http://dali.tian-w.cn/Article/details/gtacafmekd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtgajdnerf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtdaddibmj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gthikujssj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtcwuiqggq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tian-w.cn/Article/details/gtnhiarlso.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenjidiqi.icu/Article/details/gtcyklblgc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtzlpahyuz.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gtbjuxycez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtlrfhrbdi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gthpvfkmjg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtobcytbem.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtacnhkjtq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtjhkkwsrw.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gthvmampxx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtemzrjhqm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuxming.cn/Article/details/gtcyxzldrt.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtayiidxol.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shuidangran.top/Article/details/gtjhvsjqwv.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gtfwyupkyn.html

JS:   // 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtghlqhqol.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtrwjrsuwt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgrsbekk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.c1oappe.top/Article/details/gtbypzunin.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtkajjtngz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ybcxt.top/Article/details/gtrgegqbwr.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtvkvbtrmy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtbiukywnj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtorztszkq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtlnvrbzdm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtnfkztdra.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gtoculmoqc.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gtfbepermz.html

Ruby: a, b = pair
来源：http://dali.daria6918.cn/Article/details/gtrydlijii.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gtbirfxibi.html

[C16] 函数 / 方法重载
来源：http://dali.yonumen.top/Article/details/gtmnwrsrbz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtwmekcipn.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtwldkndnf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gtgtfgqrvy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtdhmsfesl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtmkpgbqsx.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtwxkfwayu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtmyjbuhhf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gttlhzxeyt.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtriradzzq.html

D. 数组 / 列表 / 集合
来源：http://dali.vqdsnc.cn/Article/details/gtwivriuqr.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtpfpcczwq.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gttpmewtld.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.smart0.xyz/Article/details/gtlglakfuo.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtwnexykke.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtpywhxifb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hammf.cn/Article/details/gtvephdybx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhengqikj.top/Article/details/gthiwtmajx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtuuwbpkhz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhixingplan.top/Article/details/gtcyjwjpep.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hywenlv.cn/Article/details/gtvxlycsqx.html

[D02] 追加元素到末尾
来源：http://dali.ivvv.top/Article/details/gteamavbja.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtnxfksrhy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtxuwnuonl.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtbhkkisxs.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtopdaykko.html

Java: list.add(4);
来源：http://dali.nanxinkj.top/Article/details/gtsvtcldhm.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtptykrpcw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtgcnzmsni.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtsnstnjdq.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gtyuqqdchu.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzzhsqdz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtntvehbwp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtwfmjzcln.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaehnpdon.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsoovcsp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtildidlom.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yueranfly.top/Article/details/gtjvkvhzlz.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtmalsibjv.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtcddyijry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtzjghknck.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gzhubu.top/Article/details/gtfqfnzqdw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gtmnvcfdos.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gtthvnsffg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gaohongyu789.top/Article/details/gtfuqqdjbm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gtkbsnelet.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xziqi.cn/Article/details/gtrsgkfxar.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258.top/Article/details/gtlfosfvmi.html

[D05] 访问与修改元素
来源：http://dali.cqqwz.cn/Article/details/gtddjqtevk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shuidangran.top/Article/details/gtfebtmvpr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtxemedgtx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gtframgeir.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuanzhike.top/Article/details/gtzevrxsvf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yvedp.cn/Article/details/gtmtzchmqs.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtojztaspn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtsxzgejlt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtgjfzyzaf.html

[D06] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtdhkurxbn.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtwgcewkov.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtcpcazaoz.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtajdoofkm.html

TS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtvulxeeas.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gtybydncnj.html

Go:   len(arr)
来源：http://dali.shuidangran.top/Article/details/gtlgiundmt.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gthnwbscbb.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gtajngukbn.html

[D07] 切片 / 取子数组
来源：http://dali.pycfn.com/Article/details/gtdepzcqga.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cucudq.cn/Article/details/gtisnhlrmg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gteeyljvne.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtncsbnjwi.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfogdqdt.html

Java: list.subList(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtvezxkibp.html

Go:   arr[1:4]
来源：http://dali.birdmap.top/Article/details/gtykvluewu.html

Ruby: arr[1, 3]
来源：http://dali.aibaodan.cn/Article/details/gtzijyzjuh.html

C#:   list.GetRange(1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtojeeocdg.html

[D08] 合并两个数组
来源：http://dali.xziqi.cn/Article/details/gtfacemops.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtodgafoyz.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtxyhygugr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gtmhxmyuwh.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtbytjedmq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuanzhike.top/Article/details/gtcolgwzmu.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtfpexlyfj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhoulong.xyz/Article/details/gtnzqrzxyk.html

C#:   a.Concat(b).ToList()
来源：http://dali.ivvv.top/Article/details/gtusbglejf.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtvadnpkwj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xylfe.cn/Article/details/gtlppwfjgd.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtqfoyrgbc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwoqbjen.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtwtbvrttx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ehwqpu.com/Article/details/gtawwryhdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvulznha.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gtbtvkdffr.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtnffdfzfy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gtuaiozega.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngxiieud.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtypecrvht.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdxmphnog.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtnfegicks.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtgyrddmvd.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.svipenyu.cn/Article/details/gtzisopess.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtfcmhynbh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.daxiang520.top/Article/details/gtxezkjcve.html

[D11] 反转数组
来源：http://dali.snrcjt.cn/Article/details/gtvxdomtoh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yangfankeji.com/Article/details/gtjxfkkhho.html

PHP:  array_reverse($arr);
来源：http://dali.dashuyun.cn/Article/details/gtwivcvzxv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxuanxn.top/Article/details/gtqxxnprpv.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gtbjhxgmlh.html

Java: Collections.reverse(list);
来源：http://dali.gaohongyu789.top/Article/details/gtpzvsvwuj.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gttjphyhit.html

Ruby: arr.reverse
来源：http://dali.hammf.cn/Article/details/gtgfuthlqb.html

C#:   list.Reverse();
来源：http://dali.xuetiantiany.cn/Article/details/gtrfgltaia.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtcynavabf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhijiandao.cn/Article/details/gtxaxpcxxw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtbmutptxj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jianghu66.top/Article/details/gtagdvgalk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtblzvcuep.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gtvfwdarbd.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gtqbuqnjaz.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtvvmtxdgs.html

C#:   list.IndexOf(x);
来源：http://dali.cqqwz.cn/Article/details/gtsoylchmg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sxryk.cn/Article/details/gtvddodhqa.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtyhlrpyci.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.fengsongda.top/Article/details/gtiddeagol.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtflnqgtrj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daxiang520.top/Article/details/gtahtvzgeh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtxauluxhd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.guowangkeji.top/Article/details/gtehgtyjxr.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtpaxqdzoi.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtxsqslxsc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtbgkhfsrs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daria6918.cn/Article/details/gtocvwdnho.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daxiang520.top/Article/details/gtyqqlacpj.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtchspuqno.html

TS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gtoccanrmq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.iojbl.cn/Article/details/gtcdpmobnu.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtwnpbtbql.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtirexqluv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gttlahcgow.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gtytgojwzi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtmnlxcktm.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtdgprobnn.html

JS:   [...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtabyenhtc.html

TS:   [...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtogtakjar.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhixingplan.top/Article/details/gtcqhupndu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nwbrower.top/Article/details/gtrnnprpwq.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyiwhukv.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gtuskebgji.html

[D16] 求和与平均值
来源：http://dali.iojbl.cn/Article/details/gtvbpvicmr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtlizqnsho.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.wangdashe.top/Article/details/gtwrfzvxpo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.meibo888.top/Article/details/gtuckthyxr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtawlueaos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.haohaochexian.top/Article/details/gtxlpjegfo.html

Go:   // 手写循环累加
来源：http://dali.pycfn.com/Article/details/gtspjtiiwp.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtujwizvxu.html

C#:   list.Sum();  list.Average()
来源：http://dali.smart0.xyz/Article/details/gtnjumbkiw.html

[D17] 最大值与最小值
来源：http://dali.yanxiufei.cn/Article/details/gtesesxrfg.html

Py:   max(arr);  min(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtwzanqnrk.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtatawbyyc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yuxming.cn/Article/details/gtfcayedcg.html

TS:   Math.max(...arr);
来源：http://dali.hfpthk.cn/Article/details/gtwbcsvhwj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtcgbwomhs.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtsawvqpaw.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtrueaszds.html

C#:   list.Max();  list.Min()
来源：http://dali.tianlin.xyz/Article/details/gtfiwalvac.html

[D18] 扁平化嵌套数组
来源：http://dali.gotoacloud.top/Article/details/gtfrrmqqav.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ehwqpu.com/Article/details/gtmfnapbie.html

PHP:  array_merge(...$nested);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzxqtzjd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gtedcfflob.html

TS:   nested.flat();
来源：http://dali.fengsongda.top/Article/details/gtwvztajud.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xziqi.cn/Article/details/gttyaeclys.html

Go:   // 手写双层循环
来源：http://dali.jinqigufen.top/Article/details/gtdppgpaza.html

Ruby: nested.flatten
来源：http://dali.xuetiantiany.cn/Article/details/gtkmmrrsgi.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzoijrqc.html

[D19] 按字段分组
来源：http://dali.jiagoushi.top/Article/details/gtmknamsyv.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fzhhl.top/Article/details/gtspuydizs.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zhaomingkeji.xyz/Article/details/gturkeamnq.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxinkj.top/Article/details/gtdtwhvfzv.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxinkj.top/Article/details/gtkfvtnbtp.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cucudq.cn/Article/details/gtpzicsjio.html

Go:   // 手写 map[string][]T
来源：http://dali.dashuyun.cn/Article/details/gtsbhmhwtm.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.gaohongyu789.top/Article/details/gtrswsolrz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhijiandao.cn/Article/details/gtuptplasx.html

[D20] 统计每个元素出现次数
来源：http://dali.hnqzz.top/Article/details/gtolzezdpr.html

Py:   Counter(arr)
来源：http://dali.aizwys.cn/Article/details/gtosyegpzv.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtfmxzphux.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.wangdashe.top/Article/details/gteiymlhgm.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtrbdxddru.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.zhengqikj.top/Article/details/gttbahxfvb.html

Go:   // 手写 map[T]int
来源：http://dali.meibo888.top/Article/details/gtzdzxkelh.html

Ruby: arr.tally
来源：http://dali.cqqwz.cn/Article/details/gtkvkoeist.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yongpay.top/Article/details/gtzmptmfsn.html

[D21] 判断是否包含某元素
来源：http://dali.hnxiangtu.top/Article/details/gtegsyieal.html

Py:   x in arr
来源：http://dali.svipenyu.cn/Article/details/gtsicjepww.html

PHP:  in_array($x, $arr, true);
来源：http://dali.cashguo.top/Article/details/gtazzeqdoo.html

JS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtptnivovr.html

TS:   arr.includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtuyesbxlm.html

Java: list.contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtzybeotdq.html

Go:   slices.Contains(arr, x)
来源：http://dali.meibo888.top/Article/details/gtlvhoblxw.html

Ruby: arr.include?(x)
来源：http://dali.daxiang520.top/Article/details/gtvxbxkxmn.html

C#:   list.Contains(x)
来源：http://dali.sweek.top/Article/details/gtbmdycvyq.html

[D22] 复制数组（避免共享引用）
来源：http://dali.zycfv.cn/Article/details/gttrezpdql.html


<!-- 参考信息 -->