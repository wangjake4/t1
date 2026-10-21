代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtedohdkti.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtgkydoenx.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gteyosrzzy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtbczzzcwy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtubidnxvy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtelesqokf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtjvavacmg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtsqvzesjx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtidzgmzcn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtpukvkklb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.havefunace.top/Article/details/gthbpcxvff.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtkbsoodul.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtbhvrefwt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtljkkkodj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenjidiqi.icu/Article/details/gtdvkrubqv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtillthkro.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gtajnfcuid.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtmoliefbv.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxsmtqxn.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtoofbrirv.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtowstxeik.html

PHP:  return [$a, $b];
来源：http://dali.hysaishi.cn/Article/details/gtrapnxfsz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtfvxuhecs.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtyphcdxoa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfcqqyxl.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtjoldrhzy.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gthjgzaqaf.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aizwys.cn/Article/details/gtselpcyun.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtueqsjozf.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gtfslbrvnk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cheryme.top/Article/details/gtjhxygxgm.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtygmcsheg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtbisgwacx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtfwzkdwmr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtgrzrzsek.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gtsncbryfq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gotoacloud.top/Article/details/gtosevccfk.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtfbcyjnuu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hammf.cn/Article/details/gtmukgddkl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fengsongda.top/Article/details/gtlfymksdi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtvtlxdszw.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gtqwdfcjvi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gtsjgqrwdb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtrlmmjlfc.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtyhwohmna.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenzaomai.com/Article/details/gtwaqajrvn.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtmynzjnhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtjxdqwbnu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gtbijwbtmt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtggpiaoyg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtwnsnyytx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gtolbzinna.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtjclrsbjh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtuwxlyzbs.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtkhrntzzw.html

[C09] 递归
来源：http://dali.shanyushiyangtech.top/Article/details/gtcecmrxcm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gtuizkmoxn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtromhlauf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtqvsuaxxu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtrhjpgshw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtistvzvpt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gtnyaywhpa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsdichnzp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtprwurxem.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtpebixurx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtquryacsz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtxeifsrqv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtpnliifmm.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtvnuroduz.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtbhvhjnxo.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiqkvqxm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gtosseudhy.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gtxvaxyakf.html

[C11] 模块导入与导出
来源：http://dali.hongshengwenyu.top/Article/details/gttkuwrdsw.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtwyqnonla.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gticrykqpe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.tian-w.cn/Article/details/gtpvlbxhjd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shzxlz.cn/Article/details/gtdmyexktv.html

Java: import java.util.List;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcschnccw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtsxrqlrax.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pycfn.com/Article/details/gtleokeadm.html

C#:   using System.Text;
来源：http://dali.shangyingyoupin.top/Article/details/gthyrnfgzz.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenzaomai.com/Article/details/gtthvptwvl.html

Py:   (lambda: print("run"))()
来源：http://dali.bjfxy.top/Article/details/gtojtsaxan.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gttqvyzgpv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtkysswxgj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtiedsqawo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtovtndfuy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtcgjimhzf.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gtkhepldbk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtleyedctn.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtoibkihwf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258.top/Article/details/gtxprvmqbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtrmdrmuwl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtpyqppfgu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonfetrcf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtgagewbxj.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvvxkpzmo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtuoyfofxn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtovxjnwyq.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtswecryny.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hammf.cn/Article/details/gtlolrpvfy.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtlugxagxn.html

JS:   // 无泛型
来源：http://dali.cashguo.top/Article/details/gtraywewab.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtuezvrguy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gtsbhdewdj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gtvpsgseld.html

Ruby: # 无泛型
来源：http://dali.hammf.cn/Article/details/gtdmnefraq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yuanzhike.top/Article/details/gtrvklhepc.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtjcbgyywn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtndlqokze.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gtbuqmmluy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtqinsoiyy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gtwwwukxju.html

Java: // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtqubyvjpr.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtjxyesriu.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gtupzatjmq.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gthxymjrrf.html

[C16] 函数 / 方法重载
来源：http://dali.jiagoushi.top/Article/details/gtvylfeulv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtmuchodyd.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtrvlylmep.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gtmvbviibp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guannengcc.top/Article/details/gtrxlblxif.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtfkoxkkry.html

