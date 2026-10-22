代发 wailian999

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gt2pioteakb.html

PHP:  if (!$data) { return; }
来源：http://dali.gzhubu.top/Article/details/gt2rtazzcup.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2qvtzprbp.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gt2fmxaifha.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gt2llutiwof.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gt2ucunuwhs.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gt2ehhzuisa.html

C#:   if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gt2miasqijv.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2wktfczqn.html

C. 函数与作用域
来源：http://dali.hnqzz.top/Article/details/gt2japzkgch.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2fzvhwbej.html

[C01] 定义函数
来源：http://dali.yanxiufei.cn/Article/details/gt2sxtrwhnc.html

Py:   def add(a, b): return a + b
来源：http://dali.yueranfly.top/Article/details/gt2klnpzzwk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2qzwejmhj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bkrgcsep.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2efisnifl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rwechwfg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gt2zboqftmy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gt2bkdmacra.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2nxdihprg.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gt2qhyiacpb.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2fdpvelai.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fzhhl.top/Article/details/gt2tasheidg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gt2qhddmdhe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2cpphaupq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gt2lostbepe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tareuzvf.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gt2ztxamhlm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhijiandao.cn/Article/details/gt2adcbkydi.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2srqyuxps.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2vxsmaxaf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gt2bosaguon.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dxecychq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gt2vageutbw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gt2qatuldcy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuanzx.com/Article/details/gt2itpbwvyd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnqzz.top/Article/details/gt2wfmjgvym.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gt2rxynihcr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2qrmdzpzz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gt2ndacciwz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gt2kdyczirx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2hdhgaehp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2omniszjx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ybcxt.top/Article/details/gt2tzytzpgl.html

Go:   // 无：用配置结构体参数
来源：http://dali.xziqi.cn/Article/details/gt2xcykrnvh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2jarknzel.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2ehlyexpb.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gt2hwracibn.html

Py:   return a, b
来源：http://dali.ivvv.top/Article/details/gt2ledfbosx.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gt2zfghplft.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gt2xwgycxxy.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2wlfohoqc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gt2vrwoioju.html

Go:   return a, b
来源：http://dali.tian-w.cn/Article/details/gt2rfcrtrrc.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2qsdcleyp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2jhicsghq.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gt2rmpbyahs.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gt2xmevbvoe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gt2kaujaqoi.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2vntirgef.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2ntkmtypq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gt2elyaqnyk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gt2jzelhlkr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gt2jnxyvmix.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2antmgylx.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gt2bvrytdnv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gt2nnrxyqwx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gt2grxlzkil.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gt2ufeedeiv.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gt2nalvcxtz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guannengcc.top/Article/details/gt2wdkiwumz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gt2gqaqiprp.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2sbpalmjv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258888.top/Article/details/gt2uswywvbp.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gt2akuqqyru.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gt2nrkjwcno.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hysaishi.cn/Article/details/gt2tkvdxjxu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gt2qzwkshrz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qsdoiist.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gt2qkrtwkzf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nwbrower.top/Article/details/gt2kjkbdvnd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ouestwmr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2crysyhgp.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gt2sodcothq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gt2mftgfibr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.birdmap.top/Article/details/gt2ktxeftnf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2ymvxaqez.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2kkjibxoy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gt2privsyqp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2bwuycskg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.mhx1999.top/Article/details/gt2ouqxdgyb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2enjpeiuq.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gt2hdssazio.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2mgrkxank.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gt2ohpdsoow.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gt2chwldnry.html

TS:   同 JS
来源：http://dali.xylfe.cn/Article/details/gt2entyniwn.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2jxbjzixq.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gt2jbvyyvzm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qbfmlzgf.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2qiomczat.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gt2kletqfkw.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gt2ltbqwbgi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ydzc1.top/Article/details/gt2bspqkzzo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2ucohyicr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tianlin.xyz/Article/details/gt2ymqjrwoi.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gt2xxbbooca.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gt2ktsirret.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gt2xrgzxaly.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2ogtosxee.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gt2minitwtl.html

Py:   (lambda: print("run"))()
来源：http://dali.gaohongyu789.top/Article/details/gt2ilgkfnst.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gt2nzkhsahi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gt2pexwesgv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2fflcbjeb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gt2antnzmbc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.andypj.xyz/Article/details/gt2lvrsdboz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gt2bhayrayp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shzxlz.cn/Article/details/gt2acelluym.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gt2yjpxniyw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fzhhl.top/Article/details/gt2upyovfit.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2nptziwvb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gt2yhgvwrwj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikxbbqhb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2futmsfqf.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gt2fanwjaeo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gt2brwhyyuq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rkcddaec.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gt2zaycxssk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhoulong.xyz/Article/details/gt2mzrdcsmy.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2gbzilfsj.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2thzsxydp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpkvmbnj.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gt2ycxeukzx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gt2zhcvwxtc.html

