代发 wailian999

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtxwsmnrpy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtwydkuojx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.svipenyu.cn/Article/details/gtsurplbql.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtlhbcbrdl.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtnlxaukin.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtamfgqije.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtpbgffsej.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtdxnlccnw.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtrusjygsz.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gtnwezjvpo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtdcpuirtr.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtofvswhnu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtpcprbpvx.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtiwgvxqac.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtgttbahpk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtoombklgd.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gthgcayimq.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtzmuhdusx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jianghu66.top/Article/details/gtqyjunhtd.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtbjcvjnpg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtswesadyj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtfapniwec.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtjpfhvsbc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gtohmeyjek.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtoeylnemc.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtlitdrfet.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gthepspkyb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gteplnigwq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtczuuwjbr.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gtkcayqhca.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gturdulasc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtdrtghxdy.html

Ruby: arr.map(&:upcase)
来源：http://dali.yueranfly.top/Article/details/gtugxbmbtw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gtnurouifa.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gthrbzilaz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtlxyxapmi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gtooczgnqt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtzjqrmvdx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gttmhyorfn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtonzdeqkx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gttdnkbhia.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gtrdbgzpfy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtygwiayji.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtwxknvvxa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtoliiizyq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gteglwdwlw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtqxqvrifi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtalvgoktl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtqzqfmlks.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtxcmqmrcm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gthkibdwah.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtqybyllne.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtmomsjesg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtidrewplb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtebeluueb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtneoxyegc.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtyyxyxsyw.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtpfzljyxg.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtbklndcau.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gtxlzvpbzn.html

C#:   块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtmhhwlkmx.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtkmozusgo.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gtoctfyhpz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtqruptbmy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuetiantiany.cn/Article/details/gtkcyxibjs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtfahlusjr.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmglzxlam.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtkzububgj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtuecyouvl.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtwlwmcxdu.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtrlnpvfaf.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtzypseebu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtxojxosfl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtpsdtsgti.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gtdcraxufy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gthivvntii.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtsrointyj.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtadwoghmk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtupifkvrt.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258888.top/Article/details/gtbmdmhyig.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtusidjfiv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtevywizvk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtktvjsxed.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtqotoegdf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gthuoyuyyl.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtrlqvkcnb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtyntetubg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yvedp.cn/Article/details/gtdbvwucdt.html

[C14] 泛型函数
来源：http://dali.nanxuanxn.top/Article/details/gtgnhsedum.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtcfjlblfz.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtqpbmqrzo.html

JS:   // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtytqjhxkk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtjadpftxr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtviwrkepe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gtzejisljs.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtypulkqqh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtqgyvvxta.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtbgmwwtvo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtedizibfw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gtuksirctj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtwloufdvi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ydzc1.top/Article/details/gttsyzyske.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtscntezjg.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtxiceapan.html

Ruby: a, b = pair
来源：http://dali.zhiwuduotai.top/Article/details/gtgpvuzhlh.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtyqlxdfqm.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtzxriaqsk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtmykbwpgj.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtxqoqulwg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnxiangtu.top/Article/details/gttqwavzxg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtxbkhyyoi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtanfzjqko.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtxfdochkx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gtgxpxlkpv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtkazqvlac.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbmomdzrr.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtciclpjfw.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtqpihcktt.html

[D01] 创建数组 / 列表
来源：http://dali.nanxuanxn.top/Article/details/gtgwsxumpn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gttgumtfzi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.daxiang520.top/Article/details/gtexbrdieo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fzhhl.top/Article/details/gttymmoqvk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtnoblhjeb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtnjzqqhvl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtugunipee.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtwaslwmxq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.vqdsnc.cn/Article/details/gtwpasiwur.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtjpatkozx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtqxbpjpjk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.0kj1m.cn/Article/details/gtfakqnkwd.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtjoxemwdk.html

TS:   arr.push(4);
来源：http://dali.redwolf501.top/Article/details/gtarnmzdsy.html

Java: list.add(4);
来源：http://dali.sxryk.cn/Article/details/gtfkxuraqf.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtwgiivdmb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.9152youxi.cn/Article/details/gtwnkzsbxc.html

