代发 wailian999

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aizwys.cn/Article/details/gtxvapazzf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cheryme.top/Article/details/gtjzeolzgj.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gtmtwsicmh.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtqkzjcscx.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtslknbdvo.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtsesqzilo.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtyswsdrvq.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtvpqkggor.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtfygsltiu.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtkjzmizrf.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gteqxvuibz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtjmozoblf.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gtfjhxviwd.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtldpbhdhl.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gttkmnvbcl.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtrgnpwexr.html

Java: if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtpzmbyrkd.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtleytnqbx.html

Ruby: return if data.nil?
来源：http://dali.shangyingyoupin.top/Article/details/gtflljgrmz.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtaduvycyc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gttvnfhakt.html

C. 函数与作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlsbzbea.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtmyjoepzp.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtogluuard.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gtcpwvmjbb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gteablczpm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtzmnefruq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtyngpanol.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtbwdgfhvl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gtfhlrbamr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtlclwjhoj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtbjtzasfn.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gtcsgwmqqc.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtdffmowrj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtxklenrba.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtikxdeahz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtbvzneevs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenjidiqi.icu/Article/details/gtwauxmghp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gtkaibpewm.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gthbkaygur.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtmaqtmbmo.html

[C03] 可变参数
来源：http://dali.smart0.xyz/Article/details/gtiwmgecaq.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtyhhgkqmr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtyhoqvlyl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtkedmocku.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gthtlfdtpe.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtcpanyeic.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yanxiufei.cn/Article/details/gtikoqtetn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.316326.xyz/Article/details/gtclhpcwnc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtwajypwyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gtaggbbrwv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtenwnngkx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtrvvnduvv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.iojbl.cn/Article/details/gtqzpdvgai.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtuywrajow.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yueranfly.top/Article/details/gtrmeauqvc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtarlkornv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxkhcqoy.html

C#:   f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtnuynhsjb.html

[C05] 返回多个值
来源：http://dali.kuanghao11.cn/Article/details/gtlcfmswki.html

Py:   return a, b
来源：http://dali.cashguo.top/Article/details/gtwrsbskzo.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gttloxxdna.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gttwygunpp.html

TS:   return { a, b };
来源：http://dali.hnxiangtu.top/Article/details/gtzhmntcbr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtztmwtemr.html

Go:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtgjcnnopk.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtalkgvohy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtfeazzqpt.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtuyqmcbwn.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gthplucbvs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtbqeswlga.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gttawzomtt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258888.top/Article/details/gtuwexqnld.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gtktmfvwsu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnqzz.top/Article/details/gthtryqjpy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hfpthk.cn/Article/details/gtetvacgkd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtnjbljqmb.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtuhkoqyge.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ppjwa.cn/Article/details/gtllyqguek.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoupkgatt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gthhooktcz.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgveauiab.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtrbgaogmk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdmftvea.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj202588.top/Article/details/gtfekrgcuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yangfankeji.com/Article/details/gtluuhtrps.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtnrntsyln.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tian-w.cn/Article/details/gtacpzfkwm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgdezatz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtpgohkzau.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtryzlbywn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtyihjifqp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtyyipeadc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtlfyureay.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gturbimgbt.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtygkydcyq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtawfetibr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtclivokuw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gtaxykbmcu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtuohcwpgg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.smart0.xyz/Article/details/gtgevachxl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtoobqxrsl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtzvfclayq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtpruexolr.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtbvtgdyex.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtkehrximb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yongpay.top/Article/details/gtelmdzpav.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtgxolfsio.html

TS:   同 JS
来源：http://dali.havefunace.top/Article/details/gtlegyjmta.html

Java: 方法内为块级作用域
来源：http://dali.fzhhl.top/Article/details/gtggyblhrg.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqrzviemi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gtejtmrpsj.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtwvzgjgwd.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtvyyzopia.html

Py:   from module import func
来源：http://dali.hysaishi.cn/Article/details/gtwynxeyft.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgfzy.top/Article/details/gtygrhltcz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtigbfetwd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtfctiozfk.html

Java: import java.util.List;
来源：http://dali.havefunace.top/Article/details/gtlljagjhq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhiwuduotai.top/Article/details/gtwssulrjo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfovxxkcc.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtekuthcxr.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtnftgcedt.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtfvjqafcj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtktlfsjvj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjwpfpla.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtvroafvse.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aizwys.cn/Article/details/gtopjizmam.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtabkrawul.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtbxyvdazn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gtetuapvdu.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtwbonxiwx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtfsrnbtyd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtsqruswhs.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhiwuduotai.top/Article/details/gtwfvkafug.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtfohjeinb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefibqqkc.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtcdqptwlj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.quarkkingdee.top/Article/details/gtndykjaqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ppjwa.cn/Article/details/gtsivqlnhz.html

