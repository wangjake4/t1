代发 wailian999

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2rnbqggpg.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gt2xrrjoevj.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lydlxjvt.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gt2sirhvoat.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2xoxjayyi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gt2iiezdkxg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2tcoguzly.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2igcxnzgm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2ehvqbivn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.redwolf501.top/Article/details/gt2ocfvinfh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gt2rwkxhbwn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2cglnfxxo.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2lfibqbsc.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bjbzhzqi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gt2hopcgzvg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2tqorzbjs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tian-w.cn/Article/details/gt2tjwzjamf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gt2uzfxqwjv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.kuanghao11.cn/Article/details/gt2ddpssqkv.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuanzhike.top/Article/details/gt2fnapdlvq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jlsjyb.cn/Article/details/gt2tldohktm.html

[C03] 可变参数
来源：http://dali.hnqzz.top/Article/details/gt2kpmrwbkn.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gt2bdcqcnsn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.9152youxi.cn/Article/details/gt2dalgyqhc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gt2kgejfbni.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2ynsfrljy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gt2bcjsbdve.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gt2dfyflflz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gt2oldgfmrx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gt2ootxcbda.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2yqhlelmg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gt2swncuhcp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gt2ytqydflx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj202588.top/Article/details/gt2nwnqxvtb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxmtkfuz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gt2clxnbjds.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gt2qegvlfpi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2kxfbjqjf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2exjyewmh.html

[C05] 返回多个值
来源：http://dali.gotoacloud.top/Article/details/gt2ulqlnogq.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gt2poymkzqh.html

PHP:  return [$a, $b];
来源：http://dali.316326.xyz/Article/details/gt2ecapnnsf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2uhsyskxy.html

TS:   return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gt2rlniumkp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2tqiopesw.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gt2voyyqyfd.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2qjxnzkzg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gt2hhzucmfk.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258.top/Article/details/gt2llcpjidf.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gt2gsldsyba.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gt2pdpxlzjz.html

JS:   const square = x => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2gcbqndsi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuanzhike.top/Article/details/gt2vjfhmwls.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2hmrkxtwv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.fengsongda.top/Article/details/gt2qeqzwwdc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2jztabqfs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gt2dbenffzk.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2wiuswdfa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gt2nhkjtiuo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dashuyun.cn/Article/details/gt2nqmqsldw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gt2vwidfazi.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhkxeyxf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gzhubu.top/Article/details/gt2ypzaryll.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gt2hqfhdysq.html

Ruby: arr.map(&:upcase)
来源：http://dali.hfpthk.cn/Article/details/gt2oudupqas.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pyzuhlyy.html

[C08] 闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2kuuglela.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gt2ogqwvpzg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rxgecjsv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gppjttik.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2mwxmsojo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.dashuyun.cn/Article/details/gt2vgfqqloo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2jsyvtwaw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uhunrypt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ieqiogla.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gt2whdnturi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2yljrmyqi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wmsfaild.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2cjfujcsf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2lvlxsdbt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gt2yjuoztfv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gt2jovwajgy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2epzifkle.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gt2axtclzho.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2jzqbfxbj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gt2rboiqtgv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gt2elhasajf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2pjppvxsf.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gt2sxqzlari.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gt2vazowqpu.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2lwzyaxyh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gt2xgpiwqts.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gt2xyeurdlj.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gt2skhrjcmm.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gt2mhibkmwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gt2bxaynaxe.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2awafmktn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.bjfxy.top/Article/details/gt2mhlpebfx.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gt2uuwcxrgq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yongpay.top/Article/details/gt2sohpthad.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gt2othgxfph.html

C#:   using System.Text;
来源：http://dali.meibo888.top/Article/details/gt2spdypqlw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jyoumei.cn/Article/details/gt2gawmjrzy.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2javouagi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gt2hdzegeme.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2iehefroj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gt2jhelvrqf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2bqhmeosf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gt2sbjsqrke.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gt2pdalmxuv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gt2zahlcpus.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gt2urriagzs.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gt2nmxsnhzz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2kpxwglet.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxuanxn.top/Article/details/gt2mtvengky.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gt2ljovfdzv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2rldthyhl.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gt2frhoxtom.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gt2qstjuziz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gt2hrsdclqu.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2ebhjdnnk.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ybcxt.top/Article/details/gt2mdgfgqdn.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2qplvexun.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gt2njjchyoa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2iovjcqbz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gt2geaorbzl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.mhx1999.top/Article/details/gt2riouwzeq.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2mvbodjui.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gt2lllvpmgq.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gt2wcvgguyd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gt2eyewyetb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.haohaochexian.top/Article/details/gt2wcxsnher.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gt2ewzxikle.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gt2tawmbvei.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gt2exwzmuqr.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gt2fupvbhxr.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gt2knypaqss.html

C#:   var (a, b) = pair;
来源：http://dali.9152youxi.cn/Article/details/gt2ulmztbuy.html

[C16] 函数 / 方法重载
来源：http://dali.meibo888.top/Article/details/gt2fyoiwjms.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gt2uiixdxnm.html

