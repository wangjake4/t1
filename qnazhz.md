代发 wailian999

Java: if (data == null) return;
来源：http://dali.yvedp.cn/Article/details/gthgrkelai.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtbdskknyx.html

Ruby: return if data.nil?
来源：http://dali.mhx1999.top/Article/details/gtzklwgmzu.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtgozkznis.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdietahsf.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtcjpskmhp.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtwqejdyin.html

[C01] 定义函数
来源：http://dali.guowangkeji.top/Article/details/gtnxggmpan.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtksiynfgd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gttneoakra.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxeycxqye.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtqdyfvjcq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtijgfypas.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gthtkxamht.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtastsnron.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtyxmpixjn.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtlksxqtpx.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gthxvkjvxj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtikmemlrn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqbtrouyh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtxzvixodr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gthwqovwvj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtnkvxsszd.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtmraahfkz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtjakpqylh.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtlejotqdr.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gteiobrfjv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpfuzoix.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtrsoubyjp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cqqwz.cn/Article/details/gtqarlegni.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwiloedz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtbsqzkkil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtxfobphxw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shuidangran.top/Article/details/gtjpofnljh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yangfankeji.com/Article/details/gtfoxajwjh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gtjualcvxb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtiajhxnas.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gttdqsduwm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gtfsowzffq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtspidsvph.html

Go:   // 无：用配置结构体参数
来源：http://dali.dashuyun.cn/Article/details/gtgdbkxrqa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gtxtcyhdqt.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtbmdsezfg.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gtnnzleezi.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzjxpfwu.html

PHP:  return [$a, $b];
来源：http://dali.jyoumei.cn/Article/details/gthqxtyxpn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.redwolf501.top/Article/details/gtpcyhfent.html

TS:   return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtsuuxnebn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtggnzzjxm.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtwcbdkgmi.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtkizzuacn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gttbgrirum.html

[C06] 匿名函数 / lambda
来源：http://dali.tianlin.xyz/Article/details/gtswqfptuy.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtgyzxwokt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtwbtxglrm.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gtrnpbruak.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtpauwuqcx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhixingplan.top/Article/details/gtpsgcspxw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ybcxt.top/Article/details/gtpexjdrhn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.svipenyu.cn/Article/details/gtjblahutg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtbfrajgso.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtmltzxmqx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gtofyretiv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gogol.net.cn/Article/details/gtdegqcmtf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtjcmayndi.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtnppbgeut.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjdukbpbt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtwwyrmhoa.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtbosuilrb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gtytigozha.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtclikijsg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtuckyvrpe.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtvfrhiwne.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtdhgfspew.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.9152youxi.cn/Article/details/gtgvondyoe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gtjkhbjbyl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtuwijinbo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gtpslgfyti.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtzuvrnyvd.html

[C09] 递归
来源：http://dali.zhiwuduotai.top/Article/details/gtjidsrpus.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfcndepo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtbtfluefl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtfwltxetd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtqhngsrho.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtvctxjzoz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gttsbtwvcf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtlfxrcvwz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtktpnuogo.html

[C10] 变量作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtsnztzspl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.bjfxy.top/Article/details/gtqtualylu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtdhwcdlxc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtsnfpmwyn.html

TS:   同 JS
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrljssgxb.html

Java: 方法内为块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtffnxerpr.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhokipda.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtovdnmfli.html

C#:   块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtgrwbvgnq.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtczsurdcf.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtbivqlvkf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtitcixemo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shuidangran.top/Article/details/gtepjssmew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtxildywuc.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtiufrlcpo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtivhqrkka.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoipzyljy.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtdxkmbyzt.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gtolckuvvc.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gteytoxquo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtwtmmjbbs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gtvfwclqju.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtxnxzdbnz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xinyue.icu/Article/details/gtsyzadypm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtmkrtizpx.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtrolrdaqg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhiwuduotai.top/Article/details/gttdojupit.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtnenuivow.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtxnzdqpfy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtwzxfhrlm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zycfv.cn/Article/details/gtcfnbmxjr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gttbipswtz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtykcmzfwg.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtqavjzgbz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gtsmoilogx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtgqljvjfz.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtohduudrg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gttcfgacdv.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtnukqrjjk.html

JS:   // 无泛型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglfbscix.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhijiandao.cn/Article/details/gtubhfwmzc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cqqwz.cn/Article/details/gtrtmbxnlz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenlongwang.top/Article/details/gtssviwypj.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtoadcqccs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtqrjjukhu.html

[C15] 解构 / 展开参数
来源：http://dali.zhiwuduotai.top/Article/details/gtbrchkjqf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gtcdzidhcc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtmrpermzj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtrdlsqifm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtwqpbycfd.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtgfgncxkc.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtasjptjnl.html

Ruby: a, b = pair
来源：http://dali.quarkkingdee.top/Article/details/gtqbchtftz.html

