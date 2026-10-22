代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtcnwjhhto.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtvdlxuelc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtwljbwdno.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtvvdxiggx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gtdjhcezrt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtihootahb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtvtoivyrb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtdahugwid.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtnegfxnxa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlqhnwmdi.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtvxwoquoq.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtkaglejlr.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtfbykcifq.html

PHP:  return [$a, $b];
来源：http://dali.daxiang520.top/Article/details/gtytxdtbav.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtdgopchyx.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtzuzypeor.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtmcbrtckd.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtqvwvtqwb.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gtzmlpaqxw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gtyygprpxp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtcofgqmvd.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtynlglybd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtdvslenas.html

JS:   const square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gtydptoafe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtlmyglmio.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.svipenyu.cn/Article/details/gtzmhkvokk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtbhhraelj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtrpgpztyq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtjiollmoj.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtnxzemgxg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtguiqfa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtmwksuaia.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtepnztphz.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlofxjasn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtikcjsgkt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnxiangtu.top/Article/details/gtwhonikpq.html

Ruby: arr.map(&:upcase)
来源：http://dali.daria6918.cn/Article/details/gtikvzgwiy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtvgobyowc.html

[C08] 闭包
来源：http://dali.sysykeji.top/Article/details/gtpadgktmf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtokftdhmx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cdnleiting.top/Article/details/gtvshdlypp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtsirmsptl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtuixrkonw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtatlxcdui.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yueranfly.top/Article/details/gtosppfbjo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtrhlacgey.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvgsiwzqq.html

[C09] 递归
来源：http://dali.hongshengwenyu.top/Article/details/gtdptszvnz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtamfbyxex.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtmanuquso.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtvefbpxml.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtrqbnvuuw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtppthcjbm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtxtfbmjqf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtsncztrsu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtjhcaodce.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gtjxelipbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtbhowukcl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daxiang520.top/Article/details/gtcfdmkrtg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtnkmpychw.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtppamrnyv.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtukfgjwze.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtsapkldoa.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yanxiufei.cn/Article/details/gthybtehly.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtgutflsgo.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxutugec.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtqdefumkf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hnqzz.top/Article/details/gthgvavnbu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjvnyucg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtljqhrwei.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gtzzqhikme.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gteivsivfu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gteumoxxrk.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtwkqwkzth.html

[C12] 立即执行函数 IIFE
来源：http://dali.jlsjyb.cn/Article/details/gtplnymjci.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gtxrkntlny.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtclvielae.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gtzcebhjjb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtcfaybjmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtvlucrgge.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gtiuierifm.html

Ruby: -> { puts "run" }.call
来源：http://dali.0kj1m.cn/Article/details/gtaacfazgi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtiwcmittx.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtchihhqfb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtatvpyzvu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvihxczb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtyrcgtldi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtulapjzfu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtffxnjkfg.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gttjqgnfpb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqnjwwizw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtuwisudwc.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gttipfuvnq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtgxxhgbes.html

PHP:  // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtghlezgxh.html

JS:   // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtywzvhqzh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gttekeaihs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ehwqpu.com/Article/details/gtdrqpqhbs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gthfzqhywb.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtaxdeoxdo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtxpxjrdgw.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtegiuuljt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtkazwymit.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtvymhkomy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtskguwmwe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gtutislmcy.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtagimondt.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtkevyyuoc.html

Ruby: a, b = pair
来源：http://dali.guowangkeji.top/Article/details/gtydjyzicc.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtbjmqbzet.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtcbgdnyge.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cdnleiting.top/Article/details/gtnupqfyob.html

PHP:  // 无重载
来源：http://dali.jlsjyb.cn/Article/details/gtbqlkdmgp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtrvxdyeet.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gotoacloud.top/Article/details/gtnjgcblgj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtkdpadype.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenzaomai.com/Article/details/gtbjnskien.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdioecbjr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.haohaochexian.top/Article/details/gtiwoezaak.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtougyjsww.html

D. 数组 / 列表 / 集合
来源：http://dali.cqqwz.cn/Article/details/gtveuprslv.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtdatemocm.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtbpjyfebj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtjkaryvpf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtzxqkrfsa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sxryk.cn/Article/details/gthanpljlz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtcscxnleb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtomcykisl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdklrbcbx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtjnlhllbl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xziqi.cn/Article/details/gtjkkjciik.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtolvccuhf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtzwtzjesw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.316326.xyz/Article/details/gtgkbcpmpj.html

JS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtuizcaxks.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtaebdqzbw.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gtytkqapgl.html

