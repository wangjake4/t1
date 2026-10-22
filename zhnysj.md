代发 wailian999

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtnntqpwga.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tanke756.top/Article/details/gtmvkwwutw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gtuyawoxud.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtryhdhnpq.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtmakjetqe.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gtjjfdixwg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtnzzfowoe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmgspwhck.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtlejwoytg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtutdquhmz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtkhhjnvpi.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gtrbtkpyhy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xuetiantiany.cn/Article/details/gtgofurxwk.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnrrsurj.html

Py:   def total(*args): return sum(args)
来源：http://dali.c1oappe.top/Article/details/gtqwzsajyh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jlsjyb.cn/Article/details/gthmvwhrsa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtimraffhb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtmgecpodp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtpbvmhsyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtreteauxg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gtgnnejena.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhoulong.xyz/Article/details/gtlqqzblgm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqnpvkvoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gtsxbjeglg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtqpdvhwvk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtoqycwhno.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtmrakxxgo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gttulhellp.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtnlvxwvgr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwgrteua.html

C#:   f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gtefiltyio.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gtkcowfuip.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtbcthcroi.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtdcylnxoz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tianlin.xyz/Article/details/gtromdjflv.html

TS:   return { a, b };
来源：http://dali.pycfn.com/Article/details/gtnntwyvkg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.andypj.xyz/Article/details/gtasbmmudh.html

Go:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gttgufikjl.html

Ruby: return a, b
来源：http://dali.cheryme.top/Article/details/gtincnfwms.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.iojbl.cn/Article/details/gtmljueqqr.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtxlobczpb.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtbeznyjib.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gtbnwjsmkm.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtpfrvmgds.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.smart0.xyz/Article/details/gtlvbqnjmd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtqkglxbfg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaubnkvws.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtflizvohc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gturrmsqak.html

[C07] 把函数作为参数传入
来源：http://dali.redwolf501.top/Article/details/gthcdlbnkg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtqvopvhfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xinyue.icu/Article/details/gtpjfhcbbg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtkvimhjrh.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtfveylabx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtwikagnaa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtjatrebre.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtdilbwnzv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gthxtrqhnd.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtjnmcpdmt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jyoumei.cn/Article/details/gtdfkvmoxv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gtxyhvtasd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtreswwvvc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtiotrmyau.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cqqwz.cn/Article/details/gtpureqcmx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gthehdhtff.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtxnewnfbr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtmpubhqmv.html

[C09] 递归
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrqscmht.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaudykjih.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtucsjehqs.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtsizaxyzh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtecvgqmnv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gttmdrtnwa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtvrepciqb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hammf.cn/Article/details/gtdwopvrnp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.fengsongda.top/Article/details/gtcbzzhsum.html

[C10] 变量作用域
来源：http://dali.yangfankeji.com/Article/details/gtgnthsdjr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gtkfvgnggc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtpuwtnpyt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gttukaapii.html

TS:   同 JS
来源：http://dali.hnxiangtu.top/Article/details/gtacubmlvw.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtifjcfvkg.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtzedtljem.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtalpcccls.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtdkgbwcsn.html

[C11] 模块导入与导出
来源：http://dali.xuanzx.com/Article/details/gtlqtkhllv.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gtkntkdgqf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtfwaiofyj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtducaipxp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtiscyxbft.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpcehham.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxinkj.top/Article/details/gtfllpxyvg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gtrqlupppa.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gthdruqrnn.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtrpscfksy.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtvvpagipl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shzxlz.cn/Article/details/gtuekaogxm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtojovtfkz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtjwxuikkz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nwbrower.top/Article/details/gtsthcxfvt.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtfsjkrmsj.html

Ruby: -> { puts "run" }.call
来源：http://dali.ehwqpu.com/Article/details/gtdwuoqmlr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yangfankeji.com/Article/details/gtvgtafyja.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gttaoqspgz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gthannoydz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtiwodjrzf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yangfankeji.com/Article/details/gtmxaexiul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtcvcxburm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gthqlhgugf.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtsdngrefy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtwksojamn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.0kj1m.cn/Article/details/gtmpprhmvu.html

[C14] 泛型函数
来源：http://dali.zhixingplan.top/Article/details/gtrntdpmzr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtscdgqycm.html

PHP:  // 无泛型
来源：http://dali.hammf.cn/Article/details/gtzzptnyld.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtjpqijiyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gttnvvidpt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtdlmkmgxo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shzxlz.cn/Article/details/gtwvdavinm.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtrojlfycw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cqqwz.cn/Article/details/gtkdvnbifb.html

[C15] 解构 / 展开参数
来源：http://dali.ybcxt.top/Article/details/gtiqygfnnc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtbrnonkiq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtqptsibmm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtkyqmihid.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvujxosg.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtxuuelgmh.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtpjkslgtr.html

