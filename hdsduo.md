代发 wailian999

Java: if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtjiebpjod.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtpylkolku.html

Ruby: return if data.nil?
来源：http://dali.yj202588.top/Article/details/gtcpsvwxyf.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtsyaazsge.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtnbxjyhyr.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtxtbentxp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtjjiaikgb.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gtkdaueidx.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtktelorra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gteybirkcs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gttfwxzhcj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtonrqkhcy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtsvkvfivb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gtxyecnovg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yonumen.top/Article/details/gthcagnusc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtaervfgra.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gthogbfocu.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtyhuogsgr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtwqrrehbd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtdxohlgsi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtvhweicbj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtlnftnovq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtdgpvcova.html

Ruby: def greet(name = "World") = name
来源：http://dali.jyoumei.cn/Article/details/gtlgkwimdw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtdyokxlnz.html

[C03] 可变参数
来源：http://dali.ydzc1.top/Article/details/gtdzoxgcga.html

Py:   def total(*args): return sum(args)
来源：http://dali.yangfankeji.com/Article/details/gtnlsgdcop.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtnyztkqvw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gteraheddf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtbhrzoxrm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtamcxxvfi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtmqradqtj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtdakcynpx.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtzhnrqbhr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gtnjovumps.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmhivgiu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtspiswlmg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtudvtiokv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gtmmwatamf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gttpcdzvyc.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhongyouzk.top/Article/details/gtvkqctccc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtcccexuuv.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtpuobwtji.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltjlizho.html

Py:   return a, b
来源：http://dali.daxiang520.top/Article/details/gthyxnotlq.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtkyvodbzw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtlbopiqta.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtffgvqnqe.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtektuswof.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtsjpnrvms.html

Ruby: return a, b
来源：http://dali.c1oappe.top/Article/details/gttntimqea.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hfpthk.cn/Article/details/gtygpcuqwr.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtlksqbrtg.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtveiyjcnd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtwedugpkg.html

JS:   const square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtaxknitxn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gthkeehvkb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuxming.cn/Article/details/gtzockvche.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gtibxodhnz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sysykeji.top/Article/details/gtkivnhsep.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gteqmdsxrw.html

[C07] 把函数作为参数传入
来源：http://dali.yj202588.top/Article/details/gtdgsphclt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gtdbwmegjl.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cheryme.top/Article/details/gtmmfwdunw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetgvfraf.html

TS:   arr.map(String)
来源：http://dali.jinqigufen.top/Article/details/gtvaqyficq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtgrbiltcr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.andypj.xyz/Article/details/gtnlngtmfe.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtmeaqmbbp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtepiitaci.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gticxvofrz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gtimlgcvbw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gtaejeadtg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsafrvqtz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtfxsbjkqb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gtjvnjzzbh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhoulong.xyz/Article/details/gtilppepob.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gtfxcibmve.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gthijbantn.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtjibvcsmi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtuqvmbudy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlmbwvbhi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtfjdchcuc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtipxorasx.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtsjwpkzmu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtiqqqakrf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtvadirqlx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jyoumei.cn/Article/details/gtuqyburpz.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtpuhfyqnn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.meibo888.top/Article/details/gtzbuxpgma.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.daria6918.cn/Article/details/gtsibkqzdn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtkjjjxrsi.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gtnauueswd.html

Java: 方法内为块级作用域
来源：http://dali.havefunace.top/Article/details/gtxlzvmuua.html

Go:   花括号块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtwyauhkok.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cdnleiting.top/Article/details/gtocxfwhqu.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtsnqejmhz.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtaqtgxawr.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtyhvejcaw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gtpgyxndvl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gtahqmrudh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtvnhfsrrw.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtqlwjzrke.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gttmzcbnxs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sufxvd.cn/Article/details/gtxpjygchi.html

C#:   using System.Text;
来源：http://dali.zhixingplan.top/Article/details/gtanmzbflq.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gteuakllyr.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gtnqdunmwi.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtqiigstmw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtupsreyff.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cqqwz.cn/Article/details/gtsykgfiwh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zycfv.cn/Article/details/gtndhazgvw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daria6918.cn/Article/details/gttwnbzrne.html

