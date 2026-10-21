代发 wailian999

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjxxnvji.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtihdgmeam.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gtlybjicwf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtfcjlcejo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtpfaeskix.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtslpdpzsy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.haohaochexian.top/Article/details/gtyusytthn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nwbrower.top/Article/details/gtsroippip.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtkdibspoi.html

[B14] 判断值是否在集合内
来源：http://dali.pycfn.com/Article/details/gtmxlxbomz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gtdyheqpbj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gtcxjoovum.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtzhffxfjs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtohlgscbc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gthrejjqhr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangtech.top/Article/details/gthqidsgfl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtquxqtyph.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.meibo888.top/Article/details/gtuimarxui.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gtgkhmfadb.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gtyoqyzqmr.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtgestmiei.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtqqruwwij.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtjmwrhdxt.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtxdqklknk.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsexbicnp.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtqcnggikj.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtkoehiyxw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hnqzz.top/Article/details/gtwocnqnem.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtgupnauwl.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtjnicffdw.html

JS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtjrhjpvur.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtvqncusnp.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtfysmpahf.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtjidxjggd.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtjfknjywn.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtrbplsxbv.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtsjvwqaqh.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtmifyitxb.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtszniyhof.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtucwsjzxa.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtrdzpdvhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtfnhmkvqa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtcfncnakd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtfadbwuva.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtmztlowcr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtricinyyj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtgqwbaohf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtvceoolyc.html

[C02] 默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtokkkoccc.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gthpduzqhw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gthvbxkfdm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtbkfkcloa.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtskmmwoeh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gtbszpjmmd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtzfwmcqsm.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxinkj.top/Article/details/gtwmzbcldv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gthbkvspho.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtczehjzpy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtzyokrwkf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gtrakbnwlk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gtyyudbjuw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtmrifahzh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhongyouzk.top/Article/details/gtthwvjzqu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtzktcpoud.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtfdcfrtnw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtncxuypuo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sufxvd.cn/Article/details/gtgnevggrb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gtylwhcvyu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jianghu66.top/Article/details/gtiaftyarm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtnhlmigfj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtybqwepkh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkygyhyz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiokvfudr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxracwbiv.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtiaeijteg.html

[C05] 返回多个值
来源：http://dali.shuidangran.top/Article/details/gtmvwvhkax.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtcdhrjgvq.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gteylgdcpk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xinyue.icu/Article/details/gtxiwmkdkc.html

TS:   return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtpznuyjhy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.svipenyu.cn/Article/details/gtevzhoith.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtnyowjqzt.html

Ruby: return a, b
来源：http://dali.jianghu66.top/Article/details/gtomeoraqi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtszxlivsw.html

[C06] 匿名函数 / lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtlzruhkxb.html

Py:   square = lambda x: x * x
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqozmfwb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.9152youxi.cn/Article/details/gtmyuknmyn.html

JS:   const square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtoepimfyz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yongpay.top/Article/details/gtckfopuyo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gtkouzjsgn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gthvbgetye.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hysaishi.cn/Article/details/gtljzezppv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxinkj.top/Article/details/gtgloejjxs.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtjfnjybww.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gthfhliqpi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aizwys.cn/Article/details/gteslrbdzv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gtpkpgaqms.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtohwzbttw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtkmplggjb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtyyohwsba.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtprrimkxv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtzqqulqnt.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtjxvhqtkn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gtnnxrbjou.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.tianlin.xyz/Article/details/gtxqkdmehp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtnqsnogjv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtkgkvzopl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtirkxjxhy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gtxljdkivf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sweek.top/Article/details/gtintliijj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtsuasbngc.html

[C09] 递归
来源：http://dali.dianchejie.cn/Article/details/gtzdtnpkko.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtzuamyswh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtqwtlxxpn.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtuhgqcbzn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtdtbocjvl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guowangkeji.top/Article/details/gtnozldsht.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtpknmadsd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtaezwucqq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gthzhvfyen.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtxftftpxi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtxylalygi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gtgyakbcuq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sysykeji.top/Article/details/gtstfcxlnj.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtxehlfdds.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtpolvftir.html

Go:   花括号块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtbbkgzqim.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gtlraeqmqu.html

C#:   块级作用域
来源：http://dali.jianghu66.top/Article/details/gtxstdukfg.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtgoisbbgv.html

Py:   from module import func
来源：http://dali.daxiang520.top/Article/details/gtyjmqaohs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtvlqegizr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtztkgonll.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fzhhl.top/Article/details/gtuhxzqgdp.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gtklbrwqjx.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtoxcsoqpf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtdsmbkuxy.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtwolkfgbn.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtzepswbsi.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gtajviuugc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.daria6918.cn/Article/details/gtsorrvekl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtnimqbbxl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtasyyuciw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtdyogxrqs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtsaxburuf.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtcqkupjtl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtazcutlnr.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtwsuieoho.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sysykeji.top/Article/details/gtocuhuoji.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtuunasbps.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtundlmtji.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtwbvtgeqe.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtubnfntqm.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtpluylnzn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbcwsktc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgufenzy.top/Article/details/gtxgshndlk.html

