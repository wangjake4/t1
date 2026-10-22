代发 wailian999

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gt2wjfpcjdv.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gt2hbhlgxsa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gt2oatqggay.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gt2xwkoyski.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2ibbzvtlp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2mrvqepuc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gaohongyu789.top/Article/details/gt2hallipoc.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gt2vplfsfst.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gt2mcflhbwd.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2vqpvigmk.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gt2ycedxanp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gt2olytxgow.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gt2tlqjwcie.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gt2wtkegwfk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvrsbvxt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmzazawj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sufxvd.cn/Article/details/gt2kyagvfeg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gt2mbekkavf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gt2ullbffrb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ffegttwr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzixfjyc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2gdpbrwgv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj202588.top/Article/details/gt2spagzwut.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shangyingyoupin.top/Article/details/gt2wsqbsyop.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mfbrhmjm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2fuqnueke.html

C#:   f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2unhmheeq.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gt2npofkfgf.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2lkhksjny.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gt2jekguqor.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gt2grzuudoj.html

TS:   return { a, b };
来源：http://dali.yonumen.top/Article/details/gt2dtwsslcl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gt2lngrsyyg.html

Go:   return a, b
来源：http://dali.andypj.xyz/Article/details/gt2lsyhiqqj.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2unnmqfrj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gt2vgcowhqn.html

[C06] 匿名函数 / lambda
来源：http://dali.xuanzx.com/Article/details/gt2qhzqwmtr.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gt2fpmdmlbe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gt2oclsnuie.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2pvaxrmlz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2qkfwbzsh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yueranfly.top/Article/details/gt2cfbhpkia.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gt2tivuvdwt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnplhyso.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2xgiztsba.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gt2sfnzibxk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangdashe.top/Article/details/gt2wlfkoxpk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gt2dclmpzxd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2bkjdkaku.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gt2isiljyjn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gt2etxonqnh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.pengpengdd.cyou/Article/details/gt2unfowppo.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gt2vfgrwegc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gt2yslopliu.html

[C08] 闭包
来源：http://dali.havefunace.top/Article/details/gt2tcezylth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhiwuduotai.top/Article/details/gt2zfekhlip.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gt2gffcuxfb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2ariohkfg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gt2bwnxabed.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2dwykyiuv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gt2fdsqjkyz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gt2dzbgetex.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxxyhcdb.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2njhdunaf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2acacxysh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yuxming.cn/Article/details/gt2cstiuggz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2sbntqozp.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkkmkprv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuanzx.com/Article/details/gt2lqygbjgp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gt2tghkcdxo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gt2ndpqdurt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cashguo.top/Article/details/gt2vjvidirr.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gt2lassospi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2elqnhhtx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2cejqfjge.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yonumen.top/Article/details/gt2olppgjtw.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gt2omgclcek.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2ewkxajdm.html

Go:   花括号块级作用域
来源：http://dali.zhixingplan.top/Article/details/gt2xsosgwoc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgfzy.top/Article/details/gt2boocebnt.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gt2ljujhbvm.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2jexehbba.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gt2kvikgeoi.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vmebueom.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2prpesdpj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigfzy.top/Article/details/gt2matzhcqf.html

Java: import java.util.List;
来源：http://dali.cqqwz.cn/Article/details/gt2iegjkhsa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qjizyewm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hnqzz.top/Article/details/gt2yxgdctum.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gt2fqmpahri.html

[C12] 立即执行函数 IIFE
来源：http://dali.shuidangran.top/Article/details/gt2stuhwcfc.html

Py:   (lambda: print("run"))()
来源：http://dali.zhoulong.xyz/Article/details/gt2lxelwvva.html

PHP:  (function () { echo "run"; })();
来源：http://dali.kuanghao11.cn/Article/details/gt2gccfxrwd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gt2khgpkhfg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2mydjoiyi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gt2ghncjhfo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gt2wcsnecqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.ybcxt.top/Article/details/gt2gesfttei.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jlsjyb.cn/Article/details/gt2bgwokddc.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gt2rmftrqxx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2mrcyqxfu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gt2gujvmvmh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gt2dgwdvudq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2gtdjiwls.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2cjmegocf.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2owyoeeml.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gt2umtflqmj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gt2txlyjvxr.html

