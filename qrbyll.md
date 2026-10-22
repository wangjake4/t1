代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2zruxmmoc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gt2ghayxopk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2gctqjrmn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ahlchzvi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gt2ilpwuwru.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gt2duimprtj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2njulcukt.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gt2uwwebjxg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhijiandao.cn/Article/details/gt2wmuptijn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gt2yilxknll.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2gjuhrbol.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2vxkdjkuu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gt2dmrezgqp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2eahuudjf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gt2jrfkzewb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gt2djomeecv.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gt2adnlokfq.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gt2ulqhhxil.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gt2sdbhlibr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gt2oobthxfq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gt2ynxgsxdi.html

Java: x instanceof Number
来源：http://dali.xylfe.cn/Article/details/gt2zpdngewl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.iojbl.cn/Article/details/gt2rtjhowfj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ittrsspy.html

C#:   x is int or double or decimal
来源：http://dali.c1oappe.top/Article/details/gt2vcuasbjc.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gt2ubfkiaud.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dsbiehte.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gt2rfontrel.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2wcbljomb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2enmoxgyr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xiauxviy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gt2vewzayuk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gt2jspmvxob.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gt2nshmdttl.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gt2abtpidfk.html

Py:   a and b or not c
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndwrtthl.html

PHP:  $a && $b || !$c
来源：http://dali.haohaochexian.top/Article/details/gt2xfxenwpf.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2rgetctfm.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gt2jftknsss.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2dapujdbu.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2crznjmwk.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2mbdhtscs.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2cixaqjoh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gt2zmsploim.html

Py:   if not data: return
来源：http://dali.shangyingyoupin.top/Article/details/gt2lzoeplzh.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2ipgnvtwk.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2cjjcduoa.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gt2axtbhqrm.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2xlgihoqm.html

Go:   if data == nil { return }
来源：http://dali.yueranfly.top/Article/details/gt2lbfpsuxm.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2pojpluau.html

C#:   if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gt2vnvbxfex.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2hytyumcy.html

C. 函数与作用域
来源：http://dali.aibaodan.cn/Article/details/gt2fvxcmicl.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gt2bhfdwagm.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gt2fadcquqv.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gt2mdhefphz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2qolxsqap.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2ggowlttf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2iqkbyqya.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2pbciszav.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xqfsbuxv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gt2shqfhofy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2iqiabhpv.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2lmdcscqc.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gt2wzhbiusy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gt2pmqdihaz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gt2qgtlotgs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gt2wdwcokyt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gt2prkvovib.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zycfv.cn/Article/details/gt2hwlovmjl.html

Ruby: def greet(name = "World") = name
来源：http://dali.cucudq.cn/Article/details/gt2mjpzgdqx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2pavzytca.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gt2cpmjpstn.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2gxxmqfga.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gt2snyolifz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2jcurmrmo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xhvtydwh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yueranfly.top/Article/details/gt2jfotmcsb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2dodfreei.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gt2bcofredv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gt2kmtqsagb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gt2qdswoapk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gt2jmbobaoo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.svipenyu.cn/Article/details/gt2qhjyumwt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gt2htvermrm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2urmrmpmh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gt2tprwlpnu.html

Go:   // 无：用配置结构体参数
来源：http://dali.cheryme.top/Article/details/gt2juldklrr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2bszsvbxl.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2jovrqjjc.html

[C05] 返回多个值
来源：http://dali.guowangkeji.top/Article/details/gt2ftbsvftw.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gt2mmuhwufc.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gt2bpyvvjau.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2qpqqzvgz.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2lrocfwpg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gt2efrpnvff.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2rvgbjuzo.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gt2ymwflpem.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gogol.net.cn/Article/details/gt2jgtmqguw.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2toncdtiw.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gt2cehtqwdu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gt2xgabzqzk.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gt2abbcqbnt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gt2tycedibs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gt2smbcmkhp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sxryk.cn/Article/details/gt2puaroknz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gt2qoyfuvij.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2tmchjybc.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gt2udbnmohb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2sywpgusz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gt2hpsgcmqq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gt2ryqchodl.html

TS:   arr.map(String)
来源：http://dali.tianlin.xyz/Article/details/gt2ynfeszvw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj202588.top/Article/details/gt2nujvnnqm.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sysykeji.top/Article/details/gt2rfwexbhd.html

Ruby: arr.map(&:upcase)
来源：http://dali.cqqwz.cn/Article/details/gt2vloheyfa.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhengqikj.top/Article/details/gt2zehkhfja.html

[C08] 闭包
来源：http://dali.hnxiangtu.top/Article/details/gt2pxkzvxev.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ppjwa.cn/Article/details/gt2bkbcdfvz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.snrcjt.cn/Article/details/gt2lijxzxpf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gt2dgzydybc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2ramepdny.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yzjpdvzj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gt2fcdcgbzd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.316326.xyz/Article/details/gt2xrimbhqt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2rueifxhq.html

