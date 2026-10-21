代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gtmjqriwcy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtfdhagrru.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtyamufucc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtxmbkblwd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtmaugkvdi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.smart0.xyz/Article/details/gtickfeoiy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gttemcicax.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtgrpxaamw.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gthczukyta.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtnnnihhug.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtxewhvbnx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpratojbo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtnedwqdnc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.vqdsnc.cn/Article/details/gtpmhzpxst.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hysaishi.cn/Article/details/gthezscyhl.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtgshxohyt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gtxcffroxk.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gtxnclffdc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtzstrofdb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gtzgrqujnd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtgbsozxiy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtiytgbegk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hfpthk.cn/Article/details/gtpuvtitck.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pycfn.com/Article/details/gtxdwgkcyz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gtzomtywjz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gaohongyu789.top/Article/details/gtiznftrsl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjzehulab.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtehzizson.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.9152youxi.cn/Article/details/gtdtoafnyj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqlcsnze.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtdnawdtac.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtgusbsdph.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtvrmttbsd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtxamqnobc.html

C#:   f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtrvkpffme.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gttvbmdkqg.html

Py:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtjcjbamko.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gtajvywuvs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gttqoyhlme.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtkmfndydo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtqklopitf.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstymgzlq.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtyozhdgpc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtukgffxoq.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjllvdbgk.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtdfqzzpje.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtxvwafyrr.html

JS:   const square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtliafvmmc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtruhaludb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gtyxqhlfau.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtomomdpyx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtftxemxme.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtrvoitapr.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtdkkolblo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gthutfegmq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtjmjxqhlm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtaykpoiha.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtmvtlqgfz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtxbddjvnu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtkvorwswk.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrraofqia.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gtunnuanwf.html

[C08] 闭包
来源：http://dali.jinqigufen.top/Article/details/gtkkpsjrww.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gtuhmfrccy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtpsfnxthx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtjvmbzooi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtxjjjmetp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtxkxkckwx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtgjcoiwuz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtmnbwcvsg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtiducqfkp.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtgvajengu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gtqjtjvkfj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtoswahhfp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtbpswbgxe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtmsooabco.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtjcnvxhmg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtjenqlsij.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtcphevspr.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtqvctnxli.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtaszvofzn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtvdtkprwt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtokprcgzv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gtxmxjvmtd.html

TS:   同 JS
来源：http://dali.gotoacloud.top/Article/details/gtoyusypdp.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtekmmbwah.html

Go:   花括号块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtmcwswnne.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtnqzenkmk.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtzcwjited.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtgqvrswax.html

Py:   from module import func
来源：http://dali.fengsongda.top/Article/details/gtjdzxwekw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenlongwang.top/Article/details/gtmmcnxryf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtzxoxkkdn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtcxsbzinv.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtbxyhgemu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yanxiufei.cn/Article/details/gtapavzztr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtqoaxftwf.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtgujesqkz.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtpveqrwab.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigfzy.top/Article/details/gtnrxcuvyk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sxryk.cn/Article/details/gterqabtvy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtwcohkpvf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtgpulmefn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gteixnngmk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtkznswybn.html

Ruby: -> { puts "run" }.call
来源：http://dali.ybcxt.top/Article/details/gtlsvvlksm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgfzy.top/Article/details/gtgqtbuvcs.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtwmypaqcw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.dashuyun.cn/Article/details/gtunxrflqm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcfyywst.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.316326.xyz/Article/details/gtuwckrcef.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtcjtyprzy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtqadjafui.html

Go:   func add(a, b int) int
来源：http://dali.shangyingyoupin.top/Article/details/gtrptxyxqd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gtepfldadp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtidafgttz.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtluozpcpj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gtcflpbvkq.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gtgndpwvwa.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtbxptqvvr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdlkvdud.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtzfkprjzi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtmswrgcoh.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtggdgwamb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtickrxrbs.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtymaoutdd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gtspzpuimy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gtekzkfnfu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hammf.cn/Article/details/gtvwpwiobx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gthhsaadaj.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtfxxiuncp.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtbekruikd.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtysmnonzn.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gtbldsqqqu.html

[C16] 函数 / 方法重载
来源：http://dali.sxryk.cn/Article/details/gtifugyuuj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nanxuanxn.top/Article/details/gtvtakvpqu.html

