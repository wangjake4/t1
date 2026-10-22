代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gtsmmecolg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkuobsckw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtpyfqkpvp.html

Py:   list(range(0, 10, 2))
来源：http://dali.jyoumei.cn/Article/details/gtymlutxnk.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtmlvhatil.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtnrzmvngp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gtjlxlqyek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtodfseyuk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cashguo.top/Article/details/gtnpiytenx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtmxnjtzhx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtotearhll.html

[B12] 跳出多层循环
来源：http://dali.tian-w.cn/Article/details/gtivoekbjt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gttrpxloct.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtrotqscwi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtfnazutth.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtpyccfqbp.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtscmzjrqs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gtjywllsmk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtjcreevkd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtpntdwabp.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtdzqepjem.html

Py:   isinstance(x, (int, float))
来源：http://dali.fengsongda.top/Article/details/gtobszkrao.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtldbkjfco.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtonrwtexs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtvetoxlam.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtmheobppp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gtecxiyicu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtflhyiewj.html

C#:   x is int or double or decimal
来源：http://dali.nanxuanxn.top/Article/details/gtxqwfglkr.html

[B14] 判断值是否在集合内
来源：http://dali.ivvv.top/Article/details/gtadmhstrw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtebwzcdan.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtwxocnfvr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtxdsdhypl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtknistath.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtjepdtzya.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarcirmvd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gteeseizqj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtuzhoyztd.html

[B15] 布尔运算与取反
来源：http://dali.sufxvd.cn/Article/details/gtrowqnpde.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtwpskefda.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gtoeevkgux.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtkcelrjhg.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtbtkrkxoj.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtkaqncljv.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtwiqqyhrk.html

Ruby: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtmocwxhec.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtcdrvigyn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtekkvpqaw.html

Py:   if not data: return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxlrcmdb.html

PHP:  if (!$data) { return; }
来源：http://dali.zhoulong.xyz/Article/details/gtzgoelhzb.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtvzmqhdrc.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtpwzgohxt.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtphfbcdfd.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtgxqfdzmu.html

Ruby: return if data.nil?
来源：http://dali.yonumen.top/Article/details/gttrephqoj.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtcpietgrj.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbfhlsqda.html

C. 函数与作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtvtudinpu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtoeyhppcu.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtjpissqfo.html

Py:   def add(a, b): return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtbrmskzyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtzsmfyorx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtjzegeinj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtelkobdlg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtmxmeydjp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtixojshaf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtwrlnhhwo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtwxeqvzwb.html

[C02] 默认参数
来源：http://dali.wangdashe.top/Article/details/gtydxqzaco.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtadhxevbw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gthztxklsa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxcbzzzlf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gtouzzdgqj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangdashe.top/Article/details/gtxmpzlnvp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yongpay.top/Article/details/gtjaaoqwif.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtkfkdwtsx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gtbzellshe.html

[C03] 可变参数
来源：http://dali.0kj1m.cn/Article/details/gtycgrgjwe.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtlimkyhej.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgnuarawt.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gtvpqrlexh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtiksrgihm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gtqohpbqey.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gtohxbltra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtjbidpxmb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtxaikylsa.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtxivjptsq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtlcurarsz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtmytclbvi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtgsdbxxmm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtczqwxige.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nwbrower.top/Article/details/gtrrecagkz.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtiddmfpwt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gthamnoppx.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gttzkxkrnv.html

[C05] 返回多个值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmthokhwg.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtymytyfqr.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gtnzxhzgpi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtxwgmiaeq.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtrytphbwa.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhongyouzk.top/Article/details/gteiwzfvrb.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtrjeefhpy.html

Ruby: return a, b
来源：http://dali.iojbl.cn/Article/details/gtnxlgtnku.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtjsvmdhcr.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtlanzpoml.html

Py:   square = lambda x: x * x
来源：http://dali.zhijiandao.cn/Article/details/gtpixmbhlz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtwxexffqd.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtkahodive.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daxiang520.top/Article/details/gtaolttfao.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gtmzdsqpdl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gttxkbmggx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtfchmieuo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtechhxnmb.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gtkpqgzcug.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtfadxleyk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sweek.top/Article/details/gttrnxvfet.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tianlin.xyz/Article/details/gtupssyirk.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtgzflgjja.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtbgjrvzsq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtybtwmgeu.html

Ruby: arr.map(&:upcase)
来源：http://dali.yj20258888.top/Article/details/gttdairgjn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtpkdtjofc.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtddkmvfbw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtlnuqwbil.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gtiyrvrriu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gttbntmrrx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gtkfbloxdw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtqiumjqey.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yj202588.top/Article/details/gtytsggsyp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gtenlyhmlg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtmowciefs.html

