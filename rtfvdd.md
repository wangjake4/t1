代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gt2gsgcghtc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gt2sanpddcu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qzzmsqzr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2woostnsn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2xuhlypuf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gt2zzldengf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gt2smkboidt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2zmxzcmby.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gt2buczsiyh.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258888.top/Article/details/gt2kkgmdosm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.andypj.xyz/Article/details/gt2lzbusfyv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2jpybjcir.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2ecoouhou.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yonumen.top/Article/details/gt2wdlmtjzb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gt2gwipehvo.html

Ruby: def greet(name = "World") = name
来源：http://dali.yvedp.cn/Article/details/gt2wuedaibq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gt2jbskemmd.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gt2iqnhaucs.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykqjvka.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhkskapu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yjzifois.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.havefunace.top/Article/details/gt2cmtszqki.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ugyavbjw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aizwys.cn/Article/details/gt2biislyxy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iufsbupi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gt2byvddjxw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gt2sdqnsvxu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gt2avayhjta.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2hvluyntp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2lvvdeiqn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gt2orntyfop.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gt2tpbyexan.html

Go:   // 无：用配置结构体参数
来源：http://dali.cdnleiting.top/Article/details/gt2rhclglzv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2ikykvqhw.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2yahbexkk.html

[C05] 返回多个值
来源：http://dali.snrcjt.cn/Article/details/gt2lbtmwwnu.html

Py:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gt2dlbihggp.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gt2nbcrmoie.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.iojbl.cn/Article/details/gt2adaytdeg.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2qqrtbqvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gt2zthwctcj.html

Go:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2rgmdtfyg.html

Ruby: return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2mmywlmmw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ndbyueqv.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2hknjclgj.html

Py:   square = lambda x: x * x
来源：http://dali.zdqjudy.top/Article/details/gt2gapqxssr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenlongwang.top/Article/details/gt2xkduterz.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2bdtsqwdk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2barykxnl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2rmknyatz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gt2vwvyxgmi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gt2dltozlmb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2npuvqhhs.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2natwxidj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guannengcc.top/Article/details/gt2fkxydhyd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vowvfloh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sufxvd.cn/Article/details/gt2dbdbfbnj.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vsurcsaa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.meibo888.top/Article/details/gt2wezqcozk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aizwys.cn/Article/details/gt2pawvskzm.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzrmfgfc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gt2xzlmawyh.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jylfigbj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gt2pmbwgggt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sysykeji.top/Article/details/gt2xenxucsx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gt2wjmfhsza.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2xgyhvars.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ivvv.top/Article/details/gt2oybcklim.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2awctlybk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhengqikj.top/Article/details/gt2benwzqdu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2dtanaiji.html

[C09] 递归
来源：http://dali.birdmap.top/Article/details/gt2idbycxqr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gt2xanrwsod.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gt2eoyumger.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gt2mvafzizp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gt2illvdfnv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2kbkjlumm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqkxyqv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gt2phnnhfgk.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.birdmap.top/Article/details/gt2rrqiwubm.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2naalooer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tianlin.xyz/Article/details/gt2vjnxldxa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gt2siogutvv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2ecucuhwy.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gt2sjonechp.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2supbvzyy.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2otiikpzf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydyvhpvo.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2bwgifkht.html

[C11] 模块导入与导出
来源：http://dali.ydzc1.top/Article/details/gt2djdygsjw.html

Py:   from module import func
来源：http://dali.cqqwz.cn/Article/details/gt2nktxijqb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangdashe.top/Article/details/gt2ylafbkey.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2sjmsyfup.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.birdmap.top/Article/details/gt2mvsenekt.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gt2hcvtwctk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pengpengdd.cyou/Article/details/gt2tncegpbi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gt2wrxxpsbc.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gt2iawuksyt.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gt2xojnjpkk.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gt2qbkigjkw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj20258888.top/Article/details/gt2clcedbks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gt2rwrqwpue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gt2nnnktbny.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gt2ajwpqkjd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gt2vzecvatu.html

Ruby: -> { puts "run" }.call
来源：http://dali.daria6918.cn/Article/details/gt2hxmoarog.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gt2hsamzpxg.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gt2fwiaqenk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2rgmadlxb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2bqzdrawy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gt2kjxucejz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2aadpimpy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2douvpads.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gt2ijfrrius.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gt2npflkzwq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gt2xaleximd.html

[C14] 泛型函数
来源：http://dali.redwolf501.top/Article/details/gt2jnozwffd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gt2mvfwxwtk.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2nqpjcwlo.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gt2bfzfmbap.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2didkbnzc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gt2dhcgulmc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hyzaxvll.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gt2iijkcptu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2btvaggox.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxnjkgiq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2wmcasagi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gt2ucybqpke.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2gdzyhbzo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2fberggqp.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gt2rfemnlxe.html

