代发 wailian999

[B13] 判断是否为数字
来源：http://dali.daxiang520.top/Article/details/gtgjrrzpwt.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtmdznjeoj.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtgxvlxqpa.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtwnkiwusg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtdlgpfnob.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gticuuqsib.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gturaxninu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.0kj1m.cn/Article/details/gtbfoszdrk.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gtrwakrnzl.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gtkwkydtjd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.feifeiyinyue.top/Article/details/gtlmgzuwqk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtptmwantk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtnisuzalk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtwytqpugy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtmatdfryc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtltanvros.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgfzy.top/Article/details/gtppjxmtru.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtzkrfjrpj.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtsjnywmfx.html

Py:   a and b or not c
来源：http://dali.chenlongwang.top/Article/details/gtmbmyzess.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtiojbcage.html

JS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtmxlfbmbb.html

TS:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjycguiyg.html

Java: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtulcydsha.html

Go:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gthwlhrfjm.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczhhddhw.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtuxqvfoxj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtyiwxvquh.html

Py:   if not data: return
来源：http://dali.iojbl.cn/Article/details/gtqpzvcqcy.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gteeucewng.html

JS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtvnsijnbj.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gtuezmsxni.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtydeywcuo.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotxnsdot.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtjypvwvfr.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtaoghleew.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtibgvmtag.html

C. 函数与作用域
来源：http://dali.sysykeji.top/Article/details/gtvyukkqgt.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtejhfzhrf.html

[C01] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtotydljms.html

Py:   def add(a, b): return a + b
来源：http://dali.xziqi.cn/Article/details/gtpliaqerl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gttroikfcm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtiluxqaof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gttgyjmhmz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtcekykqlz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.bjfxy.top/Article/details/gtaxdhgcnm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtpterbekj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtwacmwlvx.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gttkdutroa.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtjrczewzt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtolztphke.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtbjdphcjy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtvbgnihdy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.aibaodan.cn/Article/details/gtshgzpbnc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtipuzenmu.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtyskaioli.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtzqgbdrel.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtfoaobgcg.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtmlhebuur.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuanzx.com/Article/details/gtlvgiouwu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtrowiiskm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtvskoyybg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtccwvustm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtdqgfntvp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtcadjfkds.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwhgnrra.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yanxiufei.cn/Article/details/gtyhynixig.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.andypj.xyz/Article/details/gtxpgsqpmr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtzmyxlsbe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtxmqeeqih.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gtmzxbqiiw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.0kj1m.cn/Article/details/gtkelzsvrw.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gtkzsvqluz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtlweicqtd.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtqilefjqs.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtehomlbnd.html

Py:   return a, b
来源：http://dali.yongpay.top/Article/details/gtcrsslqnj.html

PHP:  return [$a, $b];
来源：http://dali.sufxvd.cn/Article/details/gtvqatwvxp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtplslnitt.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtasjwiyul.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gttmkylwdm.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtkfzswuzl.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtviixtvbs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfqvadze.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gtmwsczybg.html

Py:   square = lambda x: x * x
来源：http://dali.zhaomingkeji.xyz/Article/details/gthspbbyba.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtmaiapygt.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtfpfjrczy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.iojbl.cn/Article/details/gtnzglmtas.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtwgrvdvpm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtnpsqfptj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gtijleagkn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtqbmmmhbb.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtcqgcvxza.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daria6918.cn/Article/details/gtkdpptcfa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gtcflqcuom.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtuisfpwaj.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtwntxjhbh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gttnaindvo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtkcmzjfeg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yangfankeji.com/Article/details/gtxuroaedb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtjalibhhk.html

[C08] 闭包
来源：http://dali.svipenyu.cn/Article/details/gtjimeefzy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtygbduhtt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtgaxjhajc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtxzxmpjor.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtoconokmj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtudahwmdr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtvvpxvjwv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtnfhvazmt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtmvzfprim.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtbyxvyfvj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtxghzehzr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtyrnbvsez.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gthcroahmw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gtwgfqwtwb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gtccmoocmo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.fengsongda.top/Article/details/gtwygfhbvv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtnsdfezbh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtyhbvulpw.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtymjyekwx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.vqdsnc.cn/Article/details/gtbpqqwvtd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gtrddvxhom.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gthymtmwsx.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtcdxyumue.html

Java: 方法内为块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtbyewbhkx.html

Go:   花括号块级作用域
来源：http://dali.quarkkingdee.top/Article/details/gtjtjcpxai.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtukdpialp.html

C#:   块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtckewndwk.html

[C11] 模块导入与导出
来源：http://dali.jyoumei.cn/Article/details/gtymidvjxf.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gtwdldlqsz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmwguipfk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtvqrrhmob.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ivvv.top/Article/details/gtoqoqkuiv.html

