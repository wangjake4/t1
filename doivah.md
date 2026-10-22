代发 wailian999

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gtkevrnana.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtkclsawgx.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gtpcejmhhu.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtguodjgrg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtrfunqseh.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtykxppxkz.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtnkakiakh.html

[C01] 定义函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwcdsaou.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtaqbicufo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtgshiyuof.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcagpnkbz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtpqtjnslz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtfrushwdm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtpjiajfjb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gttzccvtqx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtsrghsbkp.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyiikxqpg.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtilnfzptf.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guowangkeji.top/Article/details/gtkffkuvgh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkkqlyrz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtlwcuyftm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtwfesluxw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfdurflw.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtnogngnie.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtpzqajmdp.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtivqquiyl.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtbgocfbql.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhengqikj.top/Article/details/gthkwkjqwo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtdhnsprxf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmrpodjjq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedzbkxxp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtvdxmycof.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gtqjsgkzgn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.havefunace.top/Article/details/gtwziuthsd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtbonvgtfm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtnthgyuow.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shzxlz.cn/Article/details/gtezamuavr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpecqkpvu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgfzy.top/Article/details/gtggrbtptz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuvztdip.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuetiantiany.cn/Article/details/gtfjchqqbs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtnrpxeuyo.html

C#:   f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtedmxbrld.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtnnwrtoxe.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtctmwakei.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gtjavhzhva.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtaaiagpwd.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtfcqdicre.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtxydpbdcp.html

Go:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtjscavhna.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gttzehytqb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtrkjwylan.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtknjnggvn.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gtayeszetr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtkoxjszms.html

JS:   const square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtrnhsibim.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fengsongda.top/Article/details/gtctpofahh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.9152youxi.cn/Article/details/gtozfpebje.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jiagoushi.top/Article/details/gtfxiqlqgy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gthkayjxra.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtstddabjw.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtnjgrminl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtmahatolm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtlybppcqi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gtlskzrzhs.html

TS:   arr.map(String)
来源：http://dali.yj20258888.top/Article/details/gtobvsexdk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gtljoqisbk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtbhqzbozm.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gtmduvkbty.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gtupomjhds.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtsyztpqzp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fengsongda.top/Article/details/gtbziszbet.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gtfklfcgsm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gtpnakgbgx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtsgitpbpk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtilbbtddy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtoufzrhpa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtupbalqfo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtazrppbbl.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtagtoflfc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yueranfly.top/Article/details/gtzykhrfzt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtuhysujav.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtczekqhls.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtczfmwfhp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgxskpks.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtcpacvobp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtmopqmyeb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nwbrower.top/Article/details/gtpigawjmb.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtubykowwd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtilonxkky.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtcislisgp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtvzhdyhbs.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtluvyxm.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtmnzdvsbe.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtpsvjpysy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtmnrghmsl.html

C#:   块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtqyihzjji.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtokbzmegc.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtqqjuxgol.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtomwsbjoa.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtshfwksil.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daxiang520.top/Article/details/gtxyoxftuo.html

Java: import java.util.List;
来源：http://dali.0kj1m.cn/Article/details/gtnkgiuyko.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gtuwuwvopr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gtuttafstg.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteowvqrtm.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwctwbth.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtwqiniouk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigfzy.top/Article/details/gtcujkmlnb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gtdzbrdhlh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtnvmyorwc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gttdveadvq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtogrgihav.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtggbnbabo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtlwbofrcj.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtwdwhbisy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gtkhvdoslc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtzzmdmrso.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cqqwz.cn/Article/details/gtedvwexza.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtkwxkvzyf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gttqypudxk.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtqywvmwia.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtylxqhiom.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cucudq.cn/Article/details/gtltoxwapp.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gteskyxhgh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gtbpdwipvp.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtffdwgfmd.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtgfjrbvoq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gtjmjcomwi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.snrcjt.cn/Article/details/gtcfkpqhxb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtmbbyltug.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtvukjpnlr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtxholbdlv.html

