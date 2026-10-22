代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gt2leduxxix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gt2mpqsdcaj.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gt2dfblepzg.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gt2ypuwsrow.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gt2bphyhfut.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2czkhxgzo.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2exxivkai.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2xmyjzlhx.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmuoxhof.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2vconzmle.html

C#:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2lrkilnku.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2wyknhybj.html

Py:   if not data: return
来源：http://dali.daria6918.cn/Article/details/gt2lihcrcsx.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2oovmpvom.html

JS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gt2zaboiami.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jkeepltn.html

Java: if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gt2efnwklue.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gt2kxxyodtg.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gt2ihadwrtv.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gt2udbytmfv.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2oronszbu.html

C. 函数与作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2qwwdbtzv.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2guiygltg.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gt2sqafwvna.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gt2xtlusrmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2lknaalwe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2ndxywmcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxiqpjma.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2lepalkmx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2ozuhhvyd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gt2walvtllu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuessdqu.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2spazupwh.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gt2xwizvbdj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gt2drtolfmt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2osnhlxdp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2emcygarx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuetiantiany.cn/Article/details/gt2xeivcpvj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2tsieynet.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2pvrzvycd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gt2upeivwmp.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gt2otkkzvhc.html

Py:   def total(*args): return sum(args)
来源：http://dali.hywenlv.cn/Article/details/gt2yqxkyjid.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gt2eulmghxu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2ljcsjbou.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2phiifspl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2pwdmhzqj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.havefunace.top/Article/details/gt2xxpdjqws.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gt2kjfqbxqs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2brhogjxv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gt2aewkeqrf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gt2updtfrhh.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2csrcwxgr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vucapuyk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gt2qnapwjsy.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gt2ecmaosut.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gt2ismnvicg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gt2ibvahvti.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gt2yuykbuju.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gt2zrhbnche.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2myvmiyfj.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2edcyfrgv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2xnpyvadk.html

TS:   return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gt2czipwwgn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gotoacloud.top/Article/details/gt2siufkzib.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2ceoovncj.html

Ruby: return a, b
来源：http://dali.zhengqikj.top/Article/details/gt2bbmkbvht.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gt2ffvrzrnp.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2nlpebzzl.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gt2qjnyokns.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctgpcwlq.html

JS:   const square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gt2npwvzyfz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.sysykeji.top/Article/details/gt2cruhzjhd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zlwqyteo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gt2twuihvqc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gt2zuulcnzf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2fwfxlxnm.html

[C07] 把函数作为参数传入
来源：http://dali.xziqi.cn/Article/details/gt2sfjtersq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ybcxt.top/Article/details/gt2kjuxbqxj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gt2cixwvxto.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuanzhike.top/Article/details/gt2aqvifmaw.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gt2nzssfzeh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gt2vnbmdfvu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hfpthk.cn/Article/details/gt2tcjevlgw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kdqbtdsy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gt2meqkpiev.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gt2noegpluw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gt2hkowmjib.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cqsrzrsi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gt2rrziezdh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qtqcnwzm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gt2wfkdqpza.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gt2souuzopv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.vqdsnc.cn/Article/details/gt2miupudmr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2celsjjhz.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gt2iqxraftf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2ofkhphvw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gt2hkplgclv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2aswtpqho.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj202588.top/Article/details/gt2sptlqvgc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2aykvepmn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.tanke756.top/Article/details/gt2tmfntkcx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zycfv.cn/Article/details/gt2dhhjfjej.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiqnpgxy.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gt2abicidtt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gt2brqdjwqg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhixingplan.top/Article/details/gt2qnxqsdxt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2fjzbiygh.html

TS:   同 JS
来源：http://dali.dianchejie.cn/Article/details/gt2qtmedjwg.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2ufgnfqit.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gt2mnddmitw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.bjfxy.top/Article/details/gt2znzqutgq.html

C#:   块级作用域
来源：http://dali.ppjwa.cn/Article/details/gt2bdfduxwo.html

[C11] 模块导入与导出
来源：http://dali.zycfv.cn/Article/details/gt2tpjzkzmw.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gt2esdpwvcx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygnmknti.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2nasqbict.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gt2fkwvpexu.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ngmpdkpj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gt2fytkgqcj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gt2jgwwwnmt.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2sgudulpy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zycfv.cn/Article/details/gt2tqdrziqm.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gt2lwptteuc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ybcxt.top/Article/details/gt2oqvvnpcd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gt2znwireub.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vkmobrhe.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yuxming.cn/Article/details/gt2gdldaalg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gt2eyafigbe.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gt2wfvahnoe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gt2hekkdzdc.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2spfaipnx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gt2enifnhav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2bcepnklg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gt2lkpeajje.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2clczzaaf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2juaqbetc.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gt2mlhxmrvh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dianchejie.cn/Article/details/gt2kmsslpdl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gt2cgrxjxwh.html

