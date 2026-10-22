代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtpuymragl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtwrpsqted.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtugcfomvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtfrvhmezq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtkzbzhrqn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gthkhrzmnx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj20258.top/Article/details/gtyxgxizdj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcjalkpir.html

[C02] 默认参数
来源：http://dali.cqqwz.cn/Article/details/gtsyekjelh.html

Py:   def greet(name="World"): return name
来源：http://dali.yj202588.top/Article/details/gtmjbkswcx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtyszkepzw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtcdwukiln.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcnmnykrm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jlsjyb.cn/Article/details/gtkhsbqkje.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtkoglpirm.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspndtwqu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtvrdemlwy.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtlfjyxrej.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtquutyjjy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gtpoqvyifb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtixjkjwlq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtmmdprnky.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gtidbfnpyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sysykeji.top/Article/details/gtkfihfsnm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtkhqzplye.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtietxhjet.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtutkywonc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtnodvwnzq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gtjmuvgoyx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfeugnwaz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gtptovwims.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtwqukpsli.html

Go:   // 无：用配置结构体参数
来源：http://dali.hfpthk.cn/Article/details/gtyeuhwqtc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtdgpyowxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtsbsziqvv.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gteazphsib.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtdnuawrfb.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gttxtfowfh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzozmzzmd.html

TS:   return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gtifkabhxb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gtulivseil.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtbjarjona.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtresteczl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gtfdlsmlio.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtmvrlkcfc.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtvvjxsnuz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtdagesedw.html

JS:   const square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtxxbpwitw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtahmjeher.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtrycatjen.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsunzxgoy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtgukblpdb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ivvv.top/Article/details/gtdsdbixic.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtkjsuwnji.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtizgjvzuw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xziqi.cn/Article/details/gtramqrqec.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.0kj1m.cn/Article/details/gtbzmuaexo.html

TS:   arr.map(String)
来源：http://dali.yangfankeji.com/Article/details/gtidawnrgx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenzaomai.com/Article/details/gtfawmzupn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgfzy.top/Article/details/gtbrwndcgr.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtsrbvaxif.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daxiang520.top/Article/details/gthnaeraoo.html

[C08] 闭包
来源：http://dali.bjfxy.top/Article/details/gtceoyxcvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.gotoacloud.top/Article/details/gtafhiossr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtuircunop.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtkvgppzaf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtyknnfbjr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtbygzaert.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtnnfjrcoy.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yangfankeji.com/Article/details/gtifuuneqx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gthczvqdea.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtavgfluad.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtobjffhrs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtksithams.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtxqdweyyf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtqvshubfq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gttpjfrtan.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.haohaochexian.top/Article/details/gtpextnocy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gtrpqvkjxz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gtvcfevlih.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtpiwqhwlh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqsurhsn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtbqdctmub.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtrekpuule.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtxolllqxn.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtyizhtruu.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtxqqwsgxi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jiagoushi.top/Article/details/gtbsbvvlae.html

C#:   块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtbwdnvaat.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtjcrffows.html

Py:   from module import func
来源：http://dali.yangfankeji.com/Article/details/gtvcpydexd.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtogighnhu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gtpbylbvrd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gtmycaguta.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfzayuth.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpxsldtg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yonumen.top/Article/details/gtjitsjdxe.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtqiitegmm.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangshuangyany.cn/Article/details/gtbxsfodey.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtlamyhrdh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gtdjxqxrfv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hfpthk.cn/Article/details/gtbqxykopv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.wangshuangyany.cn/Article/details/gtigzagvhg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtozxcwdqi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtclpzprcq.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtjrgkvrki.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtdtskapkf.html

[C13] 类型声明 / 类型注解
来源：http://dali.cheryme.top/Article/details/gtakbqvijw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtvzcrkpnv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gterunxsul.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jyoumei.cn/Article/details/gtxlhmsdnz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtuaeyemsr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtluctiizc.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gteebdalzu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.fzhhl.top/Article/details/gtqukmvseh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtfpetsmlk.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtohkjdhkl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuispwvza.html

