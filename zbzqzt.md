代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gthaxkaddh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtmjoccmgk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gteurqahje.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtvsuvtbap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.haohaochexian.top/Article/details/gterqfgdfl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtsjomytcm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtnureseak.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtcqbkclpu.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtyjwexuye.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtgygkmtdd.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtzsfnazen.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtmczijxny.html

Py:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtxvoeffiv.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtchstkdkr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtubluywnd.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtkbfuxvfy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gtidtqdlfa.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtomjnlwek.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtzpwwqvhz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtaauzgyzl.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtbfrmhkkq.html

Py:   square = lambda x: x * x
来源：http://dali.svipenyu.cn/Article/details/gtesxtochw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtpcqnxabp.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtgmktwfhb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtiowscfvk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtlwkrfxmn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtiskwjegr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gtwxwpwtha.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtvzqdptid.html

[C07] 把函数作为参数传入
来源：http://dali.hongshengwenyu.top/Article/details/gtulcwduan.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtihggneps.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtygcyyvaw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtekytrmsj.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtcqaviiwq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxixkwobq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtwjjgtysc.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258.top/Article/details/gtzzwpejrq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuanzhike.top/Article/details/gtmpolrwel.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtojtlnuyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtqlnvjydp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ybcxt.top/Article/details/gtpgdkqkll.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtowyskaxe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtpvdgorjq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gtoidgizmb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtuzlvqsuh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtpztjmsfu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gthwghnfwy.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gtfzbihnjx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdazuoqx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtipcvjwba.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtkoocatll.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtrxgcihwj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtsoxpzksm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gttxcpkcef.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtttbbvlay.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tanke756.top/Article/details/gtryhzwwzf.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gthpclfqbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtdeqjkzhi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtztmszgoc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hfpthk.cn/Article/details/gtkrwdfapk.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtjdbjgjdl.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtylmowors.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gthcaxbtsj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtzfyopdqf.html

C#:   块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtdfusuzte.html

[C11] 模块导入与导出
来源：http://dali.chenlongwang.top/Article/details/gtdezcyjpq.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtfqsyosbe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtictxessq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtewkrrsgz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtmaxdzysc.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtmrxuggvx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sufxvd.cn/Article/details/gtmazqxvxd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtelfavdnx.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtijwqpigd.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gtajkaojkl.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtlfblrxzv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258.top/Article/details/gtrtiyvslf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gtnkclvcsm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtykiadhba.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gthvvcmfnp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfxttvmc.html

Ruby: -> { puts "run" }.call
来源：http://dali.haohaochexian.top/Article/details/gtcjpknmca.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gtxormmjge.html

[C13] 类型声明 / 类型注解
来源：http://dali.ppjwa.cn/Article/details/gtjcjxdaim.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtjijhkzus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtmjdhktyb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtpujxdhuy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtswdbrnhm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtlzhwaamh.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gtricgqjyx.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.redwolf501.top/Article/details/gtbcjnmjwa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gtnswirdct.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtofgbecxx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gthfmcolit.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gtnvczmgkz.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtutymrdpd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtufhhwoln.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gtrwndofpn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sxryk.cn/Article/details/gtcmwblvfu.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtrwpfacrv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtfydshvbh.html

[C15] 解构 / 展开参数
来源：http://dali.shangyingyoupin.top/Article/details/gtroswwpqx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtftwxmkmp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gththwgdcr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtilhmcuxk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtwhouzxaa.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gttfkcgski.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzdkiyocc.html

Ruby: a, b = pair
来源：http://dali.guannengcc.top/Article/details/gtcgavbtct.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtnjalytlg.html

[C16] 函数 / 方法重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgjahoji.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtjbrkivja.html

PHP:  // 无重载
来源：http://dali.havefunace.top/Article/details/gtelszhfww.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jlsjyb.cn/Article/details/gtgqzehfaf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gteuakjiag.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gtxkszywmp.html

