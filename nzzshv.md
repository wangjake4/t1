代发 wailian999

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gtamlepedz.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtdjglrahp.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtdejqoxaw.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtxbsqsgkk.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtuobvqivz.html

Go:   if data == nil { return }
来源：http://dali.fzhhl.top/Article/details/gtlvxotxwa.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtceuvqses.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtfdwjvore.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthgyjroxw.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtnuokatmm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gteesgwitg.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gtuawbhmlb.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gtokjyoexn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gttocuwwse.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtdeqiqxap.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrdqqecjd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtgzrmhuib.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtsijbahfs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gtomoofkwf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtjwuuqptp.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtjpzddryo.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtnmvkrcol.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtxfbmqiez.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtebupfwjz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gthrsbkeha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gthwxkizxy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tanke756.top/Article/details/gtvxhjpigy.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtkioqnqqd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hfpthk.cn/Article/details/gtevupjqdg.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gttspbylac.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtlyptqiab.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.mhx1999.top/Article/details/gtxxdbhczz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtnpfljruf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtyzirwvxo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtgywejddx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxinkj.top/Article/details/gtzdpnbtcn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtkbiyecyd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtpvfzrfze.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gttrjaufsc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtanleyuyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gtfaaqkmcz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtbgwdhohs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gthravfgoz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gttbjvndvj.html

Go:   // 无：用配置结构体参数
来源：http://dali.0kj1m.cn/Article/details/gtufvqcscz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtfuihrevb.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtvcfjxahp.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtqtjgazdj.html

Py:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtfbrqmxdm.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxrzravt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtandwgfhe.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtqzwgjvqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtlgnqjdck.html

Go:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtmomyjzjx.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtlmdeetgw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtkbttawte.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtqkigkyub.html

Py:   square = lambda x: x * x
来源：http://dali.xuanzx.com/Article/details/gtgtdwkuid.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtdwueyjlw.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtxhznkynj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaeysckw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtpxatfdia.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtveamxolu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yanxiufei.cn/Article/details/gteyyavqka.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gthmvomkwr.html

[C07] 把函数作为参数传入
来源：http://dali.xuetiantiany.cn/Article/details/gtqhxauzhc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtwlmuwqbc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ehwqpu.com/Article/details/gteynfnjiu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtekigtfgo.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gtpqzlgbve.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gtgkovdwxq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtxaewuckt.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtphjzlpcn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gttenynfwo.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtamkjlbhz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtlruprzhr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nanxinkj.top/Article/details/gtitgdcwvs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtjudnemry.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnquvocz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gttgmacgwz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtzybhgjse.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtwfhkzdvj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gthxiaptav.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtdmkkqsqx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtooiassus.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtojeccbjc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtmsqjgbfw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtnurxkplg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtdkerwyyj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gtdzkbzcfb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtariccjik.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtahmjxxgg.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gttmolovvz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yueranfly.top/Article/details/gtwuiscnly.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangshuangyany.cn/Article/details/gtoqddaxed.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gtwoyguzqb.html

TS:   同 JS
来源：http://dali.zhongyouzk.top/Article/details/gtrmuazyrf.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtrbnlkrzf.html

Go:   花括号块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtyjazfmal.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvidvpyk.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtryihqbxf.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtzjelnlbf.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gtgwdzdzpa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtycajvkwo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodvbpnfk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtsxlxzzjl.html

Java: import java.util.List;
来源：http://dali.zdqjudy.top/Article/details/gtxhxlxsdi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shangyingyoupin.top/Article/details/gtrxudsmov.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xinyue.icu/Article/details/gtomsglqcu.html

C#:   using System.Text;
来源：http://dali.gogol.net.cn/Article/details/gtnhldtvbv.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinqigfzy.top/Article/details/gtmbsfcpro.html

