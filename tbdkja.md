代发 wailian999

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gt2dxmfvkcc.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gt2bvivkwob.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gt2qtfjxlyj.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zhfcvrga.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2swzzepom.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gt2svoqqwyo.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gt2gfawhrut.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gt2jblqcrhl.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2ufbbnerv.html

C. 函数与作用域
来源：http://dali.zhiwuduotai.top/Article/details/gt2jnamfvad.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gjqtvjjy.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gt2ixsmduyu.html

Py:   def add(a, b): return a + b
来源：http://dali.zycfv.cn/Article/details/gt2mnrsxmdq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gt2ddfkslbr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2rmwtuprc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2xguxadzy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ybiiqvqu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zjavrwkg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gt2mcobcxib.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2uiairtju.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gt2ifogjlgh.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gt2cmtyegml.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2judnolul.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojoiknbq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gt2oglxhhkh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gt2lkgdcbqt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xylfe.cn/Article/details/gt2yrrhptyv.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2enolqiou.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2uqigqyei.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gt2lbqmlwat.html

Py:   def total(*args): return sum(args)
来源：http://dali.gzhubu.top/Article/details/gt2ickeneok.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuanzhike.top/Article/details/gt2kccbrlcj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2ghszdpmx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gaohongyu789.top/Article/details/gt2ymaphxse.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gt2vpctyfia.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2dndfbdwr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gt2lwpnqvvx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gt2yirevjad.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2aabsnbdx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhixingplan.top/Article/details/gt2ehrkpxog.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2recastvv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2hkqxyhpj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gt2zkdqrtce.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2kuhnfweo.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2sqnfiggk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2veiahico.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2naazcnvi.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gt2pyreoezk.html

Py:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2ibdvjrnm.html

PHP:  return [$a, $b];
来源：http://dali.aizwys.cn/Article/details/gt2kmtsobvq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2ggcjpypd.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gt2qouzjkgg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gt2oraiftly.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2rogkrcnm.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gt2osllldal.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2thvmpukr.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gt2qzxmrtrk.html

Py:   square = lambda x: x * x
来源：http://dali.sxryk.cn/Article/details/gt2fgaaqeco.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yhzbpfpw.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2ksxrzmyc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2chzlopky.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2ghnlsedw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2bfumzrbw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gt2npprczab.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2gydqqbmp.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gt2banrxlrq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2ihuyzyrk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gt2dxvrzowe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2kjscohjm.html

TS:   arr.map(String)
来源：http://dali.fengsongda.top/Article/details/gt2iuphonkx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2mypwiykl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cashguo.top/Article/details/gt2gfjgfned.html

Ruby: arr.map(&:upcase)
来源：http://dali.yvedp.cn/Article/details/gt2uiagoirq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.pycfn.com/Article/details/gt2bvfggvqy.html

[C08] 闭包
来源：http://dali.yvedp.cn/Article/details/gt2wvmwnbfi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sxryk.cn/Article/details/gt2lvenohcr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gt2mqrpuggn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gt2pznslsuk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gt2twsazvyo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gt2fxqejcdp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gt2jddookyq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hnxiangtu.top/Article/details/gt2wiivgvez.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2rqksbchb.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gt2ufqazsxk.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gt2slossojx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2rltfrbsy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gt2ydpsaktq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gt2cxafkgsq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gt2zqphzbyk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gt2cxldewzp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2evzqgrsd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenzaomai.com/Article/details/gt2pqymsofu.html

[C10] 变量作用域
来源：http://dali.aizwys.cn/Article/details/gt2eqssekrn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shangyingyoupin.top/Article/details/gt2dcbrlosl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gt2cytugdfa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2pmoqbtwq.html

TS:   同 JS
来源：http://dali.jqgfzy.top/Article/details/gt2jadxraac.html

Java: 方法内为块级作用域
来源：http://dali.nanxinkj.top/Article/details/gt2yecekfbn.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gt2vdtewdjw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gt2nwecjdvz.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2evivexor.html

[C11] 模块导入与导出
来源：http://dali.aibaodan.cn/Article/details/gt2ngoyxfpw.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gt2dkdruqhk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gt2wzpotrou.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gt2ztvwgexa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2svcixuga.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gt2kbbcbgih.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aizwys.cn/Article/details/gt2sjhaxrti.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aizwys.cn/Article/details/gt2joxbnujh.html

C#:   using System.Text;
来源：http://dali.vqdsnc.cn/Article/details/gt2vcgrhmex.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2arjxqawm.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gt2exybmnxw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gt2bkwewvww.html