PHP:  // 无重载
来源：http://dali.316326.xyz/Article/details/gt2zrxfluuw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gt2rkjadbfk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2wiperbuj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2tozvqyoc.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2wfqkbdwt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gt2iievawjp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2qutvjlwn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2hbhfjnul.html

D. 数组 / 列表 / 集合
来源：http://dali.yueranfly.top/Article/details/gt2lerxyqko.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bsjbjfkd.html

[D01] 创建数组 / 列表
来源：http://dali.pycfn.com/Article/details/gt2rlqqztfj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gt2edjcnigb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gogol.net.cn/Article/details/gt2bgrjmiay.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yongpay.top/Article/details/gt2xofjuhgh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.birdmap.top/Article/details/gt2dlataiea.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xinyue.icu/Article/details/gt2hrxtoqfi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gt2vhmkyfku.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fengsongda.top/Article/details/gt2nkgvxgup.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cheryme.top/Article/details/gt2amajxbxq.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2eqwawevc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gt2ztdvmqay.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gt2itxtgimj.html

JS:   arr.push(4);
来源：http://dali.birdmap.top/Article/details/gt2aaxkexsg.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gt2thofgqbv.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gt2wdfymbdw.html

Go:   arr = append(arr, 4)
来源：http://dali.snrcjt.cn/Article/details/gt2tyftpzap.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gt2vacuejur.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gt2fpgsucnd.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gt2bssfnohg.html

Py:   arr.insert(0, 0)
来源：http://dali.ivvv.top/Article/details/gt2sqeelbym.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cqqwz.cn/Article/details/gt2qjijdqbe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gt2gvdcmbfg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2iwbkdxqv.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gt2keajpbpy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ehwqpu.com/Article/details/gt2zengvxpz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gt2vgeeqfpw.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gt2ahlephik.html

[D04] 删除元素
来源：http://dali.sweek.top/Article/details/gt2aqatrqwl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gt2pdgarmib.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.0kj1m.cn/Article/details/gt2vepdxslq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hysaishi.cn/Article/details/gt2nrdcvyny.html

