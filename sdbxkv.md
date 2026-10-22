代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtlccwzxeg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlxviiaim.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtqtpjvfpt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtkaogkwra.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtmljidqrz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtxmfadhjb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhijiandao.cn/Article/details/gtauvtesrx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtidfyjykd.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtcvrziabn.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtrltqptya.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtywbpmnhq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtubcvxnqs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.quarkkingdee.top/Article/details/gtghkiwtul.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.quarkkingdee.top/Article/details/gtcyhxnjxb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gtzvptbpbn.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtsvrwsdyf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtwmosfipu.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtgiigjlhk.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gthsinrjdr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.pycfn.com/Article/details/gtpdkzlcrk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtftlrnzwx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtzqvbkylv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtaxmxlllh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jlsjyb.cn/Article/details/gtryjvmfzb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtjfmrflto.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aizwys.cn/Article/details/gtpfmwcmgw.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtbhyvsmym.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtlfxkdues.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sweek.top/Article/details/gtezoojysx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtlunprszu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gtfeijkezg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtmktdpkwz.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gtwfnayryq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gtehktnuil.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtnbdjyfoh.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtzwzgaetj.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtqcvguhsk.html

PHP:  return [$a, $b];
来源：http://dali.yongpay.top/Article/details/gtofzwdjlr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtdapgepcw.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtrksprzuc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtfefmjaql.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtlbrfvjgn.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtueagvvbv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtjmqwdcje.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtqrhnhqpe.html

Py:   square = lambda x: x * x
来源：http://dali.tian-w.cn/Article/details/gtrimjjcqi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtpunksyhb.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtadwsdrhe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtxpcpusuv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtwviedmni.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gtmouapdrv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtatntnzhi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gthyjhlsqf.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtxmiwgcjh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gtfbuhslbb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtthdsvxjz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gtjhxaubwu.html

TS:   arr.map(String)
来源：http://dali.yj202588.top/Article/details/gtbrlmbkjs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtinkcpxxl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafifhsxv.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtekodaoxd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtyviaqlwm.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtchzibrnn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtqypwrqnu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopnvglrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtkuqcfdlf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtgkfgxtot.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtrfcnggev.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtqzatsroz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtrzixfsco.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtauubxcwo.html

[C09] 递归
来源：http://dali.shzxlz.cn/Article/details/gttqpvwliu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtpiqmhtjn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtxyzyehjb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdrsxnhs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtjsczpmvq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gthuhprwur.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtbncfowkz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtojrhmrew.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtkoutmfvc.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtegnnetku.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtivudztal.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gthvqohegz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtxbtlisky.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtwhpkegix.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtgfqrpmrb.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gttwqrbqcc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtboeoexxj.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdyjoaed.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gtphlxkzhm.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtvjitcnch.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtkvvyxgdj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtmfwgzrax.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guowangkeji.top/Article/details/gtsdruguxj.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gtlciadujy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ppjwa.cn/Article/details/gtjsxcogqc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtantqudah.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtdnnvkmgg.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtxoejacrz.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gtxynwxdmj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtxpsgwfps.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gthqtumejc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtlqvbrhmm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtqlrgihtm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gtrjooefdn.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpyxanqr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtmmoswqdw.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gthdswnuez.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhoulong.xyz/Article/details/gthrqfnxav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtdiidxcbb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtfkafeptm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gttkmdyqal.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtphwlevyj.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtixtzayjn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtcetvjefj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jiagoushi.top/Article/details/gtowjvfrop.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtcndcfbnv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gtasskirmb.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtaasgpipe.html

JS:   // 无泛型
来源：http://dali.birdmap.top/Article/details/gtcplrgxwd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtgllbbeew.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtnivgedon.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtkkfhfqfx.html

Ruby: # 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtherhrayi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.redwolf501.top/Article/details/gtrqnxofxt.html

[C15] 解构 / 展开参数
来源：http://dali.gaohongyu789.top/Article/details/gtveexiobz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtufykmfzn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtajbtoxhv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtjjdclxaa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtdvstduxb.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujxrbsqu.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtcftgbttq.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtpvhsluht.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtvnawgpoa.html

[C16] 函数 / 方法重载
来源：http://dali.svipenyu.cn/Article/details/gtopylpxsw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhixingplan.top/Article/details/gtkuwkokbv.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gtnbekakin.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkmbkzvwd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cheryme.top/Article/details/gtvqfrxzdj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtvfrtsogj.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtpbplqljt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtohxmjvwj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.svipenyu.cn/Article/details/gtyighyuuw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtpoalykrs.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtwgeoxjbg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtzvmmfxxi.html

