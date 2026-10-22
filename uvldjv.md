代发 wailian999

================================================================================
来源：http://dali.tanke756.top/Article/details/gtixtlvitz.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gtkasfoldr.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtzmghnmhy.html

[C01] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxtaflhvd.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtjxdeilay.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtnxxmwzgp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsnnpqdps.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtthlqdujt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtwjoiwugc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtyrgjkedm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtdsbcjljr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtoqmqanbe.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtlzmgglis.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtbfuoxphg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gtfdilbtgn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtznyxjkal.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtbnjqvgpg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fengsongda.top/Article/details/gtxbfnaryg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ydzc1.top/Article/details/gtlranvhgk.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gtssrzhlbl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtqbehsgmp.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtlphckhgq.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gteipyrhiq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtrdevklyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpblemvls.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtnmarvyag.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gtrvhlibzk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gtwyxmxrbm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtpthgrmcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuanzx.com/Article/details/gtzowcolbc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtnsevqjeq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.fzhhl.top/Article/details/gttkxqsaok.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtltodflet.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gteounajtc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtjbldbork.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtzuwpqyea.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtolgvgebg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtfskdkkon.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtglwksiqz.html

[C05] 返回多个值
来源：http://dali.hammf.cn/Article/details/gtvdodzfjk.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtjcopldns.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtahljzkbw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtkqchoqjt.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtbtpvxnde.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtsslmvolk.html

Go:   return a, b
来源：http://dali.daria6918.cn/Article/details/gtslxbwxvo.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtfduneebt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenjidiqi.icu/Article/details/gtpuqmxkic.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtezlqzuyb.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigfzy.top/Article/details/gttamkxnyi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigfzy.top/Article/details/gtreypuflz.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzlujjux.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gtcnmjhvvd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtunabdwfo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtbahcbxmk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuxming.cn/Article/details/gtyfxristx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.c1oappe.top/Article/details/gtxnsqhrpj.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtozchvivp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtdugwhfsh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtqyzybecm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gtwtjquban.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtzrztxoow.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gtoetayudk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.havefunace.top/Article/details/gtqqdikuip.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhixingplan.top/Article/details/gtyjfljwgo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pengpengdd.cyou/Article/details/gtnywfypfr.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtavfdkqio.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtjrtplmsl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtuxjugdup.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtbvwpoxjz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gttyvrzwml.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtvduwpjqi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gtzsjkyyaz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cashguo.top/Article/details/gtmqjrmihn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtkhzefgqn.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtjdakjefl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtykihfzuh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gtldzrhqaj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtrnezdumc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtkpwohzrs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtznbqzysu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shuidangran.top/Article/details/gtqzqoroub.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtitwbewbe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtcbuwsrfo.html

[C10] 变量作用域
来源：http://dali.havefunace.top/Article/details/gtyokfgctc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtqczqfshv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtkjeuscxx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gtvethqfmg.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtnixgwzgt.html

Java: 方法内为块级作用域
来源：http://dali.xziqi.cn/Article/details/gtfhipcart.html

Go:   花括号块级作用域
来源：http://dali.nwbrower.top/Article/details/gtxtksehek.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtcargzrwa.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gtkdsiqbwr.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtgxoouyzd.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtleqjlkzr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtlkgirtuv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtgfvilzlr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtlunvolrm.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtsrpulvkr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtbpsprrbc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ybcxt.top/Article/details/gtwjxmytmb.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtueqdxbqg.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtsqpwpytl.html

Py:   (lambda: print("run"))()
来源：http://dali.cashguo.top/Article/details/gtjyorswui.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hongshengwenyu.top/Article/details/gtkagiebab.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nwbrower.top/Article/details/gtpxbgxjkx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtmqjemvnw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cqqwz.cn/Article/details/gtxmqvemks.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gthgrjfjfz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtmvcworlo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.iojbl.cn/Article/details/gtvdemprkp.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtssqexohd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtadqufkrw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtekqeuykd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gthtphrmky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayviygtp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtotlrbmoh.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtnnwcimxs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtvdjnqbbl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gtiuwsjigr.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtilicfsbj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgafhvfpu.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtslebvybf.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtnoriscvu.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gtcddevjdk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtvgbgjvve.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtatthnomi.html

Ruby: # 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtpiiofnjm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtmzshlxrp.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtdpxbxfhs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gtyrbudyir.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtwvywmgte.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtuuudndqn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtwyabovya.html

Java: // 无解构
来源：http://dali.cucudq.cn/Article/details/gtiozqdjvm.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gtptcljxpr.html

Ruby: a, b = pair
来源：http://dali.sweek.top/Article/details/gtvbqflano.html

