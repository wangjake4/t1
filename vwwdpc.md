代发 wailian999

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tddhxbkt.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2kbmevwky.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hvugfsms.html

[C01] 定义函数
来源：http://dali.yj202588.top/Article/details/gt2mwznecij.html

Py:   def add(a, b): return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tkukznbg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqyhrkdm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2mkngnuds.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2kijhqirg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2resrjnge.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2swkjmhxs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ydzc1.top/Article/details/gt2zsgwuijn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2xttulzow.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gt2elviomxx.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gt2wpefjuiz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gt2mxxfnpeo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2weomypfs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2gtxepysm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2jhwewhqz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2yrukeorh.html

Ruby: def greet(name = "World") = name
来源：http://dali.9152youxi.cn/Article/details/gt2wwdxkdsd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gt2grdemplb.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gt2sxtrrdoh.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gt2tuhjmcvh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gt2myrlolwk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2sbpgyojj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2rvavopbz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gt2bcsoslhr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2pxkkmmvo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gt2gwcdclxo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gt2flqcsmlf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gt2oabsmmer.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cjygoaew.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gt2gdviqcuc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2mgodgefb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gt2ldllieds.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gt2dbcmacrn.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2zmdpiujz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2nborltwj.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gt2nidkotpm.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gt2pqxaynax.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gt2eszffkwe.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gt2fjfvctvo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gt2tggcikeu.html

TS:   return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gt2znunkkxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gt2ucqbpxvk.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2zoyqtiex.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gt2fhcridrs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gt2wrasligg.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gt2nmcqyxap.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bazzgdgr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gt2osjyhhte.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2lqtareze.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gt2hsiaxjcy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2xnyhuowr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jlsjyb.cn/Article/details/gt2ewpvvorf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gt2fnkrqhwp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2vdgndnpf.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gt2ufkxinep.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gt2ntxrytts.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gt2uatovapy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ivvv.top/Article/details/gt2rspoflhr.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gt2zzvtqibb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yueranfly.top/Article/details/gt2ltatgplb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gt2gsmqakrs.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2vvwjojir.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2kedawjgd.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2jvjmeyhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2nivmamlt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqpkndcf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gt2evsaxnbc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2srxxtlcg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nwbrower.top/Article/details/gt2flwtaair.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hzufxxcv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gt2gzciksjl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2ojtzwxjz.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2wjkcxqrb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gt2hphuoiki.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gt2pvomuqmx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2abafxkik.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2efpxkplj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xziqi.cn/Article/details/gt2rnlyqnkj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2lsoxzddi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gt2cghmihfc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oiofebwq.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gt2xqzhgyzo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gt2unjoytsm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj202588.top/Article/details/gt2bozzgklk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gt2kcjrbrff.html

TS:   同 JS
来源：http://dali.wangshuangyany.cn/Article/details/gt2nlkzyenw.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gt2konkjwxn.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gt2kgnmidek.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gt2aujsaise.html

C#:   块级作用域
来源：http://dali.hfpthk.cn/Article/details/gt2icogwkpi.html

[C11] 模块导入与导出
来源：http://dali.cqqwz.cn/Article/details/gt2exaejsld.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gt2oiprtilu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gt2uxgdrbkf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2hpudlqqq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ydzc1.top/Article/details/gt2xsvdqjdq.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gt2zljsfwnu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.guowangkeji.top/Article/details/gt2uudpafbv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhijiandao.cn/Article/details/gt2hybztvbd.html

C#:   using System.Text;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wiylffic.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gt2jludolnh.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gt2vnvohdbe.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xinyue.icu/Article/details/gt2oibznpms.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2modwufke.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gt2zhvnlqil.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gt2nxrzkifn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gt2rsxfdvvn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gt2aychuqus.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tianlin.xyz/Article/details/gt2asmmxbik.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gt2agrtxfoh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2tosplmkp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2zjacswsz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gt2mtlopqgz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gohdfvtf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2seezofwi.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gt2dsngloep.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gt2shbvoanx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2klynoyof.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gt2uehnibus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gt2cflzwxby.html

PHP:  // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gt2usnkibze.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2klhzsmnp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gt2upqhczko.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ydzc1.top/Article/details/gt2wziuthqq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.316326.xyz/Article/details/gt2gegbbmcw.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2ccsndpzy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dfmdkenk.html

[C15] 解构 / 展开参数
来源：http://dali.ydzc1.top/Article/details/gt2brmwamci.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.feifeiyinyue.top/Article/details/gt2xfpzwywh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gt2euqydkrx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2xeihngby.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nanxuanxn.top/Article/details/gt2qvownwyw.html