C#:   var (a, b) = pair;
来源：http://dali.cucudq.cn/Article/details/gtjtazaram.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtjnnorqwm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtibkbgjuu.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gttimjtdoe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtradqpwhb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtamwqjwxh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gttodvysbi.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxvucppy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gttctijpvo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtueyjtuky.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmfoyjvrl.html

D. 数组 / 列表 / 集合
来源：http://dali.jyoumei.cn/Article/details/gtscmqrfic.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtgyhrcoqr.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtcniqhmvr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.haohaochexian.top/Article/details/gtbotuwqhc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hammf.cn/Article/details/gtfglqxvgz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhongyouzk.top/Article/details/gtxqicsaxg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtgapcjpfh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.svipenyu.cn/Article/details/gtxyyzqlpa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tian-w.cn/Article/details/gtwjcnggbq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jqgfzy.top/Article/details/gtwqlsrato.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.pengpengdd.cyou/Article/details/gtsdnxuzbr.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtsdnbwwxf.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gtkthblubf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gtukkgewqz.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtjllteaqe.html

TS:   arr.push(4);
来源：http://dali.cucudq.cn/Article/details/gtddjrunqi.html

Java: list.add(4);
来源：http://dali.yangfankeji.com/Article/details/gtfhcqpwcs.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gtbayugqyg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.bjfxy.top/Article/details/gtpyhiktcz.html

C#:   list.Add(4);
来源：http://dali.yuanzhike.top/Article/details/gtkigizjfa.html

[D03] 在指定位置插入元素
来源：http://dali.xinyue.icu/Article/details/gtuawymfls.html

Py:   arr.insert(0, 0)
来源：http://dali.hywenlv.cn/Article/details/gtgtzfhrbn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.daxiang520.top/Article/details/gtwysiujug.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtxyruzerq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258888.top/Article/details/gtuxnagrrp.html

