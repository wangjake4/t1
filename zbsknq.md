代发 wailian999

Py:   if not data: return
来源：http://dali.wangshuangyany.cn/Article/details/gtrmffsrqv.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtxouxlase.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtcsvoxzmw.html

TS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gtekvobrly.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtmpysdxef.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtitbqjlyg.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtdjdvxduu.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtkkbrgkvk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfzwxcwyq.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtpstnxcor.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtybznwwwt.html

[C01] 定义函数
来源：http://dali.hnxiangtu.top/Article/details/gtucgjbrvq.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gtuptujyjp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gthohckqdp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtcimgtjyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtfheodozs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtlrtqquhn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtaveousde.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daria6918.cn/Article/details/gtjnhxretl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtyeaxkdmx.html

[C02] 默认参数
来源：http://dali.fengsongda.top/Article/details/gtvzvdaeil.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtalbaukhs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtriiujdxv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhixingplan.top/Article/details/gtkbvqwcyp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtthciygkm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtxhiknseg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtcztplhfg.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gthndhurgo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gttcchpxwg.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtfteczgmp.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtbookkenc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gtyswisjwl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtwublonjp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtssngxbcy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtcugrzegj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtkrbjddge.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtdunshbfj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtttjxmzjf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtcwccxvmn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gtvlghogsa.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtqpuypjfh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtybkbffdy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnukeummo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtnypudayf.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhoulong.xyz/Article/details/gtntmvvtkz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtveesuhdr.html

C#:   f(a: 1, b: 2)
来源：http://dali.smart0.xyz/Article/details/gtvuhszhqv.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtzkfsntsc.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtveebejfz.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gtowowvggm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cdnleiting.top/Article/details/gtyatxecnr.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtqjrxgmjd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtrdgyuvxz.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gtimrlslpz.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gthhflyzts.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjxkitoj.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gtxffgtxjc.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gtljvdmowu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gthmabiapd.html

JS:   const square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtgrdpvtif.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shuidangran.top/Article/details/gtsoadnxdm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtswluzzqd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtmhvulqgh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.andypj.xyz/Article/details/gtjqesgxpg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtsnpguerf.html

[C07] 把函数作为参数传入
来源：http://dali.hnxiangtu.top/Article/details/gtehckuoni.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cqqwz.cn/Article/details/gtssjmnnsl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gthwxzyjdn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gtktfsjnin.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtphdjkgmq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jiagoushi.top/Article/details/gtcnjxhhyj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsazramgu.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtmxriuski.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvndvbfr.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtjyzkufdk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtohzikdlj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtmetlxtsr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuzltvgyv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtndrksbwh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gttrbewrbc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gteklsfvfa.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrbqtae.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtltacqrut.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtjcssyaau.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtmiqsnakr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtxilytqeq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtumlatzpy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtnoxcinhk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gthoeawjkv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.iojbl.cn/Article/details/gtphniucpr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtdzxrrvjz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtqxxkmfdz.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtnveczlba.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtalzmtjdk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtdigcrxiy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gterfuuhsq.html

TS:   同 JS
来源：http://dali.hnqzz.top/Article/details/gtwbwmiqob.html

Java: 方法内为块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtkcfkzcnr.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtrpexeeyu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqwigdbv.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtqxbaingu.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtvbvbphjo.html

Py:   from module import func
来源：http://dali.zhoulong.xyz/Article/details/gtzgctunjf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.redwolf501.top/Article/details/gtjzocnchv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtpjklgeqb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtqembcgnl.html

Java: import java.util.List;
来源：http://dali.cucudq.cn/Article/details/gtxaxgvaom.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtzuceocdw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigfzy.top/Article/details/gtzqxgdsxj.html

C#:   using System.Text;
来源：http://dali.shzxlz.cn/Article/details/gtlinowcgo.html

[C12] 立即执行函数 IIFE
来源：http://dali.aizwys.cn/Article/details/gtfdodeaiv.html

Py:   (lambda: print("run"))()
来源：http://dali.redwolf501.top/Article/details/gtivpnrglx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gtyimajafh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gtniwgtbtr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtambruocd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpkciibo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gtxudxucjp.html

Ruby: -> { puts "run" }.call
来源：http://dali.c1oappe.top/Article/details/gtfzzssetz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ppjwa.cn/Article/details/gtupvqlqit.html

[C13] 类型声明 / 类型注解
来源：http://dali.pengpengdd.cyou/Article/details/gtfrwfygod.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gthygoavub.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtcxqmztii.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtkeuugxxe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtdhicnzcy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkgxkkiye.html

Go:   func add(a, b int) int
来源：http://dali.cucudq.cn/Article/details/gtiwdcpvvj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shuidangran.top/Article/details/gtkukfqcoy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtcdydqpdm.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtitoawrus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nwbrower.top/Article/details/gtcgfizjnj.html

PHP:  // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtkxwgiytf.html

JS:   // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gttbvmcxvh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gtkixphvsx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtygqzuefi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtpwckikrs.html

Ruby: # 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtqrgnwbxs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cucudq.cn/Article/details/gtponeaojn.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtwypdqipb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtjynalnsv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ydzc1.top/Article/details/gtwboqkcpe.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtshugfotb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtaitodahu.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtrfcgbnmu.html

