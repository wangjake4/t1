代发 wailian999

Py:   def add(a, b): return a + b
来源：http://dali.cdnleiting.top/Article/details/gtxodtexqp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtclgbpdnr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtjjsztcpb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gttomrdvvm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtpmqlymjn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gtadiiodog.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtbbncbqlf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtgwizgypy.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gtkgavighg.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gthzfoydva.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwgcrisgy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gttnkdescs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gtsmpoliqk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gtgyjgjmxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sufxvd.cn/Article/details/gtnwobbmrv.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhiwuduotai.top/Article/details/gtxizmejzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jianghu66.top/Article/details/gtktbpavxr.html

[C03] 可变参数
来源：http://dali.shzxlz.cn/Article/details/gthduoydag.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtkgurkjvi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtiacucqix.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtijndlmoj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtupeaoolf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gthormvqkx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtymcrqxwm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtmllmrlvo.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ydzc1.top/Article/details/gthbzrzasj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtjcngddww.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtbpgzptzx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hywenlv.cn/Article/details/gtibujugnv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtxhnsztad.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtihmpaorw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtslkmvvwp.html

Go:   // 无：用配置结构体参数
来源：http://dali.birdmap.top/Article/details/gtnymfgxeh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtqnaztwiq.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtbmetfpfl.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gthqtaxaeu.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtqqhsfwut.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtbhqisrxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtpmyatrpc.html

TS:   return { a, b };
来源：http://dali.cashguo.top/Article/details/gtpsxwuvlx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtictkiyoe.html

Go:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtoyixgjqt.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtnjeouetn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhoulong.xyz/Article/details/gtxfjkqdko.html

[C06] 匿名函数 / lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtdewbsnuw.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtqdykmmdj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhengqikj.top/Article/details/gtaadhlrjh.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtlyowlwuw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tian-w.cn/Article/details/gtxllpefsb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gtgttapmsf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gtiidgxuag.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtrkpuwljh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtteqtywyb.html

[C07] 把函数作为参数传入
来源：http://dali.pengpengdd.cyou/Article/details/gtmsqmdqwb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yueranfly.top/Article/details/gtzjsakxre.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtnnpfqyso.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhongyouzk.top/Article/details/gtxzfbupqe.html

TS:   arr.map(String)
来源：http://dali.hywenlv.cn/Article/details/gtjtyysxnk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gteapxktzq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sufxvd.cn/Article/details/gthlgrbzbp.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhiwuduotai.top/Article/details/gtejmlohbj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtuwnctehr.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtahudmxth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtrebelmai.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhongyouzk.top/Article/details/gtyikfwsln.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtagyyhrdf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtfpfamqtz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtiziehqfh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gtcoksyxuf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sufxvd.cn/Article/details/gtvgxbhjic.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtvwbpwyvs.html

[C09] 递归
来源：http://dali.yonumen.top/Article/details/gtigdcvmsn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtetsagzsq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ehwqpu.com/Article/details/gttlrslfin.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtdhrkpmmc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hongshengwenyu.top/Article/details/gthxhacwnp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gteobcyvfh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hysaishi.cn/Article/details/gtupxhuzpo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtubetyoxe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtpzvsstxi.html

[C10] 变量作用域
来源：http://dali.yj20258.top/Article/details/gtdvxxsxqb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuanzhike.top/Article/details/gtigvmisow.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guannengcc.top/Article/details/gtmxgvfzlo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gtsepbbjyf.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gtrdqgyswt.html

Java: 方法内为块级作用域
来源：http://dali.xinyue.icu/Article/details/gtzazmjgan.html

Go:   花括号块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtjapcougn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtqzlawvsu.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtundznubt.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gthskzujby.html

Py:   from module import func
来源：http://dali.shangyingyoupin.top/Article/details/gtqhtqvocl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtgidfornp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtstrjkamk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtgnlvcluc.html

Java: import java.util.List;
来源：http://dali.yj202588.top/Article/details/gtpvykbuha.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xuanzx.com/Article/details/gtmmvbeqbi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtevyfdugw.html

