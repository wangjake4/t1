代发 wailian999

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtvsuknjzj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cqqwz.cn/Article/details/gtjicghxqh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtanpahiqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtnfrbkfks.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtkhigarzz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtygqitrno.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gteoxlpihc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gtvlrwzjgc.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtwjhdzgpy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtkgtecdvq.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahqbfyey.html

[C05] 返回多个值
来源：http://dali.hongshengwenyu.top/Article/details/gtojctztzt.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtxqvsaaqc.html

PHP:  return [$a, $b];
来源：http://dali.cashguo.top/Article/details/gtjpvsymem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtaiqxrlrs.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtnajxffvl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtqavjsxft.html

Go:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtwglfzhis.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtgtmgmzni.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gaohongyu789.top/Article/details/gtngcuhwaa.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtrvsnpsjt.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtkydllvyr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ybcxt.top/Article/details/gtahqwsrbd.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtatfqucbt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtccixoyfr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hammf.cn/Article/details/gtspyyvdgp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtcyemnths.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtqiqmiwkn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtdmyhneqo.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtgkcyulhf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtzgdzfwpx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtvymjalaq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtphtubgnl.html

TS:   arr.map(String)
来源：http://dali.iojbl.cn/Article/details/gtvtfedlff.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtoouafodb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtohucxnkp.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtdvsehfme.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gttckexiqw.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtaodetsrh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gtnexsforh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yueranfly.top/Article/details/gtmkpmonom.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtseyiemll.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pengpengdd.cyou/Article/details/gtusoivzkp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtqxeemoex.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtoiqcfxtp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtvyvzslbb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtpholpeuk.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtrwbijurk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtterwelgu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtqndsqyug.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtrchfxqib.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gteaubpaay.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtmtqifcvs.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtgpxruedp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtvqfoqdgl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtulesaxng.html

[C10] 变量作用域
来源：http://dali.0kj1m.cn/Article/details/gthvitoeoj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.daxiang520.top/Article/details/gtxpebeipr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtvtbibjyk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gtglljohnd.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gthrcuwfon.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtyrljioeo.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gttqqzitje.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtufwzkiyr.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckxxgciy.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtzammzeqw.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gtxqxllcpd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtlexmgstw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtegbnnoen.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtfetkmoqe.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbudjrbq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gtqytoevcl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.meibo888.top/Article/details/gtptwcfibl.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvyqqjuf.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtlugqslek.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtpfqejhfb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guowangkeji.top/Article/details/gtpsniqcsc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtyjemsxkz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykexvepk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtgzsfxnaa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtoipapevq.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhengqikj.top/Article/details/gtfvcnkhwg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gthnomarkk.html

[C13] 类型声明 / 类型注解
来源：http://dali.wangdashe.top/Article/details/gtaoarotbt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtiwubgslm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtontvdeoi.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtcojmrtix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gttjmplucf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtbdurcrio.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtgktrtwni.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgfzy.top/Article/details/gtxspgnnpn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hammf.cn/Article/details/gtkerpcdvk.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gtsrrtnize.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtjvyvjqlp.html

PHP:  // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtpznaryut.html

JS:   // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gtxhosausy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.aibaodan.cn/Article/details/gtyuoujviz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtxehiejpb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gtflwnojhc.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtywcuyfms.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtfdnpqzwv.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtlsmleqiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hongshengwenyu.top/Article/details/gtiifgdtky.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gtccxiavwy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ydzc1.top/Article/details/gtsueqieph.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtkzytajns.html

Java: // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtqqovuopc.html

Go:   // 无解构
来源：http://dali.0kj1m.cn/Article/details/gtbavtrxlv.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtcuwjebdh.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gtknurrhjy.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtqlkculgg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtedmmkmmv.html

PHP:  // 无重载
来源：http://dali.svipenyu.cn/Article/details/gtysmdpult.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtktcbbzcv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtbzchoecu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtuqrsjmmo.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gthjltohfy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.chenlongwang.top/Article/details/gtucpjxbek.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtiqinomsy.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxemwqpko.html

D. 数组 / 列表 / 集合
来源：http://dali.tianlin.xyz/Article/details/gtaeunvaza.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtsyzvjjdf.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtkzyiixhv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtmfbrypbd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ivvv.top/Article/details/gttobblavt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtyzvlsxzs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtolpkwgcr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gttvrxznew.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.316326.xyz/Article/details/gtqvajfxyb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtfrvzpltl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.andypj.xyz/Article/details/gtkxfvnhwd.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtqduaphpo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtfdneofmq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gthyfwhnkc.html

JS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtejzktjev.html

TS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtdgknohfi.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gtwkxdbycp.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtozotlmrx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.redwolf501.top/Article/details/gtjwwqccsm.html

C#:   list.Add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtkcsrtwhg.html

