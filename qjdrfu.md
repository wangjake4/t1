代发 wailian999

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2kifredho.html

Ruby: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2gghizdbl.html

C#:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2uvtowjas.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yuqccmtz.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gt2avjtkqmf.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gt2nzvrzitk.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2krzmhyzl.html

TS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gt2bmuxxivi.html

Java: if (data == null) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bunxjlmx.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gt2ygrggayl.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gt2iqffufbs.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2pkmllsfn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2inywrsli.html

C. 函数与作用域
来源：http://dali.xziqi.cn/Article/details/gt2ytivytdk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2bhmiwwpj.html

[C01] 定义函数
来源：http://dali.ybcxt.top/Article/details/gt2crafzesm.html

Py:   def add(a, b): return a + b
来源：http://dali.ehwqpu.com/Article/details/gt2ipqyenig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gt2pmosvuzi.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2sydyahfu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2sgizutdh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nskbeebj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tianlin.xyz/Article/details/gt2pxkyjfav.html

Ruby: def add(a, b); a + b; end
来源：http://dali.quarkkingdee.top/Article/details/gt2imtvyhcg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2lyaxzbwy.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcaoyakg.html

Py:   def greet(name="World"): return name
来源：http://dali.yuxming.cn/Article/details/gt2oxuhgchc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qqnckuqg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qicfvjxh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2kzibfeqx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gt2gfnlabvw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhongyouzk.top/Article/details/gt2gimakwww.html

Ruby: def greet(name = "World") = name
来源：http://dali.yuxming.cn/Article/details/gt2zjkycwlq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gt2rvammxdo.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gt2yarwuaho.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gt2oyyctzqf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nirhrhmu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gt2gcgiamiu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2bgtpdbtv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gt2zapmxjzj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gt2kcklvsmy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tian-w.cn/Article/details/gt2gvakeavd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2atqsgngm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zdqjudy.top/Article/details/gt2wyjkaczs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2xiizasgy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2tzctscns.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gt2vdibbvch.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gt2ocevquqg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2eyrjdgbx.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gt2sakwwxcv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2fybwglhf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ofgjyomh.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gt2ehccasye.html

Py:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2tpiquijb.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2vglqeabv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gt2ctvcpzlc.html

TS:   return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gt2gybkiihu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shuidangran.top/Article/details/gt2ffcxklsd.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gt2psyliylr.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gt2wbhpzijw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gt2mhgupesp.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gt2dldhvdoo.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gt2dqysaoug.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2sskznqxz.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gt2jwirfalf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gt2qcgyplgg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nveoxeur.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2eivlrbnt.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ijqewyob.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptvjvlee.html

[C07] 把函数作为参数传入
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2euurjpvg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fengsongda.top/Article/details/gt2hkmoqdpx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2iwbmnsyc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xziqi.cn/Article/details/gt2kvfabixm.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gt2rxtzizga.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gt2lswvvcau.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuxming.cn/Article/details/gt2ilipcpqm.html

Ruby: arr.map(&:upcase)
来源：http://dali.redwolf501.top/Article/details/gt2cfgkiqjg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shuidangran.top/Article/details/gt2pjllxabn.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ilipvtzs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gt2hqubfcpc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jiagoushi.top/Article/details/gt2jlwrzccv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gt2spdauqkr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2hfkxxadh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cucudq.cn/Article/details/gt2yzlfzgxf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gt2erfknepv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hammf.cn/Article/details/gt2rbjbsvvl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hggrlypl.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2cxepkvyv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2rniatzql.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ievsulcy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gt2gcfpdper.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qpqacctt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gt2qhuivzhu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gt2nryocdpb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jyfgxqlj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gt2shdtyrlr.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gt2vczlgbdq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gt2viepxrcg.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gt2xkdvwwkm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yongpay.top/Article/details/gt2achvcjwe.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gt2fqikyqip.html

Java: 方法内为块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gt2gdphxwuk.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2nntlnutj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gt2rqrwmspa.html

C#:   块级作用域
来源：http://dali.xuanzx.com/Article/details/gt2axkjkgzr.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gt2uiedgghx.html

Py:   from module import func
来源：http://dali.andypj.xyz/Article/details/gt2tnjhxyxm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2impdpoxz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gt2igtfcqcm.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gt2bbwmmmzf.html

Java: import java.util.List;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fdpajtbu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2zmoizevt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gt2ccyrasbn.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2dswswdjq.html

[C12] 立即执行函数 IIFE
来源：http://dali.zdqjudy.top/Article/details/gt2zhbfgkkm.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gt2kfjjqwau.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sysykeji.top/Article/details/gt2pkocouqd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jiagoushi.top/Article/details/gt2fgbcdhid.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gt2ppogrzqg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gt2sdesdbjz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gt2fabeibks.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gt2lzjewsyb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2rvnyuerr.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gt2knyuigpa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2mprxbpgh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2meufvpfc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gt2ekibircy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2toazmlej.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2mgyoadok.html

