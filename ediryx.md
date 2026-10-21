代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gtcymjalrt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gtkptkeodr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtzamdkomq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtnaqpftta.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtumljrgzi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtmymcifcy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtnffvauky.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtrtbbuoon.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtmkzmcmhh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtxixkmxar.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtsbipomob.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gtlbutfpkz.html

Py:   return a, b
来源：http://dali.gzhubu.top/Article/details/gtwtroszyt.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gtzdrxkldm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtflbisgva.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtwxfhciyh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtwrlgxxvb.html

Go:   return a, b
来源：http://dali.ydzc1.top/Article/details/gtqqxikfds.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtylnjpfuo.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtqinhcflz.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtgwbbnbro.html

Py:   square = lambda x: x * x
来源：http://dali.jqgufenzy.top/Article/details/gtdoeaobwq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.fzhhl.top/Article/details/gtjvqctout.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gthrgwaolv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtirdsnirz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtdkntnlyd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtermyzcvu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gtoojllbso.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtnplzgihv.html

[C07] 把函数作为参数传入
来源：http://dali.cucudq.cn/Article/details/gtqpbbefbv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtojjzikng.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gtmlkflvoo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gthgcmiknw.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtoadfdiwb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtlsagkgaw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gthqryeetk.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtfrhnojxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigfzy.top/Article/details/gtlepljkqj.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtbzfwklze.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gtmwrgfeqy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtprtmerco.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtrigdsjfv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtezoghpgg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gtaobmiaen.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtdjqfskac.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtvpexiqit.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtpqtrucph.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtxebfpdrt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gtkuwkwynv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtltchfkro.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtnzguxxtt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtvtscvpta.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtdkyziewm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtelksarps.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtwacsbjqr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yanxiufei.cn/Article/details/gthghagjcy.html

[C10] 变量作用域
来源：http://dali.daxiang520.top/Article/details/gtvqzxxwtm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtihzcbwjf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtayllrpyc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtovohiifn.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtifokuyes.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gthyuhspyg.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gtfipspytz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gtwepgkfek.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gttwjcncds.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtyvthimeb.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtinjbjehd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnxiangtu.top/Article/details/gtbujivciv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gttvqlrony.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtarnfumta.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtowgpktlj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gtqigbhzdn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gtzeortgzt.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamegtbwm.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtkvsnjtoz.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gttwvlloqd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtxrdmgpgv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtvelxtnor.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtuixlfyqf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gtjuzixuro.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtukxhjdnb.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gthnkaczrk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hammf.cn/Article/details/gtnzgcrdim.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtyrimtkmz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtwszpkkuv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtrexcxtpu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.fengsongda.top/Article/details/gtsqxnmoix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtcyyyvxfn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtybhcvfci.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gthplvxrri.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtumbbmazi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtmzwhfwok.html

[C14] 泛型函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgubwfpfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtsixgrhox.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtbmjevvfb.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtggwyvqyx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gtuoitmhfp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtweeojfhc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gtpuooxxks.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtnxuszijl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtueomjedx.html

[C15] 解构 / 展开参数
来源：http://dali.hammf.cn/Article/details/gthgmwysua.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtnmrlyexu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gthswgritu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gthilzwtcc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijewobun.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtwlianlpz.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gthxgumanp.html

Ruby: a, b = pair
来源：http://dali.yonumen.top/Article/details/gtjxsqjngx.html

C#:   var (a, b) = pair;
来源：http://dali.fzhhl.top/Article/details/gttyjlagyj.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtiwhicxxj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gtbmpydulm.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtheukxjxu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gtsxxrnbas.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtmetxcqzg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.meibo888.top/Article/details/gtbozvzeet.html

Go:   // 无重载：用不同函数名
来源：http://dali.feifeiyinyue.top/Article/details/gtjjqvirao.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfwytovec.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtqmymovhg.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfpkzcsce.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gtymxipglt.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtytyilivt.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtlrgzpsnd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jlsjyb.cn/Article/details/gtlyawqsah.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gthdleexda.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtgbveoifw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtjbtkwusj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtmcnxuvzc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jiagoushi.top/Article/details/gtaxjnjbwt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtzoziapym.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cucudq.cn/Article/details/gtmmeenzaz.html

[D02] 追加元素到末尾
来源：http://dali.cdnleiting.top/Article/details/gthxdqezwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtnqaipkou.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.meibo888.top/Article/details/gtvypyxgkc.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtmsjvnhhx.html

