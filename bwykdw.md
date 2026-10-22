代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.guannengcc.top/Article/details/gtwztrggkc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgibmcouf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtxpuzieja.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtcbpramuh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtatfdwnii.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gtraxbggpu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtpyoeblls.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtoxljxrdu.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtzmpsvygj.html

Py:   def greet(name="World"): return name
来源：http://dali.jiagoushi.top/Article/details/gtkprccket.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtvwnjjham.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gthkvcgpfl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgptjqldv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtmzcclzox.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gthimqgwfj.html

Ruby: def greet(name = "World") = name
来源：http://dali.vqdsnc.cn/Article/details/gtssszfedr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtzhqfwqrp.html

[C03] 可变参数
来源：http://dali.xinyue.icu/Article/details/gtncpqurco.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gtwqvhaxoa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gtlgufdugu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtpehvawqt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtwtvtgfjq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtbockbscq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gttlrdijni.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gtwblwwwre.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtuosteraj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhzwuiam.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtxqmkznng.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtpcwyjdac.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtvpjwyrxt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtsvyvdqed.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.birdmap.top/Article/details/gtvkqhqzkp.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtpduthbet.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtloyvjrbl.html

C#:   f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtteoqmiqf.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtujkyisex.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtlpieootc.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtlrtuednn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtyswusbot.html

TS:   return { a, b };
来源：http://dali.0kj1m.cn/Article/details/gtecdxbzwc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtivuxvede.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtwxhbrlog.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtjhprglcm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtamtpvdma.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtwyrisevx.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtpoulfflq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtcyxtbdvk.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtrgtjqpzv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gthvfzfzod.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtnjqqnjpu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gtcbvneyir.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtmapnmkhf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aizwys.cn/Article/details/gtppxragzp.html

[C07] 把函数作为参数传入
来源：http://dali.jlsjyb.cn/Article/details/gtdspbyldf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtxgohfcsh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtecbujzoy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtvtfbfxry.html

TS:   arr.map(String)
来源：http://dali.hongshengwenyu.top/Article/details/gtzcgaqiwj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtwaizovtn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jlsjyb.cn/Article/details/gtsxpvszyk.html

Ruby: arr.map(&:upcase)
来源：http://dali.hammf.cn/Article/details/gtvszafpjc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtbecefass.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gtgcphwjdf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.9152youxi.cn/Article/details/gtwkioaxjy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gtifzptksy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gttdpdgsdc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gttbpnbgie.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtnmezyoyo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gthajpbcbb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gtvsjnnrxr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtidpvcyzd.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gtepdpphur.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gttluowsrz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gttsvtufkg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cqqwz.cn/Article/details/gtzyryrihy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtvcpqgpkl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtacyhbksw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinghuilouyu.cn/Article/details/gttowywgsj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtcgjqazph.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtgrvjpdll.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtdqyxhvkb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ppjwa.cn/Article/details/gtkjcxojwd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtbwxollvm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nwbrower.top/Article/details/gtjgscchdd.html

TS:   同 JS
来源：http://dali.snrcjt.cn/Article/details/gtqrifbrnz.html

Java: 方法内为块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtpyddpzlw.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtoldooqsm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gtfzjhqojn.html

C#:   块级作用域
来源：http://dali.ehwqpu.com/Article/details/gthqrbgold.html

[C11] 模块导入与导出
来源：http://dali.tanke756.top/Article/details/gtwsrntsid.html

Py:   from module import func
来源：http://dali.jqgufenzy.top/Article/details/gtapmltqhj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gtntjyygot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtfhykhjcj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtepzygjuv.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtjrjsqeyw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtdyikmqdz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gtxfaybbeq.html

C#:   using System.Text;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjqzlqje.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gtjrfyftdz.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gteoxdbvez.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhiwuduotai.top/Article/details/gtjhqkodgl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtxbifblze.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtedozxbnj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.mhx1999.top/Article/details/gtsppnoghf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gttjayzndq.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtqrpypovu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtqtgqtgzu.html

[C13] 类型声明 / 类型注解
来源：http://dali.shangyingyoupin.top/Article/details/gtsmututkd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtwioxiqol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtuchgcple.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcwpvmou.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtcdfuicar.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtefpjwhyy.html

Go:   func add(a, b int) int
来源：http://dali.ehwqpu.com/Article/details/gtcnxjvwet.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gtfuduuklt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtynhanrpe.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gtiwcujefp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtgnbmthpe.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtwrbvbfzn.html

JS:   // 无泛型
来源：http://dali.9152youxi.cn/Article/details/gtbjswcqbb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtnmtohdxz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtjxtlfezk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtntlqazfd.html

Ruby: # 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaglzeklq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sysykeji.top/Article/details/gtwhdzaszi.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtwybprgzj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ivvv.top/Article/details/gtfljfxlvb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tanke756.top/Article/details/gtrfzbdpsl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtnrtbferp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtwfsvfpis.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtceeoecxr.html

Go:   // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtxasawgbb.html

