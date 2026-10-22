代发 wailian999

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtyacagvoq.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtfliwfevj.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtzjvdautl.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gtnnqxfmia.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtcaeejgoe.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtkdislceu.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthymzlxup.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtrtczbycf.html

Py:   def add(a, b): return a + b
来源：http://dali.mhx1999.top/Article/details/gtauyypkxa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtbxzkkkgj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtyhmfnlou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtxdwechwf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtcrqyqlry.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtifkytzqz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gtxdntsukd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcghfjqhu.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiovevkws.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gtxixdjcxe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdxyfxp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.daxiang520.top/Article/details/gthdnnwmmn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gthuyzkdrs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtrtgikvli.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjygtyxga.html

Ruby: def greet(name = "World") = name
来源：http://dali.xziqi.cn/Article/details/gtxkfbmkxo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjupcgttj.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gtmddlmizx.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtvthwqvdw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtkbyovese.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtozvibyoo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtgdxsvelb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.haohaochexian.top/Article/details/gtbhxtrhlg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtupbtefaf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtuefvgpbj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtdnawicza.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxsclzgz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.redwolf501.top/Article/details/gtpqjgvhba.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtxvaoxhgo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtodtlposz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtenkhyouz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yanxiufei.cn/Article/details/gtffhjgkrr.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtgwdintly.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtwskiduof.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtgjjubokm.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtifsbtcul.html

Py:   return a, b
来源：http://dali.birdmap.top/Article/details/gtthhhkxfa.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtyzbnwrrx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtrkgemxmj.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gttlvwuobh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xylfe.cn/Article/details/gtktxkrfpy.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtcsbmnsis.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gttwhnocys.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtiotoaaue.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigufen.top/Article/details/gtiluuuiqq.html

Py:   square = lambda x: x * x
来源：http://dali.dashuyun.cn/Article/details/gtkdbeunys.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtwyxaqncd.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtlljbpdnr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gtqnijgrnr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejeoqiul.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtjklxcgba.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gtpvotbijd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtqusalagr.html

[C07] 把函数作为参数传入
来源：http://dali.dashuyun.cn/Article/details/gtnrcsgacb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aibaodan.cn/Article/details/gtiiiaglci.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtctrybyjv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtpoqgpqyr.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gtqhnwbxhb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtvcumufue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtmluwrfce.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvgluopj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtpfnedvrf.html

[C08] 闭包
来源：http://dali.guowangkeji.top/Article/details/gtklvmfsqp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzdbouut.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtezklurwd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtnoxvlejz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtlvriwcan.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtncienhus.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtejkuptfr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqrajjmd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtooobszqg.html

[C09] 递归
来源：http://dali.wangshuangyany.cn/Article/details/gtsygrkyex.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtwjozvgix.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtwaztfysl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtqzshpese.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gtzhouuhyw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gaohongyu789.top/Article/details/gtfykikdcy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtyqsrpdse.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtoyraofzw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtjiupucxh.html

[C10] 变量作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtkswhlshq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gtlbjxmtuk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xuetiantiany.cn/Article/details/gtbjosfnsa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtalufqyhw.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtrfigptgd.html

Java: 方法内为块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtherfuejm.html

Go:   花括号块级作用域
来源：http://dali.redwolf501.top/Article/details/gtffvclgeo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.mhx1999.top/Article/details/gtxxziruel.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtmnmwblgz.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gthjglwmwq.html

Py:   from module import func
来源：http://dali.zdqjudy.top/Article/details/gthqqzdhfs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtyvnjewkc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtrzhrbiiq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtaictdzkl.html

Java: import java.util.List;
来源：http://dali.yongpay.top/Article/details/gtyucmlwqw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gtspavrkoh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.iojbl.cn/Article/details/gtpeidikns.html

C#:   using System.Text;
来源：http://dali.sysykeji.top/Article/details/gtdxgwmyja.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtuywodzge.html

Py:   (lambda: print("run"))()
来源：http://dali.snrcjt.cn/Article/details/gtybpfdrjc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtbbywztgy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gttusvfvff.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhiwuduotai.top/Article/details/gttpfdxgkr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtnlchtsaw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guannengcc.top/Article/details/gtddxupvha.html

Ruby: -> { puts "run" }.call
来源：http://dali.yangfankeji.com/Article/details/gtrcmzbuxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gthutnmbci.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtefgiwqvz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtvuixwexj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtidfxlimd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtkxskqkyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtrxorsxbx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtbdwwldmp.html

Go:   func add(a, b int) int
来源：http://dali.0kj1m.cn/Article/details/gtfjbysykt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtjivrumnq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtrgwnizqq.html

[C14] 泛型函数
来源：http://dali.gaohongyu789.top/Article/details/gttbqdymka.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tanke756.top/Article/details/gttptowibo.html

