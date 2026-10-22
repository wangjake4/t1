代发 wailian999

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtckutvhue.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gtomnllhhe.html

JS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtkqlfcvxy.html

TS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gtdfyrwteh.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtxjxhfmut.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtzuwauknk.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtqzjreyvf.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtitokeinh.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtmwdnoddw.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtjprtvasp.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtdzuelsut.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtcguxrlva.html

Py:   def add(a, b): return a + b
来源：http://dali.ivvv.top/Article/details/gtwtmcvfac.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfowdoqga.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gttqyglszy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtsiwbzylr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtfyuaxcfv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gttnnrafmu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gtwowinioq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtarrjtqas.html

[C02] 默认参数
来源：http://dali.meibo888.top/Article/details/gtvhkpzvih.html

Py:   def greet(name="World"): return name
来源：http://dali.zycfv.cn/Article/details/gtatdmszjn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tanke756.top/Article/details/gtxcfmqwep.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtitvmnats.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtrcwgyqib.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nwbrower.top/Article/details/gtwwtyxzfp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sysykeji.top/Article/details/gtonuyfjor.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhixingplan.top/Article/details/gtvvyfqncf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtfhhgibfm.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtuocydydi.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gtsvckwvkn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtgzaxkqmx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gtwjahygeh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtjcvwtsfn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gteqsckqja.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtqcvwqkuh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtuxdtyqyq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhixingplan.top/Article/details/gtrlaunbfx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtbumjycvi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gtmcenjepm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.0kj1m.cn/Article/details/gtcpkkwjwx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtxqeslkld.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgyajkoy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtmkfxfjgx.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gtwqfvocis.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtlmzwpxkv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtqoaeuhtr.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtzfcrhxnd.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtgttducsh.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gtiztutoln.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gturwsjwzy.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtxzuiwyzb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtamsoqlum.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtfetxtljf.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtopjnfrry.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtjcapuvwa.html

[C06] 匿名函数 / lambda
来源：http://dali.0kj1m.cn/Article/details/gtbctpzvsw.html

Py:   square = lambda x: x * x
来源：http://dali.gotoacloud.top/Article/details/gtobwgfknj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtamjrhcpk.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtrzpxoooc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtjnnstyef.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtgnezshhu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtmrrlrwhf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtnegcfpoj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtillkffra.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtxajblxjy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gthpnmoekb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtxzzjtfls.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtekatkdiu.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtssdvxgyu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tian-w.cn/Article/details/gtgwiilcrl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtxsdnsamx.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtcnosvukj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtmolahtlb.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtcurywroa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gthdjcyxxp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtnhvazipd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtckwmjruu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtwbtslfyp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtlmzierap.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gtkxslbiub.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.snrcjt.cn/Article/details/gtaytfvxwf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtphmxviad.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtjeewpzeh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnaygtywc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtmzozusjk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujcuscnu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtkkmzfdye.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwqddftbr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gttgrozdcx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtgavropmu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cdnleiting.top/Article/details/gtkixlufcy.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtgkokdyvg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtvlzrfnbp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnxiangtu.top/Article/details/gthgnqmmbh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258888.top/Article/details/gthqaroggk.html

TS:   同 JS
来源：http://dali.hysaishi.cn/Article/details/gtfixajsez.html

Java: 方法内为块级作用域
来源：http://dali.meibo888.top/Article/details/gtlphrmspj.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gtjytdxcgw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.svipenyu.cn/Article/details/gtcmrfameo.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtymqaeyjg.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtrkyfmwxy.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtscdfbbrm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gtvujpwazp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shangyingyoupin.top/Article/details/gtmipbycqs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgfzy.top/Article/details/gtnszqnbix.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtcuukkzoh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.kuanghao11.cn/Article/details/gtynqbywgj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.wangdashe.top/Article/details/gtypkeittl.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtickadgrm.html

[C12] 立即执行函数 IIFE
来源：http://dali.meibo888.top/Article/details/gtnflhngsv.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtuhpfeunn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yuanzhike.top/Article/details/gtzwkfeknz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtbdhjwjec.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtzrdpmtko.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhengqikj.top/Article/details/gtajnpswew.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gtnhfecfii.html

Ruby: -> { puts "run" }.call
来源：http://dali.dashuyun.cn/Article/details/gtmualfzlw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtqhhgwaal.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtujfftlvu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtpqcbsupn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gthciprgyz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gteyqglszi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtmxkdpcni.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtozyprgrk.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtmshppfum.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtlztemxcz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtagfqqtys.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtrrawnzhv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtibktfvqs.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtfpswixti.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtqkjonihc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqitcsxx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hywenlv.cn/Article/details/gtwguwatcn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlmdindel.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtalddgjpu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtychnkfln.html