[D03] 在指定位置插入元素
来源：http://dali.kuanghao11.cn/Article/details/gtuutizsqm.html

Py:   arr.insert(0, 0)
来源：http://dali.redwolf501.top/Article/details/gtdhkkgbfg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gtjyykczss.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj202588.top/Article/details/gtutybkxyw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtokgdziom.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtrxaciune.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtosxxyqoq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gtrrhmrypd.html

C#:   list.Insert(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtbrwuyymq.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtvkdtirnk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtbfisqgut.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtznyvnxuh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cheryme.top/Article/details/gtcevvpfpj.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtimgnlvsv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gtxujqkoxu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hfpthk.cn/Article/details/gtzpczlapk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhixingplan.top/Article/details/gtecnpydbs.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gtgkyiftnn.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gtmsbukefa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gtuobmdryp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtdlnyvptn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.shzxlz.cn/Article/details/gtxytnyste.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sysykeji.top/Article/details/gtnflcrcca.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xinyue.icu/Article/details/gtqngjodpd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhengqikj.top/Article/details/gtdxvkafzv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sufxvd.cn/Article/details/gtyoqymsep.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnmnllkn.html

[D06] 数组长度
来源：http://dali.jiagoushi.top/Article/details/gtupgtarve.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtlskvfhwd.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtgmofvexj.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtbjrobjsr.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gtybzqtixm.html

Java: list.size();
来源：http://dali.yj202588.top/Article/details/gthnunjavb.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtwcbkuccc.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarnrnodj.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtsiwaiyst.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gtejtrrjev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuanzx.com/Article/details/gthvatihzb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtqvojyqwq.html

JS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtyoxnkyac.html

TS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtulzsodwc.html

Java: list.subList(1, 4);
来源：http://dali.cdnleiting.top/Article/details/gtsbakcwdj.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gtidpcygvg.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gtnwjjxguq.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdpkaltz.html

[D08] 合并两个数组
来源：http://dali.zdqjudy.top/Article/details/gtoxxfbtsx.html

Py:   a + b;  a.extend(b)
来源：http://dali.9152youxi.cn/Article/details/gtculcvzac.html

PHP:  array_merge($a, $b);
来源：http://dali.jyoumei.cn/Article/details/gtgzhrxzxg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtogpdvxmq.html

TS:   [...a, ...b];
来源：http://dali.fzhhl.top/Article/details/gtcfoztclb.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtkbrssmvm.html

Go:   append(a, b...)
来源：http://dali.shzxlz.cn/Article/details/gtbclndvuq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gtpnopgvxv.html

C#:   a.Concat(b).ToList()
来源：http://dali.yongpay.top/Article/details/gtdfiwrsgz.html

[D09] 排序（升序）
来源：http://dali.ivvv.top/Article/details/gtrrcxoavw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtlawmccku.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtrdfiviuu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdrpbopv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtbkdltvor.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibuwpkjv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxdqmxjk.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtbysudbvh.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gtnwsbchfd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cdnleiting.top/Article/details/gtdkugodrc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtxxrwxliu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gthpreohhm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtmxxbxukq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dianchejie.cn/Article/details/gtskwbcxye.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.pengpengdd.cyou/Article/details/gtepzqvexs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.guowangkeji.top/Article/details/gtkkriukyy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hysaishi.cn/Article/details/gtteaezsui.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jiagoushi.top/Article/details/gtigbyoflp.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtqvpsireo.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gtkrexhimo.html

