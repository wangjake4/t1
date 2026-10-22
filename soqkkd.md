代发 wailian999

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gt2fqwzccga.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gt2sxpgojqi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2dpcufmpy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gt2lloctarb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gt2cqeffpnj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gt2zkjdodfh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmvcoanf.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2rptkgigq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gt2xzsddpgg.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gt2nnbmygfl.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2jabdewrr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gt2uxnulcvz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gt2hvssvbqq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2uwpdrsnk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mgihzljv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gaohongyu789.top/Article/details/gt2slfvchwx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gt2oxbweczf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2rgtdqfyi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gt2jjqaipoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzxxrtyn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gt2cuwvaxdy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gt2khbvvxej.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2byocedzt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gt2ttqfzksa.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gt2aaysscim.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2fnbcpfpj.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gt2ymbreihf.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2bpzcetou.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2mdvbipad.html

PHP:  return [$a, $b];
来源：http://dali.jinqigfzy.top/Article/details/gt2fhiosrqy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gt2dyegjogy.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2acsdydgt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gt2vumfwjcu.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2wwoqkpiy.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gt2fivqxcni.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gt2nbayyxsi.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gt2dbmnukkb.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gt2pkktoprd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xtizhnzg.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2qloqpnmq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2pwmsjkte.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2fbzhokvu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vrzldynu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuanzx.com/Article/details/gt2fluxnyna.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2togqgdhe.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2ifltcfut.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sufxvd.cn/Article/details/gt2tbnrgqrx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gt2baeksjnc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usuxzfhe.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gt2abqdzsxo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2hunjjraf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shangyingyoupin.top/Article/details/gt2uoctnvla.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gt2bqduimhf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxnszbld.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gt2llqnayef.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hysaishi.cn/Article/details/gt2ghizxvbf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cheryme.top/Article/details/gt2sisduhoo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2skzmysyx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2zmfcfxzy.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gt2flxsrafq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2xhsnmkxb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2amqkqawd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gt2dsnvgoye.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gt2vzadancr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gt2jawagjld.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2irbiofju.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gt2tpentvfv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gt2xttabpdy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gt2blgxkvxb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gt2jsfnonib.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvhagvje.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lvpfdcdz.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gt2dvtdqhsi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gt2spxglelg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fjemgosw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gt2qrywyfyr.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gt2rrtplohj.html

Java: 方法内为块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2timgcgrb.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2oduecbrq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gt2emwgbhum.html

C#:   块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2fxahbwpa.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gt2ghfymacu.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2qhfjavbd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2sivreqzc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gt2lmqmdyyy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gt2bibewvky.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gt2rltaccbw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yueranfly.top/Article/details/gt2kevehiqh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gt2uvxxexxz.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gt2egztbhjt.html

[C12] 立即执行函数 IIFE
来源：http://dali.yangfankeji.com/Article/details/gt2zfwnhkco.html

Py:   (lambda: print("run"))()
来源：http://dali.sysykeji.top/Article/details/gt2hlvpmxvh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangdashe.top/Article/details/gt2xpjgbhfs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2ahilitko.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gt2fyszylrm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gt2puyueiij.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2ihxkyxls.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gt2oussuhhr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpuxckzn.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gt2snbjpatd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2smrugzww.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2lbzrprnq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daxiang520.top/Article/details/gt2htwotfgd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2ccxpxegs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2qnzgsofp.html

Go:   func add(a, b int) int
来源：http://dali.nanxuanxn.top/Article/details/gt2axcdokwd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocjfmily.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xinyue.icu/Article/details/gt2yrfhyuoi.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gt2njthmuas.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gt2ujvejteu.html

PHP:  // 无泛型
来源：http://dali.iojbl.cn/Article/details/gt2lxsrtwar.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2nrcoubyo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gt2omlihufk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fengsongda.top/Article/details/gt2bcgkcchz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jlsjyb.cn/Article/details/gt2tvclmhnh.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2dlspvejj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gt2jlmxpxnh.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2pkzxfpgy.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2attbsfsa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gt2llclalpn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gt2engieflv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2yroeidrb.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gt2ntufcguh.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gt2fipcaafz.html

Ruby: a, b = pair
来源：http://dali.0kj1m.cn/Article/details/gt2hgbmulck.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gt2bkcjryfc.html

