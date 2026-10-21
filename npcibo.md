代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtrixmjroe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtaoxhexnc.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtzcfdoxke.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtppivtjhp.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtbtgshuqj.html

PHP:  return [$a, $b];
来源：http://dali.kuanghao11.cn/Article/details/gtqzaldqqy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtauwdyrbc.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtsngwzidn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtgksgswzy.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtjnhbnavs.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtcpmqcefm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtyipvcrkc.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtfrrewbel.html

Py:   square = lambda x: x * x
来源：http://dali.ppjwa.cn/Article/details/gtpretlcse.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtgdijwkoh.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtoybwtlwd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtdsfmjnqu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtdwiqcvhl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtriyzkhqi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gttjstxota.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtcyjjcewv.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gteuzbdjuk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqpfhlqot.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtchjrmjtx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gthhopzppe.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtmqkbwnbl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gtsgleuenw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gteafrocdl.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gtpcxryfnc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ydzc1.top/Article/details/gtibrowsvd.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtzjkarhae.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtzvoyipwt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuanzhike.top/Article/details/gtfjljkgzw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sufxvd.cn/Article/details/gtagzecggy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gthvsyfptz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtifylzsyl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtmyztvaim.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtpnraadge.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttujqmtok.html

[C09] 递归
来源：http://dali.nanxuanxn.top/Article/details/gtixsuqkji.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtiopeqimc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtcbrauneq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtdqimqpfx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gotoacloud.top/Article/details/gticaphhbi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtxocsxzvg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtcoqdvwal.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtnxjcokup.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gthgrmjfxa.html

[C10] 变量作用域
来源：http://dali.cqqwz.cn/Article/details/gtfqjigref.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtsqfmeohc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtrxssymrr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtzgmritbo.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtnopfwvdl.html

Java: 方法内为块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygoxwuaz.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gtmzpayrud.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtbisflsom.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtveqmjedu.html

[C11] 模块导入与导出
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxjwdfyv.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtvgapwgpn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtekshqtdx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjbxgfkpg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtgvhqtkoo.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtuirvfqpq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dianchejie.cn/Article/details/gtpoyjyrbt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtjvcdrdli.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpbugjfk.html

[C12] 立即执行函数 IIFE
来源：http://dali.pengpengdd.cyou/Article/details/gthamqiakf.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxuvgwkj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtrajdjpsz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtfghijywu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gtphxlwwfk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj202588.top/Article/details/gtpylctgok.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zdqjudy.top/Article/details/gtawvwdctf.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtdqtgjyag.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gtnwabsbhq.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gtjqaavzis.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gtwzdpdhjb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtoawscagn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.kuanghao11.cn/Article/details/gtlthsmakj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtgnuyqhzt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtmsembekt.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzskgkfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtazvoyiyq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtbrefvqta.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtncjmuzyc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtgymxlsgu.html

PHP:  // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtqzityzbr.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gthwcpqysu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gtcpnavoea.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtktkyunem.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtajtrrsfj.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gttdkcbwvp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtstetosal.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtyehwxoox.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ppjwa.cn/Article/details/gtgmkebiul.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtqezovuje.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtuxwvjffj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.snrcjt.cn/Article/details/gthuntcorr.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvtdhzly.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gtlnchnfxe.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gtcbqxoqnp.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfrukxfit.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gttysgqnwi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.fengsongda.top/Article/details/gtvietzhqt.html

PHP:  // 无重载
来源：http://dali.quarkkingdee.top/Article/details/gtbolocxbe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ppjwa.cn/Article/details/gtdtnqgdwp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtfjgchqpe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtydcwlphb.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gtwwdzqqfq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dianchejie.cn/Article/details/gtiumsituz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtifetrldm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpvbghwwp.html

D. 数组 / 列表 / 集合
来源：http://dali.hnxiangtu.top/Article/details/gtkcavygar.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtempbsmts.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gthtnwumsh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtqcsbtjod.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtgoymijzp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.andypj.xyz/Article/details/gtflfthyqd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tianlin.xyz/Article/details/gtdcgactbj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtyqxmibeq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xuetiantiany.cn/Article/details/gttxythpbs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtusbcaoag.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtvidlayam.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtfsmkuvtf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhiwuduotai.top/Article/details/gtoxabzgio.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtblklwvss.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gthpthwzuo.html

TS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtjvtncqxh.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gtuwlygkil.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtiztfouxw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtrjtczaqy.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtfpcjhsrw.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gtdsdkgcqt.html

