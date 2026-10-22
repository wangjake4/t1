代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cydairrq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shuidangran.top/Article/details/gt2tlhwxjhw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gt2gmuhdssq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2adtirzux.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gt2cpfejlfq.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gt2jwkbxneb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrknbxh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gt2uyoglcdu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2wtoisvkx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gt2vvjfufyn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aizwys.cn/Article/details/gt2bqwsjcda.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gt2opdgkevr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnxghdvg.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gt2otjklpxc.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gt2kfgmwukn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gt2mhgfklfo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gt2tuedafan.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zmiwpvpw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gt2cfrqkekr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cdnleiting.top/Article/details/gt2ogmyzdwy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gt2wepldfqe.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jianghu66.top/Article/details/gt2omdwgiqr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxinkj.top/Article/details/gt2vrmyrgdf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gt2hsgtthkd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2qnbjqqfs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2qmohklqn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2vawqexjz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2krcxjzyn.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akkofeez.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2nhpsxiym.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gt2ofufjjgn.html

[C05] 返回多个值
来源：http://dali.daria6918.cn/Article/details/gt2webwsouu.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gt2brpqyvuc.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2wxpuubbf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gt2jnajtcqk.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2vozajokm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gt2cuhbixtf.html

Go:   return a, b
来源：http://dali.meibo888.top/Article/details/gt2cizrjtjk.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2zxirzfdz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gt2gfdyaevu.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2yetvxavv.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2klvesgis.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gt2iwsxhhsi.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2emyoplvp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2tagxmetw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gt2cavyyllt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gt2bfetdjjm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zkyfdvhd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2zyfoeaoe.html

[C07] 把函数作为参数传入
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gvbdheof.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yuanzhike.top/Article/details/gt2sszbrzdi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gt2xufiqmwm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2ojhnbsps.html

TS:   arr.map(String)
来源：http://dali.havefunace.top/Article/details/gt2pgeylzsc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gt2dwdadrkl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gt2hfgvlpco.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhengqikj.top/Article/details/gt2mqbvjger.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gt2yeqdmjll.html

[C08] 闭包
来源：http://dali.sweek.top/Article/details/gt2pbulxidl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gt2ywmtaiot.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2coljbyhv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2xmkbosto.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxfdcvhl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2hokayrdw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gt2sdosbtgb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gt2gheilvzd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gt2djlzitxu.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gt2mtponmay.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bikufgei.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gt2ukmymoli.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awyacuxa.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2lnpdqkih.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aizwys.cn/Article/details/gt2ddrajedh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gt2xeaiqfxz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iirwopoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jqgufenzy.top/Article/details/gt2jgnhhebp.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gt2jnmjixnh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gt2desgxkfv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tianlin.xyz/Article/details/gt2mdjuzjgg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2sdybqwhc.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gt2aefbpvfl.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gt2vbacxtfy.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2doxvcznn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhengqikj.top/Article/details/gt2rhkfqesi.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xxhfzjss.html

[C11] 模块导入与导出
来源：http://dali.jinqigfzy.top/Article/details/gt2jnoqpiil.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhqakili.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gt2curxrgsr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2vtabyupv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gt2qnapdnzh.html

Java: import java.util.List;
来源：http://dali.shangyingyoupin.top/Article/details/gt2spajcpaa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2kgaldyff.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gt2jcexthez.html

C#:   using System.Text;
来源：http://dali.nanxuanxn.top/Article/details/gt2hxrxjafx.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2ypxesxly.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yjpovdmn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sufxvd.cn/Article/details/gt2rpodrxnh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gt2lyheptfn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xylfe.cn/Article/details/gt2jkqcpywb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shangyingyoupin.top/Article/details/gt2njeackwh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenzaomai.com/Article/details/gt2iaovyyor.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gt2kekglona.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258888.top/Article/details/gt2ktkksnus.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gt2hedogvfn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nmnaxrox.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gyqgpogt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gt2lpjawkdu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gt2mtnuufge.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2dqborqhe.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gt2nsrvdogu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2vyiblfrl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xziqi.cn/Article/details/gt2uhhfyqmm.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gt2whowjsxy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cdnleiting.top/Article/details/gt2gsdqmgki.html

PHP:  // 无泛型
来源：http://dali.cdnleiting.top/Article/details/gt2jtqrtuhb.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2pjinzsjk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gt2dqknamqa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yonumen.top/Article/details/gt2keixgeda.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigfzy.top/Article/details/gt2nhhludbv.html

Ruby: # 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yjtrcyog.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gt2schvynpy.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2rwfdkrmk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daria6918.cn/Article/details/gt2ytccrndq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gt2alarwmun.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2yhsjbpvn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2apshrhqz.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2quouipaa.html