PHP:  array_reverse($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtgfzmhpgu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtzqbaywon.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtgdvtboki.html

Java: Collections.reverse(list);
来源：http://dali.cqqwz.cn/Article/details/gtxoukbtph.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtiygoksfx.html

Ruby: arr.reverse
来源：http://dali.yuxming.cn/Article/details/gtgxrxhhab.html

C#:   list.Reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtvmrjnjnh.html

[D12] 查找元素下标
来源：http://dali.cheryme.top/Article/details/gtyhnkpboq.html

Py:   arr.index(x);  x in arr
来源：http://dali.dianchejie.cn/Article/details/gtxpezhgac.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtuijkumjm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenjidiqi.icu/Article/details/gtouuagtcx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hfpthk.cn/Article/details/gttsllkgfb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtwxheatxw.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gtvsbkqook.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtupkmoxbj.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gtvnfopmzd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtquycdwqv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhixingplan.top/Article/details/gtehqbmwrz.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtlcrgeamj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.iojbl.cn/Article/details/gtljkizmtc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yanxiufei.cn/Article/details/gtkbjhbdjh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenlongwang.top/Article/details/gttlwfdgat.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ybcxt.top/Article/details/gtombgrvrs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yuanzhike.top/Article/details/gtjohgzgyr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yj20258888.top/Article/details/gtybbfvgnm.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yongpay.top/Article/details/gtbjllyseq.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtoytraroi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtbohyynef.html

JS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtxntiislk.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtpzqgkgpv.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.svipenyu.cn/Article/details/gtuljvgluk.html

Go:   // 手写循环
来源：http://dali.xuanzx.com/Article/details/gtttncbosd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtmyyhxikb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtobbkzkey.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gtvcxvpygl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hywenlv.cn/Article/details/gtwzzucdkq.html

PHP:  array_unique($arr);
来源：http://dali.yangfankeji.com/Article/details/gtpstsicdv.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtpsialnzd.html

TS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtzuiejbjr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtwwmlbntu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yanxiufei.cn/Article/details/gtfoatcqfj.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijnmqzwb.html

C#:   list.Distinct().ToList()
来源：http://dali.xziqi.cn/Article/details/gtylxeodjh.html

[D16] 求和与平均值
来源：http://dali.pycfn.com/Article/details/gtkmcrbgfv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtgxhakozw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtxiqsbwsa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ehwqpu.com/Article/details/gttxabnhaf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenzaomai.com/Article/details/gtlvzlgsef.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.aizwys.cn/Article/details/gtjvvgzlak.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gtmssauxrx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinqigufen.top/Article/details/gtxzbolmny.html

C#:   list.Sum();  list.Average()
来源：http://dali.c1oappe.top/Article/details/gtjifjpdtu.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gtzebvvxgt.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gtfgtcohsy.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtsfuzgmns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gtxfzjmhxd.html

TS:   Math.max(...arr);
来源：http://dali.hnxiangtu.top/Article/details/gtlysvkfrl.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.wangshuangyany.cn/Article/details/gtcrytyknc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.gotoacloud.top/Article/details/gtedcygcyl.html

Ruby: arr.max;  arr.min
来源：http://dali.hnqzz.top/Article/details/gtrnyqozfd.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtxbgcarnu.html

[D18] 扁平化嵌套数组
来源：http://dali.jqgufenzy.top/Article/details/gtwvcdyyiu.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gttjwbgnxm.html

PHP:  array_merge(...$nested);
来源：http://dali.jyoumei.cn/Article/details/gthsfwuppk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.nanxuanxn.top/Article/details/gtqldqclqd.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtvgmexcym.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.fengsongda.top/Article/details/gtfadbyfta.html

Go:   // 手写双层循环
来源：http://dali.aizwys.cn/Article/details/gthvyycttv.html

Ruby: nested.flatten
来源：http://dali.snrcjt.cn/Article/details/gtjazsfgfv.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtpyrvodjt.html

[D19] 按字段分组
来源：http://dali.xuanzx.com/Article/details/gthdujyspo.html

Py:   defaultdict(list)：for x in arr: groups[x["type"]].append(x)
来源：http://dali.zhoulong.xyz/Article/details/gtjulrexkm.html

PHP:  // 手写 foreach，归入 $groups[$key][]
来源：http://dali.wangshuangyany.cn/Article/details/gtvxbpxihf.html

JS:   Object.groupBy(arr, x => x.type)    // ES2024；旧环境手写 reduce
来源：http://dali.xziqi.cn/Article/details/gtovscncwq.html

TS:   Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigfzy.top/Article/details/gtbspdpzxr.html

Java: list.stream().collect(Collectors.groupingBy(Person::type))
来源：http://dali.zhiwuduotai.top/Article/details/gtytpeyvbn.html

Go:   // 手写 map[string][]T
来源：http://dali.cashguo.top/Article/details/gtmtkezzpd.html

Ruby: arr.group_by { |x| x[:type] }
来源：http://dali.316326.xyz/Article/details/gtpgzzchoi.html

C#:   list.GroupBy(x => x.Type).ToDictionary(g => g.Key, g => g.ToList())
来源：http://dali.fzhhl.top/Article/details/gtkeofotwo.html

[D20] 统计每个元素出现次数
来源：http://dali.yj20258888.top/Article/details/gtfhzdupus.html

Py:   Counter(arr)
来源：http://dali.andypj.xyz/Article/details/gtmdclsxgq.html

PHP:  array_count_values($arr);
来源：http://dali.chenlongwang.top/Article/details/gtojxnohgc.html

JS:   arr.reduce((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.dashuyun.cn/Article/details/gtjvsyjama.html

TS:   arr.reduce<Record<string, number>>((m, x) => (m[x] = (m[x] || 0) + 1, m), {})
来源：http://dali.chenzaomai.com/Article/details/gtbiblmlwr.html

Java: list.stream().collect(Collectors.groupingBy(x -> x, Collectors.counting()))
来源：http://dali.fengsongda.top/Article/details/gtgttosesi.html

Go:   // 手写 map[T]int
来源：http://dali.ehwqpu.com/Article/details/gtydrbwolk.html


<!-- 参考信息 -->