TS:   arr.splice(0, 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2cpiundyg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jiagoushi.top/Article/details/gt2ltkydtbo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yongpay.top/Article/details/gt2mkypnzds.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2mcccfedt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gt2acyjcelc.html

[D05] 访问与修改元素
来源：http://dali.daxiang520.top/Article/details/gt2mdknakvt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2lxtumebv.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gt2rmagwcmy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gt2sletinwp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnxiangtu.top/Article/details/gt2lwwlaqcu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ydzc1.top/Article/details/gt2umrtuuos.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhongyouzk.top/Article/details/gt2vidljkmb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gt2hqbdmuip.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gt2uluphetb.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gt2zjkpvpyu.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gt2nbvsaugq.html

PHP:  count($arr);
来源：http://dali.snrcjt.cn/Article/details/gt2htjhhrlh.html

JS:   arr.length
来源：http://dali.yangfankeji.com/Article/details/gt2dbirvhwo.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gt2vapjxrlq.html

Java: list.size();
来源：http://dali.sweek.top/Article/details/gt2xrrtsogl.html

Go:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gt2mmrgresg.html

Ruby: arr.length; arr.size
来源：http://dali.svipenyu.cn/Article/details/gt2bskcsvfu.html

C#:   list.Count;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfhwjkod.html

[D07] 切片 / 取子数组
来源：http://dali.hfpthk.cn/Article/details/gt2cnjagifo.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zdqjudy.top/Article/details/gt2rkptlvlu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.ehwqpu.com/Article/details/gt2uzvsvfns.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gt2yxaeygug.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gt2uwwmcjdi.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2lkezwguv.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gt2mtefolbp.html

Ruby: arr[1, 3]
来源：http://dali.zdqjudy.top/Article/details/gt2akgkiirl.html

C#:   list.GetRange(1, 3);
来源：http://dali.sysykeji.top/Article/details/gt2mkoomeih.html

[D08] 合并两个数组
来源：http://dali.9152youxi.cn/Article/details/gt2cnrovsta.html

Py:   a + b;  a.extend(b)
来源：http://dali.guowangkeji.top/Article/details/gt2ztptjqqb.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gt2salyngmd.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.fzhhl.top/Article/details/gt2aazmcaay.html

TS:   [...a, ...b];
来源：http://dali.yuxming.cn/Article/details/gt2zgtccwze.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gt2jsjkamfl.html

Go:   append(a, b...)
来源：http://dali.yj20258.top/Article/details/gt2bgjtkcbr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xziqi.cn/Article/details/gt2mcfjqceq.html

C#:   a.Concat(b).ToList()
来源：http://dali.xziqi.cn/Article/details/gt2ibzmtaxe.html

[D09] 排序（升序）
来源：http://dali.yuanzhike.top/Article/details/gt2sdptioht.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2owpvehwx.html

PHP:  sort($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2anbyjakp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.xuanzx.com/Article/details/gt2oyhlexej.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nanxinkj.top/Article/details/gt2vjrccpah.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gt2czmgphhm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.316326.xyz/Article/details/gt2lfdiwcjf.html

Ruby: arr.sort
来源：http://dali.pycfn.com/Article/details/gt2sdfwttnh.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gt2pkmsuogc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gt2ommjfdrh.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gt2acmlwxkp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gt2vjsgmxkt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kqgedceo.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tanke756.top/Article/details/gt2wqxakrua.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.daxiang520.top/Article/details/gt2sbfzdfrh.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cdnleiting.top/Article/details/gt2pgncyypd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yj20258.top/Article/details/gt2tgrzpotm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yuxming.cn/Article/details/gt2dbmxluvk.html

[D11] 反转数组
来源：http://dali.shuidangran.top/Article/details/gt2dadfocls.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.dashuyun.cn/Article/details/gt2lgtvnnmb.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gt2egvoimcq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258888.top/Article/details/gt2siiwaeuo.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gt2pyflxhyq.html

Java: Collections.reverse(list);
来源：http://dali.pycfn.com/Article/details/gt2hcrxeixy.html

Go:   slices.Reverse(arr)
来源：http://dali.haohaochexian.top/Article/details/gt2frynepld.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2clliqbip.html

C#:   list.Reverse();
来源：http://dali.xylfe.cn/Article/details/gt2bigsfwkn.html

[D12] 查找元素下标
来源：http://dali.zycfv.cn/Article/details/gt2zfokcmkw.html

Py:   arr.index(x);  x in arr
来源：http://dali.gogol.net.cn/Article/details/gt2vogrzxks.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.c1oappe.top/Article/details/gt2tnbfgcja.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.sweek.top/Article/details/gt2onaiaoxa.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gt2vnapegao.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.andypj.xyz/Article/details/gt2lizumrkd.html

Go:   slices.Index(arr, x)
来源：http://dali.kuanghao11.cn/Article/details/gt2uoczoutv.html

Ruby: arr.index(x)
来源：http://dali.aizwys.cn/Article/details/gt2ztqzhued.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hpfmrshs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.gotoacloud.top/Article/details/gt2hsujvgdm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gt2wwunlrwe.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2xmjahere.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhoulong.xyz/Article/details/gt2ctemqqhu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.svipenyu.cn/Article/details/gt2iglvterw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gt2kdordeho.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.yongpay.top/Article/details/gt2fjpcdvlo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ydzc1.top/Article/details/gt2ffrqbwtu.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bionzbmk.html

[D14] 映射转换（每个元素变形）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2buavsepw.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.guannengcc.top/Article/details/gt2aegxirax.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.daria6918.cn/Article/details/gt2xaazdouq.html

JS:   arr.map(x => x * 2)
来源：http://dali.xinyue.icu/Article/details/gt2xditrsji.html

TS:   arr.map(x => x * 2)
来源：http://dali.yj202588.top/Article/details/gt2ekgihjbw.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gt2lcbbqsau.html

Go:   // 手写循环
来源：http://dali.xziqi.cn/Article/details/gt2vjinuopl.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2knbirugq.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zycfv.cn/Article/details/gt2wxgzplip.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gt2aqyjizko.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2qablwcbs.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gt2sifokwua.html

JS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2vvqpkgel.html

TS:   [...new Set(arr)]
来源：http://dali.9152youxi.cn/Article/details/gt2faoavvti.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.hnxiangtu.top/Article/details/gt2dldwxrob.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.fengsongda.top/Article/details/gt2ewcpkbzr.html

Ruby: arr.uniq
来源：http://dali.xuanzx.com/Article/details/gt2qyratpvk.html

C#:   list.Distinct().ToList()
来源：http://dali.fengsongda.top/Article/details/gt2cmqdljsb.html

[D16] 求和与平均值
来源：http://dali.fzhhl.top/Article/details/gt2jcpdubgl.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yongpay.top/Article/details/gt2wewclypp.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2diaqoprm.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.sufxvd.cn/Article/details/gt2liqphgfn.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2fepletln.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.gzhubu.top/Article/details/gt2fukvezxk.html

Go:   // 手写循环累加
来源：http://dali.zhijiandao.cn/Article/details/gt2poqudran.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.haohaochexian.top/Article/details/gt2gkbvfcrm.html

C#:   list.Sum();  list.Average()
来源：http://dali.jianghu66.top/Article/details/gt2pnwjnutb.html

[D17] 最大值与最小值
来源：http://dali.hammf.cn/Article/details/gt2nphhuqdk.html

Py:   max(arr);  min(arr)
来源：http://dali.ybcxt.top/Article/details/gt2dwwnmmne.html

PHP:  max($arr);  min($arr);
来源：http://dali.ppjwa.cn/Article/details/gt2olzxskwo.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.mhx1999.top/Article/details/gt2gwjvrwgr.html

TS:   Math.max(...arr);
来源：http://dali.jianghu66.top/Article/details/gt2rtxyjxtt.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.pycfn.com/Article/details/gt2bmilprgk.html


<!-- 参考信息 -->