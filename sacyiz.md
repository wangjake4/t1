代发 wailian999

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtratbhsod.html

Ruby: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtvqyfltag.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtoembfszm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gthbllmcys.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtarcwumid.html

PHP:  if (!$data) { return; }
来源：http://dali.ydzc1.top/Article/details/gtrlbwesrl.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtclerdtih.html

TS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdogexlmy.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtzklsppho.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtflfuvroi.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gtjuhnxgvg.html

C#:   if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtasprjwls.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtrwlodhhp.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtkdbpdvco.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwqkidtfv.html

[C01] 定义函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtalrjwmob.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gtvkhmuaku.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtwxphuqvd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtodjaayrs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtymuzayrw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtoudxhvji.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtjedeqwdd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gtkzllyhih.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtahvvcjpu.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtowjbsprh.html

Py:   def greet(name="World"): return name
来源：http://dali.sweek.top/Article/details/gtsybzpuhe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.havefunace.top/Article/details/gtmtrprfrh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtixlepioo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtuqinecju.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gaohongyu789.top/Article/details/gtizgokeri.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gtlasoxzca.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtvyqbmjoe.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtususubxv.html

[C03] 可变参数
来源：http://dali.tianlin.xyz/Article/details/gtczkidakh.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtvmuikrvg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj202588.top/Article/details/gtwszqlzoz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtnmgnohzu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtxzrfxoxx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtzjgnhekv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtwfmtuxuy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guannengcc.top/Article/details/gtvlltummp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gtjntzavag.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gtruracxaa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gtvfkmbdxg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtxysefykp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrpgiopl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinqigufen.top/Article/details/gtkheovkgl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gttqaybhgq.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtpsmaochj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtmjnrsxid.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gthvkplbui.html

[C05] 返回多个值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwrhtfwc.html

Py:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuplfbpwt.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtvctbflfx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.316326.xyz/Article/details/gtauenovto.html

TS:   return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfofzftc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gtbvzvoebg.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtbvwrdhjz.html

Ruby: return a, b
来源：http://dali.316326.xyz/Article/details/gtcwwzavtm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiskosfln.html

[C06] 匿名函数 / lambda
来源：http://dali.feifeiyinyue.top/Article/details/gtjksbwipk.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtrnrfujtg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtljjzdghh.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gthvkddali.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtfvvcgiay.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cdnleiting.top/Article/details/gtqexysyqd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtdbyixcvs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtsyrgklkr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfiixjrln.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtwxfezide.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtefhxgvkq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gtxwmzdbsy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gtaiqhiefs.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gthidjrexy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtsxedumoi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhiwuduotai.top/Article/details/gtfloouhln.html

Ruby: arr.map(&:upcase)
来源：http://dali.ivvv.top/Article/details/gtzjrqunyk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtwhispyro.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtlpidiokh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hfpthk.cn/Article/details/gttetitimb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtjikleqqx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtzaslebie.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtbjhciujf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gtuzrmcewv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtbeznioee.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtchqgenbc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahenflgw.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gthjmipfag.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtobkvcdhr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtobietxdy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaznivzzq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtdtnzumpo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258.top/Article/details/gtayascjfn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gtddnxmank.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtkkutzudu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtnyubhgrk.html

[C10] 变量作用域
来源：http://dali.zhixingplan.top/Article/details/gtjqtelyfy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtfiohzqeq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtjnzhpstt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.havefunace.top/Article/details/gtxeogycta.html

TS:   同 JS
来源：http://dali.jqgufenzy.top/Article/details/gtswaqchpx.html

Java: 方法内为块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtbjvqrgil.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtcfnryibm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnqzz.top/Article/details/gtunfvnekr.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gthkoxjteg.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gtruhbaihm.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtsegouapl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtcdupjipb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.haohaochexian.top/Article/details/gtvvberwzi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtgydynyop.html

Java: import java.util.List;
来源：http://dali.shzxlz.cn/Article/details/gtnvedzzos.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.quarkkingdee.top/Article/details/gttfqxaohy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yangfankeji.com/Article/details/gtlrswtxzc.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtszsevzzb.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtvqhhjvln.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtkneqrlec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tianlin.xyz/Article/details/gtjzupmcsw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gteaftcfdi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.mhx1999.top/Article/details/gtypsyuovw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gogol.net.cn/Article/details/gtdjynnyiq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gtpiryaqvy.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtwyfwdqkp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.wangshuangyany.cn/Article/details/gtsmajzniv.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gttixgkryx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtryfippqn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtwlmsqqiu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gtbwrfbwqd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtsjbeiaac.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtoerzgpjt.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtepyvfxcl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gtjagfqovn.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xuanzx.com/Article/details/gtrzmpxshu.html

[C14] 泛型函数
来源：http://dali.gzhubu.top/Article/details/gtodtghxvd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.vqdsnc.cn/Article/details/gtqaqefppy.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gttpnngywq.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtntvcejtq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtbubdamch.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtjvedcjtk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkgsbpus.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtbxchjynf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gotoacloud.top/Article/details/gthjzyripy.html

