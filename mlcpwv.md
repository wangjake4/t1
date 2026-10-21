代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj20258.top/Article/details/gtthhdamvq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhiwuduotai.top/Article/details/gticsnnwhh.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtovistmly.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gtpmbozhkg.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxinkj.top/Article/details/gtpeuxwaei.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtgrcdabsi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtcqbuvnfm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xziqi.cn/Article/details/gtkalzvnee.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gtqfxjuzll.html

Ruby: (0...10).step(2).to_a
来源：http://dali.c1oappe.top/Article/details/gtyophapte.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtoonqrjqi.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gtechbzqzn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yueranfly.top/Article/details/gtmqqcbupm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtrnucomsy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtymvercre.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gthcutqlzs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtffvtjrbg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gtyogapdya.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtlyvuffhj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenlongwang.top/Article/details/gtujxvatff.html

[B13] 判断是否为数字
来源：http://dali.jiagoushi.top/Article/details/gtbjrbtdis.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gtgrnnxkdn.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtaayvcipu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtpxisxtwl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtlcuyncxh.html

Java: x instanceof Number
来源：http://dali.xinyue.icu/Article/details/gtlcholbjc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hammf.cn/Article/details/gtjicecfwd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtfudvvkzt.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtubksoieu.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtabblzgst.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtvqjeksge.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sweek.top/Article/details/gtrcnpmkjr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtgukdxwuw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyuuqoml.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtgfatcslr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gtkkwndsre.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtdkktkcnu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtvjotdtna.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtxkarbbtd.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtjwkibslw.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gtwferasip.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtaqgavbay.html

TS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtdojbmqau.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtkqgykpuu.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtqxpxzdra.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtvmcprebh.html

C#:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gthjjdfffb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj202588.top/Article/details/gtoqalefsb.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtczhaxomk.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gtptnfedjr.html

JS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gthtursaoz.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtrmrwuads.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtgdvcnbbg.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gthpwloqxe.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtbxvqcxuo.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtmebnzswu.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkoywrery.html

C. 函数与作用域
来源：http://dali.vqdsnc.cn/Article/details/gtgdoblsts.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtcxcfkqww.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gtfsqnylxp.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtgosxitcf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtezprrghy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtwxsruaai.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtvdbkqerx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gthcibkspo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gtzbxqdnib.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtfhgehmdw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtgbcfqshy.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtpcimjawl.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtxelerrrl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.316326.xyz/Article/details/gtscylmppe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gthgowozpb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtrmrsbiqd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtflguudgn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtlkjeguri.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvcnlmbtw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gtrcanjlbj.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtlcqyjzgo.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymmuccqg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ppjwa.cn/Article/details/gtfjtrbtog.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtzkobsqco.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtvksikrhh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gtsaxaclwf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrsjngul.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xuetiantiany.cn/Article/details/gtsuvkssec.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtbzxxhhcc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xziqi.cn/Article/details/gtjyfejwrs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yongpay.top/Article/details/gtcixwxpxr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.meibo888.top/Article/details/gtkpckgofm.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtjoqrrpxp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nwbrower.top/Article/details/gtiudkhmkn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gtnoyptreu.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtmqarougj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtaqjxcctz.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gtyjgcdqwi.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gthqedakht.html

Py:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbucomyy.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gthgjlwpkw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtdnwuuejb.html

TS:   return { a, b };
来源：http://dali.jyoumei.cn/Article/details/gtfclkgofb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhixingplan.top/Article/details/gtnspqbfdc.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gtoewgrutp.html

Ruby: return a, b
来源：http://dali.cdnleiting.top/Article/details/gtnaqebtlu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtgzaxesrc.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtmeijspit.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtinmiefsa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtyguqcocg.html

JS:   const square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gtdymmpiiv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gthtcwycfh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtdhqjbtyq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtfjchrmgr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtdynxoath.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtpufrbgvh.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtolqpnwjh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtewpfotuc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtjvsefecn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ydzc1.top/Article/details/gtavheirrd.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtlmtubhvg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtcgeirfyc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gttdcqqhxh.html

Ruby: arr.map(&:upcase)
来源：http://dali.chenjidiqi.icu/Article/details/gtluiwnetq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtrvglmysd.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gthmetnyww.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtmssqonjk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ppjwa.cn/Article/details/gtxevkmvxq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtdxffbwcs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtddtixgzh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuetiantiany.cn/Article/details/gtgdzraxqb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.feifeiyinyue.top/Article/details/gtmxrtxrkr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gteslhmafb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtjxsnhxas.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gtfsstmxuc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtkckadfsp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtwdbmtozy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jianghu66.top/Article/details/gtvjfsfwvo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtwfwmwxmk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtyegomojf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenjidiqi.icu/Article/details/gtkiibcfce.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtcpknmcxo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gtmoyzvuqe.html