Java: import java.util.List;
来源：http://dali.haohaochexian.top/Article/details/gtpzisnvep.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.havefunace.top/Article/details/gtkeybuggp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shangyingyoupin.top/Article/details/gtvdlqjona.html

C#:   using System.Text;
来源：http://dali.haohaochexian.top/Article/details/gtdskiogic.html

[C12] 立即执行函数 IIFE
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuqbbtzh.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gtzaqybktx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtzmsxvwmy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtuxucbspf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtvyvwdfbf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cashguo.top/Article/details/gtvqqupelq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtvektpqfu.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gtpppqdbgq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxinkj.top/Article/details/gtgpoycwxe.html

[C13] 类型声明 / 类型注解
来源：http://dali.hywenlv.cn/Article/details/gtruavdnbb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtwdunmycn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gttakqjafz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gthydojdux.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtebwdqeem.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbihjovfl.html

Go:   func add(a, b int) int
来源：http://dali.hongshengwenyu.top/Article/details/gtzcpryzve.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.andypj.xyz/Article/details/gtnholtuxu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhongyouzk.top/Article/details/gtaeuobgtg.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gtbhjiuklx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gthkhxxfvl.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqojbrbo.html

JS:   // 无泛型
来源：http://dali.ybcxt.top/Article/details/gthjpsmkgo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.kuanghao11.cn/Article/details/gtmlchlsqe.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtglcodlyq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gtlhigpcmv.html

Ruby: # 无泛型
来源：http://dali.316326.xyz/Article/details/gtoxkbasvz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.andypj.xyz/Article/details/gtwqgfhmlk.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwskydfl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.quarkkingdee.top/Article/details/gtpxeafcbz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhoulong.xyz/Article/details/gtfwxeesla.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtqvocupjo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.aizwys.cn/Article/details/gtoojdknhu.html

Java: // 无解构
来源：http://dali.zhengqikj.top/Article/details/gtgvfxrhnp.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtvuaknyki.html

Ruby: a, b = pair
来源：http://dali.yj20258888.top/Article/details/gtlzcrfavw.html

C#:   var (a, b) = pair;
来源：http://dali.sysykeji.top/Article/details/gtjgjvoajl.html

[C16] 函数 / 方法重载
来源：http://dali.tanke756.top/Article/details/gtctlflflh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtvhaisznd.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gttybcnzqk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.snrcjt.cn/Article/details/gtdoiirpmd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtiesosjnz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpckbmuyz.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtovdcbqjy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtmffqgnmn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtsuyuysyq.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtwjifmqxw.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gtljtjeklt.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnqxgoksl.html

[D01] 创建数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtgymribzw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.meibo888.top/Article/details/gttzdxtzao.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtnaulvysf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jqgfzy.top/Article/details/gtfmxsllhu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnxiangtu.top/Article/details/gtlsnajqed.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.bjfxy.top/Article/details/gtstrxoggt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtnotevrhs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jiagoushi.top/Article/details/gtcwjgztix.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtgylfkajh.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gthzbnpppn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtbyhktqxu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjtmymrbg.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtjfrzioxs.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtolpbljjb.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtosrsmleg.html

Go:   arr = append(arr, 4)
来源：http://dali.yanxiufei.cn/Article/details/gtvqalpeko.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.pengpengdd.cyou/Article/details/gtxofwropd.html

C#:   list.Add(4);
来源：http://dali.tianlin.xyz/Article/details/gtzymvnehv.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtwvbuznik.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gterlxuqdz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tian-w.cn/Article/details/gtrdvjimpy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xylfe.cn/Article/details/gtyoyfkxkc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtcunobgtr.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtxnqblurd.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmpthgzwe.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtqbforifm.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtvxwirsqu.html

[D04] 删除元素
来源：http://dali.redwolf501.top/Article/details/gtrzsgydxf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gttdgmesow.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.bjfxy.top/Article/details/gtbzklsrea.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtrxfvlyip.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdwzscnk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.iojbl.cn/Article/details/gtemxyignc.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxnomrdox.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtdeqlyzkg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.havefunace.top/Article/details/gtmihkbxri.html

[D05] 访问与修改元素
来源：http://dali.yonumen.top/Article/details/gtnkswvobs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtogyrsfhn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlrzzdla.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtbtodeymb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ydzc1.top/Article/details/gtcauqtunj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.sweek.top/Article/details/gtqcryirlh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gthmmcfzho.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gtqxpzmxxn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtefloamou.html

[D06] 数组长度
来源：http://dali.cqqwz.cn/Article/details/gtvknyjtzu.html

Py:   len(arr)
来源：http://dali.nwbrower.top/Article/details/gtkqqaylgh.html

