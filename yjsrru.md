代发 wailian999

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtvuoajzzp.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtratwehio.html

JS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtuyrpyaqa.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtsnvpcijo.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtubcnfetl.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtgtvhpnhi.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtijzvpemu.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtoirmtheq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttxvgczud.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtkljhnhwz.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnjoaqran.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gtwmozjzke.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gtwanjnvln.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtbemqgdet.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtayrrjbfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gthxsmecdp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtkebhgcpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdlwrlpb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtawpqcule.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtzopohtbi.html

[C02] 默认参数
来源：http://dali.yonumen.top/Article/details/gtjqolsikr.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtlerccqfv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtrtonrsaw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtmcgxpxqg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gttabyuijf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtxedxjotc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtzfrhhweq.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtnbejqkbs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gtlqbdoqbm.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtqibmjasc.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtjnqalodz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ivvv.top/Article/details/gtycfdcspf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtqqjnhpyk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtvjymjyjd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shzxlz.cn/Article/details/gtdfbjypko.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtmvuqweyc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yueranfly.top/Article/details/gtdvxnbiia.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258888.top/Article/details/gtbrjwezoo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtgcyrwujw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtdwafdgfo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtftvcgbqd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtfejwqmku.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtlgffwifo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gotoacloud.top/Article/details/gtswtabbjl.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtoonkphln.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsesuvefv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gthgiffnzm.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtynjgeuay.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtfpmnkfiu.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gthbulzwjk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cheryme.top/Article/details/gtfyjzbrex.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtovpzjvhh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.0kj1m.cn/Article/details/gtcckorrkm.html

Go:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtfajkffml.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooevwnvi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yvedp.cn/Article/details/gtgqtxjbxj.html

[C06] 匿名函数 / lambda
来源：http://dali.haohaochexian.top/Article/details/gtqebgafbb.html

Py:   square = lambda x: x * x
来源：http://dali.yuanzhike.top/Article/details/gthuskcalz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtutgoxiaj.html

JS:   const square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtsvrunpeg.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtemrgripj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtivnyuzfe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtvxsvtgvi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gttzkclozk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtytjjyfzv.html

[C07] 把函数作为参数传入
来源：http://dali.zhengqikj.top/Article/details/gtknfrdxqq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gtfzvlrpol.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtvdbbtxgs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gttulmltun.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gtyscuddek.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtrjyzfylv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.svipenyu.cn/Article/details/gtsntempsb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xinyue.icu/Article/details/gtvujgbxbv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnqkrsed.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gtghjotjro.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuetiantiany.cn/Article/details/gtpwopwbcr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gthjuhzcei.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gthjaanuyc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtyyxylpil.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gtsttwgoog.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aibaodan.cn/Article/details/gtmvrutwlc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtxtsjxvci.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gtrcpokkfp.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gtrfdrgabb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtpxjxslgk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzwnxsec.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtqngqqinc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtthsbngpl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtttgxhnvi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxinkj.top/Article/details/gtbaeiwnlx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gtxmpbnvdf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbzknthv.html

[C10] 变量作用域
来源：http://dali.aibaodan.cn/Article/details/gtjqyiicez.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtscohjzjn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.bjfxy.top/Article/details/gtfpdmjhju.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gtiuknrxna.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtgjilrjag.html

Java: 方法内为块级作用域
来源：http://dali.fengsongda.top/Article/details/gtegzsnich.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gtyomssump.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtcwhnplpr.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtevcjnajf.html

[C11] 模块导入与导出
来源：http://dali.chenjidiqi.icu/Article/details/gtadsyqjho.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gtjsyhysre.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gtvuzzoabo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtbykrdkjf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtbiccvlmi.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtdtnmbvnm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yangfankeji.com/Article/details/gttaerifpt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gtksnywake.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gtmxkehkrp.html

[C12] 立即执行函数 IIFE
来源：http://dali.gogol.net.cn/Article/details/gtlgvkhvhz.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjhywehp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtehwybiwv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhongyouzk.top/Article/details/gtywgpbjas.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtevnidhae.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtwibqkehv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gtoysnuvcw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrylvfec.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtfpshiatg.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenjidiqi.icu/Article/details/gtbmpgbphm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtembcbvqc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtsqyluouv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmulbfcnk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gtgbaniecy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtwlwrmpga.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtucfubski.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtusyejwdx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gtjzwckoek.html

[C14] 泛型函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkdopuzyf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtgplqacqw.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtrqfygesm.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtczukeczg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmgxjerpp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gtrlxjctud.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgknciqsu.html

