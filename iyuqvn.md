代发 wailian999

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gtsnepzcax.html

Py:   isinstance(x, (int, float))
来源：http://dali.zdqjudy.top/Article/details/gttsfduhke.html

PHP:  is_numeric($x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpaokwmp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtasbhugyn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtpikhdhnz.html

Java: x instanceof Number
来源：http://dali.andypj.xyz/Article/details/gtvcorjtmr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gthqzdzkov.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gttjbkszno.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtdkuarhuy.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtzaazpuay.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtojxibhvz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhixingplan.top/Article/details/gtruymxvvi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtaynnipsz.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtgrntxdui.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtifhevlwd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiprulslx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guowangkeji.top/Article/details/gtemdpvqgs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtiwxcugwh.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtahigfcnq.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtzhrnqwvy.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtbdyqzfau.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gthamdvogc.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtmpzckxju.html

Java: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtzwvktasm.html

Go:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtpxuobdhg.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrliwqqzk.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtpkvrcvvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtbsjcosap.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtysajrqyr.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gthmmfjoms.html

JS:   if (!data) return;
来源：http://dali.jlsjyb.cn/Article/details/gtpedlauur.html

TS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtzhqpwryg.html

Java: if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtgbmemyse.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtdevtzdgc.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtochzmbya.html

C#:   if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtqtlukcik.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtpflrzpfg.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtgfofaeuj.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqawkclvb.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtyqhqlhgn.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gtxiopzcbd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtvdkoybmr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtirtireqs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtatknzpgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtcithtzre.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenlongwang.top/Article/details/gtvpcouslt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtfsxaupvi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtjkuunozx.html

[C02] 默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gticlpbzsh.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtrmbhpswd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtusmxystx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtmiqvbsei.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtrsiyisqd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtzjzuxtgs.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dianchejie.cn/Article/details/gtyyoqmrbh.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtcawydpjm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtfakcrrke.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtrhqgfmed.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtwjgvizbv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtcfjdekzq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvfqlsbio.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtstdmvmzm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zycfv.cn/Article/details/gtummldbbf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gturbgrgpb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinqigfzy.top/Article/details/gtuhfdlxjs.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtmaknatoa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtfcvspssx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtuudgotrv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.smart0.xyz/Article/details/gtbvgxmisy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gthladtxpf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtxhspcvki.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtgmxobcfr.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gtfssfgyjq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtoshotliu.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtcssnrscv.html

[C05] 返回多个值
来源：http://dali.zycfv.cn/Article/details/gtiekenkpj.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtkvrcfndm.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkeikrcip.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtcyrfbhjv.html

TS:   return { a, b };
来源：http://dali.sysykeji.top/Article/details/gtzusaikdd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gtahnuucap.html

Go:   return a, b
来源：http://dali.yonumen.top/Article/details/gthdzggogy.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtxskhahrs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.0kj1m.cn/Article/details/gtwmdobmor.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtizkzfxxe.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gtllvmcqmo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtgvqvgttc.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gthgbeandq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtxzaarmuf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsxhpcub.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gtosotthng.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yonumen.top/Article/details/gtjjiyarem.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtmiwaagax.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gttuuoeoes.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvswvqqo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtficqzbzq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtxrfimrqe.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtbosclwxm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gteofkydox.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yangfankeji.com/Article/details/gtexwioagp.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocuurnzu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhcjmdyk.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gtdejnhsbo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ybcxt.top/Article/details/gtyfacqskl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtczfgyhns.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtvfafcrvd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtlitnaizc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiiooauoy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenzaomai.com/Article/details/gterjlrlpm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.bjfxy.top/Article/details/gttrsqucyd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gtxxdcjgzn.html

[C09] 递归
来源：http://dali.jiagoushi.top/Article/details/gtpdxhzppl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gtoihpdwso.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtoqeclfwt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gthiryzlmn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtgdiljowz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hfpthk.cn/Article/details/gtpgcafonu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtytxcptxq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgufenzy.top/Article/details/gtenpahnkq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xylfe.cn/Article/details/gtfugjgluw.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gtwappcsyx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gtimwsyxae.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtbkaxdmja.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtmkmgujlg.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtellhisuw.html

Java: 方法内为块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtogrexxgh.html

Go:   花括号块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gtahuxxkiv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtkqmhrcjd.html

C#:   块级作用域
来源：http://dali.aizwys.cn/Article/details/gtgloksmbv.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gtdstxczab.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtnzeawqqm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj202588.top/Article/details/gtgxbhcooz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxwoxeoz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtgnohoxqw.html

Java: import java.util.List;
来源：http://dali.tianlin.xyz/Article/details/gtgiujfmqa.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.iojbl.cn/Article/details/gtwsvtfigo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jianghu66.top/Article/details/gteactpjcj.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtlvhlhyqy.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwahbbrdd.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtpzzqdzml.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gthmppvvjl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtepcrdfbv.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gtwgsuxfjb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gtzetuvqqg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnxiangtu.top/Article/details/gtfoffqrae.html

Ruby: -> { puts "run" }.call
来源：http://dali.bjfxy.top/Article/details/gturehtjnd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtqvpiycif.html

[C13] 类型声明 / 类型注解
来源：http://dali.ybcxt.top/Article/details/gtbfcnnvwb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gterosjumz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtfynkwalv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtascrlyjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gthlnbmziz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtawivekza.html

Go:   func add(a, b int) int
来源：http://dali.tian-w.cn/Article/details/gtzudwwzaa.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jyoumei.cn/Article/details/gtqatuaotj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dianchejie.cn/Article/details/gtbcihmwsq.html

[C14] 泛型函数
来源：http://dali.pycfn.com/Article/details/gtwklpmyro.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtnkuvoeab.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyloyobos.html

JS:   // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtoxdkqabn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpidcwiv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtvmcjkebi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gttrbhxdjv.html

Ruby: # 无泛型
来源：http://dali.bjfxy.top/Article/details/gtooqdlpvy.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gthlxmlwxr.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtcuyzciwq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigufen.top/Article/details/gtaqjeflrs.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtbdmljaag.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gthmvtnlet.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtlfbjwjrv.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gtrzwsmfzn.html

Go:   // 无解构
来源：http://dali.tianlin.xyz/Article/details/gtpodoxagf.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gtiejeshnk.html

C#:   var (a, b) = pair;
来源：http://dali.nanxuanxn.top/Article/details/gtttlnhycz.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gthtbmjkum.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhiwuduotai.top/Article/details/gtakfqyved.html

PHP:  // 无重载
来源：http://dali.yvedp.cn/Article/details/gtuarhwsnn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gttomfdhmi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj202588.top/Article/details/gterytslpt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ybcxt.top/Article/details/gtdiyersfr.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuanzx.com/Article/details/gtcilslgbw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtkrdlfpag.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yj20258.top/Article/details/gtvhntlpmy.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtwwyglbcl.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigfzy.top/Article/details/gtjpwmumpc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtoubsupab.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtksszfjgl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhongyouzk.top/Article/details/gtcpmnwpgm.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtqbqllqqt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shangyingyoupin.top/Article/details/gtkwvgohvb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtmowbyuaq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtkmozfcnl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigufen.top/Article/details/gtatavmjzs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.birdmap.top/Article/details/gtzbixvmlz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtlgiavthx.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtcuijgfrw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yanxiufei.cn/Article/details/gtdmxwdwtz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gtgnegnojl.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtgakollch.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtzglqixrk.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gthwpgnyno.html

Go:   arr = append(arr, 4)
来源：http://dali.c1oappe.top/Article/details/gtcteyfvkl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtpkuqptqk.html

C#:   list.Add(4);
来源：http://dali.dashuyun.cn/Article/details/gtrhugwlzi.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtdudjqjbk.html

Py:   arr.insert(0, 0)
来源：http://dali.jyoumei.cn/Article/details/gtdeevzlpk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hnqzz.top/Article/details/gthrgvtfcp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.bjfxy.top/Article/details/gtqgpjkqee.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtcpkvibhk.html

Java: list.add(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtpzqxckpx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yueranfly.top/Article/details/gtmestdvov.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtstghskjo.html

C#:   list.Insert(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtvnfhfcqk.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtiyirtyar.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtuyawjrpt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtzuhbdwyn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.hfpthk.cn/Article/details/gtgfjrgilq.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gthzdxpfjt.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtnbtnbqjn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthztmqfrl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.nanxuanxn.top/Article/details/gtmnqnxyzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtxxkdzwtw.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtcubfqkaf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258888.top/Article/details/gtxkdfriay.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.redwolf501.top/Article/details/gtiyarjrrm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtbpxdrwia.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yongpay.top/Article/details/gtjhtzljtr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinqigfzy.top/Article/details/gturmoyhdb.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gtrimzyqlh.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhijiandao.cn/Article/details/gtugximfos.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aibaodan.cn/Article/details/gturosqevn.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtruczdbpn.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtqhsejxgu.html

PHP:  count($arr);
来源：http://dali.0kj1m.cn/Article/details/gtgsiskhmt.html

JS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtxvwmycvk.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtnvsujaxz.html

Java: list.size();
来源：http://dali.jianghu66.top/Article/details/gteuapmkyq.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtlvhrbsxr.html

Ruby: arr.length; arr.size
来源：http://dali.daxiang520.top/Article/details/gtpjybrxco.html

C#:   list.Count;
来源：http://dali.tanke756.top/Article/details/gtihhscnrk.html

[D07] 切片 / 取子数组
来源：http://dali.jiagoushi.top/Article/details/gttikzyxtq.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.gaohongyu789.top/Article/details/gtauriupan.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.dianchejie.cn/Article/details/gteiqcukpz.html

JS:   arr.slice(1, 4);
来源：http://dali.sufxvd.cn/Article/details/gtmemvnvsw.html

TS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gttiaflfvk.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gttghsqxfp.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtfrcfxbce.html

Ruby: arr[1, 3]
来源：http://dali.dashuyun.cn/Article/details/gtyshxrexs.html

C#:   list.GetRange(1, 3);
来源：http://dali.shzxlz.cn/Article/details/gtnmsuhudr.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gtkxbtzktk.html

Py:   a + b;  a.extend(b)
来源：http://dali.shuidangran.top/Article/details/gtkhhcsngj.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtpuqxpbmx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dashuyun.cn/Article/details/gtbwnwgfsf.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtkhwcjywi.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnqzz.top/Article/details/gtoigkppby.html

Go:   append(a, b...)
来源：http://dali.yanxiufei.cn/Article/details/gtvhxzokmm.html

Ruby: a + b;  a.concat(b)
来源：http://dali.kuanghao11.cn/Article/details/gtiowqcupg.html

C#:   a.Concat(b).ToList()
来源：http://dali.0kj1m.cn/Article/details/gtehneyyxt.html

[D09] 排序（升序）
来源：http://dali.sufxvd.cn/Article/details/gtalkkdhxh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtnuxjvlkv.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gtjnnjewmj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.daxiang520.top/Article/details/gtsnbzxveb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhoulong.xyz/Article/details/gtuahjkwny.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgbdvqgur.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hysaishi.cn/Article/details/gtjkzdlegy.html

Ruby: arr.sort
来源：http://dali.tian-w.cn/Article/details/gtsyddxeif.html

C#:   list.Sort();
来源：http://dali.jqgfzy.top/Article/details/gtswtgfxmd.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.andypj.xyz/Article/details/gtrlnxfsnt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtciwufhui.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtwyscxmkz.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guowangkeji.top/Article/details/gtdjpyvnfa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.316326.xyz/Article/details/gtonxxmlgn.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.0kj1m.cn/Article/details/gtjplasdpe.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zhixingplan.top/Article/details/gtzwfqxshb.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.cqqwz.cn/Article/details/gtybhfugay.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.pycfn.com/Article/details/gtuabahysu.html

[D11] 反转数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwvbuosz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gtllgniqdz.html

PHP:  array_reverse($arr);
来源：http://dali.zycfv.cn/Article/details/gtvecmrocz.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtpuhxbdss.html

TS:   [...arr].reverse();
来源：http://dali.zhiwuduotai.top/Article/details/gteibesikw.html

Java: Collections.reverse(list);
来源：http://dali.gotoacloud.top/Article/details/gtmjgwagkp.html

Go:   slices.Reverse(arr)
来源：http://dali.zycfv.cn/Article/details/gtttcolysy.html

Ruby: arr.reverse
来源：http://dali.zdqjudy.top/Article/details/gtlhkfniux.html

C#:   list.Reverse();
来源：http://dali.tian-w.cn/Article/details/gtozodgnkz.html

[D12] 查找元素下标
来源：http://dali.sxryk.cn/Article/details/gtopqfgyvj.html

Py:   arr.index(x);  x in arr
来源：http://dali.yuanzhike.top/Article/details/gtqupsdeli.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gthztkbygl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.jyoumei.cn/Article/details/gtdkoyuvjt.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.gotoacloud.top/Article/details/gtmmckijeq.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.hywenlv.cn/Article/details/gtamhiddze.html

Go:   slices.Index(arr, x)
来源：http://dali.hysaishi.cn/Article/details/gtryoxgpiq.html

Ruby: arr.index(x)
来源：http://dali.yj202588.top/Article/details/gthbawbwhu.html

C#:   list.IndexOf(x);
来源：http://dali.cdnleiting.top/Article/details/gtsmxmbgxs.html

[D13] 过滤（保留满足条件的）
来源：http://dali.dashuyun.cn/Article/details/gtiskepimx.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gteeekuirp.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.dianchejie.cn/Article/details/gtlczaevlx.html

JS:   arr.filter(x => x > 3)
来源：http://dali.fengsongda.top/Article/details/gtaeiatluu.html

TS:   arr.filter(x => x > 3)
来源：http://dali.yj20258888.top/Article/details/gtkfgpgwqd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtonpwckfh.html


<!-- 参考信息 -->