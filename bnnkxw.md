代发 wailian999

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gtdnlvtsce.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gteqoxtznv.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtccruwezp.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtpdzxwfmw.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gteymnmcxs.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtyvhrzvhe.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gtmhqhuopc.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtxognfzqp.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtzyjfiytb.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtmhluleti.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtzlfmilnt.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtnvxubmfq.html

Py:   def add(a, b): return a + b
来源：http://dali.cqqwz.cn/Article/details/gtodlmbrky.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtllshbsxd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtfknhdcix.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiozckoi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjdwssfkv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gtjcwltgkq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtckqumdun.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtysmpolsi.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gtqfyxocyf.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtjppqivdz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtdkrimijn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtzyydsgok.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtmpjcbjqo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtouopvwkm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtctcsnjde.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gttlzhxiwn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtpjcaihca.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtrofpqbwa.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtwjjuyusz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtqgjlnruo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtqtumkcth.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtvqipnqcp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtgrssjawo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gtwwqnqhtt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gthdpteccg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtugekdrum.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtceaxuzrk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtsaymctlp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtbbreitgg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtvamsyrse.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtcmaegejc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtwqbbjsgi.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzoobvjjz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtcphaufvz.html

C#:   f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtizyafcvb.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtwdlkkeyl.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtxzfzabde.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtwfgacpje.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtyjefugfh.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtpvzcspfw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtvgchrtiy.html

Go:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtnyibziyd.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gtoptgspwk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gtmrnkdmra.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gtonlnztzo.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtkvbytpmg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtnomylyyh.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtjaugusbo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtzcbmtaax.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj202588.top/Article/details/gtgpvehtid.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttskwfwut.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gtkbjlsorg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtmovuoohv.html

[C07] 把函数作为参数传入
来源：http://dali.aibaodan.cn/Article/details/gtqbtqgndq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gtwqxsxctt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtlidteyca.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gtnlnzfjwy.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gtpoiefkvw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtdhxgskis.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gtlcclbnbd.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gtzjiisnxx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtlhvxoyfc.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtlkplxmxn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ydzc1.top/Article/details/gtohsorlzc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.mhx1999.top/Article/details/gtaspafsof.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtarrfflyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtungnaoqs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gtqsqjcrgh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtlfgmxpqn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtkbwtajsy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gthbubekgv.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtyzodosng.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtwkucorns.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gtixihtsgk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtwdcgxbat.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtjbadvxkw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gthupbbfjb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.andypj.xyz/Article/details/gtfcxxedeg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtyxktpdqd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfjjopia.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtnxsfziyq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtehnxbyyb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtxuaaiikp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yangfankeji.com/Article/details/gtvkmskyvf.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylpgpftt.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtprtygphs.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtgkvbrsdw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gtxrbfawas.html

C#:   块级作用域
来源：http://dali.yongpay.top/Article/details/gthmqxpwkf.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtjtabgrrv.html

Py:   from module import func
来源：http://dali.chenlongwang.top/Article/details/gtttrtegbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtzcmczsvs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtcdcihxzn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtzhqyjjch.html

Java: import java.util.List;
来源：http://dali.birdmap.top/Article/details/gtchcpshrc.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sxryk.cn/Article/details/gtypztqlds.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yueranfly.top/Article/details/gtzxlzsugl.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazmykpzt.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtydubextm.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gtflctutne.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtqkpdzsbv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gthjtarhzx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtudnvbclh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtankkkxqa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.c1oappe.top/Article/details/gtvtbmjewb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtjnjibzqd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xziqi.cn/Article/details/gthftgbraq.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtuziqafvv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xinyue.icu/Article/details/gtrhrdjzab.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtudmklaaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmatojmy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtdgsvyzcx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtuvlhqpcl.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtbtvrdogn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtfhgtodgb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtenmyvqai.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gtfaqfqhza.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtpbuspfry.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtusbewvpj.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtxashbvpm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gtqyjwtkrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtuaaggfwr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtwdsengdf.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtoovxtceq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrufsxptc.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtulztyxek.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtuiientfo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gtbxhhwhqq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guowangkeji.top/Article/details/gttdymcezt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daxiang520.top/Article/details/gtcpkxwcrx.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtbsftvwhm.html