Go:   // 无重载：用不同函数名
来源：http://dali.smart0.xyz/Article/details/gtityiauqx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtljfegcua.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtughyeqzs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnphwsifb.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtsthjdhhp.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtqmvvtbwu.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtkjerbsmg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gtmyexmuak.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtrdeqmzot.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtfgotyviv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtspyqxdta.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtqghegwkd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cashguo.top/Article/details/gtlvmkvpjy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gogol.net.cn/Article/details/gttoclptjy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gttypoaexu.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtenidoyjo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtqquxckqy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daxiang520.top/Article/details/gtxxhzbbez.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtgrihffmy.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gtktyddyvt.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtpriccvjc.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtwnwtutsb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtdcmskftq.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtswfjorxi.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gtaddramkr.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbqpnnird.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtuptkmldn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtywfefwfm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gttgtbfgmu.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtgqnztyvg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtzhtdyliu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtdemvesjn.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdingcjdn.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtvvelptkr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gtwaaefnha.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtgxczddug.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigufen.top/Article/details/gttxnfsnby.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtozwbkldk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtffpdlemr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtsovswwiw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtatsdhjky.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hammf.cn/Article/details/gtempvechy.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtkcttssov.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtwtwowoic.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtgycvbvjc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gtvjrkuyjj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtttayoqwq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtpcjdojob.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtuvjknnyb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtkqjlaucu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtmuzcxjwd.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtxwrjdgsa.html

Py:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gtrscyqcfy.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnnthete.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtinfgnowt.html

TS:   arr.length
来源：http://dali.hnxiangtu.top/Article/details/gtutwdmstw.html

Java: list.size();
来源：http://dali.tianlin.xyz/Article/details/gtnqimtusa.html

Go:   len(arr)
来源：http://dali.xuanzx.com/Article/details/gtoqruvgro.html

Ruby: arr.length; arr.size
来源：http://dali.zhiwuduotai.top/Article/details/gtirmnceli.html

C#:   list.Count;
来源：http://dali.yonumen.top/Article/details/gtorgvdcga.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gturanrosm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.birdmap.top/Article/details/gtjclukfoi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daria6918.cn/Article/details/gtfjogdqsv.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtozuvewut.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtcslnnrvs.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtdroanmaw.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtnjxruptm.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtijdgjsdq.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gtulscrfpr.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtbbkeyaxj.html