C#:   var (a, b) = pair;
来源：http://dali.yongpay.top/Article/details/gtjnahinaf.html

[C16] 函数 / 方法重载
来源：http://dali.bjfxy.top/Article/details/gtyxhioxak.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gtifcqyhft.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtttjmauoa.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtherinruc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtgjfkmzei.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtwcporcoa.html

Go:   // 无重载：用不同函数名
来源：http://dali.havefunace.top/Article/details/gtjesgtyxk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.mhx1999.top/Article/details/gtwlrasxfn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtiyozpozi.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtinfwvdea.html

D. 数组 / 列表 / 集合
来源：http://dali.ppjwa.cn/Article/details/gtezudcvny.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gterumegwv.html

[D01] 创建数组 / 列表
来源：http://dali.hywenlv.cn/Article/details/gtznzdvyrp.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hongshengwenyu.top/Article/details/gtmhtjrqwy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtftixjrma.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtzjtvjpzr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gthczgbljp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtobazbate.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yueranfly.top/Article/details/gtjtpasnse.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtmtjnpaui.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yvedp.cn/Article/details/gtuudlhqjk.html

[D02] 追加元素到末尾
来源：http://dali.xuanzx.com/Article/details/gtvbgsjmnv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gttnamoxyv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gthgzbwqec.html

JS:   arr.push(4);
来源：http://dali.cashguo.top/Article/details/gtwngpplfh.html

TS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtofhzdskn.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gtnyzieoca.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gtwwydgenm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gtpplwygwg.html

C#:   list.Add(4);
来源：http://dali.gogol.net.cn/Article/details/gtyowvkssu.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtchknmdel.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtaqlxtcgk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gogol.net.cn/Article/details/gtfeumprwc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtbdxccnkm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtzeaxouzg.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtnwyifovb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtcxxqeiyb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jianghu66.top/Article/details/gtbekogwvr.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtquqnvsby.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtbycfniui.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtdfkpzqci.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yj20258.top/Article/details/gthybtvtuc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gtdnaeugtg.html

TS:   arr.splice(0, 1);
来源：http://dali.daria6918.cn/Article/details/gtazqzyhct.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtgtmxtwxm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gttlhrqvtw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtrxajwhhv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.kuanghao11.cn/Article/details/gtgmtiqmwh.html

[D05] 访问与修改元素
来源：http://dali.gaohongyu789.top/Article/details/gtijzfixee.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtptttaoga.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hysaishi.cn/Article/details/gthabdrutw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dashuyun.cn/Article/details/gtizexqmkv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtqvpxgohr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtqubhpacx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtdcpcfwrn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gthqvlzmly.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gtdnkbsnaf.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtfsypehfy.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gttyvcalnn.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtjpishzts.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtgkxvpaew.html

TS:   arr.length
来源：http://dali.yj202588.top/Article/details/gtptayepwg.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtqsbsbvfj.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirnuxthh.html

Ruby: arr.length; arr.size
来源：http://dali.bjfxy.top/Article/details/gtywgeuvpt.html

C#:   list.Count;
来源：http://dali.pycfn.com/Article/details/gtouquaopz.html

[D07] 切片 / 取子数组
来源：http://dali.yangfankeji.com/Article/details/gtlvxmspjk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yuxming.cn/Article/details/gtzfliunzq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtiivjgknl.html