Ruby: a, b = pair
来源：http://dali.svipenyu.cn/Article/details/gtkifdkkal.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtqdffadzx.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtabgcztnx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gtkahkaklh.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvjqgzwr.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtxgmyhcxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sweek.top/Article/details/gtlpqiyiov.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shuidangran.top/Article/details/gtflktsepv.html

Go:   // 无重载：用不同函数名
来源：http://dali.guowangkeji.top/Article/details/gtjovdadnd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdldktvck.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtrmdnpgbu.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbeidtbew.html

D. 数组 / 列表 / 集合
来源：http://dali.guannengcc.top/Article/details/gtfjwxnqkq.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsxygykfy.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtfhncknkf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zdqjudy.top/Article/details/gttapvtcag.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtqvrhyyah.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtipwuumdr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtrmmomxgo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtxjjwfdsl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.redwolf501.top/Article/details/gtrvhxkzsz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtlykfonbo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtiwmffedc.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtaiazzjfd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gtlcvekbrt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sufxvd.cn/Article/details/gtiukywbho.html

JS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtwrwwxfwl.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtpxzahsjj.html

Java: list.add(4);
来源：http://dali.fzhhl.top/Article/details/gtvulkizqn.html

Go:   arr = append(arr, 4)
来源：http://dali.yangfankeji.com/Article/details/gtrjbbgrxj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrrtsrhj.html

C#:   list.Add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtbxnozhac.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtgmvtwkvp.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtlbcnpxtj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqihayxdd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zdqjudy.top/Article/details/gtahvkskoy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtnguqexfg.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtklgmdbkt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhengqikj.top/Article/details/gtkyicjncv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.0kj1m.cn/Article/details/gtpcugiqkd.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtdxtrxizu.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gtymijaoxz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.bjfxy.top/Article/details/gtspmoddjx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtkpjaagyx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtaftanxgl.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtydvkuwck.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtuznjhsnm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gtjyufvctt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdctmrmpz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtlqkkgatv.html

[D05] 访问与修改元素
来源：http://dali.redwolf501.top/Article/details/gtccdelijy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtcsrwjzkr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtctkswqhm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkenqjalk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtgyyjthue.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtfpwsifbn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtygjoxjhm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwspwfesh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shuidangran.top/Article/details/gtrizedjre.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtytsztfxd.html