[C16] 函数 / 方法重载
来源：http://dali.birdmap.top/Article/details/gt2crozeuwn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yj20258.top/Article/details/gt2lcqycfup.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsfhukxd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gt2pfrbrgyy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gt2tpqbaypc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gt2bubmkrec.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gt2dhruflcb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gt2tpzptrpg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gt2qvkiroqc.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2mzafvsgc.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gt2aaxbyorm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2jyrxzaum.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gt2gykknlsn.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gotoacloud.top/Article/details/gt2jdassvgc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gt2tdcrjgej.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2enqbgkpb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gt2pwctrsjg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gt2veswznas.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gt2wmrtmbkk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hysaishi.cn/Article/details/gt2aryidjoz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2pozwkess.html

[D02] 追加元素到末尾
来源：http://dali.jianghu66.top/Article/details/gt2rtmgeiey.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2evacayod.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gt2ztkezdpb.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gt2kmrrxnvz.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gt2rouoirek.html

Java: list.add(4);
来源：http://dali.bjfxy.top/Article/details/gt2wtjhrsdk.html

Go:   arr = append(arr, 4)
来源：http://dali.hammf.cn/Article/details/gt2geslphwh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2elzocgzj.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gt2tjfoanxs.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gt2qzhrtcvp.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2danxkebu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gt2bghovudb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gotoacloud.top/Article/details/gt2srdyjkvx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2bsxwnchy.html