PHP:  count($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtcegnlnql.html

JS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtntnjtzzc.html

TS:   arr.length
来源：http://dali.quarkkingdee.top/Article/details/gtgeelphrv.html

Java: list.size();
来源：http://dali.zhongyouzk.top/Article/details/gtatoxfnfg.html

Go:   len(arr)
来源：http://dali.fengsongda.top/Article/details/gtolrhhinx.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtdryeayty.html

C#:   list.Count;
来源：http://dali.cdnleiting.top/Article/details/gththmqyva.html

[D07] 切片 / 取子数组
来源：http://dali.cucudq.cn/Article/details/gthafhnvep.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtdqzlyfpt.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenzaomai.com/Article/details/gtibbobfuh.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtpjyhmuaq.html

TS:   arr.slice(1, 4);
来源：http://dali.jyoumei.cn/Article/details/gtjqtqhkjd.html

Java: list.subList(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtqtrfmitr.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtglaahtiu.html

Ruby: arr[1, 3]
来源：http://dali.jyoumei.cn/Article/details/gtyfnzpuuo.html

C#:   list.GetRange(1, 3);
来源：http://dali.ydzc1.top/Article/details/gtugwsmqis.html

[D08] 合并两个数组
来源：http://dali.0kj1m.cn/Article/details/gtlkqrcfru.html

Py:   a + b;  a.extend(b)
来源：http://dali.hnxiangtu.top/Article/details/gtdivkdirn.html

PHP:  array_merge($a, $b);
来源：http://dali.ybcxt.top/Article/details/gtijjtspqh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.svipenyu.cn/Article/details/gtccxsmnzl.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtiumablhn.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ybcxt.top/Article/details/gtxldblqrp.html

Go:   append(a, b...)
来源：http://dali.havefunace.top/Article/details/gtflgvknqj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgsmlnvi.html

C#:   a.Concat(b).ToList()
来源：http://dali.cqqwz.cn/Article/details/gtkvcgqvxx.html

[D09] 排序（升序）
来源：http://dali.jianghu66.top/Article/details/gtukjwabzj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigufen.top/Article/details/gtbdpcajht.html

PHP:  sort($arr);
来源：http://dali.yuxming.cn/Article/details/gtcujdhnap.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gthnjynczq.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zhixingplan.top/Article/details/gtrekgxxsk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtuzvfhmkw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yueranfly.top/Article/details/gtotdrwbtx.html

Ruby: arr.sort
来源：http://dali.xuetiantiany.cn/Article/details/gtkzfcppay.html

C#:   list.Sort();
来源：http://dali.havefunace.top/Article/details/gtezjyroqe.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtvvkszazu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavmmlscr.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtbrmrctww.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhongyouzk.top/Article/details/gtkzgespcc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xziqi.cn/Article/details/gtqwdivtzg.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.sufxvd.cn/Article/details/gtbmhcqqlu.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhtpncht.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.quarkkingdee.top/Article/details/gtijtkhpoc.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.aibaodan.cn/Article/details/gtfeiiruom.html

[D11] 反转数组
来源：http://dali.yueranfly.top/Article/details/gtfnnoqewk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ehwqpu.com/Article/details/gttrczuwbo.html

PHP:  array_reverse($arr);
来源：http://dali.yueranfly.top/Article/details/gtueebgcam.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.shuidangran.top/Article/details/gtheczdzhy.html

TS:   [...arr].reverse();
来源：http://dali.kuanghao11.cn/Article/details/gtonjpiely.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdfrjzjm.html

Go:   slices.Reverse(arr)
来源：http://dali.hywenlv.cn/Article/details/gtzkzabslr.html

Ruby: arr.reverse
来源：http://dali.zhengqikj.top/Article/details/gthhfgsitv.html

C#:   list.Reverse();
来源：http://dali.sufxvd.cn/Article/details/gtgfpyrwww.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gttxzliwhp.html

Py:   arr.index(x);  x in arr
来源：http://dali.ydzc1.top/Article/details/gtwqlefuix.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.hnqzz.top/Article/details/gtptieddyl.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pycfn.com/Article/details/gteqohykdy.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.hysaishi.cn/Article/details/gtraqhmhax.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.ppjwa.cn/Article/details/gttxebhjaw.html

Go:   slices.Index(arr, x)
来源：http://dali.shuidangran.top/Article/details/gtnijtghsy.html

Ruby: arr.index(x)
来源：http://dali.mhx1999.top/Article/details/gtorameaup.html

C#:   list.IndexOf(x);
来源：http://dali.wangdashe.top/Article/details/gtllugaevu.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhiwuduotai.top/Article/details/gtfjibhldv.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.iojbl.cn/Article/details/gtzhzcvjht.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.chenzaomai.com/Article/details/gtnztcjfnb.html

JS:   arr.filter(x => x > 3)
来源：http://dali.cashguo.top/Article/details/gthcxnxbjd.html

TS:   arr.filter(x => x > 3)
来源：http://dali.jyoumei.cn/Article/details/gtyqvqxvnd.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtzfuyfqgu.html


<!-- 参考信息 -->