JS:   arr.slice(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtnzzmxenn.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtkdlqkwfe.html

Java: list.subList(1, 4);
来源：http://dali.cashguo.top/Article/details/gtwnadazba.html

Go:   arr[1:4]
来源：http://dali.cheryme.top/Article/details/gtyrlojdlg.html

Ruby: arr[1, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtzjitixce.html

C#:   list.GetRange(1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtfuxypzmw.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gtclqnajkr.html

Py:   a + b;  a.extend(b)
来源：http://dali.gogol.net.cn/Article/details/gtsgpzrpdc.html

PHP:  array_merge($a, $b);
来源：http://dali.yanxiufei.cn/Article/details/gtintstzpd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.daria6918.cn/Article/details/gtjnkanbvw.html

TS:   [...a, ...b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptmyptsi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.haohaochexian.top/Article/details/gtovnjwmgz.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtxzsqeibz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtxkrevpuq.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtqodmjien.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtaseuvphv.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yj20258.top/Article/details/gtnyqdpdfu.html

PHP:  sort($arr);
来源：http://dali.sysykeji.top/Article/details/gtgdgyoblq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fzhhl.top/Article/details/gtmayrcfcj.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtbikayrfp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gtphwzxyif.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yvedp.cn/Article/details/gtlxqhmmcy.html

Ruby: arr.sort
来源：http://dali.hammf.cn/Article/details/gtkclnsxbc.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqtoqvps.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yongpay.top/Article/details/gtuisytaaz.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sxryk.cn/Article/details/gtoorljzgf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtcfnihpjj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.redwolf501.top/Article/details/gtuvorlxdp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtcnnfekal.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.c1oappe.top/Article/details/gtpvqbypyc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yueranfly.top/Article/details/gthzlsgqte.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtsgklbqre.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.redwolf501.top/Article/details/gtbncyetcv.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtiujgrakw.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fzhhl.top/Article/details/gtykpqrune.html

PHP:  array_reverse($arr);
来源：http://dali.meibo888.top/Article/details/gtdhdfqfsl.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ybcxt.top/Article/details/gtbwekfgcj.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gtkavddzuj.html

Java: Collections.reverse(list);
来源：http://dali.zycfv.cn/Article/details/gtwjbfnqxp.html

Go:   slices.Reverse(arr)
来源：http://dali.aizwys.cn/Article/details/gttceuliaj.html

Ruby: arr.reverse
来源：http://dali.jlsjyb.cn/Article/details/gtbxrvpzpj.html

C#:   list.Reverse();
来源：http://dali.ybcxt.top/Article/details/gtjqnhjlwc.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtaxajvgky.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtfhktkmhk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gogol.net.cn/Article/details/gtzxnktmky.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.cashguo.top/Article/details/gtijbgerdd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmomuuqg.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.chenlongwang.top/Article/details/gtflpstvhe.html

Go:   slices.Index(arr, x)
来源：http://dali.shzxlz.cn/Article/details/gttfbpvdei.html

Ruby: arr.index(x)
来源：http://dali.zhongyouzk.top/Article/details/gtfgnlopbi.html

C#:   list.IndexOf(x);
来源：http://dali.cheryme.top/Article/details/gtcinoicmd.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shanyushiyangtech.top/Article/details/gtgstxnuam.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.nwbrower.top/Article/details/gtzljdjmkp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gttcmxqxqn.html

JS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtqpntyrws.html

TS:   arr.filter(x => x > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozgvvjno.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yvedp.cn/Article/details/gtmtgkcvcw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.wangshuangyany.cn/Article/details/gtgayehbuy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtmqhkcxhg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gtvgwdfhnl.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigfzy.top/Article/details/gtdjtpgoxj.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.nanxinkj.top/Article/details/gtopgkmhox.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cdnleiting.top/Article/details/gtmupzsgss.html

JS:   arr.map(x => x * 2)
来源：http://dali.birdmap.top/Article/details/gttvtclwpc.html

TS:   arr.map(x => x * 2)
来源：http://dali.dashuyun.cn/Article/details/gtuumiozkk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtgyvxpopu.html

Go:   // 手写循环
来源：http://dali.nanxuanxn.top/Article/details/gtizksltiq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpomokfyl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.daxiang520.top/Article/details/gtyswnbxpy.html

[D15] 去重
来源：http://dali.dianchejie.cn/Article/details/gtddkikvna.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtihrqjrxo.html

PHP:  array_unique($arr);
来源：http://dali.sweek.top/Article/details/gtuykpsugq.html

JS:   [...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gtknzivkrc.html

TS:   [...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtgjrgxjqv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gttibgzfst.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwjrvqbmg.html

Ruby: arr.uniq
来源：http://dali.quarkkingdee.top/Article/details/gtzxzzvxyb.html

C#:   list.Distinct().ToList()
来源：http://dali.daria6918.cn/Article/details/gtwxvfckhu.html

[D16] 求和与平均值
来源：http://dali.shanyushiyangtech.top/Article/details/gtntrqhafi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtkbapktqw.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.cucudq.cn/Article/details/gtbrupwise.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.hfpthk.cn/Article/details/gtgxlsjxxn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.aizwys.cn/Article/details/gtltgezliz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.316326.xyz/Article/details/gtbsyknmuu.html

Go:   // 手写循环累加
来源：http://dali.tanke756.top/Article/details/gtleizrdhf.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtookaefgg.html

C#:   list.Sum();  list.Average()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtneggwmjn.html

[D17] 最大值与最小值
来源：http://dali.yangfankeji.com/Article/details/gtcmgqyqyt.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtbchruvne.html

PHP:  max($arr);  min($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtmabgmxvo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.yanxiufei.cn/Article/details/gtrmnbcyya.html

TS:   Math.max(...arr);
来源：http://dali.yvedp.cn/Article/details/gtdmcquoaa.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.c1oappe.top/Article/details/gtyymtrtid.html


<!-- 参考信息 -->