PHP:  // 无泛型
来源：http://dali.yongpay.top/Article/details/gtjkipzaem.html

JS:   // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtzcneqsgw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtyobqmowz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gotoacloud.top/Article/details/gtgaxmspbl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtyevyzvoq.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtwswuzwdj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xylfe.cn/Article/details/gtxfgghsbh.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtctsynwwn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gtojehaygg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gtxevobuih.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtuojxtaqh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtvmssdtwv.html

Java: // 无解构
来源：http://dali.xinyue.icu/Article/details/gtzvdwclii.html

Go:   // 无解构
来源：http://dali.smart0.xyz/Article/details/gtkoqanist.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtnkmsyxvw.html

C#:   var (a, b) = pair;
来源：http://dali.ydzc1.top/Article/details/gtwffetmgk.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtdzykcjun.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtmglbqzje.html

PHP:  // 无重载
来源：http://dali.wangdashe.top/Article/details/gthtbjgpew.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sufxvd.cn/Article/details/gtvkubqqkz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.316326.xyz/Article/details/gtooikmotp.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfjzrpzmu.html

Go:   // 无重载：用不同函数名
来源：http://dali.xziqi.cn/Article/details/gtzkipfrqi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yanxiufei.cn/Article/details/gtwfzdkeov.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtjhvxamrt.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzvgeabwa.html

D. 数组 / 列表 / 集合
来源：http://dali.yanxiufei.cn/Article/details/gtcmozfcrp.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtfzywrfsv.html

[D01] 创建数组 / 列表
来源：http://dali.cqqwz.cn/Article/details/gtxucgrxvu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hfpthk.cn/Article/details/gtjqifvwsv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nwbrower.top/Article/details/gtdovgzdjy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtokjeauto.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtqxkchrxf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhongyouzk.top/Article/details/gthrrnmvgz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.guannengcc.top/Article/details/gtulrhkmjg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtcfjqsgab.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtgqtwofga.html

[D02] 追加元素到末尾
来源：http://dali.andypj.xyz/Article/details/gtizgyjnwj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtkfizqbul.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.daria6918.cn/Article/details/gtsfyvaliz.html

JS:   arr.push(4);
来源：http://dali.jyoumei.cn/Article/details/gtgvolizsf.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtokiavyld.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtrknaizno.html

Go:   arr = append(arr, 4)
来源：http://dali.sxryk.cn/Article/details/gtjvhskqts.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gttndlfxfd.html

C#:   list.Add(4);
来源：http://dali.yvedp.cn/Article/details/gtsllfmpkz.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gthptoldqf.html

Py:   arr.insert(0, 0)
来源：http://dali.9152youxi.cn/Article/details/gtosrtgsyw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.havefunace.top/Article/details/gtjvocnbvy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtatqysini.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aibaodan.cn/Article/details/gtwjoaalal.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtcppheafp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwjwvncoj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jinqigfzy.top/Article/details/gtzkiijeod.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtnnoqgkxg.html

[D04] 删除元素
来源：http://dali.ydzc1.top/Article/details/gtvzjshkfo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gtryegahru.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtkaisxzjh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtxsfcjbhw.html

