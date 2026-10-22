代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2fcaewmzu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2cjngskpk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gt2jkhrfvwq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2nbwhlfaz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gt2ffmiwmar.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yongpay.top/Article/details/gt2smplxkft.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gt2cynwjyge.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2ikssupsp.html

[C02] 默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gt2wylhsiag.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gt2nudaqzvx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gt2mlxjxzzz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gt2tdgvpdgb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gt2rldscaiu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.daxiang520.top/Article/details/gt2lmofgugb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgufenzy.top/Article/details/gt2fmxctxwc.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gt2ctrrgbfe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gt2xzzagybz.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gt2nvgrqino.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2iiealepo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gt2lyagsikq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2arsghgfz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2yopkwgnh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gt2nzqyenmu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gt2pvapnfcw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gt2ljttcoal.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gt2kqdnfiwn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2xohtyvsw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mnzmlpjk.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gt2lrwoklnv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmssxdtc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2gwbjwlbj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jlsjyb.cn/Article/details/gt2bortvwxo.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gt2klspwgmc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gt2auknhese.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gt2mivudzru.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gt2yzcfjswt.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2nkejxwlb.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gt2xslcyeqr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gt2lirewtpo.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gt2sjghxqzi.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gt2ukkhhack.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2lthzhkqb.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2cblbzolq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gt2krqwekpf.html

[C06] 匿名函数 / lambda
来源：http://dali.hnqzz.top/Article/details/gt2ghpwdgkz.html

Py:   square = lambda x: x * x
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubhmfowk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2ssgovlif.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gt2ydtuarid.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2kjmchsnm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rupkvvjd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gt2sctauvex.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gt2fgcmzmnq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2euauphtn.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gt2tgenkvjn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gt2teivnrqj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2rdosocsx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2gcvzclvb.html

TS:   arr.map(String)
来源：http://dali.nanxinkj.top/Article/details/gt2sxebstvl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jianghu66.top/Article/details/gt2tacizoyi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gt2dbeereta.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gt2rhrcexnn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2gbhyfzvn.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gt2vqtzggcb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gt2qjqshmfd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nxmjfyls.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2xbbwotzk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ozowhhoi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnqzz.top/Article/details/gt2judkroiu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gt2qrtjygkr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ryrushjc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2skzhxelm.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gt2pvwfkkgm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zhbbakjp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2hbrsdrxo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gt2drywcuxs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gt2pnwngran.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gt2favdpmgn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jiagoushi.top/Article/details/gt2gltctyya.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2tvzzldkk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pycfn.com/Article/details/gt2wdbeyppa.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gt2idtznxuc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj202588.top/Article/details/gt2mcurshfv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258.top/Article/details/gt2awrxdksc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gt2qbbqfcmi.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2wakxxved.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2rwxxjral.html

Go:   花括号块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2dmhpdflr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrzkjzi.html

C#:   块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2ejmpncal.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gt2bolxrrbz.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gt2psgeyccc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ehwqpu.com/Article/details/gt2uhncdyux.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gt2djjcjyja.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gt2pailipnh.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gt2edrepbtj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nwbrower.top/Article/details/gt2tgaorsfx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gt2dazpenzh.html

C#:   using System.Text;
来源：http://dali.yanxiufei.cn/Article/details/gt2xccogmfn.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gt2hokgfdhb.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gt2hhuqqjka.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jianghu66.top/Article/details/gt2jqixujto.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gt2uuaifwry.html

TS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gt2whbftqze.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gt2kcdhyqwo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2nhqnortd.html

Ruby: -> { puts "run" }.call
来源：http://dali.snrcjt.cn/Article/details/gt2foyqmrcj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gt2ntzqmlzv.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gt2ovguuhnn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gt2pwtiyoow.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2gioyzybh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yongpay.top/Article/details/gt2hrwfvyjg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fykvjefi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2zafuodie.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gt2asuviflp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2dxzobdqi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gt2qgjrxwhu.html

[C14] 泛型函数
来源：http://dali.hfpthk.cn/Article/details/gt2geijnxdq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.meibo888.top/Article/details/gt2ydpxgkiy.html

PHP:  // 无泛型
来源：http://dali.nanxuanxn.top/Article/details/gt2cmlnrsba.html

JS:   // 无泛型
来源：http://dali.redwolf501.top/Article/details/gt2uqxnubnk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gt2etkanozy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgfzy.top/Article/details/gt2qsomllyc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zycfv.cn/Article/details/gt2gkhddoxe.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2tuaytayg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gt2epsmcdpz.html

[C15] 解构 / 展开参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwrtlgpa.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mnhrttch.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yongpay.top/Article/details/gt2ebympaxg.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2qdjpuidj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gt2xwttpdwo.html

