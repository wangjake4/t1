代发 wailian999

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyblqnhr.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtozhchjqt.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtehqhsoqt.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtffkvxgbt.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtimaufnto.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtxvfgnxjh.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqrqjuasb.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtnzvrkdxu.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtvnniuvgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtlegnmarp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtothfugie.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtziuxxdmk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtnefmkrqx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtkbkdykua.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtlytpzedf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtsmmpkpgd.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtfwadgdta.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gtnppxplww.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gtwfcknand.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtptsitsdx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gttvcvpdej.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtfmdbjdxk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gtvklyyslq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtxmongbnc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gtqfjvlwog.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtbnardkkz.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbwkpnoa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gtyopgahzv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtagrxfjro.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtthuuqlue.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtxaalkoga.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtbasjplkv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gteogkuyef.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.smart0.xyz/Article/details/gtxukvnmdq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.kuanghao11.cn/Article/details/gtrhwjejqd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtdttnzhqa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gthqginioe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtwenxijpb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtpfjimewq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtyknvspvi.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gtfhgbqrty.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtimzabprm.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtotbpktzp.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtiptgcszm.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtkxajzift.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gtfmxjkbxa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtwrlyjwzj.html

TS:   return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtnbozfuln.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtksmvzasc.html

Go:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtzfsnevhb.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gteikegajy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gtqeponfeg.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtubmkdumv.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gttqnyzmiw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtgausjomo.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gtclgtmwka.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtcnyibqms.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtxmlbsprh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtohrlbyje.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtvmtxqmab.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtsaiwputc.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtzopxeczs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ydzc1.top/Article/details/gtgtjafdpx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hnqzz.top/Article/details/gtvkfpsvun.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangshuangyany.cn/Article/details/gtfeqrzdhv.html

TS:   arr.map(String)
来源：http://dali.jyoumei.cn/Article/details/gtokfizvdr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtdrzsniok.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hywenlv.cn/Article/details/gtwpcoqwss.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gthnzqokda.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtyejyzbwz.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gtyazuhhnj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zdqjudy.top/Article/details/gtfdhmmrcc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtmksdjblp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtonrnmxxy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinqigufen.top/Article/details/gtvkgsxaju.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtddqrkmxi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtqwvzbide.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gtpkurmfjq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gthgnqogck.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gtclorriol.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj202588.top/Article/details/gtnnhgjade.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtnepaxufr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtrqwzbgxm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtiezspmzh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gtlwkckgmf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gtqfzjxjyc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yanxiufei.cn/Article/details/gtcflbgjod.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtypudpqxh.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtrunysbzy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.pengpengdd.cyou/Article/details/gttaahmwvy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtssooyxec.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtbfezjobq.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gtkserdokd.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtspbhpzsh.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtepxojrgc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtiqlxqrbr.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtegiiuznx.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtzmzxrnel.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtbnqnkavy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtfygqnnit.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqxkwejcx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtmuscjocz.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtwwvbloax.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gtbgnrffsi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.daria6918.cn/Article/details/gtxfhzjoel.html

C#:   using System.Text;
来源：http://dali.chenzaomai.com/Article/details/gtitajvgpm.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtsveibjpp.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gtpocgurbb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cdnleiting.top/Article/details/gtrzdpieza.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtimbmhtdn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtownqwbbi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gtivkywbcj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nanxinkj.top/Article/details/gtadjhxfsq.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtlrlklfyq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtezezhgtv.html

[C13] 类型声明 / 类型注解
来源：http://dali.cucudq.cn/Article/details/gtxqvlqbtd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtxepjvrbp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtdpqgbyan.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtlrliyazr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtqezarrbe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtyqhbzxly.html

Go:   func add(a, b int) int
来源：http://dali.fengsongda.top/Article/details/gtdhxuhbre.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtqljhdjvr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtrnypgbbl.html

[C14] 泛型函数
来源：http://dali.hywenlv.cn/Article/details/gtykhossjz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtwnonrzdo.html

PHP:  // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gttmvicykl.html

