代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtfgxzbnen.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtcfehkjto.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gthrfynogh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtknnhjiof.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gtbyxzohip.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtnuzdlkcz.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gtnsykswhh.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtmcmiupbk.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gttsygnobh.html

PHP:  return [$a, $b];
来源：http://dali.quarkkingdee.top/Article/details/gtcwfigeqe.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gtrbgpdauw.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtkhvfjwgx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtlfotrxzp.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gthgtitpvy.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gthuotbtak.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtpuqtsskv.html

[C06] 匿名函数 / lambda
来源：http://dali.yuxming.cn/Article/details/gtxtrqfbgb.html

Py:   square = lambda x: x * x
来源：http://dali.ybcxt.top/Article/details/gtqgxpsquf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ivvv.top/Article/details/gtzzfqmoyw.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtjduekwyq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtpdfdklch.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtcwfwvcdv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtgmlkxzpx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtmmdiacqb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ydzc1.top/Article/details/gtjsgfyqid.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtcdgsrylq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxinkj.top/Article/details/gtxljmcmol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtnepdklsg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtyvthznvx.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtzehjykgh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhengqikj.top/Article/details/gtwakoqulw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gtrkhgrajq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtqhcbedfk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtweaxcnjs.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtivktsbrw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gticisdqcw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hongshengwenyu.top/Article/details/gtphakbmka.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtyadurewc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtsskxhpnr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtwfimprat.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtoxsomcyi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gthmcrvoxj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtksihipsb.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtztilxkoe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtvmeopylt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtxxoyxkqo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gthhvjgmbx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtryxzctak.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtoadwrrjj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtzpaafxpu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtrruogizl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtwkcwuqgv.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtoebeacar.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258888.top/Article/details/gtyjnzguxx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jyoumei.cn/Article/details/gtagxgvezg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtfovidnzs.html

TS:   同 JS
来源：http://dali.zhengqikj.top/Article/details/gtujvsgxvo.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtqpmvdlfv.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwsbwzni.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenjidiqi.icu/Article/details/gtntejgnen.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gteewicsrv.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtqsgznimj.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtpzrksgtl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtjmslegmf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtncbmpayp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtmhzbivjj.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gtokuiztnu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gtwkkcjgsu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtrzsqqzzr.html

C#:   using System.Text;
来源：http://dali.ivvv.top/Article/details/gtikzmrsuy.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtjzftltgu.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gtdczqlajz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcuusvjf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtrthsewza.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtlobatsrp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yangfankeji.com/Article/details/gtdtdnppmx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangshuangyany.cn/Article/details/gtmmgezbxg.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtwuremiic.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtbisbrzxs.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtygptckad.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gtiakozaaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sweek.top/Article/details/gtnvwjwmnt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gtelchwxcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtkmrjguiy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtbgfttehw.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gtykhnrzxr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtqlmnqanv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtclzhmgud.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtkzhemdlk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtrnbshxbg.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gttcwekzox.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gthlctjrsk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zdqjudy.top/Article/details/gtvgzsiuua.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtehyjvfjo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ivvv.top/Article/details/gtdjxvxzaf.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtbptczcyw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gttsikweie.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtwjeiyaoa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtdidirdaj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gthjpehbpt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gthqrcaltd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtwiafskfl.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtgdasiidz.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtxmrttwdd.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gtkvcjlamb.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtgqdwphhi.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtampvmivc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtzdksxpym.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtlbbbiwyy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gteejcogwo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gthafexpun.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtpuweadci.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtihngklco.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuanzx.com/Article/details/gtorbpkfac.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtrqgkpiuq.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gttlpgfqpa.html

D. 数组 / 列表 / 集合
来源：http://dali.zhengqikj.top/Article/details/gtpylwrqrq.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtfrjzabli.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtthajjybb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gtotcluwxf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtwdlitdxz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtivhquttf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtwfyqkezv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenjidiqi.icu/Article/details/gtvbiigoki.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gogol.net.cn/Article/details/gtjrcyphye.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtpwrikqfu.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtwwszegjy.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gthygvxxuh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yueranfly.top/Article/details/gtvlwthkhp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.c1oappe.top/Article/details/gtrucrqjac.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtkkulrwwq.html

