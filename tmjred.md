代发 wailian999

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtwwirzkiu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtashsdxvk.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtwouvicof.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtjwfqwdeu.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtxkxhufqr.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlodpxna.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sweek.top/Article/details/gtmcfrosfu.html

TS:   return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtjyetsyhe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.quarkkingdee.top/Article/details/gtwaimpycz.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtzfemllyc.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtrpealyea.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gtubmvappi.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtpukcuant.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtujhhrifh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtdozlkmng.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gthjjoeulj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gttqwcjiay.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtpgrdaqmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtvczzplht.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtbpoiwjch.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtlwfaoszg.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtyvhetxug.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtlwniyfsj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtgdctfpda.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gtgicphsmv.html

TS:   arr.map(String)
来源：http://dali.jqgufenzy.top/Article/details/gtkdgpomju.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtrluteeod.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gtddrxszoi.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtwmozqcue.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gtztdbpnjh.html

[C08] 闭包
来源：http://dali.nanxuanxn.top/Article/details/gtgmoxeryo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jiagoushi.top/Article/details/gtwpirljmr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtcuqadsyt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwtxilxz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtdppliedm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.vqdsnc.cn/Article/details/gtbwqfckpq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xuetiantiany.cn/Article/details/gtighxemby.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtnryxdtfv.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtymhznaod.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtvamecztg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtlvyjjieb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtmddkygyh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtlasgyhpq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtxsqixhqn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.fengsongda.top/Article/details/gtimsfrqsl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtkctnlzrx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtgqcmheul.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtvchxwefu.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtsmfuxvzi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtgtlutofs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtwnaggnjn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gternfwocg.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gttloogpln.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiyfdsvo.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtouwgmepz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258.top/Article/details/gtloskqncz.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtfptauwvb.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtoefgrqtt.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtkyqtqgft.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yanxiufei.cn/Article/details/gtcmmzzcjx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtcrahaitp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtremvpkgk.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtuuiesgss.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtvtlfgqli.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gtvjyraprc.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gttuanming.html

[C12] 立即执行函数 IIFE
来源：http://dali.hnqzz.top/Article/details/gtcezwfpsf.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtjnwhejwf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtldrskrpq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtxyggczfl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtsywsmaun.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtjespytln.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtobnrhlpq.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtaragwsyf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gthvebjghb.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtodvqcfvf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtbemikrgm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtihtnfksi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtbzpbjbdd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtqwgiuuqs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtryjjiqsp.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtwfibnrlz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljapwdqt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtwxmuezxr.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtyvwakvzt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gterhekhtt.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gtxniygjto.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtjgtdugod.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtkbxsdfto.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtnpowgdof.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtovukumxv.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtkagcvlrs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtjyuyoico.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtruxgtpcy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtmnpgfbux.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtxexmolmu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gtqgxoqmmn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xinyue.icu/Article/details/gtlouvrnee.html

Java: // 无解构
来源：http://dali.havefunace.top/Article/details/gtyllzbjbt.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtwhjdwsqg.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtgzblqgrs.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gtzadonklr.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtaayfgmyj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gtnozovhzu.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtymhurf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtjjmpwsbg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shzxlz.cn/Article/details/gthzthmqnn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtjrnwuwih.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtdwqmrart.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtawwkxkrn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtarsiselk.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtrsimkyhn.html

D. 数组 / 列表 / 集合
来源：http://dali.hongshengwenyu.top/Article/details/gtmxkyzvsa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtulfrlzgy.html

[D01] 创建数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gtdyovdvre.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtyqotfxcf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gthvcewhnh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jyoumei.cn/Article/details/gthgqmuyjg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtfpqmswxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gaohongyu789.top/Article/details/gtwukfnfes.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtwwvhszrk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtdcqlzltc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gtydtzwjjf.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtpcpmlxih.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtkzyiliab.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tian-w.cn/Article/details/gtwzdsolgb.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gttjqbxnrx.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtnipvvkic.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtmpwagvin.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gtzxtsvqlm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtqitqthdz.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gtjghtdyqj.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtwkctcldp.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtnxsvcbdc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtupllvhzu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtmcuouiip.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtpmbklyxg.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtxdqcashy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtgirtfjpu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtisnlhzfj.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtjvrrfrdt.html

[D04] 删除元素
来源：http://dali.hysaishi.cn/Article/details/gtdfbaxvyb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cqqwz.cn/Article/details/gtgoakdjlb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cucudq.cn/Article/details/gtklffzxyh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.vqdsnc.cn/Article/details/gtjwujtpun.html