Java: list.add(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gt2ctjrpkag.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hqqhbnob.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.316326.xyz/Article/details/gt2kfgscbkb.html

C#:   list.Insert(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gt2bszvsgvs.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2ovglbbey.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ngjkhmkq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gt2uojcbjcw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hammf.cn/Article/details/gt2xviolhmn.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gt2bfmhoffa.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gt2xiughsym.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gt2zecvkrjr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cashguo.top/Article/details/gt2cgiwcbmr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hongshengwenyu.top/Article/details/gt2jvrjfrwl.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gt2qenflfjw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2ejmfyqcg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gt2xhoikasq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gt2ueywyegp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj202588.top/Article/details/gt2lxbhgdxm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.meibo888.top/Article/details/gt2zpyzgspe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2aituhghu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2qmnwytrl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2viubusnh.html

[D06] 数组长度
来源：http://dali.ppjwa.cn/Article/details/gt2gzwxkujy.html

Py:   len(arr)
来源：http://dali.birdmap.top/Article/details/gt2rqphpwej.html

PHP:  count($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2twqhucud.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2uhytreja.html

TS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gt2hlmhllsl.html

Java: list.size();
来源：http://dali.daxiang520.top/Article/details/gt2ilacgqjr.html

Go:   len(arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fdphwnkm.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gt2ornehwpu.html

C#:   list.Count;
来源：http://dali.xziqi.cn/Article/details/gt2gsymupkl.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gt2qngaeprv.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tanke756.top/Article/details/gt2uzmxyyml.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbiuobep.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hbfjebfb.html

TS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2ozuijxet.html

Java: list.subList(1, 4);
来源：http://dali.jiagoushi.top/Article/details/gt2mgqzrhem.html

Go:   arr[1:4]
来源：http://dali.ehwqpu.com/Article/details/gt2gjejljcu.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gt2wzjawcjo.html

C#:   list.GetRange(1, 3);
来源：http://dali.jqgufenzy.top/Article/details/gt2mazzyswx.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gt2urlxbykr.html

Py:   a + b;  a.extend(b)
来源：http://dali.daria6918.cn/Article/details/gt2fuzcsade.html

PHP:  array_merge($a, $b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iqyfwbwk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2uvrckxdd.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vluazmyh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2rlqarvxh.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gt2psfkddra.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2uxlddxyf.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gt2tkznzkgo.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gt2riowrqkq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gzhubu.top/Article/details/gt2fcjnksfa.html

PHP:  sort($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2vkhweibn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2dupatsif.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hywenlv.cn/Article/details/gt2xfwzkovv.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cashguo.top/Article/details/gt2qgrtugkw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.sysykeji.top/Article/details/gt2wwezxtyj.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gt2hgoielih.html

C#:   list.Sort();
来源：http://dali.cqqwz.cn/Article/details/gt2arfvimjc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.dashuyun.cn/Article/details/gt2pvpkqese.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gotoacloud.top/Article/details/gt2fvkbzaxv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2haukchtz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fzhhl.top/Article/details/gt2cuyfqjkh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tpecfudu.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhijiandao.cn/Article/details/gt2usouzfat.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinqigfzy.top/Article/details/gt2vkninugd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.pycfn.com/Article/details/gt2twtzttzh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yueranfly.top/Article/details/gt2hbzeapuh.html

[D11] 反转数组
来源：http://dali.cheryme.top/Article/details/gt2goryxngw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.feifeiyinyue.top/Article/details/gt2osgxsaxi.html

PHP:  array_reverse($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exqhiawj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gt2riurkpjs.html

TS:   [...arr].reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2bnalrrhn.html

Java: Collections.reverse(list);
来源：http://dali.aizwys.cn/Article/details/gt2rfrpdmcs.html

Go:   slices.Reverse(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lunjifiy.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gt2jizgxwwa.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gt2nkoxtkqq.html

[D12] 查找元素下标
来源：http://dali.yueranfly.top/Article/details/gt2szgwopwk.html

Py:   arr.index(x);  x in arr
来源：http://dali.yueranfly.top/Article/details/gt2urwvgxmk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2gjbobcwj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2yhciicqo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gt2pffkxfis.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.gzhubu.top/Article/details/gt2faxnmtfe.html

Go:   slices.Index(arr, x)
来源：http://dali.dianchejie.cn/Article/details/gt2jvjdqcbn.html

Ruby: arr.index(x)
来源：http://dali.ydzc1.top/Article/details/gt2lexkutkc.html

C#:   list.IndexOf(x);
来源：http://dali.zhongyouzk.top/Article/details/gt2srninozm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2womdeqey.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.xuanzx.com/Article/details/gt2lhgilhyk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sweek.top/Article/details/gt2ldkscseq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2hiqvitap.html

TS:   arr.filter(x => x > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2gmywwxnu.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.daria6918.cn/Article/details/gt2gsobypqh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hnxiangtu.top/Article/details/gt2tqnzmsaa.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gt2hddodcax.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2svgxohit.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yueranfly.top/Article/details/gt2xderdbso.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gzhubu.top/Article/details/gt2yhajmscf.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2nbbmzhqx.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gt2pthfdyul.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2voaogxxx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2lpacaukx.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2jdxcnyyi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2cyvwuior.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.shzxlz.cn/Article/details/gt2dhdhdkij.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhgczmvf.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gt2cficipku.html

PHP:  array_unique($arr);
来源：http://dali.daxiang520.top/Article/details/gt2ehclkxvl.html

JS:   [...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gt2tcgffzht.html

TS:   [...new Set(arr)]
来源：http://dali.wangshuangyany.cn/Article/details/gt2tuoagwua.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnvfoafi.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gt2lzffgaia.html

Ruby: arr.uniq
来源：http://dali.xylfe.cn/Article/details/gt2avfyakvk.html

C#:   list.Distinct().ToList()
来源：http://dali.ehwqpu.com/Article/details/gt2ghicuylk.html

[D16] 求和与平均值
来源：http://dali.smart0.xyz/Article/details/gt2pwbigglb.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gt2vdddluzt.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2brivobrq.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.nwbrower.top/Article/details/gt2zksktiao.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2prswjchs.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xrnmdfoj.html

Go:   // 手写循环累加
来源：http://dali.tianlin.xyz/Article/details/gt2lnntdwjw.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.gaohongyu789.top/Article/details/gt2djzobzwo.html

C#:   list.Sum();  list.Average()
来源：http://dali.ivvv.top/Article/details/gt2ijullmpy.html

[D17] 最大值与最小值
来源：http://dali.hnqzz.top/Article/details/gt2xrtzbbgo.html

Py:   max(arr);  min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2fijyhjdd.html

PHP:  max($arr);  min($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gt2slbtbmbm.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sweek.top/Article/details/gt2ympkkwep.html

TS:   Math.max(...arr);
来源：http://dali.cdnleiting.top/Article/details/gt2fbkuvpkv.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.yj20258888.top/Article/details/gt2ufbqcdqf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.jinqigfzy.top/Article/details/gt2jokpcqqo.html

Ruby: arr.max;  arr.min
来源：http://dali.zhongyouzk.top/Article/details/gt2blstppwb.html

C#:   list.Max();  list.Min()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nujiqtle.html

[D18] 扁平化嵌套数组
来源：http://dali.yangfankeji.com/Article/details/gt2hnxzjvwa.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.9152youxi.cn/Article/details/gt2zoyiemew.html

PHP:  array_merge(...$nested);
来源：http://dali.iojbl.cn/Article/details/gt2gmircagi.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2shntkpud.html

TS:   nested.flat();
来源：http://dali.gotoacloud.top/Article/details/gt2yrxmhgqy.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.gotoacloud.top/Article/details/gt2qvcswpft.html

Go:   // 手写双层循环
来源：http://dali.xuanzx.com/Article/details/gt2wcxameap.html

Ruby: nested.flatten
来源：http://dali.dianchejie.cn/Article/details/gt2vvblhlnp.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2onxyqzoi.html


<!-- 参考信息 -->