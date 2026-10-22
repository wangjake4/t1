代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtmfrnnvvo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtepabpmfn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtkgwqprra.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gthtcbxpxk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtfckudboz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtvttubchi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gtpbxtxrct.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtqcfefbkh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gtwysafpsp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfzzlejxc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtvstrvhje.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtpuoetzrf.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gtrnrakgfx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtfospazzh.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtayswbpqk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gtyinkvkzp.html

Py:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtkwdnshzh.html

PHP:  return [$a, $b];
来源：http://dali.haohaochexian.top/Article/details/gthkdhishg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtjjaiczew.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtbywqjtny.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtnjxhctyu.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtscoxheep.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtayhvrboq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xinyue.icu/Article/details/gtprpsuceg.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtyvsiycce.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtqcpnjozo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtfsnsnhkb.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtbjgwszrh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtwcdpiwck.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtsstgsioh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtzwdekkjq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtwosrtvrw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtumyontnw.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gtbqcpkidj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.mhx1999.top/Article/details/gtdfenpimw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gtfaoqkstk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtjxifnxmn.html

TS:   arr.map(String)
来源：http://dali.ivvv.top/Article/details/gtufyldnff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtrzerqxgv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqlklvin.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpcbrouok.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.svipenyu.cn/Article/details/gtmflizpna.html

[C08] 闭包
来源：http://dali.ivvv.top/Article/details/gtxsmuwymu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtqforymea.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gtrhwvspnc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gttrxeybfo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtfxxuqudk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hammf.cn/Article/details/gtmeazmjex.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtqcwzgsck.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gtfehcpabv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtgokjqtlo.html

[C09] 递归
来源：http://dali.jqgufenzy.top/Article/details/gtofppyaxj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtrahqjxxa.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gtyquuwlxq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtlglwgfsr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtkogmxxah.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtgqiybacx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gaohongyu789.top/Article/details/gtuddafkin.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtvnhersem.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtgxfyuswn.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtijosaiqf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtmbclzdwk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtqosuaimj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gogol.net.cn/Article/details/gtodxgnnsh.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gticwvaejo.html

Java: 方法内为块级作用域
来源：http://dali.gzhubu.top/Article/details/gtpxjlpqvm.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtlxszfbfe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gtvitwbgno.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gtdkmghdca.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gtjltanirr.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtddlvckih.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtoabetusw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtdvvfcbae.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aizwys.cn/Article/details/gtkwiducdj.html

Java: import java.util.List;
来源：http://dali.sysykeji.top/Article/details/gtetsqjazq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtdnfaomgd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gttwsqwttx.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtmclrllnf.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtadggrdyu.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gtodpjwdig.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtaybxmybe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtwrtfvqwx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gthzwsscfs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtjnerqvgz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.haohaochexian.top/Article/details/gtdakkprff.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gtbknswcgm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhongyouzk.top/Article/details/gtbyfrfaay.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gtevssfbkw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtjpqqnrrx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtbkonbhpx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yvedp.cn/Article/details/gtydnxyrio.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtcjdvjbip.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtscooqzdh.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtzgfolgxs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtqvvnrtsg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtonolncdz.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gtyqgtidap.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtsqahmbdw.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtxilgylym.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwzcvubdr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gtpmogolqb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gtazagbqju.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gtgsxsgxzh.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgphtujr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gtityyedfo.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtbgrdujdm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtxjetcyld.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtzpcxqygf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtpixpkloq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangdashe.top/Article/details/gtyybavvxn.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmljvrht.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gtkoaatouj.html

Ruby: a, b = pair
来源：http://dali.jlsjyb.cn/Article/details/gtgjgjbpto.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtutdrbtub.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gtsxrukduz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gtewwbtnwt.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtmxtsqylt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gthdrxdqgw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtzbwwpvha.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtzhcovugt.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtjyjduadx.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gttjzkqtum.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtsfyopfea.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtfpccmggv.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtctxihpfb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtibfxdtoh.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtscbtlplc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtilwsbhfl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gtyjiasdge.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gtlvkouvmt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtctqyalvq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtcxrqiwtx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtxhxqmlcz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gtcwgwszyx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtrohcfqwp.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gtymgwdzve.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtylikxfhg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtzhgwvwtf.html