[C09] 递归
来源：http://dali.xuetiantiany.cn/Article/details/gtnjeukjsg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gthhqffcsm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtsnggbiho.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtxivttdso.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtdsqzdvfv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtblwtsnry.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtncrzxnlq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtrummxncx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtasayhedx.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtjmcjxbsa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtuulocgec.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.quarkkingdee.top/Article/details/gtgkxxkkxt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtqqhgylec.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtfzrwhdqe.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtdhcogafi.html

Go:   花括号块级作用域
来源：http://dali.shuidangran.top/Article/details/gtbcqdluzm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.c1oappe.top/Article/details/gtuzfpywfw.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtotuqmbmh.html

[C11] 模块导入与导出
来源：http://dali.xylfe.cn/Article/details/gtnelaiepk.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gthezzdasm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zdqjudy.top/Article/details/gtwdaqliwz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtahlokjvo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtjkxyuwmc.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgekkeib.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jlsjyb.cn/Article/details/gtdeflounc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtpdjktmzg.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtpsmlqnvw.html

[C12] 立即执行函数 IIFE
来源：http://dali.cheryme.top/Article/details/gtjusqveix.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtxrhutpcv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gtcjupsrtt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zdqjudy.top/Article/details/gtryyqcrjg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gttrooopqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtfultwrqd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.snrcjt.cn/Article/details/gtebensjqe.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtelfhzcyi.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtoihgjfzx.html

[C13] 类型声明 / 类型注解
来源：http://dali.xylfe.cn/Article/details/gtgjijgyxa.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.aibaodan.cn/Article/details/gtbcxnvxqj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gthlhbdueq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guannengcc.top/Article/details/gtkcmtgpva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtfzoznjed.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gthwpjgtia.html

Go:   func add(a, b int) int
来源：http://dali.chenzaomai.com/Article/details/gtuetgmdzm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.mhx1999.top/Article/details/gthtydbxod.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.meibo888.top/Article/details/gtwwntjjbm.html

[C14] 泛型函数
来源：http://dali.ivvv.top/Article/details/gtlswzvkdh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hongshengwenyu.top/Article/details/gtcjfcmbfz.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtjocnibem.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtcxhkkhtg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xuanzx.com/Article/details/gtmhodeoae.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnxiangtu.top/Article/details/gtrtrstknh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtyolydvff.html

Ruby: # 无泛型
来源：http://dali.aizwys.cn/Article/details/gtquwaeagr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gzhubu.top/Article/details/gtgjedcecc.html

[C15] 解构 / 展开参数
来源：http://dali.quarkkingdee.top/Article/details/gtscpdnzrh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gthwvbwrka.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gtgaeziorx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gteeoyudzg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtygxadyqw.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gtogkztqkz.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtecqxywwt.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtkyopytnf.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtdavhlhne.html

[C16] 函数 / 方法重载
来源：http://dali.ydzc1.top/Article/details/gtmahmytpn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtfllojaul.html

PHP:  // 无重载
来源：http://dali.kuanghao11.cn/Article/details/gtkrkvjnyi.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtyosgfoor.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jqgfzy.top/Article/details/gtqapsjclz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtukpkbsws.html

Go:   // 无重载：用不同函数名
来源：http://dali.9152youxi.cn/Article/details/gtdgxfoidc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.vqdsnc.cn/Article/details/gtmmpdhaui.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nwbrower.top/Article/details/gtkfgnwahv.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttoveskid.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtmfsiagds.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtnacfbqte.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtdiodemdd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqsdgmhd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yj20258888.top/Article/details/gtjemfsquj.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gthrquvivg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtihayyzkd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxdcwwko.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yuanzhike.top/Article/details/gtkywxncdi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gzhubu.top/Article/details/gtgvabqlmg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yongpay.top/Article/details/gtibdauwel.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtloavntxm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtsepioisw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.birdmap.top/Article/details/gthwfpibao.html

JS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtafhfgxbz.html

TS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtqtmgopdj.html

Java: list.add(4);
来源：http://dali.pycfn.com/Article/details/gtuqbtyjsu.html

Go:   arr = append(arr, 4)
来源：http://dali.fzhhl.top/Article/details/gtoavtipar.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gogol.net.cn/Article/details/gtiicpuydc.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gteljavprp.html

[D03] 在指定位置插入元素
来源：http://dali.gotoacloud.top/Article/details/gtmundpxzi.html

Py:   arr.insert(0, 0)
来源：http://dali.pengpengdd.cyou/Article/details/gtmhwphrhr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nwbrower.top/Article/details/gtcggojdxr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgufenzy.top/Article/details/gtnddlgiew.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtclgugfjg.html

Java: list.add(0, 0);
来源：http://dali.gaohongyu789.top/Article/details/gteqvfueja.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258.top/Article/details/gtmtmrygjd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yanxiufei.cn/Article/details/gtfptqtxtv.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtojliprie.html

