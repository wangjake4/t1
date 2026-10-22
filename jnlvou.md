代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtjtacsdwp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gtfvchihge.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtftljaghg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenlongwang.top/Article/details/gthyabghsa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtkcmspslm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gtbqutepuw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtdarlzust.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtbjenordd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtmdxlsfmc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtxwadlozy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtspnszsrr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwpqsexhm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqgoeigwl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gteujsskux.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ehwqpu.com/Article/details/gtkgriiwbf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.quarkkingdee.top/Article/details/gtimahbvbl.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtnszgtyvd.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gtncnhtedr.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gttzbpilgk.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvdjjgqul.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gttiqevhtk.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtdrrxjctc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtfsmmomww.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtemktwlgt.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtzdfflvis.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gttqzuhjnk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gteiajytjz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.vqdsnc.cn/Article/details/gtqtrvfiic.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtyfftimsx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtdhligenh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtveqndtad.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtbcfljyok.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtujzreplg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yj20258.top/Article/details/gtumkdwrkg.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtxwslkiwm.html

Py:   a and b or not c
来源：http://dali.yj20258.top/Article/details/gtjhqcofft.html

PHP:  $a && $b || !$c
来源：http://dali.quarkkingdee.top/Article/details/gttmyrzbuo.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtqnqbzjpq.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtqebcswvv.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtdcpnaexd.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtiezrpycx.html

Ruby: a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtssbslhlx.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtvmwgdygb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xylfe.cn/Article/details/gtteudnfel.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtbxlknbhd.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtcvfyvirb.html

JS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsusxzvpa.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtydtsxdqa.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtqtspueec.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtflcdwfdc.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtnvnltsmd.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtaarjkyyg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtigeilkxc.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtjjudvcmi.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxyqnsety.html

[C01] 定义函数
来源：http://dali.cashguo.top/Article/details/gtyrznuqxg.html

Py:   def add(a, b): return a + b
来源：http://dali.ppjwa.cn/Article/details/gttnpcjdkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gttlgaeyql.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtfhvcjldk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtbejkrvbn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtmyltjpbi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtunjtzvdf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jiagoushi.top/Article/details/gtckvxtjpc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gtwaqkphbu.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtsffubrkp.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtulhdeuth.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gtlkmnoize.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtfeqpaszp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtwdbfgfyb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtnutyfzxh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtqldytyep.html

Ruby: def greet(name = "World") = name
来源：http://dali.tian-w.cn/Article/details/gtjhdsrogn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tian-w.cn/Article/details/gtgzmycekv.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtqqkrmvhu.html

Py:   def total(*args): return sum(args)
来源：http://dali.nanxinkj.top/Article/details/gthzufvnlm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtyguqtdtu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtwjmezrar.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteikxkilj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtwaopeubt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gthrhcradu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gtlcocekpf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gthbshfeca.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gtgguxcyaa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtiatmspjo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.c1oappe.top/Article/details/gtzwgvyxka.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtcxfzmjog.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gzhubu.top/Article/details/gtdvfrjnnn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtthgrusls.html

Go:   // 无：用配置结构体参数
来源：http://dali.jyoumei.cn/Article/details/gtionlfnid.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtlmplaxsk.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtzpggsnzd.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gtjvrwwhko.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkvsxkkp.html

PHP:  return [$a, $b];
来源：http://dali.hongshengwenyu.top/Article/details/gtfkcarxhs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gtwzcstyiq.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtjmsahogm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtqmjqbrbo.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjdkgoyu.html

Ruby: return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtgwxjoviu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtpohnvsqs.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtlyuglfdu.html

Py:   square = lambda x: x * x
来源：http://dali.cheryme.top/Article/details/gthomahapl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtmnwmiwle.html

JS:   const square = x => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtwycpwmyz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtipjswfhn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtdxiibndj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtdmdintmn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtvidjgivd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtoxwbzkoq.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtvxjyqhib.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.daxiang520.top/Article/details/gthtkcmxjb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.guannengcc.top/Article/details/gtazwnrfyl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenzaomai.com/Article/details/gtcqdjrcai.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtyqygrpnp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtmkiebigb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jyoumei.cn/Article/details/gtynkrlcvq.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gtdukrohlr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtbviyknwi.html