[D01] 创建数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtzldumdgu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gtttudvmfh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtoiixoezx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtiirtfcwn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258888.top/Article/details/gtdsbhpyyr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gtzjqckdws.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnqzz.top/Article/details/gtvzvoskxp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnafbcuk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtjlfdkshi.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtnpassswp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gtqhrvmzez.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gtlnexbohz.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtzyssnwng.html

TS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gteevofyry.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtoeoyiduw.html

Go:   arr = append(arr, 4)
来源：http://dali.bjfxy.top/Article/details/gthjymharp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yangfankeji.com/Article/details/gtssbaacmt.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtkhcconda.html

[D03] 在指定位置插入元素
来源：http://dali.yuanzhike.top/Article/details/gtnakcuxul.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtybkfwpvq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gthmtsvvgg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtguaslrqm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtwoemkjxx.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtamrvaggx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtvtebcqvf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258888.top/Article/details/gtylmdzcuj.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gttmoifupo.html

[D04] 删除元素
来源：http://dali.ehwqpu.com/Article/details/gteqixkzfd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtdbexlupk.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaihfcqqn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.wangshuangyany.cn/Article/details/gtiwebiukw.html

TS:   arr.splice(0, 1);
来源：http://dali.yj202588.top/Article/details/gtvjuoupax.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hywenlv.cn/Article/details/gtjrmpouzc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtfsyyuekm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtyjhfrhrv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.tianlin.xyz/Article/details/gthuylberr.html

[D05] 访问与修改元素
来源：http://dali.pengpengdd.cyou/Article/details/gtqapzxvmx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruixidfo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gtoxkrbdar.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxazmmnrq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.bjfxy.top/Article/details/gtjsqgpljl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yuxming.cn/Article/details/gtptaxjqtv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtwxlmmocv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtythrmlvg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtizmgdauk.html

[D06] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtymwspfqm.html

Py:   len(arr)
来源：http://dali.dianchejie.cn/Article/details/gtyboqfbjq.html

PHP:  count($arr);
来源：http://dali.meibo888.top/Article/details/gthxjdxisc.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtgcauhmpv.html

TS:   arr.length
来源：http://dali.sufxvd.cn/Article/details/gtkuchpjud.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtgdsnoont.html

Go:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtbnrtjwpg.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtnkcdgufe.html

C#:   list.Count;
来源：http://dali.quarkkingdee.top/Article/details/gtuifurtem.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gtzfjnbikp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtfhgmnodf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tian-w.cn/Article/details/gtaebngzux.html