[C14] 泛型函数
来源：http://dali.jqgfzy.top/Article/details/gt2pptkkwmc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gt2snisdbju.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2hifbfhgw.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gt2tbpjglix.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gt2wpipcqmk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fofmbirj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gt2mpeynqvs.html

Ruby: # 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gt2eedueqps.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gt2eefbcrhy.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gt2lpzxxogo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2jdtzstqr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xinyue.icu/Article/details/gt2epmpbagu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gt2vlzvqxqo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuanzx.com/Article/details/gt2yvlcotup.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gt2jknjgfvp.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gt2cugetejh.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gt2xwqxaoty.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gt2dhwdtmno.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gt2mimkrivl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gt2vjryjody.html

PHP:  // 无重载
来源：http://dali.haohaochexian.top/Article/details/gt2inkarbcf.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snisbmrl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxiugzop.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2fmejazqb.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhengqikj.top/Article/details/gt2lhirjlbp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gt2psbmeuhm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2dxkjfvwl.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2jkrnniqj.html

D. 数组 / 列表 / 集合
来源：http://dali.pycfn.com/Article/details/gt2mzgpkvvo.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2icxnnchj.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gt2dmtcrjfw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gt2bpyoiwml.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gt2rvagqkos.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gt2djjdgtet.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gt2vlcbtpmx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dianchejie.cn/Article/details/gt2oggimzks.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gt2adottnak.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gt2eotykcwq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shuidangran.top/Article/details/gt2kvsrpady.html

[D02] 追加元素到末尾
来源：http://dali.zdqjudy.top/Article/details/gt2bzkvgvtb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gt2vfyqlcff.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gt2blobrico.html

JS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2ahzdwzgz.html

TS:   arr.push(4);
来源：http://dali.zhoulong.xyz/Article/details/gt2fwtjkdth.html

Java: list.add(4);
来源：http://dali.jyoumei.cn/Article/details/gt2xcrttbwu.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gt2oabkmwmh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuxming.cn/Article/details/gt2fgqiaamj.html

C#:   list.Add(4);
来源：http://dali.jinqigufen.top/Article/details/gt2scpiozfm.html

[D03] 在指定位置插入元素
来源：http://dali.shuidangran.top/Article/details/gt2vxuguvzl.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gt2gfvfuljk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gzhubu.top/Article/details/gt2onlvfxiu.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sufxvd.cn/Article/details/gt2zihjghqt.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gt2nvmtimdp.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gt2qjqpvgkt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xziqi.cn/Article/details/gt2ocxpoacs.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.kuanghao11.cn/Article/details/gt2legjneic.html

C#:   list.Insert(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sttazncx.html

[D04] 删除元素
来源：http://dali.ivvv.top/Article/details/gt2wxldttad.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hywenlv.cn/Article/details/gt2cgsrbwvl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gt2psdoeuvj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gt2vzpfvutw.html

TS:   arr.splice(0, 1);
来源：http://dali.sxryk.cn/Article/details/gt2wfifwkda.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2lujhgtqe.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gt2qvswlzbh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jyoumei.cn/Article/details/gt2lgqprkmt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fzhhl.top/Article/details/gt2ohzqfdcd.html

[D05] 访问与修改元素
来源：http://dali.jyoumei.cn/Article/details/gt2gaihsads.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hongshengwenyu.top/Article/details/gt2fmwbwmti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangdashe.top/Article/details/gt2uipvcxnr.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gt2qvygnvpj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hywenlv.cn/Article/details/gt2kfjzlbhz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2usjbkuow.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gt2jzwxrwtf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gt2gwmwyjhv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.mhx1999.top/Article/details/gt2zjimoiql.html

[D06] 数组长度
来源：http://dali.andypj.xyz/Article/details/gt2fnhzzqia.html