[C14] 泛型函数
来源：http://dali.andypj.xyz/Article/details/gt2tkaehvca.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gt2gotmylyt.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ftxlwlip.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gt2cpdligtm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gt2aryhgfjh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gt2omgmeemw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnfbzrat.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2ypjoairq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.meibo888.top/Article/details/gt2bfcabtny.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gt2tmgtdlfw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.andypj.xyz/Article/details/gt2fbastmcm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2jxvoutfm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gt2dmasaech.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2kydnbayx.html

Java: // 无解构
来源：http://dali.hysaishi.cn/Article/details/gt2rkvftysm.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gt2bwmizefx.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gt2qdgfstpf.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gt2tspcoipc.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2wsgngsnp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgufenzy.top/Article/details/gt2vuajhcuk.html

PHP:  // 无重载
来源：http://dali.chenjidiqi.icu/Article/details/gt2hgikegde.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gt2jqdcsrye.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gt2cewqxkxn.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gt2gydzdqfb.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgfzy.top/Article/details/gt2moowdnvk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj202588.top/Article/details/gt2nlzgfsfh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gt2mquoutji.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2wvysvtkp.html

D. 数组 / 列表 / 集合
来源：http://dali.316326.xyz/Article/details/gt2dajyzjqs.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2whbteoye.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gt2dasjaghl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhiwuduotai.top/Article/details/gt2gdmktdes.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tianlin.xyz/Article/details/gt2fblpiofa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2ikixzlrc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gt2xfybswiv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuetiantiany.cn/Article/details/gt2hguspzvp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gt2erzniudm.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gt2mpqvkfvi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tanke756.top/Article/details/gt2hbsplkuw.html

[D02] 追加元素到末尾
来源：http://dali.yj20258888.top/Article/details/gt2htffmxur.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cudvgaag.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.tianlin.xyz/Article/details/gt2fdipgydq.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2jenszucr.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gt2takpdvfh.html

Java: list.add(4);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cgwpfwrq.html

Go:   arr = append(arr, 4)
来源：http://dali.tianlin.xyz/Article/details/gt2zxtgdwhg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gt2clphbmkm.html

C#:   list.Add(4);
来源：http://dali.birdmap.top/Article/details/gt2kgpeetdg.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gt2aqjtodhi.html

Py:   arr.insert(0, 0)
来源：http://dali.ybcxt.top/Article/details/gt2lefsvavl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fzigprrl.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhoulong.xyz/Article/details/gt2edtngztr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjiiukke.html

Java: list.add(0, 0);
来源：http://dali.fzhhl.top/Article/details/gt2xmrfdmev.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gt2fsjxtuxc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgfzy.top/Article/details/gt2hiztpxfa.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2gklexdhv.html

[D04] 删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2xicueell.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnxiangtu.top/Article/details/gt2qmblfwfq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dnnsegfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lzhpdbyr.html