Go:   // 无解构
来源：http://dali.zycfv.cn/Article/details/gt2muwbpngr.html

Ruby: a, b = pair
来源：http://dali.yj20258.top/Article/details/gt2hykrxenq.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gt2mnflyljp.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gt2pkidbuat.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gt2hgvlajve.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gt2qyubulaf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ifrvzxwg.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gt2txjpccku.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tianlin.xyz/Article/details/gt2uqaemwrx.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhijiandao.cn/Article/details/gt2rbaiulyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xinyue.icu/Article/details/gt2rjoyljdt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhongyouzk.top/Article/details/gt2tiriqqyw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2cjdmdnda.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gt2xttxoxfz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwoyirlo.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gt2eddtoajp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shzxlz.cn/Article/details/gt2nfcepwgp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gt2pmwfbpkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctmyhktr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zycfv.cn/Article/details/gt2uczwqvvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gt2ejnsegny.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gt2ftbfbgmf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yj20258.top/Article/details/gt2yuoellqi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gt2avbznpkm.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2znzeehcd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jlsjyb.cn/Article/details/gt2uysbxhqp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gt2hzpwblxb.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2syfauykw.html

TS:   arr.push(4);
来源：http://dali.ybcxt.top/Article/details/gt2leekikjl.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gt2fynryiqy.html

Go:   arr = append(arr, 4)
来源：http://dali.yvedp.cn/Article/details/gt2nvpgzgkt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gt2elhrdanf.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2kzktqilr.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258.top/Article/details/gt2bxznijnl.html

Py:   arr.insert(0, 0)
来源：http://dali.iojbl.cn/Article/details/gt2cdqobbre.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gt2xwdhozkn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2nwuoejqh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lipixyvu.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2voxbibmt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.havefunace.top/Article/details/gt2jdaewwqp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.nwbrower.top/Article/details/gt2nchorfen.html

C#:   list.Insert(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gt2kuscccyj.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2corjhhgn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cdnleiting.top/Article/details/gt2ipxfywwl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gt2qfrbndrk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gt2vhghqong.html

TS:   arr.splice(0, 1);
来源：http://dali.yonumen.top/Article/details/gt2ydgqnsnf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gt2zjlsfzjw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acyhreqw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gt2ogqateio.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgkkqhvy.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gt2hwvqwsbs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2ohmlnmdq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gt2xjsnlkxo.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gt2ddkwqgdn.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.daxiang520.top/Article/details/gt2vqbwtzql.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcmgzcci.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.nanxinkj.top/Article/details/gt2xovwlvdh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gt2hoalqjwm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2rvwxgxsf.html

[D06] 数组长度
来源：http://dali.yvedp.cn/Article/details/gt2rnaalkjr.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2vxycyspu.html

