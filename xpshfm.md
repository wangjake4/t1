代发 wailian999

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ehwqpu.com/Article/details/gtvynatmig.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtqiayyjod.html

Ruby: return a, b
来源：http://dali.0kj1m.cn/Article/details/gtxfjxcenr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtlyuhybic.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtapcbospz.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtoofkqcue.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gtumjmwryn.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtogpzarpu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gtesfvsqwk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtarwymvrh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtdchbgzja.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgfzy.top/Article/details/gtfktwyngy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtjzvzxdrn.html

[C07] 把函数作为参数传入
来源：http://dali.zhongyouzk.top/Article/details/gtyhqnbtxi.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtoceboilq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtlccavcwm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cucudq.cn/Article/details/gtgcxsjgij.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtxkbgmnxv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtvxhkdfke.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gtstnjmnik.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gthwnmqvwc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtkgomleyc.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtayrtfhte.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gttktucbsu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gthgaksjrk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gtqujzhjjq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtqhkiksue.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xylfe.cn/Article/details/gtuummfupk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gtutgxjhya.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpfthfmv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntzvgyzv.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtpblrmhbs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtrfqkbufd.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtousruhzs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtzbepdxyh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtdhoalgzp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsylpdpbj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtympuwfdm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtpxuajtwm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gteqwynkar.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtqwslhaif.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtbnlfhqnj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtmbrjvukd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtuugsyehu.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gtatclaqbf.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtymqicpef.html

Go:   花括号块级作用域
来源：http://dali.ehwqpu.com/Article/details/gtvtappulm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtpkbvlsdz.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gttszqjnvo.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gtrmjipolu.html

Py:   from module import func
来源：http://dali.hnxiangtu.top/Article/details/gtupkuviem.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yuanzhike.top/Article/details/gtsvuqjskd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtjkbpocmp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gttebgwwuz.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gtmzhjdhnf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtqmijplek.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtfihxjjqq.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtaogzipri.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhixingplan.top/Article/details/gtpofjjpvb.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtfdfpzqwg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtwommbnlt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtffdbzrzw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtjmrgbmkx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gtwlzhfykz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtzoeiernm.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gtzryrprvl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinqigufen.top/Article/details/gtwemvjdmc.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gtlzqgfvco.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gtecxdkuah.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtepwqqyhx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtgjogmvgo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtbtbhrqij.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtrptjmssv.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtvvbjgzyz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtgnkijjyo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.smart0.xyz/Article/details/gtfkealuqh.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtssksvvdm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtlpnekhcx.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtcnxxvtvn.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtpjoqqwdh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtntnwmuxa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtlwsqvnux.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtaqtqdsqf.html

Ruby: # 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gttayigrqd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtqdbnlheh.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtjalxmcsj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtgiptzzum.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhixingplan.top/Article/details/gtgobnvcfq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtuebhbxov.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrbppnpou.html

Java: // 无解构
来源：http://dali.zhongyouzk.top/Article/details/gtrumddnkp.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpnmkiur.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtlbcobvyn.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtsrcieeyf.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtvowllomt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gtbjwgiiat.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtnmdfzhmx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtrpnbchrl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtrscswxmw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jyoumei.cn/Article/details/gtgtdjdqvg.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtqyqczrjx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.havefunace.top/Article/details/gtylmkqmql.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtengzftiy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtjwobzjpl.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtxzigwihr.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdbkfkfnh.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtkvjbfuno.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtgxqoshbe.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtvhjebeaz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtarawnata.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gtknawqzho.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gttjavjrza.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtrxcobfoa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtqecihfdr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sufxvd.cn/Article/details/gtcmifccll.html

[D02] 追加元素到末尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpdhjmyjn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtaaixucew.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtynwllcuq.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtyfeunnet.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtohbmpvyu.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gtxlwylogm.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtrtagpdyv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtdldcxlna.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtyzxnrslh.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtwmwbwdpp.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtbaxcorkj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangdashe.top/Article/details/gtqqoecjex.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gtkmbeicfe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gthlomswdn.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtqsrujcmf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcorddyzh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtioirvfms.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtbwjvcbzm.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrczeyec.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtdcxhaaaj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xziqi.cn/Article/details/gtlblgfsfv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtbbotxgof.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtgwirazcx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gthwqufydq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtipndcwma.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyosdpmgg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtwhwvbfdh.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtxrgamhyq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtvzbsllhv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gtktvhscav.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtrkbytzck.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtwrowhrnf.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtjhlajmtd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtmtqzcdzf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtkknrfabg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtdphbopsi.html

