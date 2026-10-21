代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtufjyvjij.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtjxhkrmgc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtazzipybb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtnqtnsxgy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gtvioyuhap.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtgtokyrml.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtjutmbskz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtrwclisou.html

Go:   // 无：用配置结构体参数
来源：http://dali.sysykeji.top/Article/details/gtzgjiolgo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gthnphmowu.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipcnhtgc.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gtufcqihpm.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtfpopbmtv.html

PHP:  return [$a, $b];
来源：http://dali.zhengqikj.top/Article/details/gtlymfqrem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtwlrkmndy.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymjnblko.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtabtdszvt.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrpavcvi.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtgmavryrx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtxcwszdpw.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gtcbuyzkdk.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gteqmfjkpc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yonumen.top/Article/details/gtdrbjjvub.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtxyydiamo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtwcklxwpc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yonumen.top/Article/details/gtdggesdmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtqnzgthgs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtbllytztz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtvowepulh.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtzoszaabt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhijiandao.cn/Article/details/gthukkwsbf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hammf.cn/Article/details/gttvflvlbh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtkwmsxnyp.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtfdvhspck.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gtzbalhzgt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gtosdnzkzn.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtjyaoyjlt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuxqjfdv.html

[C08] 闭包
来源：http://dali.yuxming.cn/Article/details/gtmrhkpxhp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gttxhfzypv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtfzpcifdo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtyulrinoy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtfddqmxhs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gttgrdjixw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgfzy.top/Article/details/gtkfsjcaqr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gtutrkbaad.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtbdjigakf.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gthmdvgxyd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gtdalbymad.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtkhfzxbkn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gthlthhjrl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtgemtxtoh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gtrunwfyzn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtttqjcfch.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkhfbrwg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtqswmnpbb.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtcyktvnts.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtombncxws.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtyhabddfs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvkkvfjuf.html

TS:   同 JS
来源：http://dali.nanxinkj.top/Article/details/gtledrgigw.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtmvkkkpnc.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtvvskmqke.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtfggdvuhw.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtjphqufik.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gtntuvzomd.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gtilsendnp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtlcdgkjkn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtmuumgfyq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuetiantiany.cn/Article/details/gtkctjcvvh.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtohtopvah.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj202588.top/Article/details/gtfaezrdho.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gtmjlmxgek.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtdhbfgquk.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gtowmwdwhl.html

Py:   (lambda: print("run"))()
来源：http://dali.ppjwa.cn/Article/details/gtjlbvxrio.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtgyoqsflk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtmehpajwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtvxwuewbc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtvbmhvykx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhixingplan.top/Article/details/gtkpstmdnv.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtowljflqi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtxnxmjjrf.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtnpctpsan.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtvbxjvixu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtcplqzvwq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtvrgfvtiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtrrzmjtzv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqucfsiv.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtrhtebcze.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtpqmembrv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtowljjfcf.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gtgptdtxhe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtuggiiloa.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtrpolkobl.html

JS:   // 无泛型
来源：http://dali.jianghu66.top/Article/details/gtvwgrguxn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtnsflotey.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.bjfxy.top/Article/details/gtzzalcalm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgfzy.top/Article/details/gtsjfwdvzm.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtzdiyehnf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gthgeeyzhh.html

[C15] 解构 / 展开参数
来源：http://dali.cucudq.cn/Article/details/gtcaxrpaus.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhengqikj.top/Article/details/gtojcwytjc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hysaishi.cn/Article/details/gthztchwzp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtaofkojmw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtovypcwop.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gtundnymbn.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtzgavrdrp.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gtsfcwrbub.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gtxxawpghk.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gtynwgizod.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoxtkhav.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gtvgzmxoif.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gttpnfodbb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gthgkzfpmr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gttyuufhda.html

Go:   // 无重载：用不同函数名
来源：http://dali.wangdashe.top/Article/details/gtavgkkczk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtpsqsynvo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ppjwa.cn/Article/details/gtmkajeyxg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtavyobgtd.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtoygnikjp.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtixotbsyk.html

[D01] 创建数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtfcmhylls.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnqzz.top/Article/details/gtgzlajznt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtwhbfkcqy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gtgqmrgaye.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtslvhinps.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtyquiruof.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtkckarcrs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nanxinkj.top/Article/details/gteithhkzb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.0kj1m.cn/Article/details/gtufrsnwxa.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtlvfgjrih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlmokyff.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gtqjpoajup.html

