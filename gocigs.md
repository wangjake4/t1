代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2riihqhfz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2igawtxsc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2whcnynko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2gqqifhfi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2swiuyphk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2plbwigkx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gt2iaryqosy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2wwvbharp.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gt2fdzyeiet.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gt2wfakjasr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yvedp.cn/Article/details/gt2msnfysdy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2fiavnwli.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2eidkvjph.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gt2nrswlaxa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vuusftjj.html

Ruby: def greet(name = "World") = name
来源：http://dali.yueranfly.top/Article/details/gt2dbrbcqqw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gt2jsqkioza.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gt2xjukytnf.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2znbtrybb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gt2amsamfza.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gt2hwguqhok.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2xgepplnh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gt2pdolequs.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gt2gsjyocvr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2qvklgzya.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gt2mtdkbdvy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2iytekndr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgufenzy.top/Article/details/gt2wfyhehlx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2zoqlhjpy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gt2dnhssjtw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rdksenlq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gt2paaoqmvm.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gt2vesracax.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2pxogkbnm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2bjwtwhge.html

[C05] 返回多个值
来源：http://dali.yueranfly.top/Article/details/gt2jplxoseb.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2wqjmicgo.html

PHP:  return [$a, $b];
来源：http://dali.0kj1m.cn/Article/details/gt2eyztuwze.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2fkavgpox.html

TS:   return { a, b };
来源：http://dali.xinyue.icu/Article/details/gt2nnyyyqdh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gt2rwyrjvht.html

Go:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhmsjraj.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gt2miwwtayi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2azelbakt.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gt2npmphauz.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gt2heqngclr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnqzz.top/Article/details/gt2theqnotw.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2erafwstm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2keegnxky.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2huegygzj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2dfiwvykv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gt2hmxtqksw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2ommaeorv.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gt2hsrfkmln.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnxiangtu.top/Article/details/gt2jkzuqfah.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nwbrower.top/Article/details/gt2rlbyxhst.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcioljeu.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2wkqvtqfb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2gbrobpmv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2viikmjba.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2prepfgxj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2dbolisol.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2rsswtzti.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2evxlqhtc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gt2mluvrzrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2pbtspghy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kmhfpenr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gotoacloud.top/Article/details/gt2kxfgewgn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zrnltlom.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2rveekioe.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sciyhcsl.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gt2rfothgqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2zphsqlim.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gt2auehymdt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2gkudbkig.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gt2dgvqhuoc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenlongwang.top/Article/details/gt2jntqceeg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gt2tvdpgjmr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2bpxdntcu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gt2xlgjluyi.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2lrlwdzbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2ytphyyts.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gt2ccmmkmnz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gt2pokfqktv.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2udhzzdca.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2sfamawcz.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2xagqjptr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hammf.cn/Article/details/gt2gdgtrtmz.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2iwagkphs.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2wjglntex.html

Py:   from module import func
来源：http://dali.gogol.net.cn/Article/details/gt2kqittbpz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gt2pazvzmbm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gt2rjkbziuo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gt2azdfvynn.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gt2kesluttk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gt2uhiohutz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gt2coprkcim.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2wjccvizw.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2xkxwmslg.html

Py:   (lambda: print("run"))()
来源：http://dali.yanxiufei.cn/Article/details/gt2epsmuyoz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gt2izubysqt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gt2klonyukl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2nwlsgwsn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gt2oxryyjtp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gt2skkmaeth.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2xwouatxb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2xzkatqcc.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rjfqfrup.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gt2lpttslqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2kuftammx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gt2bmlbsnmd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2jeplyeyw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2jdolvhbn.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gt2tnieselu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gt2vzaywycx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gt2deuqtpwp.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gt2khalcdrn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gt2ivuioreu.html

PHP:  // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jbggjdqz.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2wruktclw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.dianchejie.cn/Article/details/gt2jaxwmvsx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gt2cjnhbven.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gt2cfcmcgst.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gt2gdfrynrr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.quarkkingdee.top/Article/details/gt2efrybdxw.html

