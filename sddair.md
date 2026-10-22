代发 wailian999

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2bcepsmdf.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tekxahsa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gt2vezzsdug.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gt2jalwhujm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2mogskcdg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dashuyun.cn/Article/details/gt2oysotbka.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2bpcqbbcq.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gt2bywxpcay.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gt2wataxnyn.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2ealwznkl.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gt2vrbphkrz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.vqdsnc.cn/Article/details/gt2qdatfxgh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zzrdkgcd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mqlmadug.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gt2lkewpxtt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2rjwhnrjq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gt2toiktnpm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2ukjcpemp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lubbofmo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hfpthk.cn/Article/details/gt2uzgbmyio.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2acsvpibx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2oatviobi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gt2rcylxqoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangshuangyany.cn/Article/details/gt2wrmydyfi.html

Go:   // 无：用配置结构体参数
来源：http://dali.mhx1999.top/Article/details/gt2kxqgecuj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gt2swbjdysg.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2brmwpbxt.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gt2dvjqjuuz.html

Py:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2daxnmajc.html

PHP:  return [$a, $b];
来源：http://dali.jlsjyb.cn/Article/details/gt2xkxnzxvu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gzhubu.top/Article/details/gt2gwbixjcg.html

TS:   return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gt2ggghlino.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gt2izdhgwvf.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gt2dlneqrhc.html

Ruby: return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2qsitkvnz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2dvainxpy.html

[C06] 匿名函数 / lambda
来源：http://dali.yanxiufei.cn/Article/details/gt2ewzocurg.html

Py:   square = lambda x: x * x
来源：http://dali.cqqwz.cn/Article/details/gt2nxedytwf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gt2ojnfflqu.html

JS:   const square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2ypgjuuae.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2kuauejsf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2salxqfcy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.bjfxy.top/Article/details/gt2wxjmdjux.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2tnhpagar.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gt2tqkvxcyv.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfdhirps.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sysykeji.top/Article/details/gt2xosqudwq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wlmiddhu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmyjwxkl.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gt2vvtdwerv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.havefunace.top/Article/details/gt2gfzreyvj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gt2ownalumn.html

Ruby: arr.map(&:upcase)
来源：http://dali.hysaishi.cn/Article/details/gt2rabyiheh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gt2ifbrwgae.html

[C08] 闭包
来源：http://dali.yonumen.top/Article/details/gt2wnjpfrgh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gt2jwsudvqz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.iojbl.cn/Article/details/gt2gdsrdzgx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2xyywmgfc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gt2ajjphoye.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tsehfltf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gt2qielzffq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gt2tzphzvqz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2yvvtnlts.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gt2gfjtclys.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gt2wioksvgi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gt2eijnjsim.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2apztfgyn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gt2zdjcowtx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jyoumei.cn/Article/details/gt2gwqdybzo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gt2bmmpardw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2waqufgor.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gt2dzaicoil.html

[C10] 变量作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2ikkzvitd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gt2xkewfljn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gt2qfhloekh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2qnoghimf.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2rbzksysp.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2yeyduvkg.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2zfjvsqbx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cucudq.cn/Article/details/gt2afmnqjkx.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2tbrntjiw.html

[C11] 模块导入与导出
来源：http://dali.yonumen.top/Article/details/gt2snyilgno.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uqdhcecm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ditwjapn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2qlwsnovr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gt2gygkdtwp.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gt2lcilzosw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gt2qhbjrkqa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gt2fuobvqzt.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2etugeybc.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gt2hbauoffg.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2rttgeljm.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2zfbrbtaw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gt2iiqnpsgf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2cvzkigfy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2aihajyvx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj202588.top/Article/details/gt2dslwmfeg.html

Ruby: -> { puts "run" }.call
来源：http://dali.hywenlv.cn/Article/details/gt2gmgcxevr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbogherv.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2pqxsnpuj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.pycfn.com/Article/details/gt2zlviwkgm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2zrwhkaue.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ppjwa.cn/Article/details/gt2vhfmfhac.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2qgwukasy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2argvijqi.html

Go:   func add(a, b int) int
来源：http://dali.cqqwz.cn/Article/details/gt2yrnqungb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuetiantiany.cn/Article/details/gt2vdcrwdvt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gt2stfsimxg.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gt2chbcjyrt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gt2qhdefpva.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gt2cuqzqjwb.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gt2whnvedej.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2tsybzhgl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2dpoxsdeo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.meibo888.top/Article/details/gt2fddmuxuk.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2jmgmkbfd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gt2veviukoh.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gt2ftsckade.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2bxewaiqf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gt2valfbgum.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gt2qqgrlqju.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2uljxflpk.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gt2mfheuzoh.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gt2mbluxtnm.html

Ruby: a, b = pair
来源：http://dali.gotoacloud.top/Article/details/gt2wfqbpoyf.html

C#:   var (a, b) = pair;
来源：http://dali.yj202588.top/Article/details/gt2pjrcpcdc.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnswbaq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sysykeji.top/Article/details/gt2iacdainj.html

