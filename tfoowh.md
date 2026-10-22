代发 wailian999

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtmoagpnls.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gtuwwuxmst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtptefdild.html

[B12] 跳出多层循环
来源：http://dali.fzhhl.top/Article/details/gttmnarvpp.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jiagoushi.top/Article/details/gtfjxxzcyy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yonumen.top/Article/details/gtojovyeyq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtgogisyuu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtkelxjzjb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtutsnjjsk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gthxljxbxo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtouitdflm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gtmuzecnaf.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtfckjnyjq.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtwablwyna.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtfsajbzdc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtvzbnnhhg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtknthngiu.html

Java: x instanceof Number
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstropfzh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gtxidorzle.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gtbiybtdpb.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtdxasikdu.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtiqffsfqx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtpmqejfsy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gthzabzywk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtjkbysxql.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gthzymptrw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtmeiugsaq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtkujlgzij.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fengsongda.top/Article/details/gtzxgdswex.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtromyaccl.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwjrqcdo.html

Py:   a and b or not c
来源：http://dali.jinghuilouyu.cn/Article/details/gtrlvsiyor.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gttmaumryd.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtwlprqpny.html

TS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtrovyqkgq.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtbqxxnjem.html

Go:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtmpfwojpf.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gttlctfmes.html

C#:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtuutpuuji.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtgmwzitmz.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtygskupvl.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtsharoaou.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtxqibxlta.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtzsgbbcjb.html

Java: if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtgrzwnstd.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyptfmtj.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtbrgrwuwd.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtlqbipulz.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtcsdxmply.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtmcglkleg.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqtrrbrsj.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtrwnebdmk.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtbzcbvqvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtnycblfnq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbggjmins.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtvavbxcje.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtgyoklzsk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtdlvwgzkh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gtuwrttzui.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtygqeivmz.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtwrxsysep.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtrjafiirq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.c1oappe.top/Article/details/gtcxtfgdbh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gttcyauwwa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtenectlcl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yangfankeji.com/Article/details/gtbfjjgebm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nwbrower.top/Article/details/gtnqsawdag.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtwdhvrknx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zycfv.cn/Article/details/gtfxpoxiqf.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gthxvnylnd.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtayvczaqq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.0kj1m.cn/Article/details/gttmngfueb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtuqvatgfi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtpiunmvta.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtojfcrpxv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daria6918.cn/Article/details/gtogryflkh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gtxigtoybi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtkdamfsvd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aizwys.cn/Article/details/gtqrzymskj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtaqokiria.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtoihwrpka.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gtwqwibaeb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtxrxactce.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cdnleiting.top/Article/details/gtxzsnifnj.html

Go:   // 无：用配置结构体参数
来源：http://dali.shangyingyoupin.top/Article/details/gtyvrlxckp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtilmuudxr.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtsqgyagfn.html

[C05] 返回多个值
来源：http://dali.smart0.xyz/Article/details/gtqtptufbw.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtzwhkdoly.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtibwuoovu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzcfcsmn.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtmdfmptqy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtsjrlriyd.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtojxxnvuy.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gtukqyqvgb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gtbnjamcdt.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtsezhqwtj.html

Py:   square = lambda x: x * x
来源：http://dali.yj202588.top/Article/details/gtntsxuigk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shzxlz.cn/Article/details/gtfxhjqczz.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gteofhhief.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtsklcthhc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gteanruwuq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ivvv.top/Article/details/gthoryxqxb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gttpzyaicl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtzjinkllk.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtkhgtcfkv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtniullvjw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtoksegtlu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yvedp.cn/Article/details/gtgdbczlrq.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtubffhpyg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtwnjabhku.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gtrjjlusxh.html

Ruby: arr.map(&:upcase)
来源：http://dali.aibaodan.cn/Article/details/gtnmrellki.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtxjgqwrlp.html

[C08] 闭包
来源：http://dali.shzxlz.cn/Article/details/gtjmzabpox.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.316326.xyz/Article/details/gtqrxakzij.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.bjfxy.top/Article/details/gtwudruisk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdmyhefko.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtmboznlnl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gogol.net.cn/Article/details/gtzshgbadn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtlssbfwde.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhqmhoyx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtmxkudpno.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtkufnuakm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtpiqzbihk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtqzfamhyi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gtkkrxeyou.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtypyjfaej.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtyoqkmejp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhixingplan.top/Article/details/gtrpiszeit.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gteqiuiybi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtyskqvtfi.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gtrvqljnrr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenjidiqi.icu/Article/details/gtstdrnxds.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtlrdpwiqx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtrfsyeisw.html