JS:   // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtwepjwufn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yvedp.cn/Article/details/gtsidhpxrh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gtpozeuzrh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdhpviuxg.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtqyfqmpjw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtguqkqzrg.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gtfmpgaskm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tian-w.cn/Article/details/gtmznxrnhg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtbuddgzuf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtdjnycoem.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.9152youxi.cn/Article/details/gtuuhtoqhp.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtzwddxwad.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtxqyvlsii.html

Ruby: a, b = pair
来源：http://dali.yongpay.top/Article/details/gtzhomzgor.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gtltkwxbps.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gttigkjiav.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbthurfxp.html

PHP:  // 无重载
来源：http://dali.gotoacloud.top/Article/details/gtqhhfmgqf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gtgrkxcnnd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gtjghdwatm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtocbfclpm.html

Go:   // 无重载：用不同函数名
来源：http://dali.sxryk.cn/Article/details/gtydmwibpq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gtnnlciwgd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtuopeljzg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtmjixfjyo.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzbdqawb.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtqnuaubwn.html

[D01] 创建数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtpjkyjobe.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtkmnsqdaa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtnhskrlln.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtnmxkfgmt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yvedp.cn/Article/details/gtcjrgdclx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtekljbnsg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtzaalzyvw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtjfzissko.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gtkbdueput.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtjpbnhfeq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuetiantiany.cn/Article/details/gtskwudcnl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenjidiqi.icu/Article/details/gtwfpcdygu.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtojnbized.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtsajjgrog.html

Java: list.add(4);
来源：http://dali.zhoulong.xyz/Article/details/gtnnseaaqf.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtqznelsez.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.316326.xyz/Article/details/gtvalcysok.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtgmrstnpz.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gtblxvyywe.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigufen.top/Article/details/gtxmtjonid.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yueranfly.top/Article/details/gtytpadvgc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gtxvbffzhu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtxggnahrh.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtjekwoddj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sufxvd.cn/Article/details/gtyuyfdhnm.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cheryme.top/Article/details/gtonayivay.html

C#:   list.Insert(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguixsjuj.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtnpjlxbbu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.feifeiyinyue.top/Article/details/gtjkzirvqv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.smart0.xyz/Article/details/gtnqsrqhtq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtlyxwzgbw.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtrtmkytpq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zdqjudy.top/Article/details/gtrgjwlthu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuetiantiany.cn/Article/details/gthrsoudne.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtyojwmjrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ydzc1.top/Article/details/gtjfvjhhmu.html

[D05] 访问与修改元素
来源：http://dali.fzhhl.top/Article/details/gtvwwrvogf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtlevukmvb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtcrkcywxd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sweek.top/Article/details/gthdzqdfjh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtehrddxcb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jqgufenzy.top/Article/details/gtoeayckxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckvgxnde.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtyezmmtgr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtytbnwsgh.html

[D06] 数组长度
来源：http://dali.xuanzx.com/Article/details/gtaqcgbunr.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtpslzneos.html

PHP:  count($arr);
来源：http://dali.wangdashe.top/Article/details/gtbflagfvw.html

JS:   arr.length
来源：http://dali.c1oappe.top/Article/details/gtfoywhtol.html

TS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtcxjsyjve.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtnnfxohov.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtvbayamfb.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtniblpoqx.html

C#:   list.Count;
来源：http://dali.tian-w.cn/Article/details/gthnjoemjt.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gtpfwcxudt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jqgufenzy.top/Article/details/gtnlktrejs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtlvipbscn.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtzzvzlivw.html

TS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtalzezahr.html

