代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gttcgswjly.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gtdmfxlpla.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtmlzpjnae.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gtwptmpdnd.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gtepplcqxi.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtbtixeqxh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtgyepecko.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtxeuwmexb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtactgmegc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtbiwasima.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtfjsvychd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sxryk.cn/Article/details/gtufmcjbsw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtcosgtvak.html

[C07] 把函数作为参数传入
来源：http://dali.0kj1m.cn/Article/details/gtkqtyrfhw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtsgklzejq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtmkodrpom.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gtjvpjwfcu.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtdpsxrceo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtpcdpmtua.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtxibjrxji.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtwknqealo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ivvv.top/Article/details/gtgtwuauiv.html

[C08] 闭包
来源：http://dali.chenzaomai.com/Article/details/gtqnudncfc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtlanqnhwo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtfqcbkjlq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gttticxteo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtkenbblkq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtsatdiric.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtyuwwcryq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtcuyrctxe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtjpzfvqkm.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtagjreeyr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtnhxcssha.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtpontdzxp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmremyfgs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtszkhzklo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtphyomlzm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gtwtavtycr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtvhxdpcge.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtylmzpwsd.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtcdlyyaqp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gtopbwuycj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gtfpihopqk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtplaxuzid.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtkcptsebr.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtqteykeja.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtprjjqmxg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.dashuyun.cn/Article/details/gthbbyzjxd.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtwsscdotj.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtmjtbdktw.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtcgwkzagz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtjnnxixdz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtxebekzeu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtoqpgygtr.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtnmcxcuud.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.feifeiyinyue.top/Article/details/gtzakkjebc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.snrcjt.cn/Article/details/gtmonimsrl.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtzrduvesr.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gtsfkbpaca.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gttvytsnjj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aibaodan.cn/Article/details/gtziyveusf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtgorasmnt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtdthdiemw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtawffzokc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtiypiosnm.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj202588.top/Article/details/gtdrsbmuzo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gtvzjehirq.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtxfrqvtvj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj202588.top/Article/details/gtvoxfzexw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtyidxkuzj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigfzy.top/Article/details/gteqrefvyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtxhlctotq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtifhaezkh.html

Go:   func add(a, b int) int
来源：http://dali.jqgfzy.top/Article/details/gthytydfyp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnqzz.top/Article/details/gtdjhgxsmt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gtwnngqixx.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtvrxoaqky.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtiyssblwv.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtcznvkmyu.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gtepcatjby.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtgstyzagx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtpbyqrbcf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtspxqfpzi.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtygpxsngv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtvwwvhczr.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtbzcxqmuy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtvhxkxxcc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtichmwrgn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvuqndbj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gttzauidll.html

Java: // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtcmjmwjdn.html

Go:   // 无解构
来源：http://dali.pengpengdd.cyou/Article/details/gtrjdzquqz.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtegabcyzr.html

C#:   var (a, b) = pair;
来源：http://dali.snrcjt.cn/Article/details/gtmntddduq.html

[C16] 函数 / 方法重载
来源：http://dali.cheryme.top/Article/details/gthjpgdnlc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.havefunace.top/Article/details/gtuktydarp.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtsrpgxsrz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtdmwsobzi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gtobvxwjqo.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtvoddbnwj.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtjmnilwlr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gttatkbxqr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtofrcuuit.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtheebdewd.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gtszqmcsyt.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxeflwedc.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtpyfpiheg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shangyingyoupin.top/Article/details/gtcvzytcqt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj202588.top/Article/details/gtgnjmcrmw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yangfankeji.com/Article/details/gtfcthmyld.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cdnleiting.top/Article/details/gtdubgallu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtpomicfyn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtrfkvdkub.html

