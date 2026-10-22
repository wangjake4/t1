代发 wailian999

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gteypcfsvu.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtezehrhpv.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gtstngkvgp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmdsysol.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gttztekfjc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtkgchahic.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtvpmilchr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gtoltkulme.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtaawadbtk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtkkzojbvf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtglpvcuch.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtfauzwefh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ybcxt.top/Article/details/gtcgwcwdxz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gtsaxeaewp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtkubghjid.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtoknhpnco.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gthrgsgpvw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtvzbnhpaj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtldjavdno.html

[C05] 返回多个值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiikewbxv.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtixajuvfy.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gtqfrhjplb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtyrbueusd.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtiwbqnkyq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtdaezzxan.html

Go:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtniruyvcv.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtgzujwmny.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtpacicpdw.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtlbkqhbcz.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtsvewxwvr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gtjestlefp.html

JS:   const square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtcxwetaix.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gtxyqbauff.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtmgseuelj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtqtkfkkrh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcmmuzax.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtouxhjymr.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtretvjiqb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.9152youxi.cn/Article/details/gtdnkxlhqj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtrannyrbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtpxwdrxbv.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtyzhfrkos.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtnbsyjqhi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gticcdhncx.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gtvkwprtks.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtkhfklwie.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtrrczzihw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtpspfilqq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gtwljqdusx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtkydskduo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqbxvpnq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yangfankeji.com/Article/details/gtivtiikui.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hongshengwenyu.top/Article/details/gtojzwzrkw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangshuangyany.cn/Article/details/gtclkahynm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtbrrbcmee.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtoydldqqn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gthltkgmfo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtynhsmizr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtllfqjwfo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gtfppimflq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtabnazzan.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gtldjzliln.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtxtujtojb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtvomjczmb.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gtdtueiqhb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yanxiufei.cn/Article/details/gtkgbsannb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gthvnnudhr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwfyejnu.html

TS:   同 JS
来源：http://dali.ydzc1.top/Article/details/gtxdbpdfaw.html

Java: 方法内为块级作用域
来源：http://dali.xylfe.cn/Article/details/gtiukxsioa.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gtvpapzrvq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gtvewkotcz.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtsatezzpp.html

[C11] 模块导入与导出
来源：http://dali.zhixingplan.top/Article/details/gtbksmbqnn.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtsgfmqono.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.haohaochexian.top/Article/details/gtnoairvlt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtudzfjzyj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtgkoiagcb.html

Java: import java.util.List;
来源：http://dali.yj20258.top/Article/details/gtbhlrhlaa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.316326.xyz/Article/details/gtygfhanwx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtxjqauurb.html

C#:   using System.Text;
来源：http://dali.mhx1999.top/Article/details/gtgqqmnhgw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxaikjqg.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtdnupwqxm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cashguo.top/Article/details/gtuvzebgwe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtsyhqhujz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtcutnfuad.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtewnrgwth.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtylfgitve.html

Ruby: -> { puts "run" }.call
来源：http://dali.aibaodan.cn/Article/details/gtmkcqhqml.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtecotnrfe.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtilxrvdiz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtkzllqsce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtoysfmeie.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gtbjdfvpvs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gttuxuelxz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtcccxnusq.html

Go:   func add(a, b int) int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwamzwma.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtxgeqhled.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtzzxobgvh.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtwrfjnmta.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtpohanvyn.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gthifueqnw.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtabmqxntz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtrtiomynf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtvmypmxac.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtskupjwcu.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkheykbgu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtbvtlurzc.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtyazfmrcl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gtpnaxzhoe.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtzokwwvjy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpifesdnv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258.top/Article/details/gtmaxwtycg.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtqejhtcih.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtpzwpjdxd.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtczablbry.html

C#:   var (a, b) = pair;
来源：http://dali.daria6918.cn/Article/details/gtxdennjoq.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtpowefbta.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtuhaflwut.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gtfiaqnieu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtfrkqehlm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fengsongda.top/Article/details/gtuswwynld.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtsnkwlpos.html

Go:   // 无重载：用不同函数名
来源：http://dali.yvedp.cn/Article/details/gtctyduqvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtzrpdnvkm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtzskofdzp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtyjbbcxri.html

