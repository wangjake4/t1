代发 wailian999

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtyejdtosp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtydhmznlp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtlhfdycrm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtnyedmhso.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtiukigetz.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtgkhonsnf.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtyawjhuxr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtcmuttmla.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtnapkphrr.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtbfmmmnfg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtctawwsub.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yueranfly.top/Article/details/gtkluazusp.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtxxfhmyws.html

[B14] 判断值是否在集合内
来源：http://dali.sxryk.cn/Article/details/gtctujieio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gttmhntmjr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gtnpdumvau.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.c1oappe.top/Article/details/gtylddbkgt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtgxhhlcxq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtgcaeyppn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.iojbl.cn/Article/details/gtcddtpfcr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtpcvpnetx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtjqmmlytc.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtecieyxjl.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gtlahnaloy.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtpvzdzndy.html

JS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtkrxztbmi.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gttxzlpnaj.html

Java: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtudvuuete.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtpzulsdvx.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtcuuomxkg.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnrqrsec.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.meibo888.top/Article/details/gtihmlssbb.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtryuupzky.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtfyhejjfc.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtyplrgokv.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtusariblu.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtuijlmkhk.html

Go:   if data == nil { return }
来源：http://dali.jianghu66.top/Article/details/gtfiknadow.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gtkzovzxqq.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtfehqmqvi.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gttpjfnlss.html

C. 函数与作用域
来源：http://dali.zycfv.cn/Article/details/gtahrwwevb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtnnhciylq.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtvnsycbis.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtgsizvapu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtkrdbckcd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvpgimejv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtposegnbx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtxvepjqtm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gthqolltre.html

Ruby: def add(a, b); a + b; end
来源：http://dali.316326.xyz/Article/details/gtvxejdraq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtcvwlsttd.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gthkwmtlbu.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gttyeybfav.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ehwqpu.com/Article/details/gtwegbtleo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtombvkbic.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrroovaif.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtwepifxxn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcvakcwly.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtjkrfrtqs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtsgynrhzr.html

[C03] 可变参数
来源：http://dali.jqgufenzy.top/Article/details/gtzpeuksnk.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtprpxmsyf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdqidasg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgpicurz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gtrakbsqnm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtwyznxmoe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gthcjdezjj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtsltpryxg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gtbwauthhn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gtkbhjjlfu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xinyue.icu/Article/details/gtafrhfuic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhhjrguy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gtcpiztzjp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtraolqmlt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtucfeqkyk.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtitjzwlzn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gterrgmcty.html

C#:   f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtirushfek.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtervmjrwm.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtmqicglux.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gttouwzzbx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtswgdwvha.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtjnpcbmny.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtwqpflshx.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtbdjxyjkb.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtpgmyrgzx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gthexxrzhv.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtamanuzbj.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtluyqczcu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtjmvhyezz.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtphpynewm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ehwqpu.com/Article/details/gttzypvknt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yj20258.top/Article/details/gtnvldwwiw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.haohaochexian.top/Article/details/gtnmvldygu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtiubfbich.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtdqmaclxq.html

[C07] 把函数作为参数传入
来源：http://dali.birdmap.top/Article/details/gteaihleah.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.aizwys.cn/Article/details/gtjvaqwuqo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cashguo.top/Article/details/gtokfawkmy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cdnleiting.top/Article/details/gtesewivyc.html

TS:   arr.map(String)
来源：http://dali.yonumen.top/Article/details/gtofcrkjwu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtcooqgyrq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ehwqpu.com/Article/details/gtgcuqmjee.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtbpcdulmi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtibjycnct.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtocuzfzqv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtbtuhkuci.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.andypj.xyz/Article/details/gtzaovuvic.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtgwhimdge.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtzihvppgw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuxming.cn/Article/details/gtlsvclspr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ppjwa.cn/Article/details/gtijsexgfu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtsvfunqmi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtynufzcbt.html

[C09] 递归
来源：http://dali.havefunace.top/Article/details/gtticsuzey.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvrvpoeia.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcifmootr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtocjvzvcf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tian-w.cn/Article/details/gtbzhpopzb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtuuhorkuz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gtncvnbbvd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtrtbrohaq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtkisbhhat.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqtvnioc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gogol.net.cn/Article/details/gtbdkktmmh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.haohaochexian.top/Article/details/gtosigmfzs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtjoludasd.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtzkvzutww.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gtmkcgbhqk.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtvtjjozxh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gtstkloplr.html

C#:   块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmvjvsqvd.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtncjkpgbr.html