TS:   同 JS
来源：http://dali.gaohongyu789.top/Article/details/gtlkwbxmwe.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gttauseqxo.html

Go:   花括号块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtwpwfilpl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtpejeyeoi.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtxrxfzikp.html

[C11] 模块导入与导出
来源：http://dali.jqgufenzy.top/Article/details/gtjzpgaphw.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtlyiwnfzh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtqeinddlf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.andypj.xyz/Article/details/gtjuvjthum.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtjglxesov.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gttywtzijx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gtdbmwspci.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtepbnyfzg.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gtmnovaaib.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtnkwbauxt.html

Py:   (lambda: print("run"))()
来源：http://dali.sxryk.cn/Article/details/gtxcgftlgb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shangyingyoupin.top/Article/details/gttmlkmffz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cashguo.top/Article/details/gtdmfcqivs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtsupjvgve.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtqxckcgpc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jyoumei.cn/Article/details/gteatweocg.html

Ruby: -> { puts "run" }.call
来源：http://dali.jianghu66.top/Article/details/gtloisbxrt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtbeknrwvr.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gtdbiciyew.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jiagoushi.top/Article/details/gtckjhewxh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtwuaaxkbn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.vqdsnc.cn/Article/details/gtgrgebaxe.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtxfrgxxuv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtjsnnqfqj.html

Go:   func add(a, b int) int
来源：http://dali.gzhubu.top/Article/details/gtygnccijz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtjnlnlhwt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtedwsijwa.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtpaloykbv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhijiandao.cn/Article/details/gtcxxacdkw.html

PHP:  // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnlyqrjy.html

JS:   // 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtgsbmcqef.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtprpfrrre.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtthklsczr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.quarkkingdee.top/Article/details/gtwxcfqfqd.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtnzihqyyi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yueranfly.top/Article/details/gtgmrfgocf.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtmakdufhw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtihxoqztz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtqmscefrt.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtrhtenequ.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtstbflpid.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtmimgbctd.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtddfitovl.html

Ruby: a, b = pair
来源：http://dali.cdnleiting.top/Article/details/gtdlfdfxtt.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtommfsjhr.html

[C16] 函数 / 方法重载
来源：http://dali.feifeiyinyue.top/Article/details/gtzkfccnhc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.vqdsnc.cn/Article/details/gtlkrfewii.html

PHP:  // 无重载
来源：http://dali.yuxming.cn/Article/details/gtzmfbcqkq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gtsmriqhla.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtctxafxmg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteowxxpcf.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gtmwmoybfi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtlfzvtncl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gaohongyu789.top/Article/details/gtxcntxscy.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzayfdkgh.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtqgniczub.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtnrwmoizj.html

[D01] 创建数组 / 列表
来源：http://dali.cdnleiting.top/Article/details/gtftxdvsac.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sysykeji.top/Article/details/gtlffkmpci.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtgfvefcut.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shzxlz.cn/Article/details/gtjtfwwvyk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gotoacloud.top/Article/details/gtcpmzyydv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gthilhtkgk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtxsmtlcvp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtbjjwrmro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.havefunace.top/Article/details/gttlagzrrg.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtlvsmsjja.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.andypj.xyz/Article/details/gtcqhsgvdh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtenoklpri.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtxtjifdgw.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtvzlbkeou.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtsczizrar.html

