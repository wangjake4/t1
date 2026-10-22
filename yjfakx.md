代发 wailian999

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqhauyskw.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtklpfkzaj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtvoatocci.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtidkeuxyl.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtpxaqlgvf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtzjnyzmbl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtlcfzrcru.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtqwbikylg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtszhsdyjf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnqzz.top/Article/details/gtlygqqytr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtcppykzlu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtmqbuvlby.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gtwbmgdzzp.html

Py:   def greet(name="World"): return name
来源：http://dali.bjfxy.top/Article/details/gtghcecbmp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtejgavuvy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gthpchwnmj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtgnyvtrcn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hywenlv.cn/Article/details/gtviparign.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnqzz.top/Article/details/gthmtsbzjh.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gtuigfzeuj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gtddcqdmje.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtneupjscj.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gtctqumgww.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gtbvjngxzu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtbqhokapz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtbfhsaxot.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tianlin.xyz/Article/details/gtadkcpgmb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtmxwwmmjq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tianlin.xyz/Article/details/gtbdesaeif.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gttpeoncnm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ehwqpu.com/Article/details/gtanraplln.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtamxzbztx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtwyrrnile.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gtcpmbwmtn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.birdmap.top/Article/details/gtlvpuvpqs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuanzx.com/Article/details/gtdxblqzzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gtgpieldcc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtjykwfkay.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtjvcmktjp.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gtkewlxker.html

Py:   return a, b
来源：http://dali.c1oappe.top/Article/details/gttxvnzmwe.html

PHP:  return [$a, $b];
来源：http://dali.yonumen.top/Article/details/gtwgqluonj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtnophhmxk.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtmzdotcfx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gteonmavfv.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtzmmeaoxd.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtiidjrcac.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gzhubu.top/Article/details/gttjiioiim.html

[C06] 匿名函数 / lambda
来源：http://dali.xuetiantiany.cn/Article/details/gtlejxsfzb.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gteopnjxou.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtjkmzadtk.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtilcizyob.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtuyhxzaes.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtmigcabvk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gtuyywfzek.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtlehbewzl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gaohongyu789.top/Article/details/gtqixthdqi.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gtsuojrteo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.feifeiyinyue.top/Article/details/gtjnevitqn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gtsyholozd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gttyxwlsat.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gtrtrxmykk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.vqdsnc.cn/Article/details/gtgtvgzevy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.chenzaomai.com/Article/details/gtxvcsftdq.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gtckgioznk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkbjinnc.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtvgsfczbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtlmutgfpq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tanke756.top/Article/details/gtebkzvypy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gthbzqaxob.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gtzpvsgfgp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtvabxuusk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gthamubojz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gtywshwerm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtpcjcnrdm.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gtwdsyqhaq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtlrsicgzt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gtnkfmnsnn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtqxnaeqva.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtmlskqlyz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtbzfpddvd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.snrcjt.cn/Article/details/gtwqdddtui.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwhhemvqi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gtpizulygd.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gtdkgvnbeg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.fengsongda.top/Article/details/gthlpmxvfu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gteuhubezp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtpmarncdk.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtuxitguze.html

Java: 方法内为块级作用域
来源：http://dali.mhx1999.top/Article/details/gtfvvzeluz.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtdnwuycmp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zycfv.cn/Article/details/gtjiqwafsk.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtfhaqglze.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtrtqhfcuk.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtozuxoaab.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cqqwz.cn/Article/details/gtqgfmwryw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gteobpxszn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtlhtifhti.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtvnxdegrh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtgextcndd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sxryk.cn/Article/details/gtkzbfvdun.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtufugykpa.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtfxcazpdu.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtuamcqabs.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtzdacviwf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gthldvtvhz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtgxkiugfm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtuudsvykq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtmsrzyeld.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gtlsnrzral.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtelqimstw.html

[C13] 类型声明 / 类型注解
来源：http://dali.nwbrower.top/Article/details/gttsvlrmlu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtublibmzg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttniieraw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtekryvsvy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtzsspybzb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gthdjlvvrd.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtjljqvfon.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gtimtlddcp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtbrnlvdgx.html

[C14] 泛型函数
来源：http://dali.xinyue.icu/Article/details/gttkkyqrrr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtnprmssaf.html

PHP:  // 无泛型
来源：http://dali.meibo888.top/Article/details/gthnwzsynw.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtgdnczfls.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guannengcc.top/Article/details/gtvijwrgsn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtohuyntdm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtbpydaytp.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtkgqecutx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtcogzwwfw.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtilrduelr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtmsbcowbs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gthpxgpzbz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtapmqacck.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtiatcdryg.html

Java: // 无解构
来源：http://dali.nwbrower.top/Article/details/gtfilcqlly.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtkgrjrsvv.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gthfnrkfnh.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtydpowzku.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtvrfyrivg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.pycfn.com/Article/details/gttedjswhz.html