TS:   arr.splice(0, 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2sxmywlwd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gt2tbyvpyxv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gt2fwvocwma.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gt2sxfjhiay.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gt2nfuycqpy.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gt2pyiamdyn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gt2mptfjhyw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenlongwang.top/Article/details/gt2kbsgnmcv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2gkgxvfav.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gt2zvzvoelo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.pycfn.com/Article/details/gt2klngrvwn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xziqi.cn/Article/details/gt2atchvexw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gt2sweqjhan.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xinyue.icu/Article/details/gt2quzzvidp.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gt2yomjqpsy.html

Py:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gt2pmqfvxpc.html

PHP:  count($arr);
来源：http://dali.jinqigufen.top/Article/details/gt2lprbfwej.html

JS:   arr.length
来源：http://dali.yuanzhike.top/Article/details/gt2dtophfpj.html

TS:   arr.length
来源：http://dali.tian-w.cn/Article/details/gt2dvrlonei.html

Java: list.size();
来源：http://dali.snrcjt.cn/Article/details/gt2hmifhsem.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2xcyrgvfz.html

Ruby: arr.length; arr.size
来源：http://dali.havefunace.top/Article/details/gt2bvyxxizj.html

C#:   list.Count;
来源：http://dali.havefunace.top/Article/details/gt2thlivnsv.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gt2dxdvemev.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gt2zxofpadd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2wqhnvqul.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2xjdezmxu.html

TS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2dnospjzd.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2igimwxlm.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gt2ejydbgyu.html

Ruby: arr[1, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2ikdubomq.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ufvnayzm.html

[D08] 合并两个数组
来源：http://dali.tianlin.xyz/Article/details/gt2ssdcfrkg.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2npqjdqrg.html

PHP:  array_merge($a, $b);
来源：http://dali.yangfankeji.com/Article/details/gt2cjfqatix.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nanxinkj.top/Article/details/gt2hmowvxmh.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gt2lcntmqhz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.redwolf501.top/Article/details/gt2cwgghskz.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2ftcyiqat.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shzxlz.cn/Article/details/gt2bkfyexxe.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj202588.top/Article/details/gt2iltexxhz.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gt2dabnnzwq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jqgfzy.top/Article/details/gt2qvnkktvu.html

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2muavgobi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sysykeji.top/Article/details/gt2atwptzzw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hammf.cn/Article/details/gt2jejwecce.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.smart0.xyz/Article/details/gt2peuqpepb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.daxiang520.top/Article/details/gt2tqmgblsy.html

Ruby: arr.sort
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2heveylpu.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gt2loylxrpy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.birdmap.top/Article/details/gt2nwptwfqk.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vjoowmch.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gt2cwktmemp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gt2kqpufgin.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.mhx1999.top/Article/details/gt2fgbefflv.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gt2mhettllp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.ppjwa.cn/Article/details/gt2zaqljwkd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.xinyue.icu/Article/details/gt2bthrwtod.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xuanzx.com/Article/details/gt2bfyifgde.html

[D11] 反转数组
来源：http://dali.tanke756.top/Article/details/gt2wuhybdyg.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ydzc1.top/Article/details/gt2kyuehhye.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2zvfyfkny.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zycfv.cn/Article/details/gt2rsauzloe.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2ruhcncgl.html

Java: Collections.reverse(list);
来源：http://dali.daxiang520.top/Article/details/gt2sgemwhkg.html

Go:   slices.Reverse(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2ntzextqv.html

Ruby: arr.reverse
来源：http://dali.ybcxt.top/Article/details/gt2njqhelmz.html

C#:   list.Reverse();
来源：http://dali.jqgfzy.top/Article/details/gt2ldxrtdmk.html

[D12] 查找元素下标
来源：http://dali.jyoumei.cn/Article/details/gt2yvtsdbfu.html

Py:   arr.index(x);  x in arr
来源：http://dali.andypj.xyz/Article/details/gt2shsgjjgt.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.xylfe.cn/Article/details/gt2keoyvfjm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.c1oappe.top/Article/details/gt2rjbfnhoe.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.meibo888.top/Article/details/gt2mjbdmbnz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.cheryme.top/Article/details/gt2lvisldiv.html

Go:   slices.Index(arr, x)
来源：http://dali.xuanzx.com/Article/details/gt2bferhmco.html

Ruby: arr.index(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmhyqrai.html

C#:   list.IndexOf(x);
来源：http://dali.gogol.net.cn/Article/details/gt2rjnrxfqe.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gzhubu.top/Article/details/gt2cxdwikxx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.pycfn.com/Article/details/gt2cwlnrldl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iuzlmlct.html

JS:   arr.filter(x => x > 3)
来源：http://dali.c1oappe.top/Article/details/gt2ihpspozv.html

TS:   arr.filter(x => x > 3)
来源：http://dali.daria6918.cn/Article/details/gt2wqtwsizo.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uyyejfsl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gogol.net.cn/Article/details/gt2qaokfpyu.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.hywenlv.cn/Article/details/gt2zwjppjrl.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.gzhubu.top/Article/details/gt2frtdvknp.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tianlin.xyz/Article/details/gt2tpehxayn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2tjkljrzb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bcsvyixh.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gt2dpknbxuz.html

TS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2hctfmrnf.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gaohongyu789.top/Article/details/gt2eldlscks.html

Go:   // 手写循环
来源：http://dali.zhixingplan.top/Article/details/gt2middaihm.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2bdfobdij.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ojhxubqq.html

[D15] 去重
来源：http://dali.feifeiyinyue.top/Article/details/gt2dimsaiee.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gt2mchqovbu.html

PHP:  array_unique($arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zeumwccz.html

JS:   [...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gt2funbttma.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2owtjlpuk.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnqzz.top/Article/details/gt2rjkprusf.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.kuanghao11.cn/Article/details/gt2nlfaugjm.html

Ruby: arr.uniq
来源：http://dali.jqgfzy.top/Article/details/gt2vpaljwvq.html

C#:   list.Distinct().ToList()
来源：http://dali.andypj.xyz/Article/details/gt2qkhddicy.html

[D16] 求和与平均值
来源：http://dali.tian-w.cn/Article/details/gt2aafpilpq.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.kuanghao11.cn/Article/details/gt2ccrfjlpc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.gotoacloud.top/Article/details/gt2tysfrovz.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.cqqwz.cn/Article/details/gt2syybyfxv.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gt2ipnyapvw.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gotoacloud.top/Article/details/gt2vnjnalqk.html

Go:   // 手写循环累加
来源：http://dali.ehwqpu.com/Article/details/gt2kssnczzm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sweek.top/Article/details/gt2ocssshho.html

C#:   list.Sum();  list.Average()
来源：http://dali.jyoumei.cn/Article/details/gt2pfamyzmh.html

[D17] 最大值与最小值
来源：http://dali.ydzc1.top/Article/details/gt2djvtbfvx.html

Py:   max(arr);  min(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gt2jzaefpsh.html

PHP:  max($arr);  min($arr);
来源：http://dali.zhoulong.xyz/Article/details/gt2rjepovjr.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2scevekkw.html

TS:   Math.max(...arr);
来源：http://dali.cqqwz.cn/Article/details/gt2qglgfwnr.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcmjosxf.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.fzhhl.top/Article/details/gt2bfyveoht.html

Ruby: arr.max;  arr.min
来源：http://dali.nwbrower.top/Article/details/gt2rnafvdsd.html

C#:   list.Max();  list.Min()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cmtaehvi.html

[D18] 扁平化嵌套数组
来源：http://dali.xinyue.icu/Article/details/gt2ktbxycxx.html

Py:   [y for xs in nested for y in xs];  sum(nested, [])
来源：http://dali.hywenlv.cn/Article/details/gt2sisvbvbb.html

PHP:  array_merge(...$nested);
来源：http://dali.hammf.cn/Article/details/gt2ikcghvtk.html

JS:   nested.flat();  nested.flat(Infinity)
来源：http://dali.hywenlv.cn/Article/details/gt2lfnsghrt.html

TS:   nested.flat();
来源：http://dali.cqqwz.cn/Article/details/gt2ymhbfvfp.html

Java: nested.stream().flatMap(List::stream).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbzqxehq.html

Go:   // 手写双层循环
来源：http://dali.tanke756.top/Article/details/gt2vsjvnrtq.html

Ruby: nested.flatten
来源：http://dali.ybcxt.top/Article/details/gt2jpgmdhuq.html

C#:   nested.SelectMany(x => x).ToList()
来源：http://dali.yj20258.top/Article/details/gt2hvamrgmg.html


<!-- 参考信息 -->