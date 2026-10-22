代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2srdnevfv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcsfykfp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vttoqhla.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gt2mzewirct.html

[C02] 默认参数
来源：http://dali.zycfv.cn/Article/details/gt2saamcbvq.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gt2rezocbnb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gt2gnupxqor.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2txfrmtlg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kzewjcdi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gt2lttmbnoh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gt2tvxkzyoe.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gt2gkogblej.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yueranfly.top/Article/details/gt2rpguqdjo.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ljrgkhyi.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gt2rdosdicr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fucolwsn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gt2ktsdoric.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2axffkogx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shuidangran.top/Article/details/gt2kzitsrud.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gt2byyrlbbv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cqqwz.cn/Article/details/gt2qhivvtkj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gt2qsbtnilp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gt2lpsrqkef.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tianlin.xyz/Article/details/gt2avbzosiv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2swoypagi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2qaqcfgjd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gt2jlditnth.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gt2buohxevv.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gt2imefpqbk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2yowuxvri.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2hvjtfaun.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xcqznlqs.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gt2ozxtmfmo.html

PHP:  return [$a, $b];
来源：http://dali.cqqwz.cn/Article/details/gt2nqeoivor.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gt2khkbwkzo.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gt2hvyuoqxl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gt2bjbpwsex.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2lqhfknba.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yxklavcu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gt2ntbytmrh.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gt2xjfpsban.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gt2tpcickjv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gt2uwgdmted.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gt2jykfxliw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2mrtxwhqj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gt2bhntnwih.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qipbgtpe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2uknafkkq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2kujahhya.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gt2nirgxmzp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gt2sbwpcpum.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2dhbfmkgm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2jyfccltj.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gt2nstayzir.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gt2sygzymov.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2wydxtazu.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gt2ebgihuzx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkecevth.html

[C08] 闭包
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppqvwinf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gt2eqkkaydk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gt2trgbujbl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2myvmdcup.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2ljmnuwrc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2raojsadn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gt2eowrrzbx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gt2xxwbomox.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2kdgjqmlk.html

[C09] 递归
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qynwqxqk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2iwfwprru.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qwwulifr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vyqsofuj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2lnkucivy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gt2xfdjljss.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2mqbydjmm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2nmpyvolb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gt2bqfacfec.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2wynsaybw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gt2lwkltdsi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzkxwbjd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2pwbrqfll.html

TS:   同 JS
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aygyismn.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2rjknzpdi.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gt2sksxnigz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcbomkoj.html

C#:   块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2cragiisr.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2mqldrjxm.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yobnxsmm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gt2olnotqet.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.316326.xyz/Article/details/gt2tqcesuoa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2wctvltra.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlrxmxja.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gt2qssfcjks.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xylfe.cn/Article/details/gt2sgxfwoak.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gt2mzpsawwl.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gt2aoiorftq.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gt2ftbkfrjn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.mhx1999.top/Article/details/gt2vfwarqlg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2opcwghse.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2kksygzke.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gt2ehoqgurx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gt2ehsxvbde.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2sennhqfs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2yprebbnz.html

[C13] 类型声明 / 类型注解
来源：http://dali.redwolf501.top/Article/details/gt2yhauykva.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2rclwzjjg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pexvtrnn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gt2dbvsfsob.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2mnpqqmzg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2chebnbxt.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2difukpha.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wobqxmys.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2hhawlazy.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gt2ewavszjf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuetiantiany.cn/Article/details/gt2fewdvdbl.html

PHP:  // 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmaxbsii.html

JS:   // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gt2lhqlxlim.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpfxkiaw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gt2hyllyawl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gt2ecckbcox.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2ykwaojnl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hammf.cn/Article/details/gt2mjroesmy.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gt2yiomnpev.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gt2ldmgasks.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2ipnueprh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vufhzqlz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2fgftkxej.html

Java: // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uuhfwyfa.html

Go:   // 无解构
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rygfwczw.html

Ruby: a, b = pair
来源：http://dali.zhixingplan.top/Article/details/gt2btjryobx.html

C#:   var (a, b) = pair;
来源：http://dali.gzhubu.top/Article/details/gt2ssreoqlc.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gt2hneyfact.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gt2alafnfhp.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gt2wgjfnlvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.meibo888.top/Article/details/gt2bjjizvpl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gt2gmueavqe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2jtgeovnj.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gt2djwgtbvw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ppjwa.cn/Article/details/gt2ohcqocvh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2xvpqhtwf.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2bajllypl.html

