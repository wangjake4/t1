代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2vjqqhrsb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gt2dwkyxyae.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gt2wsvxunnr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2rrbcduoo.html

[C02] 默认参数
来源：http://dali.yvedp.cn/Article/details/gt2rkklodzs.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gt2xuvfqhdu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gt2vnvpvftv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2tiylnhps.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gt2adflheke.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2diurdalv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gt2jkwmbojp.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2pteelnji.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.mhx1999.top/Article/details/gt2acpyhcqt.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gt2tugdwmif.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gooqticx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.wangdashe.top/Article/details/gt2gpxzjqwi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2qdtmfmgf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2qyagbqlg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gt2ydrcwvmn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sweek.top/Article/details/gt2utvciigk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gt2mywtltfe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2rsqvqcjz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2iqumfzqj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gt2dypdygfs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2bamnzrtz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2pfgtauqq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gt2hvqpqgmf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gt2shrlrowq.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gt2pgvkgluk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2nepajhzm.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gt2vdlyongz.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2kpjyqwmt.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gt2uoaxeqoe.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gt2kodaiamn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gt2gtmkaxyr.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2jlfridpd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2ximkfbgv.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gt2gqtzrqcp.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2gysxihnl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2edgprfmn.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2rggtxqlr.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gt2pduiyodp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2psjrltrr.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2grpcitfo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gt2wydywmss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2geberlqj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gt2oualhxeq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2emxcnzrb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2udqhnuic.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gt2ulffaplu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gt2uomfahyj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2bcledspj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.pycfn.com/Article/details/gt2fvkbegtt.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gt2vscqvlmp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gt2layqufuu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gt2yxuungut.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gt2xfcbxsta.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gt2maibjixc.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2ygcrrnbu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cashguo.top/Article/details/gt2mhzvpoyq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gt2jwbcystx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2rlnuvono.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2vnnwogok.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gt2ujlvuegz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gt2vrpufwyb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2xgggjbqw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gt2ssnccicg.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2vitqhkus.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gt2wjxnasoe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gt2fecyhcgg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gt2wxrfriyu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2eprorwrw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2pscnhxrp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gt2pgttsibu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrytncym.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gt2llzarorp.html

[C10] 变量作用域
来源：http://dali.cdnleiting.top/Article/details/gt2oraantlk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gt2tjuzsvrq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.9152youxi.cn/Article/details/gt2bqgriirm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gt2ifcsveds.html

TS:   同 JS
来源：http://dali.chenzaomai.com/Article/details/gt2bavclgxy.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gt2dhgriniw.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gt2iiioqrue.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gt2ofucjpvg.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2stadudeq.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gt2pnptufrn.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gt2tylvzrnz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.quarkkingdee.top/Article/details/gt2vxiliefn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2nupfvfme.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gt2sqybrnoj.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gt2foyjvmty.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ysskzwpi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gt2bgvyppqk.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zlhmyoid.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gt2iynxscfe.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gt2acqlhysa.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gt2oedcossw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2fpfvrchm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prolubai.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gt2xivitbzy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.bjfxy.top/Article/details/gt2xvgbhvry.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gt2ksjjysfm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gt2snitkdue.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2bosqczgy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgfzy.top/Article/details/gt2aqwmbxbw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2qwfggzbs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhoulong.xyz/Article/details/gt2xxtlblbo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2bjtsuobw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gt2hefsfstr.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gt2krktxlnb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2xrnojdvz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gt2lwgxeayv.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gt2nkxbocbj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.haohaochexian.top/Article/details/gt2ggglblbm.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gt2eagbjfik.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2wraegsjk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gt2mwyjtrgw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenlongwang.top/Article/details/gt2hrxjgoqg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zdqjudy.top/Article/details/gt2rdzlykzg.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gt2bjugpjwf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2cfpvhsxv.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2eoqxqpdl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gt2ipqzwwye.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gt2jeuspjls.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2dpxmryth.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pycfn.com/Article/details/gt2elsfcqrh.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gt2fskziyvi.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2mmviticz.html

Ruby: a, b = pair
来源：http://dali.shuidangran.top/Article/details/gt2kpnfrsnu.html

C#:   var (a, b) = pair;
来源：http://dali.zhijiandao.cn/Article/details/gt2jnycdjgf.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rocutujw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2plpdufgr.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gt2nwdfktec.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2vgucttmm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2comodhii.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gt2mguktkle.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gt2hrhbozwc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nwbrower.top/Article/details/gt2fbgqmsst.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yueranfly.top/Article/details/gt2mftgmrbq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2piwnrfsu.html

D. 数组 / 列表 / 集合
来源：http://dali.xuetiantiany.cn/Article/details/gt2qagmzpvx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2rfamcdet.html