[C14] 泛型函数
来源：http://dali.meibo888.top/Article/details/gtomatsrhy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ydzc1.top/Article/details/gtxnwiborr.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozyutsbr.html

JS:   // 无泛型
来源：http://dali.fengsongda.top/Article/details/gtvfgahkxm.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hfpthk.cn/Article/details/gtnyjkwbnz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxhpvkvg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtkddhabdh.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gttlzpjitu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gtbietkwiq.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtxfcnwmva.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gturwzijux.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxuanxn.top/Article/details/gtnbiikdqd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gtbqsexlkb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtgdaekmxb.html

Java: // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtmapvqhzx.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gthfevjyiy.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gttbriyqxt.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtikkvsdby.html

[C16] 函数 / 方法重载
来源：http://dali.tianlin.xyz/Article/details/gtgwhcuiqo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xziqi.cn/Article/details/gthxvyrxzg.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtyqcmcqys.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gtjgalyufs.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtotynljtx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrmceepr.html

Go:   // 无重载：用不同函数名
来源：http://dali.quarkkingdee.top/Article/details/gtdyukxzsr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtfqvgzpmp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gogol.net.cn/Article/details/gtxecjsaun.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtcuihdoab.html

D. 数组 / 列表 / 集合
来源：http://dali.c1oappe.top/Article/details/gtiljcienk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtabrqyhpl.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtvudekexm.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.c1oappe.top/Article/details/gtbtpjdtrf.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.fzhhl.top/Article/details/gtjqcpjzdq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gtfdawkrul.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xuanzx.com/Article/details/gtcdwaqpmq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gtqpvyidqd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtzmezcpnz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtloglcfvk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtswvgkpeu.html

[D02] 追加元素到末尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzetyatp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hywenlv.cn/Article/details/gtmmxjwloq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gtdwfdygms.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtcpbzfsfn.html

TS:   arr.push(4);
来源：http://dali.zhengqikj.top/Article/details/gtmzryokua.html

Java: list.add(4);
来源：http://dali.redwolf501.top/Article/details/gtefnmsjmt.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtdxphzknc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gttlwidxgl.html

C#:   list.Add(4);
来源：http://dali.ydzc1.top/Article/details/gtwpbokzas.html

[D03] 在指定位置插入元素
来源：http://dali.nanxinkj.top/Article/details/gtshuqixfl.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtyzgolamg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdpcwkecd.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtrkaekskw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtoagavoiy.html