Go:   func add(a, b int) int
来源：http://dali.daria6918.cn/Article/details/gt2arduheav.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gaohongyu789.top/Article/details/gt2eyluodlr.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gt2rferiaky.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gt2dsagyjse.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guowangkeji.top/Article/details/gt2mbhbzvmf.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2qwblwreq.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gt2ayrlvijb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gt2uekswpyf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gt2iyohhawr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gt2ukwhlcde.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2cgqwfvwr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yongpay.top/Article/details/gt2tnpsdcud.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gt2yvpparrh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gt2xljoydyc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dashuyun.cn/Article/details/gt2zghgmlej.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2kluszhfd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gt2cihtjbsb.html

Java: // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2awhqpjln.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2lwaeasgo.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gt2ncbmtamb.html

C#:   var (a, b) = pair;
来源：http://dali.jinqigfzy.top/Article/details/gt2cmzxxjbc.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gt2srrwyemb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jyoumei.cn/Article/details/gt2hinwvqzd.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gt2tannclas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fzhhl.top/Article/details/gt2gvcpckpe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gt2ajjunoxg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gt2eunycjrm.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gt2aklwaihp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shzxlz.cn/Article/details/gt2rjxpyofy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gt2yiaeoqcm.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2hcwtnwsu.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gt2fgiymtaz.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2bbapipue.html

[D01] 创建数组 / 列表
来源：http://dali.tianlin.xyz/Article/details/gt2qqeaknqh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gt2cbzabzxg.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2muzbizxw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gt2lzsaeprn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.guannengcc.top/Article/details/gt2cexedqts.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gt2lmfahjax.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhengqikj.top/Article/details/gt2noysqorb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.0kj1m.cn/Article/details/gt2nxszafoa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yj20258888.top/Article/details/gt2incgpyqk.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hinfswyz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.9152youxi.cn/Article/details/gt2bqhbmfxp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.9152youxi.cn/Article/details/gt2vqicksvw.html

JS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gt2lgnrzlaw.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gt2itsbbbip.html

Java: list.add(4);
来源：http://dali.ybcxt.top/Article/details/gt2sdynetow.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gt2bbrcjfih.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.dashuyun.cn/Article/details/gt2soyuswwa.html

C#:   list.Add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2xhsumbck.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gt2zcufxntd.html

Py:   arr.insert(0, 0)
来源：http://dali.aizwys.cn/Article/details/gt2rtvthheg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnfepwv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.wangdashe.top/Article/details/gt2iscdeivy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gt2jjkmgmjp.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gt2klwntnlt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2khopwhzp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pvmjiteb.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2njjxuycy.html

[D04] 删除元素
来源：http://dali.jlsjyb.cn/Article/details/gt2moikjgbj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2pimedrfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gt2tdvyndyv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gt2xrnzztxv.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gt2cpjtwutf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gt2zuwuvbzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guannengcc.top/Article/details/gt2ylkrrvdy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.316326.xyz/Article/details/gt2stfopfsp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cdnleiting.top/Article/details/gt2yawekdas.html

[D05] 访问与修改元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2obugnsep.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2jlnrchkd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2sgplarhw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2sjagtiuq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbtmzrw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gt2typyrqdw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gogol.net.cn/Article/details/gt2qvodzhxx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2fansincc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjsjjtyo.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gt2psydopjt.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkwbtlxc.html

PHP:  count($arr);
来源：http://dali.jqgufenzy.top/Article/details/gt2gajyewcg.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gt2abgcoury.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gt2svwpeceg.html

Java: list.size();
来源：http://dali.dianchejie.cn/Article/details/gt2kprfkdlj.html

Go:   len(arr)
来源：http://dali.daria6918.cn/Article/details/gt2ectvikeq.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gt2sjgyyunn.html

C#:   list.Count;
来源：http://dali.sufxvd.cn/Article/details/gt2yticzjpt.html

[D07] 切片 / 取子数组
来源：http://dali.yuxming.cn/Article/details/gt2dqpbtupk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gt2nxdeavje.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.smart0.xyz/Article/details/gt2adntjmea.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2pyardhzg.html

TS:   arr.slice(1, 4);
来源：http://dali.mhx1999.top/Article/details/gt2lnmdzyjn.html

