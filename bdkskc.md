代发 wailian999

Java: if (data == null) return;
来源：http://dali.snrcjt.cn/Article/details/gtbducbwev.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtwgsrtjfm.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gtjrnkacqe.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmcizrav.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtwqajqagp.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtzptlwhgs.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtewvaoyln.html

[C01] 定义函数
来源：http://dali.redwolf501.top/Article/details/gttfjemqvq.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtemogfhaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtnfthcfjb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtixodznjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gturopagyz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtbvrdbcdb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtrobmttoo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gtrascmkhs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtjlfgagmd.html

[C02] 默认参数
来源：http://dali.sysykeji.top/Article/details/gtgjhevpnv.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwxwjtqz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtimuiszcz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtoqgorlep.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gthybizocj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtsmrprtru.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtdfqofpkf.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtqqvcviuq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gtpewnognq.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtrtksexpi.html

Py:   def total(*args): return sum(args)
来源：http://dali.smart0.xyz/Article/details/gtvxdfvpju.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gtrrekfgig.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtziiivfzl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtnvgpfxyx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtwnxjmgpw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtazwazvij.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gtgwlpiloc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtxfjmdovy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gtuijnkmhh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtadharrwq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtwxerbbhg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotnlbqgx.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yongpay.top/Article/details/gtdazbqhpw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhoulong.xyz/Article/details/gtkosikask.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtdrpznobj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtqwplvais.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtjrmioexe.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtuhdspiuz.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtybnvtpln.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtpvoznzgw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtabfrolya.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtuzwnhyou.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gtqccwoqtn.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtpxnvwjdb.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtdihomrvp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtmudaxdrx.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtiilgawof.html

Py:   square = lambda x: x * x
来源：http://dali.shuidangran.top/Article/details/gtnbgbqnty.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtuuzitmhq.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gttctzxwhq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtrskmaihq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ppjwa.cn/Article/details/gtidastayv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtlbtpbkva.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gteavneoje.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtopnkifqg.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtocqfhagp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtgoqismlj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtopjxeuvc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtuaoemzpd.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtlxnvahjo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtltwgdklw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtttwnglsm.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gtmfqyajpj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gttzrrieto.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtveineuem.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuxming.cn/Article/details/gtirbrvzhw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gtosobtvfo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gogol.net.cn/Article/details/gtirdzblzi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtnyjrtuui.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtsreqptmb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtutompmvc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuxming.cn/Article/details/gtwyonheol.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gteyxrdvfi.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gtfifpsycj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtygcimbif.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtcpprxlzb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtccymjjzl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtodbpoliy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtraqdkkff.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sweek.top/Article/details/gtcmhobrle.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtsleirwgm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtbpcaukht.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtfhkzwdof.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtmbkmklve.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ivvv.top/Article/details/gtbcqblqjx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhixingplan.top/Article/details/gtugrsjdhn.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gtkghzokxz.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtoltzdxhk.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtzkkkpimm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtjpbfpjaw.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtlqkoxuyy.html

[C11] 模块导入与导出
来源：http://dali.shanyushiyangtech.top/Article/details/gtiruruzmi.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtcnueojho.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gtwcddpxro.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtmclwknym.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtuaovedct.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gthfpyasat.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtkomnfobh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtgugtmrwd.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gtzetiihzg.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gttcnhijku.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtdubmzclt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtuwmdjnng.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtfgbuatdk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtyiqeoxqv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtipoguxue.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtowqreqpd.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtvvgpjvol.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtnsxgkcpe.html

[C13] 类型声明 / 类型注解
来源：http://dali.kuanghao11.cn/Article/details/gtdqjfbekt.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dianchejie.cn/Article/details/gtikgqgzpa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtrsbdwauv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nwbrower.top/Article/details/gtnemvfhzl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gttozrixgj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtjhvvpugl.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtvpsncnjs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtjozerkny.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.aizwys.cn/Article/details/gtvnmwkvjj.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtbvrcckkn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtzkplsvrh.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtmcccfwex.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtjzpzppmb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtuqgvzeyb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuanzhike.top/Article/details/gtgkiayyuz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtrupqjnfi.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtcrwxcgbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aibaodan.cn/Article/details/gtmbhojlah.html