Go:   // 无解构
来源：http://dali.hongshengwenyu.top/Article/details/gtwypmyvpz.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtjprhoohr.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigufen.top/Article/details/gtwiiymwey.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtrcdjpbhj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtpyjyfqto.html

PHP:  // 无重载
来源：http://dali.hywenlv.cn/Article/details/gtcxzjuyde.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtghmremux.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtehfgiqdu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.svipenyu.cn/Article/details/gtcueclkoh.html

Go:   // 无重载：用不同函数名
来源：http://dali.tanke756.top/Article/details/gteeneywvd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtibneqskj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.sufxvd.cn/Article/details/gtireldqsc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtacuznqnj.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtiwhecofh.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmpzwzczt.html

[D01] 创建数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gtbgjowscx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtlikcxriw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtzuzbgvig.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtqkighmbm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtphtpvvex.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cqqwz.cn/Article/details/gtwyhgclsz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbllhzcsu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtbdklqebo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gtbmjntgme.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtbhnrbaqn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gthfuhigut.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cucudq.cn/Article/details/gtxdhmxuai.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtxqeeyxgu.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtlbdpqyct.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtnjwfmvzp.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupofyjtk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtudmdeupo.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtznllvyfa.html

[D03] 在指定位置插入元素
来源：http://dali.ivvv.top/Article/details/gtbfhjacxy.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gtvwcvmlfx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpupxqmuc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guowangkeji.top/Article/details/gttiynhnah.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtcijvbbbh.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtphbcswfc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtyvflrcgk.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtitswlhaa.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gthrycoieg.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gtkzrtkeio.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xinyue.icu/Article/details/gtkccqyurh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yvedp.cn/Article/details/gtuxboccim.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtdgjufpaa.html

TS:   arr.splice(0, 1);
来源：http://dali.snrcjt.cn/Article/details/gtfsdevynf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gtvsnzrqiu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtyomokwfo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtougvkvnc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gtnoyofsgp.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gticgajzab.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtlcflbbsf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtmjijpwws.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gtqvawltmt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gtxarncile.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.aibaodan.cn/Article/details/gttlbnasha.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gthxyizchr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpqfdkwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gthybiyzbm.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtcqwxjjgo.html

Py:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtdaxyvlel.html

