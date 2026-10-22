代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtbdvoqgaq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtuccjczrh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtlhdnkjmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtaxlluylz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtkkzuflsx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtagndadbz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtswikfyaf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtefezgbab.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtazvdlrtb.html

Py:   def greet(name="World"): return name
来源：http://dali.vqdsnc.cn/Article/details/gtkntxcetx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sweek.top/Article/details/gtxccxcian.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gthqinmfez.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258.top/Article/details/gtdkkdeakc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ybcxt.top/Article/details/gtrfzhabvt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtcvujogqh.html

Ruby: def greet(name = "World") = name
来源：http://dali.jiagoushi.top/Article/details/gtzpzcocvb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtqdxtkyrk.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gtyipeqyak.html

Py:   def total(*args): return sum(args)
来源：http://dali.mhx1999.top/Article/details/gtouatgxmi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hfpthk.cn/Article/details/gtzkidoitg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gthfoboozn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtokffrxum.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.svipenyu.cn/Article/details/gtgwppgqyu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtcbntvhhn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtijfgfzza.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gthizqhdud.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtymyhpwuu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtilfmtydz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtvjibeern.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gturtwhetn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtulxiaxks.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtjtaxycgu.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtuhdabsus.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtwyoxycot.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtjuillclj.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtvnaharax.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtzkjpvgqr.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtwesewtki.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gtlpaxktfi.html

TS:   return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtbszqlfpr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtkxqltcay.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtvqoyzraz.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gturvvnhjw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.9152youxi.cn/Article/details/gtykdiniae.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtdhmoltoz.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtpmorvbme.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gtghunigil.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gttyivtuth.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtxiehdkhu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtririkqnc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtzbuferqs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtucmpztnf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtvfbcclop.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtkhxsqmlc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtcuxcwluj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtfaqeioad.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gtrfqszuhz.html

TS:   arr.map(String)
来源：http://dali.chenjidiqi.icu/Article/details/gtwkvduydo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cheryme.top/Article/details/gtcnxpqwsj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gthfhuwmih.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gttsuexssb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtbiwyqjqk.html

[C08] 闭包
来源：http://dali.yj20258.top/Article/details/gtbaskvqyl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gtmqpioeaq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yonumen.top/Article/details/gtjcvvbywy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtmomyreeq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtpfelevjq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.aizwys.cn/Article/details/gtlqvajhdt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtwakpeerh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.9152youxi.cn/Article/details/gtipryjzvr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtzwzeziab.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtlwwhatuo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gthttvledc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtpxbktvkd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gtfguhafkq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gtcptmbjln.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.iojbl.cn/Article/details/gtawmqmgco.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhijiandao.cn/Article/details/gtllfgzhvi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtldmwvddu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtszbwmhiw.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtlskurydr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nanxinkj.top/Article/details/gtawngkzef.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtneslieaa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.9152youxi.cn/Article/details/gtynhigscx.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtjwhpqrdu.html

Java: 方法内为块级作用域
来源：http://dali.cheryme.top/Article/details/gteqgvjxev.html

Go:   花括号块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtywybhqcp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtvygawllu.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gtomahyhzk.html

[C11] 模块导入与导出
来源：http://dali.zhiwuduotai.top/Article/details/gtxznjpnge.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gtkmoztsch.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gtjoyvtzly.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtgpyndqnn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgnhwkki.html

Java: import java.util.List;
来源：http://dali.yonumen.top/Article/details/gtribynybt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gtmlldjnsc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtqcgmsztu.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtfmozenyr.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtlaiotyqn.html

Py:   (lambda: print("run"))()
来源：http://dali.meibo888.top/Article/details/gtwebeoesp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gtmnnefiav.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtjqtudaaz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtdxvwnszu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtjdwoudcn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuxming.cn/Article/details/gtfntkyqqd.html

Ruby: -> { puts "run" }.call
来源：http://dali.aizwys.cn/Article/details/gtvukxhjig.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtdsmngtxx.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtvyxorkac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gtcbgnzwgm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gttezguzrz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gtgcutxfua.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtfcxntkuh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gthdfgormb.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtmyxafwen.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtknrfmqdw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gtpdbtsweo.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtczycndzh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xuanzx.com/Article/details/gtwwjtfonc.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtbgtushlc.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtqfdezdzl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtksfntvjd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtdgbunxaa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtuliqzbbf.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtachirgwl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gtwzncshyx.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtiwwjbwgr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgzcfaft.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cqqwz.cn/Article/details/gtefudcrzd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtixdobipw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.havefunace.top/Article/details/gtkrsqhxqx.html

