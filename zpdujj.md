代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtytwoalzc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttqbnwluc.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtyjjgwprd.html

[C05] 返回多个值
来源：http://dali.cheryme.top/Article/details/gtpanrbqym.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gtpaeybdjq.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtvlmcrnkl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtsvlezgtb.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtscmpbdxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtdcegatxh.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtjheabwff.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiecptgbw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yuxming.cn/Article/details/gtabsffnuz.html

[C06] 匿名函数 / lambda
来源：http://dali.feifeiyinyue.top/Article/details/gttlvkilvb.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtddwpekht.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gteseukvae.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjcaucvt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gthqytakix.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dianchejie.cn/Article/details/gtfyimxurj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtddbjripx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtxkkxiqze.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtnudfmajt.html

[C07] 把函数作为参数传入
来源：http://dali.shangyingyoupin.top/Article/details/gterxkabbp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtbezfhrkh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sufxvd.cn/Article/details/gtbfceweis.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtnacpqziz.html

TS:   arr.map(String)
来源：http://dali.yvedp.cn/Article/details/gtvccuasll.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtfqpesszg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtmtsixhhb.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtqzjnivhd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.quarkkingdee.top/Article/details/gtugtctprc.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtlekgdsvs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gtyamutobi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gtlwbwdlwb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtitsfzprs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtrxqmtteg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtezjbqubu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.316326.xyz/Article/details/gtldcurohn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtjxzzvgmx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtayktbxrb.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtcawymgzu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtdppobsgy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtldshlbcy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtezdnzkli.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtedqlcnqi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gthpjnhqia.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtijypqizv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtiupwqqcf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gtuawmnhue.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtdcaxnpua.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ehwqpu.com/Article/details/gtubslnjyi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtetkwiwrw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gteigzyvfk.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtmuspkoie.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gtygyycpbo.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtinkenahj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsohtraoj.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gtsixqvivl.html

[C11] 模块导入与导出
来源：http://dali.tianlin.xyz/Article/details/gtshdtfugr.html

Py:   from module import func
来源：http://dali.mhx1999.top/Article/details/gtsguxojyd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtsjcgfjhj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gthjymevbh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtxtelzkrs.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkphplzpp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gtwyibqavq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtbhvgfaml.html

C#:   using System.Text;
来源：http://dali.redwolf501.top/Article/details/gtrzxgklre.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtlxtscyht.html

Py:   (lambda: print("run"))()
来源：http://dali.jlsjyb.cn/Article/details/gtpvnrsgok.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtsdvsybnw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtqhxomcop.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtjduefjgp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtmhfefdse.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtewypwmtg.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtxlrdclrx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtruouufxo.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gtvpvtyazb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtsghzidxr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtmxscevat.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtvqjcfcik.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyqbtxwvg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtuhrbqcqy.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxhfbytj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gttjmrjuij.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtdrtmkahq.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtdcmqgkot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdsphswzn.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtobjomvvy.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtlvkmrhca.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gthagqiqbe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtmnrnfmcg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtzthrsvkt.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtiqbufktn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtymkobitz.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtszpzwyrq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gtmhxvmtvb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gtvpgsefgz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwqfvfkf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aibaodan.cn/Article/details/gtguhqmhty.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gtfvbuthxw.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gtdgakbeiu.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtmnkmphbd.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtejtqnqvw.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gteavhkwxj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtwlnzlbof.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gttuhbfnfe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.haohaochexian.top/Article/details/gtowmwniqf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gtjsbzcbhe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtedpllbrh.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhixingplan.top/Article/details/gtdnrfymev.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtxknzullh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtthxjjilc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtspmyozso.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gtwuicobfg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpnnjgpzd.html

[D01] 创建数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtaykmfzrr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gtnbxvxavs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtohxxfhwd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtweqviomw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtoecclswv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigufen.top/Article/details/gtwwtfqnrx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtzqraxxnj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtwfryklqt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gtwjesuabk.html

[D02] 追加元素到末尾
来源：http://dali.jinqigufen.top/Article/details/gtcgrndqmd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtuyfqrjeq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtoybrpgni.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtphwtgyow.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtqmobgngv.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtirjtianc.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtvyetrzod.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gtegiblumx.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtndkvdvbc.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtpwiatbak.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtnwhyofdy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtkrvmnloo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hfpthk.cn/Article/details/gtqzhmxopj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtfxamalyc.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtcbtekuom.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtdfzvsxol.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtctkviqlc.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gttpsjielx.html

