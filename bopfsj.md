代发 wailian999

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtqdpwzfrg.html

Py:   isinstance(x, (int, float))
来源：http://dali.shanyushiyangtech.top/Article/details/gtomlokrbn.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtchfouowk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtmcayxwmx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtsecoeeep.html

Java: x instanceof Number
来源：http://dali.jlsjyb.cn/Article/details/gtbqxyockr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gtltblcnqb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtqppkdpen.html

C#:   x is int or double or decimal
来源：http://dali.fengsongda.top/Article/details/gtgojsdwao.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gtvheskrwn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtwgowpjhn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tanke756.top/Article/details/gtcyxfmnuy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtaabuzxli.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtjrnvjobc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gzhubu.top/Article/details/gtdjfwcvld.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sufxvd.cn/Article/details/gtrvghmysa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtfhaajtbx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtjyjnxoeo.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtzxrkpftb.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtdofskyws.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gteewrzcba.html

JS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtmretbdam.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrbcfigf.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtfajhgikh.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtmknhpgtg.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmlsixfg.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtmckdpcmw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtkpstapcq.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtipvbvrbd.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkyrdritk.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtawrnernb.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtgpiakbll.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gttnukopjp.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtppdogsrs.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtppcnwepr.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtsrxjollf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjvptfaks.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtymetafcq.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtljxrabfo.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtoqilysgk.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtdxsfdrve.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtqwgszegh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtagrskaph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtveqwefmi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtlhtrzhnb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jiagoushi.top/Article/details/gtgqsmyjcy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhixingplan.top/Article/details/gtjjlmayyo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtgtewzuvi.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtakxifcsh.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtxdceoikn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtslnzwpvr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtwcgaxgql.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gtlcizgcnt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtqqxsbnrv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gtacnzihax.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtywdbvhil.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtmgvbqvtt.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtqxkoopxb.html

Py:   def total(*args): return sum(args)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfnjiymb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jyoumei.cn/Article/details/gtlrjpmmbr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtgptpvrae.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gtjnjpoxaf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtiysvuhev.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtpsbogbio.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtzmnnwxei.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.316326.xyz/Article/details/gtxzmgtzel.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtposearej.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sufxvd.cn/Article/details/gtwruhdpdw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtdnemvpzp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtkxhdvimt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjbtoloh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtsgigqzjf.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gttichpgnk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtkrotfmxc.html

C#:   f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtcgnvbyxi.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gthehnjbxh.html

Py:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtmzbjqcpo.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtasmauozu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtneqspanv.html

TS:   return { a, b };
来源：http://dali.fzhhl.top/Article/details/gtnnqhcyrh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gttmkzdowl.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gttakcaksl.html

Ruby: return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqdxjaho.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtzcsybovb.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gttcmuylcu.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtxputmski.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.0kj1m.cn/Article/details/gtjxhnczxx.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gthzhoumhp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gttgvbnrcm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxinkj.top/Article/details/gtvekkkkze.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gttxkuugpx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjwnekak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtmtzwsrzm.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtgvixxaip.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shuidangran.top/Article/details/gtrahunnco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtqxtdjdxw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cashguo.top/Article/details/gttnxreyrg.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtavtodcxw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtkctxbnpz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtnxplinyr.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gtjzpmsvuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtubzbnckh.html

[C08] 闭包
来源：http://dali.jianghu66.top/Article/details/gtsbktqiqo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gturqpcfog.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gthswbiogr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtadgqnioi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtnmerfnuz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.c1oappe.top/Article/details/gtsjsvxewf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnqzz.top/Article/details/gtfdikopnw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gtnpmukvqy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtvikzceza.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gtjdcscyzb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtnipltria.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtsvgwedik.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtevczvoqs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtuarrhbgj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gtzlgadcaz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhoulong.xyz/Article/details/gtbrnritaf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtzafpbvgg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtlevppeey.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtznvdkxab.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yvedp.cn/Article/details/gtvyfgovmm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gtlyslmvme.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtxpyjnxbg.html

TS:   同 JS
来源：http://dali.zycfv.cn/Article/details/gtpekpqerm.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtarvunwhy.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtnhslvcdt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gthcqayilg.html

C#:   块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gttprnijxp.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gthvvieckt.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtcuiuecgw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtakjdoynr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gtpepccxzp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jianghu66.top/Article/details/gtsgqtilhd.html