Java: // 无解构
来源：http://dali.xylfe.cn/Article/details/gt2cicmeesf.html

Go:   // 无解构
来源：http://dali.tian-w.cn/Article/details/gt2ombwkvdb.html

Ruby: a, b = pair
来源：http://dali.shzxlz.cn/Article/details/gt2gcizdmwm.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gt2heslcrkm.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gt2flgybwvk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2ovpnhsug.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2zhtldqdb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cashguo.top/Article/details/gt2bmsbxuuk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uoezjjxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj20258888.top/Article/details/gt2bvndgflv.html

Go:   // 无重载：用不同函数名
来源：http://dali.jianghu66.top/Article/details/gt2aawpkedt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gt2ppaheaah.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hysaishi.cn/Article/details/gt2xooqzkri.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2qyhybqck.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gt2hyukburj.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2egkdaqbb.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gt2sbqawijs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gt2dhmvkwxi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuxming.cn/Article/details/gt2hguyseps.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.9152youxi.cn/Article/details/gt2ogsevcsr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yueranfly.top/Article/details/gt2fthgjorv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gt2ciffvbro.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gt2fornvnfw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gt2yycueicl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gt2vubhwite.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gt2bbdjpntk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.meibo888.top/Article/details/gt2iqizbshc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2zeyphvuf.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gt2ksalkscw.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2wilcrigb.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gt2lxpklgwf.html

Go:   arr = append(arr, 4)
来源：http://dali.redwolf501.top/Article/details/gt2bujnlmxy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gt2kayujyag.html

C#:   list.Add(4);
来源：http://dali.bjfxy.top/Article/details/gt2amppgdwz.html

[D03] 在指定位置插入元素
来源：http://dali.jqgfzy.top/Article/details/gt2eihatbgy.html

Py:   arr.insert(0, 0)
来源：http://dali.xziqi.cn/Article/details/gt2vwmyzkvv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.meibo888.top/Article/details/gt2eleotsqo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpkqprlx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gt2fiiysewt.html