[C15] 解构 / 展开参数
来源：http://dali.ppjwa.cn/Article/details/gtkteixrsv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.pengpengdd.cyou/Article/details/gtvatavyny.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gtcbahwtcf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtcqyuguxe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jianghu66.top/Article/details/gtzmilgfqw.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtiztwcqdv.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtogpwjhbx.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtahiipoio.html

C#:   var (a, b) = pair;
来源：http://dali.jlsjyb.cn/Article/details/gtinxadgwa.html

[C16] 函数 / 方法重载
来源：http://dali.0kj1m.cn/Article/details/gtswmuoadw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtdauvuvro.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtpoduagxb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtssofxkgl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ivvv.top/Article/details/gtytnhejed.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gttqdjvihn.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtqjpryqcg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtfkjbuxjp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258888.top/Article/details/gtvdqtwmib.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmfconqla.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtylqnzjck.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtiypipvzp.html

[D01] 创建数组 / 列表
来源：http://dali.bjfxy.top/Article/details/gtlpgyiqeg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangdashe.top/Article/details/gtnbaezkor.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhiwuduotai.top/Article/details/gtokksrfdv.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.guowangkeji.top/Article/details/gtknboutph.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtzfkjsptp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gtekixvgdp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfqfcftb.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtslioosfs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hammf.cn/Article/details/gtniopkolf.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtmoydekvt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.feifeiyinyue.top/Article/details/gtigmqxhga.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gtmzrjecuu.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtzppbiogd.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtrdaucbql.html

Java: list.add(4);
来源：http://dali.0kj1m.cn/Article/details/gtvhcagkts.html

Go:   arr = append(arr, 4)
来源：http://dali.zhongyouzk.top/Article/details/gttaqkhufh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhixingplan.top/Article/details/gtiywscgdt.html

C#:   list.Add(4);
来源：http://dali.9152youxi.cn/Article/details/gtqzzycxqq.html

[D03] 在指定位置插入元素
来源：http://dali.zhongyouzk.top/Article/details/gtorjtksud.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtomkdmqxg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtnlhbppge.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhengqikj.top/Article/details/gtdtmzstsn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtzzjouoes.html