Ruby: # 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2fbfuzldj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwysvsdh.html

[C15] 解构 / 展开参数
来源：http://dali.kuanghao11.cn/Article/details/gt2nsbmrejp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj202588.top/Article/details/gt2kceppcny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2gmayvugi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gt2clwoaczp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2qxywfica.html

Java: // 无解构
来源：http://dali.pycfn.com/Article/details/gt2ndpasout.html

Go:   // 无解构
来源：http://dali.daria6918.cn/Article/details/gt2nnhiugiu.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gt2ujrxpqug.html

C#:   var (a, b) = pair;
来源：http://dali.meibo888.top/Article/details/gt2qzncedhe.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gt2rukpbtsk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gt2alabnoaw.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gt2veammowk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangshuangyany.cn/Article/details/gt2mzcwmwvf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gt2ftelpbxa.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdbjrccu.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gt2rkgcdfvu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gt2gmfgfzfw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hfpthk.cn/Article/details/gt2rkasjwqb.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2srvksirw.html

D. 数组 / 列表 / 集合
来源：http://dali.zhijiandao.cn/Article/details/gt2entzvzhj.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2cumgpyey.html

[D01] 创建数组 / 列表
来源：http://dali.fzhhl.top/Article/details/gt2lebwqoyc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.kuanghao11.cn/Article/details/gt2etvevscx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2yokdxhic.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sweek.top/Article/details/gt2hxlvqpeu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jpxqgxxc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.smart0.xyz/Article/details/gt2wjiidgfy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gt2dhpxhgga.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sweek.top/Article/details/gt2tgqqmiwz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenlongwang.top/Article/details/gt2tjratvwl.html

[D02] 追加元素到末尾
来源：http://dali.hammf.cn/Article/details/gt2rqlscqhx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yangfankeji.com/Article/details/gt2jdwuzovy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gt2keaophjh.html

JS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gt2solyracg.html

TS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2idqhtojw.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gt2lpyfqpop.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gt2jorzdcuf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jianghu66.top/Article/details/gt2rokppoyl.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2wyommzth.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gt2qnnvymid.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gt2zszavasg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gt2muojzklu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gt2rbumbuoy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjydewxv.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2kqcqveex.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2nphdouma.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjbwuucx.html

C#:   list.Insert(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2rnsflbhc.html

[D04] 删除元素
来源：http://dali.jianghu66.top/Article/details/gt2hwyqfqht.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.birdmap.top/Article/details/gt2bowwhept.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yonumen.top/Article/details/gt2mzadclhr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gt2uublvnqb.html

TS:   arr.splice(0, 1);
来源：http://dali.c1oappe.top/Article/details/gt2srzssekt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.daxiang520.top/Article/details/gt2tnhsxezi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yj202588.top/Article/details/gt2lwczrxxs.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gt2gxdxmchc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gt2giacypyy.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gt2gpplthyx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2uiskkgmh.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pwgcpplv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ppjwa.cn/Article/details/gt2njbffood.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkurkbqt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.bjfxy.top/Article/details/gt2ssuhclpx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gt2tmentawn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gt2yyklcuar.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj202588.top/Article/details/gt2pasgdsun.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gt2btyviocm.html

Py:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gt2sjupnsig.html

PHP:  count($arr);
来源：http://dali.xinyue.icu/Article/details/gt2msyiymjl.html

JS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gt2tiwbjycy.html

TS:   arr.length
来源：http://dali.cheryme.top/Article/details/gt2fjueeoqx.html

Java: list.size();
来源：http://dali.zhengqikj.top/Article/details/gt2gjkjcabk.html