[C15] 解构 / 展开参数
来源：http://dali.yongpay.top/Article/details/gteyvsgqwx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yonumen.top/Article/details/gtnpakpzhv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtxagiuubv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtiraxnplb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrepwgjzs.html

Java: // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhezufzc.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gticycgwqn.html

Ruby: a, b = pair
来源：http://dali.yuanzhike.top/Article/details/gtczdzedxg.html

C#:   var (a, b) = pair;
来源：http://dali.xylfe.cn/Article/details/gtazrlqplg.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gtlykzjtdl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtsgyljian.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtyngbegkq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gtcfksqzeo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtzxqhtvsa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gtmfsyijfd.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtcsisnels.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gthjhqvjiw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jiagoushi.top/Article/details/gteysepwkp.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtuurubobl.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gtgxttaweu.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtkyresave.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtoaidevbg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sweek.top/Article/details/gtejmxhctk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtgrcmzoog.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtibpqgngo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtiglozbvh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtdroppnrq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cucudq.cn/Article/details/gtsarpimes.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtbseqjziy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ppjwa.cn/Article/details/gtkuasvzuh.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtekhrophb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtwbnpurrm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xinyue.icu/Article/details/gtttejpjwr.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtoazhzynu.html

TS:   arr.push(4);
来源：http://dali.ydzc1.top/Article/details/gtfidwtfky.html

Java: list.add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtvaizitpi.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gtcgvbcyjk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtntncriww.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqmnxmru.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtdegwuvnn.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gtnfsrnwpz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gtfhsznedk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtmkjkovhq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtnvcppjoc.html