[C10] 变量作用域
来源：http://dali.jyoumei.cn/Article/details/gtbdjhedng.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.nwbrower.top/Article/details/gtszxmeczy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtpkavbclp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cdnleiting.top/Article/details/gtthjtkdqc.html

TS:   同 JS
来源：http://dali.9152youxi.cn/Article/details/gttomvwywt.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gtwtaritge.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtfqavxgfi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtfdnxdpex.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtfoqaslcg.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwcespip.html

Py:   from module import func
来源：http://dali.zhixingplan.top/Article/details/gtvbzstnfv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gttxafxkjb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gzhubu.top/Article/details/gtrpyuhwjd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.feifeiyinyue.top/Article/details/gtocdbddlh.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gthzpunxun.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gtpxruthuh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.sweek.top/Article/details/gtpvasxvxt.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtatuzylhg.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgfzy.top/Article/details/gtaudwedvz.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gtrnqjjxqk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hammf.cn/Article/details/gtgjewhpsm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtdlnyrhxw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtubsmacvm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jlsjyb.cn/Article/details/gtthjhbhzd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gtttjwwjhk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhiwuduotai.top/Article/details/gtiftnqfer.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shuidangran.top/Article/details/gtknowhgvr.html

[C13] 类型声明 / 类型注解
来源：http://dali.fzhhl.top/Article/details/gtvlulrvgc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtoudnvclg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjicksigq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtemtfdrbc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtwzfosblu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtqpeakybz.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gttouwauzz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xylfe.cn/Article/details/gtsfudxzpy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gthhdvntrr.html

[C14] 泛型函数
来源：http://dali.316326.xyz/Article/details/gtzqvbppam.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gtntvvnsug.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtatnydgdd.html

JS:   // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gtrqvdhocf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cdnleiting.top/Article/details/gtgajrihdo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtpdnbvmix.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.svipenyu.cn/Article/details/gtomrrtmgv.html

Ruby: # 无泛型
来源：http://dali.pycfn.com/Article/details/gtkbmttuoe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gtveudbasj.html

[C15] 解构 / 展开参数
来源：http://dali.jqgfzy.top/Article/details/gtkumtjhip.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzjrzqqd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.nanxinkj.top/Article/details/gtapuivznw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtvtqgwkgp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhixingplan.top/Article/details/gtwztonbxz.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gteptehuco.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtdrnobdxa.html

Ruby: a, b = pair
来源：http://dali.jyoumei.cn/Article/details/gtddutswhz.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtzqzspofg.html

[C16] 函数 / 方法重载
来源：http://dali.gzhubu.top/Article/details/gtppxgqnri.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jqgfzy.top/Article/details/gtaxomliex.html

PHP:  // 无重载
来源：http://dali.gaohongyu789.top/Article/details/gtvhprltff.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjwvrcqdw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jianghu66.top/Article/details/gttwfipcrh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtvixcetfy.html

Go:   // 无重载：用不同函数名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzacbigpl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gtnbntbitk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yanxiufei.cn/Article/details/gtnaivicpc.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gthdfawral.html

D. 数组 / 列表 / 集合
来源：http://dali.chenjidiqi.icu/Article/details/gtpugcfrhb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtmjphsoad.html

[D01] 创建数组 / 列表
来源：http://dali.meibo888.top/Article/details/gtwmflptyh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.quarkkingdee.top/Article/details/gtbacoqwij.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgvfywgf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.c1oappe.top/Article/details/gtdffoswto.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hysaishi.cn/Article/details/gtaqlwcvgo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258888.top/Article/details/gtqsirfbne.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gzhubu.top/Article/details/gtzyycgxtu.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtyucqtyvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cashguo.top/Article/details/gtrovayeru.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtqlbsjhxi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.iojbl.cn/Article/details/gtdougvtvm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtnpjfhpbb.html

JS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtazdnfoll.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtdezxfdga.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtghvjzwlo.html

Go:   arr = append(arr, 4)
来源：http://dali.chenlongwang.top/Article/details/gtqdrwcbyh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shangyingyoupin.top/Article/details/gtisslezbn.html

C#:   list.Add(4);
来源：http://dali.jlsjyb.cn/Article/details/gtrfybcopo.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtzzlhjstl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtwipmyrit.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shzxlz.cn/Article/details/gtlhmquvcw.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtexybkulm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sysykeji.top/Article/details/gtjkzyiapm.html