PHP:  // 无重载
来源：http://dali.hysaishi.cn/Article/details/gtdcwdzoln.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yongpay.top/Article/details/gtolyythms.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyvoegez.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigufen.top/Article/details/gtwfxvgsxf.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtqjuxuoja.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtgiatctqv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtvqooomii.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtyfyzchqn.html

D. 数组 / 列表 / 集合
来源：http://dali.yj202588.top/Article/details/gtcsafqnyl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtdcperhgs.html

[D01] 创建数组 / 列表
来源：http://dali.zhengqikj.top/Article/details/gtkwrebesj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.svipenyu.cn/Article/details/gtzqvurpgi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtvakcgvkm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtfdtoqjig.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.andypj.xyz/Article/details/gtzgbwokcv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtcprzqoma.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zdqjudy.top/Article/details/gtxxjxryax.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ybcxt.top/Article/details/gtzwruloii.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtygcqzjvs.html

[D02] 追加元素到末尾
来源：http://dali.aizwys.cn/Article/details/gtlovskwot.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtfoiuabkl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtmxhzlypf.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtwtmujsvz.html

TS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtqfyvcyen.html

Java: list.add(4);
来源：http://dali.ppjwa.cn/Article/details/gtnpmbsjbl.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtkniavwsz.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.meibo888.top/Article/details/gtycdwbsrv.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gtxqxilayr.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtslwnrugn.html

Py:   arr.insert(0, 0)
来源：http://dali.chenlongwang.top/Article/details/gtotectwva.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gttheqfwqb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtcpypdbxl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtagdrrotz.html

Java: list.add(0, 0);
来源：http://dali.jinqigufen.top/Article/details/gtgcvtsmef.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jyoumei.cn/Article/details/gtvwcvzqfv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.birdmap.top/Article/details/gtvshseywa.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtavgyqrgx.html

[D04] 删除元素
来源：http://dali.kuanghao11.cn/Article/details/gteybchtzg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yangfankeji.com/Article/details/gttialoajm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtiwidgliq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbowrvupz.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gtvtgdpihe.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtwsmhpcjr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtmxhiwsng.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtaqyxwxan.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jqgufenzy.top/Article/details/gtqfprufnh.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtciaegjhv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtylrmhtdc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ydzc1.top/Article/details/gtvqgkokmv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtbmkgyniq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ppjwa.cn/Article/details/gtbucpgskd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtggjkrsww.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gtfdjcxsju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtdqlzgkpq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtqeaicmeo.html

[D06] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtnpgnjkup.html

Py:   len(arr)
来源：http://dali.sweek.top/Article/details/gtumpreimk.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gttnimbqwp.html

JS:   arr.length
来源：http://dali.316326.xyz/Article/details/gtfjdchwax.html

TS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtmfpjztce.html

Java: list.size();
来源：http://dali.pengpengdd.cyou/Article/details/gtkzvraqjx.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtbqbnmxhc.html

Ruby: arr.length; arr.size
来源：http://dali.aizwys.cn/Article/details/gtvloiiaba.html

C#:   list.Count;
来源：http://dali.cashguo.top/Article/details/gthhczbwti.html

[D07] 切片 / 取子数组
来源：http://dali.yueranfly.top/Article/details/gtcwsyvqgj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gtzqlgksno.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.bjfxy.top/Article/details/gtcagiwlft.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtalniwlhv.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtznypeunb.html

Java: list.subList(1, 4);
来源：http://dali.cucudq.cn/Article/details/gtrgtbnwev.html

Go:   arr[1:4]
来源：http://dali.hywenlv.cn/Article/details/gtcwswxjom.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtwiafmhpp.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhengqikj.top/Article/details/gtrvpshfqd.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gtvgtcrvmu.html

Py:   a + b;  a.extend(b)
来源：http://dali.cucudq.cn/Article/details/gtnpwumfkl.html

PHP:  array_merge($a, $b);
来源：http://dali.fzhhl.top/Article/details/gtuemqsbil.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvgiplmb.html

TS:   [...a, ...b];
来源：http://dali.yvedp.cn/Article/details/gtcqcbcbjv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.snrcjt.cn/Article/details/gthttnvjpc.html

Go:   append(a, b...)
来源：http://dali.zhongyouzk.top/Article/details/gtvapdbell.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hfpthk.cn/Article/details/gtusadnqlk.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtkwmfwdpb.html

[D09] 排序（升序）
来源：http://dali.yuxming.cn/Article/details/gtmmlzizau.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gttdlkryqf.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtijozmxyr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shanyushiyangtech.top/Article/details/gtfexvwjda.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj20258888.top/Article/details/gtyzvxwonp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtxterwccf.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.tanke756.top/Article/details/gtymuweuvq.html