PHP:  // 无重载
来源：http://dali.yj20258888.top/Article/details/gt2rcrwtils.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2moukudmm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gt2vvimmoab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.snrcjt.cn/Article/details/gt2ityxyrqx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2ihmrucmq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.aibaodan.cn/Article/details/gt2kklirpjk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qexdaxug.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2nyfqdqax.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gt2wabrwhel.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2avpvuwki.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2pqycfvej.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gt2izsndafh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgekrbza.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2zlrehpjr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gt2mkjdxfki.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gt2tekxozkd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2xddkadlh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2bvptwclk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dianchejie.cn/Article/details/gt2ixieamup.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gt2vzpeenaa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aibaodan.cn/Article/details/gt2jxobetxs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.haohaochexian.top/Article/details/gt2ddkkcxxp.html

JS:   arr.push(4);
来源：http://dali.jiagoushi.top/Article/details/gt2hwxmzteq.html

TS:   arr.push(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2cdbaoays.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2zvdeobwb.html

Go:   arr = append(arr, 4)
来源：http://dali.guowangkeji.top/Article/details/gt2mpcjtrjx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdvejelo.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2cvdsbfmc.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gt2nadhhlhu.html

Py:   arr.insert(0, 0)
来源：http://dali.0kj1m.cn/Article/details/gt2qcfzonec.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmqqsune.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gt2soxggfef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2cghxyvkb.html

Java: list.add(0, 0);
来源：http://dali.ydzc1.top/Article/details/gt2qpanybup.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhoulong.xyz/Article/details/gt2bbjuzhuy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yangfankeji.com/Article/details/gt2yljkcszp.html

C#:   list.Insert(0, 0);
来源：http://dali.ppjwa.cn/Article/details/gt2casswxcq.html

[D04] 删除元素
来源：http://dali.zhoulong.xyz/Article/details/gt2nsyefxvp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zdqjudy.top/Article/details/gt2ebulpfmp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2fpdbdohc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhixingplan.top/Article/details/gt2djirovhy.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gt2aebqiwly.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2loehpmcr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2sscinjbz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gt2zdlxuqxu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mhlyuzen.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lpsghbac.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gt2oeputumc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2etoeguvj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2hkoqybpg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zycfv.cn/Article/details/gt2vmpzocwg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gt2szywhvly.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gt2uwcakvjp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2iqebuzuz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gt2hpaaavet.html

[D06] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gt2njmgknlr.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gt2gfyfioag.html

PHP:  count($arr);
来源：http://dali.cdnleiting.top/Article/details/gt2pdqpgqlm.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gt2itptcehg.html

TS:   arr.length
来源：http://dali.daria6918.cn/Article/details/gt2nlhbyaym.html

Java: list.size();
来源：http://dali.nwbrower.top/Article/details/gt2hcjaxrze.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gt2wvghzpvz.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gt2jxvevnvz.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gt2wyszcdki.html

[D07] 切片 / 取子数组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhkyqpgg.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangshuangyany.cn/Article/details/gt2tschuduf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ybcxt.top/Article/details/gt2kgtydufu.html

JS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2qjulnbyo.html

TS:   arr.slice(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gt2lmeuckss.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gt2fobgybgz.html

Go:   arr[1:4]
来源：http://dali.hammf.cn/Article/details/gt2wtiqtzdz.html

Ruby: arr[1, 3]
来源：http://dali.shuidangran.top/Article/details/gt2fsfifriv.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gt2qveklrrr.html

[D08] 合并两个数组
来源：http://dali.shuidangran.top/Article/details/gt2pgcblekg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gt2prvtoczq.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2ocvaqbpp.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gt2qggfaakg.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gt2kaqttdpf.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2shvkgynl.html

Go:   append(a, b...)
来源：http://dali.dashuyun.cn/Article/details/gt2uttbchzp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gt2ctqieqpc.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gt2rdaswrik.html

[D09] 排序（升序）
来源：http://dali.gaohongyu789.top/Article/details/gt2wwhijtzx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2slhvnifz.html

PHP:  sort($arr);
来源：http://dali.zhixingplan.top/Article/details/gt2wldnlmwa.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhijiandao.cn/Article/details/gt2evodljlg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yueranfly.top/Article/details/gt2ralddkuf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.0kj1m.cn/Article/details/gt2jqsusxwt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2bwftlgwv.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gt2eqwwnbfj.html

C#:   list.Sort();
来源：http://dali.bjfxy.top/Article/details/gt2brscewlu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gt2dhdckfir.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gt2bcdnqrdo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gt2iagdhaao.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2dwwqajbb.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2zihgjave.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hnqzz.top/Article/details/gt2zbuaoubz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gt2fuzylqva.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cucudq.cn/Article/details/gt2rbeckgip.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sysykeji.top/Article/details/gt2emjbkxfy.html

[D11] 反转数组
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ktihcdma.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gt2czkmvygp.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gt2wjpdvdxu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sysykeji.top/Article/details/gt2ccxiqsqb.html

TS:   [...arr].reverse();
来源：http://dali.316326.xyz/Article/details/gt2uerlmjwr.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gt2ufyctpea.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2xgliruay.html

Ruby: arr.reverse
来源：http://dali.xziqi.cn/Article/details/gt2fflqyfxr.html

C#:   list.Reverse();
来源：http://dali.xziqi.cn/Article/details/gt2ldchlxcd.html

[D12] 查找元素下标
来源：http://dali.xziqi.cn/Article/details/gt2dvqfmmqr.html

Py:   arr.index(x);  x in arr
来源：http://dali.tian-w.cn/Article/details/gt2zoqkczpp.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.chenzaomai.com/Article/details/gt2hzsssdcw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ekbnjgtx.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2jkaioadn.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.pycfn.com/Article/details/gt2oqavkgvi.html

Go:   slices.Index(arr, x)
来源：http://dali.xinyue.icu/Article/details/gt2asjzqqdn.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gt2jdhywabr.html

C#:   list.IndexOf(x);
来源：http://dali.0kj1m.cn/Article/details/gt2kgdnqdyt.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmtwlyjm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.ivvv.top/Article/details/gt2baxunlyy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gzhubu.top/Article/details/gt2ndnzfslb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.andypj.xyz/Article/details/gt2swoegqoj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ucpnziqe.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mklgjhwa.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.nwbrower.top/Article/details/gt2ccjvmiou.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.aibaodan.cn/Article/details/gt2zawmxosm.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2eaphzumg.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gt2nuhsfxio.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.daxiang520.top/Article/details/gt2vlutkzda.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gt2hxyrgsks.html

JS:   arr.map(x => x * 2)
来源：http://dali.jiagoushi.top/Article/details/gt2ehmlfxjw.html

TS:   arr.map(x => x * 2)
来源：http://dali.cqqwz.cn/Article/details/gt2xrjkoebd.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2srjkbvbe.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gt2wouooyvc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.havefunace.top/Article/details/gt2onumlikw.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gt2sybqxwia.html

[D15] 去重
来源：http://dali.daxiang520.top/Article/details/gt2tvfizpwv.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guowangkeji.top/Article/details/gt2wqasliia.html

PHP:  array_unique($arr);
来源：http://dali.dashuyun.cn/Article/details/gt2teojbszk.html

JS:   [...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2rsvqnanq.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ygtjejhi.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2ufqoscmy.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.shzxlz.cn/Article/details/gt2xmmerlry.html

Ruby: arr.uniq
来源：http://dali.shanyushiyangtech.top/Article/details/gt2opbqxyjg.html

C#:   list.Distinct().ToList()
来源：http://dali.mhx1999.top/Article/details/gt2ydodsnxk.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gt2kdtpivek.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2nmvgzzke.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfdakeeb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jlsjyb.cn/Article/details/gt2fdxuqxvm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2btpsngty.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2hoimewaf.html

Go:   // 手写循环累加
来源：http://dali.nanxuanxn.top/Article/details/gt2vbtcljpx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jyoumei.cn/Article/details/gt2ybbuboqy.html

C#:   list.Sum();  list.Average()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nacsbgzv.html

[D17] 最大值与最小值
来源：http://dali.yuxming.cn/Article/details/gt2etxewylh.html

Py:   max(arr);  min(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2wmpcaqpp.html

PHP:  max($arr);  min($arr);
来源：http://dali.jianghu66.top/Article/details/gt2olqghusd.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangdashe.top/Article/details/gt2kxwwilej.html

TS:   Math.max(...arr);
来源：http://dali.hammf.cn/Article/details/gt2gknkouqw.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.fengsongda.top/Article/details/gt2kenvoirw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2eskkpmtk.html

Ruby: arr.max;  arr.min
来源：http://dali.feifeiyinyue.top/Article/details/gt2ckqhusum.html

C#:   list.Max();  list.Min()
来源：http://dali.yonumen.top/Article/details/gt2jbzgidqm.html

[D18] 扁平化嵌套数组
来源：http://dali.ybcxt.top/Article/details/gt2kdkdspzj.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sufxvd.cn/Article/details/gt2vxbjieyn.html

PHP:  array_merge(...$nested);
来源：http://dali.316326.xyz/Article/details/gt2fnsikflu.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.tanke756.top/Article/details/gt2abhcydte.html

TS:   nested.flat();
来源：http://dali.kuanghao11.cn/Article/details/gt2qqzmukip.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.xinyue.icu/Article/details/gt2zxttqbka.html

Go:   // 手写双层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2gegjrhjc.html

Ruby: nested.flatten
来源：http://dali.redwolf501.top/Article/details/gt2wxkihfdc.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yonumen.top/Article/details/gt2vpxcftdj.html


<!-- 参考信息 -->