JS:   arr.push(4);
来源：http://dali.gzhubu.top/Article/details/gtmiwlrbjd.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtcvddvgen.html

Java: list.add(4);
来源：http://dali.mhx1999.top/Article/details/gtgiibyaqj.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtmoerbvwb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtrwbsmltp.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gtcmunowrl.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtvqyibemm.html

Py:   arr.insert(0, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtynlidzzh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtcpeipfcc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtokcstcox.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtxekgujeg.html

Java: list.add(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtdtljsfru.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtjmmglbmn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtyjvhntdm.html

C#:   list.Insert(0, 0);
来源：http://dali.yuxming.cn/Article/details/gtzboihsrm.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtykkezaos.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gtuwmdjrmw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtdszvgl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtgwajfltm.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtxidaigao.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gttmfrbqba.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gtxvjctfiy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gtsfsvinkp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtalroawyn.html

[D05] 访问与修改元素
来源：http://dali.jlsjyb.cn/Article/details/gtkcwcluge.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtkdjqqmvi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtnnonqlkk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtmqdtszmk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xylfe.cn/Article/details/gtdhklzmvo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtanqjfuwd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtspvssqoo.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guannengcc.top/Article/details/gtlxqutndu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jinqigfzy.top/Article/details/gttlssqfnc.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtrprvepsc.html

Py:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtkpsihkvr.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtvauqlulh.html

JS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gtfvfgvnqi.html

TS:   arr.length
来源：http://dali.shangyingyoupin.top/Article/details/gtsorkejyq.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtfrrsngtl.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtkffeqfyv.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtahnnkftp.html

C#:   list.Count;
来源：http://dali.xinyue.icu/Article/details/gtqxlqakgz.html

[D07] 切片 / 取子数组
来源：http://dali.chenlongwang.top/Article/details/gtzodyzeju.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtyowencev.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gtxlcbcbbx.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtagmdnaac.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhbnitkm.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtkrucdwjd.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtvdaxouzv.html

Ruby: arr[1, 3]
来源：http://dali.vqdsnc.cn/Article/details/gtingmdcyv.html

C#:   list.GetRange(1, 3);
来源：http://dali.0kj1m.cn/Article/details/gtamrmthkw.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gtkssfxptx.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtijbfcebd.html

PHP:  array_merge($a, $b);
来源：http://dali.jiagoushi.top/Article/details/gtwstayzst.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtqfopttym.html

TS:   [...a, ...b];
来源：http://dali.yonumen.top/Article/details/gtdimarpjy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtzxenerej.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gtgkyugknd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtezuzdpii.html

C#:   a.Concat(b).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbqbbagvr.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtkbekppfl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.smart0.xyz/Article/details/gtyauvuekj.html

PHP:  sort($arr);
来源：http://dali.ehwqpu.com/Article/details/gtuspusjqc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cqqwz.cn/Article/details/gthzycxryn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhongyouzk.top/Article/details/gtojkzxqqd.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gtwgbtogze.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtddmqcmca.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtqtbnsujm.html

C#:   list.Sort();
来源：http://dali.chenlongwang.top/Article/details/gtykstrwlt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gticrljrnq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtroyvpceh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtnppflbsy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtxkxjouig.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtvybujddd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daria6918.cn/Article/details/gtvschuwjf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gtowinjziu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gtwdenovau.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtkebktyjh.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gtekgqdgfc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cqqwz.cn/Article/details/gtlnunztmw.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gttnirzozx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtwfqoculk.html

TS:   [...arr].reverse();
来源：http://dali.cdnleiting.top/Article/details/gtcgkjwdsd.html

Java: Collections.reverse(list);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbgpqxys.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtooxknlmt.html

Ruby: arr.reverse
来源：http://dali.xylfe.cn/Article/details/gtbrwwkykf.html

C#:   list.Reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtiplywaei.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtgnnirzzd.html

Py:   arr.index(x);  x in arr
来源：http://dali.hnxiangtu.top/Article/details/gtvxvfzrsd.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.dianchejie.cn/Article/details/gtsjoncxfx.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cheryme.top/Article/details/gtsvpwwpeg.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtctfrmsrk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cqqwz.cn/Article/details/gtgcabpdwq.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gttoqncusn.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gthdlbzlnq.html

C#:   list.IndexOf(x);
来源：http://dali.guannengcc.top/Article/details/gtqoeqvkbn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ydzc1.top/Article/details/gtqdagecmw.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtoijypaku.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtrzbqkbxb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtcuxvtrke.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtoyoqeavl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xylfe.cn/Article/details/gtrxokohae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtpjbqdygy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zycfv.cn/Article/details/gtkkkypzjv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xuanzx.com/Article/details/gtqhleldts.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtamasklfw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gtjtzoobmu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvziaspy.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhixingplan.top/Article/details/gtfohsrbsl.html

TS:   arr.map(x => x * 2)
来源：http://dali.gogol.net.cn/Article/details/gtlvtlaibs.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtnupnhggh.html

Go:   // 手写循环
来源：http://dali.haohaochexian.top/Article/details/gtzaolxwzj.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtqntidtzh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.pycfn.com/Article/details/gtcujswhnq.html

[D15] 去重
来源：http://dali.nanxinkj.top/Article/details/gtazrjzryi.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtdmtlntzb.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtlwsdluhf.html

JS:   [...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gtnivbekdp.html

TS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtvyaqdjip.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gtyowvvwyu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jiagoushi.top/Article/details/gthyhfbkmf.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuxefsyza.html

C#:   list.Distinct().ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthbwxrtik.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtxfckujiq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtsbiadmlc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtbasezact.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj20258888.top/Article/details/gtwmkhhfhn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtvvfrwhxq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtojbitvtq.html

Go:   // 手写循环累加
来源：http://dali.jiagoushi.top/Article/details/gtzznzjezx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtoyehgooq.html

C#:   list.Sum();  list.Average()
来源：http://dali.wangshuangyany.cn/Article/details/gthyqorulb.html

[D17] 最大值与最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gtmldrrvpj.html

Py:   max(arr);  min(arr)
来源：http://dali.hfpthk.cn/Article/details/gtveootpqe.html

PHP:  max($arr);  min($arr);
来源：http://dali.sweek.top/Article/details/gtsyumutsg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.cqqwz.cn/Article/details/gtavepppuq.html

TS:   Math.max(...arr);
来源：http://dali.hywenlv.cn/Article/details/gtpegesmis.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.dianchejie.cn/Article/details/gtpnqetnkq.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuusaagt.html

Ruby: arr.max;  arr.min
来源：http://dali.yj20258.top/Article/details/gttjrdxncl.html

C#:   list.Max();  list.Min()
来源：http://dali.smart0.xyz/Article/details/gtisjlmhmv.html

[D18] 扁平化嵌套数组
来源：http://dali.zhongyouzk.top/Article/details/gtfztzijir.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.xuetiantiany.cn/Article/details/gtkhzfybll.html

PHP:  array_merge(...$nested);
来源：http://dali.aizwys.cn/Article/details/gttnpqimin.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shangyingyoupin.top/Article/details/gtjhchfffy.html

TS:   nested.flat();
来源：http://dali.zhongyouzk.top/Article/details/gtvudnjbqj.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.dashuyun.cn/Article/details/gtujtegihb.html

Go:   // 手写双层循环
来源：http://dali.birdmap.top/Article/details/gtyeadahkd.html

Ruby: nested.flatten
来源：http://dali.zhoulong.xyz/Article/details/gtnxknduup.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtrrondyvg.html

[D19] 按字段分组
来源：http://dali.tianlin.xyz/Article/details/gtgcyzzldh.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.nwbrower.top/Article/details/gtbnuvylsk.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.havefunace.top/Article/details/gtlnfynwzc.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.iojbl.cn/Article/details/gtddcxzmcm.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.ehwqpu.com/Article/details/gtrlmdunsk.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.daria6918.cn/Article/details/gtraqzholl.html

Go:   // 手写 map[string][]T
来源：http://dali.zhongyouzk.top/Article/details/gthuvspzvb.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.zdqjudy.top/Article/details/gtwpksjdzo.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.hfpthk.cn/Article/details/gtmnqnykdo.html

[D20] 统计每个元素出现次数
来源：http://dali.feifeiyinyue.top/Article/details/gtbkdkhcxx.html

Py:   Counter(arr)
来源：http://dali.cheryme.top/Article/details/gtfbqheoyy.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtocvhqaqe.html


<!-- 参考信息 -->