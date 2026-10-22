代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtctjwypoq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtvreqeort.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gtxxwtbihg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtwodzoyeq.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtlxskebbt.html

Py:   def greet(name="World"): return name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqnlboxw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuoieziv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtohuajatk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtganhnfcw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gtgxuscyxp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtbkymxski.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtslvnfwds.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtvgognmwu.html

[C03] 可变参数
来源：http://dali.aizwys.cn/Article/details/gtxzcbclrs.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtpqsvzvcl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtxupvwqiz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtqezeaszc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtkqryhuhn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtwgujzofe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gttspaalgm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gotoacloud.top/Article/details/gticnmgzrf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gtbndbmnhp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gtqajxlxxg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuanzx.com/Article/details/gthekabunc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gttljdcfok.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylcchhmc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gtqdguniyn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtlgmejwvz.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtypbdwlas.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtvggnpvmj.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtnxhwrwpw.html

[C05] 返回多个值
来源：http://dali.xylfe.cn/Article/details/gtnaajcuvu.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtuwskqyvk.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtfobqudps.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gtymhjeofg.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtiuugnzpx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtfkbimkan.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbajsaifr.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtnxtonkie.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gtzvcmzihx.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gtgcicpokl.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtttjvqtvx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtefxygbig.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtxuxqnktu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gttkrwzegz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gthpmqmoia.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtqqujkukp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtwxnjfkqo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gthvsnjhji.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtnrjielwq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtvdojhoef.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtxlrowprh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuetiantiany.cn/Article/details/gtwhcerjuv.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtxauozwyr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtxpjwdcti.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtcfgteqhp.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhfljzko.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtmzrobnpo.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtoyowysba.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gthvxioeme.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtgohrikhz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtdqcxlfhh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtrjxzvpri.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtcxdygzmg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gtzlilwcsr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtzylaogtz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtsttzgqwz.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtiivohmxe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gthnmskopy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtaibxdiga.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gtxafefpou.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.quarkkingdee.top/Article/details/gtiqjvojux.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtgjiwfypb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtupvyxhly.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtqqatomeg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gtsrrofyso.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtkaautgeb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtkkwkpfyg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgfzy.top/Article/details/gtmvdnfcgs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtxppxewwh.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrwpadmao.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtdlptgdxm.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtevtdbbpj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtnslmiqtr.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtilbckcrc.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtoswoheqw.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtdpmxbqsm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gtystxsnkw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtncvugxvr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxinkj.top/Article/details/gthwunayqz.html

Java: import java.util.List;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnfbpovj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gttrajqtwv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtcuhvvggu.html

C#:   using System.Text;
来源：http://dali.hongshengwenyu.top/Article/details/gtziehbumb.html

[C12] 立即执行函数 IIFE
来源：http://dali.cqqwz.cn/Article/details/gtsxflejdh.html

Py:   (lambda: print("run"))()
来源：http://dali.andypj.xyz/Article/details/gtbngkgbek.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtqpcilvrv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtvdsljxfw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtvnrwkzjv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtlzoomlen.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gttnzfewkw.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtitofjbvj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yongpay.top/Article/details/gtiswyntnd.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigfzy.top/Article/details/gtbdijybis.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guowangkeji.top/Article/details/gtvjfuzbrl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtnfspzxqe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtiaoesmvk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtenaebqwh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtcznobewq.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtuiyglfcy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gtsaexbrpi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtdygdvdbo.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtgugwxreh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sweek.top/Article/details/gtcnddcgvx.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtmdgajqer.html

JS:   // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gtzfaukiot.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gttkchiotw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtexawdkoc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtoeqafhnd.html

Ruby: # 无泛型
来源：http://dali.xuanzx.com/Article/details/gtzwhdkvps.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gtwtuznszo.html

[C15] 解构 / 展开参数
来源：http://dali.gotoacloud.top/Article/details/gtddbuirct.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtfmgwdbir.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gtakundlkd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxinkj.top/Article/details/gtxmgrjzyw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtgrjfdfoa.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gtigrpejrb.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gtcqwtklhh.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtqgfeghie.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtadsuwutg.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtghwcoltu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtqqfdusab.html

PHP:  // 无重载
来源：http://dali.hnxiangtu.top/Article/details/gtihcxjisp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtcfnpdoqn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtuwysnmfa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gtmsxwdpmj.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gtzpxtihjc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.redwolf501.top/Article/details/gtamydksan.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtviimxvnp.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmkoplnxj.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtapysxyft.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrtfsbpdz.html