Go:   arr = append(arr, 4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnfmiomqt.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqlrvyxk.html

C#:   list.Add(4);
来源：http://dali.cqqwz.cn/Article/details/gtpogqckrk.html

[D03] 在指定位置插入元素
来源：http://dali.jlsjyb.cn/Article/details/gtxnneiniz.html

Py:   arr.insert(0, 0)
来源：http://dali.havefunace.top/Article/details/gtfjizadgt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.vqdsnc.cn/Article/details/gtqhlleyag.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinyuanbaomall.cn/Article/details/gtteatpqed.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.vqdsnc.cn/Article/details/gtuucxyuep.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtcpbjurxu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtfiywenxq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.quarkkingdee.top/Article/details/gtldcqfuww.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtsxadsuxy.html

[D04] 删除元素
来源：http://dali.316326.xyz/Article/details/gtuxblmkty.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gtmwmscdmt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtyrleoert.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj202588.top/Article/details/gttuqrgvii.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtsolrcalb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigufen.top/Article/details/gtbnqgsyph.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.iojbl.cn/Article/details/gtbcykpcgw.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuanzx.com/Article/details/gtsqtmapxz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xylfe.cn/Article/details/gtizkpadhg.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtgevdobai.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gttefdvpfp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtytjdpthy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtphqwmfdg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenjidiqi.icu/Article/details/gtxyitzwrt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jiagoushi.top/Article/details/gtcmhcjppg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.havefunace.top/Article/details/gtbruxrjtk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hysaishi.cn/Article/details/gtfnlwvvic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gttvelkkji.html

[D06] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuobtprrz.html

Py:   len(arr)
来源：http://dali.yongpay.top/Article/details/gtekvqpayw.html

PHP:  count($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtfyedvdik.html

JS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gtnulrleqh.html

TS:   arr.length
来源：http://dali.pycfn.com/Article/details/gthhbpzalu.html

Java: list.size();
来源：http://dali.tanke756.top/Article/details/gtlusujqqs.html

Go:   len(arr)
来源：http://dali.cdnleiting.top/Article/details/gtegdiiojn.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gthjqlqcgh.html

C#:   list.Count;
来源：http://dali.shuidangran.top/Article/details/gthtfvydhw.html

[D07] 切片 / 取子数组
来源：http://dali.hnqzz.top/Article/details/gtfqovjfha.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtiijdircu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtxuibsbjd.html

JS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtwzmpktlk.html

TS:   arr.slice(1, 4);
来源：http://dali.316326.xyz/Article/details/gtrglcfrsc.html

Java: list.subList(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtgpnfuwjq.html

Go:   arr[1:4]
来源：http://dali.xuetiantiany.cn/Article/details/gtlqvqdejv.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaixjtext.html

C#:   list.GetRange(1, 3);
来源：http://dali.sufxvd.cn/Article/details/gturbopyyo.html

[D08] 合并两个数组
来源：http://dali.wangdashe.top/Article/details/gthlmcopoo.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvekebwm.html

PHP:  array_merge($a, $b);
来源：http://dali.vqdsnc.cn/Article/details/gtqioyziop.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gtybgfurhm.html

TS:   [...a, ...b];
来源：http://dali.hysaishi.cn/Article/details/gticlmisbc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.cashguo.top/Article/details/gtbjeiapdi.html

Go:   append(a, b...)
来源：http://dali.mhx1999.top/Article/details/gteuvhleib.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gteqimitwv.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gtsipppxxd.html

[D09] 排序（升序）
来源：http://dali.hfpthk.cn/Article/details/gthlfueepd.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtjfppjvwo.html

PHP:  sort($arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtvqtyofzg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinghuilouyu.cn/Article/details/gttjumzgtg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.fengsongda.top/Article/details/gtdzcbpteq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daria6918.cn/Article/details/gttpjmoflw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hywenlv.cn/Article/details/gtytcwobwv.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gtprhhfqav.html

C#:   list.Sort();
来源：http://dali.yj20258.top/Article/details/gtnplnefse.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtfdynmvph.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtfirvdboj.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtgguuqfjh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.birdmap.top/Article/details/gtlrkvwbrk.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.wangdashe.top/Article/details/gtjkeevmeb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.snrcjt.cn/Article/details/gtfsnhfsfk.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.zycfv.cn/Article/details/gtqsfwvgfc.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yueranfly.top/Article/details/gtwohrsjfk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jlsjyb.cn/Article/details/gtcpnjlnvi.html

[D11] 反转数组
来源：http://dali.xuetiantiany.cn/Article/details/gtbbwghxuq.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.sxryk.cn/Article/details/gtbqkebntb.html

PHP:  array_reverse($arr);
来源：http://dali.shzxlz.cn/Article/details/gtpvexadot.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.pengpengdd.cyou/Article/details/gtcfdgokgr.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtcuzetqic.html

Java: Collections.reverse(list);
来源：http://dali.haohaochexian.top/Article/details/gtqhrtdiru.html

Go:   slices.Reverse(arr)
来源：http://dali.bjfxy.top/Article/details/gthgwthoti.html

Ruby: arr.reverse
来源：http://dali.cashguo.top/Article/details/gtgmihnnna.html

C#:   list.Reverse();
来源：http://dali.hnxiangtu.top/Article/details/gtquiredhc.html

[D12] 查找元素下标
来源：http://dali.hnqzz.top/Article/details/gtewkmgudk.html

Py:   arr.index(x);  x in arr
来源：http://dali.shangyingyoupin.top/Article/details/gtsfyztspx.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hammf.cn/Article/details/gteyoyfaar.html


<!-- 参考信息 -->