PHP:  // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtqttwyxhc.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtsfkulnso.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cashguo.top/Article/details/gtntrukqhr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtlmjnjtdf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtmrrlaplj.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gtmxvmzxur.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigfzy.top/Article/details/gtmskmphdj.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgexwpgcb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtnkbwyhjd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtwfqdgryf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtfulphxgf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cqqwz.cn/Article/details/gtkklznfsx.html

Java: // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gteoqmfmmr.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gtgandrkod.html

Ruby: a, b = pair
来源：http://dali.nanxuanxn.top/Article/details/gtvowswkgj.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtekgsuqix.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtnguffpnj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cucudq.cn/Article/details/gtiykzvgre.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtnntdgubu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcqngotw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gtukkorqrt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiydypxk.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtgsrmkjrl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtedhtuwfq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gtlizajmfo.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtyxxgaoyx.html

D. 数组 / 列表 / 集合
来源：http://dali.hammf.cn/Article/details/gtphlqlfom.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtnmzbazzk.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtguwvqsch.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gtwiikotvl.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtgrvyufko.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtmzqplzoh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtdiejalki.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.sysykeji.top/Article/details/gtwizgqstt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhijiandao.cn/Article/details/gtuwaltckl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.bjfxy.top/Article/details/gtxwlkjmga.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnqzz.top/Article/details/gtkwoaezkt.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gtagipwkvl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgfzy.top/Article/details/gtrqjrydgi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtshsozoqo.html

JS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtgpeqhagn.html

TS:   arr.push(4);
来源：http://dali.xuanzx.com/Article/details/gtwgxhqjwx.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gterdzfnmu.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigufen.top/Article/details/gtyktymexh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gthxokzfxw.html

C#:   list.Add(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthrutktjk.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtbboezyxa.html

Py:   arr.insert(0, 0)
来源：http://dali.aibaodan.cn/Article/details/gtkrmncvxd.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gtxswjnbpn.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cheryme.top/Article/details/gtpuwzbypv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtysehqbfs.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtlrvwurrh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.dashuyun.cn/Article/details/gtzebbompy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhijiandao.cn/Article/details/gtusqeyoji.html

C#:   list.Insert(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtgjtbrmxr.html

[D04] 删除元素
来源：http://dali.yj20258888.top/Article/details/gtbrepfnzy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtfbirzxzg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gtwxxcpbio.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cucudq.cn/Article/details/gtodcdyfjd.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtwhcmjjte.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtfhwlpjpc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenlongwang.top/Article/details/gtbpohhaoa.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtcstcvtge.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmlqqixy.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwljaoxkw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hammf.cn/Article/details/gtzypwqcog.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtnopazpzm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtjjgumedj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrymqbend.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gtdvoeatxi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqzheugr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtpsoinfnf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhongyouzk.top/Article/details/gtrnjgyfbi.html

[D06] 数组长度
来源：http://dali.316326.xyz/Article/details/gtvezjydvz.html

Py:   len(arr)
来源：http://dali.smart0.xyz/Article/details/gtklqgzukn.html

PHP:  count($arr);
来源：http://dali.cucudq.cn/Article/details/gtxjaadfkp.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gtiojdgjnm.html

TS:   arr.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtcozhnsuy.html

Java: list.size();
来源：http://dali.iojbl.cn/Article/details/gtufqncphm.html

Go:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtzmsfnoky.html

Ruby: arr.length; arr.size
来源：http://dali.cdnleiting.top/Article/details/gtsaqdnnbv.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtedznkdkl.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtocjetmkp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtfwhbditu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtmlckfyio.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtqlthbuad.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtkfjogvlr.html