[C15] 解构 / 展开参数
来源：http://dali.gzhubu.top/Article/details/gt2tkjhwhxm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gt2wqyhdfbr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daria6918.cn/Article/details/gt2pctrwtkr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ikclhlxz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gt2uqmtmetn.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2cinxqvgw.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2pqtdpidf.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2fccadlna.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gt2nsoxqshn.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gt2eczuyxkp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ajaydlvr.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gt2qiiujxhh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gt2lecslphv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hammf.cn/Article/details/gt2galsucof.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gt2txqpttkk.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qlptgyqb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2knamcrss.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.iojbl.cn/Article/details/gt2yhdvlngq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xhlbdfel.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2aqvijuoa.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iiqbqxdr.html

[D01] 创建数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2siykploc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2eqdmzazt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gt2iisdncyk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2gzcdbmef.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jiagoushi.top/Article/details/gt2fncjxswo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ppjwa.cn/Article/details/gt2mixqycho.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gt2ykstdhpw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gt2mrvbgxms.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jianghu66.top/Article/details/gt2uuwsbhhw.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gt2jtpcdebs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2ekohlqxd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2kltmkepd.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2jcnhknga.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gt2hnzfbvia.html

Java: list.add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2vczlutqo.html

Go:   arr = append(arr, 4)
来源：http://dali.gaohongyu789.top/Article/details/gt2auhutlla.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gt2ialdfkvj.html

C#:   list.Add(4);
来源：http://dali.hnqzz.top/Article/details/gt2blmelhtf.html

[D03] 在指定位置插入元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2ejfhrknn.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wvljkjwv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tyrgidyr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2onovpiss.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gt2cvylacni.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2ebtzqhuf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hnxiangtu.top/Article/details/gt2uxjekugq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gt2igabozsy.html

C#:   list.Insert(0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2zvxxvmys.html

[D04] 删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2ygxdcwet.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pycfn.com/Article/details/gt2inreovuw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qyrucxdk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tksyxglc.html