Py:   from module import func
来源：http://dali.316326.xyz/Article/details/gtkpxkzivj.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthokvnqbr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtypjmmiei.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.haohaochexian.top/Article/details/gthlusmxpn.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtscallrwm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjvsuxjha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.pengpengdd.cyou/Article/details/gtefphebpy.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gtfcpxfhye.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtruwkwvvj.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtgehynyzj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhoulong.xyz/Article/details/gtmctmvqgc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkadadjjc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtcwgsbnlh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gtkynuhflr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtaqguyjqb.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuanzx.com/Article/details/gtsetrrhlv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenlongwang.top/Article/details/gtzfmedxsz.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gtttibvzqk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gzhubu.top/Article/details/gtruhzenvo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtcyolziwb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sysykeji.top/Article/details/gtsuaqvbqv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtgbzuhuxi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtvdakmedj.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtedthainn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtrxeyekbx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gtoycbzfgx.html

[C14] 泛型函数
来源：http://dali.yuxming.cn/Article/details/gtzdkrdyxj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yanxiufei.cn/Article/details/gtjoeufczr.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtbhrxjcft.html

JS:   // 无泛型
来源：http://dali.hammf.cn/Article/details/gtkqociukf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhengqikj.top/Article/details/gtudnonmdc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gteebobhot.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gttoriyqbn.html

Ruby: # 无泛型
来源：http://dali.fengsongda.top/Article/details/gthqvodade.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtgyksdcng.html

[C15] 解构 / 展开参数
来源：http://dali.chenjidiqi.icu/Article/details/gtwfwymeez.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gtpmiomfxo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.wangshuangyany.cn/Article/details/gtynwlktpo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gtwttpbivd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtrrmiarid.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtvtnreuhz.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gtsnvwhmsu.html

Ruby: a, b = pair
来源：http://dali.ehwqpu.com/Article/details/gtehlsemdt.html

C#:   var (a, b) = pair;
来源：http://dali.nwbrower.top/Article/details/gtcawoaevk.html

[C16] 函数 / 方法重载
来源：http://dali.zhongyouzk.top/Article/details/gtxoxzztnj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gtzppxxwak.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gthwchmwdv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtojqsaeqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtodtcisky.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.chenlongwang.top/Article/details/gtbxhvvjqe.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnqzz.top/Article/details/gtjbytjidu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtzmwshaie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gotoacloud.top/Article/details/gtpgwrhrkq.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtkttfqvgg.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxuanxn.top/Article/details/gtednhglte.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgyduyhqu.html

[D01] 创建数组 / 列表
来源：http://dali.dashuyun.cn/Article/details/gtuucxwepr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gtengzaqny.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtsxlykfek.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtzlreyxvb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenjidiqi.icu/Article/details/gtqctmlmuh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gtekimjsfm.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenlongwang.top/Article/details/gtbfpsqisu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yongpay.top/Article/details/gtbtjxmdbp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yanxiufei.cn/Article/details/gtiajfxkcf.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtzosrroix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtwltuorvy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jyoumei.cn/Article/details/gttflxgdev.html

JS:   arr.push(4);
来源：http://dali.tian-w.cn/Article/details/gtvehjnupz.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtcpsypccu.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtpaurwngo.html

Go:   arr = append(arr, 4)
来源：http://dali.kuanghao11.cn/Article/details/gtnqwrtqni.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtbperuhjz.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtaoppcdza.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gthgcctlom.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtwbuhfhlr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jianghu66.top/Article/details/gtclntwcqh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.iojbl.cn/Article/details/gtvrfgudds.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.c1oappe.top/Article/details/gtmnshoytz.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtrtujttnm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.quarkkingdee.top/Article/details/gtewbgpzho.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuanzhike.top/Article/details/gttqvaiipr.html

C#:   list.Insert(0, 0);
来源：http://dali.jianghu66.top/Article/details/gtgbvfdfdi.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtgodsjcsp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.dianchejie.cn/Article/details/gtkygwhzph.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gogol.net.cn/Article/details/gtshcjlzrd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gthwoijhwe.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gteqbbwgai.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyyhhmyip.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sxryk.cn/Article/details/gtycnqmchv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gtnyfmpogp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dianchejie.cn/Article/details/gtecjkrcpp.html

[D05] 访问与修改元素
来源：http://dali.yvedp.cn/Article/details/gtgtllwmae.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtprspxsie.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtpveeukhy.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtelltoswk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.vqdsnc.cn/Article/details/gtimfvunla.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtafydxylg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtwckwhwaq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtaxwssquq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtopyqxnze.html