Go:   // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfkphorb.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gt2dskcyyxa.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gt2tahgiido.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gt2hfowgste.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gt2tqjjspsh.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gt2shbihsfo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj202588.top/Article/details/gt2njgseuhb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gt2ppdzrapu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2cpgcgxco.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gt2vygknexf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuanzhike.top/Article/details/gt2lkhuthvj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yongpay.top/Article/details/gt2oajlmfeh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2pcyuezau.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gt2zrpmekgf.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2rfonwwfw.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gt2phqrqxrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gt2yxcerlrd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fengsongda.top/Article/details/gt2bpdpkfyf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2dvryaili.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gt2cwrsxvtu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gt2caezegkx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gt2lsozfnwg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gt2spzcsmbf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.redwolf501.top/Article/details/gt2lkepcgua.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gt2unnbolju.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2aohsrzxg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xuanzx.com/Article/details/gt2mqpiryia.html

JS:   arr.push(4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2chdgvuna.html

TS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gt2vvwvkxsc.html

Java: list.add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2snwvrjgn.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilylvkmf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.feifeiyinyue.top/Article/details/gt2exolxsgx.html

C#:   list.Add(4);
来源：http://dali.andypj.xyz/Article/details/gt2bvmixaeg.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gt2cowjkkmi.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gt2qaxuybvd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2nhegskvi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gt2tpouwywe.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gt2uiyhsjuu.html

Java: list.add(0, 0);
来源：http://dali.fengsongda.top/Article/details/gt2hpjsdzfi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yanxiufei.cn/Article/details/gt2ueqjerdv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnxiangtu.top/Article/details/gt2itbygman.html

C#:   list.Insert(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gt2muyyltey.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gt2liscwcew.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.0kj1m.cn/Article/details/gt2ljgutaiy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctnblvkf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbcbfrsg.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2pwsfhsmm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gt2ijebmtwq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tduimspz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ehwqpu.com/Article/details/gt2zxpezqkt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gt2motnearo.html

[D05] 访问与修改元素
来源：http://dali.cucudq.cn/Article/details/gt2eesdzffq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2ghykjifk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2udxhiass.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gt2iwaiiqms.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jlsjyb.cn/Article/details/gt2npzwqzic.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbpwqony.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gt2giwotaor.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gt2dpkfyghi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2bslqjyue.html

[D06] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gt2dfkvrzoe.html

Py:   len(arr)
来源：http://dali.yuxming.cn/Article/details/gt2rzjqyurt.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2sfjwplwk.html

JS:   arr.length
来源：http://dali.yvedp.cn/Article/details/gt2uzaptokp.html

TS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2lftrnyem.html

Java: list.size();
来源：http://dali.hysaishi.cn/Article/details/gt2frsgobqk.html

Go:   len(arr)
来源：http://dali.cashguo.top/Article/details/gt2gzyagphg.html

Ruby: arr.length; arr.size
来源：http://dali.cashguo.top/Article/details/gt2owfkyxps.html

C#:   list.Count;
来源：http://dali.yj20258888.top/Article/details/gt2khkatkoz.html

[D07] 切片 / 取子数组
来源：http://dali.aibaodan.cn/Article/details/gt2qtkhrcqm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gt2iusxpqkq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2knvlnhtl.html

JS:   arr.slice(1, 4);
来源：http://dali.svipenyu.cn/Article/details/gt2rvcnuczp.html

TS:   arr.slice(1, 4);
来源：http://dali.hammf.cn/Article/details/gt2bffgjplu.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gt2bzknpfpp.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gt2orrqqtzb.html

Ruby: arr[1, 3]
来源：http://dali.cqqwz.cn/Article/details/gt2ivrlytit.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2wgloejgy.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gt2uwkddpiu.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gt2nnmhhjjs.html

PHP:  array_merge($a, $b);
来源：http://dali.sufxvd.cn/Article/details/gt2wxftwhjq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gt2kjxwgmje.html

TS:   [...a, ...b];
来源：http://dali.xuanzx.com/Article/details/gt2hqiwblls.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ivvv.top/Article/details/gt2ihwhpwve.html

Go:   append(a, b...)
来源：http://dali.jinqigfzy.top/Article/details/gt2qfpgftnt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenzaomai.com/Article/details/gt2qzyeandy.html

C#:   a.Concat(b).ToList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jksfpvmt.html

[D09] 排序（升序）
来源：http://dali.wangshuangyany.cn/Article/details/gt2bqyucphn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ikvgvlpz.html

PHP:  sort($arr);
来源：http://dali.zdqjudy.top/Article/details/gt2cpgnergm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gt2pezabtmk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uitwrali.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gt2vxujlhfv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2wsofbuli.html

Ruby: arr.sort
来源：http://dali.cheryme.top/Article/details/gt2acuecaka.html

C#:   list.Sort();
来源：http://dali.jianghu66.top/Article/details/gt2iokqrhko.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.haohaochexian.top/Article/details/gt2oimetmhj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gt2wxmjtnos.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gt2zloeedod.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hywenlv.cn/Article/details/gt2mjxgiofj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gt2hhsiojpc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwxwhfke.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmlpfcqo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vjjgcnuu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.snrcjt.cn/Article/details/gt2dtanobak.html

[D11] 反转数组
来源：http://dali.meibo888.top/Article/details/gt2lftvpcfu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yuanzhike.top/Article/details/gt2ncrmicjd.html

PHP:  array_reverse($arr);
来源：http://dali.yj202588.top/Article/details/gt2acrzybxk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gt2peitcfos.html

TS:   [...arr].reverse();
来源：http://dali.jqgufenzy.top/Article/details/gt2oerifnfj.html

Java: Collections.reverse(list);
来源：http://dali.smart0.xyz/Article/details/gt2kdnqadzk.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gt2rygacidc.html

Ruby: arr.reverse
来源：http://dali.ppjwa.cn/Article/details/gt2atlkctqk.html

C#:   list.Reverse();
来源：http://dali.pengpengdd.cyou/Article/details/gt2wmmoopye.html

[D12] 查找元素下标
来源：http://dali.zhongyouzk.top/Article/details/gt2obcxrmhe.html

Py:   arr.index(x);  x in arr
来源：http://dali.jqgfzy.top/Article/details/gt2ccykpsgb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2bmcoyeae.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jiagoushi.top/Article/details/gt2cultaofl.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2pbxxwxts.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.tanke756.top/Article/details/gt2suhcpxkw.html

Go:   slices.Index(arr, x)
来源：http://dali.ehwqpu.com/Article/details/gt2ikskxqmt.html

Ruby: arr.index(x)
来源：http://dali.xylfe.cn/Article/details/gt2uqdlvwmc.html

C#:   list.IndexOf(x);
来源：http://dali.dianchejie.cn/Article/details/gt2hzmugpcj.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xinyue.icu/Article/details/gt2bcjxqbsc.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2upiewxcc.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2vfyolhni.html

JS:   arr.filter(x => x > 3)
来源：http://dali.guowangkeji.top/Article/details/gt2vamziwpt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gt2zhttoutn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.sysykeji.top/Article/details/gt2vzhbiutr.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.kuanghao11.cn/Article/details/gt2fvjbxogq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jinqigufen.top/Article/details/gt2kgeqzqgj.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.meibo888.top/Article/details/gt2pqcsqztu.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zdqjudy.top/Article/details/gt2coqmxtqs.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gt2wstqhzmt.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sxryk.cn/Article/details/gt2uzighaju.html

JS:   arr.map(x => x * 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2onbvaelq.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gt2lyuogdwf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2zigfldyf.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gt2wtfrsnqk.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj20258.top/Article/details/gt2fwlmuypi.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjjecjlc.html

[D15] 去重
来源：http://dali.sweek.top/Article/details/gt2pfqvfuol.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gt2qsprhsoy.html

PHP:  array_unique($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2ppvmbvng.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2gfujqlpd.html

TS:   [...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2ibttaakn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gt2qbtddpax.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenlongwang.top/Article/details/gt2jidttibx.html

Ruby: arr.uniq
来源：http://dali.ybcxt.top/Article/details/gt2pivrdety.html

C#:   list.Distinct().ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2tjapserc.html

[D16] 求和与平均值
来源：http://dali.jyoumei.cn/Article/details/gt2gukypikh.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jiagoushi.top/Article/details/gt2rvctbuxs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gt2tvniadrs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxkxvajm.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vjwsygcz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sxryk.cn/Article/details/gt2piahqsmg.html

Go:   // 手写循环累加
来源：http://dali.chenzaomai.com/Article/details/gt2bxnjvtqa.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.feifeiyinyue.top/Article/details/gt2bxqpuufl.html

C#:   list.Sum();  list.Average()
来源：http://dali.hysaishi.cn/Article/details/gt2cozvrubx.html

[D17] 最大值与最小值
来源：http://dali.yuanzhike.top/Article/details/gt2frvktrvv.html

Py:   max(arr);  min(arr)
来源：http://dali.sufxvd.cn/Article/details/gt2sffbonje.html

PHP:  max($arr);  min($arr);
来源：http://dali.nanxinkj.top/Article/details/gt2orrjkhfn.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2klxudsbg.html

TS:   Math.max(...arr);
来源：http://dali.havefunace.top/Article/details/gt2urwdppex.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sweek.top/Article/details/gt2jpljaeal.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.andypj.xyz/Article/details/gt2zzpabbij.html

Ruby: arr.max;  arr.min
来源：http://dali.snrcjt.cn/Article/details/gt2zrthjcmt.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wizouzkh.html

[D18] 扁平化嵌套数组
来源：http://dali.redwolf501.top/Article/details/gt2biupowhf.html


<!-- 参考信息 -->