Java: list.add(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtwjfcebzh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtzlzgybqb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtdpahqqzt.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtrlhrnukr.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtgabaldbh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gtfvajhzsm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cdnleiting.top/Article/details/gtraaenfge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtaxiqasqn.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gteddgiftz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gtwhjgksgb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtsgsqtzyh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sysykeji.top/Article/details/gtrquowjsk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtarrmzlga.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtyedizqtg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtjpagwzmm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtepqnnzvu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpadsfnsj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigufen.top/Article/details/gttdmunhjd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gtvalmwhyr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtywpcaheg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtajjydmzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtcqcdjixe.html

[D06] 数组长度
来源：http://dali.daxiang520.top/Article/details/gtmifzpvug.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtthmiahnl.html

PHP:  count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtflcutdql.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtatxyuuhu.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtzixyryph.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gthycdmobd.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtmxrrwyso.html

Ruby: arr.length; arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gtdrpnqiem.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtyqgmkbdb.html

[D07] 切片 / 取子数组
来源：http://dali.gogol.net.cn/Article/details/gtybqpbwql.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yvedp.cn/Article/details/gtlxyduuxd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yj202588.top/Article/details/gtlaagpkxu.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmptggry.html

TS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtglsmuuxd.html

Java: list.subList(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtxozxuoye.html

Go:   arr[1:4]
来源：http://dali.sweek.top/Article/details/gtkljpttqa.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtoxmhvtlr.html

C#:   list.GetRange(1, 3);
来源：http://dali.yongpay.top/Article/details/gtrntusccl.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtydlhsugx.html

Py:   a + b;  a.extend(b)
来源：http://dali.havefunace.top/Article/details/gtpdhbuquo.html

PHP:  array_merge($a, $b);
来源：http://dali.aibaodan.cn/Article/details/gtzwxdxwsu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shuidangran.top/Article/details/gtoueadhkj.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtnayzmdsn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaiikhjw.html

Go:   append(a, b...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthumfndwk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtcnjpdilq.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisyqqvrw.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gttvfxsuii.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gteyycvxay.html

PHP:  sort($arr);
来源：http://dali.xylfe.cn/Article/details/gtyuhsyaon.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtumcbudsn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxuanxn.top/Article/details/gttxvdhukp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gthggbcmee.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cdnleiting.top/Article/details/gthhdvfrxa.html

Ruby: arr.sort
来源：http://dali.0kj1m.cn/Article/details/gtmggdgdsx.html

C#:   list.Sort();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtniatmlgb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jianghu66.top/Article/details/gtewxydyqq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnxpdzunc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gtfxqbjsej.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsoizzbi.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtvhzjwztd.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtnnrrmbsh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gtwaxouhxv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.chenjidiqi.icu/Article/details/gtfnkxzsqr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.birdmap.top/Article/details/gtuslexxuy.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gtffkhbwcn.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.0kj1m.cn/Article/details/gtcnulbwns.html

PHP:  array_reverse($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtfzxqvowd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gtdlrfybnj.html

TS:   [...arr].reverse();
来源：http://dali.yj202588.top/Article/details/gtpsvglvoh.html

Java: Collections.reverse(list);
来源：http://dali.jqgfzy.top/Article/details/gtplgkzedm.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtjjpawogv.html

Ruby: arr.reverse
来源：http://dali.0kj1m.cn/Article/details/gtylwekfdb.html

C#:   list.Reverse();
来源：http://dali.cucudq.cn/Article/details/gtclglsthg.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gtscviouuj.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gtijzmxusy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gtyunpebfj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtaizeldkb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtcsowkafl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xziqi.cn/Article/details/gtwobauhxn.html

Go:   slices.Index(arr, x)
来源：http://dali.yangfankeji.com/Article/details/gtaekoxmtp.html

Ruby: arr.index(x)
来源：http://dali.yuxming.cn/Article/details/gtaqclatxt.html

C#:   list.IndexOf(x);
来源：http://dali.yuanzhike.top/Article/details/gtpkvcenou.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yueranfly.top/Article/details/gtsrlcbxqh.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guowangkeji.top/Article/details/gtjigfclsw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtuubyrwoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.mhx1999.top/Article/details/gtwanrjekw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhengqikj.top/Article/details/gtbjnirfcb.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hywenlv.cn/Article/details/gtpwcoktax.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hfpthk.cn/Article/details/gtlpfyynnn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgkphjne.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtpviilrfq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tanke756.top/Article/details/gtkzognfwu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hysaishi.cn/Article/details/gtqlaqiwhm.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gaohongyu789.top/Article/details/gthqrtojuu.html

JS:   arr.map(x => x * 2)
来源：http://dali.aizwys.cn/Article/details/gtbeduaxyy.html

TS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gtcuclcsiu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gtcxsnvkuo.html

Go:   // 手写循环
来源：http://dali.yangfankeji.com/Article/details/gtakxcvvmx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jianghu66.top/Article/details/gtxwokpkzm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gtlwmiqsyg.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtloxdrzte.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gthbxruvaf.html

PHP:  array_unique($arr);
来源：http://dali.tianlin.xyz/Article/details/gtmamsujox.html

JS:   [...new Set(arr)]
来源：http://dali.jqgufenzy.top/Article/details/gtehfrrsxg.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gtkqvgchdc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtjcvwzjvy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.nanxinkj.top/Article/details/gtiqxudhtc.html

Ruby: arr.uniq
来源：http://dali.jinqigufen.top/Article/details/gtecgppsmz.html

C#:   list.Distinct().ToList()
来源：http://dali.gotoacloud.top/Article/details/gtpfxnvnyz.html

[D16] 求和与平均值
来源：http://dali.hnxiangtu.top/Article/details/gtqczilupn.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.daria6918.cn/Article/details/gtngxxbogb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtlbwvqafu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aibaodan.cn/Article/details/gtwivlvfaa.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtrrewuakz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gtglxajres.html

Go:   // 手写循环累加
来源：http://dali.c1oappe.top/Article/details/gtusfitnuq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ybcxt.top/Article/details/gtpfyevwvc.html

C#:   list.Sum();  list.Average()
来源：http://dali.nwbrower.top/Article/details/gtdhtgrzal.html

[D17] 最大值与最小值
来源：http://dali.guannengcc.top/Article/details/gtmipwcdyp.html

Py:   max(arr);  min(arr)
来源：http://dali.ehwqpu.com/Article/details/gthvkvoxuu.html


<!-- 参考信息 -->