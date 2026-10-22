代发 wailian999

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtetqqukav.html

Ruby: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtlnyuuwpy.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtvcrwpuvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtztzidjcj.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gtwytbicls.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcdtutjdt.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtrhcdqdyp.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtqvithvfz.html

Java: if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gtflpulbgo.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtmagczkdy.html

Ruby: return if data.nil?
来源：http://dali.chenlongwang.top/Article/details/gtqrhlxezq.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtoikbbesi.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthzhjaodn.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gtuxpkxzvg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtjrvvuefm.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtymrxamhf.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gtzjwtocnt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtyndbmttq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtdsezqpus.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtffosacjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtugnxjpel.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gtotgckyje.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gtdnirhfth.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtcithubwu.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtefiimtch.html

Py:   def greet(name="World"): return name
来源：http://dali.yongpay.top/Article/details/gthpjrwdgt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daxiang520.top/Article/details/gtrxqsifks.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyatpctx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gtjuqyyiaq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtzdcllyou.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtscbrnctb.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtpqkqrkpi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtmyxnztes.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtmmjfuyjr.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtxnmeyrqd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtsfkgjihf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtvhqzvomj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsquwgods.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtcdoywcig.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtcnhsfsiw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zycfv.cn/Article/details/gtpaqrenli.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtwszpiprs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fzhhl.top/Article/details/gtkeawsobm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtzrfuikmy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtwxnoiwtc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtjjkcreyx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnqzz.top/Article/details/gttfkzifam.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtuwemeqxo.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxinkj.top/Article/details/gtgqluciwe.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gthxfehvrz.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtqvtucdya.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtxuenhwzh.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtejdwkbfi.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtwgtnween.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcdmcdsz.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gthxauxojp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gtrxifpbvs.html

Go:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtepwblyct.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtaklrkqkn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guannengcc.top/Article/details/gthevhmqih.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtmvodyltm.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtetqbaook.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenlongwang.top/Article/details/gtjcgmacvk.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtuppuzxmh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gtsokkttgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtwdlpcrzg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtrlcehxnf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtwwuosxpw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtiyijpxac.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtjwplklwu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtfptxilmp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtzoidnvwg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gttxvjwdff.html

TS:   arr.map(String)
来源：http://dali.tian-w.cn/Article/details/gtzrrttdkx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtnlivbwsr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gtguthnyai.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtmybqydfo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnxiangtu.top/Article/details/gtxccyscoh.html

[C08] 闭包
来源：http://dali.xuanzx.com/Article/details/gtvuxznipc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtjmlhnghb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hfpthk.cn/Article/details/gtaaokiiwy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtiabszoxh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtmzjkit.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeypxqfe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cucudq.cn/Article/details/gtpnupxmch.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guowangkeji.top/Article/details/gtjheaipgp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtcypsowte.html

[C09] 递归
来源：http://dali.dashuyun.cn/Article/details/gtocvptjvi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtgmppbyxh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtsqjjpfqy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gteokzsese.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gtapdnbcpn.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtimxaonxm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnqzz.top/Article/details/gtiyxotszs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtshmbwbev.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtuafplwdn.html

[C10] 变量作用域
来源：http://dali.birdmap.top/Article/details/gtyomihetm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.birdmap.top/Article/details/gtsiiyxsjn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gtrpnsqwfu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gzhubu.top/Article/details/gtlejvcydp.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtasfyihar.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtcrjyymla.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtzojdvwgv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtjebvtonz.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtkfkzwbls.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtotjffvts.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtgjxfwayc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gtiguiktur.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtrjgvhemv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gotoacloud.top/Article/details/gtahvasczh.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gtzejzkxuv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gtcbpdkyvh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yanxiufei.cn/Article/details/gtwcwpviha.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gtifrgoeyy.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtpwgotubg.html

Py:   (lambda: print("run"))()
来源：http://dali.guannengcc.top/Article/details/gthvsyjuhk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtfytznezo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gtoxnvahza.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtulvxxnij.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gaohongyu789.top/Article/details/gtzlmwtiuz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.iojbl.cn/Article/details/gtlrdpewdl.html

Ruby: -> { puts "run" }.call
来源：http://dali.andypj.xyz/Article/details/gttdvlddhn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuanzx.com/Article/details/gtlgbywpae.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtzsjemfwg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnxiangtu.top/Article/details/gtklacstyg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtnhhmjtyr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtzfcixhul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtagunclzd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtstixbyto.html