PHP:  // 无重载
来源：http://dali.mhx1999.top/Article/details/gtkngiljdv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhixingplan.top/Article/details/gtrzwbioad.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.andypj.xyz/Article/details/gttryvkull.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtrhlvopen.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtlowvryan.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtxdxftfuw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hammf.cn/Article/details/gtbhemvqzn.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtqpeobrcz.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtvyurrfiv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtgtetbgtb.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtsdduxwtp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aizwys.cn/Article/details/gtmsofpdwh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gtcovqivvi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gttblijgsk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.bjfxy.top/Article/details/gtyehbtuwy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtseqpardc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ppjwa.cn/Article/details/gtclqyosua.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtemgsmuor.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gttrlpqkna.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtfgkwlrnj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gttkytggos.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiashjezx.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtywahygmn.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqgpcnkgv.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtpextfjwx.html

Go:   arr = append(arr, 4)
来源：http://dali.ybcxt.top/Article/details/gtkvjqyfrt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gtkaqcbpqv.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtbybgeafi.html

[D03] 在指定位置插入元素
来源：http://dali.jiagoushi.top/Article/details/gttmclznha.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gthpuoljhn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aibaodan.cn/Article/details/gtrxtysxjj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.andypj.xyz/Article/details/gtypaazdnc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtzuhwnikh.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gtpbgipqss.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.0kj1m.cn/Article/details/gtkarnodnt.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtxmxiscpd.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtnpqzulsf.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gtmmcqyvdb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.sxryk.cn/Article/details/gthhocytvt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtcoluzrvv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yvedp.cn/Article/details/gtaveawgyu.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtelxyqypt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zycfv.cn/Article/details/gtorifvrwh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtnedirjdh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.snrcjt.cn/Article/details/gtxywbdywa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daxiang520.top/Article/details/gtuauwcorg.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gtdmjjjasx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtindqluoc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtcrhowbaf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfibomya.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hongshengwenyu.top/Article/details/gtjlnxnhfl.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtjnunalfg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtbfabsavp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtaurrxcly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtqaadonyv.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtaqpxtzyn.html

Py:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gthgvoftzu.html

PHP:  count($arr);
来源：http://dali.hnqzz.top/Article/details/gtzfstqrnf.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtsgtifmyg.html

TS:   arr.length
来源：http://dali.hywenlv.cn/Article/details/gtkxfzefzi.html

Java: list.size();
来源：http://dali.nanxuanxn.top/Article/details/gtaeuafuyw.html

Go:   len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gtdybojzqa.html

Ruby: arr.length; arr.size
来源：http://dali.guowangkeji.top/Article/details/gtarafxoje.html

C#:   list.Count;
来源：http://dali.fzhhl.top/Article/details/gtctzubgpl.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtpnfbwgac.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwmvhjpg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gtcgdjfenk.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtpxbrsjey.html

