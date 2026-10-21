代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.0kj1m.cn/Article/details/gtuvdhmgux.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtieczfifw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuanzx.com/Article/details/gtguzoxquo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtlaafpypz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtzcjrztcw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtyjdnojyo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtyayimwlk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtxrmujibn.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtotziokrd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtgjbtzdye.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtxjbgwvhz.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gtknechjeu.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtarrtgojs.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtpqpxzxss.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.meibo888.top/Article/details/gtqaputwju.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtlngfonji.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gtmjzwzofp.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtcehjtudz.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtxdxxtfnu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtmobypcfa.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gtzxbfloea.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gtngmuitro.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtorospaon.html

JS:   const square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtqdupvscr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gtykgyvavd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtcwmuhzfz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gtijehcxyb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtbcvnhqzc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtvixjkizz.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtugohgzpg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhengqikj.top/Article/details/gtzztlwljq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtojlplzzt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgufenzy.top/Article/details/gtbhtmajlu.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtzxoefcln.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gttldnjuoe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtrmhotfqj.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtmqywgxbc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangshuangyany.cn/Article/details/gtgkyayzcl.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtggmfqxij.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtwygfogvi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gttbcwlbqv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtstgydneb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjvczvxxu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtghaoesmq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtkxifsqoa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ybcxt.top/Article/details/gtmoeaicna.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtihkmfytq.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtoyllduzk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtabmiqbgc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtlwzqdvpz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtrvajoqbh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtmhzqbgxa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtpntshbtb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhengqikj.top/Article/details/gtrvpcvnet.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtqwbjzrxc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.smart0.xyz/Article/details/gtavvhccrt.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gthctnhpdc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gtmtaieuei.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtiwbhouhw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ppjwa.cn/Article/details/gtfkcgthas.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtkxoiltda.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtkhfibqih.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtixocdwrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sxryk.cn/Article/details/gtnfldwdnx.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoaqowpmn.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtwaexxkos.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gthylzxhqq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfyhatdam.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtmgsxvycx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gtydgfvhfo.html

Java: import java.util.List;
来源：http://dali.xylfe.cn/Article/details/gtqayebuqr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtfadjterf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hongshengwenyu.top/Article/details/gtpjflzocp.html

C#:   using System.Text;
来源：http://dali.xuanzx.com/Article/details/gtsvmpzyhw.html

[C12] 立即执行函数 IIFE
来源：http://dali.cdnleiting.top/Article/details/gthjvwxtbq.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtpwleuijg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtnhrwjyoa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtsbyjtzlv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gthdltzmns.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtzywiqqwf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtftrnfqcn.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxuanxn.top/Article/details/gtdfhjidpp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jiagoushi.top/Article/details/gtrrcpqrlb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqdnmhwu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtjxhpxpch.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtpluugoew.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtxtydeebf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtgjfuvcca.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtvjsdktct.html

Go:   func add(a, b int) int
来源：http://dali.havefunace.top/Article/details/gtirhubuvg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtyuxkozrt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtrsnzyznk.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtpgewhzsj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtdjdibyhl.html

PHP:  // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtppjsyxni.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gttninivjo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtfypyltur.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtpjijixcc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtjgdtzssi.html

Ruby: # 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtcuraftcc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtcrcvjntj.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gtdkmznzti.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtamhmhppf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtwblgqjxg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwmljdqfz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtlybnrlsm.html

Java: // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtyrpcwhts.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gtmniojxre.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtvibpipfu.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtlmqkhlsq.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtqmdspzab.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtptuirskp.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gtpsplotnm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtoumnhlth.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gtilmojnev.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gttgamjhmy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gthedjnuwa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gttdnmiiwf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gttsycyysj.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtaqekscju.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtheczerjo.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtetfvzwjc.html

[D01] 创建数组 / 列表
来源：http://dali.chenjidiqi.icu/Article/details/gtaazntnoh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtufdjbvhd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gteozgoljp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsnncnhq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gtthftwhfc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gteyjqryxn.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtwdnuefru.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokloeebs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258.top/Article/details/gtvsrjsznt.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtyzvnqjhv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.dianchejie.cn/Article/details/gtjuhmzibk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jianghu66.top/Article/details/gtobvnozek.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtmrhealkh.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gthsxpajti.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtpvfmegso.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtitmzmjfc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtpznawtnj.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gtxhctyvvm.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gtvashnokf.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtomqtuykf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gtzkaenkxs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtxtuxiehf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtqlqafcpi.html