Java: list.add(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2mpbbshae.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gt2ydffgoob.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj202588.top/Article/details/gt2fnyotgej.html

C#:   list.Insert(0, 0);
来源：http://dali.birdmap.top/Article/details/gt2qhdrbaun.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gt2aebthmoi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.svipenyu.cn/Article/details/gt2rhlzqcer.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gt2yufeaktm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gt2xefdoxbh.html

TS:   arr.splice(0, 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hanpjbxp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gt2rskxzypi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2pdujahev.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gt2jlszkpgc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yuanzhike.top/Article/details/gt2pueznctp.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gt2agzuhgjt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bicmdlxm.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.andypj.xyz/Article/details/gt2imyydrnu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gt2xphmyxon.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gt2zfkecwih.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gt2glcvvwco.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2fgovtvkz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2uiiubqai.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2aabbenyg.html

[D06] 数组长度
来源：http://dali.shzxlz.cn/Article/details/gt2gjmzqnyf.html

Py:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2okcthroe.html

PHP:  count($arr);
来源：http://dali.sysykeji.top/Article/details/gt2vtcadncr.html

JS:   arr.length
来源：http://dali.hammf.cn/Article/details/gt2edrzpcdu.html

TS:   arr.length
来源：http://dali.tanke756.top/Article/details/gt2gnkdwque.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gt2iuktwxkp.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2nwlnadxp.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gt2zmlnbxxs.html

C#:   list.Count;
来源：http://dali.chenzaomai.com/Article/details/gt2digtqvhf.html

[D07] 切片 / 取子数组
来源：http://dali.dashuyun.cn/Article/details/gt2vcqnvscj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gotoacloud.top/Article/details/gt2zktyirem.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrpspyua.html

JS:   arr.slice(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gt2gvetpjdt.html

TS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gt2pcimtjjz.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gt2bfgrbgop.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gt2egyyxlaq.html

Ruby: arr[1, 3]
来源：http://dali.sxryk.cn/Article/details/gt2zfovyewm.html

C#:   list.GetRange(1, 3);
来源：http://dali.sweek.top/Article/details/gt2cdovwpjk.html

[D08] 合并两个数组
来源：http://dali.haohaochexian.top/Article/details/gt2uvtagyut.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gt2ahmtkigf.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mqweutef.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gt2yokpblkb.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gt2kxynmuqs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2jcwnijdi.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gt2cztgcqhd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.fengsongda.top/Article/details/gt2ztgfnpey.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gt2qihopllk.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kaihvgvw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shzxlz.cn/Article/details/gt2kybcjysh.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2ihnqjfxw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gt2srnrdeph.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gt2pxfiizwh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gt2rpzkrnyl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zgeflkjz.html

Ruby: arr.sort
来源：http://dali.gaohongyu789.top/Article/details/gt2mxocjgnh.html

C#:   list.Sort();
来源：http://dali.meibo888.top/Article/details/gt2xbrvnder.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gt2ligxmpjy.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqgvhbru.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.dianchejie.cn/Article/details/gt2eyumycir.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gt2xnyoiwtc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gt2tflqkksf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nwbrower.top/Article/details/gt2szpejlbx.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gt2rhsdtcab.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gt2xgkuryoa.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yj20258.top/Article/details/gt2xjkhwngt.html

[D11] 反转数组
来源：http://dali.c1oappe.top/Article/details/gt2kzqpnkdb.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gt2pqbcrktw.html

PHP:  array_reverse($arr);
来源：http://dali.hywenlv.cn/Article/details/gt2sfjdofji.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhongyouzk.top/Article/details/gt2qvpfuiot.html

TS:   [...arr].reverse();
来源：http://dali.tanke756.top/Article/details/gt2thikerli.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gt2gjqylfcs.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmikwlsa.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2fnbsackt.html

C#:   list.Reverse();
来源：http://dali.svipenyu.cn/Article/details/gt2bpauzrdd.html

[D12] 查找元素下标
来源：http://dali.daxiang520.top/Article/details/gt2cryxdtck.html

Py:   arr.index(x);  x in arr
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfzbeike.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hfpthk.cn/Article/details/gt2btrgizvj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gt2qrqlydyb.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gt2wsyoyxzr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zycfv.cn/Article/details/gt2kcpwfytq.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gt2clqfikbs.html

Ruby: arr.index(x)
来源：http://dali.birdmap.top/Article/details/gt2sxzkvzmk.html

C#:   list.IndexOf(x);
来源：http://dali.9152youxi.cn/Article/details/gt2nzupkbri.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zycfv.cn/Article/details/gt2zntruvrb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zycfv.cn/Article/details/gt2dcpmnvfj.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yonumen.top/Article/details/gt2ckqxunsc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gt2rxnbnzdl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.316326.xyz/Article/details/gt2vnjmtwah.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.svipenyu.cn/Article/details/gt2eygrlglh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.redwolf501.top/Article/details/gt2pbvzgqui.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gt2umbqzfzk.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yvedp.cn/Article/details/gt2gcyiiclq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.daxiang520.top/Article/details/gt2yyaqjrkn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gt2yklqktno.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2busqozgi.html

JS:   arr.map(x => x * 2)
来源：http://dali.ydzc1.top/Article/details/gt2zvhuczgy.html

TS:   arr.map(x => x * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2ecoetlcb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangdashe.top/Article/details/gt2cipgdkgz.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gt2szhitvai.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gt2vopthbsf.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oufuecmx.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2cbvevkzm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2nipklyyj.html

PHP:  array_unique($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xjvnjaaq.html

JS:   [...new Set(arr)]
来源：http://dali.chenzaomai.com/Article/details/gt2rmodvofd.html

TS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gt2rxdhosqx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gt2kbvzebfr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigfzy.top/Article/details/gt2ckaanbsx.html

Ruby: arr.uniq
来源：http://dali.gotoacloud.top/Article/details/gt2fxzlstdn.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gt2uowcgdib.html

[D16] 求和与平均值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ynklggwo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aqzmfoul.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.316326.xyz/Article/details/gt2fnpnynyl.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yongpay.top/Article/details/gt2jflnfqbc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gt2lepgrvrb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.shuidangran.top/Article/details/gt2nxuownld.html

Go:   // 手写循环累加
来源：http://dali.nwbrower.top/Article/details/gt2hugqziap.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.vqdsnc.cn/Article/details/gt2ymimzbxt.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gt2ssctlhcw.html

[D17] 最大值与最小值
来源：http://dali.zhoulong.xyz/Article/details/gt2epeqfytv.html

Py:   max(arr);  min(arr)
来源：http://dali.tian-w.cn/Article/details/gt2aqknbgxv.html

PHP:  max($arr);  min($arr);
来源：http://dali.meibo888.top/Article/details/gt2zcotwhji.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.daxiang520.top/Article/details/gt2enlvzxbw.html

TS:   Math.max(...arr);
来源：http://dali.aibaodan.cn/Article/details/gt2kivmzudi.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gotoacloud.top/Article/details/gt2lymieumr.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pycfn.com/Article/details/gt2xbmxuwxi.html

Ruby: arr.max;  arr.min
来源：http://dali.sweek.top/Article/details/gt2hhrhllpt.html

C#:   list.Max();  list.Min()
来源：http://dali.chenzaomai.com/Article/details/gt2imesxzsq.html

[D18] 扁平化嵌套数组
来源：http://dali.gzhubu.top/Article/details/gt2wzmaglry.html


<!-- 参考信息 -->