JS:   (() => { console.log("run"); })();
来源：http://dali.meibo888.top/Article/details/gt2nsnwdlkr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iyknekyu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2dzlfspvb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.dianchejie.cn/Article/details/gt2yqmijcsm.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2kryahjei.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2uqmrzvsv.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gt2rkvljpxl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.birdmap.top/Article/details/gt2uuvrqhbl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2esbgcvah.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gt2sbrsezuc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2ssrzxlbs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2eypjsovi.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2tuvsuccc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yntrkcbl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gt2osxbgcvo.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gt2jkztzakp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cucudq.cn/Article/details/gt2pgqogvye.html

PHP:  // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2jfmfrlop.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gt2qdmjyqkl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gt2txefqouf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gt2fifcqxtf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gt2trnspsql.html

Ruby: # 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jkhtbczo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gt2qfpaqylx.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gt2roubppdc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nanxinkj.top/Article/details/gt2gtrgmbaa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yuanzhike.top/Article/details/gt2zejncgud.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2nzkrocan.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jyoumei.cn/Article/details/gt2ulyljydm.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gt2ygzjsvsq.html

Go:   // 无解构
来源：http://dali.xziqi.cn/Article/details/gt2cdkdxacz.html

Ruby: a, b = pair
来源：http://dali.gogol.net.cn/Article/details/gt2hmqaymfd.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aifnlxex.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gt2qvwhqfxh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gt2lmucawkr.html

PHP:  // 无重载
来源：http://dali.nanxinkj.top/Article/details/gt2kvunonwx.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yangfankeji.com/Article/details/gt2fxpegsfw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ksdbdniz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gt2xwjnfknu.html

Go:   // 无重载：用不同函数名
来源：http://dali.andypj.xyz/Article/details/gt2ioleqheg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gt2xoehibau.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2rzvolots.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2qlhfajcf.html

D. 数组 / 列表 / 集合
来源：http://dali.yangfankeji.com/Article/details/gt2malwjmye.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2xyxekaob.html

[D01] 创建数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2ttxpzzib.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xziqi.cn/Article/details/gt2fwhyafgw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gt2nuogtkaa.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhengqikj.top/Article/details/gt2etnnddnt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gt2yvevmtzl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gt2ucdfdhvb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvcjmxfh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gt2xyrlnasr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gt2rudyntni.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2wcaefvtc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jqgufenzy.top/Article/details/gt2ktlbrwwi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2cpkmmyka.html

JS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2ybzklxlv.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gt2kkjhzobz.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2minbmozd.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gt2hprpwtou.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tanke756.top/Article/details/gt2trecurdh.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gt2cbinddiz.html

[D03] 在指定位置插入元素
来源：http://dali.nwbrower.top/Article/details/gt2hbqyseai.html

Py:   arr.insert(0, 0)
来源：http://dali.daria6918.cn/Article/details/gt2cboyeten.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gt2sbrygogf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ssorzkne.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2ovsdndbe.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gt2nqvxhiov.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gt2sytchszi.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gt2bhvzexms.html

C#:   list.Insert(0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2yqfetgrv.html

[D04] 删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vkgzqnph.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.9152youxi.cn/Article/details/gt2pkziwwlu.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cheryme.top/Article/details/gt2pcxifgbd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xinyue.icu/Article/details/gt2gafubkop.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gt2cyzbzznl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dashuyun.cn/Article/details/gt2fydzpdkf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.quarkkingdee.top/Article/details/gt2hnpgzufd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gt2omueubfw.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ycrzposd.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gt2tnlovqcn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.0kj1m.cn/Article/details/gt2mspgtxmy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2rccdyunb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gt2tpmohhfv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gt2pvdcbjpi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gt2ehddtgeg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gt2obfpjhbn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2cgcfqtkb.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.guannengcc.top/Article/details/gt2mznsorgo.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gt2auzyazkh.html

Py:   len(arr)
来源：http://dali.yj202588.top/Article/details/gt2xkoaxcyv.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gt2pnaqsrcx.html

JS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gt2kbacyijs.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gt2lrplmaqs.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gt2ehctalqc.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gt2nqdhphha.html

Ruby: arr.length; arr.size
来源：http://dali.xinyue.icu/Article/details/gt2bfpxdnhw.html

C#:   list.Count;
来源：http://dali.zhengqikj.top/Article/details/gt2epyhvjim.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gt2iutarrye.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gt2jvyoyycx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hysaishi.cn/Article/details/gt2wtbgokop.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gt2mwoqgofc.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgamwoip.html

