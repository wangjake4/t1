代发 wailian999

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtyeltwmwo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtguxwrgdx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yonumen.top/Article/details/gtrcoogxow.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtqifebwla.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtbstxegpp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gttpukfsrt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gtnaqoyfuy.html

[B12] 跳出多层循环
来源：http://dali.zycfv.cn/Article/details/gtmvaygiic.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyatfxad.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gthwmjwife.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtflvlmdhg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtgxziehpc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtpfkkuswz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sysykeji.top/Article/details/gtztquqevf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gtgwpshjyn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtzwaezavm.html

[B13] 判断是否为数字
来源：http://dali.jqgufenzy.top/Article/details/gtisicdxnr.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtowxxqxfn.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtejxiamtl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtwfmuznju.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtrpcofojo.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gtnzlrixfl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.snrcjt.cn/Article/details/gtnhnkajgy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xinyue.icu/Article/details/gtgtnthqvm.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gttayfdrtu.html

[B14] 判断值是否在集合内
来源：http://dali.birdmap.top/Article/details/gtleichfnh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zycfv.cn/Article/details/gtkyttjgpy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtuegoecot.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtmksfuokm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtoizdmjon.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gtlpbqsstl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yvedp.cn/Article/details/gtorvdrmiy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnqzz.top/Article/details/gtxhtgfsie.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xziqi.cn/Article/details/gteyqohsak.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtylznpqcn.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtgxdwscbw.html

PHP:  $a && $b || !$c
来源：http://dali.jiagoushi.top/Article/details/gtmpevpnxh.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtkolsfsqx.html

TS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gteqxfbamk.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtjbcqvstr.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtwmvkshoh.html

Ruby: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtqtvreyla.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtimmvgtyw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cdnleiting.top/Article/details/gtvgsqrasx.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtzvufbnol.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtwkflryhf.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtqolylpyh.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtoiodkxnw.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gttrldraws.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtgifntgdo.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gtijprnyll.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtowiazmjr.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtafybvwiq.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtyypiubwa.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpgushaio.html

[C01] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtjrzmuaoz.html

Py:   def add(a, b): return a + b
来源：http://dali.iojbl.cn/Article/details/gtajwwxyni.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtbacrnsuo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtsobomfzq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtfslpdsei.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtkrcxonhf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenzaomai.com/Article/details/gtzwwfjrxv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfzubzjea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtefdcjvva.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtzpjbroyn.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtpwguyunw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gtkhscmico.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtrmskgwiw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtqynkuqck.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gthtvgrohm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtjtdqxqrb.html

Ruby: def greet(name = "World") = name
来源：http://dali.sxryk.cn/Article/details/gtfrshagup.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenlongwang.top/Article/details/gtewtxxsyy.html

[C03] 可变参数
来源：http://dali.nwbrower.top/Article/details/gtpgdxcepi.html

Py:   def total(*args): return sum(args)
来源：http://dali.bjfxy.top/Article/details/gtcetplkom.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.andypj.xyz/Article/details/gtnikozjxi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtlubfthtc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ppjwa.cn/Article/details/gtyvlcmosd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gtotouueaa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtsfzqjxgr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtnqdstwtr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.9152youxi.cn/Article/details/gtjkuugfrk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gtqcddozmt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gtrcmnpdlp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtwhkqlrlh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtslppmvft.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yvedp.cn/Article/details/gtrzafaibn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hammf.cn/Article/details/gtizjgmvuv.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtsuecsvtx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtbgupinoe.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtpfltcjst.html

[C05] 返回多个值
来源：http://dali.gogol.net.cn/Article/details/gtmfohgafs.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gtkxxltbnh.html

PHP:  return [$a, $b];
来源：http://dali.xuanzx.com/Article/details/gtydjaxsbh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtcjemwozy.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtmycnlvyd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gthientrcs.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtwdxiokfe.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtocypxywi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchrtzedg.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtaiztygvj.html

Py:   square = lambda x: x * x
来源：http://dali.yangfankeji.com/Article/details/gtycxllnsc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtraqxmesn.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gtbyjxehpz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrycgflrx.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shzxlz.cn/Article/details/gtpiyhdrts.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.havefunace.top/Article/details/gtyorfbvno.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xylfe.cn/Article/details/gtefzxuejy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtlaillmwd.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtteydkump.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtbskdbzhq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangdashe.top/Article/details/gtranxxpro.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hammf.cn/Article/details/gttuqdgveg.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtqpaajyfx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtnbmifmbl.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gtpjnkqmgx.html