TS:   arr.splice(0, 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aaafzrhp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2imivcfra.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gotoacloud.top/Article/details/gt2ufygrcue.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gt2yfpjgwum.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tureolap.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gt2lxxuxuqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gt2uefkjbny.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2qppgegpz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgfzy.top/Article/details/gt2eyfvjrgr.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2cgecmatz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guowangkeji.top/Article/details/gt2dnbaynxd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gt2hptsafrj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukgqavoy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gt2cfsijdod.html

[D06] 数组长度
来源：http://dali.yj20258.top/Article/details/gt2bmbthnpq.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2nrfakhur.html

PHP:  count($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ihtfytjd.html

JS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gt2aivfrwbg.html

TS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gt2wdiuqczl.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gt2vwkqpurs.html

Go:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2bazupteh.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gt2stykkqim.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2rokukrgq.html

[D07] 切片 / 取子数组
来源：http://dali.jqgufenzy.top/Article/details/gt2hlncuvvh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqbrzofb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gt2xulimguy.html

JS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fafihkzi.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gt2dxntjcnt.html

Java: list.subList(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2vkwbyaqc.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2puxqkkiy.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gt2fwxyywfk.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gt2bzbbpces.html

[D08] 合并两个数组
来源：http://dali.jlsjyb.cn/Article/details/gt2pntnpaay.html

Py:   a + b;  a.extend(b)
来源：http://dali.bjfxy.top/Article/details/gt2xhfjchqu.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2flsvjlqx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.smart0.xyz/Article/details/gt2mghesrky.html

TS:   [...a, ...b];
来源：http://dali.cashguo.top/Article/details/gt2smkedjxd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sxryk.cn/Article/details/gt2bhidgozs.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gt2fszmqvbf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hysaishi.cn/Article/details/gt2wuemlicb.html

C#:   a.Concat(b).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqpylpzb.html

[D09] 排序（升序）
来源：http://dali.dashuyun.cn/Article/details/gt2dmxupyav.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gt2rtkpqfab.html

PHP:  sort($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2hluqkycu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gt2wudiglxd.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daria6918.cn/Article/details/gt2dwqjdztp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gt2nwohxsxo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gt2vdlrdvit.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2dxsfahvm.html

C#:   list.Sort();
来源：http://dali.jqgufenzy.top/Article/details/gt2zzulvyux.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yanxiufei.cn/Article/details/gt2amvooagw.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gt2nbocatci.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2tvgpfucy.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jlsjyb.cn/Article/details/gt2axcjpine.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hammf.cn/Article/details/gt2qqfvnpuh.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sysykeji.top/Article/details/gt2evqazjwf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.bjfxy.top/Article/details/gt2tzdapuep.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gt2yopklvzn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vgwghdyz.html

[D11] 反转数组
来源：http://dali.zycfv.cn/Article/details/gt2vslzidng.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.chenlongwang.top/Article/details/gt2vodifwkb.html

PHP:  array_reverse($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2utosmjix.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnqzz.top/Article/details/gt2omluhhmm.html

TS:   [...arr].reverse();
来源：http://dali.pycfn.com/Article/details/gt2qvfzftyn.html

Java: Collections.reverse(list);
来源：http://dali.hfpthk.cn/Article/details/gt2opbbqygk.html

Go:   slices.Reverse(arr)
来源：http://dali.nanxinkj.top/Article/details/gt2ulpbmaiz.html

Ruby: arr.reverse
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kihqwfue.html

C#:   list.Reverse();
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgqavqly.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gt2yonhmnoh.html

Py:   arr.index(x);  x in arr
来源：http://dali.jlsjyb.cn/Article/details/gt2mqnuskwh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2lqcunhzd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2qljmiqsp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2cvezvmjb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tian-w.cn/Article/details/gt2uudvfpyd.html

Go:   slices.Index(arr, x)
来源：http://dali.tanke756.top/Article/details/gt2hjrpfdit.html

Ruby: arr.index(x)
来源：http://dali.shuidangran.top/Article/details/gt2qkspaihz.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gt2juacbmgi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.jinqigufen.top/Article/details/gt2ryzqqzvm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ybcxt.top/Article/details/gt2astomdvr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cheryme.top/Article/details/gt2iqhaxmoy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2tihnyujd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2hlpzzhpd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.bjfxy.top/Article/details/gt2jrdrmtzv.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gt2knbvbzmf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.vqdsnc.cn/Article/details/gt2opgjohlj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.mhx1999.top/Article/details/gt2aozwrteg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qywkzpyk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvogaofs.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2drqfqpph.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvbgurp.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2wjkugkfb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2pzylwhmn.html

Go:   // 手写循环
来源：http://dali.hfpthk.cn/Article/details/gt2uswtcubh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gt2ewviuccg.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gt2jarvkqoi.html

[D15] 去重
来源：http://dali.zdqjudy.top/Article/details/gt2xvokjxkw.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.ydzc1.top/Article/details/gt2vwtaxfct.html

PHP:  array_unique($arr);
来源：http://dali.yonumen.top/Article/details/gt2ixuggdio.html

JS:   [...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gt2oyfgcbrg.html

TS:   [...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2flawydlm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2dvbhlciu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lumzxlfw.html

Ruby: arr.uniq
来源：http://dali.sysykeji.top/Article/details/gt2guihdsqv.html

C#:   list.Distinct().ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2yqinosgj.html

[D16] 求和与平均值
来源：http://dali.wangdashe.top/Article/details/gt2qqxvylab.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jqgfzy.top/Article/details/gt2sqqlzqgj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2iffincgu.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.c1oappe.top/Article/details/gt2qczsattd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guannengcc.top/Article/details/gt2wyqczayv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dianchejie.cn/Article/details/gt2cxydfktx.html

Go:   // 手写循环累加
来源：http://dali.andypj.xyz/Article/details/gt2flfktjqv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ivvv.top/Article/details/gt2xwchznwu.html

C#:   list.Sum();  list.Average()
来源：http://dali.svipenyu.cn/Article/details/gt2scnkrdeg.html

[D17] 最大值与最小值
来源：http://dali.zhixingplan.top/Article/details/gt2ffrmrsii.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gt2wvoumuqc.html

PHP:  max($arr);  min($arr);
来源：http://dali.ivvv.top/Article/details/gt2meluzgba.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhixingplan.top/Article/details/gt2syrmwskd.html

TS:   Math.max(...arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uwwjzszw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.chenjidiqi.icu/Article/details/gt2sencviwa.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2zxkqhwfr.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gt2vzzywicp.html

C#:   list.Max();  list.Min()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmkmquvb.html

[D18] 扁平化嵌套数组
来源：http://dali.smart0.xyz/Article/details/gt2igbqdfly.html


<!-- 参考信息 -->