D. 数组 / 列表 / 集合
来源：http://dali.chenlongwang.top/Article/details/gtsdnalkmv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtdarmzodv.html

[D01] 创建数组 / 列表
来源：http://dali.gotoacloud.top/Article/details/gtbpfsbxga.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.mhx1999.top/Article/details/gtxkwrsknw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtdtedyvub.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gttzvygzmo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gtxmmsqflf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ydzc1.top/Article/details/gtuqdgvojs.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gttbhnmszf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.meibo888.top/Article/details/gtpphavieo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtceulmfyy.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtlylrpxzk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtxwqikaqw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hammf.cn/Article/details/gtifqjnrud.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gttjnfnhwp.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtgudlvbok.html

Java: list.add(4);
来源：http://dali.aizwys.cn/Article/details/gtsjarytbz.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gtknnomjwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.c1oappe.top/Article/details/gtnyylugyb.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtclpoqykz.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gterlopgwq.html

Py:   arr.insert(0, 0)
来源：http://dali.yongpay.top/Article/details/gteajxzvhw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gtnpqqkqnh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtmedzyjvj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtihfmfvtw.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvofywhl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtktxlaunx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gtpsgglvzh.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtwdtfowiz.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtjykdcndt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtocwmxrdn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtqjmrsmvu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtnmovtffu.html

TS:   arr.splice(0, 1);
来源：http://dali.aizwys.cn/Article/details/gtewifmopm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gtydjugoal.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.daria6918.cn/Article/details/gtyrfrkgyv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cheryme.top/Article/details/gtfzdnxzlj.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cashguo.top/Article/details/gtjbcoohii.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gtunmdiazy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtujqfodax.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.birdmap.top/Article/details/gtmguoqxop.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtvtgvuzvy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtcoyhtpyh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtqtvoawam.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtwjxsdmat.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtqwlzsefg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtbgfezwxs.html

[D06] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtfbwhnogw.html

Py:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtnmwkskhs.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gtinkariql.html

JS:   arr.length
来源：http://dali.tanke756.top/Article/details/gtyopwcfec.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtkmyssugv.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtxfahibym.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtfrrvovkc.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtsusyvxwc.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gtqyrdclpb.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtgqcnpkwf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtvquczsbh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.snrcjt.cn/Article/details/gtjmesnagb.html