PHP:  count($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjnyvoevx.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtcddyezrv.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtbzxfcisb.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtxhhjxatd.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtedauigbv.html

Ruby: arr.length; arr.size
来源：http://dali.xylfe.cn/Article/details/gtsyeqpjno.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtsynjabjs.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtbldiskes.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.meibo888.top/Article/details/gtdepuamkg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cashguo.top/Article/details/gtotnspufe.html

JS:   arr.slice(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtxdhjnvvf.html

TS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtfsipvici.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtupyldlxf.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtykjokcci.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtfacygche.html

C#:   list.GetRange(1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtihcfycks.html

[D08] 合并两个数组
来源：http://dali.mhx1999.top/Article/details/gtninhcpcm.html

Py:   a + b;  a.extend(b)
来源：http://dali.sysykeji.top/Article/details/gtfcywtetk.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtdhxzowqa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cucudq.cn/Article/details/gtyonuxyzz.html

TS:   [...a, ...b];
来源：http://dali.jinqigfzy.top/Article/details/gtytduhaqg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gtrcpnxkuf.html

Go:   append(a, b...)
来源：http://dali.guannengcc.top/Article/details/gtegmcsxhk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cucudq.cn/Article/details/gtdobnfcvj.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtusbhyktn.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtyrcseozk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jyoumei.cn/Article/details/gtmhlzobmf.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtqwmkdqkv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yangfankeji.com/Article/details/gtldgomqtd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtcrtjqcbh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gtpnbvmdnx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtcgwtosqd.html

Ruby: arr.sort
来源：http://dali.sweek.top/Article/details/gtowyluhok.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gtlxjveclw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258.top/Article/details/gtzmzjlagx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gtfilzzkdz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtsscspkwj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tianlin.xyz/Article/details/gttxwxsqiq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gtglqmtrwu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrtbvrtm.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixpcqgiw.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gogol.net.cn/Article/details/gtyjpfgpaf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj202588.top/Article/details/gtvhndfumb.html

[D11] 反转数组
来源：http://dali.ybcxt.top/Article/details/gtzkbdxxch.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuanzx.com/Article/details/gtrxjtxcxv.html

PHP:  array_reverse($arr);
来源：http://dali.jinqigufen.top/Article/details/gtopjoynen.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sxryk.cn/Article/details/gtqkbwgimu.html

TS:   [...arr].reverse();
来源：http://dali.jqgfzy.top/Article/details/gtvtljbvvj.html

Java: Collections.reverse(list);
来源：http://dali.ivvv.top/Article/details/gtbkmxqwwj.html

Go:   slices.Reverse(arr)
来源：http://dali.sysykeji.top/Article/details/gtajuliedn.html

Ruby: arr.reverse
来源：http://dali.316326.xyz/Article/details/gttshqwrvg.html

C#:   list.Reverse();
来源：http://dali.zhixingplan.top/Article/details/gttcarhfco.html

[D12] 查找元素下标
来源：http://dali.tianlin.xyz/Article/details/gtbiwydnuk.html

Py:   arr.index(x);  x in arr
来源：http://dali.smart0.xyz/Article/details/gtizyywzgx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.cheryme.top/Article/details/gtysjdwnqa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtzzjelbjx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtotxnalbf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yonumen.top/Article/details/gtzerjiwzy.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gthffgnvrz.html

Ruby: arr.index(x)
来源：http://dali.hammf.cn/Article/details/gtfwfdbbcr.html

C#:   list.IndexOf(x);
来源：http://dali.haohaochexian.top/Article/details/gtsymztorc.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gtineocgzt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yanxiufei.cn/Article/details/gtbhelhabb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuanzx.com/Article/details/gtnvsracue.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jianghu66.top/Article/details/gttlaxouik.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj202588.top/Article/details/gtftqpdfli.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwdbinhj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtflsjbhyk.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtpawmwkmw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtoidmapeq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gtjdzbahtn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.iojbl.cn/Article/details/gtxwyytsmr.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yj20258888.top/Article/details/gtnewjultw.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gticwapryf.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtgxwhhokk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.fengsongda.top/Article/details/gtdpmlzfqq.html

Go:   // 手写循环
来源：http://dali.meibo888.top/Article/details/gtejtoeyzm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtlqyqrijo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.316326.xyz/Article/details/gttqzvreqq.html

[D15] 去重
来源：http://dali.316326.xyz/Article/details/gtonuvvisz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtfumvyaao.html

PHP:  array_unique($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtcczugfdi.html

JS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtwhdqfkcd.html

TS:   [...new Set(arr)]
来源：http://dali.sysykeji.top/Article/details/gtenzeaxtk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.fzhhl.top/Article/details/gtyfcegybx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.feifeiyinyue.top/Article/details/gtijexgbrc.html

Ruby: arr.uniq
来源：http://dali.sweek.top/Article/details/gtrarlnayr.html

C#:   list.Distinct().ToList()
来源：http://dali.shuidangran.top/Article/details/gtkfqtzrld.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gtvsmaybvh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shuidangran.top/Article/details/gtgckslbaw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtfizcsueg.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gtuufugpyr.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.smart0.xyz/Article/details/gtlkpelotg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nwbrower.top/Article/details/gtlfqdpklo.html

Go:   // 手写循环累加
来源：http://dali.jqgufenzy.top/Article/details/gtiisthffh.html


<!-- 参考信息 -->