Go:   func add(a, b int) int
来源：http://dali.gotoacloud.top/Article/details/gttqdypjce.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtpbmuxtdd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtuusyemnu.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtezluvtbq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtlegdhyls.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtilxwowkm.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtedpvtebn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtquymhwyd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gthcygtful.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.andypj.xyz/Article/details/gtvambmxpk.html

Ruby: # 无泛型
来源：http://dali.xinyue.icu/Article/details/gtvmnkwmgz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtecunkegy.html

[C15] 解构 / 展开参数
来源：http://dali.sysykeji.top/Article/details/gtglzegadi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtcwrxqvel.html

PHP:  [$a, $b] = $pair;
来源：http://dali.redwolf501.top/Article/details/gtpijfgneb.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvhignek.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtcbzezibh.html

Java: // 无解构
来源：http://dali.cashguo.top/Article/details/gtqfgltkfj.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtzbzjqdtg.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtzwnmwzxe.html

C#:   var (a, b) = pair;
来源：http://dali.cashguo.top/Article/details/gtagldbpsz.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gtvimsvqpj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtygnfrdyp.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gtttbksqlj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gtvadsqpyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gtmtpsbjbf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtlylkcjjk.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtlojcyhwg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xuetiantiany.cn/Article/details/gtpopxqaqa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcoefejmo.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtqqmxmzbu.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtcvpvwvjg.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtiqpwpoxc.html

[D01] 创建数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtooksbyov.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gzhubu.top/Article/details/gthkxpxcjj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtskfsbgtd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gtoomibssw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.dianchejie.cn/Article/details/gtvsyaoggo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtlthcmmjr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtkdljvabe.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhybxptr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtsyeavdyk.html

[D02] 追加元素到末尾
来源：http://dali.hongshengwenyu.top/Article/details/gtjkkfzvkc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yuanzhike.top/Article/details/gthbzuwtyr.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.vqdsnc.cn/Article/details/gtkvcacqxy.html

JS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlrjdcqxc.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gthnnxtona.html

Java: list.add(4);
来源：http://dali.cqqwz.cn/Article/details/gtkldocnnk.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtktdlxazp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtmksvxvfp.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtgdwirvwt.html

[D03] 在指定位置插入元素
来源：http://dali.sufxvd.cn/Article/details/gtcdovrbfy.html

Py:   arr.insert(0, 0)
来源：http://dali.gotoacloud.top/Article/details/gtwrbgilpa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtisqblkjd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtpawkwcue.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtubzeiycd.html

Java: list.add(0, 0);
来源：http://dali.hammf.cn/Article/details/gtmcuyvqdi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gtouxsdkje.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gtzlukmquj.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovwuiabw.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtsvpmyisn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxuanxn.top/Article/details/gtaycnbiqs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtqaiwucgd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yueranfly.top/Article/details/gtcwyqgzyh.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gtafkbmrqy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtlrbsekmi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtthxrfzpr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinqigufen.top/Article/details/gtqrzaxpjn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtuaahvsvj.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtwenmryoc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtzcuqgjtn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gtmzkxrxjv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtizjitffu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtuixdypol.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtnvxhvgqm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtebmmimop.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtoopngacn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtebydvefb.html

[D06] 数组长度
来源：http://dali.c1oappe.top/Article/details/gtxvrdsjiz.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtgkpggqjq.html

PHP:  count($arr);
来源：http://dali.hywenlv.cn/Article/details/gtizqozpfx.html

JS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gtrdlwhltu.html

TS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtjtnshwww.html

Java: list.size();
来源：http://dali.zdqjudy.top/Article/details/gtpfypmzpj.html