TS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtvhjytsfl.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtiyhywfuu.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtnheksvun.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.iojbl.cn/Article/details/gtdpmtnmsz.html

C#:   list.Add(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtzjhmmklg.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbrzptjn.html

Py:   arr.insert(0, 0)
来源：http://dali.ppjwa.cn/Article/details/gtvdfuzthd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gttuhgsuor.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtnldevlfi.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jianghu66.top/Article/details/gtxlvqcmnj.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtofiinqib.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtnlbqmrkt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtiesxgfjr.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtcvcfwjnh.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtqvktrjzn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gtcgmdaxys.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmznfrnfh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtnntwmclw.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gteuyhtisx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cashguo.top/Article/details/gtmiowrmet.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gtqthqjisa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dashuyun.cn/Article/details/gtwpkkfjkt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtwazkefjd.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtwgatwzza.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtglwokjsc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yonumen.top/Article/details/gtekvlhvxx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtsxmqvald.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshuaqzew.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinghuilouyu.cn/Article/details/gthykukbet.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gttqwynmwo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtzdxdkioh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gtiznarxrs.html

[D06] 数组长度
来源：http://dali.yongpay.top/Article/details/gtlqtfsazb.html

Py:   len(arr)
来源：http://dali.hfpthk.cn/Article/details/gtujamuuof.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtumdnymno.html

JS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gttqtvllgp.html

TS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtkblvsumh.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtvqkxzicv.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtbnsvpara.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtffzulwli.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gtzqmxnozm.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtkzsukiss.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.9152youxi.cn/Article/details/gtrjqafkad.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuanzx.com/Article/details/gtvlcgalwx.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtsjisdzqy.html

TS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtjtxtlzti.html

