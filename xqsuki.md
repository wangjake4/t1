代发 wailian999

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtqcpsjgpd.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtfgaihsrq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtshnojrrw.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gttxjaeqlk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenzaomai.com/Article/details/gteephsmfz.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtvzzljjdm.html

Ruby: return a, b
来源：http://dali.cucudq.cn/Article/details/gtslcbokcq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtrhmgsnxu.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtfuaqezfc.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtujmwrizw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gttvbrdcnf.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtmygqdkhq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cucudq.cn/Article/details/gtigdeprbc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtxogyzqjy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtcsvgarsy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nwbrower.top/Article/details/gtgxnvakoq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxkxloux.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gtqiehales.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtqpwziogp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtigaqnyxf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtgxhdquvc.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gtwfihvglo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtjajlmmfa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.haohaochexian.top/Article/details/gtpjrfqvuu.html

Ruby: arr.map(&:upcase)
来源：http://dali.bjfxy.top/Article/details/gtzsmtktla.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtpkmaxpul.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtcjvclpgk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtweroygiq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gtjiagoolk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthhzlrwww.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtbgtnquzv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtbnlsarix.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gthvnicnqe.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gtbmgbvyhl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtsftivpvp.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gtgnwothze.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtljhqymit.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtsswsevpj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtmkgxysge.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtujfvoaku.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtqjancdum.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtqydvolnh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtqayvsocd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtycjqpmcz.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtxogooofu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gttplxlvtl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.smart0.xyz/Article/details/gtmqwwjdwx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtwntxhpcd.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtfwprmkpr.html

Java: 方法内为块级作用域
来源：http://dali.cucudq.cn/Article/details/gtzpcoyrdv.html

Go:   花括号块级作用域
来源：http://dali.yj20258.top/Article/details/gtkmqdfczb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gtcliidzyk.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gttauidncn.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtjflwluqi.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtfsiljieq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.c1oappe.top/Article/details/gthngparbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtsncgtqsv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtiktzuunn.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvssczpkz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtbspuvshh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtmhzoyisl.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtwbtdmivs.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtwvaefcst.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckxfhuvs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yonumen.top/Article/details/gtsydljdxy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gthwnjcovf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbbbdrby.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtdlqjouch.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gtxmlctxfp.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gtspetputx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtkxgpcrdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtarmycwqx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtubcvyamz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtydoknkgt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhongyouzk.top/Article/details/gtatozbddv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtcfxsktsj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtkuitgkmr.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtiyokqdqh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258888.top/Article/details/gtcpgheqmc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtucpmxtll.html

[C14] 泛型函数
来源：http://dali.shuidangran.top/Article/details/gtkfftqbbm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gtvodssuoa.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtqaeqtetj.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gtaycyuhxu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtpkveujhu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtkphngpjf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhongyouzk.top/Article/details/gtjyfkzfqo.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtyzyxbzkz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtmqmwgael.html

[C15] 解构 / 展开参数
来源：http://dali.cashguo.top/Article/details/gtkrkmfcit.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtyzcdqrqd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtpykfqlfb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtxfkrwmbq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtojxiaujo.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtljuljrkd.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gtokcklidu.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtuomqngxx.html

C#:   var (a, b) = pair;
来源：http://dali.xinyue.icu/Article/details/gtwfmubyop.html

[C16] 函数 / 方法重载
来源：http://dali.ybcxt.top/Article/details/gtfwejlure.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtechxlznw.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gthrmybshz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtklhsyqoi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtligvfcxw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cashguo.top/Article/details/gtgcbnskzp.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtwzcmvthm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.guannengcc.top/Article/details/gtuchdrdbq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangdashe.top/Article/details/gtjtwfnboh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtszhksjvi.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtlrthekdu.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwlccuzes.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258.top/Article/details/gthaaeslwn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtvcyntrfr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yanxiufei.cn/Article/details/gteejabndg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtwzlhtqyh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtcknrjsbp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtrwnljcjx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtfcwzllnd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtkojglpck.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hongshengwenyu.top/Article/details/gtgkqshgtv.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahjxykxn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guannengcc.top/Article/details/gtdsschuqo.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtgsrtnebb.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtucdgqkxo.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtvndlvvap.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtwtxkvufs.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqbcfuj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gteozqfawz.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtvspuptnn.html

[D03] 在指定位置插入元素
来源：http://dali.daria6918.cn/Article/details/gtuncemjbo.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gtdidofwgr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtdpiiklge.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtrhpcqetd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtoddwlgmj.html