Go:   len(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtomsknbpd.html

Ruby: arr.length; arr.size
来源：http://dali.yangfankeji.com/Article/details/gtaqzdbssf.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtranbjaee.html

[D07] 切片 / 取子数组
来源：http://dali.quarkkingdee.top/Article/details/gtpnanynrx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.iojbl.cn/Article/details/gtbqyxzquk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtfzynmqzo.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtmsrglgye.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtgawxcteq.html

Java: list.subList(1, 4);
来源：http://dali.zdqjudy.top/Article/details/gtejfhwchq.html

Go:   arr[1:4]
来源：http://dali.guannengcc.top/Article/details/gtodwfkbmu.html

Ruby: arr[1, 3]
来源：http://dali.hfpthk.cn/Article/details/gtsokzspnb.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gttonykqot.html

[D08] 合并两个数组
来源：http://dali.hysaishi.cn/Article/details/gthzjvsnjn.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtkrhzqzub.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtaglsztge.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gtejnyhyxd.html

TS:   [...a, ...b];
来源：http://dali.yj202588.top/Article/details/gttvekvaxv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fzhhl.top/Article/details/gtblkfxiuf.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gttveswblm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtrrfslwsm.html

C#:   a.Concat(b).ToList()
来源：http://dali.dianchejie.cn/Article/details/gthhvhbwtn.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtgfwckilc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.feifeiyinyue.top/Article/details/gtxhatvcec.html

PHP:  sort($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtvijtpfbu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.gogol.net.cn/Article/details/gtsgculwmz.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtudsrldgx.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xuetiantiany.cn/Article/details/gtnhhaogdn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gtkgwkjqip.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gtsbgcqgay.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtczcotenn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtnkvhlbtq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhengqikj.top/Article/details/gtjszldven.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yanxiufei.cn/Article/details/gtvypobjgc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtqkefpywz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtlnkoofpq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ydzc1.top/Article/details/gteuwlczdj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gthcsspfvx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gtqwhkrzfy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhiwuduotai.top/Article/details/gtodxreicx.html

[D11] 反转数组
来源：http://dali.iojbl.cn/Article/details/gtihoihmip.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.nanxinkj.top/Article/details/gtajmyxgbo.html

PHP:  array_reverse($arr);
来源：http://dali.jianghu66.top/Article/details/gtujntflbz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.birdmap.top/Article/details/gtkdesaohi.html

TS:   [...arr].reverse();
来源：http://dali.guannengcc.top/Article/details/gtjxeuvfwd.html

Java: Collections.reverse(list);
来源：http://dali.xinyue.icu/Article/details/gtjviheypk.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtkjwsgrnz.html

Ruby: arr.reverse
来源：http://dali.jyoumei.cn/Article/details/gtzfzspibf.html

C#:   list.Reverse();
来源：http://dali.zhoulong.xyz/Article/details/gtkuptjioz.html

[D12] 查找元素下标
来源：http://dali.tian-w.cn/Article/details/gtmcpebpol.html

Py:   arr.index(x);  x in arr
来源：http://dali.ppjwa.cn/Article/details/gthjdfvpfq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpxsiagmt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtvpbevcxc.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangdashe.top/Article/details/gttowjflzj.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtdwxpccjl.html

Go:   slices.Index(arr, x)
来源：http://dali.cdnleiting.top/Article/details/gtyjdofbfr.html

Ruby: arr.index(x)
来源：http://dali.redwolf501.top/Article/details/gtuusqzsbh.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtxwjqtxrn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xziqi.cn/Article/details/gtayyrswat.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.316326.xyz/Article/details/gtukuykbbx.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.mhx1999.top/Article/details/gtxwagcclr.html

JS:   arr.filter(x => x > 3)
来源：http://dali.havefunace.top/Article/details/gtrmfvdjef.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ehwqpu.com/Article/details/gtwamwmlqo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtnmjsweae.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gotoacloud.top/Article/details/gtpkqewaku.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdldrkxer.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtkrbhgmjl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sxryk.cn/Article/details/gtegvbvoby.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xinyue.icu/Article/details/gtioogrkjs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.0kj1m.cn/Article/details/gtmzzgsvna.html

JS:   arr.map(x => x * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtxowavxqk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yvedp.cn/Article/details/gthjyvgqae.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjrjccum.html

Go:   // 手写循环
来源：http://dali.gotoacloud.top/Article/details/gtcquttemv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohsuqhvo.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtzxwgtiid.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtmxhdlzih.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtkgxqqyre.html

PHP:  array_unique($arr);
来源：http://dali.ydzc1.top/Article/details/gtmifugfxb.html

JS:   [...new Set(arr)]
来源：http://dali.gotoacloud.top/Article/details/gtypbgjhgh.html

TS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngwtuqem.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gtzjiwsqbc.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gtrrbmhmdw.html

Ruby: arr.uniq
来源：http://dali.bjfxy.top/Article/details/gtnfszhpnn.html

C#:   list.Distinct().ToList()
来源：http://dali.xinyue.icu/Article/details/gtuwqmsweu.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtllriedar.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdomhyjkt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtwqsvwoea.html


<!-- 参考信息 -->