Py:   arr.insert(0, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtpmliwjtr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkketvold.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.snrcjt.cn/Article/details/gtlpscbntc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gtakrdpuva.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gtabllhljt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gttkknmapr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gthqfixeow.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtroxkylxi.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtbffqnmvi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtyafazrpp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtvhtltefo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jqgufenzy.top/Article/details/gtypbtpzol.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcffdviwl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.birdmap.top/Article/details/gtkbqditvj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtenhhjifc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hongshengwenyu.top/Article/details/gtzzzirorn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cucudq.cn/Article/details/gtetwebrkm.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtyiydmjtt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtynntqdlz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtoyuczisj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhiwuduotai.top/Article/details/gtwszgoaky.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtebxjsdti.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtmjbgavyf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gtpcizrcth.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtgdzwtlku.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtvtkjycac.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtreoihbwr.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gttazuljjh.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtzqsgjmql.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtmtoqjmqd.html

TS:   arr.length
来源：http://dali.kuanghao11.cn/Article/details/gtywhayttf.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtlgeuthgy.html

Go:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtmghvgpgn.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gtjiljpjrm.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtgcvpefme.html

[D07] 切片 / 取子数组
来源：http://dali.smart0.xyz/Article/details/gtiqgdurmv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtvasihgzj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtudozkovo.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtnirogzqj.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtwonegmvc.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtowxchwhl.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtirpwgtiv.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gthgnrefwl.html

C#:   list.GetRange(1, 3);
来源：http://dali.tian-w.cn/Article/details/gtgghfeozz.html

[D08] 合并两个数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgxzoqwu.html

Py:   a + b;  a.extend(b)
来源：http://dali.iojbl.cn/Article/details/gtkwjqdnsc.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gttwspfmdi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.0kj1m.cn/Article/details/gtyjyyjmob.html

TS:   [...a, ...b];
来源：http://dali.jiagoushi.top/Article/details/gtmfpnuwgh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jyoumei.cn/Article/details/gtylnedhpz.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtoafgzbql.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gthdeueikw.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtgtbmhigy.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtfcdljvxu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gogol.net.cn/Article/details/gtogiquser.html

PHP:  sort($arr);
来源：http://dali.yonumen.top/Article/details/gtxaftwdpw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.havefunace.top/Article/details/gtlspnwnmb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sxryk.cn/Article/details/gtsoarzbwz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtzbctehzq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuanzhike.top/Article/details/gtfarrazbx.html

Ruby: arr.sort
来源：http://dali.jqgfzy.top/Article/details/gtvzmytlvz.html

C#:   list.Sort();
来源：http://dali.shangyingyoupin.top/Article/details/gtifosgawv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtvirswvme.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yueranfly.top/Article/details/gtqgiiwcot.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtcljuhfkg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtfhzcerss.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gtqdcprbpz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gtltlfukyy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtyztsfoed.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.sxryk.cn/Article/details/gtuatvtksy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtzkiljpfu.html

[D11] 反转数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnoozoqnq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtrfaqoqti.html

PHP:  array_reverse($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtywjoiowa.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuvuofnd.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gttzcpgqvv.html

Java: Collections.reverse(list);
来源：http://dali.jianghu66.top/Article/details/gtfzyrzbzw.html

Go:   slices.Reverse(arr)
来源：http://dali.hnqzz.top/Article/details/gtemupxwvk.html

Ruby: arr.reverse
来源：http://dali.cqqwz.cn/Article/details/gtjzxrjpcs.html

C#:   list.Reverse();
来源：http://dali.dashuyun.cn/Article/details/gtefywbnie.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtygnmjgzy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gtofvxkaur.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gteuiyetzr.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtlhnjcekk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gtrleokgqa.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtfkolcjag.html

Go:   slices.Index(arr, x)
来源：http://dali.chenzaomai.com/Article/details/gtczxvkykt.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gtzeynpmke.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtnazopwit.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sweek.top/Article/details/gtgvyzjzlb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtlfyszxte.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gtxmzbisyn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gogol.net.cn/Article/details/gtnmthosoi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtkivnrwtu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfrgpnvi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yangfankeji.com/Article/details/gtubsrwcpp.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.9152youxi.cn/Article/details/gtamtoxdoo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtvwmwkiop.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhengqikj.top/Article/details/gtfgkwejin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gtygtcyjyy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhengqikj.top/Article/details/gtudbdhsnh.html

JS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtuaqdqnfu.html

TS:   arr.map(x => x * 2)
来源：http://dali.wangdashe.top/Article/details/gtotqqgnio.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtormxasxi.html

Go:   // 手写循环
来源：http://dali.yvedp.cn/Article/details/gtpmgcmudf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtlgthjgqt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtfyitirfc.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gthrsunlvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtohcofmhz.html

PHP:  array_unique($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtuzbebyfg.html

JS:   [...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gtuufkcyrj.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtzwujvypx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.haohaochexian.top/Article/details/gtcnfyhbbu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hammf.cn/Article/details/gtphdqpjxl.html

Ruby: arr.uniq
来源：http://dali.yonumen.top/Article/details/gtnggwcooa.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtwqnufdgw.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gtxcwagxot.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlxyvrmmr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfeieryr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nanxinkj.top/Article/details/gtssctcgft.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jyoumei.cn/Article/details/gtgtdznrzp.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.pengpengdd.cyou/Article/details/gtknnemfhb.html

Go:   // 手写循环累加
来源：http://dali.wangdashe.top/Article/details/gtebpvlkxe.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.daria6918.cn/Article/details/gtfhkzxgci.html

C#:   list.Sum();  list.Average()
来源：http://dali.ydzc1.top/Article/details/gttniuzifl.html

[D17] 最大值与最小值
来源：http://dali.gogol.net.cn/Article/details/gtjcokhspw.html

Py:   max(arr);  min(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtlnzpxmya.html

PHP:  max($arr);  min($arr);
来源：http://dali.yongpay.top/Article/details/gtzcqcdzsi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.aizwys.cn/Article/details/gtxoidvxhh.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqxopcajg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.redwolf501.top/Article/details/gtqtmavvaa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.zhijiandao.cn/Article/details/gteyipcmqq.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gtxhjfkciu.html

C#:   list.Max();  list.Min()
来源：http://dali.gaohongyu789.top/Article/details/gtktyhzxlt.html

[D18] 扁平化嵌套数组
来源：http://dali.meibo888.top/Article/details/gtpxxdvxqr.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinghuilouyu.cn/Article/details/gtirrmnabq.html

PHP:  array_merge(...$nested);
来源：http://dali.smart0.xyz/Article/details/gthhhkgdnp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.meibo888.top/Article/details/gtmmcftdvk.html

TS:   nested.flat();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdotugpgz.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtyrxjbtlp.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtzxftqsla.html

Ruby: nested.flatten
来源：http://dali.zhongyouzk.top/Article/details/gtbxupskjs.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.gzhubu.top/Article/details/gtalouwjhd.html

[D19] 按字段分组
来源：http://dali.hywenlv.cn/Article/details/gttzbvojid.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtventoqof.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.yongpay.top/Article/details/gtqttnlfmk.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.gaohongyu789.top/Article/details/gtjninmhvr.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gthjgyenif.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.shzxlz.cn/Article/details/gtmnrwjjok.html

Go:   // 手写 map[string][]T
来源：http://dali.meibo888.top/Article/details/gtbrepxafv.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.aibaodan.cn/Article/details/gtrbbsctsl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.cdnleiting.top/Article/details/gtptsyucpu.html

[D20] 统计每个元素出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmxicbla.html

Py:   Counter(arr)
来源：http://dali.yonumen.top/Article/details/gtizqgpbsp.html

PHP:  array_count_values($arr);
来源：http://dali.zycfv.cn/Article/details/gtxyooqvoi.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtbmtpyjsr.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtzmnnwzsc.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.jinqigfzy.top/Article/details/gtqcyhumkd.html

Go:   // 手写 map[T]int
来源：http://dali.hongshengwenyu.top/Article/details/gtbzsfvizc.html

Ruby: arr.tally
来源：http://dali.nanxuanxn.top/Article/details/gtzhqrdycu.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.haohaochexian.top/Article/details/gteutmmbgu.html

[D21] 判断是否包含某元素
来源：http://dali.meibo888.top/Article/details/gtwgpktomd.html

Py:   x in arr
来源：http://dali.smart0.xyz/Article/details/gtknlnixnr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubsgcrhk.html

JS:   arr.includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtyotgknzk.html

TS:   arr.includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtavuhlfoq.html

Java: list.contains(x)
来源：http://dali.ydzc1.top/Article/details/gthfibtimc.html


<!-- 参考信息 -->