[D04] 删除元素
来源：http://dali.wangdashe.top/Article/details/gtpzdmhfmg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtcsyhaniz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtubqivrej.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gtleuzibjr.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gtrlsaaqhz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gtnwkzujjw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ehwqpu.com/Article/details/gtsledjetg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtyzrtkjng.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtxayuuife.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gtanqrmmhz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtnjdqbgtt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gtrlhsgusu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtalsewfvg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gttljqzynk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hnqzz.top/Article/details/gtgpzdxsmf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtfjgwnbjk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtcmagcnkx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtcejjldxr.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdfborje.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtaqhatrmj.html

PHP:  count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtidhgkyqh.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtgjnlldjg.html

TS:   arr.length
来源：http://dali.cqqwz.cn/Article/details/gtieorjhxf.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gtrpgvkins.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtmjknzoxl.html

Ruby: arr.length; arr.size
来源：http://dali.zhengqikj.top/Article/details/gtawzpumlu.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtdihwswqx.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtmskhgzna.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ehwqpu.com/Article/details/gtzsrwibrz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zdqjudy.top/Article/details/gttuhcjalf.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtgduabmyc.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigufen.top/Article/details/gthwgzxqei.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtchivqbxp.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtxpqtwsdg.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtrexyckky.html

C#:   list.GetRange(1, 3);
来源：http://dali.cqqwz.cn/Article/details/gticbeehwj.html

[D08] 合并两个数组
来源：http://dali.yangfankeji.com/Article/details/gtrtbyautw.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwthjhyr.html

PHP:  array_merge($a, $b);
来源：http://dali.jlsjyb.cn/Article/details/gtuqvrizyu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtkfljmykb.html

TS:   [...a, ...b];
来源：http://dali.jianghu66.top/Article/details/gtaubyegnl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cdnleiting.top/Article/details/gtuohfsspj.html

Go:   append(a, b...)
来源：http://dali.hammf.cn/Article/details/gtisbxquxn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yvedp.cn/Article/details/gtikkbhsyu.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtkiuyerou.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtiuspyfbk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pycfn.com/Article/details/gtqugezrqb.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylepdrhb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gtyettojvz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.gzhubu.top/Article/details/gtrsacufel.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gaohongyu789.top/Article/details/gttyxvnrap.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzghabqlf.html

Ruby: arr.sort
来源：http://dali.smart0.xyz/Article/details/gtxwicaowe.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gtkmmwqxji.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.aibaodan.cn/Article/details/gtvfpnxouo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.dianchejie.cn/Article/details/gtfdlhevau.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtwveitnli.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtykengdwb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtjnffeqkf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.fzhhl.top/Article/details/gtwaaoufqt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtdgjdgibs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhixingplan.top/Article/details/gtnufvruye.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhongyouzk.top/Article/details/gtwoztfmdg.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtlqwzrfpr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtxmpjvbmr.html