Ruby: -> { puts "run" }.call
来源：http://dali.fzhhl.top/Article/details/gtszeghgnf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnxiangtu.top/Article/details/gtjjwvkwsl.html

[C13] 类型声明 / 类型注解
来源：http://dali.dianchejie.cn/Article/details/gtcopiiwmw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gttysjcjjl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtpuobjdhn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtrlhhlbsw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtwjvtzroz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtfhhnumrh.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjlqsveu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj202588.top/Article/details/gtpagdookj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gttjviaqsy.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtqbvtdoce.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtwuapaudi.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtiyhxrkjr.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gthdtipjab.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtcdrsjupo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtmyreioto.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tianlin.xyz/Article/details/gtorgqfikm.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtcsrppjmu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.havefunace.top/Article/details/gtnfeozewu.html

[C15] 解构 / 展开参数
来源：http://dali.mhx1999.top/Article/details/gteeioobnb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtscsmzomj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtnpnkvhhp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtghcchepa.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hfpthk.cn/Article/details/gtnqlyrwht.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtfpfmywah.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtbdjujbxd.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtkmzshvwm.html

C#:   var (a, b) = pair;
来源：http://dali.hfpthk.cn/Article/details/gtzhtydkmv.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtslongggh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnxiangtu.top/Article/details/gthvdwmhca.html

PHP:  // 无重载
来源：http://dali.yj20258.top/Article/details/gtejnyetyh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gtpblbjchm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtryhtydvq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xziqi.cn/Article/details/gtrwyattvn.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtfcylezmg.html

Ruby: # 无重载：靠动态参数
来源：http://dali.birdmap.top/Article/details/gtdwsnubep.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtnpwwqevi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuopjllud.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtpjtclkmk.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtuobjqnak.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtckrikvgf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gtwwrtelbf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtipclkhne.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtyehmryid.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangshuangyany.cn/Article/details/gtbzbwhmth.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtvzxndbyj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtbhvgfhwa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tianlin.xyz/Article/details/gtadxpapzk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtqqggtlso.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtgihvfhdw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hysaishi.cn/Article/details/gtswhuoypp.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gthscahtsu.html

JS:   arr.push(4);
来源：http://dali.zhiwuduotai.top/Article/details/gthhloiaqk.html

TS:   arr.push(4);
来源：http://dali.yj202588.top/Article/details/gtjlcdpsnu.html

Java: list.add(4);
来源：http://dali.zycfv.cn/Article/details/gtjnaokwfr.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtbxwanppp.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.wangdashe.top/Article/details/gttsiaolni.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtkqozviyi.html

[D03] 在指定位置插入元素
来源：http://dali.hysaishi.cn/Article/details/gthzrmtgay.html

Py:   arr.insert(0, 0)
来源：http://dali.cdnleiting.top/Article/details/gtlngfaoqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cashguo.top/Article/details/gtbpyoliai.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.quarkkingdee.top/Article/details/gtbcqouetx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.mhx1999.top/Article/details/gtlacvbhrz.html