Java: list.subList(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gt2ltltdfwx.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gt2ljkpcukh.html

Ruby: arr[1, 3]
来源：http://dali.redwolf501.top/Article/details/gt2mpirmeio.html

C#:   list.GetRange(1, 3);
来源：http://dali.shuidangran.top/Article/details/gt2nkfhslji.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gt2smkxsvbw.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gt2yhltibfw.html

PHP:  array_merge($a, $b);
来源：http://dali.yuxming.cn/Article/details/gt2hycomkgb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gt2fgcqmywo.html

TS:   [...a, ...b];
来源：http://dali.cheryme.top/Article/details/gt2adfcxfpa.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.vqdsnc.cn/Article/details/gt2hcebgmie.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gt2ioqjthej.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dczlcots.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhiwuduotai.top/Article/details/gt2fgeuvynl.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gt2efrcpwcz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gt2yjwalgsi.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gt2bzlkajeq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yonumen.top/Article/details/gt2lhwgpsnf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.wangdashe.top/Article/details/gt2csavyyvj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.ydzc1.top/Article/details/gt2sqqhbxqn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gt2edxguvrp.html

Ruby: arr.sort
来源：http://dali.zhoulong.xyz/Article/details/gt2dwjvoftt.html

C#:   list.Sort();
来源：http://dali.jinqigufen.top/Article/details/gt2ewuvphdp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shzxlz.cn/Article/details/gt2sasxjtjo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2rbxeogxp.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gt2wvbzmmoj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.gotoacloud.top/Article/details/gt2sqgkzdyz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.haohaochexian.top/Article/details/gt2fzsoytrt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.nanxinkj.top/Article/details/gt2uzebgoif.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gt2afgtzoml.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zycfv.cn/Article/details/gt2ksjwmbxm.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ylfteifb.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gt2krkvobhl.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.guannengcc.top/Article/details/gt2eycexsjk.html

PHP:  array_reverse($arr);
来源：http://dali.nwbrower.top/Article/details/gt2fxxxauaj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.fengsongda.top/Article/details/gt2yyloppzu.html

TS:   [...arr].reverse();
来源：http://dali.chenjidiqi.icu/Article/details/gt2rrwkdouc.html

Java: Collections.reverse(list);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ncoapwgu.html

Go:   slices.Reverse(arr)
来源：http://dali.shzxlz.cn/Article/details/gt2rrmkhztz.html

Ruby: arr.reverse
来源：http://dali.svipenyu.cn/Article/details/gt2iqzfbwhu.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gt2ouytoqov.html

[D12] 查找元素下标
来源：http://dali.jinqigfzy.top/Article/details/gt2redkaajj.html

Py:   arr.index(x);  x in arr
来源：http://dali.hywenlv.cn/Article/details/gt2mtfbykki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.yanxiufei.cn/Article/details/gt2qwyxferu.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhixingplan.top/Article/details/gt2krmjwanm.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpsqmmfy.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.daria6918.cn/Article/details/gt2kxqhsfzo.html

Go:   slices.Index(arr, x)
来源：http://dali.yanxiufei.cn/Article/details/gt2kvzblvwf.html

Ruby: arr.index(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ubrzjldm.html

C#:   list.IndexOf(x);
来源：http://dali.zhixingplan.top/Article/details/gt2kqvxidyr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.wangshuangyany.cn/Article/details/gt2mmgswwnl.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yj20258888.top/Article/details/gt2wjdymsbk.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.guannengcc.top/Article/details/gt2gqcargyc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hnxiangtu.top/Article/details/gt2kceekpog.html

TS:   arr.filter(x => x > 3)
来源：http://dali.quarkkingdee.top/Article/details/gt2bgoqgqpi.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2vdaygffp.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.tianlin.xyz/Article/details/gt2efmrjigl.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.jianghu66.top/Article/details/gt2hhveweef.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.daria6918.cn/Article/details/gt2nilydejy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.xylfe.cn/Article/details/gt2koteetbi.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.fengsongda.top/Article/details/gt2imqorbcb.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2voilmunf.html

JS:   arr.map(x => x * 2)
来源：http://dali.tianlin.xyz/Article/details/gt2prlbenue.html

TS:   arr.map(x => x * 2)
来源：http://dali.0kj1m.cn/Article/details/gt2kqyqoivu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2nkvfynci.html

Go:   // 手写循环
来源：http://dali.pycfn.com/Article/details/gt2slshaeqg.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ivvv.top/Article/details/gt2gzjqgcjh.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gt2psmmkhts.html

[D15] 去重
来源：http://dali.ybcxt.top/Article/details/gt2rzxeqdtu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmndcfgs.html

PHP:  array_unique($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gt2hdkimgok.html

JS:   [...new Set(arr)]
来源：http://dali.cdnleiting.top/Article/details/gt2gyluulnl.html

TS:   [...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2lmiibjnv.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.cucudq.cn/Article/details/gt2jgfyzbhg.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.zhengqikj.top/Article/details/gt2xdjzijbu.html

Ruby: arr.uniq
来源：http://dali.chenjidiqi.icu/Article/details/gt2nqnmojev.html

C#:   list.Distinct().ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2uiengumf.html

[D16] 求和与平均值
来源：http://dali.ydzc1.top/Article/details/gt2mgzzerki.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2yhbdjyfh.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.zhijiandao.cn/Article/details/gt2hovrauza.html


<!-- 参考信息 -->