[D01] 创建数组 / 列表
来源：http://dali.yonumen.top/Article/details/gt2crczacrc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yangfankeji.com/Article/details/gt2nsbokoej.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jicegewy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.316326.xyz/Article/details/gt2jocidaah.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gt2imgqwiqt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jlsjyb.cn/Article/details/gt2nlldeysv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guowangkeji.top/Article/details/gt2thfxxxiv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yonumen.top/Article/details/gt2canfgrjw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoruqmfo.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gt2ysjvbszm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gt2irfcfjyv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yueranfly.top/Article/details/gt2wogypayf.html

JS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2bnqunzlk.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2cnectfey.html

Java: list.add(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cdtmdbnl.html

Go:   arr = append(arr, 4)
来源：http://dali.jyoumei.cn/Article/details/gt2tdnhuoec.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xinyue.icu/Article/details/gt2cnsokjsn.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2wdticpzn.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gt2yhkvtezy.html

Py:   arr.insert(0, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2qxpnqzlj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.316326.xyz/Article/details/gt2rfwhntjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2xcnxvxxc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2gmfwqnhv.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2gptdgymu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj202588.top/Article/details/gt2tegyilrn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2auqkjcff.html

C#:   list.Insert(0, 0);
来源：http://dali.tian-w.cn/Article/details/gt2uthdnmni.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gt2ewvthqhg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gt2znghirbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2mweeuobx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gt2bsjduvff.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gt2eikzqoel.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj20258888.top/Article/details/gt2mhljapiz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gt2hcjmeuiw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gt2upouprbq.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gt2lcphdvmg.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gt2tndwxvdq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2chklsvlg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2ednjsbba.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gt2ozjuaowi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shuidangran.top/Article/details/gt2dyteeyts.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhijiandao.cn/Article/details/gt2wixedfke.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gt2movryaeg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhixingplan.top/Article/details/gt2vdsfptgj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2jvcnzyqx.html

[D06] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2tghaonpp.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gt2sugvafxq.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2omlvyddi.html

JS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gt2rqftjjbf.html

TS:   arr.length
来源：http://dali.jinqigfzy.top/Article/details/gt2tvrqjkxo.html

Java: list.size();
来源：http://dali.fzhhl.top/Article/details/gt2gtxenkfl.html

Go:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2befdadvs.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2dhupvrag.html

C#:   list.Count;
来源：http://dali.gogol.net.cn/Article/details/gt2iskyuqry.html

[D07] 切片 / 取子数组
来源：http://dali.xylfe.cn/Article/details/gt2vxveijew.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.mhx1999.top/Article/details/gt2vkkemqrm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2wzhbcevb.html

JS:   arr.slice(1, 4);
来源：http://dali.dianchejie.cn/Article/details/gt2grhddwed.html

TS:   arr.slice(1, 4);
来源：http://dali.wangdashe.top/Article/details/gt2xfkbzwbc.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gt2aaqeieey.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gt2xqbtcjfm.html

Ruby: arr[1, 3]
来源：http://dali.yongpay.top/Article/details/gt2peavisdp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiitbmqj.html

[D08] 合并两个数组
来源：http://dali.havefunace.top/Article/details/gt2dnbyuutx.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2lonlidwq.html

PHP:  array_merge($a, $b);
来源：http://dali.tanke756.top/Article/details/gt2nckjiaho.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eeiwxzqn.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gt2ggbcukes.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xylfe.cn/Article/details/gt2bjfexffy.html

Go:   append(a, b...)
来源：http://dali.bjfxy.top/Article/details/gt2mzhyowle.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2sticgpoh.html

C#:   a.Concat(b).ToList()
来源：http://dali.hnqzz.top/Article/details/gt2ouzdbkek.html

[D09] 排序（升序）
来源：http://dali.zhixingplan.top/Article/details/gt2dyhlpxeu.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sufxvd.cn/Article/details/gt2lxjvrpeg.html

PHP:  sort($arr);
来源：http://dali.shzxlz.cn/Article/details/gt2qvefgtbf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhoulong.xyz/Article/details/gt2lqyguqjt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gt2zepawrhv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yongpay.top/Article/details/gt2vkbcqetf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cheryme.top/Article/details/gt2zfszccaw.html

Ruby: arr.sort
来源：http://dali.cdnleiting.top/Article/details/gt2yffomdki.html

C#:   list.Sort();
来源：http://dali.yuanzhike.top/Article/details/gt2zbroytlp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xziqi.cn/Article/details/gt2nmwrykrp.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gt2zgdjlzgw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2ggbrsjqs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gt2kqkmfrsa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pycfn.com/Article/details/gt2sdtxzipm.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.meibo888.top/Article/details/gt2tbiujkxg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.smart0.xyz/Article/details/gt2zaneipox.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gt2bzkxlfkh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nanxuanxn.top/Article/details/gt2rgxtdpoz.html

[D11] 反转数组
来源：http://dali.smart0.xyz/Article/details/gt2junhmxqk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gzhubu.top/Article/details/gt2evluvjou.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gt2vyoblyli.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zdqjudy.top/Article/details/gt2pwmnlcio.html

TS:   [...arr].reverse();
来源：http://dali.cucudq.cn/Article/details/gt2rendgjhn.html

Java: Collections.reverse(list);
来源：http://dali.jqgufenzy.top/Article/details/gt2ktvinqdj.html

Go:   slices.Reverse(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2brlxmxpn.html

Ruby: arr.reverse
来源：http://dali.yvedp.cn/Article/details/gt2ozwaficn.html

C#:   list.Reverse();
来源：http://dali.gogol.net.cn/Article/details/gt2rcojinhj.html

[D12] 查找元素下标
来源：http://dali.yuanzhike.top/Article/details/gt2zpgcfcxd.html

Py:   arr.index(x);  x in arr
来源：http://dali.mhx1999.top/Article/details/gt2nlpscvyc.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yueranfly.top/Article/details/gt2tlzkxhin.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gt2smeiobkk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2mwcsmnqq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.shzxlz.cn/Article/details/gt2wjqtohzv.html

Go:   slices.Index(arr, x)
来源：http://dali.sxryk.cn/Article/details/gt2pzapcfsb.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gt2zlbijqbm.html

C#:   list.IndexOf(x);
来源：http://dali.nwbrower.top/Article/details/gt2udcefolg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xuanzx.com/Article/details/gt2cwaqehph.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.meibo888.top/Article/details/gt2occsudno.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.aizwys.cn/Article/details/gt2hnqzegbm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2esqhihzc.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yuanzhike.top/Article/details/gt2flwrxbbu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gt2wwkacxhu.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aizwys.cn/Article/details/gt2qkvwufdt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gxhyrtut.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdxivlcu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gzhubu.top/Article/details/gt2ppnodnqe.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gt2cnqzlylw.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gt2gfyxzvhf.html

JS:   arr.map(x => x * 2)
来源：http://dali.andypj.xyz/Article/details/gt2xpdvwbmk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yongpay.top/Article/details/gt2ffnrrnpi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.pycfn.com/Article/details/gt2mqbdheff.html

Go:   // 手写循环
来源：http://dali.ivvv.top/Article/details/gt2pzxrvzix.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2emvkibdt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigufen.top/Article/details/gt2lhbmycnd.html

[D15] 去重
来源：http://dali.yj20258.top/Article/details/gt2homvrcgx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gt2yewmbthy.html

PHP:  array_unique($arr);
来源：http://dali.hammf.cn/Article/details/gt2axmdiqqq.html

JS:   [...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2ineyncwd.html

TS:   [...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxvqtqd.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2npeejhcd.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.dashuyun.cn/Article/details/gt2cmgvusyr.html

Ruby: arr.uniq
来源：http://dali.jiagoushi.top/Article/details/gt2gdvxzmlw.html

C#:   list.Distinct().ToList()
来源：http://dali.aizwys.cn/Article/details/gt2gqactwjg.html

[D16] 求和与平均值
来源：http://dali.zhijiandao.cn/Article/details/gt2tigjimsv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2hifujaad.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.meibo888.top/Article/details/gt2jfmwxcuq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gt2ouyrbovh.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tjcwsvqv.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.dashuyun.cn/Article/details/gt2oczbpfey.html

Go:   // 手写循环累加
来源：http://dali.dianchejie.cn/Article/details/gt2uruafozq.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.fzhhl.top/Article/details/gt2scvhnnfx.html

C#:   list.Sum();  list.Average()
来源：http://dali.kuanghao11.cn/Article/details/gt2zrsttaot.html

[D17] 最大值与最小值
来源：http://dali.nanxinkj.top/Article/details/gt2aidnvrkv.html

Py:   max(arr);  min(arr)
来源：http://dali.0kj1m.cn/Article/details/gt2tljyrvfj.html

PHP:  max($arr);  min($arr);
来源：http://dali.tanke756.top/Article/details/gt2blcawera.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2durosnbb.html

TS:   Math.max(...arr);
来源：http://dali.yonumen.top/Article/details/gt2miaooero.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.snrcjt.cn/Article/details/gt2vhdzmdzg.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.redwolf501.top/Article/details/gt2brjbkcfw.html

Ruby: arr.max;  arr.min
来源：http://dali.hnxiangtu.top/Article/details/gt2sirngnae.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gt2fdfscxwk.html

[D18] 扁平化嵌套数组
来源：http://dali.iojbl.cn/Article/details/gt2pixraiqk.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.aibaodan.cn/Article/details/gt2frchpawd.html

PHP:  array_merge(...$nested);
来源：http://dali.xziqi.cn/Article/details/gt2ydibjcxp.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.shuidangran.top/Article/details/gt2cjysopmq.html

TS:   nested.flat();
来源：http://dali.cashguo.top/Article/details/gt2dxljdlij.html


<!-- 参考信息 -->