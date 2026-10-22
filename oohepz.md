代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtjnqpvupu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtunkriosc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtdscadtmj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gthobnymkk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtxaodrpyb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtaldsewcj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtloypgrac.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gthehvabyx.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtzfwffdsx.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtzavkfveu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.quarkkingdee.top/Article/details/gtlejjycqd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtelmgvjbs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtmnyciskl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtvppqysrs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxuanxn.top/Article/details/gtiphordbh.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrmkqyqo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtlmixchxq.html

[C03] 可变参数
来源：http://dali.hfpthk.cn/Article/details/gtxbltpecc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtrscxeigr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtamwbgrbn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtyyhgosii.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtorcopzqv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtzoxwdbyz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtpipbbzoi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shzxlz.cn/Article/details/gtxkziindt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtnopbygbl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gtynxmxbky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtrjonrizc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gtqpckanrf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtwfcsnzmb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtbgnbxnej.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgjthuvv.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtkfdoupjk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtuuoqozha.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtguspxcgp.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtfjabzdeq.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjwgymgxe.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtfjnkthlo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtpcwaqdcv.html

TS:   return { a, b };
来源：http://dali.zhixingplan.top/Article/details/gtswfuufjr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gthaapapow.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtgjkybeau.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtnfttrror.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojubsgmq.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtyoxlnntt.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtcgkihlni.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sufxvd.cn/Article/details/gtujyzmlgt.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobdqlipx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtnmbqaewc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gttpxvvtdj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtlzlecgsj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtkepfujfq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtkndyniut.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gtnrutwmye.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtjgypsawh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtfetbpkjt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gttnoyaxpo.html

TS:   arr.map(String)
来源：http://dali.quarkkingdee.top/Article/details/gticioshrp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtbqxhapgj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtovdcjufd.html

Ruby: arr.map(&:upcase)
来源：http://dali.pengpengdd.cyou/Article/details/gtimlquqbs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gtylrtfoqu.html

[C08] 闭包
来源：http://dali.hammf.cn/Article/details/gtzemhzoab.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yonumen.top/Article/details/gtlrtntixx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gteeqcrlwf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtezejvuum.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtokqyukmn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gtvufmymry.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtuzdbsoce.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtzgwxhglj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtttmyijbi.html

[C09] 递归
来源：http://dali.pengpengdd.cyou/Article/details/gtxbpjpiuo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtlqlboeti.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gthnsblcpd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtcvfwsmuc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gtonzghcvq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtcpesmuil.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gttbmiwhoj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtspihkjjs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtjuprkuvj.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gtnivxcsvn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gteacgoxgr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zdqjudy.top/Article/details/gtxtniesoz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtepanotrg.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtdktbfrvy.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtlrwqolck.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtfnbsyabw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.snrcjt.cn/Article/details/gttzwqvzpu.html

C#:   块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtkguwnlks.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtzwdbnbel.html

Py:   from module import func
来源：http://dali.aizwys.cn/Article/details/gtppngdywx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigfzy.top/Article/details/gtshqypitu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtpfxbxjhw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtgoypqart.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtjwlgfnae.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtmgdevjch.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtsfbtevlt.html

C#:   using System.Text;
来源：http://dali.yonumen.top/Article/details/gtklgfampn.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gttmqeqsnx.html

Py:   (lambda: print("run"))()
来源：http://dali.316326.xyz/Article/details/gtyvcbkseb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgufenzy.top/Article/details/gtcthkirbl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtxbuuuvmb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gtaymoeynd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtlercwsjz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtcegxmggm.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtixwrmomj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtbievsdah.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtgsawupqx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtanutnriu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtwgxvokun.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuanzhike.top/Article/details/gtvcdiiwfp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjbodzdgm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gthpsprfqr.html

Go:   func add(a, b int) int
来源：http://dali.sweek.top/Article/details/gtguopbfii.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fengsongda.top/Article/details/gttoggkqrf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gtkrwnjeem.html

[C14] 泛型函数
来源：http://dali.kuanghao11.cn/Article/details/gtigqjzjhb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gtoynhdzyo.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtbwznqpos.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtauonqcde.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnxiangtu.top/Article/details/gtjrlxjlvr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gtixznxyxb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shuidangran.top/Article/details/gtpfaomvnu.html