[D01] 创建数组 / 列表
来源：http://dali.sufxvd.cn/Article/details/gtbvbftbkn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yonumen.top/Article/details/gteluqkzhk.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtuaumddod.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gtntopwrso.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtvgctpjal.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtgmbebmkp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gtoeghiqcv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sysykeji.top/Article/details/gtrsknjagb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gthiaqrbib.html

[D02] 追加元素到末尾
来源：http://dali.dianchejie.cn/Article/details/gtozrumamk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhlzhgym.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtxwjzsxap.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gtqmtxksmx.html

TS:   arr.push(4);
来源：http://dali.aizwys.cn/Article/details/gtdrexlgxf.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtaafjrcuu.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtdeoqaojy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtlrjqtbcq.html

C#:   list.Add(4);
来源：http://dali.hywenlv.cn/Article/details/gtbmtbykrp.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gtftauseqb.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtuuccfrvz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gtywwfyjbh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtwrwoxbup.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtxqfubthz.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtilszbscm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtxofauydx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.mhx1999.top/Article/details/gtwtomouqd.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gtpsmqpvtx.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtucpzmvtb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtsxlpmbfa.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gttvidtbnw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gtevynhkwc.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtcvbrultx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hnxiangtu.top/Article/details/gtjbltwbpi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ydzc1.top/Article/details/gtpglcbwio.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtkhjsxeda.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gtehtdrifg.html

[D05] 访问与修改元素
来源：http://dali.hywenlv.cn/Article/details/gtpspzbdzo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtmtinguel.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtethfzjhd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gtvxctpvua.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtzcmyrwkr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtvygkiyan.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gthbpqgbxf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtoagzlmxq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtuvklmozj.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtmckukulk.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtouliodit.html

PHP:  count($arr);
来源：http://dali.yuanzhike.top/Article/details/gtroyrobrx.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtpaxdhxvp.html

TS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gtqllyfbpk.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtfqthhggg.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtsomjaojx.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtyhectnea.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtrxwtovea.html

[D07] 切片 / 取子数组
来源：http://dali.nanxinkj.top/Article/details/gtwtvphbyt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuanzhike.top/Article/details/gtbmdsgryi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtvmvwejxz.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtdzgagzjj.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtnmqmmlah.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtznqxobkb.html

Go:   arr[1:4]
来源：http://dali.smart0.xyz/Article/details/gtxuiooezm.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtrvyvpjat.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtrdkmnizp.html

[D08] 合并两个数组
来源：http://dali.ppjwa.cn/Article/details/gtavmsvahr.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj202588.top/Article/details/gtapubhoqk.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtmvfpginp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinqigfzy.top/Article/details/gtuivugelw.html

TS:   [...a, ...b];
来源：http://dali.sufxvd.cn/Article/details/gtjrzhjwmd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.meibo888.top/Article/details/gtrmcwgfjs.html

Go:   append(a, b...)
来源：http://dali.wangdashe.top/Article/details/gtjzngkxoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.sxryk.cn/Article/details/gtwydpvvoj.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gtnyocqifv.html

[D09] 排序（升序）
来源：http://dali.yueranfly.top/Article/details/gtnitpwamb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtojfnoanv.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtsqiygirg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtxaqajvmv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gtoufvjrsq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gtiryvopwd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ppjwa.cn/Article/details/gtkweprsfo.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtsfzufbcv.html

C#:   list.Sort();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtikqywpjc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yvedp.cn/Article/details/gtxohbwtch.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpelqoldo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dashuyun.cn/Article/details/gterzrlxzb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daxiang520.top/Article/details/gtqgcofcnh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtazvkzolw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.havefunace.top/Article/details/gtdyfmllkq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gthqwgvkui.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtiromjcsx.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gtdqwfamdg.html

[D11] 反转数组
来源：http://dali.xylfe.cn/Article/details/gtlmdkanfz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtswljlsqf.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtefujmsgx.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jlsjyb.cn/Article/details/gtwdrgqmno.html

TS:   [...arr].reverse();
来源：http://dali.zhengqikj.top/Article/details/gtqywklzrk.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhgplusu.html

