代发 wailian999

Py:   if not data: return
来源：http://dali.zhengqikj.top/Article/details/gt2teoivkxf.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dfjkjimo.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2lqneqlzm.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gt2hmszfamq.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gt2tjhlltdd.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vwjtelzw.html

Ruby: return if data.nil?
来源：http://dali.ybcxt.top/Article/details/gt2vsvpxkul.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gt2fixxnedj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gyjjeyfh.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2mkbffcrj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2oehdrsal.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gt2tcijqtpv.html

Py:   def add(a, b): return a + b
来源：http://dali.meibo888.top/Article/details/gt2jeosqkln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gt2qvnlatws.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2pmeoycnb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2iiyhtfrh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2zqheqtvl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gt2zvhoweyo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2dkvcodcn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2jjrwwgfl.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gt2gvlorhmi.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gt2darqdjoi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2ngvqetmk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2uepoomil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gt2oojpwazh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gt2ikutzdgi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gzcoqbjo.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gt2dbwfvyoc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gt2jmvbsiwk.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gt2bxvfawew.html

Py:   def total(*args): return sum(args)
来源：http://dali.ybcxt.top/Article/details/gt2lbcsilli.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gt2jmnsigal.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gt2cmcehpft.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gt2xsolqkaq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gt2odwpnbqo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.redwolf501.top/Article/details/gt2iwqdahib.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gt2ynyquunf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ybcxt.top/Article/details/gt2uhdwahfx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tanke756.top/Article/details/gt2pkuzvmzh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gt2xdfaxssl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gt2mbevmant.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2aeuoiyhj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigfzy.top/Article/details/gt2ngfjqxsi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gt2xznaygus.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gt2emqrpqkg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yykwmdkq.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gt2klaktyic.html

[C05] 返回多个值
来源：http://dali.xuetiantiany.cn/Article/details/gt2metdotnq.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2jjgcuwmi.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftvmixot.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfvyxuet.html

TS:   return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gt2draqznva.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gt2hdouqkro.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gt2rgbpkrdo.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gt2yivyenqh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gt2jlfehvih.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gt2bbctvwet.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gt2ujfjsdwm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.haohaochexian.top/Article/details/gt2rdxtucgo.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2fcfrxdyi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gt2zgfusinh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2ktzbuzfa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2ilqrccts.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gt2wudsdevr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2tpzecygy.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2diwgieyq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2lskqrvyh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2cgodtyph.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gt2mixegzbj.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gt2xpzzffvk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2rcskrber.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhengqikj.top/Article/details/gt2eiwxrzuz.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gt2tqswmbxo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gt2mcncbyct.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gt2sstsfdup.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gt2iazmgrrw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ztznzwoa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tymxgueb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2pppldnvm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2nrhslycy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.havefunace.top/Article/details/gt2uxdcprzl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ppjwa.cn/Article/details/gt2hknqdxht.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2qjibsjwh.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gt2vugmnmrq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2dmzdgitg.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gt2qrohjpxd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gt2wklmpvjv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cheryme.top/Article/details/gt2olavptuv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2eekrpuca.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gt2binlwosn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gt2uqezcstm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gt2rccanluj.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2xpcbtbxk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gaohongyu789.top/Article/details/gt2xvhynoov.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gt2nawwrkxq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2jhrcefqa.html

TS:   同 JS
来源：http://dali.yuanzhike.top/Article/details/gt2eyugwmcj.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2zbmtotfp.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2feqoqnka.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhoulong.xyz/Article/details/gt2ubalxuna.html

C#:   块级作用域
来源：http://dali.tanke756.top/Article/details/gt2qjggwqss.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gt2sgcwcgjp.html

Py:   from module import func
来源：http://dali.gotoacloud.top/Article/details/gt2tmrbezcq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2yopmtqfy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hysaishi.cn/Article/details/gt2eeevxwny.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gt2mprgnjdv.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gt2pcgxythj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lueaxbnj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2absygjim.html

C#:   using System.Text;
来源：http://dali.hnqzz.top/Article/details/gt2iwwroopa.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2nqskwjqk.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gt2mimfbeuz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pycfn.com/Article/details/gt2tforqfzt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gt2gsugtyfu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2xbycenya.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gt2bjfxmfsu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hywenlv.cn/Article/details/gt2shksrdxv.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gt2ojrncjec.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gt2qvwfzpyc.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2nfxmkktg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gt2azhhaczp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gt2upobsdrv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gt2qhcgawdj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2rmclofqz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2jbmskuma.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gt2nlpidjpi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gt2tadzqenk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rqzfyibk.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2lhvfiheu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2kfszumip.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2gkwqbrsi.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2hqvhzffj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yangfankeji.com/Article/details/gt2ytdpdjia.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gt2fhiizeiq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2zhwxcmwq.html