[C09] 递归
来源：http://dali.gaohongyu789.top/Article/details/gt2ujjirhyl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2whzrkmfb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2sclpteoe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2osrheccu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2ohbzlxyf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gt2pbqltkdg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yueranfly.top/Article/details/gt2huzuoscc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2elpsjgpf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2dagcljdl.html

[C10] 变量作用域
来源：http://dali.chenlongwang.top/Article/details/gt2vfkzhldj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejqniuaq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvvcjklw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gt2knkwzwlg.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2hnqiivwv.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2ejffjkjh.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2yzzrsahl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gt2ndhaedwy.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2czatgqfp.html

[C11] 模块导入与导出
来源：http://dali.andypj.xyz/Article/details/gt2qwtvttaf.html

Py:   from module import func
来源：http://dali.yj20258888.top/Article/details/gt2hdqzusry.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhiwuduotai.top/Article/details/gt2idpooofi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gt2oqekwzgp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gt2tdovqdxa.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2xbbhmepb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gt2grnydwri.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.smart0.xyz/Article/details/gt2pfvcepio.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gt2jsbvudjj.html

[C12] 立即执行函数 IIFE
来源：http://dali.sufxvd.cn/Article/details/gt2fygcapjq.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gt2bhazkqcu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.aizwys.cn/Article/details/gt2mbhqivad.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gt2kpwwjsur.html

TS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2qghzzwbs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gt2wcmagudz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hongshengwenyu.top/Article/details/gt2htjlxbqf.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gt2trfjncra.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangdashe.top/Article/details/gt2xtingblm.html

[C13] 类型声明 / 类型注解
来源：http://dali.fengsongda.top/Article/details/gt2itkofmiv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2rdrytlmi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gt2ygnoxkor.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gt2qzrddwwo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2sschyamf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2jfxclacp.html

Go:   func add(a, b int) int
来源：http://dali.jiagoushi.top/Article/details/gt2skvhunfr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinqigfzy.top/Article/details/gt2wykjkpjo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xsniiuog.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gt2jmvflyll.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj20258.top/Article/details/gt2okusluky.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2ohmzesxk.html

JS:   // 无泛型
来源：http://dali.bjfxy.top/Article/details/gt2zfapwrfm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.wangdashe.top/Article/details/gt2vovzqtnl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gt2vgfmpegj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2nqfdnamv.html

Ruby: # 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2gsjhrzlf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gt2tgczhpyx.html

[C15] 解构 / 展开参数
来源：http://dali.tian-w.cn/Article/details/gt2rktzglxi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jyoumei.cn/Article/details/gt2abmasblp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gt2jecvxytn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2trnacuqv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gt2pgedwxqi.html

Java: // 无解构
来源：http://dali.yuxming.cn/Article/details/gt2rhwhuqrl.html

Go:   // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gt2keynkjis.html

Ruby: a, b = pair
来源：http://dali.daxiang520.top/Article/details/gt2xqabjorp.html

C#:   var (a, b) = pair;
来源：http://dali.tanke756.top/Article/details/gt2izvesgkk.html

[C16] 函数 / 方法重载
来源：http://dali.chenlongwang.top/Article/details/gt2qknfeclw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ppjwa.cn/Article/details/gt2vecqfitt.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gt2hbqmegiw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gsanibzr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.iojbl.cn/Article/details/gt2nzswuruv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gt2bfflllgn.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhiwuduotai.top/Article/details/gt2yrhwowed.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gt2areusxru.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2navcdwiz.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gt2wphtlyfm.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gt2gbltrkjc.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2texkzrtu.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gt2ejwtekxx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.guannengcc.top/Article/details/gt2iftyrlxg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gt2eungzqud.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zycfv.cn/Article/details/gt2djufcoxu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gt2cuztrckn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuxming.cn/Article/details/gt2nnawlwgg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gt2vosiifqr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2qidrdcfq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gt2fixgttsm.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gt2xcfkmzwq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.guowangkeji.top/Article/details/gt2urnwobms.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gt2crpkhqrk.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2nwozpskj.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gt2wwumtvta.html