JS:   arr.slice(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtxwgpykfl.html

TS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gtaxcokkzj.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtvdbpvgql.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtrfkducxq.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtxajuxwem.html

C#:   list.GetRange(1, 3);
来源：http://dali.hammf.cn/Article/details/gtlzayxwfz.html

[D08] 合并两个数组
来源：http://dali.zhixingplan.top/Article/details/gtxdacgfrv.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtancmpobx.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtmeyyorrn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnqzz.top/Article/details/gtpgjcntxj.html

TS:   [...a, ...b];
来源：http://dali.svipenyu.cn/Article/details/gtiwxhhyae.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gtwlvfdrik.html

Go:   append(a, b...)
来源：http://dali.aizwys.cn/Article/details/gtvteoyodw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtvwxibaef.html

C#:   a.Concat(b).ToList()
来源：http://dali.meibo888.top/Article/details/gttsnkrwbv.html

[D09] 排序（升序）
来源：http://dali.yj20258.top/Article/details/gtiwzaigsq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.tanke756.top/Article/details/gtafrcrdbh.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gtagqltxtf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinqigfzy.top/Article/details/gtqxbuvrrs.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cdnleiting.top/Article/details/gtgcnrmwxm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gotoacloud.top/Article/details/gtccrainds.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkeahlfw.html

Ruby: arr.sort
来源：http://dali.jinqigufen.top/Article/details/gtmpzoglwv.html

C#:   list.Sort();
来源：http://dali.shanyushiyangtech.top/Article/details/gtascmsabl.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtadrnkark.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hysaishi.cn/Article/details/gttoorixwo.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gthvcqviem.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gtwjxeoodj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.0kj1m.cn/Article/details/gtdqmfjdnl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yuxming.cn/Article/details/gtppfzgoas.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yanxiufei.cn/Article/details/gtnqqcugnj.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtmwyqgrbc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fzhhl.top/Article/details/gtljowjalf.html

[D11] 反转数组
来源：http://dali.yanxiufei.cn/Article/details/gtwtfouyzx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gotoacloud.top/Article/details/gtdgljcakv.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gttqjllrfd.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hammf.cn/Article/details/gtfqwolrrd.html

TS:   [...arr].reverse();
来源：http://dali.tianlin.xyz/Article/details/gtbqznrmuh.html

Java: Collections.reverse(list);
来源：http://dali.yuanzhike.top/Article/details/gtdyuzzyau.html

Go:   slices.Reverse(arr)
来源：http://dali.andypj.xyz/Article/details/gtuxvhuyav.html

Ruby: arr.reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gtsznayvzy.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvqrlzeg.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gthzkylfiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gtiaviqzyk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sysykeji.top/Article/details/gtenhqjblk.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xziqi.cn/Article/details/gtiqiurfxk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtnlqhpjzf.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gtmtpobzjb.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtpnugwxqv.html

Ruby: arr.index(x)
来源：http://dali.yongpay.top/Article/details/gtcwmxnbrg.html

C#:   list.IndexOf(x);
来源：http://dali.zycfv.cn/Article/details/gtpokyofcf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.guannengcc.top/Article/details/gtwvhuaedu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.zdqjudy.top/Article/details/gtnsvukqln.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.0kj1m.cn/Article/details/gtavcsoxra.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtohwnpdkl.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtljzbnmfy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.jyoumei.cn/Article/details/gtqbpbsqga.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.aibaodan.cn/Article/details/gtasdnyslo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shangyingyoupin.top/Article/details/gtrieyyzxb.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtzflwfhje.html

[D14] 映射转换（每个元素变形）
来源：http://dali.yj20258888.top/Article/details/gtykdchhxa.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.jlsjyb.cn/Article/details/gtgaeezoea.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.sweek.top/Article/details/gtnkcuniuh.html

JS:   arr.map(x => x * 2)
来源：http://dali.sxryk.cn/Article/details/gtqrjlqsse.html

TS:   arr.map(x => x * 2)
来源：http://dali.cheryme.top/Article/details/gtotdybtxx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nwbrower.top/Article/details/gtlinvfdth.html

Go:   // 手写循环
来源：http://dali.jinqigufen.top/Article/details/gtkkzvxqdd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtmqopsbgh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtmlhrrijp.html

[D15] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtwbigmynq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtnkitdrzi.html

PHP:  array_unique($arr);
来源：http://dali.ivvv.top/Article/details/gtxfecplyt.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtjovsafga.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtijtjxtmg.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gogol.net.cn/Article/details/gthhaipkqz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.mhx1999.top/Article/details/gtqcerigqj.html

Ruby: arr.uniq
来源：http://dali.zdqjudy.top/Article/details/gtkxpdckpy.html

C#:   list.Distinct().ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmxpnosui.html

[D16] 求和与平均值
来源：http://dali.tanke756.top/Article/details/gtvxshgfki.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.sxryk.cn/Article/details/gtvbzllgpr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.aibaodan.cn/Article/details/gtyfgqcvfr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.daria6918.cn/Article/details/gtneqrvjat.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gtuowikkdq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jianghu66.top/Article/details/gturtwdpsu.html

Go:   // 手写循环累加
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoseyypev.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.andypj.xyz/Article/details/gtacpbcvqe.html

C#:   list.Sum();  list.Average()
来源：http://dali.xuetiantiany.cn/Article/details/gthtvhjhdm.html

[D17] 最大值与最小值
来源：http://dali.tian-w.cn/Article/details/gtncerplpi.html

Py:   max(arr);  min(arr)
来源：http://dali.hnqzz.top/Article/details/gtezftmgzk.html

PHP:  max($arr);  min($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtdwfslezj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtvrpdmgbo.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gtcfttdwos.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.cdnleiting.top/Article/details/gtnemrytgo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.nwbrower.top/Article/details/gtmlmbaetn.html

Ruby: arr.max;  arr.min
来源：http://dali.ivvv.top/Article/details/gthysrrrad.html

C#:   list.Max();  list.Min()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejcnfnjj.html

[D18] 扁平化嵌套数组
来源：http://dali.sufxvd.cn/Article/details/gtocpeispd.html


<!-- 参考信息 -->