Ruby: arr.map(&:upcase)
来源：http://dali.yonumen.top/Article/details/gttmjodkfv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtidygbhsr.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gtrehggbxf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.guowangkeji.top/Article/details/gtxctfezmo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.smart0.xyz/Article/details/gttxjkucyu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtnxhkqsho.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtkwppkskk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtefjbhlsv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.haohaochexian.top/Article/details/gthxurwudz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtfobtwwtm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtsbnztjwh.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtsvhuwqzy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtmzeknhfl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gtivrakpjp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gtwewinqdw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtsqmdsrcb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtbbkbbmka.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gtjcqsajvo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtebchhavs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yj20258888.top/Article/details/gtyeykcapv.html

[C10] 变量作用域
来源：http://dali.yj20258888.top/Article/details/gtdwofhqzk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sxryk.cn/Article/details/gtcgpdxsqc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtqpevpkuv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtdileqlzq.html

TS:   同 JS
来源：http://dali.hongshengwenyu.top/Article/details/gtawlquvxx.html

Java: 方法内为块级作用域
来源：http://dali.ydzc1.top/Article/details/gtyffpuqnb.html

Go:   花括号块级作用域
来源：http://dali.hfpthk.cn/Article/details/gticcsrzdk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jyoumei.cn/Article/details/gtadazkbzc.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtiiecgbxh.html

[C11] 模块导入与导出
来源：http://dali.wangdashe.top/Article/details/gtoecftwbb.html

Py:   from module import func
来源：http://dali.birdmap.top/Article/details/gthqxvjpjr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtqbcukogf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtomwkwziw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtshndpqap.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtndiuqtwt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gtybzlxnhg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtjbadhbki.html

C#:   using System.Text;
来源：http://dali.ydzc1.top/Article/details/gtoyanucah.html

[C12] 立即执行函数 IIFE
来源：http://dali.jianghu66.top/Article/details/gtlwzeephw.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtislrofys.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gotoacloud.top/Article/details/gtublfyluy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yangfankeji.com/Article/details/gtjapqzxla.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtxygvbnzj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.pycfn.com/Article/details/gtfftuwgrd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtmztdiuga.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gtojmusxlz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gtlbgmlwhz.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtasfikucw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jlsjyb.cn/Article/details/gtsyxgsicc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gthrmptexj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cdnleiting.top/Article/details/gtnrjrojwg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtkqpnadiy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtrmhnqjjy.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtzpgncwko.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtbufwubew.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jianghu66.top/Article/details/gtygfshjkh.html

[C14] 泛型函数
来源：http://dali.sufxvd.cn/Article/details/gtkjfxyymm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.birdmap.top/Article/details/gtafqrrjpi.html

PHP:  // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtcamrhalk.html

JS:   // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtuxqxjcur.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xylfe.cn/Article/details/gtzpkzpaef.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gteedhqtjz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sufxvd.cn/Article/details/gtiphxoxvh.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtziymeugd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yonumen.top/Article/details/gtkxgcmazb.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gtzxbyqdfk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cucudq.cn/Article/details/gtzjtlfgkd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sufxvd.cn/Article/details/gtcijyhbcw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtebtxfrvt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtvrzblwfd.html

Java: // 无解构
来源：http://dali.yj20258888.top/Article/details/gtztvuatoj.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujwftowx.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftieddeg.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtfvbmnnui.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gtdwhrgwnn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yvedp.cn/Article/details/gtwngwcogt.html

PHP:  // 无重载
来源：http://dali.redwolf501.top/Article/details/gtfizzdhqt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtfesdybtd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xziqi.cn/Article/details/gtthyplmiz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhongyouzk.top/Article/details/gtoywkusvm.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtbgoeobcd.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cqqwz.cn/Article/details/gtyzgvgrzs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.316326.xyz/Article/details/gtrjlfdmtk.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtmfjlzqpt.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvgssexd.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjhkaltrg.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtteupnfli.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtcgaqryow.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtkiferkgj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cucudq.cn/Article/details/gtbcuimage.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtmlnndoxm.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cucudq.cn/Article/details/gtxlhprjri.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.kuanghao11.cn/Article/details/gtoelvvtly.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtohiedrfc.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.kuanghao11.cn/Article/details/gtowswxxlp.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtdjfpqtbg.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daxiang520.top/Article/details/gtfkqnzwef.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hywenlv.cn/Article/details/gtgkqgahcc.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtlkupdfrj.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gthujqrmhj.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtyqgjtywp.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gtqsltjozi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jlsjyb.cn/Article/details/gtlcbvewje.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtlpoydfmx.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtnhfhoudi.html

Py:   arr.insert(0, 0)
来源：http://dali.yanxiufei.cn/Article/details/gtaeezovws.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.fengsongda.top/Article/details/gtxwjfghwb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtguwckjxg.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtsfngglis.html

Java: list.add(0, 0);
来源：http://dali.daxiang520.top/Article/details/gtdoqheids.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhiwuduotai.top/Article/details/gttkenxfwy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.tanke756.top/Article/details/gtnyiqzlvs.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtwfwbrfle.html