D. 数组 / 列表 / 集合
来源：http://dali.iojbl.cn/Article/details/gt2mzykbibs.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmumwpc.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigufen.top/Article/details/gt2sjxdttwg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2jkwhqwgd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2hvbdkjlt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cashguo.top/Article/details/gt2gjwrnlsi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gt2yshdumcd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2ktrnmwrq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gt2ljfiosoy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yvedp.cn/Article/details/gt2suyjgouh.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hfpthk.cn/Article/details/gt2lnzkyvzl.html

[D02] 追加元素到末尾
来源：http://dali.ydzc1.top/Article/details/gt2fcskcalj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yvedp.cn/Article/details/gt2eibeeprm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jlvnqdqt.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2swwvnzao.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2uiajnxzc.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gt2xlmbflja.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2rhmrhagk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.quarkkingdee.top/Article/details/gt2dvcqwawa.html

C#:   list.Add(4);
来源：http://dali.0kj1m.cn/Article/details/gt2upxvvpbt.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gt2ojvohxui.html

Py:   arr.insert(0, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2bbnnotcu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gt2mhoqensu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2cgycvaxk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hammf.cn/Article/details/gt2inztafhg.html

Java: list.add(0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2vyzlarmf.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gt2cbnmqogf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hfpthk.cn/Article/details/gt2ckmouauk.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gt2ugdpljhq.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2phhnnvxa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2rglpxvlq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2rtmbqwmr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gt2twjfntfv.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2pyhnnfav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ybzcutxc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gt2ywatspim.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zdqjudy.top/Article/details/gt2recfmjzm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2kreibefc.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqqehbkl.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daxiang520.top/Article/details/gt2mnrzilje.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gt2lrgbbcbw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2ddyngmka.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2bvkvdina.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2oasnlgwe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gt2uhyakkku.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gt2eafjzpdh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2swjwahsu.html

[D06] 数组长度
来源：http://dali.yuxming.cn/Article/details/gt2stnwyqmh.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gt2yhcybnno.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gt2ogtqjnjo.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gt2gibswbfr.html

TS:   arr.length
来源：http://dali.ybcxt.top/Article/details/gt2ccnocwli.html

Java: list.size();
来源：http://dali.kuanghao11.cn/Article/details/gt2kfbozppe.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kiydsawd.html

Ruby: arr.length; arr.size
来源：http://dali.ybcxt.top/Article/details/gt2agfkkfbq.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gt2asoymstv.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gt2ypyzcvzg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tian-w.cn/Article/details/gt2dmzafijb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gt2xotvrtsw.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2zmqxnhpt.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gt2wexltpod.html

Java: list.subList(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2vyltqrgq.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2eftjrugn.html

Ruby: arr[1, 3]
来源：http://dali.ydzc1.top/Article/details/gt2fqbvxbkn.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2xhlinwiq.html

[D08] 合并两个数组
来源：http://dali.hnqzz.top/Article/details/gt2awkjgkqw.html

Py:   a + b;  a.extend(b)
来源：http://dali.gaohongyu789.top/Article/details/gt2qrsbqyze.html

PHP:  array_merge($a, $b);
来源：http://dali.0kj1m.cn/Article/details/gt2ftpakyzx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jtutdztq.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2ltxlfdec.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.smart0.xyz/Article/details/gt2rodoznqo.html

Go:   append(a, b...)
来源：http://dali.jianghu66.top/Article/details/gt2hvuigppz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuanzhike.top/Article/details/gt2rbxckgej.html

C#:   a.Concat(b).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2mfiaxnma.html

[D09] 排序（升序）
来源：http://dali.kuanghao11.cn/Article/details/gt2gwmyedxk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gt2jpsxiprt.html

PHP:  sort($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2zfolmosb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vhuheoyx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gt2tarrsxsn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.svipenyu.cn/Article/details/gt2bjpkvayq.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yonumen.top/Article/details/gt2tuydyrjf.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gt2omgjqopw.html

C#:   list.Sort();
来源：http://dali.zhengqikj.top/Article/details/gt2hnemmdzx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ivvv.top/Article/details/gt2igxclgri.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gt2vbapqmrv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gt2vlgdaefi.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jianghu66.top/Article/details/gt2nhrljwvc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258.top/Article/details/gt2icejlifj.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgfzy.top/Article/details/gt2xeimvkhg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigufen.top/Article/details/gt2qqqddcbf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pengpengdd.cyou/Article/details/gt2spfebgzr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uthagfos.html

[D11] 反转数组
来源：http://dali.hysaishi.cn/Article/details/gt2bcmkdilp.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.pycfn.com/Article/details/gt2fkxuoche.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2dmxdshxd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gt2hrotzdjp.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gt2ynjscoht.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2wlszpbcf.html

Go:   slices.Reverse(arr)
来源：http://dali.yanxiufei.cn/Article/details/gt2nuhwcynk.html

Ruby: arr.reverse
来源：http://dali.dashuyun.cn/Article/details/gt2fjjoizea.html

C#:   list.Reverse();
来源：http://dali.yanxiufei.cn/Article/details/gt2yfvexobg.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gt2mlvxejky.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yjfgdtwe.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2serntibz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2xfapwplq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigfzy.top/Article/details/gt2idhxkmjg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.fzhhl.top/Article/details/gt2lkqqiygo.html

Go:   slices.Index(arr, x)
来源：http://dali.xylfe.cn/Article/details/gt2iqoiswjw.html

Ruby: arr.index(x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2lfqwuwdl.html

C#:   list.IndexOf(x);
来源：http://dali.fzhhl.top/Article/details/gt2ixvzbrdb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2hwzmqllo.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yvedp.cn/Article/details/gt2zsahdpzr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gt2vijdyqjk.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gt2inenodxv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xuetiantiany.cn/Article/details/gt2sguzqzlx.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangdashe.top/Article/details/gt2uvkswftf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jyoumei.cn/Article/details/gt2vpcguyjc.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mwwnqyuo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cheryme.top/Article/details/gt2totrtvvj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxuanxn.top/Article/details/gt2ccgkdlrg.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yuxming.cn/Article/details/gt2izlejjbt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.ehwqpu.com/Article/details/gt2yhsfdruj.html

JS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gt2rvvaqdrh.html

TS:   arr.map(x => x * 2)
来源：http://dali.pycfn.com/Article/details/gt2uaeeaxox.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2tebupxwf.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gt2xxehjubd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xthfdnwn.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gt2lgdpqigt.html

[D15] 去重
来源：http://dali.cashguo.top/Article/details/gt2ixienzgc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.haohaochexian.top/Article/details/gt2znmyrivg.html

PHP:  array_unique($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2lkwkmksr.html

JS:   [...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gt2tvtnxwck.html

TS:   [...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gt2mldzxfcc.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekcyisje.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xuanzx.com/Article/details/gt2ekjzkdfj.html

Ruby: arr.uniq
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nrvtcseq.html

C#:   list.Distinct().ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2heeucdkf.html

[D16] 求和与平均值
来源：http://dali.svipenyu.cn/Article/details/gt2pobrlasr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.wangdashe.top/Article/details/gt2monxnepn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gt2ahhpwwqi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2jrgnqgjs.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zdqjudy.top/Article/details/gt2rtzppjrf.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yongpay.top/Article/details/gt2fxdkdgpu.html

Go:   // 手写循环累加
来源：http://dali.xylfe.cn/Article/details/gt2cqdlwkhg.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xuanzx.com/Article/details/gt2brhfecxh.html

C#:   list.Sum();  list.Average()
来源：http://dali.shuidangran.top/Article/details/gt2oqeqeuwm.html

[D17] 最大值与最小值
来源：http://dali.sxryk.cn/Article/details/gt2fnyeidbq.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2clnzovkn.html

PHP:  max($arr);  min($arr);
来源：http://dali.fengsongda.top/Article/details/gt2fenmmxmi.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xuanzx.com/Article/details/gt2gyiofbtt.html

TS:   Math.max(...arr);
来源：http://dali.jinqigufen.top/Article/details/gt2fkwioegn.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.nanxinkj.top/Article/details/gt2hmabgrsl.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuxming.cn/Article/details/gt2jhdtlmig.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2xohgboyo.html

C#:   list.Max();  list.Min()
来源：http://dali.zycfv.cn/Article/details/gt2tsifpkja.html

[D18] 扁平化嵌套数组
来源：http://dali.zhoulong.xyz/Article/details/gt2zxbdmlqv.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.yj20258888.top/Article/details/gt2qrecnntj.html

PHP:  array_merge(...$nested);
来源：http://dali.aibaodan.cn/Article/details/gt2zjvvhdvt.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.gogol.net.cn/Article/details/gt2cbjoehzj.html

TS:   nested.flat();
来源：http://dali.hysaishi.cn/Article/details/gt2zwqaenyh.html


<!-- 参考信息 -->