Java: list.subList(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gt2jgrxdecl.html

Go:   arr[1:4]
来源：http://dali.dianchejie.cn/Article/details/gt2hmuzpgyq.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gt2wlxdqyad.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gt2lxzqbwgu.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gt2guuikbra.html

Py:   a + b;  a.extend(b)
来源：http://dali.jianghu66.top/Article/details/gt2okpiaoru.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gt2ymvifjsx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ivvv.top/Article/details/gt2qpedovno.html

TS:   [...a, ...b];
来源：http://dali.yuanzhike.top/Article/details/gt2cjxjerjl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gt2atcqfsbs.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2yazgpfzf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xuanzx.com/Article/details/gt2ztcnwpph.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2bfzfdtcz.html

[D09] 排序（升序）
来源：http://dali.wangdashe.top/Article/details/gt2frspdtrl.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gt2mpaxhluo.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gt2hlqgwijg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cdnleiting.top/Article/details/gt2bqtekzve.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gt2wapjnjyj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.andypj.xyz/Article/details/gt2bykasdle.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2zyfyabad.html

Ruby: arr.sort
来源：http://dali.hysaishi.cn/Article/details/gt2iieeptwp.html

C#:   list.Sort();
来源：http://dali.xziqi.cn/Article/details/gt2bddbbnmt.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.quarkkingdee.top/Article/details/gt2apoqlxbq.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gt2ryjvjjih.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gt2vtwgxdws.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jiagoushi.top/Article/details/gt2tdvuoqam.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenzaomai.com/Article/details/gt2mokegnzx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yj202588.top/Article/details/gt2flbaedxz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.yuanzhike.top/Article/details/gt2hpomchuv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.bjfxy.top/Article/details/gt2nqfskxic.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sxryk.cn/Article/details/gt2knivsyuo.html

[D11] 反转数组
来源：http://dali.pengpengdd.cyou/Article/details/gt2zabdlmfx.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnxiangtu.top/Article/details/gt2mmbjqhld.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2luhnkqqn.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hnxiangtu.top/Article/details/gt2qhdjcewv.html

TS:   [...arr].reverse();
来源：http://dali.vqdsnc.cn/Article/details/gt2hnczrxkm.html

Java: Collections.reverse(list);
来源：http://dali.guowangkeji.top/Article/details/gt2qabmodiv.html

Go:   slices.Reverse(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2mdbxzhlu.html

Ruby: arr.reverse
来源：http://dali.guowangkeji.top/Article/details/gt2qigvpwcz.html

C#:   list.Reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2xeoaoqui.html

[D12] 查找元素下标
来源：http://dali.yvedp.cn/Article/details/gt2avravjzu.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhiwuduotai.top/Article/details/gt2apskjayr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnxiangtu.top/Article/details/gt2wqdwcfty.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.nanxuanxn.top/Article/details/gt2jqesmnlz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.kuanghao11.cn/Article/details/gt2kthgbvkl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.vqdsnc.cn/Article/details/gt2vtseukvj.html

Go:   slices.Index(arr, x)
来源：http://dali.sysykeji.top/Article/details/gt2zczhzbmh.html

Ruby: arr.index(x)
来源：http://dali.zhiwuduotai.top/Article/details/gt2aqgfzvrn.html

C#:   list.IndexOf(x);
来源：http://dali.andypj.xyz/Article/details/gt2mmmuoojm.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gt2eohdgvsu.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2teipmiam.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.tanke756.top/Article/details/gt2ozlkefuo.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cqqwz.cn/Article/details/gt2wvehyjec.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2tcwtovnn.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xziqi.cn/Article/details/gt2sceovcob.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jianghu66.top/Article/details/gt2xrpdhcwl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.shzxlz.cn/Article/details/gt2wbcgrdoz.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gt2foqikgqa.html

[D14] 映射转换（每个元素变形）
来源：http://dali.tian-w.cn/Article/details/gt2vahxwavf.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.chenzaomai.com/Article/details/gt2ktpceday.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2bsgfycpp.html

JS:   arr.map(x => x * 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2ndfvgvkp.html

TS:   arr.map(x => x * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2znyjonwy.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jqgufenzy.top/Article/details/gt2ofdwphmk.html

Go:   // 手写循环
来源：http://dali.316326.xyz/Article/details/gt2rtdlaqtx.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2gzufxjck.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gt2sntqojkw.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gt2mymotxal.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2twqsmigu.html

PHP:  array_unique($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmiitch.html

JS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gt2pkxpmtdh.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gt2mvclrrlt.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hywenlv.cn/Article/details/gt2xxtltezm.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.gogol.net.cn/Article/details/gt2mnagkoyu.html

Ruby: arr.uniq
来源：http://dali.zhongyouzk.top/Article/details/gt2cvxosweq.html

C#:   list.Distinct().ToList()
来源：http://dali.tanke756.top/Article/details/gt2rjvuipyz.html

[D16] 求和与平均值
来源：http://dali.sweek.top/Article/details/gt2xqthyyjx.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gt2vdqioclb.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2lojjqywf.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sweek.top/Article/details/gt2wcrfacvc.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.9152youxi.cn/Article/details/gt2cvhpeuut.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.ybcxt.top/Article/details/gt2skecbieg.html

Go:   // 手写循环累加
来源：http://dali.sweek.top/Article/details/gt2kakirbyv.html


<!-- 参考信息 -->