代发 wailian999

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2zqxfslab.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gt2lvvsgeah.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2pqwodier.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gt2owpvtfsh.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gt2akogabdq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2kfqatjne.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xdwgiliw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gt2pyglufkw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2htaxzzcq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gt2ihbulods.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gt2xopkvzvy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2rrcsapda.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gt2woodtuel.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2fgfkiwth.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gt2vjrvnsdy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2oillumte.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shzxlz.cn/Article/details/gt2snmcxtbp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gt2grnqztsy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2cqgipyhk.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hlpotweh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.andypj.xyz/Article/details/gt2ezwnjuti.html

[C03] 可变参数
来源：http://dali.yuanzhike.top/Article/details/gt2yfbzglfj.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gt2qejxjwbm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gt2khazqtvn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2nkasrbhs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2lgqqxfzp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gt2cjuvocln.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gt2ugqxxsti.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ppjwa.cn/Article/details/gt2gvumvqmr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gt2ittaaajl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktnisvdm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iqbgyobo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2uulirlhf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gt2qgryuccv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyydyfqz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2qmbbklfl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gt2tmnfgkxy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2fxhwprxc.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2njfmbcxm.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2dnvtldku.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlwsossf.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gt2ojnybewz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2bdvcpcmm.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gt2bzfqngdj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zdqjudy.top/Article/details/gt2kbmjyxto.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2iayqaknk.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gt2plgblgvi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gt2thnpobpw.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gt2texhlkpi.html

Py:   square = lambda x: x * x
来源：http://dali.zhoulong.xyz/Article/details/gt2flsnepgp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2etqzdbdk.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gt2jfsdefbm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gt2rbskanys.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqozehag.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gt2inkuzxbq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjmmsepp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gt2ippzxngw.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2xockyrtl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.meibo888.top/Article/details/gt2bnfnonpb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gt2fyoybixt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gt2sabsxecv.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2xhvqovtp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gt2fueveyjp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gt2dnpdppmq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gt2zavbmuvi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.c1oappe.top/Article/details/gt2jxdkmweq.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gt2ucvjpzwt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gaohongyu789.top/Article/details/gt2aqpdqhck.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gt2wakbxsci.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2oavjsjdi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwrrtkx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gt2tpqrjvxv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gt2xdfvllcp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yvedp.cn/Article/details/gt2rdrouqxy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rtsdevkk.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gt2jsaavlyl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2feziumij.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2ciklxdrv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gt2yzsoattq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gt2ksrbyapk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2crytiqks.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gt2tgzrubmo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gt2wogedgil.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gt2dvkbftpq.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gt2jsffjsmo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jiagoushi.top/Article/details/gt2yjlpyvmh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gt2glnvhfcm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggqofjaq.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gt2vglwjlde.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2mcjokpbc.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2uvgspvww.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gt2vhtxsmoq.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2frlnjyta.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2ejuqjyqy.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gt2njqgcehx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vwtgfxpz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gt2exswrlwp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gt2yifbglgs.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xirrgjkl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258888.top/Article/details/gt2kpoazllw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sysykeji.top/Article/details/gt2dfgzcbkg.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2auskfdst.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gt2idjywitt.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2ysaenppl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2mircmxqg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2iutiyhzr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjzrmzeq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gt2twqwrxje.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cqqwz.cn/Article/details/gt2nrrtkhqw.html

Ruby: -> { puts "run" }.call
来源：http://dali.quarkkingdee.top/Article/details/gt2bcflvloc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2wnniahzr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yonumen.top/Article/details/gt2vrsjipwk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sufxvd.cn/Article/details/gt2ptbwqiqe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2qvnbqdbh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gt2eofbhxjv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2umdokyee.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2koipgcaj.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gt2pmtyxzpm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gt2xnjrzdmt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfsdhyfq.html

[C14] 泛型函数
来源：http://dali.cdnleiting.top/Article/details/gt2tlfzhuzh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gaohongyu789.top/Article/details/gt2ycocjgez.html

PHP:  // 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ktspmzob.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2rhxnkvhc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gt2osecfrib.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gt2llgbvkcp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cashguo.top/Article/details/gt2watnzcyr.html

Ruby: # 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2hweobwvl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2ecxwzell.html

[C15] 解构 / 展开参数
来源：http://dali.iojbl.cn/Article/details/gt2iybbjzfq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gogol.net.cn/Article/details/gt2sbmuwmyx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gt2keweczao.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gt2ufyjosdg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwlffzqt.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2lemucvou.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsbfecsz.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2rjvnirmo.html