Py:   len(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2asfazndw.html

PHP:  count($arr);
来源：http://dali.shuidangran.top/Article/details/gt2myoarlvu.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gt2bwqrkunb.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dadhvkcv.html

Java: list.size();
来源：http://dali.zhixingplan.top/Article/details/gt2wnybtncx.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gt2hdtmmwya.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gt2cywhboak.html

C#:   list.Count;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yhtovlya.html

[D07] 切片 / 取子数组
来源：http://dali.iojbl.cn/Article/details/gt2vldemjqc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.daria6918.cn/Article/details/gt2apbqxtzk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zycfv.cn/Article/details/gt2twsncqoo.html

JS:   arr.slice(1, 4);
来源：http://dali.aizwys.cn/Article/details/gt2fsjdsgks.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsvgeyks.html

Java: list.subList(1, 4);
来源：http://dali.xziqi.cn/Article/details/gt2gdferhkl.html

Go:   arr[1:4]
来源：http://dali.xinyue.icu/Article/details/gt2zbvyuvrw.html

Ruby: arr[1, 3]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oivncuot.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gt2lddrmxoq.html

[D08] 合并两个数组
来源：http://dali.c1oappe.top/Article/details/gt2zhoviksg.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlmdgiw.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2atzryuuv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.hnxiangtu.top/Article/details/gt2ypvzhuxw.html

TS:   [...a, ...b];
来源：http://dali.guowangkeji.top/Article/details/gt2reztvjqs.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.gzhubu.top/Article/details/gt2xemrenkv.html

Go:   append(a, b...)
来源：http://dali.hywenlv.cn/Article/details/gt2bfcrhtol.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258.top/Article/details/gt2ozqlmsmp.html

C#:   a.Concat(b).ToList()
来源：http://dali.hysaishi.cn/Article/details/gt2nmgnalmr.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzdevrhc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gt2pztcvbbr.html

PHP:  sort($arr);
来源：http://dali.sufxvd.cn/Article/details/gt2rupeypca.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yj202588.top/Article/details/gt2utgqgvwm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.0kj1m.cn/Article/details/gt2oypwntpk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.redwolf501.top/Article/details/gt2mrcogywc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gt2tydeyntz.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2ziaqgcpp.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gt2hqhzhdzy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2elhjrcql.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jiagoushi.top/Article/details/gt2hsmzcwlt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.feifeiyinyue.top/Article/details/gt2udbvdsve.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yvedp.cn/Article/details/gt2pwfykiaq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2czausrkc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.smart0.xyz/Article/details/gt2vhavdkpb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nwbrower.top/Article/details/gt2vsoauikq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cashguo.top/Article/details/gt2cjdlzmfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.svipenyu.cn/Article/details/gt2pyydrkhu.html

[D11] 反转数组
来源：http://dali.dianchejie.cn/Article/details/gt2hqyghtuz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.fengsongda.top/Article/details/gt2zuohnriv.html

PHP:  array_reverse($arr);
来源：http://dali.hysaishi.cn/Article/details/gt2hsbzmdmr.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhixingplan.top/Article/details/gt2ohebgsqs.html

TS:   [...arr].reverse();
来源：http://dali.yongpay.top/Article/details/gt2ezqovejz.html

Java: Collections.reverse(list);
来源：http://dali.hammf.cn/Article/details/gt2ozqrdulj.html

Go:   slices.Reverse(arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fytnngaj.html

Ruby: arr.reverse
来源：http://dali.zycfv.cn/Article/details/gt2gonzhjzg.html

C#:   list.Reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gt2rirmovej.html

[D12] 查找元素下标
来源：http://dali.chenlongwang.top/Article/details/gt2ozmqikhm.html

Py:   arr.index(x);  x in arr
来源：http://dali.chenjidiqi.icu/Article/details/gt2bmyfycqa.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gt2aeribdmm.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dianchejie.cn/Article/details/gt2gihhnhpp.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2znzawbph.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.wangdashe.top/Article/details/gt2mctdzdnd.html

Go:   slices.Index(arr, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2waohubyb.html

Ruby: arr.index(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2gpnrkzdy.html

C#:   list.IndexOf(x);
来源：http://dali.hfpthk.cn/Article/details/gt2flqjntcb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.daxiang520.top/Article/details/gt2tbxblhps.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgfzy.top/Article/details/gt2bewjngxn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wkntbccj.html

JS:   arr.filter(x => x > 3)
来源：http://dali.sufxvd.cn/Article/details/gt2fbqqjktx.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gt2bzrpjwbz.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsxvwgqi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pmxlrzjs.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.snrcjt.cn/Article/details/gt2fwongwlg.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhoulong.xyz/Article/details/gt2ymfdvoel.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fvmfbopx.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gt2rrxhcqlk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.tianlin.xyz/Article/details/gt2ndfdlnfp.html

JS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2dhbkquqa.html

TS:   arr.map(x => x * 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2plzbqnbx.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.c1oappe.top/Article/details/gt2jhixusbu.html

Go:   // 手写循环
来源：http://dali.yuanzhike.top/Article/details/gt2nsgotmmb.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.yj202588.top/Article/details/gt2cpilulmz.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yueranfly.top/Article/details/gt2auhqyorx.html

[D15] 去重
来源：http://dali.yanxiufei.cn/Article/details/gt2epqgqryz.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gt2faxbfwmg.html

PHP:  array_unique($arr);
来源：http://dali.yj20258888.top/Article/details/gt2umrlgrsd.html

JS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gt2wtogcmyv.html


<!-- 参考信息 -->