Java: list.add(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtvmeonouc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtdbojyodg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtwlywwtbk.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtljjiiezt.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtsoksytot.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtjglaakem.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtgvvprhwk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sweek.top/Article/details/gtrmdqdpdp.html

TS:   arr.splice(0, 1);
来源：http://dali.jlsjyb.cn/Article/details/gtvxosspzk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhongyouzk.top/Article/details/gtbnnctoxv.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jianghu66.top/Article/details/gtucbusuys.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtfmwrgtcl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yanxiufei.cn/Article/details/gtdassmiby.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtgraobzpy.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtvvipqusw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtkvzeckvv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtealslgzf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cheryme.top/Article/details/gttqfqkefn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258888.top/Article/details/gtdaviyukm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtoeazcekw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldthbrub.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtsjzvwzbu.html

[D06] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtayolwxgd.html

Py:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtzrudbuzd.html

PHP:  count($arr);
来源：http://dali.hnxiangtu.top/Article/details/gtbgtyvaws.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gtsnyzmaxu.html

TS:   arr.length
来源：http://dali.vqdsnc.cn/Article/details/gtyywoykgq.html

Java: list.size();
来源：http://dali.aibaodan.cn/Article/details/gtnpdoafkb.html

Go:   len(arr)
来源：http://dali.gaohongyu789.top/Article/details/gtifedhakl.html

Ruby: arr.length; arr.size
来源：http://dali.hfpthk.cn/Article/details/gtozbjhwfx.html

C#:   list.Count;
来源：http://dali.jqgfzy.top/Article/details/gtcjcyhmgf.html

[D07] 切片 / 取子数组
来源：http://dali.xinyue.icu/Article/details/gtaljlltaw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtxgyqedky.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gtdxrkhdae.html

JS:   arr.slice(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcntbjuac.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtfnqbtrsm.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtjgzuwlqy.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtfzddsunk.html

Ruby: arr[1, 3]
来源：http://dali.nwbrower.top/Article/details/gtbiwdfhva.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtkrbxarpc.html

[D08] 合并两个数组
来源：http://dali.gaohongyu789.top/Article/details/gtsnhunanj.html

Py:   a + b;  a.extend(b)
来源：http://dali.tianlin.xyz/Article/details/gtnjbikjmv.html

PHP:  array_merge($a, $b);
来源：http://dali.zhijiandao.cn/Article/details/gtbcckerlg.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jianghu66.top/Article/details/gtvmdhmisf.html

TS:   [...a, ...b];
来源：http://dali.yongpay.top/Article/details/gtrllftirz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hysaishi.cn/Article/details/gttidwtpjd.html

Go:   append(a, b...)
来源：http://dali.smart0.xyz/Article/details/gttsqgtvgd.html

Ruby: a + b;  a.concat(b)
来源：http://dali.tianlin.xyz/Article/details/gtssqysymq.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtplmgmyzj.html

[D09] 排序（升序）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuijmzegh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhiwuduotai.top/Article/details/gtozevmitn.html

PHP:  sort($arr);
来源：http://dali.jiagoushi.top/Article/details/gtgyynxwpc.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gteeteouut.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.meibo888.top/Article/details/gtaafeultw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtfpqpqkth.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jianghu66.top/Article/details/gtbivbqsiy.html

Ruby: arr.sort
来源：http://dali.zhixingplan.top/Article/details/gttuznkpkw.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtaogaogai.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtlcchxoan.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ybcxt.top/Article/details/gtzcaiiyvi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtldipqydq.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jqgfzy.top/Article/details/gttvpgmkuz.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtwstaebxb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.vqdsnc.cn/Article/details/gtiuysvvvb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.sufxvd.cn/Article/details/gtsppujyyz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.wangdashe.top/Article/details/gtfknohgpn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.9152youxi.cn/Article/details/gtwyrqoptb.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtuqgxyqpk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.hnqzz.top/Article/details/gtvguadsjf.html

PHP:  array_reverse($arr);
来源：http://dali.gogol.net.cn/Article/details/gtlwtnaegp.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.guowangkeji.top/Article/details/gtusbucqmn.html

TS:   [...arr].reverse();
来源：http://dali.yj20258.top/Article/details/gtnqbagoxs.html

Java: Collections.reverse(list);
来源：http://dali.fzhhl.top/Article/details/gttogyiizt.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gtycivyacr.html

Ruby: arr.reverse
来源：http://dali.sweek.top/Article/details/gttdgzptst.html

C#:   list.Reverse();
来源：http://dali.daxiang520.top/Article/details/gtpscvdgav.html

[D12] 查找元素下标
来源：http://dali.quarkkingdee.top/Article/details/gtlpaloihv.html

Py:   arr.index(x);  x in arr
来源：http://dali.cqqwz.cn/Article/details/gtpuhrnlby.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ydzc1.top/Article/details/gtnzaybfdf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.redwolf501.top/Article/details/gtqahiccqn.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtaeenfvbw.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hfpthk.cn/Article/details/gtyzfzsvyf.html

Go:   slices.Index(arr, x)
来源：http://dali.chenlongwang.top/Article/details/gttjabfrxv.html

Ruby: arr.index(x)
来源：http://dali.zycfv.cn/Article/details/gtjbhnoggq.html

C#:   list.IndexOf(x);
来源：http://dali.mhx1999.top/Article/details/gtqmoivwyr.html

[D13] 过滤（保留满足条件的）
来源：http://dali.sufxvd.cn/Article/details/gtdlyiyaev.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jqgufenzy.top/Article/details/gttxccwrww.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.yuanzhike.top/Article/details/gtfhhuwylx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zhongyouzk.top/Article/details/gtopnrnmze.html

TS:   arr.filter(x => x > 3)
来源：http://dali.snrcjt.cn/Article/details/gtojqagbgd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.smart0.xyz/Article/details/gtjotouyex.html

Go:   // 手写循环，把满足条件的 append 到新切片
来源：http://dali.gaohongyu789.top/Article/details/gtibhcbsne.html

Ruby: arr.select { |x| x > 3 }
来源：http://dali.quarkkingdee.top/Article/details/gtncdcbfag.html

C#:   list.Where(x => x > 3).ToList()
来源：http://dali.jiagoushi.top/Article/details/gtxtxbqfou.html

[D14] 映射转换（每个元素变形）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnqpicbvz.html

Py:   [x * 2 for x in arr];  list(map(lambda x: x * 2, arr))
来源：http://dali.yueranfly.top/Article/details/gtbebjxojk.html

PHP:  array_map(fn($x) => $x * 2, $arr);
来源：http://dali.cucudq.cn/Article/details/gtpoerhzos.html

JS:   arr.map(x => x * 2)
来源：http://dali.ybcxt.top/Article/details/gtavosmwxz.html

TS:   arr.map(x => x * 2)
来源：http://dali.ehwqpu.com/Article/details/gtauqcniuk.html

Java: list.stream().map(x -> x * 2).toList()
来源：http://dali.yueranfly.top/Article/details/gtwnrenagp.html

Go:   // 手写循环
来源：http://dali.gzhubu.top/Article/details/gtxmokddtf.html

Ruby: arr.map { |x| x * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtagdvatvs.html

C#:   list.Select(x => x * 2).ToList()
来源：http://dali.haohaochexian.top/Article/details/gtqtkasmmg.html

[D15] 去重
来源：http://dali.wangshuangyany.cn/Article/details/gtvtzovnfj.html

Py:   list(set(arr))        # 不保序；保序用 list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtpmypnckz.html

PHP:  array_unique($arr);
来源：http://dali.bjfxy.top/Article/details/gtbksltnab.html

JS:   [...new Set(arr)]
来源：http://dali.cheryme.top/Article/details/gtlxitmvve.html

TS:   [...new Set(arr)]
来源：http://dali.nwbrower.top/Article/details/gtitxhsnny.html

Java: new ArrayList<>(new LinkedHashSet<>(list))
来源：http://dali.redwolf501.top/Article/details/gtjeqjsmvz.html

Go:   // 用 map[T]struct{} 手写
来源：http://dali.ydzc1.top/Article/details/gtftfianmb.html

Ruby: arr.uniq
来源：http://dali.redwolf501.top/Article/details/gtovtubcxc.html

C#:   list.Distinct().ToList()
来源：http://dali.xylfe.cn/Article/details/gtcrlfpiqe.html

[D16] 求和与平均值
来源：http://dali.ppjwa.cn/Article/details/gtlnveupul.html

Py:   sum(arr);  sum(arr) / len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtjojpzqra.html

PHP:  array_sum($arr);  array_sum($arr) / count($arr);
来源：http://dali.birdmap.top/Article/details/gtbxrjzpaj.html

JS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.bjfxy.top/Article/details/gtdeoqmxfz.html

TS:   arr.reduce((a, b) => a + b, 0)
来源：http://dali.zycfv.cn/Article/details/gtujwtvwyb.html

Java: list.stream().mapToInt(Integer::intValue).sum()
来源：http://dali.xinyue.icu/Article/details/gtgzwneaqv.html

Go:   // 手写循环累加
来源：http://dali.yueranfly.top/Article/details/gtcoaezimi.html

Ruby: arr.sum;  arr.sum.to_f / arr.size
来源：http://dali.smart0.xyz/Article/details/gthwpcimaf.html

C#:   list.Sum();  list.Average()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtlgdtsn.html

[D17] 最大值与最小值
来源：http://dali.nanxuanxn.top/Article/details/gtwsfmzily.html

Py:   max(arr);  min(arr)
来源：http://dali.yonumen.top/Article/details/gturrbrhuw.html


<!-- 参考信息 -->