C#:   list.Add(4);
来源：http://dali.nanxinkj.top/Article/details/gttgvicxol.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gthkscrtia.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gtmdoouxge.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.smart0.xyz/Article/details/gtdrxvgunf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258888.top/Article/details/gtzrlrnnax.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gtygqikgap.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtryjkqcrb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.c1oappe.top/Article/details/gtmzhahqtl.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtvgqabviq.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtlkgzemui.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtgdtivusm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtbivlrnoo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtcepnhuwk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cashguo.top/Article/details/gtnqbldvft.html

TS:   arr.splice(0, 1);
来源：http://dali.yangfankeji.com/Article/details/gtmlrrflsr.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdaiobnub.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tianlin.xyz/Article/details/gtsvbydvad.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnvkjvrkt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gtntdzneqc.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtysrmpzuj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtjsnrxjgm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtyhlurctw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtcmhnhhbb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtbhvnmpad.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gtrdbzqcjz.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.smart0.xyz/Article/details/gtduuzjqfl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtbespbftn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtiyuxiqju.html

[D06] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtknukqtcn.html

Py:   len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtbjakugnl.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkmhsdggq.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtwsclcnjv.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtyorlzxnq.html

Java: list.size();
来源：http://dali.yongpay.top/Article/details/gtkesiqjik.html

Go:   len(arr)
来源：http://dali.gogol.net.cn/Article/details/gtnvqienow.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtlngvhzij.html

C#:   list.Count;
来源：http://dali.aibaodan.cn/Article/details/gtzzkpyjur.html

[D07] 切片 / 取子数组
来源：http://dali.jqgfzy.top/Article/details/gtjgktgvds.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtqrivghzg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtguuguzoq.html

JS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtqelmeufq.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnzsruiqd.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtnjjwxtvy.html

Go:   arr[1:4]
来源：http://dali.sxryk.cn/Article/details/gtnvlsavpe.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtrynalowt.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkxmcrgh.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgzxwikk.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gthqkwffvq.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdidcbqft.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtgakbajdx.html

TS:   [...a, ...b];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfhxqbam.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtvkvzuzbb.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gthlykozmx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ybcxt.top/Article/details/gtzyscpohi.html

C#:   a.Concat(b).ToList()
来源：http://dali.sxryk.cn/Article/details/gtinnyzttu.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtkfdlxtbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtvkkeosra.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gtxotftdox.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sweek.top/Article/details/gtqxwimxds.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.vqdsnc.cn/Article/details/gtnlmzyuou.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtoyaslzef.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.9152youxi.cn/Article/details/gtthrjdorj.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtnpfyftmr.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtjirmlytg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jqgufenzy.top/Article/details/gtvnwknecj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gtcraxskhf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gtwwnexmgi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtgmudvvsg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtdeittmgx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtykkxmwus.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.fengsongda.top/Article/details/gtszoigwbh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxqahysq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gtfwfaseez.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gtkatxdjlx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nwbrower.top/Article/details/gtmqsujpre.html

PHP:  array_reverse($arr);
来源：http://dali.ehwqpu.com/Article/details/gtycamhgdf.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gtpwimotcg.html

TS:   [...arr].reverse();
来源：http://dali.daxiang520.top/Article/details/gtarfhdzeu.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gtazayppcz.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkzoadaa.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtdvkburbl.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gtxltiqwyt.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtgwntanrq.html

Py:   arr.index(x);  x in arr
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjdylrvfs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gtojzddejc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtceqbkmxp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtoclzjdgy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tianlin.xyz/Article/details/gtbhsqzrus.html

Go:   slices.Index(arr, x)
来源：http://dali.snrcjt.cn/Article/details/gtjfkwvbgc.html

Ruby: arr.index(x)
来源：http://dali.c1oappe.top/Article/details/gtktjxcbop.html

C#:   list.IndexOf(x);
来源：http://dali.xuanzx.com/Article/details/gtugfekghg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tianlin.xyz/Article/details/gtkpjdnsrw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.quarkkingdee.top/Article/details/gtpgxmwjci.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yj202588.top/Article/details/gtswlwtdwz.html