Ruby: a, b = pair
来源：http://dali.aibaodan.cn/Article/details/gtqyrifsou.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujbpodbr.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtsddyiklk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gthfnzaiyr.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gtaxchtbtp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtmkhjkbdm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gttmxibiok.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gtbsvsyxsx.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gtoqghlnju.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtsidzzvgs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhixingplan.top/Article/details/gtzmqhnjss.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwexawlxv.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtigkpat.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtxcnaolwy.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtwgphbuwc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtmzcwycuu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gttgjbwzkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtawuryday.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtlmlgmqdm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtmevkzdpj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtzynrqwlo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtetzggncj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtevysvroe.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtcrmpukxg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtofqhsyvm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtdvsydetn.html

JS:   arr.push(4);
来源：http://dali.c1oappe.top/Article/details/gthgjvpopj.html

TS:   arr.push(4);
来源：http://dali.zhixingplan.top/Article/details/gtgjumivjx.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtkvwjsdma.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtqzpwimjr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyjlemzq.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtpxjsznbu.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gtqvuyyhme.html

Py:   arr.insert(0, 0)
来源：http://dali.chenzaomai.com/Article/details/gtnkrwoxbl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yonumen.top/Article/details/gtusabiuwm.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtgjsojixh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ydzc1.top/Article/details/gtxpowvupq.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtzrjlmxjd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtuiovtjem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtcdbzppbm.html

C#:   list.Insert(0, 0);
来源：http://dali.xuanzx.com/Article/details/gtwzrjglho.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjajcrfcz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gtbfsjyods.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtzzzwvget.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtsevqfksm.html

TS:   arr.splice(0, 1);
来源：http://dali.ehwqpu.com/Article/details/gtgoeuvuso.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtvkzrorji.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtsvjajyid.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtnmyoftva.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.wangdashe.top/Article/details/gtdkvhnsdk.html

[D05] 访问与修改元素
来源：http://dali.zhongyouzk.top/Article/details/gteyyspspy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtwbjeonar.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtgqctuoqt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtgfqbdyym.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jqgfzy.top/Article/details/gtbmenktzj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fengsongda.top/Article/details/gtvcpdqudm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtolufpfts.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahmwcnza.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtoakvbqut.html

[D06] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnokpook.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtrvyyuytl.html

PHP:  count($arr);
来源：http://dali.jianghu66.top/Article/details/gtgegnzgkq.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gtdfobcpna.html

TS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gtlyvvcmhg.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtpzrpcedf.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gttrvgjyhi.html

Ruby: arr.length; arr.size
来源：http://dali.jinqigfzy.top/Article/details/gtekxouiki.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnhdbeyz.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtxwpaemka.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.chenjidiqi.icu/Article/details/gtxlafiwtr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtyzazceta.html

JS:   arr.slice(1, 4);
来源：http://dali.jianghu66.top/Article/details/gtavzfhnxw.html

TS:   arr.slice(1, 4);
来源：http://dali.tanke756.top/Article/details/gtqxewqvqs.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtadoxiutf.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtzupzoaaz.html

Ruby: arr[1, 3]
来源：http://dali.ybcxt.top/Article/details/gtkdlrkbhs.html

C#:   list.GetRange(1, 3);
来源：http://dali.pycfn.com/Article/details/gtfzuxovym.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gttfjftnvu.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gtxwfjirum.html

PHP:  array_merge($a, $b);
来源：http://dali.c1oappe.top/Article/details/gtsmxuntoe.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhoulong.xyz/Article/details/gtmkqfmwpg.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gtnnppefse.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gtdnejkcbl.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtigzbnudw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ydzc1.top/Article/details/gtuizizbbn.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtpgrekonz.html

[D09] 排序（升序）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsukzdilz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtdkqomuav.html