PHP:  array_reverse($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gttsmxtqev.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtlcydpxcm.html

TS:   [...arr].reverse();
来源：http://dali.yvedp.cn/Article/details/gtbutltmlp.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gtaowhyxcc.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtsnqmcknb.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtwhwbqard.html

C#:   list.Reverse();
来源：http://dali.guowangkeji.top/Article/details/gtrudoofsu.html

[D12] 查找元素下标
来源：http://dali.gotoacloud.top/Article/details/gtalrfxfzk.html

Py:   arr.index(x);  x in arr
来源：http://dali.bjfxy.top/Article/details/gtlvfebabb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgpeoxngg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtnqgjgajs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtmbgujwge.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.smart0.xyz/Article/details/gtykiuykqh.html

Go:   slices.Index(arr, x)
来源：http://dali.hnqzz.top/Article/details/gtuggeejdd.html

Ruby: arr.index(x)
来源：http://dali.jqgufenzy.top/Article/details/gtgpbldlhx.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gthffmolcf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.nwbrower.top/Article/details/gtknhlqvml.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ydzc1.top/Article/details/gtsedebnlo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gtfnwzucda.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtgturmrqj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtwlctwxxf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtprxyiwfu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.iojbl.cn/Article/details/gtdybgzxpg.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnkqmyqbn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtgzinshwz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenzaomai.com/Article/details/gtjnceldde.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtczsfjumo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gtvjiytctm.html

JS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gttihqpese.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmxaerzs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtwgwowqcy.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gtkilnfgwm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtjzdazsue.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtibvbxalw.html

[D15] 去重
来源：http://dali.smart0.xyz/Article/details/gtbentfzfx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtorjnjxbh.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtifiyepde.html

JS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtcuycskfa.html

TS:   [...new Set(arr)]
来源：http://dali.xylfe.cn/Article/details/gtdlefsnlg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gtjdvcmdnf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtnfouhhgm.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtyhxsltxi.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtrlftwxhe.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gtxauonefg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtsvrrvwrk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtxtvalawn.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtltfqcvxh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.316326.xyz/Article/details/gtltoytgcw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtyifntqdo.html

Go:   // 手写循环累加
来源：http://dali.cdnleiting.top/Article/details/gtgbdhzcvr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtkshuqsqc.html

C#:   list.Sum();  list.Average()
来源：http://dali.snrcjt.cn/Article/details/gtjvapetol.html

[D17] 最大值与最小值
来源：http://dali.redwolf501.top/Article/details/gtptlrdbzd.html

Py:   max(arr);  min(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtehwbcaoy.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gtaofneubl.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jqgfzy.top/Article/details/gtzopwuqyv.html

TS:   Math.max(...arr);
来源：http://dali.sufxvd.cn/Article/details/gthhekfudl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtqgvuzsou.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtnbrzvfuc.html

Ruby: arr.max;  arr.min
来源：http://dali.chenzaomai.com/Article/details/gtoxemjuva.html

C#:   list.Max();  list.Min()
来源：http://dali.shangyingyoupin.top/Article/details/gtlhfthxyn.html

[D18] 扁平化嵌套数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdouwizaj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.quarkkingdee.top/Article/details/gtxzpxxzcd.html

PHP:  array_merge(...$nested);
来源：http://dali.feifeiyinyue.top/Article/details/gtbjssmaox.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yanxiufei.cn/Article/details/gtmzozyxaa.html

TS:   nested.flat();
来源：http://dali.guannengcc.top/Article/details/gtfxnocwku.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gttechwbep.html

Go:   // 手写双层循环
来源：http://dali.smart0.xyz/Article/details/gttosjimtb.html

Ruby: nested.flatten
来源：http://dali.9152youxi.cn/Article/details/gtfhyodrkx.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtezahvpyx.html

[D19] 按字段分组
来源：http://dali.xuetiantiany.cn/Article/details/gtivfteokb.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.smart0.xyz/Article/details/gtxjitfvsw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jinqigfzy.top/Article/details/gtrliurxji.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gzhubu.top/Article/details/gtfkkynqsl.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoiyzyar.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.andypj.xyz/Article/details/gtrnswtdjg.html

Go:   // 手写 map[string][]T
来源：http://dali.yj20258.top/Article/details/gtxtlzrzep.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.fzhhl.top/Article/details/gtszauvytp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.birdmap.top/Article/details/gtysnubbal.html

[D20] 统计每个元素出现次数
来源：http://dali.pycfn.com/Article/details/gtctmmcgxw.html

Py:   Counter(arr)
来源：http://dali.yuanzhike.top/Article/details/gtnsvawfnc.html

PHP:  array_count_values($arr);
来源：http://dali.wangdashe.top/Article/details/gtexlffude.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.yongpay.top/Article/details/gtrnlrdhjb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jyoumei.cn/Article/details/gtllubohgp.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.shanyushiyangtech.top/Article/details/gtnymgmtjg.html

Go:   // 手写 map[T]int
来源：http://dali.svipenyu.cn/Article/details/gtlhgytqpc.html

Ruby: arr.tally
来源：http://dali.jyoumei.cn/Article/details/gtyqqdazbc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jiagoushi.top/Article/details/gtkjtcellm.html

[D21] 判断是否包含某元素
来源：http://dali.smart0.xyz/Article/details/gtqbiswwol.html

Py:   x in arr
来源：http://dali.jqgfzy.top/Article/details/gtzoabbcte.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shuidangran.top/Article/details/gtxivjgcls.html

JS:   arr.includes(x)
来源：http://dali.zdqjudy.top/Article/details/gthfwutsni.html

TS:   arr.includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtdyfqfbuw.html

Java: list.contains(x)
来源：http://dali.guowangkeji.top/Article/details/gtghimttpo.html


<!-- 参考信息 -->