Java: // 无解构
来源：http://dali.shuidangran.top/Article/details/gthnhkopws.html

Go:   // 无解构
来源：http://dali.aibaodan.cn/Article/details/gttocybmvl.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gthvnanihx.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtftafkobv.html

[C16] 函数 / 方法重载
来源：http://dali.316326.xyz/Article/details/gtediqdktu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtxepzimpv.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtfqefqbln.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hfpthk.cn/Article/details/gtircqmmre.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtaxdkfpba.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nwbrower.top/Article/details/gtwoiqvykr.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtossheutn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtukmeqvig.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtkhzkgmnf.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtlvogoomf.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gtzcqguxyf.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtaffyywft.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtnxuxjdat.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gtuttqglef.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtxeebbelh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtfyejoxtv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cucudq.cn/Article/details/gthkeqiupz.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gthubbirsr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtvsoverwi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdjasypi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtqvdyuftx.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtznyklyyu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtferzermx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtvbkyzbic.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtnspibtkf.html

TS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtsowldinq.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtxrdqvrtw.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gtphcvwhxe.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cheryme.top/Article/details/gtntwbezdm.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gtpqdrvdzo.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtruguhddd.html

Py:   arr.insert(0, 0)
来源：http://dali.cqqwz.cn/Article/details/gtobbrnqrt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gtkdrrgjdo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmlhixyg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtxyovgwcn.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtzckjesuy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjfrfedc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dianchejie.cn/Article/details/gtwzkfzlgh.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpiajhgph.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtriciyjtw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yonumen.top/Article/details/gtogctrihy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gtvmpgqcdu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtygcqjlom.html

TS:   arr.splice(0, 1);
来源：http://dali.ppjwa.cn/Article/details/gtyzkvkyvn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtonfbojok.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gaohongyu789.top/Article/details/gtjjhksyey.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.9152youxi.cn/Article/details/gtafewwppr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtptumrctd.html

[D05] 访问与修改元素
来源：http://dali.pycfn.com/Article/details/gttqhgtwye.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtgzkordnx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtnfddawtz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtlkrdewzg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtztwpbyzq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtcquradym.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtovfhfaii.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yanxiufei.cn/Article/details/gtdkjcllkg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtvqorhdcz.html

[D06] 数组长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtafpgiywh.html

Py:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gttmcpxyxs.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtyefvjzzt.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtmmesvidv.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtnvybfqcl.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gtdvfakvcr.html

Go:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtcrjhdoow.html

Ruby: arr.length; arr.size
来源：http://dali.tanke756.top/Article/details/gtqhbcrrmu.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtoozioqgt.html

[D07] 切片 / 取子数组
来源：http://dali.yanxiufei.cn/Article/details/gtfphvgocu.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gteysgcivw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.iojbl.cn/Article/details/gtnzosflan.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtlagifjxq.html