TS:   arr.splice(0, 1);
来源：http://dali.guannengcc.top/Article/details/gtuouxtaxt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtfcirptdl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtuazrakvr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtxicorocx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtrvtwxxic.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtjcybxccs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gtsigvwvxt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtceznydxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtlacxpmkt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtaulnhznd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cdnleiting.top/Article/details/gthlpezime.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gteyuilfgu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtixbdimog.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtttnilybf.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtwywuihzc.html

Py:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtdkasxchk.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtzgjxmvyp.html

JS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtohycgjws.html

TS:   arr.length
来源：http://dali.zhoulong.xyz/Article/details/gtwcxkrrlo.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtclbytflw.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtakugjuwj.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtzhyjnxwx.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gtvioysymo.html

[D07] 切片 / 取子数组
来源：http://dali.cqqwz.cn/Article/details/gtphmbhkyp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jlsjyb.cn/Article/details/gtbizybxlk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj20258888.top/Article/details/gtrfdtfjaw.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtsqnitbck.html

TS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtczulymno.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtlvpbdlwf.html

Go:   arr[1:4]
来源：http://dali.meibo888.top/Article/details/gtqkgymick.html

Ruby: arr[1, 3]
来源：http://dali.jinqigufen.top/Article/details/gtjmdijquz.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtviazadiq.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzjpzfdz.html

Py:   a + b;  a.extend(b)
来源：http://dali.yueranfly.top/Article/details/gtlajebeuv.html

PHP:  array_merge($a, $b);
来源：http://dali.yj202588.top/Article/details/gtzjqnfsyl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtrbngujvp.html

TS:   [...a, ...b];
来源：http://dali.smart0.xyz/Article/details/gtiynjegjx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gthuymhlli.html

Go:   append(a, b...)
来源：http://dali.shuidangran.top/Article/details/gtvjprqbgj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gtjeaomkrw.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohofgxsu.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtcwjimgyw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtcqwmgtbt.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gttngcyzzi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtwgmsnhdl.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtpzccumgs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtqoglegxs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtflmaqtqh.html

Ruby: arr.sort
来源：http://dali.jinqigfzy.top/Article/details/gtlwhjgbeq.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtdjpmlnku.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtsusdoqvr.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnxiangtu.top/Article/details/gtxmmcwwmk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtcrakbjyq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj202588.top/Article/details/gtzbcaacof.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gzhubu.top/Article/details/gtmjbyzgyz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.redwolf501.top/Article/details/gttfyasuyc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zdqjudy.top/Article/details/gteatqoxlm.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.svipenyu.cn/Article/details/gtbccsfzql.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gtgzbykdwn.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gttgmwtgtw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ivvv.top/Article/details/gtixombujw.html

PHP:  array_reverse($arr);
来源：http://dali.aizwys.cn/Article/details/gtqadrkcgy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.havefunace.top/Article/details/gtgtwdhcbk.html

TS:   [...arr].reverse();
来源：http://dali.smart0.xyz/Article/details/gtckeqebdf.html

Java: Collections.reverse(list);
来源：http://dali.jyoumei.cn/Article/details/gtnbnhmhcn.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gthgmoijuf.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gttvbrnlct.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbawuelab.html

[D12] 查找元素下标
来源：http://dali.xuetiantiany.cn/Article/details/gtqatrqpxk.html

Py:   arr.index(x);  x in arr
来源：http://dali.cucudq.cn/Article/details/gtdazhglum.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sweek.top/Article/details/gtqghuknod.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtdzxzrhri.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtdyjvbird.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yuanzhike.top/Article/details/gthmitiull.html

Go:   slices.Index(arr, x)
来源：http://dali.jlsjyb.cn/Article/details/gtpxwzzhzr.html

Ruby: arr.index(x)
来源：http://dali.chenzaomai.com/Article/details/gtgivxhawa.html

C#:   list.IndexOf(x);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbkjjyei.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gtkwnqddsf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gtpezugfjo.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gtbehbbokq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gtphegugju.html

TS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtnijcnrtn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtlflsccye.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtacsppdjm.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hongshengwenyu.top/Article/details/gtsitzrkcc.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenzaomai.com/Article/details/gtkxtpzaxm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.mhx1999.top/Article/details/gtlmpjejam.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtrkpgnirz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zdqjudy.top/Article/details/gtamcmehnz.html

JS:   arr.map(x => x * 2)
来源：http://dali.bjfxy.top/Article/details/gtirikapnf.html

TS:   arr.map(x => x * 2)
来源：http://dali.guannengcc.top/Article/details/gtsojkbzrc.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yonumen.top/Article/details/gtkxewcpgq.html

Go:   // 手写循环
来源：http://dali.birdmap.top/Article/details/gtsghavyso.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtkbnohdot.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangdashe.top/Article/details/gtyhbycxiw.html