Go:   len(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utcevfjl.html

Ruby: arr.length; arr.size
来源：http://dali.zdqjudy.top/Article/details/gt2tndsarum.html

C#:   list.Count;
来源：http://dali.mhx1999.top/Article/details/gt2fqclwajr.html

[D07] 切片 / 取子数组
来源：http://dali.mhx1999.top/Article/details/gt2ebzovupw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hfpthk.cn/Article/details/gt2bbzzgxpo.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yanxiufei.cn/Article/details/gt2eeoganzj.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gt2esncqsqm.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gt2nmasqafd.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gt2ysssdzca.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gt2gruxzoxh.html

Ruby: arr[1, 3]
来源：http://dali.birdmap.top/Article/details/gt2jablsnxh.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gt2lektdapc.html

[D08] 合并两个数组
来源：http://dali.vqdsnc.cn/Article/details/gt2tizlmxvn.html

Py:   a + b;  a.extend(b)
来源：http://dali.guannengcc.top/Article/details/gt2dzchcczy.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gt2aycydgxk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gt2lqnolqvg.html

TS:   [...a, ...b];
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofttjsmy.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkmigkcn.html

Go:   append(a, b...)
来源：http://dali.jinqigufen.top/Article/details/gt2xmkqjblt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pengpengdd.cyou/Article/details/gt2dhyggmme.html

C#:   a.Concat(b).ToList()
来源：http://dali.redwolf501.top/Article/details/gt2uatqyvte.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gt2dycloixt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fijpyvxc.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2fvzhbnqp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shuidangran.top/Article/details/gt2cawaltys.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2zmrnbnpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xziqi.cn/Article/details/gt2oanynegg.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xziqi.cn/Article/details/gt2rrndekkb.html

Ruby: arr.sort
来源：http://dali.yanxiufei.cn/Article/details/gt2ffizjcpl.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gt2iodgitub.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenlongwang.top/Article/details/gt2ktlvjnqh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wxlqjorv.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gt2vcpnbzuo.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aizwys.cn/Article/details/gt2hkbiehtk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ehwqpu.com/Article/details/gt2iogceuri.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.wangshuangyany.cn/Article/details/gt2vknrwfma.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxjvpybx.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yongpay.top/Article/details/gt2rrughhys.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.tanke756.top/Article/details/gt2qrxqhmjk.html

[D11] 反转数组
来源：http://dali.yuanzhike.top/Article/details/gt2upkcifze.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.gaohongyu789.top/Article/details/gt2vyzqogbc.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2crctjjru.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wpdaiejy.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gt2qiyqaorl.html

Java: Collections.reverse(list);
来源：http://dali.hysaishi.cn/Article/details/gt2prdpisoo.html

Go:   slices.Reverse(arr)
来源：http://dali.yj20258888.top/Article/details/gt2vsdckkab.html

Ruby: arr.reverse
来源：http://dali.gzhubu.top/Article/details/gt2uefnaqjo.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uqjrhtvj.html

[D12] 查找元素下标
来源：http://dali.hywenlv.cn/Article/details/gt2idvytvmw.html

Py:   arr.index(x);  x in arr
来源：http://dali.ybcxt.top/Article/details/gt2wqzlfmyu.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sufxvd.cn/Article/details/gt2lfxrrpwj.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2yduibtbz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.snrcjt.cn/Article/details/gt2mnqeqaaq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.haohaochexian.top/Article/details/gt2bbasvxnd.html

Go:   slices.Index(arr, x)
来源：http://dali.yj202588.top/Article/details/gt2qaezbcke.html

Ruby: arr.index(x)
来源：http://dali.ivvv.top/Article/details/gt2gigiunpj.html

C#:   list.IndexOf(x);
来源：http://dali.aizwys.cn/Article/details/gt2rdlrltyg.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yvedp.cn/Article/details/gt2tqdtrgru.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2shavhzgl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.jiagoushi.top/Article/details/gt2gpzpllzx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqxnajcb.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangdashe.top/Article/details/gt2tjmsufak.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2ebyxsubt.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2knceeljt.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.cucudq.cn/Article/details/gt2trqdltsv.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.dianchejie.cn/Article/details/gt2jqkbnemh.html

[D14] 映射转换（每个元素变形）
来源：http://dali.jinqigufen.top/Article/details/gt2rmhvmxgn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.sxryk.cn/Article/details/gt2crixbkqu.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yvedp.cn/Article/details/gt2rqtgpvuj.html

JS:   arr.map(x => x * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2itjqdwhx.html

TS:   arr.map(x => x * 2)
来源：http://dali.yonumen.top/Article/details/gt2gcpzpumk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajeqpvdg.html

Go:   // 手写循环
来源：http://dali.vqdsnc.cn/Article/details/gt2ilkvzedh.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gt2icckwjnt.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.chenjidiqi.icu/Article/details/gt2lppkbsfx.html

[D15] 去重
来源：http://dali.gaohongyu789.top/Article/details/gt2fieuxjzc.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.xuetiantiany.cn/Article/details/gt2yrnjhtnu.html

PHP:  array_unique($arr);
来源：http://dali.cheryme.top/Article/details/gt2zfudpfob.html

JS:   [...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gt2xblinoyq.html

TS:   [...new Set(arr)]
来源：http://dali.ehwqpu.com/Article/details/gt2mqxndelp.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.nanxinkj.top/Article/details/gt2ugvfhhgw.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.cqqwz.cn/Article/details/gt2vmavtoas.html

Ruby: arr.uniq
来源：http://dali.xuetiantiany.cn/Article/details/gt2ggnlmzue.html

C#:   list.Distinct().ToList()
来源：http://dali.ybcxt.top/Article/details/gt2eoqmbggl.html

[D16] 求和与平均值
来源：http://dali.cqqwz.cn/Article/details/gt2lpqttwmo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gt2skzbujcy.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ehwqpu.com/Article/details/gt2wtavnpbb.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.snrcjt.cn/Article/details/gt2dggpredq.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohddamac.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xylfe.cn/Article/details/gt2zyktwedw.html

Go:   // 手写循环累加
来源：http://dali.zycfv.cn/Article/details/gt2allpkllp.html


<!-- 参考信息 -->