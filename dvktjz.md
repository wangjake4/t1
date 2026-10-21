代发 wailian999

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuetiantiany.cn/Article/details/gtxmjoopgl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sufxvd.cn/Article/details/gtskwqpugr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtxocndmhf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtftnimowe.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtqklrhkla.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtphbdwurg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtytjqdplz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gthptyfmfl.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtlwphwwij.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtmovlvoyz.html

PHP:  is_numeric($x)
来源：http://dali.cucudq.cn/Article/details/gtpkaqeblx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtaujepybd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtotpoigdh.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtblxigjpr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtbpvkbhmz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.mhx1999.top/Article/details/gtzuxjoxvj.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtajwvdudf.html

[B14] 判断值是否在集合内
来源：http://dali.nanxuanxn.top/Article/details/gtnenaclah.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtfrcnuswj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtyiuahjed.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtatgxsfnh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtdtdhckbm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtdnkflzsl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yueranfly.top/Article/details/gterpfnuef.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtkzfkuabm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihnsmgdy.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtwassgikl.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtapxnzwoz.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gtybfjqjcn.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwbngniu.html

TS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtxxpfjevk.html

Java: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtmuszreph.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtqqmypyzb.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtdftnjkbs.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtxadokbbs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtgisfmele.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gtrnmwefkz.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtmdgordio.html

JS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtbsboznko.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtnorzccni.html

Java: if (data == null) return;
来源：http://dali.gzhubu.top/Article/details/gtwgsstyza.html

Go:   if data == nil { return }
来源：http://dali.yuxming.cn/Article/details/gtxxncqvbn.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtxugwecfc.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtgkgsivdx.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtamnvyjbn.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtagpuelkr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gttwgeazuq.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gtvfkmkvey.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuyisvpot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznxpwfjv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtwibavnod.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtzeumbzbg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtytuujehm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtsvpoggzk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtlbvhrekq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtfxzhzare.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtohpmzdog.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtrnzkqinj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtewcrjmio.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtimeeoacu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jqgfzy.top/Article/details/gtxvwvjmtq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gteuodakhi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gthdvqgpzy.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtupwjuktm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangdashe.top/Article/details/gtdkzdhffq.html

[C03] 可变参数
来源：http://dali.316326.xyz/Article/details/gtrxrbbegs.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gtljeiqdqw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtpnyjhfur.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtzyrgetys.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtttopoeas.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxuanxn.top/Article/details/gtjhcyyrpt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtwitdlnsv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtxbrsctuz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtjadinepm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ivvv.top/Article/details/gtfblbzvzr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtdmxjsozw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtzpsapczw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtwrmbnmkg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtfjsvlqmv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtlsksmzcv.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtgxcjlslt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtisemktyb.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtcyxrlkum.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gthquyvpny.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtoospmvtz.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpwdkhbcw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtwfhmkoxq.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gthxyebymp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gtctqjyygk.html

Go:   return a, b
来源：http://dali.cashguo.top/Article/details/gtlycziyqh.html

Ruby: return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtppmwyekt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxuanxn.top/Article/details/gtwhllhxfi.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtcovmgocs.html

Py:   square = lambda x: x * x
来源：http://dali.cdnleiting.top/Article/details/gtespmhvko.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gtgiihgcvw.html

JS:   const square = x => x * x;
来源：http://dali.pycfn.com/Article/details/gttaptzxyq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtsjefrhgq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtvoaiwrfo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtlotzuvfr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gtnraknocu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlqmyhtyl.html

[C07] 把函数作为参数传入
来源：http://dali.cashguo.top/Article/details/gtxohticlv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlfrlwui.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gthdfytsbk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnriavtkc.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtcdmqlohf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.pycfn.com/Article/details/gtekjzzcym.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtzfhihhvl.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gteostrzjl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtaaklgxih.html

[C08] 闭包
来源：http://dali.dashuyun.cn/Article/details/gtivkwpsre.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtjwutfndo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtohgtpiwz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtdeapckdd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtdhgaywzz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtoyhrpiqb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxuanxn.top/Article/details/gtxhjuccev.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtobodqixh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtacntqjtl.html

[C09] 递归
来源：http://dali.ywan-chungtsiang.top/Article/details/gtffpiyioq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtgzrpbzto.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ivvv.top/Article/details/gtbxkfxjfa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtdoxgakuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtinaiddyu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtvkxnjpnd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xylfe.cn/Article/details/gtnsnlzcap.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtbllcifon.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtdirkrhjb.html