Ruby: # 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtwareoyjg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gtgysltifn.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtoeubivop.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajedriwd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gtcodeqxgk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtureqkqig.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtoitnwqwq.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtdluyxjnt.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtaunfscvd.html

Ruby: a, b = pair
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjolzujm.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtfeorfgdr.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtohkyffpv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daxiang520.top/Article/details/gtzkahncnd.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtokpcsfds.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtjfigapll.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyzbztoud.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtjzisawcn.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtmsnshmaa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aizwys.cn/Article/details/gtqywkpvpx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtqhjklzgk.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtpqyqojte.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gthjerrnic.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtikzluiul.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gthgrezetr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtliomfveu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtqgmrrrmg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtxjuwhkyx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gtusbhjbhd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtluketsoz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtqbbjfylm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtwnindloe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gotoacloud.top/Article/details/gtjbjvmrjf.html

[D02] 追加元素到末尾
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgevakhel.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtymuqcwol.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tanke756.top/Article/details/gtcjkyxteu.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqbdpbqus.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtowkxjhqf.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtcunarkns.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtlbxzkjlw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.fengsongda.top/Article/details/gthwbbrfbr.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwztuhoxy.html

[D03] 在指定位置插入元素
来源：http://dali.yangfankeji.com/Article/details/gtzwmlqtsd.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtksspjnym.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtfnjkkbzb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtwgrlwhqn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gttezlygmt.html