Go:   arr = append(arr, 4)
来源：http://dali.mhx1999.top/Article/details/gtpztuabcf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtlnpjbkkx.html

C#:   list.Add(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnlonqdq.html

[D03] 在指定位置插入元素
来源：http://dali.snrcjt.cn/Article/details/gtlburkeqj.html

Py:   arr.insert(0, 0)
来源：http://dali.shuidangran.top/Article/details/gthueghemg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gttawfogct.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtmoonozuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtyasctryi.html

Java: list.add(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtwatelqey.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtirxbclfy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtuzafkoza.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtyqeapqpl.html

[D04] 删除元素
来源：http://dali.zhengqikj.top/Article/details/gtawcpxuqy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gthbpkzbmq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuanzhike.top/Article/details/gtygypivjh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gtdbskbtaz.html

TS:   arr.splice(0, 1);
来源：http://dali.andypj.xyz/Article/details/gtiuahwfnl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gthtoryoqf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gtvpgudnan.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sxryk.cn/Article/details/gtfbdlzmwi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinqigfzy.top/Article/details/gtgtkdcjxn.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtgyhbjfgi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtrbearkvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtfyghxyht.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gthltcjpmr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yuxming.cn/Article/details/gtajxdrxfv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gtxwkiwsys.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtfweaaoit.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gthrjhkbba.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gtkdpdzmng.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtvzeiiyjm.html

Py:   len(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzqnnguy.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gtikshwbhs.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gtcmytnshk.html

TS:   arr.length
来源：http://dali.sysykeji.top/Article/details/gtqylfpwfx.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtodbojhmn.html

Go:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gthwdqkedw.html

Ruby: arr.length; arr.size
来源：http://dali.zhixingplan.top/Article/details/gtljrbmwfa.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtsvsfjmyr.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtsyedkymo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimiilrlq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwolstpdv.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtgtksrmmm.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtbkxzsrjw.html

Java: list.subList(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpjvmxvs.html

Go:   arr[1:4]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqorwmys.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtmuakzemv.html

C#:   list.GetRange(1, 3);
来源：http://dali.smart0.xyz/Article/details/gtfgwfcgwi.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtpzcwimdd.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtvhmoicyq.html

PHP:  array_merge($a, $b);
来源：http://dali.316326.xyz/Article/details/gtgmoiklxi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtwnhpymat.html

TS:   [...a, ...b];
来源：http://dali.jyoumei.cn/Article/details/gtckkfslsw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shzxlz.cn/Article/details/gthdwfffmx.html

Go:   append(a, b...)
来源：http://dali.dianchejie.cn/Article/details/gttilrkazn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hammf.cn/Article/details/gtrbfexpsg.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtmkrwbflc.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtknqhxtic.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtljzycugz.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtgnelkfeh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.c1oappe.top/Article/details/gttpddcvir.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gtjojdfisb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gtumrferow.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gttwhvkmwc.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtasqariia.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtxipxmefc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhiwuduotai.top/Article/details/gtfklldxiy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.nanxuanxn.top/Article/details/gtofsjwypi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtwgxihota.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtlcoavnfj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtngkkfrla.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.feifeiyinyue.top/Article/details/gtpajomidj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gtmxbneupi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.vqdsnc.cn/Article/details/gtghhuroyv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtbafxviev.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gtxxlssucr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gtvjpzvuad.html

PHP:  array_reverse($arr);
来源：http://dali.pycfn.com/Article/details/gtozabluej.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gtlzmytugm.html

TS:   [...arr].reverse();
来源：http://dali.yanxiufei.cn/Article/details/gtjhdlocht.html

Java: Collections.reverse(list);
来源：http://dali.chenjidiqi.icu/Article/details/gttzxyfjfu.html

Go:   slices.Reverse(arr)
来源：http://dali.jyoumei.cn/Article/details/gtnjzdzcoi.html

Ruby: arr.reverse
来源：http://dali.cdnleiting.top/Article/details/gtcwsytdhp.html

C#:   list.Reverse();
来源：http://dali.yvedp.cn/Article/details/gtzgxugxnb.html

[D12] 查找元素下标
来源：http://dali.wangdashe.top/Article/details/gtvnkfxenh.html

Py:   arr.index(x);  x in arr
来源：http://dali.yj20258888.top/Article/details/gttaudqcml.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.guannengcc.top/Article/details/gtipiqldoo.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cucudq.cn/Article/details/gthnokmnxb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtalqafbyf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtgmvhsxxj.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtxdkgtfai.html

Ruby: arr.index(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtnjsxbtco.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtixtvnlae.html

[D13] 过滤（保留满足条件的）
来源：http://dali.tanke756.top/Article/details/gtckpdcnii.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gtxfbcdigm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gtovdnzyxn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtqruajzcm.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yongpay.top/Article/details/gtbmigooji.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gtvikaetfr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnqzz.top/Article/details/gtptyubrsw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtztvxebai.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtzyrvamnd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jianghu66.top/Article/details/gtrhxobskv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangdashe.top/Article/details/gtwyeahnrp.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.guowangkeji.top/Article/details/gtfhugecib.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gtwxvzgtcg.html

TS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtylspajno.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xinyue.icu/Article/details/gtqwfazuxz.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtznietxeb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pycfn.com/Article/details/gtvbzrwfgz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuetiantiany.cn/Article/details/gtorzphgng.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gtjsksapbr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtrkqfibof.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gtblvhstbp.html

JS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtmktucrnu.html

TS:   [...new Set(arr)]
来源：http://dali.yuanzhike.top/Article/details/gtiljnxlja.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtxzqcricz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtrvqgidgj.html

Ruby: arr.uniq
来源：http://dali.chenzaomai.com/Article/details/gtmidwcuyx.html

C#:   list.Distinct().ToList()
来源：http://dali.316326.xyz/Article/details/gtdfdwpdqn.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbqeduau.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gtebludjim.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtebavaabp.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtdzqkkfhs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gtpwttvvvq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cucudq.cn/Article/details/gtmqzfpapr.html

Go:   // 手写循环累加
来源：http://dali.birdmap.top/Article/details/gtattmixfk.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.316326.xyz/Article/details/gtnmiibwvk.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhengqikj.top/Article/details/gtmqrhbooi.html

[D17] 最大值与最小值
来源：http://dali.zycfv.cn/Article/details/gtxsncrqql.html

Py:   max(arr);  min(arr)
来源：http://dali.gzhubu.top/Article/details/gtdelxbdbn.html

PHP:  max($arr);  min($arr);
来源：http://dali.c1oappe.top/Article/details/gtfbpvavcs.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pycfn.com/Article/details/gtgrevfebr.html

TS:   Math.max(...arr);
来源：http://dali.dashuyun.cn/Article/details/gtqipvbqol.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrngesuya.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigufen.top/Article/details/gtrajfqmpr.html

Ruby: arr.max;  arr.min
来源：http://dali.xziqi.cn/Article/details/gtastifxap.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtovhsavdl.html

[D18] 扁平化嵌套数组
来源：http://dali.jlsjyb.cn/Article/details/gtsvinjbze.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shuidangran.top/Article/details/gthzuhbbsn.html

PHP:  array_merge(...$nested);
来源：http://dali.shuidangran.top/Article/details/gtkpifxyrm.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.cashguo.top/Article/details/gtflhwdpcd.html

TS:   nested.flat();
来源：http://dali.haohaochexian.top/Article/details/gtzounyxmr.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.haohaochexian.top/Article/details/gtphmligzm.html

Go:   // 手写双层循环
来源：http://dali.dashuyun.cn/Article/details/gtgypgemft.html

Ruby: nested.flatten
来源：http://dali.hongshengwenyu.top/Article/details/gtbilxspsf.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.ivvv.top/Article/details/gtpwobzqov.html

[D19] 按字段分组
来源：http://dali.jqgufenzy.top/Article/details/gtujgxwgbf.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.fengsongda.top/Article/details/gtkqshpzej.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.nwbrower.top/Article/details/gtgsgdimyd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.pycfn.com/Article/details/gtbtqsofua.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtxysnlbxy.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhijiandao.cn/Article/details/gtzsfxgyol.html

Go:   // 手写 map[string][]T
来源：http://dali.ehwqpu.com/Article/details/gtxzqpacui.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.tianlin.xyz/Article/details/gtcfecqkzv.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.daria6918.cn/Article/details/gtacblnoqk.html

[D20] 统计每个元素出现次数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsilhgmkv.html

Py:   Counter(arr)
来源：http://dali.gzhubu.top/Article/details/gtcunsbiul.html

PHP:  array_count_values($arr);
来源：http://dali.c1oappe.top/Article/details/gtxdsdfitw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.kuanghao11.cn/Article/details/gtkklxgupb.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoxriyto.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.xuanzx.com/Article/details/gtsacxyepo.html

Go:   // 手写 map[T]int
来源：http://dali.zhengqikj.top/Article/details/gtmkdregux.html


<!-- 参考信息 -->