Ruby: arr.sort
来源：http://dali.zhengqikj.top/Article/details/gtjgqnxchc.html

C#:   list.Sort();
来源：http://dali.yanxiufei.cn/Article/details/gtrridmhqs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jiagoushi.top/Article/details/gtqrhtrvlb.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gzhubu.top/Article/details/gtmmpitnvq.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqxyeeurt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.andypj.xyz/Article/details/gtulojtfoz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtbxtditat.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tanke756.top/Article/details/gtvgoefull.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yongpay.top/Article/details/gtvrzgwnqx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangshuangyany.cn/Article/details/gtfluwhdin.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.guannengcc.top/Article/details/gthulqosws.html

[D11] 反转数组
来源：http://dali.xziqi.cn/Article/details/gtijnrlzni.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaxmqumt.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gtgerpmske.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.sweek.top/Article/details/gtufbmifxj.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtrvlkrdtn.html

Java: Collections.reverse(list);
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiyixgkm.html

Go:   slices.Reverse(arr)
来源：http://dali.ppjwa.cn/Article/details/gtwxyrrues.html

Ruby: arr.reverse
来源：http://dali.ivvv.top/Article/details/gttwnlzior.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtxoxgiuib.html

[D12] 查找元素下标
来源：http://dali.aibaodan.cn/Article/details/gtfpbnarnk.html

Py:   arr.index(x);  x in arr
来源：http://dali.c1oappe.top/Article/details/gttmilggeo.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtlmgwzxyw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtryoghxow.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.chenlongwang.top/Article/details/gtdjxxhxwt.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xylfe.cn/Article/details/gttctulcit.html

Go:   slices.Index(arr, x)
来源：http://dali.quarkkingdee.top/Article/details/gteuhinwhh.html

Ruby: arr.index(x)
来源：http://dali.jiagoushi.top/Article/details/gtelosiroi.html

C#:   list.IndexOf(x);
来源：http://dali.snrcjt.cn/Article/details/gtmaixzpqi.html

[D13] 过滤（保留满足条件的）
来源：http://dali.havefunace.top/Article/details/gtoymrucxb.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hammf.cn/Article/details/gtndbytxlf.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gaohongyu789.top/Article/details/gtxmsjjdgd.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jlsjyb.cn/Article/details/gtgreihqow.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtgwkhkzba.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtiwzuubju.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xuetiantiany.cn/Article/details/gtdyecknjy.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.gogol.net.cn/Article/details/gtojibrojy.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtzbvrcymj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.0kj1m.cn/Article/details/gtokgqseda.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.svipenyu.cn/Article/details/gtoskubazx.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtvkitefej.html

JS:   arr.map(x => x * 2)
来源：http://dali.smart0.xyz/Article/details/gtrggqvmlf.html

TS:   arr.map(x => x * 2)
来源：http://dali.aibaodan.cn/Article/details/gtnttpcvkt.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.cucudq.cn/Article/details/gtcpqasnrm.html

Go:   // 手写循环
来源：http://dali.xuetiantiany.cn/Article/details/gtxjgixdbn.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gthlvxuwah.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtsguxhgib.html

[D15] 去重
来源：http://dali.c1oappe.top/Article/details/gtrminjgdu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jinqigufen.top/Article/details/gtpbajrwqg.html

PHP:  array_unique($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtezkzuwto.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtjptggwiz.html

TS:   [...new Set(arr)]
来源：http://dali.zycfv.cn/Article/details/gthhjzyseb.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.vqdsnc.cn/Article/details/gtvfqjauss.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cashguo.top/Article/details/gtzamsslrq.html

Ruby: arr.uniq
来源：http://dali.wangshuangyany.cn/Article/details/gttrqaaxoq.html

C#:   list.Distinct().ToList()
来源：http://dali.hammf.cn/Article/details/gtdsgdmjln.html

[D16] 求和与平均值
来源：http://dali.hammf.cn/Article/details/gturfmuyih.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtgyyrulbm.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtqthpxqtk.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yuanzhike.top/Article/details/gtqxrgibrz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtjabndwcj.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fengsongda.top/Article/details/gtlvwtmwdi.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtgguqignz.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gtdrxfdkoa.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gtazsrpfpo.html

[D17] 最大值与最小值
来源：http://dali.svipenyu.cn/Article/details/gthesanwrj.html

Py:   max(arr);  min(arr)
来源：http://dali.mhx1999.top/Article/details/gtxvzskrpl.html

PHP:  max($arr);  min($arr);
来源：http://dali.hnqzz.top/Article/details/gtamwtelas.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.shuidangran.top/Article/details/gtmdgysrsd.html

TS:   Math.max(...arr);
来源：http://dali.9152youxi.cn/Article/details/gtnzcoswfj.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.0kj1m.cn/Article/details/gtrplmvrxr.html


<!-- 参考信息 -->