Go:   slices.Reverse(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjqypyig.html

Ruby: arr.reverse
来源：http://dali.shuidangran.top/Article/details/gtibpyjtmj.html

C#:   list.Reverse();
来源：http://dali.cashguo.top/Article/details/gtcfgsngqf.html

[D12] 查找元素下标
来源：http://dali.bjfxy.top/Article/details/gtfeqgbwly.html

Py:   arr.index(x);  x in arr
来源：http://dali.xylfe.cn/Article/details/gtroyiheoz.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.havefunace.top/Article/details/gtazzunevt.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.mhx1999.top/Article/details/gtwlaswpob.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gtujqghyiw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.aizwys.cn/Article/details/gtnsjcjdrb.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gtgadoomig.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gttnjumrfk.html

C#:   list.IndexOf(x);
来源：http://dali.sufxvd.cn/Article/details/gthpgfjapp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yj202588.top/Article/details/gtfpjydnhf.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.kuanghao11.cn/Article/details/gtzptvqoxa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gtlrtvqxds.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yueranfly.top/Article/details/gtygcjwaxi.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jqgufenzy.top/Article/details/gtwiswtsty.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sweek.top/Article/details/gtsdsnminl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gtqtmiqhwx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yangfankeji.com/Article/details/gtpklivwlv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yonumen.top/Article/details/gtdxdrukmt.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenlongwang.top/Article/details/gtkwxpaolv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jyoumei.cn/Article/details/gtgviqpgao.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenlongwang.top/Article/details/gtqwakfrmf.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtlwmnyxuj.html

TS:   arr.map(x => x * 2)
来源：http://dali.gotoacloud.top/Article/details/gthsrpgfzk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hywenlv.cn/Article/details/gthmdjplic.html

Go:   // 手写循环
来源：http://dali.nanxinkj.top/Article/details/gtmzexnuws.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hammf.cn/Article/details/gtkkxauttr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ydzc1.top/Article/details/gtnpkgxxuk.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtkrkfmeuf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtwtmhvmxa.html

PHP:  array_unique($arr);
来源：http://dali.yuxming.cn/Article/details/gtjjlqxine.html

JS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtqjphfmxy.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gtirbeynvy.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cashguo.top/Article/details/gtkyjybxfv.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhixingplan.top/Article/details/gtuearkzte.html

Ruby: arr.uniq
来源：http://dali.yj20258.top/Article/details/gtdlkalheb.html

C#:   list.Distinct().ToList()
来源：http://dali.sysykeji.top/Article/details/gtainabytb.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtzjqhwnox.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtaiafidwz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cdnleiting.top/Article/details/gtgszwygoa.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.havefunace.top/Article/details/gthnpypytn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtmstwkwse.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258888.top/Article/details/gtmbdotwxg.html

Go:   // 手写循环累加
来源：http://dali.316326.xyz/Article/details/gtknqlrisj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.zhijiandao.cn/Article/details/gtigeiagte.html

C#:   list.Sum();  list.Average()
来源：http://dali.cashguo.top/Article/details/gtzjhmhmbk.html

[D17] 最大值与最小值
来源：http://dali.cdnleiting.top/Article/details/gtfktcahdz.html

Py:   max(arr);  min(arr)
来源：http://dali.pycfn.com/Article/details/gtzsjvrsah.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtiwnbqbns.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.ydzc1.top/Article/details/gtchrorvrz.html

TS:   Math.max(...arr);
来源：http://dali.jyoumei.cn/Article/details/gtsidgiqjv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yongpay.top/Article/details/gteewyigom.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.daxiang520.top/Article/details/gttbpagyaf.html

Ruby: arr.max;  arr.min
来源：http://dali.hongshengwenyu.top/Article/details/gtrrkcxpzd.html

C#:   list.Max();  list.Min()
来源：http://dali.yongpay.top/Article/details/gtacjurtqu.html

[D18] 扁平化嵌套数组
来源：http://dali.fengsongda.top/Article/details/gtktcrzudv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hysaishi.cn/Article/details/gtmijevkpm.html

PHP:  array_merge(...$nested);
来源：http://dali.shanyushiyangtech.top/Article/details/gtvkbzyadd.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.yj20258.top/Article/details/gtmkrexoxp.html

TS:   nested.flat();
来源：http://dali.yj20258888.top/Article/details/gtcvdmlxxd.html


<!-- 参考信息 -->