[D04] 删除元素
来源：http://dali.svipenyu.cn/Article/details/gtzbgrrfxw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtwedmjddx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtqxnftkde.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtguamrqwr.html

TS:   arr.splice(0, 1);
来源：http://dali.pengpengdd.cyou/Article/details/gtpcmoczbc.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuanzx.com/Article/details/gtydmvoaoj.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jyoumei.cn/Article/details/gtwhzlfibi.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhoulong.xyz/Article/details/gtvgxqddik.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtpqlvdzim.html

[D05] 访问与修改元素
来源：http://dali.hnxiangtu.top/Article/details/gtggowfwei.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwspppknf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtznbvyppe.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.vqdsnc.cn/Article/details/gtkqdlptnf.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.aibaodan.cn/Article/details/gtlqxiczhd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtttctecbq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.mhx1999.top/Article/details/gtxshdwmxz.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtjqoweinn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtpccrxxdu.html

[D06] 数组长度
来源：http://dali.9152youxi.cn/Article/details/gtzunhcmcx.html

Py:   len(arr)
来源：http://dali.bjfxy.top/Article/details/gtzqtwkfae.html

PHP:  count($arr);
来源：http://dali.316326.xyz/Article/details/gtvubprnwp.html

JS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtieopljmh.html

TS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtyzbiwptg.html

Java: list.size();
来源：http://dali.shangyingyoupin.top/Article/details/gtkhftagen.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gtakyrjvlj.html

Ruby: arr.length; arr.size
来源：http://dali.wangdashe.top/Article/details/gtybewrikm.html

C#:   list.Count;
来源：http://dali.haohaochexian.top/Article/details/gtvgvvhkxt.html

[D07] 切片 / 取子数组
来源：http://dali.tian-w.cn/Article/details/gtbsfsjzxn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.nanxinkj.top/Article/details/gtdtgmkowi.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.tanke756.top/Article/details/gtbsablupd.html

JS:   arr.slice(1, 4);
来源：http://dali.chenzaomai.com/Article/details/gtqbjhqpxv.html

TS:   arr.slice(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtmhpjudlr.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtghxllthp.html

Go:   arr[1:4]
来源：http://dali.ppjwa.cn/Article/details/gtkevsccje.html

Ruby: arr[1, 3]
来源：http://dali.jianghu66.top/Article/details/gtqcwkhgsx.html

C#:   list.GetRange(1, 3);
来源：http://dali.guannengcc.top/Article/details/gtcingewbp.html

[D08] 合并两个数组
来源：http://dali.chenzaomai.com/Article/details/gtbgliqxho.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtwyuvseyb.html

PHP:  array_merge($a, $b);
来源：http://dali.zhiwuduotai.top/Article/details/gtjebxfykv.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.wangdashe.top/Article/details/gtpkzhxpks.html

TS:   [...a, ...b];
来源：http://dali.daria6918.cn/Article/details/gtrejnzmnq.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtqoceikxm.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gtptustndb.html

Ruby: a + b;  a.concat(b)
来源：http://dali.meibo888.top/Article/details/gtzrgdhehx.html

C#:   a.Concat(b).ToList()
来源：http://dali.sweek.top/Article/details/gtuaprlbpd.html

[D09] 排序（升序）
来源：http://dali.redwolf501.top/Article/details/gtaggmfxli.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtagtwwzku.html

PHP:  sort($arr);
来源：http://dali.redwolf501.top/Article/details/gtwdltkqjj.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.andypj.xyz/Article/details/gtfriokjdh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.hnxiangtu.top/Article/details/gtpklpabpr.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.fengsongda.top/Article/details/gtfqdarmbm.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jiagoushi.top/Article/details/gtuluptpgx.html

Ruby: arr.sort
来源：http://dali.shanyushiyangtech.top/Article/details/gtiubfhnaz.html

C#:   list.Sort();
来源：http://dali.yonumen.top/Article/details/gthtefrxke.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gaohongyu789.top/Article/details/gtupgboblx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.zycfv.cn/Article/details/gtoijngfdk.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtuvwbvjzd.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cucudq.cn/Article/details/gtkxctxdsc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gteknbvhzp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlsghbocs.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.hysaishi.cn/Article/details/gtoqdnsrfa.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jlsjyb.cn/Article/details/gtoovpasuh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfxgtcnks.html

[D11] 反转数组
来源：http://dali.tian-w.cn/Article/details/gtmansuknd.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jlsjyb.cn/Article/details/gtfhnbwifd.html

PHP:  array_reverse($arr);
来源：http://dali.sufxvd.cn/Article/details/gtaglpxvgq.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.cdnleiting.top/Article/details/gtdgcsmdqk.html


<!-- 参考信息 -->