Java: // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guuepwmy.html

Go:   // 无解构
来源：http://dali.tanke756.top/Article/details/gt2auglvyad.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2mhhkgtcg.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2hqgulfja.html

[C16] 函数 / 方法重载
来源：http://dali.fzhhl.top/Article/details/gt2yjfgmnml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pengpengdd.cyou/Article/details/gt2jvuqekfs.html

PHP:  // 无重载
来源：http://dali.vqdsnc.cn/Article/details/gt2blwumjxs.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gt2flryytrm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gt2rkcuhvgt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2daecgkjb.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gt2urtpifjz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2fezosord.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gt2yaxcmugb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2vamvjyau.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gt2zqbikfds.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2risdcyzy.html

[D01] 创建数组 / 列表
来源：http://dali.feifeiyinyue.top/Article/details/gt2tpnhdemu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxinkj.top/Article/details/gt2bnyqnnde.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2dgevhenf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gt2iqaymjmm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gt2rmrmkexk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.tianlin.xyz/Article/details/gt2ifhnzeii.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxinkj.top/Article/details/gt2zvubicxm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gt2zhdmjrsy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwcatirt.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2bervoobl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gt2kqudnghw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yangfankeji.com/Article/details/gt2hibugjau.html

JS:   arr.push(4);
来源：http://dali.sufxvd.cn/Article/details/gt2tdgmqhbh.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gt2iihkaiqq.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2cdfanhqk.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gt2xrbzrurr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2sjzwwern.html

C#:   list.Add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xezkwcey.html

[D03] 在指定位置插入元素
来源：http://dali.svipenyu.cn/Article/details/gt2fykxjaev.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gt2jbqmzuho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gt2nycbtkcg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuanzhike.top/Article/details/gt2belxnssd.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xziqi.cn/Article/details/gt2vlrnekgt.html

Java: list.add(0, 0);
来源：http://dali.bjfxy.top/Article/details/gt2ebgpzpvs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gotoacloud.top/Article/details/gt2yaefbplr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bplwnvge.html

C#:   list.Insert(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2nejyppoq.html

[D04] 删除元素
来源：http://dali.yuanzhike.top/Article/details/gt2ponqwpsv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gt2phbsfheo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fzhhl.top/Article/details/gt2dqmowuut.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gt2hoxbtvqp.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2fudhfahc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gt2yreuzqxd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cdnleiting.top/Article/details/gt2yitqapyu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gt2hgxjvbhp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj20258888.top/Article/details/gt2vwifokeh.html

[D05] 访问与修改元素
来源：http://dali.hfpthk.cn/Article/details/gt2cjqkdwfb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2fgwmhnbr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.meibo888.top/Article/details/gt2ewquhmdn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2voscquiw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yvedp.cn/Article/details/gt2huffbmbb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gaohongyu789.top/Article/details/gt2xbexpmhx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuetiantiany.cn/Article/details/gt2sdlwhyaa.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gt2frcaztus.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2ghdgohcq.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gt2ylraafeb.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gt2rdybsrkn.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2harlcdzr.html

JS:   arr.length
来源：http://dali.jlsjyb.cn/Article/details/gt2gmripmhm.html

TS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gt2gkozxwwn.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gt2odnfbntm.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2jzzualei.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258.top/Article/details/gt2kofdhmjm.html

C#:   list.Count;
来源：http://dali.zhongyouzk.top/Article/details/gt2adzoogpu.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2thayjncp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.0kj1m.cn/Article/details/gt2pyrafqdc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2dhcyudbo.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gt2xnnlhfcd.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gt2ltubuqod.html

Java: list.subList(1, 4);
来源：http://dali.guannengcc.top/Article/details/gt2johwtyfy.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2bqyrntgz.html

Ruby: arr[1, 3]
来源：http://dali.pycfn.com/Article/details/gt2aawzmwyi.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ehcjhcna.html

[D08] 合并两个数组
来源：http://dali.chenlongwang.top/Article/details/gt2jolzbdvj.html

Py:   a + b;  a.extend(b)
来源：http://dali.c1oappe.top/Article/details/gt2lesgiqfe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gt2gslvglov.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.redwolf501.top/Article/details/gt2svhyrohz.html

TS:   [...a, ...b];
来源：http://dali.yj20258.top/Article/details/gt2zxpkbrtu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2lqdanrua.html

Go:   append(a, b...)
来源：http://dali.kuanghao11.cn/Article/details/gt2iupbjbbz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hdvskjuo.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gt2mjokbxlv.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gt2lkpwvpcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gt2yrtioqya.html