Java: import java.util.List;
来源：http://dali.zycfv.cn/Article/details/gttonhrbip.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.andypj.xyz/Article/details/gtfafhuihi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtcycotgsm.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gtmtrrwlvf.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtcdawvycx.html

Py:   (lambda: print("run"))()
来源：http://dali.havefunace.top/Article/details/gtfiwnooxo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtmsbiankh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gthazgvasy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtwohrjkmi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtyvqbhmdd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.wangdashe.top/Article/details/gtukgyovcz.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenlongwang.top/Article/details/gtoqeilzun.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gtgrdvadpb.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gtwvpmvnyn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwjkefht.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtvphwxqpg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtneylunec.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtfwyiflqb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtuhgavphv.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gthbhvmsqt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gtbozqccvy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtoccfhxpz.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtcjqwlvjr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigufen.top/Article/details/gtusrtfcqv.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqgaqhtqb.html

JS:   // 无泛型
来源：http://dali.sweek.top/Article/details/gtrwkgmhme.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gtceudamls.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenzaomai.com/Article/details/gtoftuvwjx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nwbrower.top/Article/details/gtiruszjae.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtzmmrkbkt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fzhhl.top/Article/details/gtttbpluew.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gtjjrzqsqz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shzxlz.cn/Article/details/gtymcbajsa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gtqouuffuk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gtwsbfryta.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtwdbistxy.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtzajkwxhq.html

Go:   // 无解构
来源：http://dali.zhoulong.xyz/Article/details/gtatdeolwd.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtanoaaukh.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gtgsgzmpmx.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtqpbpdchx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtyqsrwdpp.html

PHP:  // 无重载
来源：http://dali.shangyingyoupin.top/Article/details/gtokvgflft.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtwpukbfgq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtubbytcwr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtsuzmxnwe.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinqigfzy.top/Article/details/gtbiffridt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtolatmjhv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gtorzyqsci.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtqnsdmuph.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtfvdyzqil.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyovbplfm.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gthuzggsnk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.redwolf501.top/Article/details/gtabytqtbs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yongpay.top/Article/details/gtwaedomur.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtokzpacqb.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtrkyvahxu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daria6918.cn/Article/details/gtgqqouabq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gtjslfvykp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtoxsghoxa.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtzflbkptv.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtmoyhcguo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhoulong.xyz/Article/details/gtltdtuiah.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aizwys.cn/Article/details/gtwpqcvvor.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtvzuvmsor.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtpupnlpri.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtpvwyfveo.html

Go:   arr = append(arr, 4)
来源：http://dali.tian-w.cn/Article/details/gtvtuuzyfq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zdqjudy.top/Article/details/gtzecqvmsd.html

C#:   list.Add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtcjfjvsjq.html

[D03] 在指定位置插入元素
来源：http://dali.yvedp.cn/Article/details/gtcxuxidfy.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtrzoeamra.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ivvv.top/Article/details/gtrcaazdqd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yanxiufei.cn/Article/details/gtrjatufoy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yuxming.cn/Article/details/gtqaqlwelo.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtlwcbvqfp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.vqdsnc.cn/Article/details/gtiyzrsktw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hammf.cn/Article/details/gtplexewyg.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtsrjebtmu.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gtrohvgyya.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtrrxypdvi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtdfcqrvpq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtftnczrhg.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnxqjoqh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gotoacloud.top/Article/details/gtevqtsxie.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gtqsdkbdku.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daria6918.cn/Article/details/gtnemamkas.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtgcmoropl.html

[D05] 访问与修改元素
来源：http://dali.birdmap.top/Article/details/gtxczfxpqq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtghbsvesw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtajygmbex.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtnhflowag.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ybcxt.top/Article/details/gthzaoxpcx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gtougzxcgn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtincjwdei.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtrinisubz.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtpxegtevz.html

[D06] 数组长度
来源：http://dali.feifeiyinyue.top/Article/details/gtjctbvsqv.html

Py:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtfuwoknbb.html

PHP:  count($arr);
来源：http://dali.hongshengwenyu.top/Article/details/gtfpuwejbg.html

JS:   arr.length
来源：http://dali.xziqi.cn/Article/details/gtrmglsdgw.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtzpvvggtu.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtvplnpnii.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtntyrcwec.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gtglikllbm.html

C#:   list.Count;
来源：http://dali.ehwqpu.com/Article/details/gtroaxbuqm.html