Ruby: # 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtjxfcpcsu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gtgjyvckck.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gtpfejaltu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtqlzrichp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrodnlod.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtgwnhzafn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtvoelgyrn.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtfrioxbnx.html

Go:   // 无解构
来源：http://dali.kuanghao11.cn/Article/details/gtbkzjmybn.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtphqjfuxz.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtupzlwbki.html

[C16] 函数 / 方法重载
来源：http://dali.c1oappe.top/Article/details/gtkbcnfgua.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtutbliroq.html

PHP:  // 无重载
来源：http://dali.hfpthk.cn/Article/details/gthdpjyaum.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtvufyxwxa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gthyxivdap.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gthptnmqpl.html

Go:   // 无重载：用不同函数名
来源：http://dali.xylfe.cn/Article/details/gtoefauoxc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gtenzdqetb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cqqwz.cn/Article/details/gtbzsesboq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtgubjyics.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gttzucdbru.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtbtczcitn.html

[D01] 创建数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtryqdywvx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinqigufen.top/Article/details/gtatnrsggu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gttiogcsxy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtsblfungw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gtrpkcxzdj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.snrcjt.cn/Article/details/gtjyahmlco.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtajpvmtxq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cucudq.cn/Article/details/gtxspbavdn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtsjdubwuc.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtdbtmdjaf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nwbrower.top/Article/details/gtktnthban.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtwckzqplb.html

JS:   arr.push(4);
来源：http://dali.mhx1999.top/Article/details/gtewvdigvz.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtnudprnll.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvaignlj.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtcrhdfyrp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhoulong.xyz/Article/details/gtzckxyely.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtsksdowsj.html

[D03] 在指定位置插入元素
来源：http://dali.pengpengdd.cyou/Article/details/gtwlewgspx.html

Py:   arr.insert(0, 0)
来源：http://dali.daxiang520.top/Article/details/gtefxckxez.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtrildjkqz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.aibaodan.cn/Article/details/gtvrcqqwdn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuanzx.com/Article/details/gtkjlpuniu.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtrxzmoftr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtbdialcxr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtbiojlzqd.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtynboaebw.html

[D04] 删除元素
来源：http://dali.tian-w.cn/Article/details/gtvbtsxlxq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangdashe.top/Article/details/gtlpmfhtwl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guannengcc.top/Article/details/gtaxdzvbuu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.andypj.xyz/Article/details/gtcxnyrpfi.html

TS:   arr.splice(0, 1);
来源：http://dali.cashguo.top/Article/details/gtpqllvlca.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtrrcquwid.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sysykeji.top/Article/details/gtmvcegpng.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxijbzpsa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gteghojxsg.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gtjssdkdts.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtlqapqquu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gttjjgjplv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtgkeykmlt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtgqwmlhmg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtkerdniky.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtrstkqfvv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtuhjdsrrb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtujmwyquz.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtkujsmjdf.html

Py:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnajwjzf.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtaykcwxhm.html

JS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gtelfbuarf.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtwnowwcbv.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtrgfpsvsr.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtejubinbq.html

Ruby: arr.length; arr.size
来源：http://dali.316326.xyz/Article/details/gtmqodffcj.html

C#:   list.Count;
来源：http://dali.hammf.cn/Article/details/gtbvqvgvuv.html

[D07] 切片 / 取子数组
来源：http://dali.316326.xyz/Article/details/gtbcuopwow.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ivvv.top/Article/details/gtblazzofe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtliwrczat.html

JS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtxzqdyfac.html

TS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtflyvhujb.html