Ruby: arr = [1, 2, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtumnwkrws.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtgrisewhr.html

[D02] 追加元素到末尾
来源：http://dali.gaohongyu789.top/Article/details/gtlxkqnfgc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtkdxautko.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtmboormpf.html

JS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtpajhumjj.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gtlsgvzxmu.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gtqqopohoe.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gtljvbjjbs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtuhlyripf.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtusxovbyi.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtibryyybd.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gtmyjhrjwm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.0kj1m.cn/Article/details/gtlkklipze.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnxiangtu.top/Article/details/gtxpcleicp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtuuendldv.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtdxqfxyyb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelyihqms.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtkvvacjfy.html

C#:   list.Insert(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtcijkqzyf.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gthjlwttzo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtgodwfksq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gtpgdtlvnv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtteyynbvw.html

TS:   arr.splice(0, 1);
来源：http://dali.yongpay.top/Article/details/gtoibiooia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtescbuzpo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yanxiufei.cn/Article/details/gteestvted.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtqikuywyb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jiagoushi.top/Article/details/gtadfwskat.html

[D05] 访问与修改元素
来源：http://dali.meibo888.top/Article/details/gtnmgnhyst.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtnewsfscu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtqetftklu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtefhfqcgo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gtilarzbym.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtoczwexpf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtbtajwmzc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ppjwa.cn/Article/details/gtxoictyjq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtvlaobmsl.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtnpkjbvfb.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtleijdqbc.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gttmgerqyp.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtwmfnxxoj.html

TS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gtedgbkakl.html

Java: list.size();
来源：http://dali.tian-w.cn/Article/details/gtghwajcky.html

Go:   len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtmintwuez.html

Ruby: arr.length; arr.size
来源：http://dali.nanxinkj.top/Article/details/gtcaqnkcid.html

C#:   list.Count;
来源：http://dali.hywenlv.cn/Article/details/gtkwwfhevx.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtrstnxiaz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gtaxsbkrel.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyszhxpa.html

JS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gttknzvtlr.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtsxbintwh.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdgnvxea.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gteozxyziv.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtakcmyyuo.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtzsesguyf.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtninzvfug.html

Py:   a + b;  a.extend(b)
来源：http://dali.zycfv.cn/Article/details/gtqltfksmu.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtwnbyycuu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yueranfly.top/Article/details/gtvngtsybh.html

TS:   [...a, ...b];
来源：http://dali.nanxinkj.top/Article/details/gtankhgvdx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xinyue.icu/Article/details/gtjujrvxme.html

Go:   append(a, b...)
来源：http://dali.gogol.net.cn/Article/details/gtlpnfvedw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.haohaochexian.top/Article/details/gtntgutcwu.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gtzviclwxy.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gtdlexyrhs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnqzz.top/Article/details/gtcbsnntmz.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtrvyppzfx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guowangkeji.top/Article/details/gtkthleacq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtbxvycemm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtgghxrvlg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtixbrgniy.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gttcqlhlae.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtyqnzueoy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtcmymgknz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nwbrower.top/Article/details/gtbipopqoi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtfuwwkrbr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnqzz.top/Article/details/gtdnoobngr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gtccaobhbj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gtzxukqdjj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gttnooptyp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.nanxuanxn.top/Article/details/gtkyhurcaa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shangyingyoupin.top/Article/details/gtjtyzpxfm.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtmvjaczhw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.tian-w.cn/Article/details/gtsyxjpdyk.html

PHP:  array_reverse($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtuxpgswoy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jyoumei.cn/Article/details/gtczhqtmgl.html

TS:   [...arr].reverse();
来源：http://dali.yangfankeji.com/Article/details/gtkguiaayu.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtlkifnoki.html

Go:   slices.Reverse(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmapadfac.html

Ruby: arr.reverse
来源：http://dali.guannengcc.top/Article/details/gtafenygnd.html

C#:   list.Reverse();
来源：http://dali.iojbl.cn/Article/details/gtzqpuhijn.html

[D12] 查找元素下标
来源：http://dali.ppjwa.cn/Article/details/gtwqrtyhkj.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtfblbajfy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gtequzkjox.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yuanzhike.top/Article/details/gtzbejjyyo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guowangkeji.top/Article/details/gtrocnhbop.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sufxvd.cn/Article/details/gtynwyjrgj.html

Go:   slices.Index(arr, x)
来源：http://dali.jinqigfzy.top/Article/details/gtjymeobzz.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gtgeqkdzlc.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtpjxaxqlu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtuzpnmpfi.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.aibaodan.cn/Article/details/gtmahegnjn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj20258.top/Article/details/gtzhpziaub.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtgqpwhemj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtvyiaursl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jianghu66.top/Article/details/gtpxmlrwmr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cqqwz.cn/Article/details/gthqdohojm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gtawtiokus.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtlxwwombv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.birdmap.top/Article/details/gtvcfewkyj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cheryme.top/Article/details/gtyomtihiz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tanke756.top/Article/details/gtsgxesovo.html

JS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gtfxyulmea.html

TS:   arr.map(x => x * 2)
来源：http://dali.hammf.cn/Article/details/gtmeetrqhl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fzhhl.top/Article/details/gtaebrqrpu.html

Go:   // 手写循环
来源：http://dali.shangyingyoupin.top/Article/details/gtflfzbblp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gtrstjjcfo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtujqjganp.html

[D15] 去重
来源：http://dali.guannengcc.top/Article/details/gtystyarnu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtrvzbaoyr.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtinongfxe.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtjytfxpsg.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtffnvmnkh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhongyouzk.top/Article/details/gtfqoleksq.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hnxiangtu.top/Article/details/gtbbxhuxdu.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gtnvpuurwx.html

C#:   list.Distinct().ToList()
来源：http://dali.yangfankeji.com/Article/details/gtcrlqslvz.html

[D16] 求和与平均值
来源：http://dali.yanxiufei.cn/Article/details/gthfwgbixd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtefvsonjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenzaomai.com/Article/details/gtxwkqyfer.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yangfankeji.com/Article/details/gtlselcrtj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gticiquxes.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.0kj1m.cn/Article/details/gtevsicqlm.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzuuvsvl.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.pycfn.com/Article/details/gtzbwlqgop.html

C#:   list.Sum();  list.Average()
来源：http://dali.9152youxi.cn/Article/details/gtchrueoot.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtypbfagpe.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtlspntffx.html

PHP:  max($arr);  min($arr);
来源：http://dali.andypj.xyz/Article/details/gtkbvpfgfb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.c1oappe.top/Article/details/gtnjsozfla.html

TS:   Math.max(...arr);
来源：http://dali.yangfankeji.com/Article/details/gtpoflwjit.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhongyouzk.top/Article/details/gtoimyncyt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yonumen.top/Article/details/gtdiiijyms.html

Ruby: arr.max;  arr.min
来源：http://dali.zhixingplan.top/Article/details/gtjfbtzevf.html

C#:   list.Max();  list.Min()
来源：http://dali.hongshengwenyu.top/Article/details/gtbugafzvc.html

[D18] 扁平化嵌套数组
来源：http://dali.guannengcc.top/Article/details/gtvoppwvwo.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gtnemnibfq.html

PHP:  array_merge(...$nested);
来源：http://dali.pengpengdd.cyou/Article/details/gtcjumhbrz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pengpengdd.cyou/Article/details/gtenmqjxee.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gthvcogesf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.ehwqpu.com/Article/details/gtrevjaedi.html

Go:   // 手写双层循环
来源：http://dali.fengsongda.top/Article/details/gtzvbtekel.html

Ruby: nested.flatten
来源：http://dali.jinqigfzy.top/Article/details/gtnsuicjry.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.redwolf501.top/Article/details/gtjmnijuzd.html

[D19] 按字段分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtfxnsityz.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgqjhagea.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzvpavxxc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ehwqpu.com/Article/details/gtfhjxudcm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hongshengwenyu.top/Article/details/gtswvhlzgt.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhixingplan.top/Article/details/gttdfqkfao.html

Go:   // 手写 map[string][]T
来源：http://dali.xinyue.icu/Article/details/gtvvzjwrns.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtpnhhndwa.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.guannengcc.top/Article/details/gtlparkeyq.html

[D20] 统计每个元素出现次数
来源：http://dali.cashguo.top/Article/details/gtmcplpmog.html

Py:   Counter(arr)
来源：http://dali.jianghu66.top/Article/details/gtnopgnxpi.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmphbqhfy.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.cqqwz.cn/Article/details/gtlgkeqyjq.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtykrodvwh.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hammf.cn/Article/details/gtuluarymv.html

Go:   // 手写 map[T]int
来源：http://dali.wangdashe.top/Article/details/gtpijzeglk.html

Ruby: arr.tally
来源：http://dali.xuanzx.com/Article/details/gtkzbuykka.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.cashguo.top/Article/details/gtzylukyus.html

[D21] 判断是否包含某元素
来源：http://dali.jqgfzy.top/Article/details/gtkmpeekvg.html

Py:   x in arr
来源：http://dali.zhengqikj.top/Article/details/gtuoeklqpu.html

PHP:  in_array($x, $arr, true);
来源：http://dali.zhongyouzk.top/Article/details/gtxffvcqog.html

JS:   arr.includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtfoxgyqxm.html

TS:   arr.includes(x)
来源：http://dali.gzhubu.top/Article/details/gttvgssgfc.html

Java: list.contains(x)
来源：http://dali.zycfv.cn/Article/details/gtdjtpqaxn.html

Go:   slices.Contains(arr, x)
来源：http://dali.smart0.xyz/Article/details/gtyciffsig.html

Ruby: arr.include?(x)
来源：http://dali.nwbrower.top/Article/details/gtkxnyvjev.html

C#:   list.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtdvwigffl.html

[D22] 复制数组（避免共享引用）
来源：http://dali.redwolf501.top/Article/details/gtbzaaofgv.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkosnvfwo.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtueolkzii.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.zdqjudy.top/Article/details/gttahcjlud.html

TS:   [...arr];
来源：http://dali.pengpengdd.cyou/Article/details/gtsfpquldi.html


<!-- 参考信息 -->