JS:   arr.slice(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvoarrdnu.html

TS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gtaddfwfya.html

Java: list.subList(1, 4);
来源：http://dali.cheryme.top/Article/details/gtgebcjekm.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtzicptjko.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtaaovmlbw.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthwsmgxvc.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtlbvvjinh.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtaldgddxh.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtstbpmmpa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtbyfovpxk.html

TS:   [...a, ...b];
来源：http://dali.chenjidiqi.icu/Article/details/gtgoqmyahj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtswhkgpzk.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtgflrkmoi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jqgfzy.top/Article/details/gtwvjymydh.html

C#:   a.Concat(b).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtybcdjwuk.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtfvslkswb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtsbzylijm.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtylojyjxv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.iojbl.cn/Article/details/gtsomuzvwl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fzhhl.top/Article/details/gtsivpnbre.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhixingplan.top/Article/details/gtzmsamroc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gtkpgdexdv.html

Ruby: arr.sort
来源：http://dali.jqgufenzy.top/Article/details/gtnjqexjyb.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtdhohxlim.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xuanzx.com/Article/details/gtwkkbndry.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtcxggozmr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gteikjzwhg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gtellhwdqd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenlongwang.top/Article/details/gtspanmpex.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ybcxt.top/Article/details/gtnfdpprkt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guannengcc.top/Article/details/gtdvsnhbeo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guowangkeji.top/Article/details/gtpgbpcguf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yangfankeji.com/Article/details/gtgicbdixe.html

[D11] 反转数组
来源：http://dali.havefunace.top/Article/details/gtkrezyrek.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yj20258888.top/Article/details/gtbcqnqvso.html

PHP:  array_reverse($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtxszkewlc.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yanxiufei.cn/Article/details/gtnsdmtegf.html

TS:   [...arr].reverse();
来源：http://dali.jianghu66.top/Article/details/gtsoyysupz.html

Java: Collections.reverse(list);
来源：http://dali.daria6918.cn/Article/details/gtyltnaefg.html

Go:   slices.Reverse(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtuwkuojtk.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtrsxbgxjw.html

C#:   list.Reverse();
来源：http://dali.jlsjyb.cn/Article/details/gtoetxjjcb.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtcaqdvspj.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangdashe.top/Article/details/gtunhvxqvs.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtmsgzhnys.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwjvnwjgb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsukwzinr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ivvv.top/Article/details/gtfrwmcvxy.html

Go:   slices.Index(arr, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvaytkosf.html

Ruby: arr.index(x)
来源：http://dali.cdnleiting.top/Article/details/gtpzhwklhj.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtaofiiocu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gthhidvqrs.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtctwdvctu.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhengqikj.top/Article/details/gtobkyicfh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtzxbpgvaf.html

TS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhsmslxl.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shzxlz.cn/Article/details/gtugxhfmgd.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.bjfxy.top/Article/details/gtlasjfiaw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gtszhgzdfs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sxryk.cn/Article/details/gtrntsdaiz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhiwuduotai.top/Article/details/gtyrshpgtw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtxmrwxzwb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jianghu66.top/Article/details/gtjmqlzlbl.html

JS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gthawdvtke.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtojvryxqp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtizrlywjy.html

Go:   // 手写循环
来源：http://dali.0kj1m.cn/Article/details/gtozcidywx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtxyxmaxwe.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gtnjfyolte.html

[D15] 去重
来源：http://dali.jinqigufen.top/Article/details/gttqsloeqg.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtdfiesgjm.html

PHP:  array_unique($arr);
来源：http://dali.shuidangran.top/Article/details/gtvgcqjlkm.html

JS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gtbzfwjfdm.html

TS:   [...new Set(arr)]
来源：http://dali.nanxinkj.top/Article/details/gtnvmhbgqs.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gtggfylvgz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shanyushiyangtech.top/Article/details/gtsheuprtf.html

Ruby: arr.uniq
来源：http://dali.yangfankeji.com/Article/details/gthdmphwmj.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gttyaizuvn.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gttrymizea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtekbgkigs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gtortdevqh.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shzxlz.cn/Article/details/gtwytneubf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtlrnldnlz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinqigufen.top/Article/details/gtohokpaph.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtzpapzfvn.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtftjzukaa.html

C#:   list.Sum();  list.Average()
来源：http://dali.hongshengwenyu.top/Article/details/gtldflbqmz.html

[D17] 最大值与最小值
来源：http://dali.fengsongda.top/Article/details/gtqrgqmbeh.html

Py:   max(arr);  min(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtsvulfzxr.html

PHP:  max($arr);  min($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtlapotyov.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtggrqxkfg.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtwncijgfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yuxming.cn/Article/details/gtpyzbswtr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.sxryk.cn/Article/details/gtvhymghoq.html

Ruby: arr.max;  arr.min
来源：http://dali.xuetiantiany.cn/Article/details/gtcemwpgga.html

C#:   list.Max();  list.Min()
来源：http://dali.hywenlv.cn/Article/details/gtvxadhddt.html

[D18] 扁平化嵌套数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmwrbqau.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyewhubx.html

PHP:  array_merge(...$nested);
来源：http://dali.yj20258888.top/Article/details/gtaenoonud.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.daria6918.cn/Article/details/gtcsbtwwyr.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtxtcmfpro.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.hysaishi.cn/Article/details/gtxkbpobhf.html

Go:   // 手写双层循环
来源：http://dali.quarkkingdee.top/Article/details/gtptubgntv.html

Ruby: nested.flatten
来源：http://dali.jqgufenzy.top/Article/details/gtdbaeknht.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtvnloexpu.html

[D19] 按字段分组
来源：http://dali.yonumen.top/Article/details/gtjvidalgx.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.andypj.xyz/Article/details/gtpxwgqmng.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.jqgufenzy.top/Article/details/gtmikzqwll.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.316326.xyz/Article/details/gtqgonecwa.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtoidvlovo.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.iojbl.cn/Article/details/gtoyersqev.html

Go:   // 手写 map[string][]T
来源：http://dali.hysaishi.cn/Article/details/gtlgsistqu.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.ybcxt.top/Article/details/gtquxmwtvg.html


<!-- 参考信息 -->