[C10] 变量作用域
来源：http://dali.cheryme.top/Article/details/gtqgzyxirp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ydzc1.top/Article/details/gteyppwdlc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.kuanghao11.cn/Article/details/gtidwgidwd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gthcsdfhzm.html

TS:   同 JS
来源：http://dali.tanke756.top/Article/details/gtmvbubpmg.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtfgxjzbgl.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtsabtxmhx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtxumqjwpp.html

C#:   块级作用域
来源：http://dali.nanxinkj.top/Article/details/gtymzugzfw.html

[C11] 模块导入与导出
来源：http://dali.yj20258.top/Article/details/gtkymxqysb.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gtkrlfrltg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtwwwyyzmc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gtfafavhpt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtidkiydfd.html

Java: import java.util.List;
来源：http://dali.chenlongwang.top/Article/details/gtalsayume.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shuidangran.top/Article/details/gtvuatnmnw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtdztqviuj.html

C#:   using System.Text;
来源：http://dali.fengsongda.top/Article/details/gtavbsgrmh.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtaslcolsw.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gtsysliqmd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtrzingxzf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtwymjwxae.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtxclfhasm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gtzpnrstex.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.nwbrower.top/Article/details/gtruxxxuwh.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtwfueuuuo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.haohaochexian.top/Article/details/gtsmyqryec.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gtiysdiqsk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangdashe.top/Article/details/gthxicphci.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gthbwyxylo.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtehzvqoec.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtxqswxpbo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtszajusqq.html

Go:   func add(a, b int) int
来源：http://dali.hnxiangtu.top/Article/details/gtfwoxaeax.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.c1oappe.top/Article/details/gtwyqxwlxy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtashmvmww.html

[C14] 泛型函数
来源：http://dali.zhijiandao.cn/Article/details/gtwligwlnw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinghuilouyu.cn/Article/details/gtouvytsqi.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtgvlnmqma.html

JS:   // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykcamcof.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.birdmap.top/Article/details/gtbevcwxng.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtspdkucxa.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gtwfvbsuot.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtwxvrfiuk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtlpipiauk.html

[C15] 解构 / 展开参数
来源：http://dali.aizwys.cn/Article/details/gttdcggozo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangdashe.top/Article/details/gtmcsksnnb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gtahmkoyfj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtrmzqssoc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gtkzjhvkif.html

Java: // 无解构
来源：http://dali.zdqjudy.top/Article/details/gtsalgghmo.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtdeqmaqld.html

Ruby: a, b = pair
来源：http://dali.cashguo.top/Article/details/gtcmkzcgtc.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtlhtymcmf.html

[C16] 函数 / 方法重载
来源：http://dali.yueranfly.top/Article/details/gtfdwjfkdb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gtqykadyif.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtifnanrld.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.kuanghao11.cn/Article/details/gtgoniafcj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gthmbmdooq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtgawicilb.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtghdqtope.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtprlrsmom.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtxicttvlk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtorzyixbb.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtqsrbsqbh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmtjxyapq.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtwsmnsxdj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtpduqizsj.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sweek.top/Article/details/gtlysfcpmw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hammf.cn/Article/details/gthhtkrwfx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtvobrpbpt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gtdmrzyrpa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtlvwlloai.html

Ruby: arr = [1, 2, 3]
来源：http://dali.cdnleiting.top/Article/details/gtldzdkohl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.wangdashe.top/Article/details/gtsgarveja.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtfihxdpnz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.fengsongda.top/Article/details/gtobywmtpw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtasvbrxgq.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtmftawbst.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtofpcfkpz.html

Java: list.add(4);
来源：http://dali.yj20258888.top/Article/details/gtlsjyvdlx.html

Go:   arr = append(arr, 4)
来源：http://dali.wangshuangyany.cn/Article/details/gtonheyqpo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gtfsdotuap.html

C#:   list.Add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztfhtimu.html

[D03] 在指定位置插入元素
来源：http://dali.jyoumei.cn/Article/details/gtmnpwrbck.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtnbthdqvt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zdqjudy.top/Article/details/gtairvgvwh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gtzjgelmlh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtaxipbqyx.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygsktwxc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shuidangran.top/Article/details/gtzfszizcn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yj20258.top/Article/details/gttxjinzur.html

C#:   list.Insert(0, 0);
来源：http://dali.yonumen.top/Article/details/gtjvalegcq.html

[D04] 删除元素
来源：http://dali.yuxming.cn/Article/details/gtvarmaacc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtbujwpmyv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yangfankeji.com/Article/details/gtxfrynjdy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.bjfxy.top/Article/details/gtociaolqq.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtkuewdugm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtpbynnwbp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhixingplan.top/Article/details/gtkxarnkco.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlhqosxec.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtcoqirqko.html