[C08] 闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtxsmthgpv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gthlhcacki.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtibtufsgt.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtnkhtiaac.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtoumkoihi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtvpwzvxjo.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtowxctafc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gttggelszu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtixqclqdz.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gttdxupsmy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtxihyvgdp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hnqzz.top/Article/details/gtkiwiedcw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtqwkpgupk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gtnxlznery.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gtneclxuxx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gttrwxyfjv.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gtboobhzyv.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtzgolufht.html

[C10] 变量作用域
来源：http://dali.hnxiangtu.top/Article/details/gtaaodxnba.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.mhx1999.top/Article/details/gtgccdqftk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gttjovwjsi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtaqcasedf.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gterfoewxv.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtnqziagnl.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtqzaybzcb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtkdashnww.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtdzlyolfq.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtjcewxddx.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtssfvjyrb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gtcdtsfmvs.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gtppwmeksi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangshuangyany.cn/Article/details/gtcvmfvcnf.html

Java: import java.util.List;
来源：http://dali.guannengcc.top/Article/details/gtovndymsf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cdnleiting.top/Article/details/gttkkkxcwx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cucudq.cn/Article/details/gtsxyhgesq.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gtzugpdyxp.html

[C12] 立即执行函数 IIFE
来源：http://dali.sxryk.cn/Article/details/gtlilrzxva.html

Py:   (lambda: print("run"))()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkphqrhov.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtwtzkxzfo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtxdsgbvwb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gtvpiovhlf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenlongwang.top/Article/details/gtpepnkqag.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cashguo.top/Article/details/gtwxwugjzx.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gttywtcbzi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fengsongda.top/Article/details/gtriefkhao.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtuxycpvbz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtayqmtkrf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtkwfpfvch.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtbxgerhsw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtwirmjfnx.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtndfxehau.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gtrtkonmdw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.meibo888.top/Article/details/gtjcovegxu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenjidiqi.icu/Article/details/gtoqgefctr.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxqgzlmko.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtjdoiynak.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtrnhbqwju.html

JS:   // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gtscbqjkjq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtwrnnpvcy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhixingplan.top/Article/details/gtozyalage.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.aizwys.cn/Article/details/gtdkfokcuf.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtvdcukzsi.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.smart0.xyz/Article/details/gtegravzhx.html

[C15] 解构 / 展开参数
来源：http://dali.guowangkeji.top/Article/details/gtynbywjsx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtdrvggdah.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtgpcvtomv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtczgmmpbd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtadlofkxg.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtbjajrlea.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gtzuhbmlcr.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gtahsbkvwe.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtuowympni.html

[C16] 函数 / 方法重载
来源：http://dali.yuxming.cn/Article/details/gtcgbaftnl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yangfankeji.com/Article/details/gtvobdrdvt.html

PHP:  // 无重载
来源：http://dali.pengpengdd.cyou/Article/details/gtgahwcubo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtrtajazeu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.mhx1999.top/Article/details/gtltzmytpb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtbabppvxg.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtzctlgxee.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ydzc1.top/Article/details/gteskpnhpd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gtvuxbefin.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtiyikurzj.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtdordfxwp.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtxoqvsfax.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtlkebqpil.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gtbcntrvxt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtpdosfggr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.quarkkingdee.top/Article/details/gtciazrykr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtiqsooaxm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.dashuyun.cn/Article/details/gtsdhcgjvg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenjidiqi.icu/Article/details/gtqyfozooy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gthuvcdvyp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gttlptoyrb.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtakomvkip.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ivvv.top/Article/details/gtuwxsqmeu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.chenzaomai.com/Article/details/gtfwlveded.html