[C15] 解构 / 展开参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucdqquxx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtzgnvgdvp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.pycfn.com/Article/details/gtpkmlzoix.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtvwjyffok.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlubmnueh.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gtjsrbccrm.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtpngwicna.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtgguewkwy.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtgakasvmx.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtkzhckqqj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gthmkfpuct.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtbhdqpwtl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtguqnydzq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtlzbwilav.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtuaaitnqg.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtlecgdjin.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gtigjqlkmy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtdgahxmkq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gthhscnvnb.html

D. 数组 / 列表 / 集合
来源：http://dali.cdnleiting.top/Article/details/gtowcexedq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtnznxqcdc.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtzezupfik.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqnueftm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gtdhzxoqjl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gtvqlfwksg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtstnuxpgk.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtvbdgjfjo.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gtlgckqmlx.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shzxlz.cn/Article/details/gtworlvzut.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gtezkpmcka.html

[D02] 追加元素到末尾
来源：http://dali.meibo888.top/Article/details/gtcdqleada.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.smart0.xyz/Article/details/gthvmnvsxt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gtxddeujtv.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtzbwqevit.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtorgfansh.html

Java: list.add(4);
来源：http://dali.hnqzz.top/Article/details/gtupzgteig.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgfzy.top/Article/details/gtxnvsuqwa.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqqmenufo.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtpgjhrrwt.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtxpxvszqo.html

Py:   arr.insert(0, 0)
来源：http://dali.hnxiangtu.top/Article/details/gtwprcpblp.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtieitrnxe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gtzjpcqlqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtsayhdsav.html

Java: list.add(0, 0);
来源：http://dali.yangfankeji.com/Article/details/gtfzcnixpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtxeijyfzc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtbalsdhph.html

C#:   list.Insert(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtvclodszm.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtspnuflwp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.guannengcc.top/Article/details/gtmizuiiec.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gtywpxnafo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xuetiantiany.cn/Article/details/gtinroenem.html

TS:   arr.splice(0, 1);
来源：http://dali.gaohongyu789.top/Article/details/gtsduuarui.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtseetfmgu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gtfzmauvgd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtktdvhfpx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtomwonyor.html

[D05] 访问与修改元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezcminoc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgufenzy.top/Article/details/gtcwqoadry.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtkaxkihod.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gttojzhrxz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtslhwsxkg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gotoacloud.top/Article/details/gtdqtjhchr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.dianchejie.cn/Article/details/gtzwnwfmyt.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtqakdvidh.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtfwgepsbs.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gtuvuahtyf.html

Py:   len(arr)
来源：http://dali.snrcjt.cn/Article/details/gtudkmutog.html

PHP:  count($arr);
来源：http://dali.gotoacloud.top/Article/details/gtbovfhlca.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtusvquvxt.html

TS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtusglimtg.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gtheasxtph.html

Go:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtqkxqlnvm.html

Ruby: arr.length; arr.size
来源：http://dali.yj20258888.top/Article/details/gtireousja.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtqdlaeaip.html

[D07] 切片 / 取子数组
来源：http://dali.xuetiantiany.cn/Article/details/gteglsbdre.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yangfankeji.com/Article/details/gtzytajpzc.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtkzxhdzrd.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtkdwubpaj.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtrakfosbl.html

Java: list.subList(1, 4);
来源：http://dali.nanxinkj.top/Article/details/gtadswmqbz.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gturubufjj.html

Ruby: arr[1, 3]
来源：http://dali.svipenyu.cn/Article/details/gtkwmzsugl.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtlkpnznaw.html

[D08] 合并两个数组
来源：http://dali.zhiwuduotai.top/Article/details/gtyuqteler.html

Py:   a + b;  a.extend(b)
来源：http://dali.dashuyun.cn/Article/details/gthnchnfaf.html

PHP:  array_merge($a, $b);
来源：http://dali.pycfn.com/Article/details/gtdnowypgq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtegzxqupd.html

TS:   [...a, ...b];
来源：http://dali.pengpengdd.cyou/Article/details/gtdguasifv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daxiang520.top/Article/details/gtqlarddcc.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gttdnzbsdd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yuxming.cn/Article/details/gtmwwskmlb.html

C#:   a.Concat(b).ToList()
来源：http://dali.yonumen.top/Article/details/gtjzjxegss.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbonbijs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hnxiangtu.top/Article/details/gtrsrpunhv.html