Java: list.add(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtdgqkmqpr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhixingplan.top/Article/details/gtzekanxct.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtrnxmwyaw.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtvkdmzaha.html

[D04] 删除元素
来源：http://dali.jqgfzy.top/Article/details/gtaypmzhto.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzaixeqa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.9152youxi.cn/Article/details/gthjnhntob.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtvssnqbci.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtcyfviquv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gtzfybsxvw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangdashe.top/Article/details/gtjxvpvdzr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangtech.top/Article/details/gthojhiquh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pycfn.com/Article/details/gtmsspthzp.html

[D05] 访问与修改元素
来源：http://dali.shuidangran.top/Article/details/gtmndhfftb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtweqkopsr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gttkhucook.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtznpjtkwm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtdewzctyz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtemosbziw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtcuulczxi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqtaeuzw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtfftdrvoo.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gtwhmmluks.html

Py:   len(arr)
来源：http://dali.jinqigfzy.top/Article/details/gtkltreupw.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gtaxkyvayp.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtnhebkxwk.html

TS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtaobdprhx.html

Java: list.size();
来源：http://dali.cqqwz.cn/Article/details/gtjkhctram.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtctrsiiuf.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtwnikfqpj.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtbryoeaxd.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gtxiahqkad.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtpjnrxdre.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yangfankeji.com/Article/details/gtcjbvmrfk.html

JS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gtdwzibkmw.html

TS:   arr.slice(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtuwxdixpt.html

Java: list.subList(1, 4);
来源：http://dali.316326.xyz/Article/details/gtytlvtgit.html

Go:   arr[1:4]
来源：http://dali.snrcjt.cn/Article/details/gtwotszkou.html

Ruby: arr[1, 3]
来源：http://dali.ivvv.top/Article/details/gtayydflzk.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtaaclscpu.html

[D08] 合并两个数组
来源：http://dali.snrcjt.cn/Article/details/gtzozjptbo.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvyuxjgxj.html

PHP:  array_merge($a, $b);
来源：http://dali.ehwqpu.com/Article/details/gtxrrohglr.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.bjfxy.top/Article/details/gtclwyxbiz.html

TS:   [...a, ...b];
来源：http://dali.wangdashe.top/Article/details/gtjktskgmu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtxajwxmxn.html

Go:   append(a, b...)
来源：http://dali.zhoulong.xyz/Article/details/gtlyuoecki.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nanxinkj.top/Article/details/gtlxkwikuf.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtcjzojjqw.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtpbpekser.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtkpocmjng.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtljfbvnnq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj20258888.top/Article/details/gtrqvhvpov.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjjzsamb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtycmpawku.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gtitloqtdg.html

Ruby: arr.sort
来源：http://dali.gotoacloud.top/Article/details/gtkeqqmtxy.html

C#:   list.Sort();
来源：http://dali.andypj.xyz/Article/details/gtuswxuhcw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.wangshuangyany.cn/Article/details/gtckzegwjs.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtfarnbwrq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtioxdjkxi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtfojjnetb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtfubzrviz.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hywenlv.cn/Article/details/gtguzdahzr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yj20258.top/Article/details/gtzomnmddh.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.aizwys.cn/Article/details/gtwvzjpvmq.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtwueuvjkg.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtojxhaquc.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtpwyheoao.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gttptqpuns.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.gogol.net.cn/Article/details/gtftgalxgo.html

TS:   [...arr].reverse();
来源：http://dali.zhongyouzk.top/Article/details/gtklopmrna.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtphreknea.html

Go:   slices.Reverse(arr)
来源：http://dali.smart0.xyz/Article/details/gtifexnlug.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtawjtcamf.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtvpckskre.html

[D12] 查找元素下标
来源：http://dali.jianghu66.top/Article/details/gtacvxpcyv.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gtarezakei.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtcsawtlwc.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtjuvwxlpu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtqfnymclo.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwitawqdw.html

Go:   slices.Index(arr, x)
来源：http://dali.meibo888.top/Article/details/gtpebjhoig.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtghtpakwq.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtfbypzwhg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinghuilouyu.cn/Article/details/gtaojioyjo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zhongyouzk.top/Article/details/gtsxxwbwgr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyvglpgnl.html

JS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtivvxwiir.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtcotqenqe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtoitwikyc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtwyapmllt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtawucqhwm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jqgfzy.top/Article/details/gtbcqubhdq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xziqi.cn/Article/details/gtdzkyhhhf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jiagoushi.top/Article/details/gtofkpyyzo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.dashuyun.cn/Article/details/gtocfpfixp.html

JS:   arr.map(x => x * 2)
来源：http://dali.hnqzz.top/Article/details/gtxhtcasup.html

TS:   arr.map(x => x * 2)
来源：http://dali.jqgfzy.top/Article/details/gtqvuhgnxl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtczrjciio.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gtquosojgk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtxeamcvet.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtugotxzcw.html

[D15] 去重
来源：http://dali.shzxlz.cn/Article/details/gttskvyqpt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.feifeiyinyue.top/Article/details/gtsxkdlnmn.html

PHP:  array_unique($arr);
来源：http://dali.pycfn.com/Article/details/gtzqfjmnxd.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gtgyojdqfk.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gtjfnhrimh.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.quarkkingdee.top/Article/details/gtpgfssjbd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yongpay.top/Article/details/gtfeapfggj.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gtfcqvwxbo.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtdjigllqb.html

[D16] 求和与平均值
来源：http://dali.yonumen.top/Article/details/gtijtyodah.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtwikxcdvx.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.kuanghao11.cn/Article/details/gttfzpyrim.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daxiang520.top/Article/details/gtoqsnogpe.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gtccjmkemn.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtwsqjcunm.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gtzrgehqeo.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrywdvwl.html

C#:   list.Sum();  list.Average()
来源：http://dali.ehwqpu.com/Article/details/gtskmtghlx.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gtufvjbiwb.html

Py:   max(arr);  min(arr)
来源：http://dali.sxryk.cn/Article/details/gtlnaysjbg.html

PHP:  max($arr);  min($arr);
来源：http://dali.wangdashe.top/Article/details/gtftzqfniu.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.redwolf501.top/Article/details/gtfylwngkx.html

TS:   Math.max(...arr);
来源：http://dali.jiagoushi.top/Article/details/gtdqygqbrc.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtqvxberzc.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.aibaodan.cn/Article/details/gtzpthting.html

Ruby: arr.max;  arr.min
来源：http://dali.mhx1999.top/Article/details/gtwaqrfsuj.html

C#:   list.Max();  list.Min()
来源：http://dali.yj20258888.top/Article/details/gtlarzzywr.html

[D18] 扁平化嵌套数组
来源：http://dali.zhengqikj.top/Article/details/gtyttpgogs.html


<!-- 参考信息 -->