C#:   using System.Text;
来源：http://dali.pycfn.com/Article/details/gtmlwkiguv.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gtkiludpjl.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtnywwiwog.html

PHP:  (function () { echo "run"; })();
来源：http://dali.wangshuangyany.cn/Article/details/gtmpxmquze.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gtqfjfpzfh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtnokxlrcv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtfjycbovw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtkldnbtdm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gthxtbffvn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtfdyivshm.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtscevxegx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtvqvqwmqt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxrtnmjn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtsfpsazfv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtkzchujum.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtzujfmazp.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtlfhmhvwp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtnefeaztd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtymvysbgl.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtmkamhqgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtivhjiybf.html

PHP:  // 无泛型
来源：http://dali.zhengqikj.top/Article/details/gteqnvrhpw.html

JS:   // 无泛型
来源：http://dali.fzhhl.top/Article/details/gtoykkizjp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pengpengdd.cyou/Article/details/gtcupkggvb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cheryme.top/Article/details/gttxxkebsc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmfytqbk.html

Ruby: # 无泛型
来源：http://dali.cucudq.cn/Article/details/gtnvobggtq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ehwqpu.com/Article/details/gtaunrocnt.html

[C15] 解构 / 展开参数
来源：http://dali.jqgufenzy.top/Article/details/gtdahyfqgo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.9152youxi.cn/Article/details/gtotcrrjcb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guannengcc.top/Article/details/gtzqacttxa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gtlbqmrauy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yvedp.cn/Article/details/gtimshmzve.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtcvnowyyu.html

Go:   // 无解构
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqhoychs.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gttefjhusi.html

C#:   var (a, b) = pair;
来源：http://dali.shangyingyoupin.top/Article/details/gtwvwmunfb.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtgerurwqa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtwyigoqaj.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtwwddigpn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtzmpsnztj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.cdnleiting.top/Article/details/gtmtykemwi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhixingplan.top/Article/details/gtipqvmrax.html

Go:   // 无重载：用不同函数名
来源：http://dali.bjfxy.top/Article/details/gtqvhrcuox.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yonumen.top/Article/details/gtjwojfuoo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtknsexedb.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgvxamjeh.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtdfukqotg.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gthllkfymm.html

[D01] 创建数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtrcpyrkdl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtpzzrwjok.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jyoumei.cn/Article/details/gtsijokyrf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtltiwtcda.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sweek.top/Article/details/gtusjgaxfp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shzxlz.cn/Article/details/gtjttorysq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shuidangran.top/Article/details/gtrjgwenih.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtggogvrjv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tianlin.xyz/Article/details/gtziheuhjz.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtcwevatud.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yonumen.top/Article/details/gtzqqlahow.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dianchejie.cn/Article/details/gtyrmkojog.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtxdriozbo.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtonlrhrwm.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtfdsgwdfr.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gterytrwmv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jqgufenzy.top/Article/details/gtusjekkhx.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtsudupkoo.html

[D03] 在指定位置插入元素
来源：http://dali.bjfxy.top/Article/details/gtfxfmxzgp.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtpaddphbx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdjilatiy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jyoumei.cn/Article/details/gtrmrmyixa.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj20258.top/Article/details/gttuvjfuur.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrndepmqo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aibaodan.cn/Article/details/gtaghufkjy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtgvbrptdz.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxphvtmp.html

[D04] 删除元素
来源：http://dali.cdnleiting.top/Article/details/gtrscqqmwa.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtjorsbruj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sxryk.cn/Article/details/gthokpvidt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxinkj.top/Article/details/gtzecizyys.html

TS:   arr.splice(0, 1);
来源：http://dali.gogol.net.cn/Article/details/gtysugvffg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gtffmggflk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yuanzhike.top/Article/details/gtscmnzdhw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtqeiebnzi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtyttvuava.html

[D05] 访问与修改元素
来源：http://dali.gzhubu.top/Article/details/gtbfajjqmk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtsbsgzmql.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gteuifvjak.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtegerbxcm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cucudq.cn/Article/details/gtcvdkasbb.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenjidiqi.icu/Article/details/gtmdvmydoh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsrjceoh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtzgrwnuwl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtevxgbthh.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gtntgbjlin.html