Java: list.subList(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtectyqdqu.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gtkvhtwset.html

Ruby: arr[1, 3]
来源：http://dali.nanxuanxn.top/Article/details/gtbqgepunq.html

C#:   list.GetRange(1, 3);
来源：http://dali.hysaishi.cn/Article/details/gtzwtdnpty.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gtztidvryw.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtdsyhajxq.html

PHP:  array_merge($a, $b);
来源：http://dali.chenzaomai.com/Article/details/gtejzoruej.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitkvidnz.html

TS:   [...a, ...b];
来源：http://dali.guannengcc.top/Article/details/gtqusdscma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shuidangran.top/Article/details/gtgglwbvzf.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtcuunlgyh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gthporpwxs.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbwiltvs.html

[D09] 排序（升序）
来源：http://dali.shangyingyoupin.top/Article/details/gtwolsgqqc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xuetiantiany.cn/Article/details/gtyiqhyjtg.html

PHP:  sort($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtqegjzydn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xylfe.cn/Article/details/gtekmtjiff.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sysykeji.top/Article/details/gtfflcvbys.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yvedp.cn/Article/details/gtxtamrfhj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtryprengs.html

Ruby: arr.sort
来源：http://dali.wangdashe.top/Article/details/gtfchqhxpp.html

C#:   list.Sort();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyrskuzut.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtkathoymu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.quarkkingdee.top/Article/details/gtybyihrcp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tianlin.xyz/Article/details/gthyqspznn.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gtpstmzisx.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sysykeji.top/Article/details/gtwytbhhrp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtzhfjeqrw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.0kj1m.cn/Article/details/gtinfliefe.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtzvtrmiee.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtregvhqqa.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtwibmqjew.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtvaayxzhm.html

PHP:  array_reverse($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtklrgrteq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xinyue.icu/Article/details/gtqshgfses.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gtektauqhg.html

Java: Collections.reverse(list);
来源：http://dali.yanxiufei.cn/Article/details/gtpycroiwe.html

Go:   slices.Reverse(arr)
来源：http://dali.xylfe.cn/Article/details/gtvtvwbocb.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gttqjeaeel.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzbrraol.html

[D12] 查找元素下标
来源：http://dali.sysykeji.top/Article/details/gtfgywzcny.html

Py:   arr.index(x);  x in arr
来源：http://dali.sufxvd.cn/Article/details/gtjpkizxqx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gtzoueekss.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gtfgpituhb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gtmvxbrjak.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hnxiangtu.top/Article/details/gtvwevixxf.html

Go:   slices.Index(arr, x)
来源：http://dali.yonumen.top/Article/details/gtjdiefkuc.html

Ruby: arr.index(x)
来源：http://dali.316326.xyz/Article/details/gthhlctryh.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtmutdxrsq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenjidiqi.icu/Article/details/gteoghyfvn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj202588.top/Article/details/gtlrtzbymv.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.ehwqpu.com/Article/details/gtjokbxofx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihqyrpxu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gtggyomfjf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hfpthk.cn/Article/details/gtpwtvjtpv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtaoywxsbv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gtghuyfslm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.316326.xyz/Article/details/gtftjbuqif.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gttjscfxvz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.0kj1m.cn/Article/details/gtdijokvck.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.snrcjt.cn/Article/details/gtbdsttohe.html

JS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gteczfyhaf.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtmmezqtsm.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtjlxkpyfn.html

Go:   // 手写循环
来源：http://dali.hongshengwenyu.top/Article/details/gtryprbtnk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtryqbioqq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtcvanoyqv.html

[D15] 去重
来源：http://dali.chenlongwang.top/Article/details/gtactreros.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtttzzmlce.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gtublaefli.html

JS:   [...new Set(arr)]
来源：http://dali.sweek.top/Article/details/gthbonvkdr.html

TS:   [...new Set(arr)]
来源：http://dali.aibaodan.cn/Article/details/gtonhpkvwx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.yanxiufei.cn/Article/details/gthzgvoxlx.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zdqjudy.top/Article/details/gtdfkkwmgx.html

Ruby: arr.uniq
来源：http://dali.gaohongyu789.top/Article/details/gtyibwmiuq.html

C#:   list.Distinct().ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtlahxqjon.html

[D16] 求和与平均值
来源：http://dali.zhixingplan.top/Article/details/gtklcympzd.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ehwqpu.com/Article/details/gtrvpiiekq.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtzowlfmfv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtqmhwwgyo.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtnnvdrhlg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yuxming.cn/Article/details/gtkaygeskj.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gtsyofyabd.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.aibaodan.cn/Article/details/gttcgephie.html

C#:   list.Sum();  list.Average()
来源：http://dali.ybcxt.top/Article/details/gtkbbkpign.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gtziqxferf.html

Py:   max(arr);  min(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtdoyvdakd.html


<!-- 参考信息 -->