[D05] 访问与修改元素
来源：http://dali.yuxming.cn/Article/details/gtnuzqsjwj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtiahkscen.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtjrzryklb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtwxzoecna.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.0kj1m.cn/Article/details/gtuhzkwcco.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.redwolf501.top/Article/details/gtreyldlmi.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtrpyvujzg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tian-w.cn/Article/details/gtvivaljal.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtdvartlvi.html

[D06] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtmdkqbeip.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtpbpstnzt.html

PHP:  count($arr);
来源：http://dali.yueranfly.top/Article/details/gtayevopuq.html

JS:   arr.length
来源：http://dali.chenzaomai.com/Article/details/gtjgymscii.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gthyqvmcbl.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtjpeeuayp.html

Go:   len(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtijsuawnm.html

Ruby: arr.length; arr.size
来源：http://dali.nanxuanxn.top/Article/details/gtjqvretaj.html

C#:   list.Count;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqeohgxlb.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtijwebnid.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xuetiantiany.cn/Article/details/gtwflmelxg.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tianlin.xyz/Article/details/gtvrqepovd.html

JS:   arr.slice(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtjbfntxqa.html

TS:   arr.slice(1, 4);
来源：http://dali.xuanzx.com/Article/details/gtjgjcjzwm.html

Java: list.subList(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtkumzttwi.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtguwhalhu.html

Ruby: arr[1, 3]
来源：http://dali.guowangkeji.top/Article/details/gtqlwznbvm.html

C#:   list.GetRange(1, 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkbdiwnxa.html

[D08] 合并两个数组
来源：http://dali.xinyue.icu/Article/details/gtxjmrizck.html

Py:   a + b;  a.extend(b)
来源：http://dali.hfpthk.cn/Article/details/gtgetjmndx.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtkgztknim.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.birdmap.top/Article/details/gtxklzbmxb.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtjnikjchx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtdefocxwt.html

Go:   append(a, b...)
来源：http://dali.chenjidiqi.icu/Article/details/gtopqugweh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtuutscfda.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtfgpyetlx.html

[D09] 排序（升序）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfsbktynm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gtkmuvvozx.html

PHP:  sort($arr);
来源：http://dali.jinqigufen.top/Article/details/gtqtrmxtiv.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hysaishi.cn/Article/details/gtxtvnzskt.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.cqqwz.cn/Article/details/gtnkfsmeaz.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zycfv.cn/Article/details/gtsqaayjil.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenjidiqi.icu/Article/details/gthtwgkphw.html

Ruby: arr.sort
来源：http://dali.sxryk.cn/Article/details/gthetimwpc.html

C#:   list.Sort();
来源：http://dali.cucudq.cn/Article/details/gttacqqpoq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.guannengcc.top/Article/details/gtlnztcpwo.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.gogol.net.cn/Article/details/gtywijdelc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtdmcoiqon.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cheryme.top/Article/details/gthhwlhals.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yj20258888.top/Article/details/gtudakfxww.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shangyingyoupin.top/Article/details/gtbkcohidb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jiagoushi.top/Article/details/gtnleosmff.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yangfankeji.com/Article/details/gtiyrwoerv.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenjidiqi.icu/Article/details/gtilwriadd.html

[D11] 反转数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlxwbewz.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sufxvd.cn/Article/details/gtdjksvxxh.html

PHP:  array_reverse($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtniqybrtv.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenjidiqi.icu/Article/details/gtkievmumi.html

TS:   [...arr].reverse();
来源：http://dali.0kj1m.cn/Article/details/gtsbyimety.html

Java: Collections.reverse(list);
来源：http://dali.ppjwa.cn/Article/details/gtzznexoio.html

Go:   slices.Reverse(arr)
来源：http://dali.tian-w.cn/Article/details/gtmyzwyryu.html

Ruby: arr.reverse
来源：http://dali.chenjidiqi.icu/Article/details/gtathwoqmo.html

C#:   list.Reverse();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarltrmet.html

[D12] 查找元素下标
来源：http://dali.yangfankeji.com/Article/details/gtpuxjixds.html

Py:   arr.index(x);  x in arr
来源：http://dali.zhengqikj.top/Article/details/gtjxzywtki.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.ppjwa.cn/Article/details/gtnwrwmjfz.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.guannengcc.top/Article/details/gtkqddruin.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.fzhhl.top/Article/details/gtdkdgjgha.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcgjlqhh.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtvxnppgkj.html


<!-- 参考信息 -->