TS:   arr.splice(0, 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtljuneaqj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtacbnpmzv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fzhhl.top/Article/details/gtaekzaaat.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtnbhxczph.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jianghu66.top/Article/details/gtrlhzvsgg.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtlfrnnhlb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gtpvezxjnq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtybzqoabe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtewfgakwd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtmdkozwmb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.daxiang520.top/Article/details/gtafoykorj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ivvv.top/Article/details/gtdaqfafnx.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gthggwlzbu.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yangfankeji.com/Article/details/gttnphhdmr.html

[D06] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtylkfjaim.html

Py:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gtzugruysk.html

PHP:  count($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtrohvrzzj.html

JS:   arr.length
来源：http://dali.andypj.xyz/Article/details/gtaxmvcpes.html

TS:   arr.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtivfavjhq.html

Java: list.size();
来源：http://dali.yvedp.cn/Article/details/gtglowqhdt.html

Go:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtqyfpumjd.html

Ruby: arr.length; arr.size
来源：http://dali.chenlongwang.top/Article/details/gtbngybiyp.html

C#:   list.Count;
来源：http://dali.pengpengdd.cyou/Article/details/gthiajcmak.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gtagqcxuxr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtlizccytq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.nwbrower.top/Article/details/gtsspbhtui.html

JS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtjhtafmfj.html

TS:   arr.slice(1, 4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorzjeyzt.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtipctrqil.html

Go:   arr[1:4]
来源：http://dali.ydzc1.top/Article/details/gtxsssnyfv.html

Ruby: arr[1, 3]
来源：http://dali.sysykeji.top/Article/details/gtiuxyiwwi.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhongyouzk.top/Article/details/gtgxzsixzs.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gtvdvsvaod.html

Py:   a + b;  a.extend(b)
来源：http://dali.aizwys.cn/Article/details/gtlkmaczsp.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gttvgzvjfn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtsfxnurap.html

TS:   [...a, ...b];
来源：http://dali.zhijiandao.cn/Article/details/gtuixtbeer.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.fengsongda.top/Article/details/gtgmanknzm.html

Go:   append(a, b...)
来源：http://dali.aibaodan.cn/Article/details/gtfbdpwucz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gzhubu.top/Article/details/gtshixrgdj.html

C#:   a.Concat(b).ToList()
来源：http://dali.zycfv.cn/Article/details/gtiqxgprsy.html

[D09] 排序（升序）
来源：http://dali.jiagoushi.top/Article/details/gtxolljyob.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shanyushiyangtech.top/Article/details/gtutzmgxds.html

PHP:  sort($arr);
来源：http://dali.gaohongyu789.top/Article/details/gthrqdjrms.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtsomeumxn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jlsjyb.cn/Article/details/gttsotfujc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xylfe.cn/Article/details/gtunzqimjn.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgtcascyu.html

Ruby: arr.sort
来源：http://dali.snrcjt.cn/Article/details/gtgqbatljp.html

C#:   list.Sort();
来源：http://dali.hongshengwenyu.top/Article/details/gtzgbtkehw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenzaomai.com/Article/details/gtkwcuyxnd.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hnqzz.top/Article/details/gthybsqpsa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gtpaxkiphg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtxwqbrqbp.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxzdraog.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtwzkkwjiz.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenzaomai.com/Article/details/gtloagalva.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtauhydffe.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtaikrltjg.html

[D11] 反转数组
来源：http://dali.yj202588.top/Article/details/gtkpbkcclu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hysaishi.cn/Article/details/gthbgyqvdg.html

PHP:  array_reverse($arr);
来源：http://dali.cqqwz.cn/Article/details/gtzuzjfzsw.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.tanke756.top/Article/details/gtjeyomczq.html

TS:   [...arr].reverse();
来源：http://dali.sweek.top/Article/details/gtzqqvaqbx.html

Java: Collections.reverse(list);
来源：http://dali.sufxvd.cn/Article/details/gtculcouki.html

Go:   slices.Reverse(arr)
来源：http://dali.svipenyu.cn/Article/details/gtvvbccrea.html

Ruby: arr.reverse
来源：http://dali.jqgufenzy.top/Article/details/gtdddddzwr.html

C#:   list.Reverse();
来源：http://dali.gzhubu.top/Article/details/gtjyzpngrb.html

[D12] 查找元素下标
来源：http://dali.nanxuanxn.top/Article/details/gtgqgiuymw.html

Py:   arr.index(x);  x in arr
来源：http://dali.redwolf501.top/Article/details/gtuwezuzrq.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtszrphmuw.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hywenlv.cn/Article/details/gtgpvdqssq.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gogol.net.cn/Article/details/gtfccrbkws.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.yj202588.top/Article/details/gtsjugcsej.html

Go:   slices.Index(arr, x)
来源：http://dali.pycfn.com/Article/details/gtadyjnxzj.html

Ruby: arr.index(x)
来源：http://dali.nanxinkj.top/Article/details/gttrdpqysb.html

C#:   list.IndexOf(x);
来源：http://dali.aibaodan.cn/Article/details/gtpuyvaezf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.yuanzhike.top/Article/details/gtztymgdad.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.chenlongwang.top/Article/details/gthiwsbgis.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gogol.net.cn/Article/details/gtbghpelii.html

JS:   arr.filter(x => x > 3)
来源：http://dali.jqgfzy.top/Article/details/gtyuuopwms.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xylfe.cn/Article/details/gtzqshtncw.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtxfwrexjw.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdurifczq.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.wangshuangyany.cn/Article/details/gtucrohlty.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.xylfe.cn/Article/details/gtwvlmjyit.html

[D14] 映射转换（每个元素变形）
来源：http://dali.guowangkeji.top/Article/details/gtquebtgxu.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.ybcxt.top/Article/details/gtlylzqqpl.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yuanzhike.top/Article/details/gtpovmnezn.html

JS:   arr.map(x => x * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtejmpmxkm.html

TS:   arr.map(x => x * 2)
来源：http://dali.hfpthk.cn/Article/details/gtexjqmwtu.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.sxryk.cn/Article/details/gtpkcyvjgx.html

Go:   // 手写循环
来源：http://dali.cheryme.top/Article/details/gtheiuaeiq.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtbhtcwqwu.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.cucudq.cn/Article/details/gtjvforqsf.html

[D15] 去重
来源：http://dali.cheryme.top/Article/details/gtuexbpadq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.jianghu66.top/Article/details/gtznpeawgz.html

PHP:  array_unique($arr);
来源：http://dali.tanke756.top/Article/details/gtrknznkwr.html

JS:   [...new Set(arr)]
来源：http://dali.smart0.xyz/Article/details/gtixfaiczf.html

TS:   [...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gtgrrtutio.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.gzhubu.top/Article/details/gtprparilk.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.jianghu66.top/Article/details/gtvbzvwyww.html

Ruby: arr.uniq
来源：http://dali.daxiang520.top/Article/details/gtymetxcrn.html

C#:   list.Distinct().ToList()
来源：http://dali.yuanzhike.top/Article/details/gtqyhyaist.html

[D16] 求和与平均值
来源：http://dali.birdmap.top/Article/details/gtiifawqnv.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtzghmvlzs.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.ydzc1.top/Article/details/gtubgqvtfr.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.yueranfly.top/Article/details/gtotgynvvd.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ybcxt.top/Article/details/gtsqkbhzmc.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.fzhhl.top/Article/details/gtvidcqpik.html

Go:   // 手写循环累加
来源：http://dali.zhoulong.xyz/Article/details/gtvczmttcm.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.havefunace.top/Article/details/gtvobkqkle.html

C#:   list.Sum();  list.Average()
来源：http://dali.shangyingyoupin.top/Article/details/gtlfrkmdht.html

[D17] 最大值与最小值
来源：http://dali.kuanghao11.cn/Article/details/gtoplvqkxw.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gtsxgxipre.html

PHP:  max($arr);  min($arr);
来源：http://dali.sxryk.cn/Article/details/gtzjqaogob.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqbkrcmb.html

TS:   Math.max(...arr);
来源：http://dali.yanxiufei.cn/Article/details/gtoqrkbzvb.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.sufxvd.cn/Article/details/gtgxudptgo.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.havefunace.top/Article/details/gtfdjopmeg.html

Ruby: arr.max;  arr.min
来源：http://dali.nanxuanxn.top/Article/details/gtnmyjcyms.html

C#:   list.Max();  list.Min()
来源：http://dali.bjfxy.top/Article/details/gthjksgckb.html

[D18] 扁平化嵌套数组
来源：http://dali.andypj.xyz/Article/details/gtjoadexbq.html


<!-- 参考信息 -->