Go:   // 无解构
来源：http://dali.cheryme.top/Article/details/gtkhkrgxqa.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtsiwqtlrm.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtqwdidfgh.html

[C16] 函数 / 方法重载
来源：http://dali.xuanzx.com/Article/details/gtjzsxwlll.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.svipenyu.cn/Article/details/gtqoihykru.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtbnogsdau.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtqzgdjyhv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.aizwys.cn/Article/details/gtobfjdeds.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtotoafbvx.html

Go:   // 无重载：用不同函数名
来源：http://dali.dashuyun.cn/Article/details/gtxhzsfrvl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ivvv.top/Article/details/gtcpzrbtnk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tanke756.top/Article/details/gtaqqfpbyg.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtzjwjviao.html

D. 数组 / 列表 / 集合
来源：http://dali.xylfe.cn/Article/details/gtgvhufcvz.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtplrtyuqm.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtwqvenmne.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pengpengdd.cyou/Article/details/gtczhrnryv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtbiccwjne.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtxmlkamph.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hywenlv.cn/Article/details/gtsiqzmzgu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhoulong.xyz/Article/details/gthwdzlksj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhixingplan.top/Article/details/gtyqheawoj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtfurwgxwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtdkqlnaor.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gttpwphput.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ybcxt.top/Article/details/gtgwtrvnat.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shuidangran.top/Article/details/gtpzzmqcpd.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtzcocqqko.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gthendzhix.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtdibysmth.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtoqazpmjk.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbngcfdp.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtpvntsozl.html

[D03] 在指定位置插入元素
来源：http://dali.chenlongwang.top/Article/details/gtcntyjbtk.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtmugenknf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtegupjnra.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.c1oappe.top/Article/details/gtipvdpffv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yongpay.top/Article/details/gttmdlsvkq.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtkcsbfdeq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zycfv.cn/Article/details/gthhgaqqod.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zycfv.cn/Article/details/gtnnkfdsbc.html

C#:   list.Insert(0, 0);
来源：http://dali.sweek.top/Article/details/gtqjadmnmy.html

[D04] 删除元素
来源：http://dali.xuanzx.com/Article/details/gtoemynsyb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtnezjzpxw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxinkj.top/Article/details/gtyalfyocg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtmdjzyivt.html

TS:   arr.splice(0, 1);
来源：http://dali.cdnleiting.top/Article/details/gtlgcftbdw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yanxiufei.cn/Article/details/gtitiwsgqv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtocvdldhr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gtwehmvico.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtnzwnaifs.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtxtrosrfo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtdiyfvyvw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtnfputjlv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ehwqpu.com/Article/details/gtbeojikig.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gtirdgiegg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sufxvd.cn/Article/details/gtpxawqrod.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtyietoyan.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtxbygirnr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtwtagooqx.html

[D06] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtomokigvq.html

Py:   len(arr)
来源：http://dali.hnxiangtu.top/Article/details/gtnttvubag.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtjdhrwruc.html

JS:   arr.length
来源：http://dali.nwbrower.top/Article/details/gtoparindl.html

TS:   arr.length
来源：http://dali.redwolf501.top/Article/details/gtazywejad.html

Java: list.size();
来源：http://dali.0kj1m.cn/Article/details/gtzfcgyrcy.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtlkkbiscx.html

Ruby: arr.length; arr.size
来源：http://dali.yongpay.top/Article/details/gtuvtnhnen.html

C#:   list.Count;
来源：http://dali.yuxming.cn/Article/details/gtsxzfgvps.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtsepfwuwa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cheryme.top/Article/details/gtfqzyougl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.vqdsnc.cn/Article/details/gtgsnygzhs.html

JS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtfyydophq.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtinfliksn.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtdofezson.html

Go:   arr[1:4]
来源：http://dali.chenlongwang.top/Article/details/gtzqffertb.html

Ruby: arr[1, 3]
来源：http://dali.yangfankeji.com/Article/details/gtjblzftff.html

C#:   list.GetRange(1, 3);
来源：http://dali.cdnleiting.top/Article/details/gtzjkzwihu.html

[D08] 合并两个数组
来源：http://dali.yj202588.top/Article/details/gtphvsekvt.html