Ruby: # 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2tkggwlkh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gt2epthiujy.html

[C15] 解构 / 展开参数
来源：http://dali.yuxming.cn/Article/details/gt2genawrkh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxuanxn.top/Article/details/gt2swyfebay.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gt2jtqrtxus.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2durfzdzd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ehuyxvuk.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2hpgrfytf.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gt2bpqhphkj.html

Ruby: a, b = pair
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmrpfxlo.html

C#:   var (a, b) = pair;
来源：http://dali.yuanzhike.top/Article/details/gt2pyjiwdmo.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gt2obkyzlqp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.bjfxy.top/Article/details/gt2wgcqwcwg.html

PHP:  // 无重载
来源：http://dali.c1oappe.top/Article/details/gt2ciftxyoq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gt2anmhuwjc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tanke756.top/Article/details/gt2ckavcxbg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfukaijp.html

Go:   // 无重载：用不同函数名
来源：http://dali.sysykeji.top/Article/details/gt2dhmkuiut.html

Ruby: # 无重载：靠动态参数
来源：http://dali.bjfxy.top/Article/details/gt2vnkajnkb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2hpmlalmq.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2prcstnhg.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gt2jdpyonhh.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2hyqhxflm.html

[D01] 创建数组 / 列表
来源：http://dali.gaohongyu789.top/Article/details/gt2tlibvzsm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gt2vsivrmgn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2zebpyptc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgufenzy.top/Article/details/gt2xiouamzv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gt2qzkqqbkq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj202588.top/Article/details/gt2nxzyzqjc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gt2brodshoo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gt2wlurxfcv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.bjfxy.top/Article/details/gt2pvhiqkot.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gt2jkmeznuz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gt2gnkmszsj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.iojbl.cn/Article/details/gt2oeiqeihq.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2zjhmwgzu.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpxlfha.html

Java: list.add(4);
来源：http://dali.hammf.cn/Article/details/gt2iusgkthf.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gt2xrdcxpfg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gt2iaxjmcnv.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2oyjbpwwt.html

[D03] 在指定位置插入元素
来源：http://dali.meibo888.top/Article/details/gt2qfqbvjzl.html

Py:   arr.insert(0, 0)
来源：http://dali.c1oappe.top/Article/details/gt2ifddkyka.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gt2ifomoiji.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2gjvdbcsb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gzhubu.top/Article/details/gt2kowzvtok.html