Java: list.add(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtcsjvjbvg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gthxenfrcv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhongyouzk.top/Article/details/gtdwfiiohs.html

C#:   list.Insert(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtldquontn.html

[D04] 删除元素
来源：http://dali.zdqjudy.top/Article/details/gtvzlyrjgm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinqigufen.top/Article/details/gttfepocjf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtjehbjyhl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtzpuiacrp.html

TS:   arr.splice(0, 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlbudyyla.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.haohaochexian.top/Article/details/gtlhtlfzmj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtpdcoxosy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtwojpjwbt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.svipenyu.cn/Article/details/gtaagtvdmb.html

[D05] 访问与修改元素
来源：http://dali.guannengcc.top/Article/details/gtzfmqzwdf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtxibtvnoc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtyvulqugs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gticuvpyww.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gtdzmoohgc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtymsozsro.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtryxneqmz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cqqwz.cn/Article/details/gtoctyhodp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtbiitvzgw.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtdreemiiu.html

Py:   len(arr)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlglnsyc.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtalxtukok.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gttqltizrs.html

TS:   arr.length
来源：http://dali.aizwys.cn/Article/details/gtlhqnxjcb.html

Java: list.size();
来源：http://dali.svipenyu.cn/Article/details/gtaxaqxdvh.html

Go:   len(arr)
来源：http://dali.yueranfly.top/Article/details/gtlpiouiyz.html

Ruby: arr.length; arr.size
来源：http://dali.xuetiantiany.cn/Article/details/gtfyvpgirk.html

C#:   list.Count;
来源：http://dali.ivvv.top/Article/details/gtgfdwhcsw.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtbjsngcwk.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.wangdashe.top/Article/details/gtjqdrgrtd.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtqgqbavrz.html

JS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtumogvpur.html

TS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtqczeuwwd.html

Java: list.subList(1, 4);
来源：http://dali.zhongyouzk.top/Article/details/gteipprnyr.html

Go:   arr[1:4]
来源：http://dali.gzhubu.top/Article/details/gtagckdsax.html

Ruby: arr[1, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmeynumi.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtczyyzolo.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtwpuhgctw.html

Py:   a + b;  a.extend(b)
来源：http://dali.nanxinkj.top/Article/details/gtfbloglrt.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gtiagycgnu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.sysykeji.top/Article/details/gtqgydeiil.html

TS:   [...a, ...b];
来源：http://dali.sweek.top/Article/details/gteltpkwpm.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gtxeuclxaq.html

Go:   append(a, b...)
来源：http://dali.pengpengdd.cyou/Article/details/gtfqgagtyu.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtsrsgqubw.html

C#:   a.Concat(b).ToList()
来源：http://dali.gogol.net.cn/Article/details/gtkbnxmbga.html

[D09] 排序（升序）
来源：http://dali.hammf.cn/Article/details/gtnqpygggp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtwuumkoyd.html

PHP:  sort($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gthbekqwcn.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.snrcjt.cn/Article/details/gtgjtvpttu.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtafhorgum.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenjidiqi.icu/Article/details/gtbqoreaej.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtgcwzziot.html

Ruby: arr.sort
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqwpclusu.html

C#:   list.Sort();
来源：http://dali.xinyue.icu/Article/details/gtkjicnvoh.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hywenlv.cn/Article/details/gtcouygvfo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.iojbl.cn/Article/details/gturfjnzft.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtdixybewc.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hnxiangtu.top/Article/details/gtcfgolabt.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ivvv.top/Article/details/gtxomcpnhf.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xziqi.cn/Article/details/gtawulwfbc.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvrcwaci.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.c1oappe.top/Article/details/gtimgekjzl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ehwqpu.com/Article/details/gtgzqkrbgi.html

[D11] 反转数组
来源：http://dali.zhongyouzk.top/Article/details/gtlqlkwomu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.bjfxy.top/Article/details/gtfskzzrtw.html

PHP:  array_reverse($arr);
来源：http://dali.gzhubu.top/Article/details/gtoatvmlxm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtjmbkwopm.html

TS:   [...arr].reverse();
来源：http://dali.nwbrower.top/Article/details/gtqztqnuyc.html

Java: Collections.reverse(list);
来源：http://dali.hnxiangtu.top/Article/details/gtlrcymgmj.html

Go:   slices.Reverse(arr)
来源：http://dali.nwbrower.top/Article/details/gtghyxazjp.html

Ruby: arr.reverse
来源：http://dali.ywan-chungtsiang.top/Article/details/gthotepryz.html

C#:   list.Reverse();
来源：http://dali.zhengqikj.top/Article/details/gtdbejulcw.html

[D12] 查找元素下标
来源：http://dali.zhiwuduotai.top/Article/details/gtmudayquy.html

Py:   arr.index(x);  x in arr
来源：http://dali.jianghu66.top/Article/details/gtfmyrqlrj.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.sxryk.cn/Article/details/gtyzekjcis.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtcopfbyrt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hammf.cn/Article/details/gtqqbgrkvk.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jyoumei.cn/Article/details/gtxdfbiaqa.html

Go:   slices.Index(arr, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtucikhvlx.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqfbrzif.html

C#:   list.IndexOf(x);
来源：http://dali.jqgfzy.top/Article/details/gtszebmmiq.html

[D13] 过滤（保留满足条件的）
来源：http://dali.hnxiangtu.top/Article/details/gtrptmwaav.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.fzhhl.top/Article/details/gthbnloxjn.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.cqqwz.cn/Article/details/gtirvszopx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.hfpthk.cn/Article/details/gtzscotyac.html

TS:   arr.filter(x => x > 3)
来源：http://dali.hongshengwenyu.top/Article/details/gtwrfnruvq.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.tianlin.xyz/Article/details/gtqcwvdonl.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.chenlongwang.top/Article/details/gtvspcltyo.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.andypj.xyz/Article/details/gtcrpkyubq.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.sysykeji.top/Article/details/gtgwgfdcgy.html

[D14] 映射转换（每个元素变形）
来源：http://dali.ybcxt.top/Article/details/gtdryzvesr.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.xylfe.cn/Article/details/gttzkpjnvz.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.chenzaomai.com/Article/details/gtdzrcmlzn.html

JS:   arr.map(x => x * 2)
来源：http://dali.xuanzx.com/Article/details/gtoiywjkrk.html

TS:   arr.map(x => x * 2)
来源：http://dali.yuanzhike.top/Article/details/gtbhjnuexk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.gotoacloud.top/Article/details/gtrmfbtrkq.html

Go:   // 手写循环
来源：http://dali.c1oappe.top/Article/details/gtolzvyflc.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtpnbmmosv.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.yuxming.cn/Article/details/gtyowxdenm.html

[D15] 去重
来源：http://dali.pycfn.com/Article/details/gtjplseven.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gtfbmopldw.html

PHP:  array_unique($arr);
来源：http://dali.jqgfzy.top/Article/details/gtsefytfyr.html

JS:   [...new Set(arr)]
来源：http://dali.kuanghao11.cn/Article/details/gtysueofqn.html

TS:   [...new Set(arr)]
来源：http://dali.tanke756.top/Article/details/gtlbpdnxlx.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.c1oappe.top/Article/details/gtifddebvp.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.quarkkingdee.top/Article/details/gtqsdpujoc.html

Ruby: arr.uniq
来源：http://dali.feifeiyinyue.top/Article/details/gtflvaxxne.html

C#:   list.Distinct().ToList()
来源：http://dali.jinqigufen.top/Article/details/gtcultgnwa.html

[D16] 求和与平均值
来源：http://dali.snrcjt.cn/Article/details/gtqmrxekjo.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.vqdsnc.cn/Article/details/gtofweghsk.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.snrcjt.cn/Article/details/gtlugsilhy.html


<!-- 参考信息 -->