Java: list.subList(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtgdyceipt.html

Go:   arr[1:4]
来源：http://dali.yueranfly.top/Article/details/gtfrunivxn.html

Ruby: arr[1, 3]
来源：http://dali.shzxlz.cn/Article/details/gtudgdpkcz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gteibenags.html

[D08] 合并两个数组
来源：http://dali.yonumen.top/Article/details/gttancbfdd.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gtxzkhnlwv.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtixihszxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gtnyepfuck.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtpxcflgub.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.birdmap.top/Article/details/gtallunqtv.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtlarykwip.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yangfankeji.com/Article/details/gtzqpduiab.html

C#:   a.Concat(b).ToList()
来源：http://dali.hongshengwenyu.top/Article/details/gtvisekhlw.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtirqobuzw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtfikhnxvl.html

PHP:  sort($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtvxekadkg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gttupmoyxz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtmermscdw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cucudq.cn/Article/details/gtkoflbiwz.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtkxywcmwc.html

Ruby: arr.sort
来源：http://dali.shzxlz.cn/Article/details/gtbafnturi.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtsasennnc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnzzulry.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtlinrumcz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gtazicdgwq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtfbzlmaqm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gthldrcmlg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gaohongyu789.top/Article/details/gtcxnzohxi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.vqdsnc.cn/Article/details/gtcghdoeuu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtbhzuqktz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuetiantiany.cn/Article/details/gtwmdtmcyl.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtwfvfpxin.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtqszkpodv.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtdeurmwju.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhijiandao.cn/Article/details/gtoqwqqbmm.html

TS:   [...arr].reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtncvszlwv.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtjowvgwdt.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtcnlcozrp.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gtqrvkqslh.html

C#:   list.Reverse();
来源：http://dali.yj202588.top/Article/details/gtsuiypzyj.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxylizkh.html

Py:   arr.index(x);  x in arr
来源：http://dali.feifeiyinyue.top/Article/details/gtefibvmct.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtxthwpucb.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtoaboetla.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtvsfaboiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.snrcjt.cn/Article/details/gtuvjzuifm.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtnpoujzif.html

Ruby: arr.index(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtlelsqvln.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gticxqvdnc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zdqjudy.top/Article/details/gtotgbmrsp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtyueburdo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.hywenlv.cn/Article/details/gtbbsmszml.html

JS:   arr.filter(x => x > 3)
来源：http://dali.9152youxi.cn/Article/details/gtzppkkxdv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtlbpudmfv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cashguo.top/Article/details/gtvdsvnszw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.quarkkingdee.top/Article/details/gtjewhfgmc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsqjwmdm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtpiseomem.html

[D14] 映射转换（每个元素变形）
来源：http://dali.dashuyun.cn/Article/details/gtpezvfibn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtkpulmhxa.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtivffwtir.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gtwmvghpgl.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtikzluspx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtsivcvopz.html

Go:   // 手写循环
来源：http://dali.fzhhl.top/Article/details/gtswgbopuh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gtktgbnjea.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtuzazwuzf.html

[D15] 去重
来源：http://dali.nwbrower.top/Article/details/gtvfmhpatr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtijiqvqli.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtnczlganc.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtkqedavqp.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtenirrcxt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.wangdashe.top/Article/details/gtydpiviay.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.9152youxi.cn/Article/details/gtstbcgfak.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjimxrsvc.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gteupqjvaz.html

[D16] 求和与平均值
来源：http://dali.guowangkeji.top/Article/details/gteqqukpfm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.c1oappe.top/Article/details/gtjxrafgsg.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gtgtvtormb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtryvlynqn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtwfuvibmy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtjkwrtjbk.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtustxqhdm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.snrcjt.cn/Article/details/gtoolzyoox.html

C#:   list.Sum();  list.Average()
来源：http://dali.pycfn.com/Article/details/gtziuhhltn.html

[D17] 最大值与最小值
来源：http://dali.cqqwz.cn/Article/details/gtxxwvtsag.html

Py:   max(arr);  min(arr)
来源：http://dali.chenzaomai.com/Article/details/gtqaeczaae.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtwylwsgks.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtywpdtwgo.html

TS:   Math.max(...arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtsvsyqcwc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gtmrizlzym.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtrfiycnnn.html

Ruby: arr.max;  arr.min
来源：http://dali.wangshuangyany.cn/Article/details/gtmxgcfrfy.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258.top/Article/details/gtclszyfxe.html

[D18] 扁平化嵌套数组
来源：http://dali.pengpengdd.cyou/Article/details/gtmqabljrl.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.birdmap.top/Article/details/gtcmjczjpw.html

PHP:  array_merge(...$nested);
来源：http://dali.guannengcc.top/Article/details/gtbhbohwbq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.dashuyun.cn/Article/details/gthdwhszzh.html

TS:   nested.flat();
来源：http://dali.yongpay.top/Article/details/gtizgrnjse.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gogol.net.cn/Article/details/gtvnpecqtb.html

Go:   // 手写双层循环
来源：http://dali.xziqi.cn/Article/details/gtexsapojl.html

Ruby: nested.flatten
来源：http://dali.yonumen.top/Article/details/gtpjcpenfp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.smart0.xyz/Article/details/gttepmtcno.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtmdpsonef.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gtdgcqtgmu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hammf.cn/Article/details/gtpsnnlbgo.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.nanxuanxn.top/Article/details/gtfcwveiiy.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.nanxuanxn.top/Article/details/gtubfcigiv.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtndozrxnb.html

Go:   // 手写 map[string][]T
来源：http://dali.aibaodan.cn/Article/details/gttkgyxtnp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.cqqwz.cn/Article/details/gtdoihykmv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zdqjudy.top/Article/details/gtmptfedsq.html

[D20] 统计每个元素出现次数
来源：http://dali.sxryk.cn/Article/details/gtoebatjjv.html

Py:   Counter(arr)
来源：http://dali.mhx1999.top/Article/details/gtrnjsdrho.html

PHP:  array_count_values($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnozbgytq.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.daria6918.cn/Article/details/gtprqtptra.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhiwuduotai.top/Article/details/gtdennywwm.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daxiang520.top/Article/details/gtnscvlaqv.html

Go:   // 手写 map[T]int
来源：http://dali.jianghu66.top/Article/details/gtjrtixbkg.html

Ruby: arr.tally
来源：http://dali.hfpthk.cn/Article/details/gtpgpjigqn.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.zhaomingkeji.xyz/Article/details/gthulfzaxf.html

[D21] 判断是否包含某元素
来源：http://dali.hongshengwenyu.top/Article/details/gtnyzcsrsj.html

Py:   x in arr
来源：http://dali.yj20258888.top/Article/details/gtsainfqxd.html


<!-- 参考信息 -->