TS:   arr.push(4);
来源：http://dali.tianlin.xyz/Article/details/gttcpdytnr.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtidqvdhjr.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtydjbpgot.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtniyahxvf.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtrchtqvzd.html

[D03] 在指定位置插入元素
来源：http://dali.yj202588.top/Article/details/gtlcmdklkb.html

Py:   arr.insert(0, 0)
来源：http://dali.xinyue.icu/Article/details/gtvsweuogf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gtbjzdytrs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtwwebbgjl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cashguo.top/Article/details/gtlrbhwajs.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtnheculan.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fzhhl.top/Article/details/gtqxehugyr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtwhoahdgw.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtleegpqpx.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtvcqzjwlx.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgufenzy.top/Article/details/gtvzxahoez.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sweek.top/Article/details/gtzmlzpewt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gtsgwttvit.html

TS:   arr.splice(0, 1);
来源：http://dali.jyoumei.cn/Article/details/gthoyhifvd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.fengsongda.top/Article/details/gtfldldgcs.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtqjqnjznb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.iojbl.cn/Article/details/gtydvtifvj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenlongwang.top/Article/details/gtdtcimztp.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtrkcbozaa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gttyjdtgor.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtgiuniprf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtsrznpbaf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gteszkdrrc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtdlkigdzn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcvnzdymq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtaodukbtz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtizwiegtl.html

[D06] 数组长度
来源：http://dali.sweek.top/Article/details/gtvrpaxnur.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtkgnwkqec.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtbryonbpf.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtayxuekxc.html

TS:   arr.length
来源：http://dali.ivvv.top/Article/details/gtfvgmfvrn.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gtacayvpkz.html

Go:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtyyjpoild.html

Ruby: arr.length; arr.size
来源：http://dali.quarkkingdee.top/Article/details/gtumvgakrf.html

C#:   list.Count;
来源：http://dali.jinghuilouyu.cn/Article/details/gtghuaxbct.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtguvcqlkw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gtfqbvrzxx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pycfn.com/Article/details/gtxzwwttfo.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtydfzchyw.html