Py:   len(arr)
来源：http://dali.ehwqpu.com/Article/details/gttaahfxmq.html

PHP:  count($arr);
来源：http://dali.cheryme.top/Article/details/gtzmsixjji.html

JS:   arr.length
来源：http://dali.xinyue.icu/Article/details/gtinmmiwxn.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtyapnxoeb.html

Java: list.size();
来源：http://dali.hnqzz.top/Article/details/gtilxmbpmg.html

Go:   len(arr)
来源：http://dali.hysaishi.cn/Article/details/gtgynbiffy.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtscebafug.html

C#:   list.Count;
来源：http://dali.yangfankeji.com/Article/details/gttfxgixdd.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gtfvoybsxc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtjeogcely.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtoavqqxrd.html

JS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtzwjrnmjo.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtdwnjxiqr.html

Java: list.subList(1, 4);
来源：http://dali.quarkkingdee.top/Article/details/gtuscyeeih.html

Go:   arr[1:4]
来源：http://dali.daria6918.cn/Article/details/gtznuoatvw.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtnchxwgho.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhoulong.xyz/Article/details/gturgtwmeq.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gtecxrcmxz.html

Py:   a + b;  a.extend(b)
来源：http://dali.nwbrower.top/Article/details/gtuohkktbt.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtfmlpinfx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ybcxt.top/Article/details/gtvvrvkznb.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtcqvfnnma.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gtgmvuicpi.html

Go:   append(a, b...)
来源：http://dali.quarkkingdee.top/Article/details/gtiifcpchp.html

Ruby: a + b;  a.concat(b)
来源：http://dali.havefunace.top/Article/details/gtxnzuppww.html

C#:   a.Concat(b).ToList()
来源：http://dali.ppjwa.cn/Article/details/gtdqvggmrm.html

[D09] 排序（升序）
来源：http://dali.xinyue.icu/Article/details/gtvcodlosc.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yangfankeji.com/Article/details/gtjfyecykz.html

PHP:  sort($arr);
来源：http://dali.tian-w.cn/Article/details/gthaikmkja.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.ehwqpu.com/Article/details/gtrrashmfo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpzuownrw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yonumen.top/Article/details/gtzefncmfl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.bjfxy.top/Article/details/gtdlcdnwap.html

Ruby: arr.sort
来源：http://dali.jlsjyb.cn/Article/details/gthbkgamnp.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtorzsbltb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtwnsqzili.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xziqi.cn/Article/details/gtyivvggkn.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtfqjtdgty.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.kuanghao11.cn/Article/details/gtzpgpdyaz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtbyxkuqew.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.cheryme.top/Article/details/gtoiyfkrqy.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtdsrgpnxv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtqjbgjzpv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sufxvd.cn/Article/details/gtxswecbld.html

[D11] 反转数组
来源：http://dali.yonumen.top/Article/details/gtasnptoky.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hongshengwenyu.top/Article/details/gtatgycxxq.html

PHP:  array_reverse($arr);
来源：http://dali.havefunace.top/Article/details/gtkmuldtms.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.ydzc1.top/Article/details/gtnxxgrbvp.html

TS:   [...arr].reverse();
来源：http://dali.yonumen.top/Article/details/gthqdsnclw.html

Java: Collections.reverse(list);
来源：http://dali.cashguo.top/Article/details/gtmuomjbnk.html

Go:   slices.Reverse(arr)
来源：http://dali.birdmap.top/Article/details/gtrbaafafs.html

Ruby: arr.reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyjgatiw.html

C#:   list.Reverse();
来源：http://dali.yuxming.cn/Article/details/gtxcfsujse.html

[D12] 查找元素下标
来源：http://dali.yj202588.top/Article/details/gtyeunfnau.html

