代发 wailian999

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtzaagtjog.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtrjhetick.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gthkdjamsa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtfxrzlbkp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gttievcfcb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtbypytslc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yongpay.top/Article/details/gtrqpirnxg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtixsnosds.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gttdfhrlne.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtnksyqbgo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtlzeursjx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zdqjudy.top/Article/details/gtrctkagbc.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtmfpynepj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtzabjcszy.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtvikugotx.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtuywzfkaf.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gtqqrqojrr.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gtukljwhxh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmrhghuzr.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtbovqhlal.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtyjqzyvfi.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtborchswq.html

Ruby: return a, b
来源：http://dali.nwbrower.top/Article/details/gttpipzidw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fzhhl.top/Article/details/gtfgjniesz.html

[C06] 匿名函数 / lambda
来源：http://dali.quarkkingdee.top/Article/details/gtziilgdaz.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtpoatfbeb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.smart0.xyz/Article/details/gteibpqeyx.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtegwoozzl.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtjqnbnfcc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gthomghggk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gthgorytxq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenlongwang.top/Article/details/gtkugwnwpu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gteypfarqf.html

[C07] 把函数作为参数传入
来源：http://dali.sysykeji.top/Article/details/gtjcuapmkq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gtftuoepnz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtspfdgsgt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtkdymldmu.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtefminkfj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gtfchcxwti.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtlrnfectq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gtrlhrcrlt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtsxcgapcm.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtycrvskyx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtdftkctkw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gtilfaxows.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtbveeoqti.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtsprfbstk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtzcbsbooh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ehwqpu.com/Article/details/gtlmqtgxhz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxxgbjec.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtixczsehi.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtohtlezcj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtcbvdslyx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtwpctuuqc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxinkj.top/Article/details/gtygdsbtyd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gttvdiiglt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvkquhhfc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gthzvlbrgb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gthtwmjomg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gtnblnvrbj.html

[C10] 变量作用域
来源：http://dali.yongpay.top/Article/details/gtkrheazxy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtzdvwonyk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shuidangran.top/Article/details/gteyxaaett.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtsixzzggu.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtagghuakw.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtrbotonlm.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtkqhvukgr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gtlhxkppxx.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtlfivaomt.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtuvlhfbiw.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtehndtvlz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtvxctvofr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtgwqyfoha.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.svipenyu.cn/Article/details/gteicypows.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtkxjqduyl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtqugqkekp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtqxsuturd.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtrnxonyax.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtkglcezdw.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gtqgfzpymy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtomjycdub.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtpqfrbmlu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.feifeiyinyue.top/Article/details/gtidobgbng.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuanzhike.top/Article/details/gtqfwlpjum.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.0kj1m.cn/Article/details/gtgdbktdhs.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtazyxaelj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cashguo.top/Article/details/gtnkcncytz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgfzy.top/Article/details/gtuyuctufl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtjduwqxzm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtqzmeqfpb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pycfn.com/Article/details/gtpdwgbuox.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmtgfmqxj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcmifmdlg.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtfesklzse.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gtuzukxxwo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtwehnevln.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtzxbijibf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtynldmybh.html

PHP:  // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtkjhngusg.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtvzjonrdz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtcgmtrzob.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtbcavudcx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gtvfrtnlqu.html

Ruby: # 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtnvmojlst.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtvceilttd.html

[C15] 解构 / 展开参数
来源：http://dali.birdmap.top/Article/details/gtywgzxyot.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtmualmnrv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gtwdffljve.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gthghjvlya.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtegsrdwdj.html

Java: // 无解构
来源：http://dali.c1oappe.top/Article/details/gtcvxmrpzv.html

Go:   // 无解构
来源：http://dali.pycfn.com/Article/details/gtwndgnnjb.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gturjfyvbv.html

C#:   var (a, b) = pair;
来源：http://dali.wangshuangyany.cn/Article/details/gthdjjmogd.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtrmpwcdqg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtfrfcamto.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtmtsvsmyy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwpiukfdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtomnmhvap.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtlabuychj.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtsdqqzjav.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjtdfhnf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtzkdgluun.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsoogambf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtehafxfnz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtwhikpaxr.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtsjkkeagp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtbjfppumj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtihmerldo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtuwboxxng.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.quarkkingdee.top/Article/details/gtggqefhuh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtjrqwmrdz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gtousjpfrj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aibaodan.cn/Article/details/gtyponiumv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtspfwenaq.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtmydmxsny.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jyoumei.cn/Article/details/gtzwrqpzse.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtzedlepgw.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gtnwhjyzad.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsyyqjkb.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtmvjuxcds.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtdtmrphac.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtdvunsbkr.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtddbuscvw.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtsvvctjus.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gttannifxp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtczehimxg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ydzc1.top/Article/details/gtgoiorzui.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtxtbbjwup.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiyhtjcym.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sweek.top/Article/details/gtzutyeopa.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.aizwys.cn/Article/details/gtpzrstmzr.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtptosljnj.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtdrwdgwxd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xziqi.cn/Article/details/gtwnqaqkih.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdpurrpu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gtzsajrnpn.html