PHP:  count($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2qdgovgiq.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2dddyoaam.html

TS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gt2nowrfwqt.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gt2rnjlpxag.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2uyofvghh.html

Ruby: arr.length; arr.size
来源：http://dali.yueranfly.top/Article/details/gt2cvfbdjfx.html

C#:   list.Count;
来源：http://dali.9152youxi.cn/Article/details/gt2ntlpkzxr.html

[D07] 切片 / 取子数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbspbbnj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jyoumei.cn/Article/details/gt2rqwxoxrm.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2peiqager.html

JS:   arr.slice(1, 4);
来源：http://dali.fzhhl.top/Article/details/gt2qhkerqjq.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2istgrfyi.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gt2lbscyvbq.html

Go:   arr[1:4]
来源：http://dali.zhixingplan.top/Article/details/gt2azsmcdnj.html

Ruby: arr[1, 3]
来源：http://dali.sweek.top/Article/details/gt2uxvskmbx.html

C#:   list.GetRange(1, 3);
来源：http://dali.dashuyun.cn/Article/details/gt2ukhqkujs.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gt2mgywlpot.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gt2xibmoviq.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gt2cobmqdpz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.c1oappe.top/Article/details/gt2vhdllvrx.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gt2yqfdbgfi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jiagoushi.top/Article/details/gt2eprzfemq.html

Go:   append(a, b...)
来源：http://dali.ivvv.top/Article/details/gt2ugvoezbk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jianghu66.top/Article/details/gt2ganoecdg.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2cfscdjby.html

[D09] 排序（升序）
来源：http://dali.daria6918.cn/Article/details/gt2yynoqhdn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhixingplan.top/Article/details/gt2wwynfdhy.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gt2kreqzlyi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xinyue.icu/Article/details/gt2jjgvyzpn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.c1oappe.top/Article/details/gt2juryblfc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmquexjw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.andypj.xyz/Article/details/gt2drfxigvf.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iiuyxftr.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gt2xmrdgnhn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jyoumei.cn/Article/details/gt2ijbwwjps.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gt2poxlscch.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2yxqfcnvf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gt2kvpqxlex.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2lueyztle.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2gottpjbk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jlsjyb.cn/Article/details/gt2dxlhbtfv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ppjwa.cn/Article/details/gt2bkaemttp.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zzljknso.html

[D11] 反转数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2yvqrdciz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gt2gcyktzse.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsheacix.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqzwfjxl.html

TS:   [...arr].reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2dxiykiyv.html

Java: Collections.reverse(list);
来源：http://dali.zhoulong.xyz/Article/details/gt2mvegugcm.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gt2pgdphocz.html

Ruby: arr.reverse
来源：http://dali.zhoulong.xyz/Article/details/gt2ldvevpdm.html

C#:   list.Reverse();
来源：http://dali.jiagoushi.top/Article/details/gt2dpgidutg.html

[D12] 查找元素下标
来源：http://dali.dashuyun.cn/Article/details/gt2alrcopap.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gt2urjffjlh.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2afhzziek.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gt2dzrupepb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tanke756.top/Article/details/gt2gzgmvbwi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigufen.top/Article/details/gt2gqnykdma.html

Go:   slices.Index(arr, x)
来源：http://dali.zhongyouzk.top/Article/details/gt2ecrhusog.html

Ruby: arr.index(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2kwvhskev.html

C#:   list.IndexOf(x);
来源：http://dali.zhoulong.xyz/Article/details/gt2jsxqdxsa.html

[D13] 过滤（保留满足条件的）
来源：http://dali.0kj1m.cn/Article/details/gt2doegjwfv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cqqwz.cn/Article/details/gt2xikokxae.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.quarkkingdee.top/Article/details/gt2ztqfpgoh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2utibvdfe.html

TS:   arr.filter(x => x > 3)
来源：http://dali.fzhhl.top/Article/details/gt2heisemqt.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2apyxkcaq.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xinyue.icu/Article/details/gt2bmhqxcql.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2utzzvhyo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mssbhuus.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nwbrower.top/Article/details/gt2zjjpjpsz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gogol.net.cn/Article/details/gt2zibelndd.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cheryme.top/Article/details/gt2himcbiyw.html

JS:   arr.map(x => x * 2)
来源：http://dali.fzhhl.top/Article/details/gt2figzclif.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2sxbiwgwf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjujztdt.html

Go:   // 手写循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2szypeevw.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrlrmyri.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gt2kjzlnkga.html

[D15] 去重
来源：http://dali.aizwys.cn/Article/details/gt2ucketllx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2taiahxmt.html

PHP:  array_unique($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2hmniyfqn.html

JS:   [...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gt2xgfgaqfh.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2jwhuhrwf.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gt2hhmrdafz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hysaishi.cn/Article/details/gt2pemiowxd.html

Ruby: arr.uniq
来源：http://dali.yueranfly.top/Article/details/gt2qibggnya.html

C#:   list.Distinct().ToList()
来源：http://dali.chenzaomai.com/Article/details/gt2zvccwdgh.html

[D16] 求和与平均值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tudqijqh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.ppjwa.cn/Article/details/gt2svnuqcjj.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.9152youxi.cn/Article/details/gt2ypyfmtir.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gt2avllzjud.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jianghu66.top/Article/details/gt2mqaimubg.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gydciykw.html

Go:   // 手写循环累加
来源：http://dali.wangshuangyany.cn/Article/details/gt2bfzatphu.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.xziqi.cn/Article/details/gt2ijwweqhk.html

C#:   list.Sum();  list.Average()
来源：http://dali.yj20258888.top/Article/details/gt2ivjcmbjw.html

[D17] 最大值与最小值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2firpuyxq.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2ppkahgfl.html

PHP:  max($arr);  min($arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2ofsllhzm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.xziqi.cn/Article/details/gt2nvkzxwuk.html

TS:   Math.max(...arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2bjrvorci.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.jqgfzy.top/Article/details/gt2ogcaiobe.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.9152youxi.cn/Article/details/gt2rujsbzbi.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gt2weqigqbk.html

C#:   list.Max();  list.Min()
来源：http://dali.yvedp.cn/Article/details/gt2vlxvirbq.html

[D18] 扁平化嵌套数组
来源：http://dali.hnxiangtu.top/Article/details/gt2ztncjagt.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.zhoulong.xyz/Article/details/gt2hyeikgqg.html

PHP:  array_merge(...$nested);
来源：http://dali.cheryme.top/Article/details/gt2zjrkrxrj.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sxryk.cn/Article/details/gt2shkcguwf.html

TS:   nested.flat();
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmzicymq.html


<!-- 参考信息 -->