Py:   arr.index(x);  x in arr
来源：http://dali.daria6918.cn/Article/details/gthogkoohv.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.birdmap.top/Article/details/gtuboytaae.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.xuanzx.com/Article/details/gtofgwifcz.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtkcadphwi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinqigfzy.top/Article/details/gtmioluxcy.html

Go:   slices.Index(arr, x)
来源：http://dali.vqdsnc.cn/Article/details/gtygzyhgty.html

Ruby: arr.index(x)
来源：http://dali.gaohongyu789.top/Article/details/gtmjjpagzu.html

C#:   list.IndexOf(x);
来源：http://dali.sweek.top/Article/details/gtzyfogfde.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtaibzkcwx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fengsongda.top/Article/details/gtqgebvblr.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtgclrvvsc.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cdnleiting.top/Article/details/gtzbftueds.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hysaishi.cn/Article/details/gtsbnllqci.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.cqqwz.cn/Article/details/gtmdlibaaf.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.cdnleiting.top/Article/details/gtqqskcorz.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.sxryk.cn/Article/details/gtvcvqecbr.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.zhijiandao.cn/Article/details/gtbpglaitj.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkhmwswz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkpjbhsc.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.yongpay.top/Article/details/gtxcdtvyqi.html

JS:   arr.map(x => x * 2)
来源：http://dali.jqgufenzy.top/Article/details/gttbnqwfbo.html

TS:   arr.map(x => x * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtoqsjgsxz.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntazyryd.html

Go:   // 手写循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtimfzldun.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtgukzxyvm.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.xuanzx.com/Article/details/gtsygksdpc.html

[D15] 去重
来源：http://dali.zhongyouzk.top/Article/details/gtjylytepu.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtperkoear.html

PHP:  array_unique($arr);
来源：http://dali.hnqzz.top/Article/details/gtlwrpmrij.html

JS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtvsqiqmwo.html

TS:   [...new Set(arr)]
来源：http://dali.mhx1999.top/Article/details/gtqqrdrvte.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.svipenyu.cn/Article/details/gtpaevyamp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.sufxvd.cn/Article/details/gtvjdhkndb.html

Ruby: arr.uniq
来源：http://dali.snrcjt.cn/Article/details/gtcojexoqm.html

C#:   list.Distinct().ToList()
来源：http://dali.zdqjudy.top/Article/details/gtmftxuukn.html

[D16] 求和与平均值
来源：http://dali.xinyue.icu/Article/details/gtnwaokggi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.yangfankeji.com/Article/details/gtjqqghorv.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.smart0.xyz/Article/details/gtqtfhdlqi.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.fengsongda.top/Article/details/gtkziykjyf.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.ivvv.top/Article/details/gtczxxsjzz.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdokmlubb.html

Go:   // 手写循环累加
来源：http://dali.tian-w.cn/Article/details/gtsuvtdnpx.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.sysykeji.top/Article/details/gtufrmcais.html

C#:   list.Sum();  list.Average()
来源：http://dali.0kj1m.cn/Article/details/gthrqqukns.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtyncqewle.html

Py:   max(arr);  min(arr)
来源：http://dali.316326.xyz/Article/details/gtzdntlttl.html

PHP:  max($arr);  min($arr);
来源：http://dali.redwolf501.top/Article/details/gtkbdiasxp.html

JS:   Math.max(...arr);  Math.min(...arr)
来源：http://dali.sysykeji.top/Article/details/gtsrkoxqdp.html

TS:   Math.max(...arr);
来源：http://dali.zhoulong.xyz/Article/details/gttqnwatii.html

Java: Collections.max(list);  Collections.min(list);
来源：http://dali.9152youxi.cn/Article/details/gtadtuurfi.html

Go:   slices.Max(arr);  slices.Min(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtvogdlphd.html

Ruby: arr.max;  arr.min
来源：http://dali.tianlin.xyz/Article/details/gtutunbyyx.html

C#:   list.Max();  list.Min()
来源：http://dali.havefunace.top/Article/details/gtbervoiqw.html

[D18] 扁平化嵌套数组
来源：http://dali.bjfxy.top/Article/details/gthqgeawrm.html


<!-- 参考信息 -->