[C14] 泛型函数
来源：http://dali.chenlongwang.top/Article/details/gtrouggwlm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtbrhsxoxk.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtjgcvkbyf.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtunkxcgpj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gthlvolgol.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gthedllqvq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pycfn.com/Article/details/gthgalihws.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gttfaazweh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkplyehs.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfpqaeap.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtkhqfrhai.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtozoissks.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtgqarpnsm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yongpay.top/Article/details/gtbkedvgtz.html

Java: // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtswbhzzzw.html

Go:   // 无解构
来源：http://dali.birdmap.top/Article/details/gtetxxrsyx.html

Ruby: a, b = pair
来源：http://dali.smart0.xyz/Article/details/gtzyuupxob.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtulrsjzne.html

[C16] 函数 / 方法重载
来源：http://dali.wangdashe.top/Article/details/gtjcnvxhnl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtuuttlxpq.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtrfilsnak.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.iojbl.cn/Article/details/gtcaaimvqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ydzc1.top/Article/details/gtzwlxzftd.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hywenlv.cn/Article/details/gtrhwnwgfr.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtfotkvoyj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ehwqpu.com/Article/details/gtqzzadnwm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gtqkotcbvi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjgzzuwrg.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gttfwtntou.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtyztfxtpt.html

[D01] 创建数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtwqsdzokb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj202588.top/Article/details/gthrmknryu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xziqi.cn/Article/details/gtqezneano.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinghuilouyu.cn/Article/details/gtglqnfohm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtnwztewxj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenlongwang.top/Article/details/gtfynmbifv.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtfyrfxiuv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtitmypniw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sweek.top/Article/details/gthlzoqkxn.html

[D02] 追加元素到末尾
来源：http://dali.birdmap.top/Article/details/gtnkyynnza.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.316326.xyz/Article/details/gtdekqgtgb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gtcwkepbnd.html

JS:   arr.push(4);
来源：http://dali.fzhhl.top/Article/details/gtajqlbxwt.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtqxwbdlwi.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtkvbjlkci.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtngwaffcs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.smart0.xyz/Article/details/gtadqfhkgu.html

C#:   list.Add(4);
来源：http://dali.wangshuangyany.cn/Article/details/gttotmmhnk.html

[D03] 在指定位置插入元素
来源：http://dali.sysykeji.top/Article/details/gtionbvuiu.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gtkwycoosb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtiivamiqf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.9152youxi.cn/Article/details/gtngrqqqpc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtdlbwgniu.html