TS:   arr.slice(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtqlozvjuj.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtvqtoedsb.html

Go:   arr[1:4]
来源：http://dali.jinqigufen.top/Article/details/gtecolunuk.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gtxpyoinki.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtprwyacbq.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtjcfgxtgs.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtprcohdck.html

PHP:  array_merge($a, $b);
来源：http://dali.chenjidiqi.icu/Article/details/gtogqvzbrh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuxming.cn/Article/details/gtdrcvdrrr.html

TS:   [...a, ...b];
来源：http://dali.tianlin.xyz/Article/details/gtlocdoatt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtrgsxcmmu.html

Go:   append(a, b...)
来源：http://dali.cqqwz.cn/Article/details/gtankoezoi.html

Ruby: a + b;  a.concat(b)
来源：http://dali.quarkkingdee.top/Article/details/gthmmjffza.html

C#:   a.Concat(b).ToList()
来源：http://dali.tanke756.top/Article/details/gtgtkvjanm.html

[D09] 排序（升序）
来源：http://dali.ppjwa.cn/Article/details/gtiftfdbwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhoulong.xyz/Article/details/gtudbqmayc.html

PHP:  sort($arr);
来源：http://dali.sweek.top/Article/details/gtmyveffpg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqgcraup.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cashguo.top/Article/details/gtkihavimh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinghuilouyu.cn/Article/details/gtrisfqpnd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tianlin.xyz/Article/details/gtjzzbogev.html

Ruby: arr.sort
来源：http://dali.mhx1999.top/Article/details/gtximogdgo.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gtfutjnkpg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtoukqsdqo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtjonwfueh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtbnqlqens.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgotqctbm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yangfankeji.com/Article/details/gtsaoxbrsf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.hammf.cn/Article/details/gtkpnuhnxo.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtmkistwvf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.316326.xyz/Article/details/gtmggzcrjl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.quarkkingdee.top/Article/details/gtghjdwwkz.html

[D11] 反转数组
来源：http://dali.jiagoushi.top/Article/details/gthcjamlhi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtnjwpobcl.html

PHP:  array_reverse($arr);
来源：http://dali.cheryme.top/Article/details/gthisnjhaz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.daria6918.cn/Article/details/gtbnntavon.html

TS:   [...arr].reverse();
来源：http://dali.daria6918.cn/Article/details/gtyehfbfkg.html

Java: Collections.reverse(list);
来源：http://dali.snrcjt.cn/Article/details/gtfgagzhjt.html

Go:   slices.Reverse(arr)
来源：http://dali.redwolf501.top/Article/details/gtdfbnqpaj.html

Ruby: arr.reverse
来源：http://dali.wangdashe.top/Article/details/gtvopcupty.html

C#:   list.Reverse();
来源：http://dali.yonumen.top/Article/details/gtipjaxpyk.html

[D12] 查找元素下标
来源：http://dali.feifeiyinyue.top/Article/details/gtxnsalxvh.html

Py:   arr.index(x);  x in arr
来源：http://dali.zycfv.cn/Article/details/gttcwzxwjt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtvvwcvmnm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yongpay.top/Article/details/gtpyrnqbyk.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmtsdyjyd.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenzaomai.com/Article/details/gtemrdyvst.html

Go:   slices.Index(arr, x)
来源：http://dali.ydzc1.top/Article/details/gtsgfuwluz.html

Ruby: arr.index(x)
来源：http://dali.0kj1m.cn/Article/details/gtpaudeycl.html

C#:   list.IndexOf(x);
来源：http://dali.pengpengdd.cyou/Article/details/gtiupbmzzq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hfpthk.cn/Article/details/gtfvmicbah.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.smart0.xyz/Article/details/gttyvpcggy.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsertgzh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtzvwbiuna.html

TS:   arr.filter(x => x > 3)
来源：http://dali.guannengcc.top/Article/details/gtzlitcxwy.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhijiandao.cn/Article/details/gtbccstogh.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.feifeiyinyue.top/Article/details/gtbtsbmhxe.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tanke756.top/Article/details/gtaosuiprs.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gotoacloud.top/Article/details/gtlvtnjnwv.html

[D14] 映射转换（每个元素变形）
来源：http://dali.cheryme.top/Article/details/gtjmpqusfi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ydzc1.top/Article/details/gtdqpgldfz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.redwolf501.top/Article/details/gthsrhkabl.html

JS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtjkplysfn.html

TS:   arr.map(x => x * 2)
来源：http://dali.ppjwa.cn/Article/details/gtzslgtjwr.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jiagoushi.top/Article/details/gtsbdquopo.html

Go:   // 手写循环
来源：http://dali.ydzc1.top/Article/details/gtrayuvaif.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtojryrxfr.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtnnuyuagv.html

[D15] 去重
来源：http://dali.jqgufenzy.top/Article/details/gtkpowdfnr.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.smart0.xyz/Article/details/gtzdbvpclg.html

PHP:  array_unique($arr);
来源：http://dali.nwbrower.top/Article/details/gtnlvdqaez.html

JS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtayxzddgi.html

TS:   [...new Set(arr)]
来源：http://dali.jlsjyb.cn/Article/details/gtxqvaqrha.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtbiwvznnh.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.hywenlv.cn/Article/details/gtrwmhxtyi.html

Ruby: arr.uniq
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjeqykxg.html

C#:   list.Distinct().ToList()
来源：http://dali.yongpay.top/Article/details/gtaqquiglo.html

[D16] 求和与平均值
来源：http://dali.yj20258888.top/Article/details/gtyuggdtlm.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.guowangkeji.top/Article/details/gtpzfjtwyd.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gtdccqnhzb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sysykeji.top/Article/details/gtdodclqqb.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gttidncvvm.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jyoumei.cn/Article/details/gtgajpgmju.html

Go:   // 手写循环累加
来源：http://dali.gotoacloud.top/Article/details/gtseifkrib.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.iojbl.cn/Article/details/gtbpgzecen.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtnxftfilm.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gtbsrehvly.html

Py:   max(arr);  min(arr)
来源：http://dali.zdqjudy.top/Article/details/gtxiwgselw.html

PHP:  max($arr);  min($arr);
来源：http://dali.sysykeji.top/Article/details/gtfkmtxcoj.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gtkousntqo.html

TS:   Math.max(...arr);
来源：http://dali.zycfv.cn/Article/details/gthakimgat.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hammf.cn/Article/details/gtdjhtynht.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yuanzhike.top/Article/details/gtaufuxsdn.html

Ruby: arr.max;  arr.min
来源：http://dali.yvedp.cn/Article/details/gtbonjegpd.html

C#:   list.Max();  list.Min()
来源：http://dali.yueranfly.top/Article/details/gtveykqeut.html

[D18] 扁平化嵌套数组
来源：http://dali.jiagoushi.top/Article/details/gtzslsctmw.html


<!-- 参考信息 -->