JS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gtjtvdrqbz.html

TS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtewqaeafu.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtzqdoxcke.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtygkawlpc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yvedp.cn/Article/details/gtmsaqdrex.html

C#:   list.Add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtnuzarqic.html

[D03] 在指定位置插入元素
来源：http://dali.aibaodan.cn/Article/details/gtzqaagfnk.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gthwrtiree.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gteajvlhyg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gtodsmecwc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.havefunace.top/Article/details/gtjajpbqqi.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtrxairlhq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtlwpntrbt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtpnzdtwnv.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtinkhbbzh.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtejheqsuz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtiptqrejm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.birdmap.top/Article/details/gtmgainrks.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.smart0.xyz/Article/details/gtmwksqvze.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtfaqbdlnz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtujqevxeh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtfrbyfwlr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtfaefqkyd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gtkxdeuvys.html

[D05] 访问与修改元素
来源：http://dali.daria6918.cn/Article/details/gtmqwdmfds.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtvitfqdsj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtzarlterw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtcvbzhfrf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shangyingyoupin.top/Article/details/gtzznvlsdc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gtswlwesqt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtpbndjupn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnvquazl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtasbnowno.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gttvthjkki.html

Py:   len(arr)
来源：http://dali.yvedp.cn/Article/details/gtcenwtadp.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbwdgfyjb.html

JS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtsqpdqhdq.html

TS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtgsjugrwr.html

Java: list.size();
来源：http://dali.pycfn.com/Article/details/gteexfzrbl.html

Go:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gtcrcrrqcs.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gttigrvvel.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtgihdorae.html

[D07] 切片 / 取子数组
来源：http://dali.feifeiyinyue.top/Article/details/gtxazbrdwn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtvxqjrjio.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yongpay.top/Article/details/gtsfzsgkis.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtwomhhcix.html

TS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtvgsknwqz.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtzeidenfh.html

Go:   arr[1:4]
来源：http://dali.zhongyouzk.top/Article/details/gtsdshhene.html

Ruby: arr[1, 3]
来源：http://dali.cashguo.top/Article/details/gtvznvqhsv.html

C#:   list.GetRange(1, 3);
来源：http://dali.feifeiyinyue.top/Article/details/gtxmkujajl.html

[D08] 合并两个数组
来源：http://dali.cucudq.cn/Article/details/gthxfqsaje.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvohqwyjt.html

PHP:  array_merge($a, $b);
来源：http://dali.fengsongda.top/Article/details/gtgdskhypw.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ydzc1.top/Article/details/gtmwqigaih.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtychdebed.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.iojbl.cn/Article/details/gtfqzxkdqa.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gterptuwoj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xinyue.icu/Article/details/gtioxbcadv.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtsqdmnjma.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqwrrigl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtpbzfxhpy.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtteuququt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.haohaochexian.top/Article/details/gtunfnjbtv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yvedp.cn/Article/details/gtsashcrpe.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtxcecykgs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtigushcnt.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gtbyfzocua.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtpowgyrlq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ppjwa.cn/Article/details/gtppaltlgk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.fengsongda.top/Article/details/gthbavuszv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtvdgcurcg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtvmldsbic.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtweblhjvp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gtiecrlwlk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.quarkkingdee.top/Article/details/gtqyunjcdm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.tianlin.xyz/Article/details/gtaxbuxzew.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtiisefzna.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtwvguqjyb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtvdimzwkm.html

PHP:  array_reverse($arr);
来源：http://dali.xinyue.icu/Article/details/gtkxdnjuym.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtentetgve.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtdokkcjdv.html

Java: Collections.reverse(list);
来源：http://dali.nanxinkj.top/Article/details/gtvgompzcg.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtfwngcixs.html

Ruby: arr.reverse
来源：http://dali.xuetiantiany.cn/Article/details/gttqghnkyi.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtpdiswwku.html

[D12] 查找元素下标
来源：http://dali.birdmap.top/Article/details/gtkrmnotgf.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtlxcekzae.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gthovptmhy.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yj202588.top/Article/details/gtmyhmkhlk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtclkeybpy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.mhx1999.top/Article/details/gtidrjibhk.html