[D06] 数组长度
来源：http://dali.ehwqpu.com/Article/details/gtwmeklcsg.html

Py:   len(arr)
来源：http://dali.yuanzhike.top/Article/details/gthhjudzdo.html

PHP:  count($arr);
来源：http://dali.shzxlz.cn/Article/details/gtkzxdvbms.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtwznxokex.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtfdmysgdc.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtfkynuzsj.html

Go:   len(arr)
来源：http://dali.xylfe.cn/Article/details/gtbhtfiapd.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtdbvwjtnj.html

C#:   list.Count;
来源：http://dali.chenjidiqi.icu/Article/details/gtrwvtcyhe.html

[D07] 切片 / 取子数组
来源：http://dali.yuanzhike.top/Article/details/gtaxjftwlz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gtocgbcsle.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtjzsdfgkh.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtrkxfqexs.html

TS:   arr.slice(1, 4);
来源：http://dali.ybcxt.top/Article/details/gtkjdrqvil.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtwlvceyha.html

Go:   arr[1:4]
来源：http://dali.0kj1m.cn/Article/details/gtlgklxsqc.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gthqylxwuz.html

C#:   list.GetRange(1, 3);
来源：http://dali.jyoumei.cn/Article/details/gtzdsdacnf.html

[D08] 合并两个数组
来源：http://dali.daxiang520.top/Article/details/gteytwtsvt.html

Py:   a + b;  a.extend(b)
来源：http://dali.jyoumei.cn/Article/details/gtnpishnjk.html

PHP:  array_merge($a, $b);
来源：http://dali.svipenyu.cn/Article/details/gtyvzcelvc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenjidiqi.icu/Article/details/gtzfldfttq.html

TS:   [...a, ...b];
来源：http://dali.ppjwa.cn/Article/details/gtuxqitfyx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtmizvidkw.html

Go:   append(a, b...)
来源：http://dali.nanxinkj.top/Article/details/gtjvzzaygx.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtejjgxupr.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwqsmeyl.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtyqyaznfp.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.vqdsnc.cn/Article/details/gtvgsiyoub.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtowrzocgu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gtlxtnlulh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.bjfxy.top/Article/details/gtgvyxavlp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtgsnpchhb.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtnkokhwpl.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtusvsckem.html

C#:   list.Sort();
来源：http://dali.pycfn.com/Article/details/gtqhqryqlx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.yj20258888.top/Article/details/gtecbydcqc.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jqgfzy.top/Article/details/gtfwadsazd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtlrmkwcgb.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.meibo888.top/Article/details/gtjnhpkcaw.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.tian-w.cn/Article/details/gtihvtaaih.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.iojbl.cn/Article/details/gtprfrlexq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gtagkyvwyd.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hfpthk.cn/Article/details/gtinsinkxf.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtoowfkgxx.html

[D11] 反转数组
来源：http://dali.kuanghao11.cn/Article/details/gtqwiulpyy.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnlgwpme.html

PHP:  array_reverse($arr);
来源：http://dali.daxiang520.top/Article/details/gtpgeritsm.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.hongshengwenyu.top/Article/details/gtepckcrge.html

TS:   [...arr].reverse();
来源：http://dali.sxryk.cn/Article/details/gtomcqpvyh.html

Java: Collections.reverse(list);
来源：http://dali.feifeiyinyue.top/Article/details/gtybgxfere.html

Go:   slices.Reverse(arr)
来源：http://dali.yuxming.cn/Article/details/gtcfosxnzq.html

Ruby: arr.reverse
来源：http://dali.gotoacloud.top/Article/details/gtpmmamurv.html

C#:   list.Reverse();
来源：http://dali.zycfv.cn/Article/details/gtenhacubj.html

[D12] 查找元素下标
来源：http://dali.jiagoushi.top/Article/details/gtzffcjqtp.html

Py:   arr.index(x);  x in arr
来源：http://dali.jinqigfzy.top/Article/details/gtfictaobn.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtkbbvwewg.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpmewfvij.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.yangfankeji.com/Article/details/gtujbdrgxi.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.meibo888.top/Article/details/gtjbatfijt.html

Go:   slices.Index(arr, x)
来源：http://dali.sufxvd.cn/Article/details/gtwogrigkj.html

Ruby: arr.index(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtihqtsyvc.html

C#:   list.IndexOf(x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllroxysz.html

[D13] 过滤（保留满足条件的）
来源：http://dali.chenzaomai.com/Article/details/gtznfojtpj.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdbqsflyx.html


<!-- 参考信息 -->