TS:   arr.splice(0, 1);
来源：http://dali.gzhubu.top/Article/details/gtowgemipo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtpezljgdl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shzxlz.cn/Article/details/gtqxidawsc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhongyouzk.top/Article/details/gtflmmlgkn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnqzz.top/Article/details/gtpgynnilg.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtwcrdcxmc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtofajnepc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gtzfcxgxzx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gteupttzmv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttuobyytq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gtfrhidqrm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtqotzvwnr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gthvyfrxip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtblzvnjvq.html

[D06] 数组长度
来源：http://dali.fengsongda.top/Article/details/gtbekgzqpi.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtwlmlqidp.html

PHP:  count($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtgqwgmslh.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gttutlzpey.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtftmbyrdv.html

Java: list.size();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawjdctsr.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtxnjromot.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gtmdjetnps.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gtuhrwymwt.html

[D07] 切片 / 取子数组
来源：http://dali.shzxlz.cn/Article/details/gtnjznilgx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.dianchejie.cn/Article/details/gtzwbhkkbu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtxwhiiifn.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtehfyeygu.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtkpzdgths.html

Java: list.subList(1, 4);
来源：http://dali.hammf.cn/Article/details/gtkgclraci.html

Go:   arr[1:4]
来源：http://dali.havefunace.top/Article/details/gtafnrvzrp.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtcwdcznpv.html

C#:   list.GetRange(1, 3);
来源：http://dali.tanke756.top/Article/details/gtkewsulgb.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gtkfhhtzen.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtfgppwyhu.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtestefoga.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtqializlz.html

TS:   [...a, ...b];
来源：http://dali.birdmap.top/Article/details/gtmiirgvdy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtgklslvzf.html

Go:   append(a, b...)
来源：http://dali.316326.xyz/Article/details/gtdxvlgftl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ivvv.top/Article/details/gtmrsmcgen.html

C#:   a.Concat(b).ToList()
来源：http://dali.c1oappe.top/Article/details/gtpgprpevj.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtvranyzbp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruepcvfx.html

PHP:  sort($arr);
来源：http://dali.haohaochexian.top/Article/details/gtaxwwaqsm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangshuangyany.cn/Article/details/gtyocxtwsh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtxmckugqn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sxryk.cn/Article/details/gtojzxovwg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sufxvd.cn/Article/details/gtcbwysahr.html

Ruby: arr.sort
来源：http://dali.xylfe.cn/Article/details/gteblvopah.html

C#:   list.Sort();
来源：http://dali.svipenyu.cn/Article/details/gthizthwhx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhijiandao.cn/Article/details/gtxivhjzey.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtjflpapit.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.mhx1999.top/Article/details/gtlkqtghtm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtrzkovcmd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xuanzx.com/Article/details/gtnbhdtviu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwpkxagmi.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gtfogwtsvr.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtbdpicgta.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jqgfzy.top/Article/details/gtyugbcuwr.html

[D11] 反转数组
来源：http://dali.chenzaomai.com/Article/details/gtzllwaass.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sysykeji.top/Article/details/gtcovpnued.html

PHP:  array_reverse($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtmwowtikv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yangfankeji.com/Article/details/gtwldakwfl.html

TS:   [...arr].reverse();
来源：http://dali.svipenyu.cn/Article/details/gtceqamehb.html

Java: Collections.reverse(list);
来源：http://dali.jiagoushi.top/Article/details/gtxsyqgsiy.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtcpeekswv.html

Ruby: arr.reverse
来源：http://dali.tian-w.cn/Article/details/gtdccnhiak.html

C#:   list.Reverse();
来源：http://dali.yongpay.top/Article/details/gtvulmagrt.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtsvrinwih.html

Py:   arr.index(x);  x in arr
来源：http://dali.ehwqpu.com/Article/details/gthqgqtfav.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtkqufiogs.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtmnswxlbj.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtpctkbcqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtrxqvjypo.html

Go:   slices.Index(arr, x)
来源：http://dali.hammf.cn/Article/details/gtkninmhob.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gtjgioxymx.html

C#:   list.IndexOf(x);
来源：http://dali.ybcxt.top/Article/details/gtbbmlsmlk.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtzgriyxix.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtpcbgxivo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.vqdsnc.cn/Article/details/gtusmrjxgn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtkqdbogqv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jiagoushi.top/Article/details/gtxnrcnngb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhixingplan.top/Article/details/gtvqhmmrux.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jlsjyb.cn/Article/details/gtibkztwlh.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sweek.top/Article/details/gtuaxjorym.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gtbovftjda.html

[D14] 映射转换（每个元素变形）
来源：http://dali.kuanghao11.cn/Article/details/gtwqtpbdwb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.haohaochexian.top/Article/details/gtcnrmgrby.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.smart0.xyz/Article/details/gtclnkucyk.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gthtztyofd.html

TS:   arr.map(x => x * 2)
来源：http://dali.chenlongwang.top/Article/details/gtalcaxrsi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtbwnesjgo.html

Go:   // 手写循环
来源：http://dali.daxiang520.top/Article/details/gtpbrwpgob.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtbktqsxid.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.c1oappe.top/Article/details/gtjqncyzmq.html

[D15] 去重
来源：http://dali.aibaodan.cn/Article/details/gtkxhlxbpq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtjtbqsrfs.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwcxmevdb.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtfynjgmoq.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gtydllxmas.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ivvv.top/Article/details/gtslyvtzir.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtwnlmbogv.html

Ruby: arr.uniq
来源：http://dali.shangyingyoupin.top/Article/details/gtahhwxygn.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwreujukl.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosxtatox.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cashguo.top/Article/details/gtsjcdoyyb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sysykeji.top/Article/details/gtxqifjgoj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtkguunzid.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtcibmyzdh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hnqzz.top/Article/details/gtcjlmjgim.html

Go:   // 手写循环累加
来源：http://dali.daxiang520.top/Article/details/gtlitiusjf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sxryk.cn/Article/details/gtqybfdxei.html

C#:   list.Sum();  list.Average()
来源：http://dali.zhijiandao.cn/Article/details/gtxpifxkkp.html

[D17] 最大值与最小值
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiyhfdoi.html

Py:   max(arr);  min(arr)
来源：http://dali.sweek.top/Article/details/gtkeuvrjxe.html

PHP:  max($arr);  min($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtczyrnuic.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhongyouzk.top/Article/details/gtaxlfmaeb.html

TS:   Math.max(...arr);
来源：http://dali.zhongyouzk.top/Article/details/gtstusxxnx.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuanzhike.top/Article/details/gtpsmurlcr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.ppjwa.cn/Article/details/gtbtckazrc.html

Ruby: arr.max;  arr.min
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdhzmtky.html

C#:   list.Max();  list.Min()
来源：http://dali.jiagoushi.top/Article/details/gtcdalfkim.html

[D18] 扁平化嵌套数组
来源：http://dali.hywenlv.cn/Article/details/gtmfglynua.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hammf.cn/Article/details/gtrkahlhmw.html

PHP:  array_merge(...$nested);
来源：http://dali.chenjidiqi.icu/Article/details/gtrcgqzdud.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.pycfn.com/Article/details/gthxckadmv.html

TS:   nested.flat();
来源：http://dali.zhixingplan.top/Article/details/gtcxkavmuq.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.cqqwz.cn/Article/details/gtsypyynto.html

Go:   // 手写双层循环
来源：http://dali.pycfn.com/Article/details/gtmasilmds.html

Ruby: nested.flatten
来源：http://dali.nanxinkj.top/Article/details/gtscxxnezm.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cheryme.top/Article/details/gteyswapop.html

[D19] 按字段分组
来源：http://dali.aibaodan.cn/Article/details/gtugotvvfn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.iojbl.cn/Article/details/gtwlsljnab.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.hongshengwenyu.top/Article/details/gtqxomnwva.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.jianghu66.top/Article/details/gtbkrodbzh.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.zdqjudy.top/Article/details/gtopokioxf.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtflqgvfhr.html

Go:   // 手写 map[string][]T
来源：http://dali.mhx1999.top/Article/details/gtfvhcjeec.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.sufxvd.cn/Article/details/gtcjvtcrnl.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.zhoulong.xyz/Article/details/gttfcnnqsn.html

[D20] 统计每个元素出现次数
来源：http://dali.daxiang520.top/Article/details/gtfyjguwnd.html

Py:   Counter(arr)
来源：http://dali.birdmap.top/Article/details/gtvotjmgxe.html

PHP:  array_count_values($arr);
来源：http://dali.sufxvd.cn/Article/details/gtrinsfrpc.html


<!-- 参考信息 -->