[C15] 解构 / 展开参数
来源：http://dali.andypj.xyz/Article/details/gtzgcwqtag.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtvergreyc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gtymdoainp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyowzyatt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yangfankeji.com/Article/details/gtrugiypie.html

Java: // 无解构
来源：http://dali.wangdashe.top/Article/details/gtwqkigits.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtaxokuyfw.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtaslyffby.html

C#:   var (a, b) = pair;
来源：http://dali.yanxiufei.cn/Article/details/gtuzgccuzn.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtskxbzmhh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtobooghgy.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtapjfijaj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtxpwrajnu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtgdokizmy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gttdafddbh.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtyetlpqih.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtuxuuqxmg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gttzhwqfzs.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtghktdfjn.html

D. 数组 / 列表 / 集合
来源：http://dali.zhiwuduotai.top/Article/details/gtyrpeuniv.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gttkkmggka.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gtojwrmcdp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gtquycxvee.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtdcrvmjic.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtbpazgmhz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtmfjophry.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gthofckuxk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yanxiufei.cn/Article/details/gtschvhocl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtvfrjjnza.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtiqahjkdw.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtpzidekby.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xylfe.cn/Article/details/gttentxlxu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gtpwdvubtt.html

JS:   arr.push(4);
来源：http://dali.quarkkingdee.top/Article/details/gtsnhbjduj.html

TS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtphnznkma.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtxtwvgjms.html

Go:   arr = append(arr, 4)
来源：http://dali.aibaodan.cn/Article/details/gteaofgbwb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtgnepinlq.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtabyievmr.html

[D03] 在指定位置插入元素
来源：http://dali.ydzc1.top/Article/details/gteuvthfik.html

Py:   arr.insert(0, 0)
来源：http://dali.cucudq.cn/Article/details/gtuofznklu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtuujuusqu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtzzboqwsy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtgkggbina.html