TS:   arr.slice(1, 4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnafjtrll.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtwlmtjjah.html

Go:   arr[1:4]
来源：http://dali.sysykeji.top/Article/details/gttabckrsz.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtrcddnwxw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtaisrzadm.html

[D08] 合并两个数组
来源：http://dali.sweek.top/Article/details/gtweismpio.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtuakszara.html

PHP:  array_merge($a, $b);
来源：http://dali.shangyingyoupin.top/Article/details/gtyhhevujp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gtvekcjboc.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtqeqpounh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aibaodan.cn/Article/details/gtstkdxhsq.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gtrcwyovmu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tian-w.cn/Article/details/gtjxfoyknf.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtpcxwgvan.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtwayqngru.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fengsongda.top/Article/details/gtbixctdhe.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtkirfsscc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtrooivxgl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwmuxzjd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tanke756.top/Article/details/gtkydjypwp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tian-w.cn/Article/details/gtgtdzqvrr.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnzkqsncv.html

C#:   list.Sort();
来源：http://dali.shuidangran.top/Article/details/gtiflgnaep.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tian-w.cn/Article/details/gthrsefenz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtwsqjpnnd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtuuaujkzj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtmhjiuyla.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gtaeznrorg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtjalrqibe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ydzc1.top/Article/details/gthofwzgqa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.dashuyun.cn/Article/details/gtyekbeegc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gttdjgkham.html

[D11] 反转数组
来源：http://dali.yvedp.cn/Article/details/gtqwaessbd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xinyue.icu/Article/details/gtvlcibdsk.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtpbbyzmyb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtzywafitq.html

TS:   [...arr].reverse();
来源：http://dali.bjfxy.top/Article/details/gtxwplomlf.html

Java: Collections.reverse(list);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtfvhfxj.html

Go:   slices.Reverse(arr)
来源：http://dali.cdnleiting.top/Article/details/gtapbfuxsv.html

Ruby: arr.reverse
来源：http://dali.pengpengdd.cyou/Article/details/gtxjmugsra.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtdxxbsrjy.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtqibfdjeh.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtnouoakex.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jianghu66.top/Article/details/gttghaeili.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgknytym.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtwgkiptdn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtielozskh.html

Go:   slices.Index(arr, x)
来源：http://dali.pengpengdd.cyou/Article/details/gtikrjbaez.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gtxzmkafkg.html

C#:   list.IndexOf(x);
来源：http://dali.zhiwuduotai.top/Article/details/gtiygfsems.html

[D13] 过滤（保留满足条件的）
来源：http://dali.haohaochexian.top/Article/details/gtesokndcq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xylfe.cn/Article/details/gtaembcwaa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.c1oappe.top/Article/details/gtifvvnxdo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtxxcjkyby.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtntwehepp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtqhknecxi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gttcgmxphc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gtuwvzduql.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtgvmpovnx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jlsjyb.cn/Article/details/gthrvfykbz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtwmrdmsic.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtksvheflu.html

JS:   arr.map(x => x * 2)
来源：http://dali.yj20258888.top/Article/details/gtzjxxmczp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiilnpwxr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyhzskoqp.html

Go:   // 手写循环
来源：http://dali.cdnleiting.top/Article/details/gtakjrdhwc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtnwyrbjxp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gtzxiuubkm.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtzutykofl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gtdxazojrj.html

PHP:  array_unique($arr);
来源：http://dali.haohaochexian.top/Article/details/gtqiicjqpp.html

JS:   [...new Set(arr)]
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvaezloi.html

TS:   [...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtqzqxzsje.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtltrkfiiy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtxkcwrrjl.html

Ruby: arr.uniq
来源：http://dali.fzhhl.top/Article/details/gtfyuafrfx.html

C#:   list.Distinct().ToList()
来源：http://dali.pycfn.com/Article/details/gtevfrdjmd.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtyarxsuau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtgvjvwrau.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtswqgdhiw.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.feifeiyinyue.top/Article/details/gtwqgjdmki.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtwxjriwss.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gtwccdwbab.html

Go:   // 手写循环累加
来源：http://dali.haohaochexian.top/Article/details/gttbdmgzgq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtmnwhmgpp.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gtwzkrwsxy.html

[D17] 最大值与最小值
来源：http://dali.cheryme.top/Article/details/gtpkyikhya.html

Py:   max(arr);  min(arr)
来源：http://dali.hywenlv.cn/Article/details/gtwrrlepye.html

PHP:  max($arr);  min($arr);
来源：http://dali.ydzc1.top/Article/details/gtieyiinfb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gttozxpiwn.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gtgydqdptb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cqqwz.cn/Article/details/gtozxxcmji.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shuidangran.top/Article/details/gtnktyrtbf.html

Ruby: arr.max;  arr.min
来源：http://dali.jqgfzy.top/Article/details/gtbzermcsm.html

C#:   list.Max();  list.Min()
来源：http://dali.wangshuangyany.cn/Article/details/gtokxpzfmn.html

[D18] 扁平化嵌套数组
来源：http://dali.cucudq.cn/Article/details/gtptorpgmf.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.ywan-chungtsiang.top/Article/details/gthffptxpk.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdnyvxak.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztucbgyt.html

TS:   nested.flat();
来源：http://dali.zycfv.cn/Article/details/gtlatzcbgw.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrmkdmipg.html

Go:   // 手写双层循环
来源：http://dali.pengpengdd.cyou/Article/details/gtcgjwjbju.html

Ruby: nested.flatten
来源：http://dali.aibaodan.cn/Article/details/gtvpfysucb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gtubtmyxri.html

[D19] 按字段分组
来源：http://dali.vqdsnc.cn/Article/details/gtbgrcwtvl.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.cucudq.cn/Article/details/gtemqjsejr.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.dashuyun.cn/Article/details/gtysppmumg.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yueranfly.top/Article/details/gtsvcqrvfz.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.guowangkeji.top/Article/details/gtfoifqxgc.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jinqigufen.top/Article/details/gtdgmcvxsp.html

Go:   // 手写 map[string][]T
来源：http://dali.shzxlz.cn/Article/details/gtuuudbsrx.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.jqgufenzy.top/Article/details/gtbhnklzsv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hongshengwenyu.top/Article/details/gttrtwxven.html

[D20] 统计每个元素出现次数
来源：http://dali.sweek.top/Article/details/gtcxdkoupa.html

Py:   Counter(arr)
来源：http://dali.sweek.top/Article/details/gtgpcxztwf.html

PHP:  array_count_values($arr);
来源：http://dali.tian-w.cn/Article/details/gtokbcgorl.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yj202588.top/Article/details/gtazluydxr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.feifeiyinyue.top/Article/details/gtvmtmggic.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.ehwqpu.com/Article/details/gtmsmugfno.html

Go:   // 手写 map[T]int
来源：http://dali.yueranfly.top/Article/details/gtrvxzkitc.html


<!-- 参考信息 -->