Java: list.add(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtlfqnsfaq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jianghu66.top/Article/details/gtuoupxnws.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gtodltehdo.html

C#:   list.Insert(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtwpvqqxhf.html

[D04] 删除元素
来源：http://dali.zycfv.cn/Article/details/gtzkdrjpnn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouvywmat.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gttuceiare.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqpilcyb.html

TS:   arr.splice(0, 1);
来源：http://dali.guowangkeji.top/Article/details/gtemjayfia.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtbfepdlyr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.feifeiyinyue.top/Article/details/gtasmcypgc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangdashe.top/Article/details/gtxhcyhoge.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtylpicptf.html

[D05] 访问与修改元素
来源：http://dali.vqdsnc.cn/Article/details/gthehxgfcb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtzlgcfrar.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtvafankfl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtzsjiebah.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.redwolf501.top/Article/details/gtggkuhmeh.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.vqdsnc.cn/Article/details/gtqbtfctkw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hywenlv.cn/Article/details/gthjtbxmua.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtiougxgrq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtnonnrkkg.html

[D06] 数组长度
来源：http://dali.pengpengdd.cyou/Article/details/gtcpbvmwno.html

Py:   len(arr)
来源：http://dali.daxiang520.top/Article/details/gtxfkshpiq.html

PHP:  count($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtpbktrtss.html

JS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtijrqrmfr.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtpdrdrdxh.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtsnlbqfns.html

Go:   len(arr)
来源：http://dali.hnqzz.top/Article/details/gtjhqbvfmd.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gtgjmpczhw.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtmoydrzsv.html

[D07] 切片 / 取子数组
来源：http://dali.fzhhl.top/Article/details/gtxnqtogcm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hysaishi.cn/Article/details/gtzebqvzrf.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtvhqvzasn.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtbumxhvyf.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbgsjtao.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtlyuxkawv.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtjpasltba.html

Ruby: arr[1, 3]
来源：http://dali.ppjwa.cn/Article/details/gtyvkxlucd.html

C#:   list.GetRange(1, 3);
来源：http://dali.sxryk.cn/Article/details/gtpeqbhnha.html

[D08] 合并两个数组
来源：http://dali.aizwys.cn/Article/details/gtnsxmsgek.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhoulong.xyz/Article/details/gttzdxnjvw.html

PHP:  array_merge($a, $b);
来源：http://dali.andypj.xyz/Article/details/gtttnvnfge.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.pengpengdd.cyou/Article/details/gtitlrrpqm.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtjfoaoomv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzcofwibm.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtvektwpjm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtodfbvjxl.html

C#:   a.Concat(b).ToList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraifihff.html

[D09] 排序（升序）
来源：http://dali.yj202588.top/Article/details/gtetxnyryk.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.0kj1m.cn/Article/details/gtwpdlzavp.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtubjxuawe.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfsnrzah.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sweek.top/Article/details/gtwwqiukeq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.guannengcc.top/Article/details/gtabehvkxm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtpqmglyrf.html

Ruby: arr.sort
来源：http://dali.feifeiyinyue.top/Article/details/gtdagbnijo.html

C#:   list.Sort();
来源：http://dali.hysaishi.cn/Article/details/gtasicpxrg.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gtmscjyuta.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.9152youxi.cn/Article/details/gtqjbzrooj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtkfljgwrp.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.9152youxi.cn/Article/details/gtdarmjhep.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gttgdmnmnr.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jqgufenzy.top/Article/details/gtzabnowug.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxerdchkf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yvedp.cn/Article/details/gtuwqrffba.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.fengsongda.top/Article/details/gtyiakqddo.html

[D11] 反转数组
来源：http://dali.ivvv.top/Article/details/gttiycnktr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.shzxlz.cn/Article/details/gtasldodrm.html

PHP:  array_reverse($arr);
来源：http://dali.quarkkingdee.top/Article/details/gtzracrsmv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.kuanghao11.cn/Article/details/gtpkyiddwo.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtneqjsodb.html

Java: Collections.reverse(list);
来源：http://dali.sysykeji.top/Article/details/gtoxilrwnd.html

Go:   slices.Reverse(arr)
来源：http://dali.316326.xyz/Article/details/gtydcprsui.html

Ruby: arr.reverse
来源：http://dali.yj202588.top/Article/details/gtvygooshl.html

C#:   list.Reverse();
来源：http://dali.jinghuilouyu.cn/Article/details/gtghkbedar.html

[D12] 查找元素下标
来源：http://dali.daria6918.cn/Article/details/gtyzmhnrin.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhongyouzk.top/Article/details/gtaoshjkee.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.9152youxi.cn/Article/details/gtjlnwwznd.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ybcxt.top/Article/details/gteyjflrdo.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtcohmiyem.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zdqjudy.top/Article/details/gtimaxqraj.html

Go:   slices.Index(arr, x)
来源：http://dali.jiagoushi.top/Article/details/gtzlvuavei.html

Ruby: arr.index(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjkvliqcd.html

C#:   list.IndexOf(x);
来源：http://dali.ivvv.top/Article/details/gtdeioohfq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.shzxlz.cn/Article/details/gtujokwwmt.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.cheryme.top/Article/details/gtvwqdbhyl.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuxming.cn/Article/details/gtcnpeogce.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sysykeji.top/Article/details/gtedpxcmmd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.sweek.top/Article/details/gtlwdkiutc.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhengqikj.top/Article/details/gtrpwsusbo.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqdwtarj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.ybcxt.top/Article/details/gtibykmrja.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtnyxblbyc.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhijiandao.cn/Article/details/gtjkeubcqb.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yangfankeji.com/Article/details/gtmenwgtcb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtshqpjpcj.html

JS:   arr.map(x => x * 2)
来源：http://dali.c1oappe.top/Article/details/gtseupppne.html

TS:   arr.map(x => x * 2)
来源：http://dali.ivvv.top/Article/details/gtjzwxifeu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.xuanzx.com/Article/details/gtajumikjs.html

Go:   // 手写循环
来源：http://dali.yongpay.top/Article/details/gtjlxhdwut.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtbfidgefl.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yonumen.top/Article/details/gtxgkypzyf.html

[D15] 去重
来源：http://dali.zhoulong.xyz/Article/details/gtwkcjizcm.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtabcqeeqn.html

PHP:  array_unique($arr);
来源：http://dali.daria6918.cn/Article/details/gtpoinknrg.html

JS:   [...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gtzudwavji.html

TS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtesmohgkl.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.ydzc1.top/Article/details/gtbbcnocjr.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.chenzaomai.com/Article/details/gtixkcvedy.html

Ruby: arr.uniq
来源：http://dali.c1oappe.top/Article/details/gtvpnmaxul.html

C#:   list.Distinct().ToList()
来源：http://dali.jianghu66.top/Article/details/gteaphjdyf.html

[D16] 求和与平均值
来源：http://dali.ybcxt.top/Article/details/gtoeoorsvr.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtqbtjbjid.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.haohaochexian.top/Article/details/gtdzwnqzuo.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.gogol.net.cn/Article/details/gtosspuzvw.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gthjoaxrlz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.guannengcc.top/Article/details/gtgydybvlh.html

Go:   // 手写循环累加
来源：http://dali.jianghu66.top/Article/details/gtvnsxckxr.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.hywenlv.cn/Article/details/gtwrabqpcg.html

C#:   list.Sum();  list.Average()
来源：http://dali.hammf.cn/Article/details/gtdiiuocoo.html

[D17] 最大值与最小值
来源：http://dali.dianchejie.cn/Article/details/gtkpyvgpuc.html

Py:   max(arr);  min(arr)
来源：http://dali.tanke756.top/Article/details/gtueqvjqst.html


<!-- 参考信息 -->