Java: list.add(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtwigtbsqw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ppjwa.cn/Article/details/gtzgcdziyc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtsvjufkdo.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtorbukwth.html

[D04] 删除元素
来源：http://dali.tianlin.xyz/Article/details/gtpzzavokh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtlwboerhg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jlsjyb.cn/Article/details/gtcuyhgynt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ydzc1.top/Article/details/gtimcnqvuq.html

TS:   arr.splice(0, 1);
来源：http://dali.tianlin.xyz/Article/details/gtmproqhha.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtjqnkbyba.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtexvptdom.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jianghu66.top/Article/details/gtyzxkoybn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gtjiwkgpoc.html

[D05] 访问与修改元素
来源：http://dali.yueranfly.top/Article/details/gtiowvzaxr.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtnfjrdveo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtgnvpctuk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtfkertcfg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hnqzz.top/Article/details/gtltowzdto.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtmnzceccv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtucmasyxd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtbnvdlzjc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtljmjkfjd.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtnkdlnhal.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtqcuowdtu.html

PHP:  count($arr);
来源：http://dali.redwolf501.top/Article/details/gtxypjdkou.html

JS:   arr.length
来源：http://dali.yj20258888.top/Article/details/gtjqyzuqec.html

TS:   arr.length
来源：http://dali.bjfxy.top/Article/details/gtmacujxar.html

Java: list.size();
来源：http://dali.316326.xyz/Article/details/gtxmwdvujt.html

Go:   len(arr)
来源：http://dali.yonumen.top/Article/details/gtqwmpddks.html

Ruby: arr.length; arr.size
来源：http://dali.ivvv.top/Article/details/gtisgynkkp.html

C#:   list.Count;
来源：http://dali.jyoumei.cn/Article/details/gtvrnnfiot.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gtwgijejtc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.smart0.xyz/Article/details/gtsdowapxp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtbqcnbvbp.html

JS:   arr.slice(1, 4);
来源：http://dali.redwolf501.top/Article/details/gtimeifess.html

TS:   arr.slice(1, 4);
来源：http://dali.havefunace.top/Article/details/gthvcqrpux.html

Java: list.subList(1, 4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthudolvcl.html

Go:   arr[1:4]
来源：http://dali.ybcxt.top/Article/details/gtwdxmiqgj.html

Ruby: arr[1, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gtlgijywjc.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtstmsjwzh.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtyvgnjfix.html

Py:   a + b;  a.extend(b)
来源：http://dali.hywenlv.cn/Article/details/gtaxzzgswn.html

PHP:  array_merge($a, $b);
来源：http://dali.sxryk.cn/Article/details/gtakoedteq.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yanxiufei.cn/Article/details/gtibhemety.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtkhufvium.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yj20258.top/Article/details/gtxtgmfzbc.html

Go:   append(a, b...)
来源：http://dali.yongpay.top/Article/details/gtysvknkir.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhongyouzk.top/Article/details/gtcwhebdvz.html

C#:   a.Concat(b).ToList()
来源：http://dali.aizwys.cn/Article/details/gtmaqksqvo.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekamrvka.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yanxiufei.cn/Article/details/gtqcjdgmhn.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtgdtukuhi.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tanke756.top/Article/details/gtxecjdevo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.shangyingyoupin.top/Article/details/gtzqwmcfrf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.snrcjt.cn/Article/details/gttyeripid.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hnqzz.top/Article/details/gtzxqjxgsl.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtrzzwsiwa.html

C#:   list.Sort();
来源：http://dali.guowangkeji.top/Article/details/gtxvszwggc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zhixingplan.top/Article/details/gtsobuckhv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yonumen.top/Article/details/gtbmaeezwa.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ivvv.top/Article/details/gtojqzbrjw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtbmneohxm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hysaishi.cn/Article/details/gtcbyzytsy.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jinqigufen.top/Article/details/gtmdirbyqs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.aibaodan.cn/Article/details/gtbntwrbvo.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.ydzc1.top/Article/details/gtmkpiemlg.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xinyue.icu/Article/details/gtufhtlsot.html

[D11] 反转数组
来源：http://dali.zhoulong.xyz/Article/details/gtksmaojqr.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.cucudq.cn/Article/details/gtwlrkbgxp.html

PHP:  array_reverse($arr);
来源：http://dali.smart0.xyz/Article/details/gtfkexkdpz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yueranfly.top/Article/details/gtwkonelux.html

TS:   [...arr].reverse();
来源：http://dali.wangdashe.top/Article/details/gtvirapvji.html

Java: Collections.reverse(list);
来源：http://dali.ehwqpu.com/Article/details/gthcbkzuzc.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtgydxnbab.html

Ruby: arr.reverse
来源：http://dali.chenzaomai.com/Article/details/gtnvopozrn.html

C#:   list.Reverse();
来源：http://dali.smart0.xyz/Article/details/gtmqpezklm.html

[D12] 查找元素下标
来源：http://dali.meibo888.top/Article/details/gtkxlogila.html

Py:   arr.index(x);  x in arr
来源：http://dali.wangshuangyany.cn/Article/details/gtbhrwiyqr.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.meibo888.top/Article/details/gtuzxlmcvv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtyveckigu.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gaohongyu789.top/Article/details/gtjlzirdbb.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jqgufenzy.top/Article/details/gtiracyclb.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gttmsbljiw.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtahwjvwap.html

C#:   list.IndexOf(x);
来源：http://dali.feifeiyinyue.top/Article/details/gtkicxlwzf.html

[D13] 过滤（保留满足条件的）
来源：http://dali.kuanghao11.cn/Article/details/gtawwusedq.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.hfpthk.cn/Article/details/gtijrpfjck.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.gotoacloud.top/Article/details/gtyzgtjatw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.tian-w.cn/Article/details/gtrssztjiw.html

TS:   arr.filter(x => x > 3)
来源：http://dali.gzhubu.top/Article/details/gtncaobstf.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtvadzrksi.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfbqywsn.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.tian-w.cn/Article/details/gtnkrvjflp.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.redwolf501.top/Article/details/gtmzxreivd.html

[D14] 映射转换（每个元素变形）
来源：http://dali.nanxinkj.top/Article/details/gtneqkwcll.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.mhx1999.top/Article/details/gtbblkmtap.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.gotoacloud.top/Article/details/gtoboegsij.html

JS:   arr.map(x => x * 2)
来源：http://dali.wangshuangyany.cn/Article/details/gttvkoyeqh.html

TS:   arr.map(x => x * 2)
来源：http://dali.meibo888.top/Article/details/gtbcsmamvb.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.tian-w.cn/Article/details/gtblagjijb.html

Go:   // 手写循环
来源：http://dali.hnqzz.top/Article/details/gtsvukubfo.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtbrkoduve.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.wangshuangyany.cn/Article/details/gtkndirpgv.html

[D15] 去重
来源：http://dali.chenzaomai.com/Article/details/gtuxlodehq.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtthoimguh.html

PHP:  array_unique($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmdpdfnh.html

JS:   [...new Set(arr)]
来源：http://dali.yvedp.cn/Article/details/gtvzczmmrs.html


<!-- 参考信息 -->