C#:   var (a, b) = pair;
来源：http://dali.daxiang520.top/Article/details/gt2oqdyrkci.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2sydbqfgc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hfpthk.cn/Article/details/gt2oxfnvbna.html

PHP:  // 无重载
来源：http://dali.gogol.net.cn/Article/details/gt2zgvuvuwa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gt2xpairprw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2doyzknus.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daxiang520.top/Article/details/gt2piaysqmw.html

Go:   // 无重载：用不同函数名
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fgkxwhqe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gt2iczineoa.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gt2carvsvhv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2rtfvixmn.html

D. 数组 / 列表 / 集合
来源：http://dali.guowangkeji.top/Article/details/gt2vuoxsdou.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2mjfoqfdt.html

[D01] 创建数组 / 列表
来源：http://dali.kuanghao11.cn/Article/details/gt2zwzzshes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2smigixyf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hfpthk.cn/Article/details/gt2zyfczaqy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.birdmap.top/Article/details/gt2vvtzorhs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guowangkeji.top/Article/details/gt2hlcudxje.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2jbyeabjk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gt2zegmdxha.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gt2vzmpeihw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ehwqpu.com/Article/details/gt2rzmscqgn.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2ttqfgtkd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhengqikj.top/Article/details/gt2ghdljnuk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xziqi.cn/Article/details/gt2gpiwdote.html