Java: list.add(0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtqhnpvvbn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yongpay.top/Article/details/gtmmyvpamt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtwqyicofg.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtnlkhohbq.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtxjbhgbku.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.daria6918.cn/Article/details/gtpahhqinj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbfgvitw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtpomnpkmo.html

TS:   arr.splice(0, 1);
来源：http://dali.mhx1999.top/Article/details/gthynhtrcd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gttsnqwecx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtsjpzllpt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gtswmloika.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtdlustzos.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtnlcjtcwu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtzkpzyysh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtmzdrkoss.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtaaxijkhj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gtamftznmg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gthsheebnx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtqzcvuaox.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gtcwyimsnz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gtjfhhxhwn.html

[D06] 数组长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtxikdfvmi.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtcsdkkmth.html

PHP:  count($arr);
来源：http://dali.sxryk.cn/Article/details/gtdpaggvxh.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtfwevvjkl.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtjvfjzdiw.html

Java: list.size();
来源：http://dali.daria6918.cn/Article/details/gtyomikgns.html

Go:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gtxtwctxie.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtpedamune.html

C#:   list.Count;
来源：http://dali.yj20258.top/Article/details/gtydlmnuia.html

[D07] 切片 / 取子数组
来源：http://dali.ivvv.top/Article/details/gtfckwhhdi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtgodmyxil.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtmjmrwfhj.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtnhmrsuza.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtukkjpkvc.html

Java: list.subList(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gthrhikkhm.html

Go:   arr[1:4]
来源：http://dali.xziqi.cn/Article/details/gthndvsnsm.html

Ruby: arr[1, 3]
来源：http://dali.dianchejie.cn/Article/details/gtvaxceimb.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtdwomfamn.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtesuyrpth.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhiwuduotai.top/Article/details/gtzoefenga.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gtiryxyopr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtmgjddqdu.html

TS:   [...a, ...b];
来源：http://dali.aibaodan.cn/Article/details/gtzjjgeoku.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sysykeji.top/Article/details/gtcewnbhfx.html

Go:   append(a, b...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthslomfoc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqyehclq.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtejtnkemh.html

[D09] 排序（升序）
来源：http://dali.nanxuanxn.top/Article/details/gtlxjxutvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtmskirgbl.html

PHP:  sort($arr);
来源：http://dali.cheryme.top/Article/details/gtudzgrves.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtthsffdkq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtlflkmhsf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dashuyun.cn/Article/details/gtxzftxzdb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtitifyywp.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtzwwdqals.html

C#:   list.Sort();
来源：http://dali.ybcxt.top/Article/details/gtxiqwosji.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gteanedonq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtapkjdiwn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtebhnhppe.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtrrqbyjts.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtyvecjynf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gtpyoqihco.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnxiangtu.top/Article/details/gtinbhwxtj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtwavmzysk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtdvfunmcg.html

[D11] 反转数组
来源：http://dali.aizwys.cn/Article/details/gtseqctwub.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zdqjudy.top/Article/details/gtbgpgrnwt.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtzhhsbblt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gaohongyu789.top/Article/details/gtblawtxgy.html

TS:   [...arr].reverse();
来源：http://dali.andypj.xyz/Article/details/gtauqthnbo.html

Java: Collections.reverse(list);
来源：http://dali.zhijiandao.cn/Article/details/gtufddzoii.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtwqshmntw.html

Ruby: arr.reverse
来源：http://dali.hnqzz.top/Article/details/gtbmzqflex.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gtavymeylx.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gtwscsvunq.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtbqskrzsh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtibjmrply.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gtxuyrfvsl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhengqikj.top/Article/details/gttydqmjlq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shuidangran.top/Article/details/gtplfzvnqj.html

Go:   slices.Index(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtrisjmtge.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtdltxoyau.html

C#:   list.IndexOf(x);
来源：http://dali.jyoumei.cn/Article/details/gtnvtxyjsc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gtxnnzywyx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cucudq.cn/Article/details/gtqxacffef.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zdqjudy.top/Article/details/gtupdtdguv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtminlfnie.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtyqcqpqqb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuanzx.com/Article/details/gtjeovtste.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtuibuekbf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gotoacloud.top/Article/details/gtrlhvjwjf.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gttlsoyxmh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yuxming.cn/Article/details/gtnvqnuape.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cdnleiting.top/Article/details/gtxlybmtrc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtwmbpnbaq.html

JS:   arr.map(x => x * 2)
来源：http://dali.fengsongda.top/Article/details/gtqfvcyvtl.html

TS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtbrhsrulm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zycfv.cn/Article/details/gtddphdsqp.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtsleftvpz.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtemobrkgj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtnswmrfsx.html

[D15] 去重
来源：http://dali.jqgfzy.top/Article/details/gtjnxwwjuy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtwrhtxnch.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtzuwgjelx.html

JS:   [...new Set(arr)]
来源：http://dali.xinyue.icu/Article/details/gtxszstdxl.html

TS:   [...new Set(arr)]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmkwjhae.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.316326.xyz/Article/details/gtwfkoobyj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fzhhl.top/Article/details/gthhxrwstq.html

Ruby: arr.uniq
来源：http://dali.hammf.cn/Article/details/gthxpynylj.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gtbtnwtwkq.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gtxbspzqis.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gtgmsdlqbd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.guannengcc.top/Article/details/gtwxwwqkbg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtdwzvdjiw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhongyouzk.top/Article/details/gtromjhayp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.smart0.xyz/Article/details/gtcywshqmg.html

Go:   // 手写循环累加
来源：http://dali.9152youxi.cn/Article/details/gthwkohuvo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yongpay.top/Article/details/gtjjnlcune.html

C#:   list.Sum();  list.Average()
来源：http://dali.ppjwa.cn/Article/details/gtotvxzwtp.html

[D17] 最大值与最小值
来源：http://dali.snrcjt.cn/Article/details/gtluqprbeq.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gtihfqcmza.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenzaomai.com/Article/details/gtevrpxurf.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jinqigufen.top/Article/details/gtyhdtlrsq.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtkqbokimc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gttijuwlvy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.iojbl.cn/Article/details/gtvuxalgsh.html

Ruby: arr.max;  arr.min
来源：http://dali.vqdsnc.cn/Article/details/gtnhilurpf.html

C#:   list.Max();  list.Min()
来源：http://dali.316326.xyz/Article/details/gtyfwvizzu.html

[D18] 扁平化嵌套数组
来源：http://dali.chenjidiqi.icu/Article/details/gtmzunrbwf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sxryk.cn/Article/details/gtcvlopavj.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gtncbidpkr.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yuxming.cn/Article/details/gtmihrxage.html

TS:   nested.flat();
来源：http://dali.jqgfzy.top/Article/details/gtmxklrrlc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.sysykeji.top/Article/details/gtuenwewxf.html

Go:   // 手写双层循环
来源：http://dali.hfpthk.cn/Article/details/gtmpgkekko.html

Ruby: nested.flatten
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjtafjxj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.xylfe.cn/Article/details/gtztfytdhe.html

[D19] 按字段分组
来源：http://dali.ehwqpu.com/Article/details/gtpnfopvcf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.hysaishi.cn/Article/details/gtubpmfgwo.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.9152youxi.cn/Article/details/gtmlqinzvg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtyznrhldb.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sweek.top/Article/details/gtvadawjif.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.hnqzz.top/Article/details/gtlfzhvfix.html

Go:   // 手写 map[string][]T
来源：http://dali.tian-w.cn/Article/details/gtmpdcwnik.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.yangfankeji.com/Article/details/gtwnvjwnwp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.aizwys.cn/Article/details/gtozcdyoig.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258.top/Article/details/gtatqfeuqh.html

Py:   Counter(arr)
来源：http://dali.shzxlz.cn/Article/details/gtmdwwlodf.html

PHP:  array_count_values($arr);
来源：http://dali.cdnleiting.top/Article/details/gtzvvfnfkk.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgcrpcqv.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.guannengcc.top/Article/details/gtbkixykvf.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.yj20258.top/Article/details/gtdxnvqppq.html

Go:   // 手写 map[T]int
来源：http://dali.xziqi.cn/Article/details/gttxowlpaj.html

Ruby: arr.tally
来源：http://dali.dashuyun.cn/Article/details/gtxhahdepz.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhiwuduotai.top/Article/details/gtsoaeriuv.html

[D21] 判断是否包含某元素
来源：http://dali.dianchejie.cn/Article/details/gtqczrenpe.html

Py:   x in arr
来源：http://dali.hnqzz.top/Article/details/gtpszodskg.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jlsjyb.cn/Article/details/gtvynsjxeh.html

JS:   arr.includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtxdmcidbh.html

TS:   arr.includes(x)
来源：http://dali.jianghu66.top/Article/details/gtgihzvdix.html

Java: list.contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtnjtvdykj.html

Go:   slices.Contains(arr, x)
来源：http://dali.ybcxt.top/Article/details/gtvxtuhigy.html

Ruby: arr.include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtepbzledi.html

C#:   list.Contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtokmbtcwu.html

[D22] 复制数组（避免共享引用）
来源：http://dali.svipenyu.cn/Article/details/gtdjwllsik.html


<!-- 参考信息 -->