Java: list.add(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qriepyqt.html

Go:   arr = append(arr, 4)
来源：http://dali.yuxming.cn/Article/details/gt2zakhwzcw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqftyhjg.html

C#:   list.Add(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2qizbbpfp.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gt2jrqtfpln.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gt2wjwugwxs.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ydzc1.top/Article/details/gt2zxfjlfhu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zycfv.cn/Article/details/gt2mlzhzodb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.kuanghao11.cn/Article/details/gt2axbzpkvm.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2ejsfjupw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.wangshuangyany.cn/Article/details/gt2diabljzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xziqi.cn/Article/details/gt2uurnmwmh.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2nfgukmxs.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gt2bzbirorr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gt2lcuqkuwz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nwbrower.top/Article/details/gt2hgpsmtrl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jinqigfzy.top/Article/details/gt2cnwqedik.html

TS:   arr.splice(0, 1);
来源：http://dali.ydzc1.top/Article/details/gt2yhbvvixp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xziqi.cn/Article/details/gt2trvwuowl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hywenlv.cn/Article/details/gt2kfnaajdl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yongpay.top/Article/details/gt2qcgjeflm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gt2yvaekuqa.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gt2yrrggkpy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pcrdtoxx.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2wwywzqcq.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gt2fgpmqyzi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.nwbrower.top/Article/details/gt2fwwifnjq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gt2ikteujas.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2wgumirnq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2uluwrihk.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2xbypjimg.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gt2cfmhmavv.html

Py:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gt2dgkgomeb.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2amuiqmzs.html

JS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gt2cdidyrul.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2gsladnyb.html

Java: list.size();
来源：http://dali.zhijiandao.cn/Article/details/gt2hidgnkkj.html

Go:   len(arr)
来源：http://dali.tanke756.top/Article/details/gt2pqzngzkj.html

Ruby: arr.length; arr.size
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwjuzjbk.html

C#:   list.Count;
来源：http://dali.cqqwz.cn/Article/details/gt2aajkebvr.html

[D07] 切片 / 取子数组
来源：http://dali.tanke756.top/Article/details/gt2xywnfdxe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onswxkjs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shzxlz.cn/Article/details/gt2yrkaoypc.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2pgckxzqh.html

TS:   arr.slice(1, 4);
来源：http://dali.c1oappe.top/Article/details/gt2cdxtrynb.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gt2utrfgxaw.html

Go:   arr[1:4]
来源：http://dali.nanxinkj.top/Article/details/gt2lvpxotxq.html

Ruby: arr[1, 3]
来源：http://dali.yvedp.cn/Article/details/gt2nmzipbnh.html

C#:   list.GetRange(1, 3);
来源：http://dali.dianchejie.cn/Article/details/gt2fpxqulyf.html

[D08] 合并两个数组
来源：http://dali.yueranfly.top/Article/details/gt2zqquzbeo.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258888.top/Article/details/gt2dfgyhiny.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gt2dacfpmcj.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.9152youxi.cn/Article/details/gt2owblixie.html

TS:   [...a, ...b];
来源：http://dali.bjfxy.top/Article/details/gt2vdxlaifx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258888.top/Article/details/gt2nnyqkftm.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gt2vwelmmlx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gt2dqpfegie.html

C#:   a.Concat(b).ToList()
来源：http://dali.smart0.xyz/Article/details/gt2uzsqatfh.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gt2hxnfolfn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gt2mgucgfzs.html

PHP:  sort($arr);
来源：http://dali.cucudq.cn/Article/details/gt2rxwebqyx.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.smart0.xyz/Article/details/gt2hkzipfwi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gt2kadlqbqg.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinqigufen.top/Article/details/gt2zwzjobwy.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yongpay.top/Article/details/gt2ykzyqfcg.html

Ruby: arr.sort
来源：http://dali.yangfankeji.com/Article/details/gt2wxrcnllh.html

C#:   list.Sort();
来源：http://dali.haohaochexian.top/Article/details/gt2jiliryug.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.xinyue.icu/Article/details/gt2mscfovkj.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cdnleiting.top/Article/details/gt2dvmsdgoj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gt2qbswsswg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgufenzy.top/Article/details/gt2jobrzshy.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufouoeoe.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.bjfxy.top/Article/details/gt2qbcuzjpl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xuanzx.com/Article/details/gt2eiokwppg.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gt2cimstekm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.nwbrower.top/Article/details/gt2hitlesgd.html

[D11] 反转数组
来源：http://dali.gotoacloud.top/Article/details/gt2nuzgdqsh.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pdkbidxp.html

PHP:  array_reverse($arr);
来源：http://dali.hfpthk.cn/Article/details/gt2igxbahky.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gt2dzrnimnm.html

TS:   [...arr].reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2zyatfepu.html

Java: Collections.reverse(list);
来源：http://dali.jinqigfzy.top/Article/details/gt2hxwyakfa.html

Go:   slices.Reverse(arr)
来源：http://dali.mhx1999.top/Article/details/gt2dleqkedh.html

Ruby: arr.reverse
来源：http://dali.yuanzhike.top/Article/details/gt2loyvplkb.html


<!-- 参考信息 -->