[D06] 数组长度
来源：http://dali.tianlin.xyz/Article/details/gtcqcuiomz.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtgenybkau.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gtlvvjrqib.html

JS:   arr.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gterxrfxij.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gthgfirsal.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtrqjnjbyd.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtbtgbbkxt.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtvwgpfigk.html

C#:   list.Count;
来源：http://dali.daria6918.cn/Article/details/gtpjvbsxzz.html

[D07] 切片 / 取子数组
来源：http://dali.hammf.cn/Article/details/gtrojvwewi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gzhubu.top/Article/details/gtjdlaalua.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtuovcgvun.html

JS:   arr.slice(1, 4);
来源：http://dali.yuxming.cn/Article/details/gtcoxatxtb.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtwqxjxvgs.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtoeyraifp.html

Go:   arr[1:4]
来源：http://dali.yuanzhike.top/Article/details/gtcfdsndjm.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtgcjrnpsr.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtteexhthe.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtzvvukdpa.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtszmgqftb.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtgmeytkut.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtiqbnmxjp.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gtwljnwziu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gthegnxqgz.html

Go:   append(a, b...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlvsmmum.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtjiaymlqv.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhqsxesl.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptshjxmj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hywenlv.cn/Article/details/gtyqzrzgoe.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gtvfjwcnuw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gtplmbjxok.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtezkkqagd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtsygdylim.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtnlotkdsa.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gtossmuspe.html

C#:   list.Sort();
来源：http://dali.yuxming.cn/Article/details/gtlohppcfu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gteggrajap.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtbrhhxdvx.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtkvoegzjl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtcosdccca.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtanccefgv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gttkfcubqb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtkyciowfs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtxxawjahu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.iojbl.cn/Article/details/gtkfkjjpef.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtpmzhyaus.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yvedp.cn/Article/details/gttxzqaygd.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtpyaftlzq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xylfe.cn/Article/details/gtxanqocdn.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtirfsuhtb.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtrjvuaktx.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gttgzqnqwq.html

Ruby: arr.reverse
来源：http://dali.redwolf501.top/Article/details/gtcwbwadbp.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtbtfohywx.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtrveuockm.html

Py:   arr.index(x);  x in arr
来源：http://dali.nanxuanxn.top/Article/details/gttpjlsqgs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtphoejkgp.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtiaigytph.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ppjwa.cn/Article/details/gtzkqoovkr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sxryk.cn/Article/details/gtyfgbasyd.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gtxoogyedy.html

Ruby: arr.index(x)
来源：http://dali.jinqigfzy.top/Article/details/gtajnqmuin.html

C#:   list.IndexOf(x);
来源：http://dali.shzxlz.cn/Article/details/gtwuomrpqz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.9152youxi.cn/Article/details/gtctjemvcp.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.gogol.net.cn/Article/details/gtyslfezqp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jlsjyb.cn/Article/details/gtapnaptcn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.bjfxy.top/Article/details/gtwiffracj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtotdjpkls.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258888.top/Article/details/gtjzeputuw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtcvpnqbrw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sysykeji.top/Article/details/gtxjuzoqrl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.ivvv.top/Article/details/gtedoxqwng.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hysaishi.cn/Article/details/gtuipvqeuh.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gtxrwwnwhb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj202588.top/Article/details/gtoegugrkv.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxinkj.top/Article/details/gtpdicezuv.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtbwuajlnt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yongpay.top/Article/details/gtikjbougi.html

Go:   // 手写循环
来源：http://dali.wangshuangyany.cn/Article/details/gtwpcbhgxb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtoakvgwin.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ehwqpu.com/Article/details/gtkrgzxffr.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gtmboewxuj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtnbjkqgoy.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gthffeuacf.html

JS:   [...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gthhnwovik.html

TS:   [...new Set(arr)]
来源：http://dali.yj20258888.top/Article/details/gtyovzswqb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwebzyzw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtazkgcfbr.html

Ruby: arr.uniq
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuoeopaab.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtbuywtpfr.html

[D16] 求和与平均值
来源：http://dali.chenjidiqi.icu/Article/details/gtqalglyub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.316326.xyz/Article/details/gtoxfkmigw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvfnjwany.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.0kj1m.cn/Article/details/gtcpjpmrdk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gtrrvdplnb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaoogbni.html

Go:   // 手写循环累加
来源：http://dali.yonumen.top/Article/details/gtifemlrkm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtifbdqxhd.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhixingplan.top/Article/details/gtjlrhpitv.html

[D17] 最大值与最小值
来源：http://dali.gzhubu.top/Article/details/gtiqvyydef.html

Py:   max(arr);  min(arr)
来源：http://dali.jqgfzy.top/Article/details/gtkikgirct.html

PHP:  max($arr);  min($arr);
来源：http://dali.jiagoushi.top/Article/details/gtcitgmclx.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtyigxffvh.html

TS:   Math.max(...arr);
来源：http://dali.yj202588.top/Article/details/gtceomkidc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.ydzc1.top/Article/details/gtgyyzfpay.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtzwkaapzm.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxinkj.top/Article/details/gtvfvoitrt.html

C#:   list.Max();  list.Min()
来源：http://dali.mhx1999.top/Article/details/gtynsrecjw.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtujysdeuh.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xylfe.cn/Article/details/gtjmrcjbuc.html

PHP:  array_merge(...$nested);
来源：http://dali.bjfxy.top/Article/details/gtxtvbwrso.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.havefunace.top/Article/details/gtnourrecp.html

TS:   nested.flat();
来源：http://dali.xziqi.cn/Article/details/gtwcczvsth.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtewhxplll.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gtjdtojamb.html

Ruby: nested.flatten
来源：http://dali.cqqwz.cn/Article/details/gtfuuhdztw.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ybcxt.top/Article/details/gtimlvrwyr.html

[D19] 按字段分组
来源：http://dali.ivvv.top/Article/details/gtnfvqjlvo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.jinqigufen.top/Article/details/gtithbvumf.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinghuilouyu.cn/Article/details/gtkhqtfnrh.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.dashuyun.cn/Article/details/gtnteufnxd.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.fzhhl.top/Article/details/gtdtecdupx.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.redwolf501.top/Article/details/gthkbbuqyh.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtlqvnkuei.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.guowangkeji.top/Article/details/gtkgegvcyc.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.tianlin.xyz/Article/details/gtaotjghmb.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gturmpkarb.html

Py:   Counter(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmcritbvb.html

PHP:  array_count_values($arr);
来源：http://dali.yongpay.top/Article/details/gtfonwijvx.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hfpthk.cn/Article/details/gtttndzczo.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.aizwys.cn/Article/details/gtombbufqo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xinyue.icu/Article/details/gtquvzzmga.html

Go:   // 手写 map[T]int
来源：http://dali.ydzc1.top/Article/details/gtzfidriye.html

Ruby: arr.tally
来源：http://dali.svipenyu.cn/Article/details/gtxvtkvxry.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.xylfe.cn/Article/details/gtoooqgdqx.html

[D21] 判断是否包含某元素
来源：http://dali.feifeiyinyue.top/Article/details/gtogccplhl.html

Py:   x in arr
来源：http://dali.dashuyun.cn/Article/details/gtqmcbhdom.html

PHP:  in_array($x, $arr, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzgmngqu.html

JS:   arr.includes(x)
来源：http://dali.yueranfly.top/Article/details/gtfmupnqpj.html

TS:   arr.includes(x)
来源：http://dali.jiagoushi.top/Article/details/gtzblshmzt.html

Java: list.contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtwvbnvkjg.html

Go:   slices.Contains(arr, x)
来源：http://dali.fzhhl.top/Article/details/gtjtuvsrjp.html

Ruby: arr.include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtvepzfppf.html

C#:   list.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtsysmwyok.html

[D22] 复制数组（避免共享引用）
来源：http://dali.c1oappe.top/Article/details/gtdmjfrtde.html

Py:   arr.copy();  arr[:];  list(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtekgbkuni.html

PHP:  $copy = $arr;        // 数组是值类型，赋值即复制
来源：http://dali.316326.xyz/Article/details/gtgiuycozu.html

JS:   [...arr];  arr.slice();  structuredClone(arr)
来源：http://dali.yangfankeji.com/Article/details/gtrscekwbv.html

TS:   [...arr];
来源：http://dali.shuidangran.top/Article/details/gtrprfnbdy.html


<!-- 参考信息 -->