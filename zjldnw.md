代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gtflvyakxg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtqkmihuqv.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtcnuslbdo.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gtylmcagyb.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtqineoiyw.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtqnikqhbz.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtkwmkjapl.html

Java: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtbudovzof.html

Go:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gttbgaolxi.html

Ruby: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtwobnepyt.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtxbicjnap.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtloyobycm.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtvjwgzbla.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtgapfesyg.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gthlcaguiz.html

TS:   if (!data) return;
来源：http://dali.guannengcc.top/Article/details/gtbqkqgnnz.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtpjpaibdj.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtxwexxfez.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtazccfgqc.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtouvkfmrv.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtmbhwuifh.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtdjuidwga.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcmkzhkjb.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gtkbhhdwki.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtxzfahgmh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtvzxdybfd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtwwsyyiei.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtpwjxydcn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtypmrvanx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtbswyynuv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdjwherbk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gttpjurbeo.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtaiszoopp.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtivcsyyot.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtinltujrq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gthudmzuyk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtkvxptlqa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtminedsjj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gttsadmqxz.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gthnyzywil.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.svipenyu.cn/Article/details/gtntjojjcl.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtwjdvoygb.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj202588.top/Article/details/gtdcqxhsno.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtkrhsbbvv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtfmjaftnn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtiiknasvw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtuurizimo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gtdfnjqvgl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtvipsmrzk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtutcajyfp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtjjaiepjl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtslkyyepb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtgohguqeb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtxczzowmi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtqotybpgh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtikagexww.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtercvqqcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtgefjmrcy.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtmlfkgiac.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gtwbzdpwyf.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtlkkqengx.html