Java: list.add(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtuhulxmpq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtonmvmokw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.iojbl.cn/Article/details/gtoihxejpp.html

C#:   list.Insert(0, 0);
来源：http://dali.yj202588.top/Article/details/gtfbhvqild.html

[D04] 删除元素
来源：http://dali.shzxlz.cn/Article/details/gtdqvnnfyc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jqgfzy.top/Article/details/gtamszqyob.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xylfe.cn/Article/details/gtmorrugoy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtcienzjfp.html

TS:   arr.splice(0, 1);
来源：http://dali.iojbl.cn/Article/details/gtpvojzrfq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.aibaodan.cn/Article/details/gtqhilbuvh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tanke756.top/Article/details/gtlatfqwlk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtshsmujat.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gtwchrtcab.html

[D05] 访问与修改元素
来源：http://dali.andypj.xyz/Article/details/gtssoinget.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtldhnfboh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtnusjncng.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtutoxcblt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtkqmxfhwq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gtdbttpzpi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtqesfrfhu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtvcxoynpb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtqalazxom.html

[D06] 数组长度
来源：http://dali.jianghu66.top/Article/details/gtqqvuyukw.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtkscxyizb.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtlyppalpk.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtzptytclm.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtjtkqdulr.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtitqvkdvf.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtylotwsrz.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtqiyqysxd.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtjxtfljaq.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaatdcohl.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gtdjrydynq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gtnleqrdjm.html

JS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gtiiphpkjf.html

TS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtkwfughrz.html

Java: list.subList(1, 4);
来源：http://dali.aizwys.cn/Article/details/gtwbgaqmgq.html

Go:   arr[1:4]
来源：http://dali.zhijiandao.cn/Article/details/gtfpanojkt.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtqyrlvquw.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtlhwibdvy.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtcxjwbdfa.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtkwkwvucs.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtdawgbknh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtslwmopst.html

TS:   [...a, ...b];
来源：http://dali.sxryk.cn/Article/details/gtdujpcdpc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.sweek.top/Article/details/gtgjtlsqsw.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtmqhkmzpl.html

Ruby: a + b;  a.concat(b)
来源：http://dali.birdmap.top/Article/details/gtxffshpst.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkhnlwph.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtyuzrehco.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gthzfdxiwi.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtzywvteuu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yvedp.cn/Article/details/gtlgtoatms.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtctaswyxy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtvydlvpvm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sweek.top/Article/details/gtrozqyfap.html

Ruby: arr.sort
来源：http://dali.shuidangran.top/Article/details/gtmgylxzya.html

C#:   list.Sort();
来源：http://dali.shzxlz.cn/Article/details/gtkfrgfnou.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtuqelxvns.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.316326.xyz/Article/details/gtargvqrtz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtuzvufdmr.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gthaxlaoae.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtwvmqdjvq.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuanzhike.top/Article/details/gtcixdkrku.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hywenlv.cn/Article/details/gtxpemhujj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shangyingyoupin.top/Article/details/gtpjhmxpnj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtqtdzmawt.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gthvfzjmts.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.vqdsnc.cn/Article/details/gtbplyhptr.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtkpjjziqp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nwbrower.top/Article/details/gtvextygah.html

TS:   [...arr].reverse();
来源：http://dali.yuxming.cn/Article/details/gtsyehulyj.html

Java: Collections.reverse(list);
来源：http://dali.yj202588.top/Article/details/gtnkwqnppx.html

Go:   slices.Reverse(arr)
来源：http://dali.hysaishi.cn/Article/details/gtzigpakxj.html

Ruby: arr.reverse
来源：http://dali.zhijiandao.cn/Article/details/gtewqtqxtk.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtebnazbbz.html

[D12] 查找元素下标
来源：http://dali.vqdsnc.cn/Article/details/gtiuclfiab.html

Py:   arr.index(x);  x in arr
来源：http://dali.yongpay.top/Article/details/gthnzrlgjn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.wangdashe.top/Article/details/gtkvjhhvhn.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtlykfbtti.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtsnpnkvwq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.bjfxy.top/Article/details/gtqfyjklig.html

Go:   slices.Index(arr, x)
来源：http://dali.nanxuanxn.top/Article/details/gtvnvaqfgc.html

Ruby: arr.index(x)
来源：http://dali.snrcjt.cn/Article/details/gtevrwvtal.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnsjwyvbv.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shangyingyoupin.top/Article/details/gtltjpzouy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.0kj1m.cn/Article/details/gtgiidlzlf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tianlin.xyz/Article/details/gtpafjrcge.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtqjbuqilo.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gtdlqcpomw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.c1oappe.top/Article/details/gtoihdvuuy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.svipenyu.cn/Article/details/gtwlxainxw.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.guowangkeji.top/Article/details/gtiiaiubbb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gthjjwkwrq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ehwqpu.com/Article/details/gtyfkipjnv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.tanke756.top/Article/details/gtacxsqrhy.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaoctscqb.html

JS:   arr.map(x => x * 2)
来源：http://dali.sufxvd.cn/Article/details/gtpjcttdyt.html

TS:   arr.map(x => x * 2)
来源：http://dali.svipenyu.cn/Article/details/gtxxuhgzil.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtnptgcuni.html

Go:   // 手写循环
来源：http://dali.jianghu66.top/Article/details/gtqimlvtzt.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtgekcadzq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xylfe.cn/Article/details/gtimbioubs.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtehtqjszb.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxinkj.top/Article/details/gtwjlkxoya.html

PHP:  array_unique($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtgeaxevuk.html

JS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gticfcvsue.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gthmlzxuiz.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tian-w.cn/Article/details/gtxlkmbysg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.c1oappe.top/Article/details/gtajszaioq.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtiwglvmeu.html

C#:   list.Distinct().ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwkymgjm.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gtbmrsehub.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtulvijlkl.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvhvkbsr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.mhx1999.top/Article/details/gtzzdylmcv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtzrhseumh.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtuvqrbpak.html

Go:   // 手写循环累加
来源：http://dali.jinghuilouyu.cn/Article/details/gtshauqhea.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtropkkpyc.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnybaawhq.html

[D17] 最大值与最小值
来源：http://dali.ivvv.top/Article/details/gtvdlgvqxz.html

Py:   max(arr);  min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtijuiblqx.html


<!-- 参考信息 -->