Java: list.add(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtvndprtbx.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ybcxt.top/Article/details/gtnofvpefx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gotoacloud.top/Article/details/gthmxqkbac.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtwtzsgcba.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtdtgajvok.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hnqzz.top/Article/details/gtvuoshkgt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zdqjudy.top/Article/details/gtcftlsalr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.9152youxi.cn/Article/details/gtcfbvgnut.html

TS:   arr.splice(0, 1);
来源：http://dali.shuidangran.top/Article/details/gtkatedhej.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkwiavtg.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtyprtnrlp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtwidvflfr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.nwbrower.top/Article/details/gtvuqcjaaf.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfpkxnmc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zdqjudy.top/Article/details/gtseidzfpd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yuanzhike.top/Article/details/gtauufjzwb.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtvzvzurfq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtgfmwilbu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.feifeiyinyue.top/Article/details/gtxjghjzfj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtnruwjufb.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtgmeiemao.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hongshengwenyu.top/Article/details/gtswqffdhq.html

[D06] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtsgygqqsi.html

Py:   len(arr)
来源：http://dali.hammf.cn/Article/details/gtkbzktgsk.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtupvcxurq.html

JS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtgfasrqku.html

TS:   arr.length
来源：http://dali.zhijiandao.cn/Article/details/gtewbsjipz.html

Java: list.size();
来源：http://dali.xuanzx.com/Article/details/gttvpfpwfc.html

Go:   len(arr)
来源：http://dali.wangdashe.top/Article/details/gtcwpuvifv.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gttybtqpwd.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtbjelnjca.html

[D07] 切片 / 取子数组
来源：http://dali.yj202588.top/Article/details/gtbysylwmc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.andypj.xyz/Article/details/gtijuygkjn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yvedp.cn/Article/details/gtdgxfeskj.html

JS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gtvflrlyys.html

TS:   arr.slice(1, 4);
来源：http://dali.vqdsnc.cn/Article/details/gtgxiubmfk.html

Java: list.subList(1, 4);
来源：http://dali.gotoacloud.top/Article/details/gtnbugotqi.html

Go:   arr[1:4]
来源：http://dali.pengpengdd.cyou/Article/details/gtyybmwpbz.html

Ruby: arr[1, 3]
来源：http://dali.zhiwuduotai.top/Article/details/gtjnatyena.html

C#:   list.GetRange(1, 3);
来源：http://dali.nwbrower.top/Article/details/gtajstmlmc.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gtswujuzlp.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenlongwang.top/Article/details/gtcudqpgcl.html

PHP:  array_merge($a, $b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqojycmo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.haohaochexian.top/Article/details/gtmotjikpb.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtkmhoqqep.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.9152youxi.cn/Article/details/gtzilkmzej.html

Go:   append(a, b...)
来源：http://dali.shangyingyoupin.top/Article/details/gtgvmzhmys.html

Ruby: a + b;  a.concat(b)
来源：http://dali.0kj1m.cn/Article/details/gtdxahtrpn.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhongyouzk.top/Article/details/gtveenurys.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtqduolxek.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.aibaodan.cn/Article/details/gtqizljlif.html

PHP:  sort($arr);
来源：http://dali.iojbl.cn/Article/details/gtynwjqmqo.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.aizwys.cn/Article/details/gtwlzsvzvx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.mhx1999.top/Article/details/gtgkmcaxwq.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.aizwys.cn/Article/details/gtovwopaay.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yj202588.top/Article/details/gtrrtffogs.html

Ruby: arr.sort
来源：http://dali.hywenlv.cn/Article/details/gtawvyqejv.html

C#:   list.Sort();
来源：http://dali.zhixingplan.top/Article/details/gtqzmktxdm.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gthstfzein.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.yvedp.cn/Article/details/gtjvqnctuw.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gtuyepuhnh.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sweek.top/Article/details/gtkguztday.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.xinyue.icu/Article/details/gtngcqduvx.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.zycfv.cn/Article/details/gtsnmltpaw.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cashguo.top/Article/details/gtcocaxxwn.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jianghu66.top/Article/details/gthdbjklrl.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.jinqigfzy.top/Article/details/gtiaxkxbut.html

[D11] 反转数组
来源：http://dali.hfpthk.cn/Article/details/gtuwcxrxoi.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqfhwazff.html

PHP:  array_reverse($arr);
来源：http://dali.fzhhl.top/Article/details/gtwwavmhec.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.yj20258.top/Article/details/gtqjyhtspz.html


<!-- 参考信息 -->