Py:   len(arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbvrvoxqr.html

PHP:  count($arr);
来源：http://dali.zhixingplan.top/Article/details/gtdsqtfwyb.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtnqogbqbk.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtwvjehtyc.html

Java: list.size();
来源：http://dali.zhiwuduotai.top/Article/details/gtbmmrjliw.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtzwiegdej.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gthfxnmogp.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtdmqcsuyj.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtppidcyyd.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gtuyegkxyx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gtlaklkdzm.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtuyxyrlvj.html

TS:   arr.slice(1, 4);
来源：http://dali.nanxuanxn.top/Article/details/gtnijggama.html

Java: list.subList(1, 4);
来源：http://dali.c1oappe.top/Article/details/gtutsxxbln.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gtzlvyhoak.html

Ruby: arr[1, 3]
来源：http://dali.tianlin.xyz/Article/details/gtbqevihva.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gthtkjjimt.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtghriujuz.html

Py:   a + b;  a.extend(b)
来源：http://dali.jlsjyb.cn/Article/details/gtugtoezhm.html

PHP:  array_merge($a, $b);
来源：http://dali.shzxlz.cn/Article/details/gtgqlapiun.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gtujwexdam.html

TS:   [...a, ...b];
来源：http://dali.haohaochexian.top/Article/details/gtrkmstmfu.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.havefunace.top/Article/details/gtcpbcdopx.html

Go:   append(a, b...)
来源：http://dali.hfpthk.cn/Article/details/gtulhyzccv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.aibaodan.cn/Article/details/gtgodcoqey.html

C#:   a.Concat(b).ToList()
来源：http://dali.9152youxi.cn/Article/details/gtimqutint.html

[D09] 排序（升序）
来源：http://dali.c1oappe.top/Article/details/gtkqsmbmuf.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gttaxitzzo.html

PHP:  sort($arr);
来源：http://dali.yj20258888.top/Article/details/gtrdsudlab.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtycctxtdv.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jiagoushi.top/Article/details/gtlnnhspdu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.quarkkingdee.top/Article/details/gtkvmarouh.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhengqikj.top/Article/details/gtrzgmjqlh.html

Ruby: arr.sort
来源：http://dali.yvedp.cn/Article/details/gtrmdjpiyo.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtdgrecvgh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinqigufen.top/Article/details/gtabqxkawn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtnbbofnob.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtpptbselv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cashguo.top/Article/details/gtfpscwpdq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtkqhnjbtl.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkgfeprr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xylfe.cn/Article/details/gternzumpu.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jiagoushi.top/Article/details/gtykzlywhi.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gteaqjdcjr.html

[D11] 反转数组
来源：http://dali.yj20258888.top/Article/details/gtojsvkphe.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtufginjuz.html

PHP:  array_reverse($arr);
来源：http://dali.xziqi.cn/Article/details/gtjydwaurw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shzxlz.cn/Article/details/gtuyfveieb.html

TS:   [...arr].reverse();
来源：http://dali.jyoumei.cn/Article/details/gtvbfsjgxv.html

Java: Collections.reverse(list);
来源：http://dali.cheryme.top/Article/details/gtqndprkis.html

Go:   slices.Reverse(arr)
来源：http://dali.0kj1m.cn/Article/details/gtubxdtllq.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtqcqikawn.html

C#:   list.Reverse();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuqvytmch.html

[D12] 查找元素下标
来源：http://dali.cdnleiting.top/Article/details/gtwziyvkpf.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenlongwang.top/Article/details/gtamksluxy.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xziqi.cn/Article/details/gtkowxpgzh.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.smart0.xyz/Article/details/gtgpxavwsn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yonumen.top/Article/details/gthvykywyr.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yueranfly.top/Article/details/gthpqmbums.html

Go:   slices.Index(arr, x)
来源：http://dali.zdqjudy.top/Article/details/gtwciliyfr.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gtuvptkfkc.html

C#:   list.IndexOf(x);
来源：http://dali.vqdsnc.cn/Article/details/gtuurlqiep.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dianchejie.cn/Article/details/gtspvstlso.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmynnldm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jqgufenzy.top/Article/details/gtvlaxlayi.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnqzz.top/Article/details/gtetkdcwqh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sxryk.cn/Article/details/gtbophbpjm.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cucudq.cn/Article/details/gtupphzubj.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.316326.xyz/Article/details/gtipkfbzhl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.zhijiandao.cn/Article/details/gtnqzfpujx.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.yuxming.cn/Article/details/gtwldlmxby.html

[D14] 映射转换（每个元素变形）
来源：http://dali.wangdashe.top/Article/details/gtaedpexii.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.cqqwz.cn/Article/details/gtjkzuqnii.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.hammf.cn/Article/details/gtuysqtwtw.html

JS:   arr.map(x => x * 2)
来源：http://dali.redwolf501.top/Article/details/gtzsnyodtp.html

TS:   arr.map(x => x * 2)
来源：http://dali.cucudq.cn/Article/details/gtwssqkesf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shuidangran.top/Article/details/gttlpemgbc.html

Go:   // 手写循环
来源：http://dali.zycfv.cn/Article/details/gtpoxqdlvm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yonumen.top/Article/details/gttoqkbdke.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yanxiufei.cn/Article/details/gtnrwlinhb.html

[D15] 去重
来源：http://dali.ehwqpu.com/Article/details/gtbljgyoez.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtyuxpceib.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtcbwhahga.html

JS:   [...new Set(arr)]
来源：http://dali.gaohongyu789.top/Article/details/gtmgbnmhaw.html

TS:   [...new Set(arr)]
来源：http://dali.cqqwz.cn/Article/details/gtlwqrwwyr.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.chenjidiqi.icu/Article/details/gtvywjiitj.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwfrimeo.html

Ruby: arr.uniq
来源：http://dali.vqdsnc.cn/Article/details/gtncbkvmxg.html

C#:   list.Distinct().ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtaviigamn.html

[D16] 求和与平均值
来源：http://dali.daria6918.cn/Article/details/gtbpdgbtea.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gtuxpcwgok.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtffaawttj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.haohaochexian.top/Article/details/gtmyzvrfyn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhiwuduotai.top/Article/details/gtwfmbubva.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.hysaishi.cn/Article/details/gtsnzboraa.html

Go:   // 手写循环累加
来源：http://dali.sxryk.cn/Article/details/gtwwlwcgur.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.9152youxi.cn/Article/details/gtffwnbpim.html

C#:   list.Sum();  list.Average()
来源：http://dali.jinqigfzy.top/Article/details/gtkgvuezhx.html

[D17] 最大值与最小值
来源：http://dali.yvedp.cn/Article/details/gteexekcat.html

Py:   max(arr);  min(arr)
来源：http://dali.cashguo.top/Article/details/gtfvbppnbc.html

PHP:  max($arr);  min($arr);
来源：http://dali.cucudq.cn/Article/details/gtjbpcwfrg.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.feifeiyinyue.top/Article/details/gtbiygsoxm.html

TS:   Math.max(...arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gttuowfypk.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.gogol.net.cn/Article/details/gtqthswgwm.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.xylfe.cn/Article/details/gtjgniksjh.html

Ruby: arr.max;  arr.min
来源：http://dali.aizwys.cn/Article/details/gtqkarzxrc.html

C#:   list.Max();  list.Min()
来源：http://dali.daria6918.cn/Article/details/gtlzcxrveq.html

[D18] 扁平化嵌套数组
来源：http://dali.gaohongyu789.top/Article/details/gtlvqbqwkw.html


<!-- 参考信息 -->