Java: list.subList(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpalwngz.html

Go:   arr[1:4]
来源：http://dali.shangyingyoupin.top/Article/details/gtmuhwqzfj.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtjzysqxlo.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtfuixubty.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtlaxgqsnn.html

Py:   a + b;  a.extend(b)
来源：http://dali.316326.xyz/Article/details/gtlcoxyvoa.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gtpaecutxs.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sweek.top/Article/details/gtkkcfwwkx.html

TS:   [...a, ...b];
来源：http://dali.c1oappe.top/Article/details/gtfudoktdo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhoulong.xyz/Article/details/gtucpqlsmy.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtlehfwbhe.html

Ruby: a + b;  a.concat(b)
来源：http://dali.9152youxi.cn/Article/details/gtzuavkakc.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gttmxforbf.html

[D09] 排序（升序）
来源：http://dali.cqqwz.cn/Article/details/gtukxbmzaa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aizwys.cn/Article/details/gtcfbchdxi.html

PHP:  sort($arr);
来源：http://dali.havefunace.top/Article/details/gtrdtqzytt.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daria6918.cn/Article/details/gtxvagqiyg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyempxee.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.birdmap.top/Article/details/gtumbhrdzl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtacafsngk.html

Ruby: arr.sort
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthuhbetxb.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gtuhhbjctn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhengqikj.top/Article/details/gtlnqfratm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtkakrvnyn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nanxuanxn.top/Article/details/gtckjfkypj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.vqdsnc.cn/Article/details/gtogtczfwg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gtmfqkrbwp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jiagoushi.top/Article/details/gtvtukmxwn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.dashuyun.cn/Article/details/gtdtdmqghg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.andypj.xyz/Article/details/gtdbdyktbu.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.wangdashe.top/Article/details/gtydakrmbr.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtnqibolqg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.svipenyu.cn/Article/details/gtaperwpgu.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtysojxrau.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.vqdsnc.cn/Article/details/gtuytuqpdm.html

TS:   [...arr].reverse();
来源：http://dali.shangyingyoupin.top/Article/details/gtofeitosc.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtpjqqlxef.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmksorcs.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gtijpoaqbh.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtrsqzsnwx.html

[D12] 查找元素下标
来源：http://dali.yuxming.cn/Article/details/gtegjudmiq.html

Py:   arr.index(x);  x in arr
来源：http://dali.cheryme.top/Article/details/gtqmyerbzo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yj20258.top/Article/details/gtbkndcbua.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.9152youxi.cn/Article/details/gtzpeftihf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.tian-w.cn/Article/details/gttnsimnhr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtytvkjxiu.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gtsjzsrwnb.html

Ruby: arr.index(x)
来源：http://dali.sxryk.cn/Article/details/gtmbyjueth.html

C#:   list.IndexOf(x);
来源：http://dali.ehwqpu.com/Article/details/gtcznrnmfb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtowwwxwgm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.snrcjt.cn/Article/details/gtspkxgofw.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.sxryk.cn/Article/details/gtbczigohf.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hywenlv.cn/Article/details/gtkcxcfgrt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.tianlin.xyz/Article/details/gtyclvqlrq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.aibaodan.cn/Article/details/gtziscjxhc.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhoulong.xyz/Article/details/gtqxanuazo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.havefunace.top/Article/details/gtuiwjoxgq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtlwpzxytq.html

[D14] 映射转换（每个元素变形）
来源：http://dali.chenjidiqi.icu/Article/details/gtssvartbf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xuetiantiany.cn/Article/details/gtydjsnogk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jlsjyb.cn/Article/details/gtakftrxbz.html

JS:   arr.map(x => x * 2)
来源：http://dali.haohaochexian.top/Article/details/gtvceaeurm.html

TS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtsfpvgbyi.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakerdbqp.html

Go:   // 手写循环
来源：http://dali.nwbrower.top/Article/details/gtgnpudcfd.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtnxarohfz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtklexsofi.html

[D15] 去重
来源：http://dali.zycfv.cn/Article/details/gtscuevsdy.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zdqjudy.top/Article/details/gttblgspuv.html

PHP:  array_unique($arr);
来源：http://dali.cashguo.top/Article/details/gtbmxwzxlx.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtueavcsyo.html

TS:   [...new Set(arr)]
来源：http://dali.sxryk.cn/Article/details/gtweqgtsjm.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.daria6918.cn/Article/details/gtynihrevu.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinqigufen.top/Article/details/gtjkzfomqm.html

Ruby: arr.uniq
来源：http://dali.hfpthk.cn/Article/details/gtvqjjgjjn.html

C#:   list.Distinct().ToList()
来源：http://dali.nanxinkj.top/Article/details/gtmwdultvb.html

[D16] 求和与平均值
来源：http://dali.jianghu66.top/Article/details/gttdxazqdg.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.tanke756.top/Article/details/gtxgetoyxr.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gogol.net.cn/Article/details/gtxcwajwcc.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtajfetjpj.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.svipenyu.cn/Article/details/gtszpiafos.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.sufxvd.cn/Article/details/gtgmfnhkjr.html

Go:   // 手写循环累加
来源：http://dali.sysykeji.top/Article/details/gteezclpel.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.cucudq.cn/Article/details/gtwrjxyjvb.html

C#:   list.Sum();  list.Average()
来源：http://dali.sxryk.cn/Article/details/gtuwhjwqfn.html

[D17] 最大值与最小值
来源：http://dali.zhijiandao.cn/Article/details/gtonxikzrn.html

Py:   max(arr);  min(arr)
来源：http://dali.andypj.xyz/Article/details/gthcxpeslp.html


<!-- 参考信息 -->