Go:   // 无重载：用不同函数名
来源：http://dali.birdmap.top/Article/details/gtfugdewai.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gtotgcflod.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtlkajehgm.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtrrpvfilv.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtlootuavc.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfhjarjnd.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtpxrwcdkk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yongpay.top/Article/details/gtotptvieu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtwxsirczb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtsgxigabt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fengsongda.top/Article/details/gtuspjnwjv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtqgtnyxgj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shangyingyoupin.top/Article/details/gtxeialnft.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtlyxdefay.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gtungcdjgq.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtztsrtbcb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shangyingyoupin.top/Article/details/gtypzkvfyj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gtqxqhvozg.html

JS:   arr.push(4);
来源：http://dali.tanke756.top/Article/details/gtzmmcxknp.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtaqtednjp.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gtkfbfvvdg.html

Go:   arr = append(arr, 4)
来源：http://dali.daria6918.cn/Article/details/gtxeamdrqh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtjfobkhvb.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtsbbvlypc.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtuvfhhixs.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtzycmbphk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtcqaykhyd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtmylpgbqj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtximdapif.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gtgbwgwqun.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtzktljpug.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtqdkjfklv.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtivaloyaz.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gtwjfksfqe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtykflazyu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtgdlpqdsv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gtlymtmzme.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtnhjyyfht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.smart0.xyz/Article/details/gtpqfcndyb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhiwuduotai.top/Article/details/gtqdsmxcmb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yonumen.top/Article/details/gtjvjpfwqm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.smart0.xyz/Article/details/gtwinfohnx.html

[D05] 访问与修改元素
来源：http://dali.ehwqpu.com/Article/details/gtkckwxcaz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtgzzlmwbm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtcmqzmyap.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtzjggiqgi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gttzwdcqxu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gteldfrnub.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gtpphhtwzs.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtrlfszjgc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtlaajozmv.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtvsismzqs.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrtprop.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtapwecstl.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gtycllnege.html

TS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtunzjmxif.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gtwiqlwuqk.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpqorluvs.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gtnqywhbyf.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtilijjtzd.html

[D07] 切片 / 取子数组
来源：http://dali.guannengcc.top/Article/details/gtbojlerxi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtuluqwwpk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sxryk.cn/Article/details/gtupwvatno.html