JS:   arr.filter(x => x > 3)
来源：http://dali.ppjwa.cn/Article/details/gtxjgbvdgz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hammf.cn/Article/details/gtgqptyyba.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtubyzsfjh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yueranfly.top/Article/details/gtsjwtsobb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.dianchejie.cn/Article/details/gtowvgaylo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nwbrower.top/Article/details/gtomkvfmyl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gthsninfrc.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtyyvjaxkc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtclvtfjyv.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtnwofkten.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtsophtmhk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jianghu66.top/Article/details/gttijtjrcf.html

Go:   // 手写循环
来源：http://dali.fengsongda.top/Article/details/gtoqzrfyqy.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtclikmdqz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtkinxnrzh.html

[D15] 去重
来源：http://dali.yj202588.top/Article/details/gtpaeeufru.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtmsovifys.html

PHP:  array_unique($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecoclrla.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtrqiqjnei.html

TS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gtanfjtegx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zhijiandao.cn/Article/details/gtifpypbnu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgfzy.top/Article/details/gtapmyjrxg.html

Ruby: arr.uniq
来源：http://dali.xinyue.icu/Article/details/gthltlsgnj.html

C#:   list.Distinct().ToList()
来源：http://dali.svipenyu.cn/Article/details/gtsnnesxzm.html

[D16] 求和与平均值
来源：http://dali.c1oappe.top/Article/details/gtcrpsnudn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gthoeequuh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258888.top/Article/details/gtkmgkmuum.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxwrrdmeq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtnftgrphk.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhijiandao.cn/Article/details/gtauymrium.html

Go:   // 手写循环累加
来源：http://dali.yj20258888.top/Article/details/gtlzkmypft.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtljauqael.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangdashe.top/Article/details/gtsutqcxem.html

[D17] 最大值与最小值
来源：http://dali.9152youxi.cn/Article/details/gtretgsqkw.html

Py:   max(arr);  min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtgrzaxurj.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gturyfuyxc.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cdnleiting.top/Article/details/gtbqukzhuo.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtvrcqtvoi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fzhhl.top/Article/details/gtgxkiqobp.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gtzfygytcr.html

Ruby: arr.max;  arr.min
来源：http://dali.hywenlv.cn/Article/details/gtpfqaiidr.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuzvesdn.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gtddruedbu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.cashguo.top/Article/details/gtsnpvxvty.html

PHP:  array_merge(...$nested);
来源：http://dali.svipenyu.cn/Article/details/gtdehveect.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.chenzaomai.com/Article/details/gtsncjmivn.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gtykpequhh.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.bjfxy.top/Article/details/gtgojcxeyw.html

Go:   // 手写双层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtuepoxlnj.html

Ruby: nested.flatten
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyznwyfst.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gtcdmfywnl.html

[D19] 按字段分组
来源：http://dali.smart0.xyz/Article/details/gtlqtxqxta.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhijiandao.cn/Article/details/gtgrplcugp.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jiagoushi.top/Article/details/gtggqjydja.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.ivvv.top/Article/details/gtwbsfdvvh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtyalsivcw.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.chenzaomai.com/Article/details/gtaebvoenv.html

Go:   // 手写 map[string][]T
来源：http://dali.ppjwa.cn/Article/details/gtfxktevfs.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.meibo888.top/Article/details/gttanpdkaz.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.ehwqpu.com/Article/details/gtnsvqvuwb.html

[D20] 统计每个元素出现次数
来源：http://dali.pengpengdd.cyou/Article/details/gtunvdmhih.html

Py:   Counter(arr)
来源：http://dali.guannengcc.top/Article/details/gtxwrawtrl.html

PHP:  array_count_values($arr);
来源：http://dali.zhijiandao.cn/Article/details/gttkwawvmp.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhixingplan.top/Article/details/gtrtkgcwxp.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.jinqigufen.top/Article/details/gtnjsejtme.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlafibdru.html

Go:   // 手写 map[T]int
来源：http://dali.vqdsnc.cn/Article/details/gtscmblmoi.html

Ruby: arr.tally
来源：http://dali.fengsongda.top/Article/details/gtliflahwc.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.yj20258.top/Article/details/gtuzgqoggg.html

[D21] 判断是否包含某元素
来源：http://dali.zhixingplan.top/Article/details/gtidvqgvih.html

Py:   x in arr
来源：http://dali.havefunace.top/Article/details/gtpqtjbpuc.html


<!-- 参考信息 -->