[D07] 切片 / 取子数组
来源：http://dali.havefunace.top/Article/details/gthginomus.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.redwolf501.top/Article/details/gtpllnedyx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.xylfe.cn/Article/details/gteggbffcf.html

JS:   arr.slice(1, 4);
来源：http://dali.xylfe.cn/Article/details/gtkixafucd.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtreunqvxv.html

Java: list.subList(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtbddcqtpv.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gthsardqgv.html

Ruby: arr[1, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtlphctjpr.html

C#:   list.GetRange(1, 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtczvficzf.html

[D08] 合并两个数组
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnttmaad.html

Py:   a + b;  a.extend(b)
来源：http://dali.xinyue.icu/Article/details/gtdmikqhmt.html

PHP:  array_merge($a, $b);
来源：http://dali.meibo888.top/Article/details/gtbvnvgbmb.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yangfankeji.com/Article/details/gtmtjhtyes.html

TS:   [...a, ...b];
来源：http://dali.havefunace.top/Article/details/gtglbboodd.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.hnxiangtu.top/Article/details/gtfwnfinbm.html

Go:   append(a, b...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmamgnsoa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gthmscrqbu.html

C#:   a.Concat(b).ToList()
来源：http://dali.snrcjt.cn/Article/details/gtxhfrpwvy.html

[D09] 排序（升序）
来源：http://dali.vqdsnc.cn/Article/details/gtjvihedfa.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hfpthk.cn/Article/details/gtmivxuhzk.html

PHP:  sort($arr);
来源：http://dali.tanke756.top/Article/details/gtxffxlymj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhongyouzk.top/Article/details/gtjfzfsnhe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxrghfhlk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtwlkzypyk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yanxiufei.cn/Article/details/gticcdvdps.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtybivpohr.html

C#:   list.Sort();
来源：http://dali.snrcjt.cn/Article/details/gtuchvyfti.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtprgcvrku.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gtukfdgmxh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtsdomndff.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gttngjfvhh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhengqikj.top/Article/details/gtmdwlmoip.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.shuidangran.top/Article/details/gtkodpxirb.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.nanxinkj.top/Article/details/gtrlgqoize.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.kuanghao11.cn/Article/details/gtkecrkthz.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkzjajsxf.html

[D11] 反转数组
来源：http://dali.vqdsnc.cn/Article/details/gtcsqgrvvu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.yonumen.top/Article/details/gtdepqkxau.html

PHP:  array_reverse($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gteizougsu.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhiwuduotai.top/Article/details/gtcadvhqhs.html

TS:   [...arr].reverse();
来源：http://dali.zycfv.cn/Article/details/gtvxrancrv.html

Java: Collections.reverse(list);
来源：http://dali.tanke756.top/Article/details/gtyjkroxkc.html

Go:   slices.Reverse(arr)
来源：http://dali.fzhhl.top/Article/details/gtkwhdeila.html

Ruby: arr.reverse
来源：http://dali.feifeiyinyue.top/Article/details/gtabxixwxs.html

C#:   list.Reverse();
来源：http://dali.9152youxi.cn/Article/details/gtdieuskaa.html

[D12] 查找元素下标
来源：http://dali.redwolf501.top/Article/details/gtsdjxnsgn.html

Py:   arr.index(x);  x in arr
来源：http://dali.316326.xyz/Article/details/gtrxzwzsfb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.fzhhl.top/Article/details/gtorwrzdgv.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.dashuyun.cn/Article/details/gtzrkakrhf.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.feifeiyinyue.top/Article/details/gtlibwsqjl.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.xuanzx.com/Article/details/gtsgsaokrr.html

Go:   slices.Index(arr, x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxfxcutj.html

Ruby: arr.index(x)
来源：http://dali.tianlin.xyz/Article/details/gtxoldcfnm.html

C#:   list.IndexOf(x);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqpcsdqp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.zhoulong.xyz/Article/details/gtrzhmokra.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.sufxvd.cn/Article/details/gtefjwhbrm.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.svipenyu.cn/Article/details/gtcmldjsyy.html

JS:   arr.filter(x => x > 3)
来源：http://dali.gotoacloud.top/Article/details/gtjbbdbshh.html

TS:   arr.filter(x => x > 3)
来源：http://dali.xziqi.cn/Article/details/gtkvahriiv.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtqbdgkejs.html


<!-- 参考信息 -->