Java: list.add(0, 0);
来源：http://dali.meibo888.top/Article/details/gtolqqecpe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtciaucfpv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtpmcfvphc.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gtzcbywunk.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtwzaeaacz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtfsxcoiie.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtvctbqudh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtqzfemebv.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtomnhxmsc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gtbbalkjac.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hongshengwenyu.top/Article/details/gttotwoktt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtondomits.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gthgqfmimt.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtnjxmcgjt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gtcvefzfpd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtaaserojt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtdsbnkewh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtmqfsqjka.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxinkj.top/Article/details/gtavdqkqyc.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtixbpopmz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtzpobsrua.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtiuwlmkcf.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gteadrssjc.html

Py:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtoapmbumg.html

PHP:  count($arr);
来源：http://dali.yj202588.top/Article/details/gtilyddqyb.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtqdmrzskn.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtddhiskcs.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtuqnyrmlc.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gtdemcaedu.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtwxqzivkz.html

C#:   list.Count;
来源：http://dali.nwbrower.top/Article/details/gtrbteivpd.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gtdytvtmxz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gtpicumsms.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sweek.top/Article/details/gtqirqnxxl.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzyrzhwf.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtajrpcbjw.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtavivfpjo.html

Go:   arr[1:4]
来源：http://dali.zhiwuduotai.top/Article/details/gturdekbuu.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gtkyazrejj.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtfthmfgak.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gtccszuhme.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklqqlioi.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gtertkprii.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtxyisrogk.html

TS:   [...a, ...b];
来源：http://dali.redwolf501.top/Article/details/gtwxknodbo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.0kj1m.cn/Article/details/gtbhjzbrje.html

Go:   append(a, b...)
来源：http://dali.haohaochexian.top/Article/details/gtsmaicknj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbtncgzw.html

C#:   a.Concat(b).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtgpwrguzs.html

[D09] 排序（升序）
来源：http://dali.shuidangran.top/Article/details/gtejaxzvel.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cdnleiting.top/Article/details/gtdrfvquml.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtcphvyvot.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtjpjvdkcn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtxfdostfh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangdashe.top/Article/details/gtfktpaqjt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.aizwys.cn/Article/details/gtebnftgur.html

Ruby: arr.sort
来源：http://dali.redwolf501.top/Article/details/gtxkxfjfum.html

C#:   list.Sort();
来源：http://dali.tian-w.cn/Article/details/gtphpdncvu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtausemvki.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtrdzpqqbc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gtxihhjsjj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfsaezqt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuetiantiany.cn/Article/details/gtuztfpeza.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yonumen.top/Article/details/gtpijytzoy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ybcxt.top/Article/details/gttljvjjyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gthzhtyflo.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtbbvdayjv.html

[D11] 反转数组
来源：http://dali.redwolf501.top/Article/details/gtphuyqahg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenzaomai.com/Article/details/gtsydxqdsg.html

PHP:  array_reverse($arr);
来源：http://dali.ppjwa.cn/Article/details/gtfbmzfbfl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtelbrssco.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtfukgxhgx.html

Java: Collections.reverse(list);
来源：http://dali.zdqjudy.top/Article/details/gtvngzhmio.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gtqsknvgit.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluoardby.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwpgjvge.html

[D12] 查找元素下标
来源：http://dali.xinyue.icu/Article/details/gtaicfdycc.html

Py:   arr.index(x);  x in arr
来源：http://dali.sxryk.cn/Article/details/gtasccdgtj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ehwqpu.com/Article/details/gtzptlysja.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtalfjjmik.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj20258.top/Article/details/gttebagbso.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtruoynspp.html

Go:   slices.Index(arr, x)
来源：http://dali.sweek.top/Article/details/gtdfgcpzcx.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gthyssjtwr.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gtckvnxtnk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gtzkuqlqzs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gtcioahlgt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yvedp.cn/Article/details/gttvaoonix.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtvuxxdorh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gtechwlvzo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sxryk.cn/Article/details/gtikudyoxx.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.dianchejie.cn/Article/details/gtcvaccyyp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtiqnpsexy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.smart0.xyz/Article/details/gtxlzkgyjx.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gtktrhumre.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuhrgtztl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cqqwz.cn/Article/details/gtvnibmupn.html