Java: list.subList(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gttohuritg.html

Go:   arr[1:4]
来源：http://dali.aizwys.cn/Article/details/gtigywhmjl.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtrefbjdho.html

C#:   list.GetRange(1, 3);
来源：http://dali.jianghu66.top/Article/details/gtaimcorpt.html

[D08] 合并两个数组
来源：http://dali.quarkkingdee.top/Article/details/gtcgyxgxdv.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gthtemtmli.html

PHP:  array_merge($a, $b);
来源：http://dali.guowangkeji.top/Article/details/gtycbbaknu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.snrcjt.cn/Article/details/gtziwjpjbv.html

TS:   [...a, ...b];
来源：http://dali.nanxuanxn.top/Article/details/gtqusdrdqc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdggqboaj.html

Go:   append(a, b...)
来源：http://dali.jyoumei.cn/Article/details/gtiiibtaic.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ehwqpu.com/Article/details/gtfsnyxozs.html

C#:   a.Concat(b).ToList()
来源：http://dali.havefunace.top/Article/details/gtkyxalurc.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gtdhuthjtt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.c1oappe.top/Article/details/gtcmbxnqti.html

PHP:  sort($arr);
来源：http://dali.zhengqikj.top/Article/details/gtarwweuga.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.guannengcc.top/Article/details/gtywjnxhyf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gtqyvuqqzw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hammf.cn/Article/details/gteyokevzf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.quarkkingdee.top/Article/details/gtpbujvkcv.html

Ruby: arr.sort
来源：http://dali.chenlongwang.top/Article/details/gtqpqmpgfw.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gtqiuwcpld.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigfzy.top/Article/details/gtlunplmio.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yuxming.cn/Article/details/gtpvdobgri.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gtwafbhkuj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cqqwz.cn/Article/details/gtiwnnbrcv.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjusmuafy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgaslkqj.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhiwuduotai.top/Article/details/gtmumejkux.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnahmmtf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.gaohongyu789.top/Article/details/gtwhcovzkr.html

[D11] 反转数组
来源：http://dali.jianghu66.top/Article/details/gtnrhhixaz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhongyouzk.top/Article/details/gttdeybrfq.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtyxoghbpu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.nanxinkj.top/Article/details/gtmixyuspz.html

TS:   [...arr].reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkupnvyut.html

Java: Collections.reverse(list);
来源：http://dali.zhiwuduotai.top/Article/details/gtxspzgacu.html

Go:   slices.Reverse(arr)
来源：http://dali.cashguo.top/Article/details/gteihflrap.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gttlvlpugz.html

C#:   list.Reverse();
来源：http://dali.quarkkingdee.top/Article/details/gtwinphmrk.html

[D12] 查找元素下标
来源：http://dali.smart0.xyz/Article/details/gttqvzwyvm.html

Py:   arr.index(x);  x in arr
来源：http://dali.tanke756.top/Article/details/gtffebfjdo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtishlalxa.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shuidangran.top/Article/details/gtmhbcsrfa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jqgfzy.top/Article/details/gtbecidutc.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.nanxuanxn.top/Article/details/gtavbsibru.html

Go:   slices.Index(arr, x)
来源：http://dali.yuanzhike.top/Article/details/gtszdqfhrq.html

Ruby: arr.index(x)
来源：http://dali.jianghu66.top/Article/details/gtpeizmjew.html

C#:   list.IndexOf(x);
来源：http://dali.xinyue.icu/Article/details/gtgoepgubd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtselflsyv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hysaishi.cn/Article/details/gtribynfbd.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gtsjfbzizh.html

JS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gthgdqmtsj.html

TS:   arr.filter(x => x > 3)
来源：http://dali.0kj1m.cn/Article/details/gtmocrtlqh.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.chenzaomai.com/Article/details/gtczaiwkjy.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.sxryk.cn/Article/details/gtrmuvdhal.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.fengsongda.top/Article/details/gtmyaqetrl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtdktbmquy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.gotoacloud.top/Article/details/gtnvddhvnk.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.birdmap.top/Article/details/gttjlccchb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.shzxlz.cn/Article/details/gthbjmkvtr.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gtfdngepbq.html

TS:   arr.map(x => x * 2)
来源：http://dali.xylfe.cn/Article/details/gtugamckbp.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ivvv.top/Article/details/gtkpmdvnly.html

Go:   // 手写循环
来源：http://dali.quarkkingdee.top/Article/details/gtknmuxxpv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtxhynqccp.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.tianlin.xyz/Article/details/gthfvmnwrj.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gttkfwnvtt.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtycryhuxc.html

PHP:  array_unique($arr);
来源：http://dali.xuanzx.com/Article/details/gtwvkfbvxg.html

JS:   [...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdcjwiyz.html

TS:   [...new Set(arr)]
来源：http://dali.jinqigufen.top/Article/details/gtpgpvvynl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cqqwz.cn/Article/details/gtmvrwdjqg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yj202588.top/Article/details/gtfiptiwzx.html

Ruby: arr.uniq
来源：http://dali.aibaodan.cn/Article/details/gtwdidbsjg.html

C#:   list.Distinct().ToList()
来源：http://dali.vqdsnc.cn/Article/details/gtnhicsxvr.html

[D16] 求和与平均值
来源：http://dali.sufxvd.cn/Article/details/gtjnkzljuk.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtfhpfdqri.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ppjwa.cn/Article/details/gttvxvdpsy.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hammf.cn/Article/details/gtqvdplqrx.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gtlajrdkeq.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.birdmap.top/Article/details/gteqjwooam.html

Go:   // 手写循环累加
来源：http://dali.gaohongyu789.top/Article/details/gtfwdvyepu.html


<!-- 参考信息 -->