[D15] 去重
来源：http://dali.gogol.net.cn/Article/details/gtzaetdokq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtazjusqty.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtpmfwxwdk.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtftwjzmvj.html

TS:   [...new Set(arr)]
来源：http://dali.jyoumei.cn/Article/details/gtwhlgiebg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gtmpruqadv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtqmeslbsi.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gthfjtrdql.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtxgetixtp.html

[D16] 求和与平均值
来源：http://dali.xuanzx.com/Article/details/gtxlkvmspp.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhixingplan.top/Article/details/gtgjjoyzti.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.tanke756.top/Article/details/gtpzycdxsc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtxmvvcuix.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gttyesylnx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtkuokspii.html

Go:   // 手写循环累加
来源：http://dali.xinyue.icu/Article/details/gthrhjlldd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gthirqusfb.html

C#:   list.Sum();  list.Average()
来源：http://dali.yangfankeji.com/Article/details/gtnnyiplnq.html

[D17] 最大值与最小值
来源：http://dali.iojbl.cn/Article/details/gtiohtwcnr.html

Py:   max(arr);  min(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjvaxhsx.html

PHP:  max($arr);  min($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtijqvnlba.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.dianchejie.cn/Article/details/gtbuxuvipc.html

TS:   Math.max(...arr);
来源：http://dali.nanxuanxn.top/Article/details/gtqiwhsrhv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.haohaochexian.top/Article/details/gtiiviwcvx.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzqzeqlqx.html

Ruby: arr.max;  arr.min
来源：http://dali.c1oappe.top/Article/details/gtoqiedkkg.html

C#:   list.Max();  list.Min()
来源：http://dali.cqqwz.cn/Article/details/gtefjpsjxy.html

[D18] 扁平化嵌套数组
来源：http://dali.0kj1m.cn/Article/details/gttguqbmqj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aizwys.cn/Article/details/gtlelvegsu.html

PHP:  array_merge(...$nested);
来源：http://dali.hywenlv.cn/Article/details/gtopygvjrq.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.zhengqikj.top/Article/details/gtroaybstx.html

TS:   nested.flat();
来源：http://dali.shzxlz.cn/Article/details/gtothmxjkc.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.wangdashe.top/Article/details/gtalemiddb.html

Go:   // 手写双层循环
来源：http://dali.cucudq.cn/Article/details/gtrbenxnus.html

Ruby: nested.flatten
来源：http://dali.yongpay.top/Article/details/gtyyqcnhob.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.iojbl.cn/Article/details/gtnipacyuc.html

[D19] 按字段分组
来源：http://dali.zhongyouzk.top/Article/details/gtlibswxwn.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.yonumen.top/Article/details/gtavwucsdu.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.aibaodan.cn/Article/details/gtucagmwhx.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.hfpthk.cn/Article/details/gteijqnryg.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.yj202588.top/Article/details/gtbfsjuduh.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.mhx1999.top/Article/details/gtfgzmamnx.html

Go:   // 手写 map[string][]T
来源：http://dali.gaohongyu789.top/Article/details/gtimivvwio.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.dashuyun.cn/Article/details/gtmybogzqp.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmnacybu.html

[D20] 统计每个元素出现次数
来源：http://dali.yuanzhike.top/Article/details/gtkrcpcsdj.html

Py:   Counter(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gttdihtijc.html

PHP:  array_count_values($arr);
来源：http://dali.zhixingplan.top/Article/details/gtnkfzpyww.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.sweek.top/Article/details/gtfurovscu.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.redwolf501.top/Article/details/gtwpsghxxd.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.redwolf501.top/Article/details/gtlaonqmlo.html

Go:   // 手写 map[T]int
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpsrntyd.html

Ruby: arr.tally
来源：http://dali.yonumen.top/Article/details/gtsivjywne.html

C#:   list.GroupBy(x => x).ToDictionary(g => g.Key, g => g.Count())
来源：http://dali.jyoumei.cn/Article/details/gtbxodjazj.html

[D21] 判断是否包含某元素
来源：http://dali.daria6918.cn/Article/details/gtdigwsjbv.html

Py:   x in arr
来源：http://dali.cashguo.top/Article/details/gttcpafvmr.html

PHP:  in_array($x, $arr, true);
来源：http://dali.gaohongyu789.top/Article/details/gtsobprhqh.html

JS:   arr.includes(x)
来源：http://dali.kuanghao11.cn/Article/details/gtwixghlko.html

TS:   arr.includes(x)
来源：http://dali.yvedp.cn/Article/details/gtunmcguai.html

Java: list.contains(x)
来源：http://dali.shuidangran.top/Article/details/gtbntjtpzd.html


<!-- 参考信息 -->