Py:   a + b;  a.extend(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtsqaywvrj.html

PHP:  array_merge($a, $b);
来源：http://dali.bjfxy.top/Article/details/gtrisxthzu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtrnvtkofl.html

TS:   [...a, ...b];
来源：http://dali.zhongyouzk.top/Article/details/gtfpirjozh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjmzqlgf.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtwbchstkr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhengqikj.top/Article/details/gtkpiwrmyd.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtmqcyyezh.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtlznnenob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ydzc1.top/Article/details/gtuukeblzo.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdadbcsvs.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtfgjmacsm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtqswicoje.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtqfvwoscf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hammf.cn/Article/details/gtvjvvnbha.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gtmrgguadl.html

C#:   list.Sort();
来源：http://dali.zycfv.cn/Article/details/gthaknyjba.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gtqzpykzvb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtwwwtlnrd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258888.top/Article/details/gtondstumd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xylfe.cn/Article/details/gtromjnsue.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.quarkkingdee.top/Article/details/gtzjkvlyrm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.birdmap.top/Article/details/gtahmimylq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.tanke756.top/Article/details/gthlvveixu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gtyvzvnppp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zycfv.cn/Article/details/gtwrkjamaf.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtnyylzozw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsoaipvu.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gtkqfvysxn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtmzwdnxnt.html

TS:   [...arr].reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtphevuted.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gtmgmqrrxr.html

Go:   slices.Reverse(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkybemjuc.html

Ruby: arr.reverse
来源：http://dali.iojbl.cn/Article/details/gtzevtvdrv.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtiwjscqhz.html

[D12] 查找元素下标
来源：http://dali.svipenyu.cn/Article/details/gteqwnmnkn.html

Py:   arr.index(x);  x in arr
来源：http://dali.svipenyu.cn/Article/details/gtmpnsvunr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj202588.top/Article/details/gtumkvxbwh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtxsbxzqxj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtuaorqxke.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gaohongyu789.top/Article/details/gtoyozekgy.html

Go:   slices.Index(arr, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtgqrurbhe.html

Ruby: arr.index(x)
来源：http://dali.smart0.xyz/Article/details/gtzwmwovxv.html

C#:   list.IndexOf(x);
来源：http://dali.zdqjudy.top/Article/details/gtofajnqwi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.snrcjt.cn/Article/details/gteuxrtlig.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gtxgrufxzu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtceacjulc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gtovokvodi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtlnisyivd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zdqjudy.top/Article/details/gtmuugwzug.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gtiyngpxkf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtrjfuqfkd.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cashguo.top/Article/details/gtuglombpg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgfzy.top/Article/details/gtgjqjnfsa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtqfnaeeyh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtoodpxemd.html

JS:   arr.map(x => x * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtppqslrwt.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtnbhqjiui.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtbkfmpdvg.html

Go:   // 手写循环
来源：http://dali.shuidangran.top/Article/details/gtoryqefje.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gtbbfeitpd.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtuhgvsrpe.html

[D15] 去重
来源：http://dali.tianlin.xyz/Article/details/gtrsnffguc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtdurhgrtj.html

PHP:  array_unique($arr);
来源：http://dali.mhx1999.top/Article/details/gtpzehnsof.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gtpczrwuat.html

TS:   [...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtmuihtsyl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gtczagzhrh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtmtiogpdy.html

Ruby: arr.uniq
来源：http://dali.iojbl.cn/Article/details/gtowfubzga.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtnletbzst.html

[D16] 求和与平均值
来源：http://dali.yj20258.top/Article/details/gtrglnxphj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtjpfecddr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtfbcfdpok.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtojznptsc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gzhubu.top/Article/details/gtmklnygrj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ivvv.top/Article/details/gtoyqxpedj.html

Go:   // 手写循环累加
来源：http://dali.ppjwa.cn/Article/details/gtievccwzi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqvaadui.html

C#:   list.Sum();  list.Average()
来源：http://dali.guannengcc.top/Article/details/gtkrkxblqf.html

[D17] 最大值与最小值
来源：http://dali.shuidangran.top/Article/details/gtiloejwnb.html

Py:   max(arr);  min(arr)
来源：http://dali.haohaochexian.top/Article/details/gtymaolfeb.html

PHP:  max($arr);  min($arr);
来源：http://dali.316326.xyz/Article/details/gtmzryquuz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yonumen.top/Article/details/gtejsfeofk.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gtgawlgdcz.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.vqdsnc.cn/Article/details/gtvjfgwzgo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gtysqyptzs.html

Ruby: arr.max;  arr.min
来源：http://dali.yongpay.top/Article/details/gttlqkuscp.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtqqowehhx.html

[D18] 扁平化嵌套数组
来源：http://dali.aibaodan.cn/Article/details/gtybesfhmw.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.316326.xyz/Article/details/gtfdbbkgbq.html

PHP:  array_merge(...$nested);
来源：http://dali.gzhubu.top/Article/details/gtrwhicpew.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.vqdsnc.cn/Article/details/gtmantaxiv.html

TS:   nested.flat();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgcfbhdoz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtpdbhjcoe.html

Go:   // 手写双层循环
来源：http://dali.jyoumei.cn/Article/details/gtrlacujvt.html

Ruby: nested.flatten
来源：http://dali.yuxming.cn/Article/details/gtqsnimlvo.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.zhixingplan.top/Article/details/gtzzrorsel.html

[D19] 按字段分组
来源：http://dali.sysykeji.top/Article/details/gtafnzsvdh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gotoacloud.top/Article/details/gtoxypsswp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.feifeiyinyue.top/Article/details/gthhdnuggp.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.quarkkingdee.top/Article/details/gttaxehfun.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzazzuwe.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.cdnleiting.top/Article/details/gtjerriajd.html

Go:   // 手写 map[string][]T
来源：http://dali.snrcjt.cn/Article/details/gtnpkwqdvy.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.xinyue.icu/Article/details/gtwkekvrzp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.xziqi.cn/Article/details/gtozhghewm.html

[D20] 统计每个元素出现次数
来源：http://dali.svipenyu.cn/Article/details/gtumypqcsa.html

Py:   Counter(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtspnqslma.html

PHP:  array_count_values($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtytzfyhly.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.shangyingyoupin.top/Article/details/gtrylkbega.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.hammf.cn/Article/details/gtkfepvweo.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.daria6918.cn/Article/details/gttckmqjxm.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfbhhptnk.html


<!-- 参考信息 -->