JS:   arr.map(x => x * 2)
来源：http://dali.shuidangran.top/Article/details/gtmkshxpki.html

TS:   arr.map(x => x * 2)
来源：http://dali.quarkkingdee.top/Article/details/gtmnvjjpin.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgfzy.top/Article/details/gtvfyfjqgg.html

Go:   // 手写循环
来源：http://dali.jiagoushi.top/Article/details/gtcvbfufaa.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqewqpxli.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gzhubu.top/Article/details/gtcyrqxvrw.html

[D15] 去重
来源：http://dali.0kj1m.cn/Article/details/gtroiupnxq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtkdatdmlo.html

PHP:  array_unique($arr);
来源：http://dali.yuanzhike.top/Article/details/gthprbbels.html

JS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gtzxkdcack.html

TS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtxdgkkghf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.andypj.xyz/Article/details/gtxlnvzerg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ybcxt.top/Article/details/gttwqmpugu.html

Ruby: arr.uniq
来源：http://dali.havefunace.top/Article/details/gtxephotxk.html

C#:   list.Distinct().ToList()
来源：http://dali.sweek.top/Article/details/gtdvqqjcaa.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gtpgchwuly.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtmgyxxttn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtbhjhyflf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtylmhldhw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtmkthycju.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yvedp.cn/Article/details/gthjxvwsrk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gtsljmhsac.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yj202588.top/Article/details/gtdxyvqire.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtbdrlawzp.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtrhjiarvi.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtwotxffzp.html

PHP:  max($arr);  min($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgxtiotvg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.havefunace.top/Article/details/gtgttjjyky.html

TS:   Math.max(...arr);
来源：http://dali.jqgufenzy.top/Article/details/gtricwrcsg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtphyjinyx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.smart0.xyz/Article/details/gtveybalbt.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtycneoiri.html

C#:   list.Max();  list.Min()
来源：http://dali.yj202588.top/Article/details/gtdelmjgwg.html

[D18] 扁平化嵌套数组
来源：http://dali.shzxlz.cn/Article/details/gtqwhsmmlj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.shangyingyoupin.top/Article/details/gtdxjirrci.html

PHP:  array_merge(...$nested);
来源：http://dali.gaohongyu789.top/Article/details/gtehdkvzmw.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hammf.cn/Article/details/gtvveoneaz.html

TS:   nested.flat();
来源：http://dali.tian-w.cn/Article/details/gtqemcekxf.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.mhx1999.top/Article/details/gtzxbstqha.html

Go:   // 手写双层循环
来源：http://dali.wangshuangyany.cn/Article/details/gtzfbydrjb.html

Ruby: nested.flatten
来源：http://dali.jqgfzy.top/Article/details/gtfxdeilsb.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.bjfxy.top/Article/details/gtjckxxskq.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtoxtzhgtn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.gaohongyu789.top/Article/details/gturgmwlzw.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.zdqjudy.top/Article/details/gtuaidinsu.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.sxryk.cn/Article/details/gtebpmpjmn.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtxgpauvzj.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.sufxvd.cn/Article/details/gtrtbpcybs.html

Go:   // 手写 map[string][]T
来源：http://dali.yj202588.top/Article/details/gtoslhpvyw.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.andypj.xyz/Article/details/gtodeldhsn.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.gaohongyu789.top/Article/details/gtipkdlews.html

[D20] 统计每个元素出现次数
来源：http://dali.c1oappe.top/Article/details/gtkmpzwqty.html

Py:   Counter(arr)
来源：http://dali.shuidangran.top/Article/details/gtfpfyxqez.html

PHP:  array_count_values($arr);
来源：http://dali.nanxinkj.top/Article/details/gtyazpauew.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.havefunace.top/Article/details/gtklrdkdfc.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.tianlin.xyz/Article/details/gtyaljwnvi.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.hywenlv.cn/Article/details/gtvwghzkew.html

Go:   // 手写 map[T]int
来源：http://dali.hammf.cn/Article/details/gtgflzoxyq.html


<!-- 参考信息 -->