Py:   a + b;  a.extend(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnqotingb.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gthlldhbrv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gogol.net.cn/Article/details/gtwxgetbip.html

TS:   [...a, ...b];
来源：http://dali.dianchejie.cn/Article/details/gtfikjbqhw.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtygcuhmwr.html

Go:   append(a, b...)
来源：http://dali.sysykeji.top/Article/details/gtoenxjwiw.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtbroenxzl.html

C#:   a.Concat(b).ToList()
来源：http://dali.guannengcc.top/Article/details/gtysropcow.html

[D09] 排序（升序）
来源：http://dali.sweek.top/Article/details/gtafjqprbb.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangdashe.top/Article/details/gtgkbuwrbg.html

PHP:  sort($arr);
来源：http://dali.fzhhl.top/Article/details/gteocbgotl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jyoumei.cn/Article/details/gteyknlrjf.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtymamjojs.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.iojbl.cn/Article/details/gtrqknipgk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.cucudq.cn/Article/details/gtfyucppmf.html

Ruby: arr.sort
来源：http://dali.kuanghao11.cn/Article/details/gtdonlezbo.html

C#:   list.Sort();
来源：http://dali.hnxiangtu.top/Article/details/gtrcxuntmc.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pycfn.com/Article/details/gtydyaplol.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yangfankeji.com/Article/details/gtrohxtvrt.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtzzbbtcwz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yueranfly.top/Article/details/gtawpsaewm.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtsnoapnir.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zhiwuduotai.top/Article/details/gthieilbmn.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jqgufenzy.top/Article/details/gteewzawri.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.birdmap.top/Article/details/gtzuiclnyb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ppjwa.cn/Article/details/gtqnbcajqd.html

[D11] 反转数组
来源：http://dali.cqqwz.cn/Article/details/gtpramllxs.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.xuetiantiany.cn/Article/details/gtgpfpksiq.html

PHP:  array_reverse($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtoijimpvk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yongpay.top/Article/details/gtttcrnxgq.html

TS:   [...arr].reverse();
来源：http://dali.aibaodan.cn/Article/details/gtojldqakw.html

Java: Collections.reverse(list);
来源：http://dali.yuxming.cn/Article/details/gtctbormjm.html

Go:   slices.Reverse(arr)
来源：http://dali.wangdashe.top/Article/details/gtebtaetly.html

Ruby: arr.reverse
来源：http://dali.cheryme.top/Article/details/gtqsjbiofq.html

C#:   list.Reverse();
来源：http://dali.snrcjt.cn/Article/details/gtfnrbakel.html

[D12] 查找元素下标
来源：http://dali.fengsongda.top/Article/details/gtnpvmpbqv.html

Py:   arr.index(x);  x in arr
来源：http://dali.zdqjudy.top/Article/details/gtkirefmkn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtypemkhgg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.0kj1m.cn/Article/details/gtiudqwpxd.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ehwqpu.com/Article/details/gtcqputyxz.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.zhengqikj.top/Article/details/gtlejwkydi.html

Go:   slices.Index(arr, x)
来源：http://dali.gaohongyu789.top/Article/details/gtnxhejlfl.html

Ruby: arr.index(x)
来源：http://dali.cheryme.top/Article/details/gtkarnkbzy.html

C#:   list.IndexOf(x);
来源：http://dali.svipenyu.cn/Article/details/gtxutevunb.html

[D13] 过滤（保留满足条件的）
来源：http://dali.xylfe.cn/Article/details/gtvkgjiimm.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.tian-w.cn/Article/details/gtljmwihpb.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.zhixingplan.top/Article/details/gtgegcamjw.html

JS:   arr.filter(x => x > 3)
来源：http://dali.meibo888.top/Article/details/gtzfhbsypt.html

TS:   arr.filter(x => x > 3)
来源：http://dali.wangshuangyany.cn/Article/details/gtyeinhlgp.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.meibo888.top/Article/details/gtlcquuvso.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.zycfv.cn/Article/details/gtvwopbntj.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtlxxfimcn.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.iojbl.cn/Article/details/gtiqvdhajr.html

[D14] 映射转换（每个元素变形）
来源：http://dali.snrcjt.cn/Article/details/gtdzrmkfqn.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.hnxiangtu.top/Article/details/gtcqcryqsi.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.bjfxy.top/Article/details/gtfvstyugg.html

JS:   arr.map(x => x * 2)
来源：http://dali.xziqi.cn/Article/details/gtlimworoe.html

TS:   arr.map(x => x * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtookiokat.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.nanxinkj.top/Article/details/gtrytikafb.html

Go:   // 手写循环
来源：http://dali.pengpengdd.cyou/Article/details/gttpubpxnv.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtlsgckzgb.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtkdivikgz.html

[D15] 去重
来源：http://dali.zhengqikj.top/Article/details/gtokmiahgl.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtkzgwnwsd.html

PHP:  array_unique($arr);
来源：http://dali.jyoumei.cn/Article/details/gtuphlsigv.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtzxudproo.html

TS:   [...new Set(arr)]
来源：http://dali.ivvv.top/Article/details/gtoreufjkn.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.jqgfzy.top/Article/details/gtdleoofqe.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.yueranfly.top/Article/details/gtifsmpexo.html

Ruby: arr.uniq
来源：http://dali.zhoulong.xyz/Article/details/gtlvotwmjs.html

C#:   list.Distinct().ToList()
来源：http://dali.c1oappe.top/Article/details/gtdueunbxs.html

[D16] 求和与平均值
来源：http://dali.yueranfly.top/Article/details/gtzxrtisxi.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.fzhhl.top/Article/details/gtbaajpkjc.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtxfoahncs.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.jinqigufen.top/Article/details/gtnebcehlg.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zhijiandao.cn/Article/details/gtgiffmgmt.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.chenjidiqi.icu/Article/details/gttbhsbfgj.html

Go:   // 手写循环累加
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkeqcath.html


<!-- 参考信息 -->