Py:   (lambda: print("run"))()
来源：http://dali.yj20258888.top/Article/details/gtcuwnaypk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtfkqhqexi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtoyrtxvnk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtzipicwpn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shzxlz.cn/Article/details/gtrzahjnsf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhoulong.xyz/Article/details/gtgwipegnu.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtkajsxxbf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ydzc1.top/Article/details/gtewoltxxd.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gtsmbjuggb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtloadiofa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtwactuisz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtagdsylyy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttgbjvnej.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtiitxwqsx.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtcyeorytl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtccvixtqw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ivvv.top/Article/details/gtmatkbrrw.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gttlqxiomg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtrxdcxiac.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtzjqqoicr.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtgksgszoi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gtwwwcpizp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.kuanghao11.cn/Article/details/gtpqntkwrm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guowangkeji.top/Article/details/gtujwawnzb.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtjkmqvork.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tianlin.xyz/Article/details/gtynbpmngg.html

[C15] 解构 / 展开参数
来源：http://dali.hfpthk.cn/Article/details/gtbzyhwsid.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtnixhahjz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtfswumobk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtdnemdefm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtqczepuug.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtbddmxmwn.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtpiwphpoe.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gtotdcowit.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtormujcxs.html

[C16] 函数 / 方法重载
来源：http://dali.jlsjyb.cn/Article/details/gtpbfcwwyf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtqroylepd.html

PHP:  // 无重载
来源：http://dali.snrcjt.cn/Article/details/gtufdugnpo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtrluhqfgd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtbhquhujd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtbshrarss.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gteqekrmxr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtqzxhqzpt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gttlijayqw.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtmzflcjgo.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtjdhposhq.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtaosjdyxe.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtwddpnila.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gtcrhndmaa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtnvfttich.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtirwjnufs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtrmuxtpyw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hywenlv.cn/Article/details/gttospdrfa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gtcanwbiuj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gtwjqllgaw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gthpabnysa.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtjmcvzemk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbspwsfth.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtqgbmemzf.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtsuqopcny.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtumvuqqdu.html

Java: list.add(4);
来源：http://dali.cucudq.cn/Article/details/gtajqetvhv.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtedisbwdv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtxwvjivlh.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gttrcuqmio.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gttmoprpfo.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpxlvaou.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtyaykcgaj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtferjcnff.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznlljwwx.html