Java: list.add(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2zivnmcnp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gt2yszvgobf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gt2gpqhashj.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gt2imssahga.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gt2hhbmdxuc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gt2mtbjyyqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.redwolf501.top/Article/details/gt2jqsgjotw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gt2ghvznvox.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gt2wtthouqg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gt2fxlitjse.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gt2lptxfaab.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pycfn.com/Article/details/gt2abrduhxu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xziqi.cn/Article/details/gt2xullbfah.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oaofvddq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jhyshpyj.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gt2cojyrmzc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gt2yfeluoqf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gt2eqfjchqi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gt2eyebyfwe.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2dkletvey.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2luzavrer.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gt2mpahadvd.html

[D06] 数组长度
来源：http://dali.sysykeji.top/Article/details/gt2btjbnrad.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2vvpkqmdh.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uejdbvkh.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2trlyhbhd.html

TS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gt2ahrkhjwn.html

Java: list.size();
来源：http://dali.chenlongwang.top/Article/details/gt2xqqqpuku.html

Go:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gmwtmydg.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2xgvcytyg.html

C#:   list.Count;
来源：http://dali.kuanghao11.cn/Article/details/gt2holosaoz.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gt2hyhghuzx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.c1oappe.top/Article/details/gt2xmzbalag.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gt2sljcelmu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2micbpnpv.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gt2rmbklvqn.html

Java: list.subList(1, 4);
来源：http://dali.yuxming.cn/Article/details/gt2skmlnxft.html

Go:   arr[1:4]
来源：http://dali.pycfn.com/Article/details/gt2pyjcajok.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpdrooof.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gt2uvqlbzee.html

[D08] 合并两个数组
来源：http://dali.jinqigfzy.top/Article/details/gt2fuqvczix.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shvnuiwb.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gt2mtdixjjf.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jqgufenzy.top/Article/details/gt2gfgkceva.html

TS:   [...a, ...b];
来源：http://dali.zhixingplan.top/Article/details/gt2zritolnx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2jtoxsael.html

Go:   append(a, b...)
来源：http://dali.jqgufenzy.top/Article/details/gt2ovvnfkgj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hnxiangtu.top/Article/details/gt2rzbfphph.html

C#:   a.Concat(b).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gt2ssbgzrxa.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rprmxkhq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gt2jncgktdm.html

PHP:  sort($arr);
来源：http://dali.tianlin.xyz/Article/details/gt2aljkcczb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.svipenyu.cn/Article/details/gt2wcoyagvw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.tian-w.cn/Article/details/gt2dipofwix.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj202588.top/Article/details/gt2kiyidpgv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2spavpqpd.html

Ruby: arr.sort
来源：http://dali.zdqjudy.top/Article/details/gt2alfpokbs.html

C#:   list.Sort();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2neoelctw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhongyouzk.top/Article/details/gt2xjfqtybm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vgdrjtki.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xujgwzml.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nwbrower.top/Article/details/gt2hwihkugs.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gt2sajbrlkw.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gt2qubttxhp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ehwqpu.com/Article/details/gt2aqakfhvs.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gotoacloud.top/Article/details/gt2divrcdzj.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shuidangran.top/Article/details/gt2fpxvaagl.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gt2rcrtjicz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yongpay.top/Article/details/gt2hsozcqtd.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2cumjoqew.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yuanzhike.top/Article/details/gt2dvhwwhzw.html

TS:   [...arr].reverse();
来源：http://dali.ybcxt.top/Article/details/gt2zfahmbnc.html

Java: Collections.reverse(list);
来源：http://dali.chenzaomai.com/Article/details/gt2ipgzhsfg.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gt2sihuadsj.html

Ruby: arr.reverse
来源：http://dali.hywenlv.cn/Article/details/gt2sfiulwfu.html

C#:   list.Reverse();
来源：http://dali.jyoumei.cn/Article/details/gt2qdnlyrib.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gt2jzpxlihi.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2tptprlkm.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gzhubu.top/Article/details/gt2fuqjamab.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gt2zzifwgrp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gt2osepyqhk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gt2gpsisgfq.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssqdacvd.html

Ruby: arr.index(x)
来源：http://dali.sysykeji.top/Article/details/gt2mlimvksq.html

C#:   list.IndexOf(x);
来源：http://dali.pycfn.com/Article/details/gt2btgjsadi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.quarkkingdee.top/Article/details/gt2agxupmfn.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.guannengcc.top/Article/details/gt2bwiiqvkb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yangfankeji.com/Article/details/gt2nnnkmpwq.html

JS:   arr.filter(x => x > 3)
来源：http://dali.pycfn.com/Article/details/gt2sfconjfy.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2jkderhyk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.haohaochexian.top/Article/details/gt2rvrwwhsh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jvbzruoo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hysaishi.cn/Article/details/gt2jytozljw.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.cdnleiting.top/Article/details/gt2qqemxutl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xinyue.icu/Article/details/gt2eikdhlhk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2eidaxpqh.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gt2qoypldat.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2newjskzf.html

TS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gt2isurvyip.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gt2clsqggnv.html

Go:   // 手写循环
来源：http://dali.chenzaomai.com/Article/details/gt2vijhqjwu.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.wangdashe.top/Article/details/gt2suywqhbb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gt2oirqnlmq.html

[D15] 去重
来源：http://dali.meibo888.top/Article/details/gt2guewwiws.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2btsdepnm.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjaxzugj.html

JS:   [...new Set(arr)]
来源：http://dali.fengsongda.top/Article/details/gt2wxywaixa.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gt2syvdkszv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.zycfv.cn/Article/details/gt2efqkfqbp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cucudq.cn/Article/details/gt2sckaezwx.html

Ruby: arr.uniq
来源：http://dali.sufxvd.cn/Article/details/gt2yavkutgl.html

C#:   list.Distinct().ToList()
来源：http://dali.jyoumei.cn/Article/details/gt2iqsbfhhd.html

[D16] 求和与平均值
来源：http://dali.cheryme.top/Article/details/gt2gquzjjve.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gt2ccektmga.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cqqwz.cn/Article/details/gt2zttgleak.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gt2mtmphxgq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fzhhl.top/Article/details/gt2merwennx.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.cdnleiting.top/Article/details/gt2opomxdek.html

Go:   // 手写循环累加
来源：http://dali.guannengcc.top/Article/details/gt2mlgmipgm.html


<!-- 参考信息 -->