JS:   arr.slice(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtzzlpnqdo.html

TS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtrnxsbgmp.html

Java: list.subList(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtfzklwopj.html

Go:   arr[1:4]
来源：http://dali.jianghu66.top/Article/details/gtlcjkgigp.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtpadxaijm.html

C#:   list.GetRange(1, 3);
来源：http://dali.daria6918.cn/Article/details/gtwrmhydiq.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtnimhhfkb.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzvzjipm.html

PHP:  array_merge($a, $b);
来源：http://dali.xuetiantiany.cn/Article/details/gtbtpbbvjw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.tanke756.top/Article/details/gtdewbdjec.html

TS:   [...a, ...b];
来源：http://dali.yueranfly.top/Article/details/gtbiztbusm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.bjfxy.top/Article/details/gttoofxbdt.html

Go:   append(a, b...)
来源：http://dali.hysaishi.cn/Article/details/gtlbjlvgdz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtaesghfxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gthjrkpyey.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtwivoxjbi.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpplaakaw.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtoqfhbqpa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sxryk.cn/Article/details/gtjdgqzxvq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtpqohiaon.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.c1oappe.top/Article/details/gtsihyymnt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fzhhl.top/Article/details/gtdwqwclpy.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtgvyjvlep.html

C#:   list.Sort();
来源：http://dali.xuanzx.com/Article/details/gtoxsinvbf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtpkoxzgjh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvmzgifyo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtetvxkwiw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtueeoyqgs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gtyxchwplm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xylfe.cn/Article/details/gttcvjmtee.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gtvhvudscg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.0kj1m.cn/Article/details/gtnpvthfoi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guowangkeji.top/Article/details/gttiwbtnty.html

[D11] 反转数组
来源：http://dali.zhiwuduotai.top/Article/details/gtnegrncmx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhiwuduotai.top/Article/details/gtloskzwaq.html

PHP:  array_reverse($arr);
来源：http://dali.cucudq.cn/Article/details/gtedbdeued.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtdrckcvdu.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtddmcmvxd.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gtlevuuoes.html

Go:   slices.Reverse(arr)
来源：http://dali.yj202588.top/Article/details/gtvyfpenxm.html

Ruby: arr.reverse
来源：http://dali.jqgfzy.top/Article/details/gtoflywzoa.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtoahqkcwk.html

[D12] 查找元素下标
来源：http://dali.yanxiufei.cn/Article/details/gtnjvqeqcx.html

Py:   arr.index(x);  x in arr
来源：http://dali.iojbl.cn/Article/details/gtsnbqpcsg.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guowangkeji.top/Article/details/gticjrqsaz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtbtideycs.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtknvlifgx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cdnleiting.top/Article/details/gtzntshirv.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtvrhrzqld.html

Ruby: arr.index(x)
来源：http://dali.nwbrower.top/Article/details/gtppctynyl.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gtbuchyoql.html

[D13] 过滤（保留满足条件的）
来源：http://dali.svipenyu.cn/Article/details/gtbqwolymh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtpzvclefv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtomtcorat.html

JS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtyixomkrs.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gthebvweoi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cheryme.top/Article/details/gtraqzljjo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadztsuft.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtelcxqrxa.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gttyqnzajg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yvedp.cn/Article/details/gtfoasxdzj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhijiandao.cn/Article/details/gtamwmyeck.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtkuvhoqhk.html

JS:   arr.map(x => x * 2)
来源：http://dali.nwbrower.top/Article/details/gtdheznlhw.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gtlsyblcjl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yangfankeji.com/Article/details/gtsnekluts.html

Go:   // 手写循环
来源：http://dali.andypj.xyz/Article/details/gtawgkzxjx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.sysykeji.top/Article/details/gtxrdbjmub.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jianghu66.top/Article/details/gtyuedgsje.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtdjessekr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.chenlongwang.top/Article/details/gtkqvqbsku.html

PHP:  array_unique($arr);
来源：http://dali.gogol.net.cn/Article/details/gtrgmrqfhn.html

JS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtcjtppfil.html

TS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtcyiavknc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.0kj1m.cn/Article/details/gtfkxeorzn.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gtcljnkbsq.html

Ruby: arr.uniq
来源：http://dali.hysaishi.cn/Article/details/gtnszxnbop.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtosyzxwjh.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtonajvoje.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.smart0.xyz/Article/details/gthctxuzvt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvgqispl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtpvnzzimw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shangyingyoupin.top/Article/details/gtugglpxyy.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gtebenzzvd.html

Go:   // 手写循环累加
来源：http://dali.ybcxt.top/Article/details/gtjnnbrnpz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.dianchejie.cn/Article/details/gtzegcmmey.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtavnyulfc.html

[D17] 最大值与最小值
来源：http://dali.yonumen.top/Article/details/gtrlazowuy.html

Py:   max(arr);  min(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtivulgalm.html

PHP:  max($arr);  min($arr);
来源：http://dali.gogol.net.cn/Article/details/gtyuyihzow.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtibuxthcr.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtdkisevsu.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangdashe.top/Article/details/gttzqvuafv.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.dianchejie.cn/Article/details/gtmtfnxfwm.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtmjfkmnwm.html

C#:   list.Max();  list.Min()
来源：http://dali.hfpthk.cn/Article/details/gtrdqeqkzb.html

[D18] 扁平化嵌套数组
来源：http://dali.jianghu66.top/Article/details/gtgcknfrpb.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shzxlz.cn/Article/details/gtzulylomn.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtaqgujnwt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.iojbl.cn/Article/details/gttvsqyjfz.html

TS:   nested.flat();
来源：http://dali.dianchejie.cn/Article/details/gtoqyjsfke.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.yuxming.cn/Article/details/gtzrophtol.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylfijfon.html

Ruby: nested.flatten
来源：http://dali.ppjwa.cn/Article/details/gtbojcepoj.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtotflzdkp.html

[D19] 按字段分组
来源：http://dali.cqqwz.cn/Article/details/gtslwcisdy.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.9152youxi.cn/Article/details/gtautdkerk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.bjfxy.top/Article/details/gtmhatpnld.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.yanxiufei.cn/Article/details/gtwocpllrw.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gtsunwjlkh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.ppjwa.cn/Article/details/gtomxzxkwl.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtqmnvmwtu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtidwpkdde.html


<!-- 参考信息 -->