[D04] 删除元素
来源：http://dali.yangfankeji.com/Article/details/gtsvufwssn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jyoumei.cn/Article/details/gtsnldbfnp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtbpgctxwt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tian-w.cn/Article/details/gtpnyghgdx.html

TS:   arr.splice(0, 1);
来源：http://dali.sweek.top/Article/details/gthvuunujc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tian-w.cn/Article/details/gtuflbmjoj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtcevvwlxp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtpmmftfpe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.pengpengdd.cyou/Article/details/gtqhhjybgv.html

[D05] 访问与修改元素
来源：http://dali.xuetiantiany.cn/Article/details/gtlxoihmim.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtnodpaiis.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.ivvv.top/Article/details/gthuxjygou.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtssnlvwyd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gtwsegqugg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdykvrroh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gthpgiwznm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtawhabujo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gtjsbvasec.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtfxibabmb.html

Py:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtzigjzkak.html

PHP:  count($arr);
来源：http://dali.jinghuilouyu.cn/Article/details/gtupxepqkb.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtgmpxgnod.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtpmsbatij.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtzkveajix.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gtduyxrrkz.html

Ruby: arr.length; arr.size
来源：http://dali.sxryk.cn/Article/details/gtngetkjpq.html

C#:   list.Count;
来源：http://dali.gzhubu.top/Article/details/gtlskjbyrc.html

[D07] 切片 / 取子数组
来源：http://dali.jinqigufen.top/Article/details/gtdkkzkzqe.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cqqwz.cn/Article/details/gtamhukzeh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtqndvpqnj.html

JS:   arr.slice(1, 4);
来源：http://dali.iojbl.cn/Article/details/gtdozdceql.html

TS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gtufqyaxvl.html

Java: list.subList(1, 4);
来源：http://dali.yongpay.top/Article/details/gtlraqfjgt.html

Go:   arr[1:4]
来源：http://dali.tian-w.cn/Article/details/gtylvfhmol.html

Ruby: arr[1, 3]
来源：http://dali.wangshuangyany.cn/Article/details/gtyssdaglf.html

C#:   list.GetRange(1, 3);
来源：http://dali.kuanghao11.cn/Article/details/gtxhjinwat.html

[D08] 合并两个数组
来源：http://dali.yuxming.cn/Article/details/gtltjbdtax.html

Py:   a + b;  a.extend(b)
来源：http://dali.redwolf501.top/Article/details/gtwarjhmot.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtqbokiygk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.aizwys.cn/Article/details/gtarwwhkyc.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gtjtxrdtzj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guowangkeji.top/Article/details/gtfovoflzr.html

Go:   append(a, b...)
来源：http://dali.sufxvd.cn/Article/details/gtfdmtjpgb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkebuyssn.html

C#:   a.Concat(b).ToList()
来源：http://dali.hywenlv.cn/Article/details/gtyjacwyfr.html

[D09] 排序（升序）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakkppfuo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvtnhapx.html

PHP:  sort($arr);
来源：http://dali.yanxiufei.cn/Article/details/gthkwoetcr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtrjwmwuca.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.guowangkeji.top/Article/details/gtxlzgmauo.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtfcpbsqnj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gotoacloud.top/Article/details/gtnamzwadk.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfndpscs.html

C#:   list.Sort();
来源：http://dali.nwbrower.top/Article/details/gteklhfmsv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.meibo888.top/Article/details/gtypnburwn.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ivvv.top/Article/details/gtebnoebfz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtynpacbom.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yuanzhike.top/Article/details/gtdpzdqgxh.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gttvismexc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.jyoumei.cn/Article/details/gtjjfliweq.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.kuanghao11.cn/Article/details/gttagvbidi.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.iojbl.cn/Article/details/gtvleuotjn.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtvvaqozvl.html

[D11] 反转数组
来源：http://dali.pycfn.com/Article/details/gtjjxsqetf.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.ybcxt.top/Article/details/gtcnfctvlf.html

PHP:  array_reverse($arr);
来源：http://dali.tian-w.cn/Article/details/gtdkfxhjrb.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.jqgufenzy.top/Article/details/gtyizvfzxl.html

TS:   [...arr].reverse();
来源：http://dali.iojbl.cn/Article/details/gtfhoutgfu.html

Java: Collections.reverse(list);
来源：http://dali.sxryk.cn/Article/details/gtrcqrmgrc.html

Go:   slices.Reverse(arr)
来源：http://dali.iojbl.cn/Article/details/gtnhltdduy.html

Ruby: arr.reverse
来源：http://dali.shzxlz.cn/Article/details/gtpnbeerdl.html


<!-- 参考信息 -->