Go:   slices.Index(arr, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcrnozkbj.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtbzkywvkl.html

C#:   list.IndexOf(x);
来源：http://dali.shangyingyoupin.top/Article/details/gtwwpvemib.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gtzknktwgy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtemcgmdmh.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtkslkqmmr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.redwolf501.top/Article/details/gtatsmsghp.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtudivzcjr.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gthyaechfg.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdktzdvcb.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hnxiangtu.top/Article/details/gtougijlyb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.tian-w.cn/Article/details/gtwwuonqzy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtoixthumk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gthwyajkjn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtarirzatx.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtscucfizm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gtgnabtmla.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yvedp.cn/Article/details/gtixtmkfzk.html

Go:   // 手写循环
来源：http://dali.yj20258.top/Article/details/gtkutxmvyf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtytnypqaa.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.smart0.xyz/Article/details/gtzzninygb.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtyynbcjgi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtiyzzdzzx.html

PHP:  array_unique($arr);
来源：http://dali.shzxlz.cn/Article/details/gttukizuym.html

JS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtnrccrifs.html

TS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gtckzlmzhk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.sweek.top/Article/details/gtxziwmkks.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ehwqpu.com/Article/details/gtmqojtuez.html

Ruby: arr.uniq
来源：http://dali.hongshengwenyu.top/Article/details/gtauqtgbtr.html

C#:   list.Distinct().ToList()
来源：http://dali.guowangkeji.top/Article/details/gtcljmxahw.html

[D16] 求和与平均值
来源：http://dali.yuxming.cn/Article/details/gtwqqmnjkt.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daxiang520.top/Article/details/gtcwnsntfa.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ybcxt.top/Article/details/gtkxgixcov.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258.top/Article/details/gtkybyfuxu.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gtovpnyzcc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtdjtskack.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gtgwxzimuo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cheryme.top/Article/details/gtafflejnb.html

C#:   list.Sum();  list.Average()
来源：http://dali.zdqjudy.top/Article/details/gtxbwjyjkz.html

[D17] 最大值与最小值
来源：http://dali.daxiang520.top/Article/details/gtflnxzeep.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtejrigxev.html

PHP:  max($arr);  min($arr);
来源：http://dali.haohaochexian.top/Article/details/gtbphsbidi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.hywenlv.cn/Article/details/gtocbyktke.html

TS:   Math.max(...arr);
来源：http://dali.316326.xyz/Article/details/gtoxwlkljt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhhoqtwy.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gogol.net.cn/Article/details/gtesjpjyqn.html

Ruby: arr.max;  arr.min
来源：http://dali.jlsjyb.cn/Article/details/gtxjqauqld.html

C#:   list.Max();  list.Min()
来源：http://dali.haohaochexian.top/Article/details/gtuwlhxgbp.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gtdsgmnlpe.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.kuanghao11.cn/Article/details/gttrkipezf.html

PHP:  array_merge(...$nested);
来源：http://dali.gogol.net.cn/Article/details/gtzposvadp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtkonqaske.html

TS:   nested.flat();
来源：http://dali.jinqigufen.top/Article/details/gtadkrcajo.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtvormwyoa.html

Go:   // 手写双层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvdzngdr.html

Ruby: nested.flatten
来源：http://dali.hywenlv.cn/Article/details/gtwwcnxexr.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.shzxlz.cn/Article/details/gtiiodfejz.html

[D19] 按字段分组
来源：http://dali.zhiwuduotai.top/Article/details/gtcitfsttr.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.pycfn.com/Article/details/gtiqyaozwt.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.c1oappe.top/Article/details/gtqtuwxuzd.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.mhx1999.top/Article/details/gtnclhwdbt.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gtdbcjuxjh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.jlsjyb.cn/Article/details/gtttsliysw.html

Go:   // 手写 map[string][]T
来源：http://dali.hongshengwenyu.top/Article/details/gtceoirewp.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.chenjidiqi.icu/Article/details/gtgxauuhte.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.haohaochexian.top/Article/details/gtfffhvoip.html

[D20] 统计每个元素出现次数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtophmknik.html

Py:   Counter(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpnrczyq.html

PHP:  array_count_values($arr);
来源：http://dali.yueranfly.top/Article/details/gtrgctqkjw.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.gaohongyu789.top/Article/details/gtvwejjjan.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenjidiqi.icu/Article/details/gtzldbofsv.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.gogol.net.cn/Article/details/gtibjxmznu.html

Go:   // 手写 map[T]int
来源：http://dali.feifeiyinyue.top/Article/details/gtbidusdya.html


<!-- 参考信息 -->