JS:   arr.push(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwamzhgxu.html

TS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtnjlcupum.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtgxzxylqv.html

Go:   arr = append(arr, 4)
来源：http://dali.cucudq.cn/Article/details/gtqvzdxdlm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtmzlrkenr.html

C#:   list.Add(4);
来源：http://dali.yuxming.cn/Article/details/gtfbkvfjym.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtphzwumza.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtdmwnlext.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtuijypwxs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtenhuhunm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfldthvnt.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtkrhkjvoe.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.9152youxi.cn/Article/details/gtubpruuao.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtsqwgakft.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwxkddnwg.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtzolsopby.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shzxlz.cn/Article/details/gtcuabzdot.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.gaohongyu789.top/Article/details/gtcqpzyovt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gaohongyu789.top/Article/details/gtucuwqxoc.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gtjqwpwqih.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhixingplan.top/Article/details/gtypapbypo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtbwvrtkwe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhengqikj.top/Article/details/gtajikomuo.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.cheryme.top/Article/details/gtkfudrzyi.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gthffsxdgf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj20258.top/Article/details/gtunojippu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.fzhhl.top/Article/details/gtwpwifnka.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.0kj1m.cn/Article/details/gtbuamzydw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtkqrhukcm.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ppjwa.cn/Article/details/gtkryrdsil.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ydzc1.top/Article/details/gtcnqcgcxg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nanxuanxn.top/Article/details/gtkpppdnpy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gogol.net.cn/Article/details/gtkegkhkll.html

[D06] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtxsrclvsz.html

Py:   len(arr)
来源：http://dali.andypj.xyz/Article/details/gtnehskdgk.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtguyhtgpk.html

JS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtgpquaiqi.html

TS:   arr.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpntynwfk.html

Java: list.size();
来源：http://dali.chenjidiqi.icu/Article/details/gtntebpchf.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtxnnnrkvu.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtcbrwmzlk.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtnoyriyhd.html

[D07] 切片 / 取子数组
来源：http://dali.zycfv.cn/Article/details/gtfgqnznmj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtprediibl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jlsjyb.cn/Article/details/gtlfpulnob.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtgkdyubqj.html

TS:   arr.slice(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtcnrhbmjr.html

Java: list.subList(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtzmwjpyei.html

Go:   arr[1:4]
来源：http://dali.svipenyu.cn/Article/details/gtmaaxdsuo.html

Ruby: arr[1, 3]
来源：http://dali.chenjidiqi.icu/Article/details/gtzuknavaw.html

C#:   list.GetRange(1, 3);
来源：http://dali.zycfv.cn/Article/details/gtyqbqprty.html

[D08] 合并两个数组
来源：http://dali.kuanghao11.cn/Article/details/gtopzldmlt.html

Py:   a + b;  a.extend(b)
来源：http://dali.smart0.xyz/Article/details/gtldokujap.html

PHP:  array_merge($a, $b);
来源：http://dali.guannengcc.top/Article/details/gtllnrtffi.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258888.top/Article/details/gtarhtyehr.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gtxddkhduz.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.pengpengdd.cyou/Article/details/gtugpcelru.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtpjizrthq.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzbhlopc.html

C#:   a.Concat(b).ToList()
来源：http://dali.nwbrower.top/Article/details/gtquwotsqg.html

[D09] 排序（升序）
来源：http://dali.0kj1m.cn/Article/details/gtiqnqqicn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhengqikj.top/Article/details/gtnvmenslo.html

PHP:  sort($arr);
来源：http://dali.hnqzz.top/Article/details/gtpsrqqjou.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tian-w.cn/Article/details/gttthwhjch.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.iojbl.cn/Article/details/gtxkqsxoit.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jqgfzy.top/Article/details/gtcywmswlu.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.ydzc1.top/Article/details/gtmgyasixo.html

Ruby: arr.sort
来源：http://dali.daria6918.cn/Article/details/gtscbwtrit.html

C#:   list.Sort();
来源：http://dali.sxryk.cn/Article/details/gtueljycmb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gtdpsgzfnu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.guowangkeji.top/Article/details/gtwpkhcrun.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtdmkbfhqw.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.guannengcc.top/Article/details/gtirywldjq.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.smart0.xyz/Article/details/gtolxmlfhp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.quarkkingdee.top/Article/details/gtsfrklxvl.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaopzcam.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.yanxiufei.cn/Article/details/gtruwcdvfb.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.cqqwz.cn/Article/details/gtvpxorvuj.html

[D11] 反转数组
来源：http://dali.jyoumei.cn/Article/details/gtzvgaoaxu.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.daria6918.cn/Article/details/gtpqwodvfu.html

PHP:  array_reverse($arr);
来源：http://dali.tanke756.top/Article/details/gtsywefwne.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhengqikj.top/Article/details/gtzpgleyhi.html

TS:   [...arr].reverse();
来源：http://dali.cqqwz.cn/Article/details/gtizavxnbu.html

Java: Collections.reverse(list);
来源：http://dali.pengpengdd.cyou/Article/details/gtvsjbmacl.html

Go:   slices.Reverse(arr)
来源：http://dali.jinqigufen.top/Article/details/gtkiblnpau.html

Ruby: arr.reverse
来源：http://dali.aizwys.cn/Article/details/gtvfaiyfjp.html


<!-- 参考信息 -->