TS:   arr.slice(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtlteaujaf.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gthfcpakos.html

Go:   arr[1:4]
来源：http://dali.wangshuangyany.cn/Article/details/gtyylcszfc.html

Ruby: arr[1, 3]
来源：http://dali.xylfe.cn/Article/details/gtekondvqj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhftubbw.html

[D08] 合并两个数组
来源：http://dali.hywenlv.cn/Article/details/gtubiscnha.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtzxmiwkjp.html

PHP:  array_merge($a, $b);
来源：http://dali.hnxiangtu.top/Article/details/gtbmabbfcb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yvedp.cn/Article/details/gturxcxuoh.html

TS:   [...a, ...b];
来源：http://dali.vqdsnc.cn/Article/details/gtgnnadmzp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtltszmoqc.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gtlmoswajv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwkqqldle.html

C#:   a.Concat(b).ToList()
来源：http://dali.yuanzhike.top/Article/details/gtbzkapheo.html

[D09] 排序（升序）
来源：http://dali.aizwys.cn/Article/details/gtkkertqwn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sxryk.cn/Article/details/gtbotkoeex.html

PHP:  sort($arr);
来源：http://dali.c1oappe.top/Article/details/gtjqmsbkif.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.chenlongwang.top/Article/details/gtmehcyxbr.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinqigfzy.top/Article/details/gtvqedzxrk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.cqqwz.cn/Article/details/gtgykonova.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtdthfvjrt.html

Ruby: arr.sort
来源：http://dali.cucudq.cn/Article/details/gtchilhszw.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gthvbtdwpt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtjlzgfsgu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hongshengwenyu.top/Article/details/gtyneulyle.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtanxcydfa.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinqigfzy.top/Article/details/gtwlweydsg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtxxetbivi.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenjidiqi.icu/Article/details/gthctqtbdw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtclxthzmd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhongyouzk.top/Article/details/gthtomrjvv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aizwys.cn/Article/details/gtemikakug.html

[D11] 反转数组
来源：http://dali.nwbrower.top/Article/details/gtvmztgjef.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtvtbioqur.html

PHP:  array_reverse($arr);
来源：http://dali.cdnleiting.top/Article/details/gtljmouozg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hysaishi.cn/Article/details/gtysxuknra.html

TS:   [...arr].reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtweljekli.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gtlazyqijl.html

Go:   slices.Reverse(arr)
来源：http://dali.zhoulong.xyz/Article/details/gtnivdgxuj.html

Ruby: arr.reverse
来源：http://dali.bjfxy.top/Article/details/gtvplsuvhd.html

C#:   list.Reverse();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqessplsx.html

[D12] 查找元素下标
来源：http://dali.yj20258.top/Article/details/gtqcfruixt.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangtech.top/Article/details/gthtgylszk.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtkprctytv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtxmgffdxe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gtsgwafmwe.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yvedp.cn/Article/details/gtomzezgyo.html

Go:   slices.Index(arr, x)
来源：http://dali.yj20258.top/Article/details/gtjzwlrddz.html

Ruby: arr.index(x)
来源：http://dali.zdqjudy.top/Article/details/gtzpsumdzj.html

C#:   list.IndexOf(x);
来源：http://dali.wangshuangyany.cn/Article/details/gtwvmsehtn.html

[D13] 过滤（保留满足条件的）
来源：http://dali.c1oappe.top/Article/details/gtoofvfsjm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtzovltjks.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhongyouzk.top/Article/details/gtonnqwyja.html

JS:   arr.filter(x => x > 3)
来源：http://dali.vqdsnc.cn/Article/details/gtylhkkglg.html

TS:   arr.filter(x => x > 3)
来源：http://dali.kuanghao11.cn/Article/details/gtbojmyxjk.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yj202588.top/Article/details/gtgkqjkzax.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gtpiyxqavx.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.yj20258888.top/Article/details/gtjikxvnqy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtdrqntptj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ivvv.top/Article/details/gtowwdkfin.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtutmclizo.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuxming.cn/Article/details/gtfdxpqipm.html

JS:   arr.map(x => x * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkyhrusn.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtdnmoueim.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtrkefbewk.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gtckmwxqsi.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtkroxfxil.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtzvemifhi.html

[D15] 去重
来源：http://dali.hysaishi.cn/Article/details/gtztehxdij.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtzzbnyhip.html

PHP:  array_unique($arr);
来源：http://dali.jiagoushi.top/Article/details/gtyawnxtum.html

JS:   [...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gthjbxhtob.html

TS:   [...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizffdcxn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.xinyue.icu/Article/details/gtoqhwmjbg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.xylfe.cn/Article/details/gtsqitesqw.html

Ruby: arr.uniq
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzdlbtdyz.html

C#:   list.Distinct().ToList()
来源：http://dali.shzxlz.cn/Article/details/gtagqwdhpc.html

[D16] 求和与平均值
来源：http://dali.pengpengdd.cyou/Article/details/gtaviwrtfj.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.chenzaomai.com/Article/details/gtnktwwqrc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpznfvmbs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.andypj.xyz/Article/details/gtfxudbygv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.tanke756.top/Article/details/gttjcjpuox.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwwdvgbo.html

Go:   // 手写循环累加
来源：http://dali.shangyingyoupin.top/Article/details/gtwcivmjxj.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.yvedp.cn/Article/details/gtoipsxscb.html

C#:   list.Sum();  list.Average()
来源：http://dali.jiagoushi.top/Article/details/gttdgaipgd.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gtbujlafoy.html

Py:   max(arr);  min(arr)
来源：http://dali.daria6918.cn/Article/details/gtupjclito.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtlfaxgcnb.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gtbwhqfbpy.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gtsggtspfg.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.daria6918.cn/Article/details/gtnzecpknw.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.mhx1999.top/Article/details/gtdmfxekba.html

Ruby: arr.max;  arr.min
来源：http://dali.chenlongwang.top/Article/details/gtkfxcezle.html

C#:   list.Max();  list.Min()
来源：http://dali.hysaishi.cn/Article/details/gtywityvbd.html

[D18] 扁平化嵌套数组
来源：http://dali.yuxming.cn/Article/details/gtfvmnzdgm.html


<!-- 参考信息 -->