Java: list.add(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gthotawzgt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tian-w.cn/Article/details/gthlvdexxo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtjwyptxlb.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtypyxbpwz.html

[D04] 删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtvqckxbxc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gtcjkyfhnz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sufxvd.cn/Article/details/gtraoqyajm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtyyiangau.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtgzytxfos.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzttnjjl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtsnpzdpzq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtinnbwdbn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtowxluatr.html

[D05] 访问与修改元素
来源：http://dali.sxryk.cn/Article/details/gtzdsrvmwx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shzxlz.cn/Article/details/gtpenevxnb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtlmhaehbs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tanke756.top/Article/details/gtvzgkbqfl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtlmzbzckv.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigufen.top/Article/details/gtxfbtxbgm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthpfiqovb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtknzpsftr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtkliradzn.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtwyywitnm.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtfsdnurkc.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtyuecyyiq.html

JS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gtnxcmxapx.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtggfgczsf.html

Java: list.size();
来源：http://dali.yangfankeji.com/Article/details/gtjydgblfz.html

Go:   len(arr)
来源：http://dali.ivvv.top/Article/details/gtcarrsvpf.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtpknpmiwt.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gttdarjdzz.html

[D07] 切片 / 取子数组
来源：http://dali.chenjidiqi.icu/Article/details/gtlbbnvlzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ydzc1.top/Article/details/gtqawbmyaf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtksdvwfbn.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtgrxemxoy.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gtcljmldam.html

Java: list.subList(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtnrquckmf.html

Go:   arr[1:4]
来源：http://dali.haohaochexian.top/Article/details/gtrrpbdxuw.html

Ruby: arr[1, 3]
来源：http://dali.shanyushiyangtech.top/Article/details/gtbybyssbo.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gtpujbvroc.html

[D08] 合并两个数组
来源：http://dali.andypj.xyz/Article/details/gtplooolcz.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangshuangyany.cn/Article/details/gtzcrdnmnw.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gtsxaahjgt.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtjyllxygd.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gteqlhudvu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.wangdashe.top/Article/details/gtxisvjwwl.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gtywpjqwio.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtfrmadctj.html

C#:   a.Concat(b).ToList()
来源：http://dali.svipenyu.cn/Article/details/gtxvokhtqd.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gtndtehaed.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.316326.xyz/Article/details/gtfseuatql.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gthewezpwp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtdbrizowk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gtfnuacdax.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.dianchejie.cn/Article/details/gtqeevlfva.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.havefunace.top/Article/details/gthhsrwfba.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gtrfqulghx.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtrnzyvjcu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.0kj1m.cn/Article/details/gtxabvyced.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtsuhyibtr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gtomfhpaxi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shzxlz.cn/Article/details/gtptsdvyut.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkesxowhl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtqdcjwibh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.gogol.net.cn/Article/details/gtpzvmwvsc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhoulong.xyz/Article/details/gthkzlktvs.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigufen.top/Article/details/gtlhebxofw.html

[D11] 反转数组
来源：http://dali.xuanzx.com/Article/details/gthwziqccz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jqgufenzy.top/Article/details/gtbftitoea.html

PHP:  array_reverse($arr);
来源：http://dali.fengsongda.top/Article/details/gtcrifcovi.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pycfn.com/Article/details/gtfkpylies.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtkqbnxsiq.html

Java: Collections.reverse(list);
来源：http://dali.hnqzz.top/Article/details/gtkturcmib.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gtftsssqvb.html

Ruby: arr.reverse
来源：http://dali.hnxiangtu.top/Article/details/gtjumgrefy.html

C#:   list.Reverse();
来源：http://dali.jinqigfzy.top/Article/details/gtfczokehd.html

[D12] 查找元素下标
来源：http://dali.hfpthk.cn/Article/details/gtxfrblvfy.html

Py:   arr.index(x);  x in arr
来源：http://dali.shzxlz.cn/Article/details/gtnonuczte.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtpdvwtbql.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtscnxanqt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fengsongda.top/Article/details/gtgmrzcyio.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtcpawdjcx.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gtnjizzvhk.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtjfddtgwz.html

C#:   list.IndexOf(x);
来源：http://dali.daxiang520.top/Article/details/gtjtssovub.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yonumen.top/Article/details/gtmsctfwds.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sweek.top/Article/details/gtboemxlew.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcdlrglv.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtiyfgddbr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtqhefxvvg.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gtctusnyrm.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tian-w.cn/Article/details/gtdrawxwgu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ivvv.top/Article/details/gtriiomuek.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gtjyzaytff.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangshuangyany.cn/Article/details/gtxepxfipa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.smart0.xyz/Article/details/gttkgyopod.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnebtxrra.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtsrsxcccq.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gtfqwlqlaq.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtxwvtecoy.html

Go:   // 手写循环
来源：http://dali.bjfxy.top/Article/details/gtstfgqrgp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtmbnygobg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gtmzfcsgig.html

[D15] 去重
来源：http://dali.jlsjyb.cn/Article/details/gtjhvkqudb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gtcmwhztve.html

PHP:  array_unique($arr);
来源：http://dali.ppjwa.cn/Article/details/gtghayhhkm.html

JS:   [...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtcxcmwhed.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtalpgkbsn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yuxming.cn/Article/details/gtlmizoatx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jqgufenzy.top/Article/details/gtspktvssz.html

Ruby: arr.uniq
来源：http://dali.ppjwa.cn/Article/details/gtbdjduuke.html

C#:   list.Distinct().ToList()
来源：http://dali.havefunace.top/Article/details/gtcjfebcvv.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gtkaavlblm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjtigbfm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtcalzjecz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hnqzz.top/Article/details/gtgxveohjb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.xuetiantiany.cn/Article/details/gthwuuyhqv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.kuanghao11.cn/Article/details/gtthroluuj.html

Go:   // 手写循环累加
来源：http://dali.guowangkeji.top/Article/details/gtrslotajo.html


<!-- 参考信息 -->