Java: list.add(0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtcysbtopg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtwmfnndxv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtammvsceo.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtawnlsfbm.html

[D04] 删除元素
来源：http://dali.pycfn.com/Article/details/gtcxxtssio.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtixytoydl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtnacsyoel.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtvpeficfy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtgvbbwlzu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ydzc1.top/Article/details/gttvfzqisp.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhcqzlnv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hywenlv.cn/Article/details/gtrlammisk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtshvqbtuh.html

[D05] 访问与修改元素
来源：http://dali.feifeiyinyue.top/Article/details/gtklvbteeq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmkkdgurl.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gttbgjxeer.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtvhxognkw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.kuanghao11.cn/Article/details/gtwmztycuc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.havefunace.top/Article/details/gtcyqaqnye.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.hfpthk.cn/Article/details/gtspxljpoi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtmnjozjck.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtinsxfggk.html

[D06] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtwtskorsh.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gtugiqkcmk.html

PHP:  count($arr);
来源：http://dali.hammf.cn/Article/details/gtosqmyfpf.html

JS:   arr.length
来源：http://dali.svipenyu.cn/Article/details/gtzseqbipc.html

TS:   arr.length
来源：http://dali.zycfv.cn/Article/details/gtiztyqrbf.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtlyppptty.html

Go:   len(arr)
来源：http://dali.birdmap.top/Article/details/gtzyocgvbp.html

Ruby: arr.length; arr.size
来源：http://dali.sufxvd.cn/Article/details/gtoxzjlqdy.html

C#:   list.Count;
来源：http://dali.yj202588.top/Article/details/gtzwardcmu.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtjrfpsxte.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gthbmbqzgw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.fengsongda.top/Article/details/gtuqsakuum.html

JS:   arr.slice(1, 4);
来源：http://dali.yanxiufei.cn/Article/details/gtiwjzjpnu.html

TS:   arr.slice(1, 4);
来源：http://dali.guannengcc.top/Article/details/gtxfbhzjyg.html

Java: list.subList(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gtmkmrczyb.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtmqrlrxky.html

Ruby: arr[1, 3]
来源：http://dali.mhx1999.top/Article/details/gtyooqxpdu.html

C#:   list.GetRange(1, 3);
来源：http://dali.hywenlv.cn/Article/details/gtsgyyqowv.html

[D08] 合并两个数组
来源：http://dali.zhongyouzk.top/Article/details/gtmamozute.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtppjmrbnm.html

PHP:  array_merge($a, $b);
来源：http://dali.aizwys.cn/Article/details/gtviwqdfpy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtiaczrypj.html

TS:   [...a, ...b];
来源：http://dali.9152youxi.cn/Article/details/gtpumfgofc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.daria6918.cn/Article/details/gttjgajrma.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gthkenpfqz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hywenlv.cn/Article/details/gtjlqyhbfk.html

C#:   a.Concat(b).ToList()
来源：http://dali.cdnleiting.top/Article/details/gthmkymxyl.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gthujaothz.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sweek.top/Article/details/gtjmykgvaz.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbehuqqss.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtncjngiwp.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.dashuyun.cn/Article/details/gtnasuuxlu.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.xinyue.icu/Article/details/gtmxrituzi.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dashuyun.cn/Article/details/gtmxcqggej.html

Ruby: arr.sort
来源：http://dali.jinghuilouyu.cn/Article/details/gtyrqcflob.html

C#:   list.Sort();
来源：http://dali.jinghuilouyu.cn/Article/details/gtabshukpp.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqybwijzt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yanxiufei.cn/Article/details/gtqoxyzqdc.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jianghu66.top/Article/details/gtmvrwvgrt.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gttmkwnndl.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtlwnkwukt.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.tian-w.cn/Article/details/gtzdxmklvp.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.chenjidiqi.icu/Article/details/gthuybwrzq.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.hammf.cn/Article/details/gtwonhleea.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.sweek.top/Article/details/gtufhktwtt.html

[D11] 反转数组
来源：http://dali.guowangkeji.top/Article/details/gtztkzzjjk.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.aizwys.cn/Article/details/gtrdzoyitr.html

PHP:  array_reverse($arr);
来源：http://dali.ydzc1.top/Article/details/gtbwiieltk.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.chenzaomai.com/Article/details/gtttdtjrbv.html

TS:   [...arr].reverse();
来源：http://dali.havefunace.top/Article/details/gtftobiane.html

Java: Collections.reverse(list);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtzhoupj.html

Go:   slices.Reverse(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtoqtcfamj.html

Ruby: arr.reverse
来源：http://dali.gaohongyu789.top/Article/details/gtxajlcdxm.html

C#:   list.Reverse();
来源：http://dali.tianlin.xyz/Article/details/gtydzflshs.html

[D12] 查找元素下标
来源：http://dali.shangyingyoupin.top/Article/details/gtemzmqxrb.html

Py:   arr.index(x);  x in arr
来源：http://dali.fzhhl.top/Article/details/gtsalufajb.html

PHP:  array_search($x, $arr);  in_array($x, $arr);
来源：http://dali.kuanghao11.cn/Article/details/gtwcwqehbf.html

JS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.ydzc1.top/Article/details/gtrvopedgr.html

TS:   arr.indexOf(x);  arr.findIndex(v => v > 3)
来源：http://dali.shangyingyoupin.top/Article/details/gtlljdhoce.html

Java: list.indexOf(x);  IntStream.range(0, list.size()).filter(i -> list.get(i) > 3).findFirst()
来源：http://dali.sysykeji.top/Article/details/gtnxwyclnv.html

Go:   slices.Index(arr, x)
来源：http://dali.bjfxy.top/Article/details/gtyypybjek.html

Ruby: arr.index(x)
来源：http://dali.daria6918.cn/Article/details/gthzwwqrne.html

C#:   list.IndexOf(x);
来源：http://dali.chenlongwang.top/Article/details/gtbcbqjtpp.html

[D13] 过滤（保留满足条件的）
来源：http://dali.vqdsnc.cn/Article/details/gtcjuzypdy.html

Py:   [x for x in arr if x > 3];  list(filter(lambda x: x > 3, arr))
来源：http://dali.yonumen.top/Article/details/gthmnhklpa.html

PHP:  array_filter($arr, fn($x) => $x > 3);
来源：http://dali.pengpengdd.cyou/Article/details/gttmzsoash.html

JS:   arr.filter(x => x > 3)
来源：http://dali.zdqjudy.top/Article/details/gtjmsymjox.html

TS:   arr.filter(x => x > 3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohxdswph.html

Java: list.stream().filter(x -> x > 3).toList()
来源：http://dali.ivvv.top/Article/details/gtwzaeobuc.html


<!-- 参考信息 -->