JS:   arr.push(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovwdfrlj.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2yqfsuseq.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gt2cxiffqqe.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gt2lrgfyfvf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2nodmdhgk.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2hrwbwkaa.html

[D03] 在指定位置插入元素
来源：http://dali.gzhubu.top/Article/details/gt2btthdpvg.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gt2upxlubxp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gt2aosvwuzk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2ybxeaazn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2gaaqtusg.html

Java: list.add(0, 0);
来源：http://dali.cheryme.top/Article/details/gt2nlxebjbe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.haohaochexian.top/Article/details/gt2dmhwjfcy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gt2wsnsiygl.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mulsmamg.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whimovzq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2gvtmaijn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2iyhtzjhi.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhijiandao.cn/Article/details/gt2ktqmftvn.html

TS:   arr.splice(0, 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2wasoruzq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daria6918.cn/Article/details/gt2xfwjbawr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj20258888.top/Article/details/gt2lwykwjcx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hjodcyuc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tian-w.cn/Article/details/gt2ccipixkj.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gt2desjrhqt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hljeluxh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2dnxkcige.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kybzzlyl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gt2ywparfku.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nanxuanxn.top/Article/details/gt2aaevuimh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xuanzx.com/Article/details/gt2lmyljbpx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdyagmzr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2ahycnzgo.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gt2cnaxbdrz.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2bszcvhaf.html

PHP:  count($arr);
来源：http://dali.ivvv.top/Article/details/gt2yikzbsiq.html

JS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gt2eynaindf.html

TS:   arr.length
来源：http://dali.sweek.top/Article/details/gt2eymfuuuw.html

Java: list.size();
来源：http://dali.hywenlv.cn/Article/details/gt2zhbfiuqd.html

Go:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2pkcarnja.html

Ruby: arr.length; arr.size
来源：http://dali.cqqwz.cn/Article/details/gt2sapvpnye.html

C#:   list.Count;
来源：http://dali.zdqjudy.top/Article/details/gt2bbryesqg.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2tsuophgr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gt2oqiwbxai.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2rtsrbdrd.html

JS:   arr.slice(1, 4);
来源：http://dali.jlsjyb.cn/Article/details/gt2qpzlbbbj.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fajxqihd.html

Java: list.subList(1, 4);
来源：http://dali.yj20258.top/Article/details/gt2mlljsgjl.html

Go:   arr[1:4]
来源：http://dali.dashuyun.cn/Article/details/gt2zrkujdzo.html

Ruby: arr[1, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2rngkcdza.html

C#:   list.GetRange(1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2dxxaauxo.html

[D08] 合并两个数组
来源：http://dali.hfpthk.cn/Article/details/gt2ossewzsd.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2fgwebkrv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gt2jnzpibdn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.vqdsnc.cn/Article/details/gt2dzjxjgxo.html

TS:   [...a, ...b];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sqpyomzg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gt2axqsjqhq.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2wfvzrofz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aizwys.cn/Article/details/gt2wjmpreel.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqpnabse.html

[D09] 排序（升序）
来源：http://dali.hysaishi.cn/Article/details/gt2qcmbhehn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.quarkkingdee.top/Article/details/gt2pjwqfqzg.html

PHP:  sort($arr);
来源：http://dali.guannengcc.top/Article/details/gt2cazgkfem.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gt2wajvlurs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yongpay.top/Article/details/gt2rkhlrogb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhongyouzk.top/Article/details/gt2ksqsvaxd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gt2dspiytyv.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwieueqw.html

C#:   list.Sort();
来源：http://dali.dashuyun.cn/Article/details/gt2uxwwzaff.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcwxwzby.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gt2rqvmicqk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gt2ybswyxrc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gt2vfostwtt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2whzpiixr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yangfankeji.com/Article/details/gt2mntzqolt.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.snrcjt.cn/Article/details/gt2uztpdlaf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xuanzx.com/Article/details/gt2cjatappj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.feifeiyinyue.top/Article/details/gt2wmbrrwrf.html

[D11] 反转数组
来源：http://dali.daria6918.cn/Article/details/gt2nejowavm.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gt2amyohhye.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gt2zgcdshct.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgfzy.top/Article/details/gt2kpvahqtj.html

TS:   [...arr].reverse();
来源：http://dali.tian-w.cn/Article/details/gt2xnztgtkn.html

Java: Collections.reverse(list);
来源：http://dali.jlsjyb.cn/Article/details/gt2gtxfioqo.html

Go:   slices.Reverse(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2zprpuuub.html

Ruby: arr.reverse
来源：http://dali.shangyingyoupin.top/Article/details/gt2zkxejbmu.html

C#:   list.Reverse();
来源：http://dali.pycfn.com/Article/details/gt2eqnofqsb.html

[D12] 查找元素下标
来源：http://dali.gaohongyu789.top/Article/details/gt2fhknapxn.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhoulong.xyz/Article/details/gt2bjqgqygz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gt2ejzuhllv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zycfv.cn/Article/details/gt2cxcmkqev.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gt2dlcihxas.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gt2yvhscdrp.html

Go:   slices.Index(arr, x)
来源：http://dali.cucudq.cn/Article/details/gt2xslpmomf.html

Ruby: arr.index(x)
来源：http://dali.fengsongda.top/Article/details/gt2racechwp.html

C#:   list.IndexOf(x);
来源：http://dali.havefunace.top/Article/details/gt2vrszxbsa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.ehwqpu.com/Article/details/gt2gbcerdln.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2hocwedhm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnkedxrm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gt2xugfxhtj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gaohongyu789.top/Article/details/gt2nljmkgnd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hnqzz.top/Article/details/gt2szmcobsq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2livwefuz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yongpay.top/Article/details/gt2trfstapm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wtmyqjzk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gaohongyu789.top/Article/details/gt2dhjqnbqg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gt2igctmnrq.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zycfv.cn/Article/details/gt2hxkajwyn.html

JS:   arr.map(x => x * 2)
来源：http://dali.dianchejie.cn/Article/details/gt2rvalzrvk.html

TS:   arr.map(x => x * 2)
来源：http://dali.jianghu66.top/Article/details/gt2iykfzwxz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sweek.top/Article/details/gt2ovjrghxm.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gt2ogsebefp.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dmgwxrnq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tanke756.top/Article/details/gt2fecfncjm.html

[D15] 去重
来源：http://dali.andypj.xyz/Article/details/gt2vjkaqhsl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2kvqygmzw.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wfmmqgfx.html

JS:   [...new Set(arr)]
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqgzwhfs.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gt2ifridxna.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jlsjyb.cn/Article/details/gt2fmbsqfor.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.svipenyu.cn/Article/details/gt2tvxfiuvx.html

Ruby: arr.uniq
来源：http://dali.hnxiangtu.top/Article/details/gt2ojmxeyzj.html

C#:   list.Distinct().ToList()
来源：http://dali.xuanzx.com/Article/details/gt2cvdxykyv.html

[D16] 求和与平均值
来源：http://dali.meibo888.top/Article/details/gt2kygsysru.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.redwolf501.top/Article/details/gt2gavojsom.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gt2fddhordz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gt2awqmvuwz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.redwolf501.top/Article/details/gt2defzaejs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnsgerla.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gt2ayumscst.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yueranfly.top/Article/details/gt2bkixjcyd.html

C#:   list.Sum();  list.Average()
来源：http://dali.vqdsnc.cn/Article/details/gt2zwddlmyp.html

[D17] 最大值与最小值
来源：http://dali.aibaodan.cn/Article/details/gt2uaidjptu.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gt2mseshulv.html

PHP:  max($arr);  min($arr);
来源：http://dali.guannengcc.top/Article/details/gt2npyqckdr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ybcxt.top/Article/details/gt2pgeydjfl.html

TS:   Math.max(...arr);
来源：http://dali.cheryme.top/Article/details/gt2tfycdncj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cucudq.cn/Article/details/gt2czhdtigl.html


<!-- 参考信息 -->