PHP:  return [$a, $b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklgsoeoo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtliedzyqr.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtqfxpgkbz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gtapserhdq.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtujlqafhx.html

Ruby: return a, b
来源：http://dali.aibaodan.cn/Article/details/gtnbcptnqw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwkrnbgc.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtciprkeqx.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gtdddcmjde.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtpcbaxkmn.html

JS:   const square = x => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtpmudmhaa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtqipynudv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtkkjtoeci.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtajkliwsc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gtbgiucslu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtnttugxri.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtrjdypzeq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtsxubudzf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gthstubxeq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtgwkqxzqk.html

TS:   arr.map(String)
来源：http://dali.zycfv.cn/Article/details/gtiyshxeie.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gtkwvrrlss.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtoiwpinmo.html

Ruby: arr.map(&:upcase)
来源：http://dali.snrcjt.cn/Article/details/gtlvjdmrwo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewrwcdzi.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtybrstjbx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtyqysebgk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gtzklmlnkn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtgswszozt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtnliurgfm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.tianlin.xyz/Article/details/gtkndcezky.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhixingplan.top/Article/details/gtjazdjefp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtvmjdsrrl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtsjorahlz.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtixblahzw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.wangdashe.top/Article/details/gtvvjwrfct.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gthvoxbizp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtuofpynar.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtvspilgbw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtoswhkqmi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtjsuaiovu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtfqwvuwbq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gtewidsiog.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gthpmugkzz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtrojwvkgg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gtaactaamc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtussdygjv.html

TS:   同 JS
来源：http://dali.haohaochexian.top/Article/details/gtyqnbyzkk.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtjojboxdj.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtddnktbhf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.birdmap.top/Article/details/gtjimwreyg.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtviadfnwx.html

[C11] 模块导入与导出
来源：http://dali.fzhhl.top/Article/details/gtjtlxrutu.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkcxqupb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtfhoigatz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtjwlcmdqm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtelpoyvgi.html

Java: import java.util.List;
来源：http://dali.sufxvd.cn/Article/details/gttugljetl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtlltsatjz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gthdtcnszh.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gttexmuqqo.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gteizbeyhy.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtpccuyqkl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtgbnmgfhb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtlyfuvird.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gtcvirlaeu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtnaehbotk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gtpncxjuwx.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtxpwzcapu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtowbluwpn.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtdsuhmbcg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gtcxbqxilk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtfrrqhmlw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangshuangyany.cn/Article/details/gtwjncuqab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtlmjyehut.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtdbrxysdk.html

Go:   func add(a, b int) int
来源：http://dali.svipenyu.cn/Article/details/gtafzkzprl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtvowjqwsa.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfmlxdlx.html

[C14] 泛型函数
来源：http://dali.fzhhl.top/Article/details/gtmjtpvtsp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gthaisvxhu.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtxtmauozo.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtsojpthqg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtihnofllc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gthqlauldc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuxming.cn/Article/details/gtbaoadvhi.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtgvlhwbaz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pengpengdd.cyou/Article/details/gtyyvocbod.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtillyjrgd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtffpikcri.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtccotsbeu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtzdlemicm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.0kj1m.cn/Article/details/gtrqmaubzm.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtecoltpvl.html

Go:   // 无解构
来源：http://dali.guowangkeji.top/Article/details/gtebrcpajs.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gthpbzpdyt.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtadoyjmyb.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtutredqak.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuanzhike.top/Article/details/gtzwinisbn.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtczxiaonx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtkpwatryh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtxzjsapat.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtvtexvlfb.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtzpxdwldr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.svipenyu.cn/Article/details/gtvihampym.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtyxmguhgw.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtblzdhmvn.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtxozwwocd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrylpfxah.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gtndjstxue.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gtxmaopnel.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtvbyinabf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258.top/Article/details/gtligjkgag.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtheuuyeuz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gtvfowwvbu.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jqgufenzy.top/Article/details/gtflrqkgbm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtpnviaawp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtkarsmzpu.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gttjwpmidq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhizsina.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gtnlkigcqe.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtslwhrvqw.html

TS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtzrpwkpyn.html

Java: list.add(4);
来源：http://dali.zhixingplan.top/Article/details/gtucnqegzy.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtqixigpln.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtlgavgkbc.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gtbqlbyrsu.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gthdatvxtl.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtrwupzbda.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtauworemn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtaueedlcv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtdwkozsfr.html

Java: list.add(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gtrikjdfpl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtixiuocit.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtuxbitzvo.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtaehfcrum.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtlntzycwh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtqvsngcfg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gtqiupnaox.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gtxcysgpff.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gtxyiodywc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtqrqcrevf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtmoyypnvx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesxmaqbt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.gzhubu.top/Article/details/gtqrovasyw.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gthbosyume.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtabftmvkq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gttaulysab.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtnrpwehkp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaonpndl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtqbmamdqg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtrxqqngya.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gthuxdvxyx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtpvdeynbd.html

[D06] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gtutxjyfex.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtvfuiwnpc.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtrgufnchl.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gthchaebxl.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtrvmgwqgz.html

Java: list.size();
来源：http://dali.smart0.xyz/Article/details/gtgugiuofd.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtbculkwzs.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtshszecno.html

C#:   list.Count;
来源：http://dali.hysaishi.cn/Article/details/gtttnhycwm.html

[D07] 切片 / 取子数组
来源：http://dali.gaohongyu789.top/Article/details/gtufpkksho.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtvijmbqsx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtrigxtyjj.html

JS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gthirdijgs.html

TS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gteaqkovlv.html

Java: list.subList(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gtekyzukdi.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtgfoxnfuo.html

Ruby: arr[1, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtiyeqysfv.html

C#:   list.GetRange(1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gtagwrddnd.html

[D08] 合并两个数组
来源：http://dali.dianchejie.cn/Article/details/gtlmianazb.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtrsapszzy.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtqthdwyzf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gtxskxiiwd.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwamttht.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrlkxjxte.html

Go:   append(a, b...)
来源：http://dali.zycfv.cn/Article/details/gtweoibwpq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtuzoubebj.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnxiangtu.top/Article/details/gtxthsgyeg.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtgiipzwnv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gtzozzjurn.html

PHP:  sort($arr);
来源：http://dali.shuidangran.top/Article/details/gtvjqtxvgv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtetttqtkg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenjidiqi.icu/Article/details/gtwcibwoyq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtggoybzqt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtarilvzda.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gtkaijevyc.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtvtnfvlin.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gtzbgvcvps.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sufxvd.cn/Article/details/gtdmtrazsv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtmvvmxpuj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtxqfditcl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhijiandao.cn/Article/details/gtjlmkubcu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtwpctqjrx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hnqzz.top/Article/details/gtzpmpsmpn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjispfskk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.smart0.xyz/Article/details/gtjblyndph.html

[D11] 反转数组
来源：http://dali.dashuyun.cn/Article/details/gtatbfkuya.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhoulong.xyz/Article/details/gtwvnauyij.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtccuhsocl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guannengcc.top/Article/details/gtokblxycr.html

TS:   [...arr].reverse();
来源：http://dali.yuanzhike.top/Article/details/gtonotpozp.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gtrpuchscv.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtxeignmbw.html

Ruby: arr.reverse
来源：http://dali.jianghu66.top/Article/details/gtoeecanhx.html

C#:   list.Reverse();
来源：http://dali.yangfankeji.com/Article/details/gteeivolfm.html

[D12] 查找元素下标
来源：http://dali.jinyuanbaomall.cn/Article/details/gtursznwzl.html

Py:   arr.index(x);  x in arr
来源：http://dali.havefunace.top/Article/details/gtjzgserkw.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtyomrswej.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gtljbjqigk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gtovwssvug.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.guannengcc.top/Article/details/gtcjpkdiwx.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtscqhbaas.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gtyfvjgplg.html

C#:   list.IndexOf(x);
来源：http://dali.yangfankeji.com/Article/details/gtxejbqgab.html

[D13] 过滤（保留满足条件的）
来源：http://dali.mhx1999.top/Article/details/gtipeilhia.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtregspnyb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinqigufen.top/Article/details/gtwgqnuwtx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtsncbvzxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtylwkohdp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj20258.top/Article/details/gtkcbdnbmk.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xziqi.cn/Article/details/gtwdfaefrc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gaohongyu789.top/Article/details/gtzbdubigm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtofzutktb.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgvnpmwt.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtpfobmndn.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtlhcnivrs.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtwfrudnko.html

TS:   arr.map(x => x * 2)
来源：http://dali.zycfv.cn/Article/details/gtaemnrxfw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtygmeanmk.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtojxkgkyu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvpzhino.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtrfcflfzh.html

[D15] 去重
来源：http://dali.zhijiandao.cn/Article/details/gtggvlldnn.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuanzx.com/Article/details/gtoluxiday.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtqcizjpkc.html

JS:   [...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtpcrmwaxm.html


<!-- 参考信息 -->