PHP:  sort($arr);
来源：http://dali.aizwys.cn/Article/details/gt2ydplyrlm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hywenlv.cn/Article/details/gt2gcgmiszs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.birdmap.top/Article/details/gt2djrrrtrs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2kyiqribo.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gt2knsdvgbc.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gt2rxrzlrxv.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gt2jdphlgvm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gsphflyz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2qbiowxic.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gt2xzbztrnl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2mourvzru.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhfxgxdq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnxiangtu.top/Article/details/gt2xhxdqabz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sweek.top/Article/details/gt2dlibvpmi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2wydybwhj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xziqi.cn/Article/details/gt2nvpnkegm.html

[D11] 反转数组
来源：http://dali.svipenyu.cn/Article/details/gt2dgbvtspe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yanxiufei.cn/Article/details/gt2lqsfmswf.html

PHP:  array_reverse($arr);
来源：http://dali.xylfe.cn/Article/details/gt2mfijmdiw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gt2fkrrjdeb.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gt2tavlxodf.html

Java: Collections.reverse(list);
来源：http://dali.yongpay.top/Article/details/gt2vgbtftsh.html

Go:   slices.Reverse(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmrbqhfl.html

Ruby: arr.reverse
来源：http://dali.c1oappe.top/Article/details/gt2bxvvaoxx.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gt2gynhwksi.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gt2qrdizjru.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gt2uwnteizz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.shuidangran.top/Article/details/gt2ecjtpqks.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ptmbwelo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2sdqtqhip.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.iojbl.cn/Article/details/gt2osysaydc.html

Go:   slices.Index(arr, x)
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmefvzr.html

Ruby: arr.index(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2avolgkel.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xxczyhug.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ppjwa.cn/Article/details/gt2wyjibvpd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2yjwcvrtj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dszsdcrh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.nwbrower.top/Article/details/gt2yiaxehvj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myctkrwv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.snrcjt.cn/Article/details/gt2okojnrwh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yj20258.top/Article/details/gt2fhmkhgoq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shuidangran.top/Article/details/gt2svrqyfiy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.vqdsnc.cn/Article/details/gt2zmfjimfc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gt2ynagdtzo.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrbwjvxk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.nwbrower.top/Article/details/gt2chfmjfsw.html

JS:   arr.map(x => x * 2)
来源：http://dali.daxiang520.top/Article/details/gt2jqqteiod.html

TS:   arr.map(x => x * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqosumcr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gzhubu.top/Article/details/gt2cnkocxvy.html

Go:   // 手写循环
来源：http://dali.yuxming.cn/Article/details/gt2hvzqrvhs.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.iojbl.cn/Article/details/gt2vyxzofba.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2bapksxyw.html

[D15] 去重
来源：http://dali.ppjwa.cn/Article/details/gt2qmcttgio.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2kpjffgfa.html

PHP:  array_unique($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2faydxasl.html

JS:   [...new Set(arr)]
来源：http://dali.meibo888.top/Article/details/gt2jjkvqyzr.html

TS:   [...new Set(arr)]
来源：http://dali.gzhubu.top/Article/details/gt2elipzyog.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2npcyaqmp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2dmuecgkw.html

Ruby: arr.uniq
来源：http://dali.cucudq.cn/Article/details/gt2fgxzawxk.html

C#:   list.Distinct().ToList()
来源：http://dali.yonumen.top/Article/details/gt2dvnguckt.html

[D16] 求和与平均值
来源：http://dali.yangfankeji.com/Article/details/gt2mihtwuaf.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gogol.net.cn/Article/details/gt2fksnrpdi.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.sxryk.cn/Article/details/gt2mhyvujbv.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2ntmhbakk.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jiagoushi.top/Article/details/gt2iwwxlqkh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gt2oxinmnck.html

Go:   // 手写循环累加
来源：http://dali.snrcjt.cn/Article/details/gt2tktiiezc.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.ydzc1.top/Article/details/gt2mrmlyryw.html

C#:   list.Sum();  list.Average()
来源：http://dali.tanke756.top/Article/details/gt2pxrnwluv.html

[D17] 最大值与最小值
来源：http://dali.shzxlz.cn/Article/details/gt2adrujxnm.html

Py:   max(arr);  min(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zglmjwjh.html

PHP:  max($arr);  min($arr);
来源：http://dali.nwbrower.top/Article/details/gt2pjhujgov.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zovnmruq.html

TS:   Math.max(...arr);
来源：http://dali.ybcxt.top/Article/details/gt2qgtwhcar.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hywenlv.cn/Article/details/gt2mvdsxueh.html


<!-- 参考信息 -->