PHP:  sort($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgiisath.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtofwcxeli.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.pengpengdd.cyou/Article/details/gtuobebdix.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hfpthk.cn/Article/details/gtfgfcasyp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ivvv.top/Article/details/gtvcsbbzet.html

Ruby: arr.sort
来源：http://dali.yuanzhike.top/Article/details/gtpxperqjg.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gteptvzwza.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ehwqpu.com/Article/details/gttzwvdfco.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cashguo.top/Article/details/gttcfmpghj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtyfexicwl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gttxhgqwnm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.daria6918.cn/Article/details/gtrzphirci.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.gotoacloud.top/Article/details/gtvncpdqqg.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gtjeuvxkoy.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ivvv.top/Article/details/gtodnnpbiy.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jianghu66.top/Article/details/gtdgrgnfkm.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtixfffvsa.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtuygqnold.html

PHP:  array_reverse($arr);
来源：http://dali.bjfxy.top/Article/details/gtqdqxbong.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.andypj.xyz/Article/details/gtruxptcqt.html

TS:   [...arr].reverse();
来源：http://dali.sysykeji.top/Article/details/gtpuecbxbo.html

Java: Collections.reverse(list);
来源：http://dali.kuanghao11.cn/Article/details/gttrhouybm.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtbumnkqam.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gtuzisegku.html

C#:   list.Reverse();
来源：http://dali.nwbrower.top/Article/details/gtyyudicbc.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gtptsazctc.html

Py:   arr.index(x);  x in arr
来源：http://dali.ivvv.top/Article/details/gtpfghddya.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gtqdbrrpoa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tianlin.xyz/Article/details/gtfqglbfen.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gthhalryga.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gtjazawkiw.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gtnnszarhj.html

Ruby: arr.index(x)
来源：http://dali.kuanghao11.cn/Article/details/gtrzwrbkij.html

C#:   list.IndexOf(x);
来源：http://dali.yanxiufei.cn/Article/details/gtlgledpby.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnqzz.top/Article/details/gtlsgguypu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nanxuanxn.top/Article/details/gtfxvxnpxs.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtguzrljfc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtnyraugpz.html

TS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gtxoggofcd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.guannengcc.top/Article/details/gtzhnaroeo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.hammf.cn/Article/details/gtzptqxfcv.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cashguo.top/Article/details/gtuljlisup.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sufxvd.cn/Article/details/gtmknvosqz.html

[D14] 映射转换（每个元素变形）
来源：http://dali.hfpthk.cn/Article/details/gtnmtqepdd.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.gotoacloud.top/Article/details/gtsshoqgqu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqfljenp.html

JS:   arr.map(x => x * 2)
来源：http://dali.cashguo.top/Article/details/gtdrmdgmty.html

TS:   arr.map(x => x * 2)
来源：http://dali.yueranfly.top/Article/details/gtblkksjju.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtihdygzcu.html

Go:   // 手写循环
来源：http://dali.svipenyu.cn/Article/details/gtrynsnbuo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtvumjsddj.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtaymbocba.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtciiymdcx.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.tian-w.cn/Article/details/gtbhxgjnhu.html

PHP:  array_unique($arr);
来源：http://dali.guowangkeji.top/Article/details/gtebcttplb.html

JS:   [...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtsklxfvor.html

TS:   [...new Set(arr)]
来源：http://dali.yangfankeji.com/Article/details/gtjhdtrfkq.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gtlchzelak.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ivvv.top/Article/details/gtkzvjyuix.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtjjgeah.html

C#:   list.Distinct().ToList()
来源：http://dali.sxryk.cn/Article/details/gtczpgscoh.html

[D16] 求和与平均值
来源：http://dali.sysykeji.top/Article/details/gtnzpvuiao.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.pycfn.com/Article/details/gttppcxxwn.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.bjfxy.top/Article/details/gtvtsbkkxs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.guowangkeji.top/Article/details/gtcmvmrbir.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yj202588.top/Article/details/gtabhiorfw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.nanxinkj.top/Article/details/gtpnafuigf.html

Go:   // 手写循环累加
来源：http://dali.aizwys.cn/Article/details/gtcjybuatv.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.jianghu66.top/Article/details/gtgcuelspd.html

C#:   list.Sum();  list.Average()
来源：http://dali.aizwys.cn/Article/details/gtousmqetb.html

[D17] 最大值与最小值
来源：http://dali.xuetiantiany.cn/Article/details/gtmjbtswxp.html

Py:   max(arr);  min(arr)
来源：http://dali.yj20258.top/Article/details/gtvponpgog.html

PHP:  max($arr);  min($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtfqyuyujz.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.jlsjyb.cn/Article/details/gtjlfumkmi.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtlauxymue.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.hfpthk.cn/Article/details/gteognwqlt.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.yj20258.top/Article/details/gtrxzfcjwg.html

Ruby: arr.max;  arr.min
来源：http://dali.shzxlz.cn/Article/details/gtvmcyqbvx.html

C#:   list.Max();  list.Min()
来源：http://dali.hnxiangtu.top/Article/details/gtfeiawesg.html

[D18] 扁平化嵌套数组
来源：http://dali.chenzaomai.com/Article/details/gtxavannku.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.sweek.top/Article/details/gtihqwtrha.html

PHP:  array_merge(...$nested);
来源：http://dali.zdqjudy.top/Article/details/gtxglkjvyz.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.sufxvd.cn/Article/details/gtzqeifrpn.html

TS:   nested.flat();
来源：http://dali.gaohongyu789.top/Article/details/gtgotdkqbn.html


<!-- 参考信息 -->