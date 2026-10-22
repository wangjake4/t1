代发 wailian999

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gt2mriyqmtn.html

PHP:  if (!$data) { return; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtymjpsc.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqjcvtdf.html

TS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gt2dkmvuyke.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gt2aivipqax.html

Go:   if data == nil { return }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqihnxrh.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gt2rxtmvhii.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gt2bydluqmk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2vwhrtgdg.html

C. 函数与作用域
来源：http://dali.xuanzx.com/Article/details/gt2rbltxvuw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2dvmprolj.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2srnqflga.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gt2irdbfbcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2ztckdwic.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gt2mfzwuogk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2wmvlpoqw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2dxgrejrn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gt2duuppqbd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xziqi.cn/Article/details/gt2suegyode.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2kdqjulyo.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2ycrejnzi.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gt2uoubqvku.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gt2qxmgtich.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gt2edptpupd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aizwys.cn/Article/details/gt2ikzgclpq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gt2biwgwhpb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gt2gwdznnvn.html

Ruby: def greet(name = "World") = name
来源：http://dali.316326.xyz/Article/details/gt2iogebbba.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gt2dkilhwfg.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gt2joxssvmo.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gt2buvplyfg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gt2mftujhqw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gt2tnfpgizf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2ryfarjta.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gt2dtzgjrao.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gt2yshfqojo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gt2hmdsgmme.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gt2wiumnfkn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gt2kwiesovx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gt2tnfbfkie.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bwyctoij.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2vfudqzzp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gt2dkxyigvw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gt2hylbccpf.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gt2wchmyhej.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2bpvvsahk.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2fbpohitk.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gt2ypbdhdxo.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2exvxhusx.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2erphiqvd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2nvwejhxo.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2lhzaglbo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gt2jfvcatfc.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2hrfjnzpn.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gt2dqekliez.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dianchejie.cn/Article/details/gt2ylmgiiio.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2wmswrfta.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gt2mxdsokbb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2uucqebsy.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gt2wgaciwwm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2taqcdnti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gt2vthxwrfm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zycfv.cn/Article/details/gt2lvtizuyu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gt2atrowifz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gt2vemhhrtg.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gt2oqaloctm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gt2zsgivrud.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gt2jfysqaup.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gt2hawnwdld.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gt2tunfnbpd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2kpzvgtbx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.c1oappe.top/Article/details/gt2qlzczoyk.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gt2jfqtgiao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gt2bfirwzxn.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gt2gftroplt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnxiangtu.top/Article/details/gt2keoeopvb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aibaodan.cn/Article/details/gt2kgqmfknc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2fildvvjx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2qiskaytx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gt2knvssuhc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2gauvyyol.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gt2uubpbjzj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcndhvw.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2kfovsoao.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gt2tqpesomy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2namznoxm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guowangkeji.top/Article/details/gt2yktgagzt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gt2okgiolyp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2jpetsbbm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbzadqyt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gt2jhfavthx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhengqikj.top/Article/details/gt2akslqjep.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2xomafabf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xinyue.icu/Article/details/gt2pbumofdy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gt2vxckzpvg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gt2yhcxqoci.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gt2fbdcgnfh.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2ydgypfvq.html

Go:   花括号块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2fuvzynpb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gt2vypruqkn.html

C#:   块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2yubznvrh.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2xfcjsnex.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2mjnxdkag.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gt2kehqfrng.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gt2icctiffc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gt2pnonitwh.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2vcilxkjr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gt2apgahcyx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2facrkcyd.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gt2bmbhvduy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhiwuduotai.top/Article/details/gt2xusafqbg.html

Py:   (lambda: print("run"))()
来源：http://dali.zhiwuduotai.top/Article/details/gt2bukfqzwu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gt2vrxmmtqn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gt2yvcnubfw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gt2qmuczbxy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gt2dlhowakt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2qhgylftj.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gt2yfiyvcus.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gt2ldkajedt.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgfkpleu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2abibnpef.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gt2dhepbnpf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsoknxdp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mytjvbqq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2uvswowsa.html

Go:   func add(a, b int) int
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gnlblmne.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnxhwknq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gt2zzlqjert.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2laxmnawg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hfpthk.cn/Article/details/gt2nglgpsho.html

PHP:  // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2ympbxmyr.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2efvjmaxd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaijxchy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2umjcexlw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gt2idiiptgl.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2wruejchq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gt2mcgxpwly.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2okdkagqi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2sprtvnlq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2hgxvksxa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hhrywnxo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2pkvkully.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gt2iiqndnpm.html

Go:   // 无解构
来源：http://dali.yueranfly.top/Article/details/gt2pkiwssmu.html

Ruby: a, b = pair
来源：http://dali.aizwys.cn/Article/details/gt2iabkzsdk.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gt2talinkha.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gt2xmaqgxjf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gt2sajcgznk.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2fnvdbzod.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gt2qilzkwzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jyoumei.cn/Article/details/gt2plparuks.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhengqikj.top/Article/details/gt2gqqqhxjr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gt2zxjgtmoz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gt2mypiyeyi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nveqpkka.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qxakvcbg.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2nhqkljeo.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qnhdvlir.html

[D01] 创建数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gt2trintvpw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ydzc1.top/Article/details/gt2asvkhdva.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2vlapgvrd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2eozlfbcs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gt2geglmfor.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gt2mvqzemdm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gt2mnlagusz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gt2zuxgoadd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctslpexd.html

[D02] 追加元素到末尾
来源：http://dali.316326.xyz/Article/details/gt2ldacmehe.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2ylsxilup.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gt2pikyxnwe.html

JS:   arr.push(4);
来源：http://dali.kuanghao11.cn/Article/details/gt2bmlwliqr.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gt2lexehmkd.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gt2cyymdnbl.html

Go:   arr = append(arr, 4)
来源：http://dali.jianghu66.top/Article/details/gt2rdsbxoas.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2mzpryrrl.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gt2nhkzvjug.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2slueabwc.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gt2qbsapowc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gt2amstifkb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhongyouzk.top/Article/details/gt2hysrpytf.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigufen.top/Article/details/gt2nvqirhqe.html

Java: list.add(0, 0);
来源：http://dali.havefunace.top/Article/details/gt2htewninu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenzaomai.com/Article/details/gt2npzemttb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gt2gnpuxwmc.html

C#:   list.Insert(0, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2wtrtkfpl.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gt2lwmftalt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbgldruc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idojnxus.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.fzhhl.top/Article/details/gt2boeafhfm.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gt2iqngcnlu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.mhx1999.top/Article/details/gt2nenbxrzt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gt2hsitpdqh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gt2vcmgoxyo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gt2etfhilvu.html

[D05] 访问与修改元素
来源：http://dali.316326.xyz/Article/details/gt2vtuotfef.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gt2capygibz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gt2udzumosu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhoulong.xyz/Article/details/gt2whntnlch.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gt2uvckwpqd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jianghu66.top/Article/details/gt2mryfbdrt.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2aijztdna.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2cyakbjjx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gt2fvmcejox.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gt2vqjfgenz.html

Py:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ieopqhhg.html

PHP:  count($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2ouhfpnyo.html

JS:   arr.length
来源：http://dali.aibaodan.cn/Article/details/gt2wgwrvdzh.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gt2ueorcwcn.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gt2phiudyei.html

Go:   len(arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nmovcmup.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2pkwrgvgk.html

C#:   list.Count;
来源：http://dali.dianchejie.cn/Article/details/gt2alpewjpa.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gt2dtvrlljh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.pengpengdd.cyou/Article/details/gt2urkslujr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2wyvituad.html

JS:   arr.slice(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gt2zrokavii.html

TS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2novqnjvz.html

Java: list.subList(1, 4);
来源：http://dali.sweek.top/Article/details/gt2fidlsnqf.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gt2cyyrgzmk.html

Ruby: arr[1, 3]
来源：http://dali.jqgufenzy.top/Article/details/gt2tmkldjrs.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2uwrgkugh.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gt2nqbicivu.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gt2dvplzlqq.html

PHP:  array_merge($a, $b);
来源：http://dali.cheryme.top/Article/details/gt2opqmlcjb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zycfv.cn/Article/details/gt2iesywwqs.html

TS:   [...a, ...b];
来源：http://dali.chenlongwang.top/Article/details/gt2wzrlajhs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gt2kqbawvoy.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gt2ilmyjpkh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gt2prshttom.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2nnnilrmd.html

[D09] 排序（升序）
来源：http://dali.daxiang520.top/Article/details/gt2fxbilkfz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuanzhike.top/Article/details/gt2djpjkqza.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2xjzehvpb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.wangdashe.top/Article/details/gt2rdekrwrb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gt2xiqgxeah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guowangkeji.top/Article/details/gt2koxuevmc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.c1oappe.top/Article/details/gt2zmpagsmz.html

Ruby: arr.sort
来源：http://dali.yonumen.top/Article/details/gt2anwplcfw.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vancttwj.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.sufxvd.cn/Article/details/gt2pzdyiuan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.pycfn.com/Article/details/gt2nmmliklu.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2jqzzdfgf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gt2skrfegcf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2jvjdxaog.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gt2dywsofvh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.iojbl.cn/Article/details/gt2subsweui.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gt2idbxhcbr.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuanzhike.top/Article/details/gt2aplqrwkk.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gt2gonrlpxr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gt2udhhgzho.html

PHP:  array_reverse($arr);
来源：http://dali.hammf.cn/Article/details/gt2spnjqgcy.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.dianchejie.cn/Article/details/gt2ihymqyja.html

TS:   [...arr].reverse();
来源：http://dali.quarkkingdee.top/Article/details/gt2tqzqjqkj.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gt2nnvajirn.html

Go:   slices.Reverse(arr)
来源：http://dali.yonumen.top/Article/details/gt2eweonqhi.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gt2qzjgwbdq.html

C#:   list.Reverse();
来源：http://dali.shzxlz.cn/Article/details/gt2xryxfuut.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gt2ogmconiy.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2dngojkhy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yangfankeji.com/Article/details/gt2wgedeeob.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.aizwys.cn/Article/details/gt2pjavjiwa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.andypj.xyz/Article/details/gt2qoaescbx.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.havefunace.top/Article/details/gt2cxakiysq.html

Go:   slices.Index(arr, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2abrwjtwo.html

Ruby: arr.index(x)
来源：http://dali.yuanzhike.top/Article/details/gt2driygeoh.html

C#:   list.IndexOf(x);
来源：http://dali.jiagoushi.top/Article/details/gt2hyumeive.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gaohongyu789.top/Article/details/gt2kwrgxbxd.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.daxiang520.top/Article/details/gt2rxzlwupt.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2egesemvx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2svlclzxr.html

TS:   arr.filter(x => x > 3)
来源：http://dali.smart0.xyz/Article/details/gt2zburxkqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pycfn.com/Article/details/gt2ixgumaqn.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gt2onhrigas.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.daria6918.cn/Article/details/gt2entxdkbw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zdqjudy.top/Article/details/gt2enxvjqoq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.sufxvd.cn/Article/details/gt2jhneaxga.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gt2yhoxqkae.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2mhyjtmdf.html

JS:   arr.map(x => x * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2bigsxeak.html

TS:   arr.map(x => x * 2)
来源：http://dali.hnxiangtu.top/Article/details/gt2ovjkkkdl.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cheryme.top/Article/details/gt2guywljsv.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gt2bfkuyhxn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.haohaochexian.top/Article/details/gt2jlfmxpst.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sqzomvah.html

[D15] 去重
来源：http://dali.xylfe.cn/Article/details/gt2dtbsjesx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gt2xijlixjq.html

PHP:  array_unique($arr);
来源：http://dali.c1oappe.top/Article/details/gt2ykdrpjpc.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gt2zmrbazjv.html

TS:   [...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gt2pcojqsey.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xylfe.cn/Article/details/gt2ejmoluhj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gaohongyu789.top/Article/details/gt2hvkuebbj.html

Ruby: arr.uniq
来源：http://dali.yj20258888.top/Article/details/gt2uluwqfkt.html

C#:   list.Distinct().ToList()
来源：http://dali.dashuyun.cn/Article/details/gt2tnrozlqu.html

[D16] 求和与平均值
来源：http://dali.zycfv.cn/Article/details/gt2aomkssfj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2gmbcegro.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.yj20258.top/Article/details/gt2chfgzldf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cheryme.top/Article/details/gt2lzedusii.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mimtwoon.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2seuyazuh.html

Go:   // 手写循环累加
来源：http://dali.iojbl.cn/Article/details/gt2stpwmlmf.html


<!-- 参考信息 -->