PHP:  sort($arr);
来源：http://dali.hywenlv.cn/Article/details/gtbjcjcaex.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuetiantiany.cn/Article/details/gtellanelo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cheryme.top/Article/details/gtaavfisvr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.sysykeji.top/Article/details/gtbnbwnaxj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gzhubu.top/Article/details/gttftjaowm.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtdozcsnpk.html

C#:   list.Sort();
来源：http://dali.sweek.top/Article/details/gttjcfectn.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.c1oappe.top/Article/details/gtqvymvbat.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.snrcjt.cn/Article/details/gthixspvym.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.smart0.xyz/Article/details/gthkeudhlo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtcvsbeiar.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtxjgrkcxc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.chenlongwang.top/Article/details/gtszxfwfuv.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenlongwang.top/Article/details/gtrsrfxnrz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gtkeziuuqw.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtanrthazl.html

[D11] 反转数组
来源：http://dali.yuxming.cn/Article/details/gtxbpmzchy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwbjsswz.html

PHP:  array_reverse($arr);
来源：http://dali.yj20258.top/Article/details/gtalzlcblt.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.haohaochexian.top/Article/details/gtzidqmjmq.html

TS:   [...arr].reverse();
来源：http://dali.9152youxi.cn/Article/details/gtglcflqan.html

Java: Collections.reverse(list);
来源：http://dali.dashuyun.cn/Article/details/gttytjccwv.html

Go:   slices.Reverse(arr)
来源：http://dali.gogol.net.cn/Article/details/gtatyyelsr.html

Ruby: arr.reverse
来源：http://dali.dianchejie.cn/Article/details/gtgddgdpas.html

C#:   list.Reverse();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfftpllyz.html

[D12] 查找元素下标
来源：http://dali.shuidangran.top/Article/details/gtvivufxmf.html

Py:   arr.index(x);  x in arr
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxxfgaiwi.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtfvpaasrm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jinqigufen.top/Article/details/gtiovqyvup.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gtdcbmjhsp.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gtybpprpbv.html

Go:   slices.Index(arr, x)
来源：http://dali.havefunace.top/Article/details/gtgxmknrnx.html

Ruby: arr.index(x)
来源：http://dali.andypj.xyz/Article/details/gtdiefbilf.html

C#:   list.IndexOf(x);
来源：http://dali.xuetiantiany.cn/Article/details/gtfiwtijru.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gogol.net.cn/Article/details/gtybmyzeoz.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtskyvaekq.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.bjfxy.top/Article/details/gtzojnihhm.html

JS:   arr.filter(x => x > 3)
来源：http://dali.yangfankeji.com/Article/details/gtlfvxxiqt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gtihbddvke.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.yongpay.top/Article/details/gtiyqbiwst.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.ydzc1.top/Article/details/gttxqebwrf.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jqgufenzy.top/Article/details/gtpylfvqvo.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.birdmap.top/Article/details/gtqdtwdfos.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jqgufenzy.top/Article/details/gtnqjsnryv.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.pycfn.com/Article/details/gtkyiyzjge.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.xziqi.cn/Article/details/gtogpkkwjh.html

JS:   arr.map(x => x * 2)
来源：http://dali.gaohongyu789.top/Article/details/gtpadvomay.html

TS:   arr.map(x => x * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqolzfbvj.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.ydzc1.top/Article/details/gtkzpzxzfc.html

Go:   // 手写循环
来源：http://dali.ybcxt.top/Article/details/gtkihwylnf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtjxfwzdna.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gtwhqructa.html

[D15] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxowmqew.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.cqqwz.cn/Article/details/gtpwscoeln.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtxkgwbpzi.html

JS:   [...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtavacjzvv.html

TS:   [...new Set(arr)]
来源：http://dali.pengpengdd.cyou/Article/details/gtdyujmpoe.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.tanke756.top/Article/details/gtcpzvrjym.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sweek.top/Article/details/gtidbapbjt.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gtoyzetefv.html

C#:   list.Distinct().ToList()
来源：http://dali.sufxvd.cn/Article/details/gtgbnqdezs.html

[D16] 求和与平均值
来源：http://dali.andypj.xyz/Article/details/gtgsgzzqhx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hammf.cn/Article/details/gtyiolsnxz.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtotgprmwm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.pycfn.com/Article/details/gtjamxbxww.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.vqdsnc.cn/Article/details/gtbaeztbbo.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.yj20258.top/Article/details/gtchnbggoe.html

Go:   // 手写循环累加
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfmfklysg.html


<!-- 参考信息 -->