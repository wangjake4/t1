代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.9152youxi.cn/Article/details/gtjphxssdx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtjyjmetgt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtgflhcluv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gtmssjqqff.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zycfv.cn/Article/details/gtdxlvgnmp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyktjawlu.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gteoimiipq.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gtdxkqyeqc.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtxggfgpnk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtshxofv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtyhhhfdzg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gthazllfcg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gtgnypphhf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtjivhxbzv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gtzdfhbhxl.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtdbkokkyr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtnpmgyeli.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtdsojywha.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtfblkrjot.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtlgpzddtk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtbsuitrqk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gttmdjqhef.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gtxvzlanbp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gtreitjcpl.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtisuhzwhx.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gtbdpkgibo.html

PHP:  is_numeric($x)
来源：http://dali.fzhhl.top/Article/details/gterevhxvp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtykjjckwp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gttcnebmwj.html

Java: x instanceof Number
来源：http://dali.smart0.xyz/Article/details/gtkrnhpszh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zdqjudy.top/Article/details/gthefuamew.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtmlsjedqt.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdhyorujb.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtbigvicxa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gtbplvmjgk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqsbakzk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtgkmsfvmc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigufen.top/Article/details/gtwcelgcyb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtugekbhwt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gtbtiqlzay.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtcrbcwitd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtxcupefou.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtbfexdgus.html

Py:   a and b or not c
来源：http://dali.hammf.cn/Article/details/gtubttetoh.html

PHP:  $a && $b || !$c
来源：http://dali.meibo888.top/Article/details/gtzznfhrwc.html

JS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtsuxivtib.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtpanwjlln.html

Java: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtrwkpvegp.html

Go:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtsrorxduk.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtdfmfvfpk.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtwihgmjcd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gtxjvkpqou.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gtbumdejwq.html

PHP:  if (!$data) { return; }
来源：http://dali.tian-w.cn/Article/details/gtdvipqowy.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtkzuzorsu.html

TS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtlwwuabqr.html

Java: if (data == null) return;
来源：http://dali.yuanzhike.top/Article/details/gtkwqolnlf.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gthfzmyfya.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtxgxzfgpd.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtcyuiqwzb.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsvtkwztq.html

C. 函数与作用域
来源：http://dali.yonumen.top/Article/details/gtbaezgbfn.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmkqwoxom.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtutpmmplw.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtxmvonteu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtqpfnobfs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtmcublxmh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gtbslropnf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gthnuflwli.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yanxiufei.cn/Article/details/gtpcnnvufh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtwhvpilnr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtpjizncfz.html

[C02] 默认参数
来源：http://dali.mhx1999.top/Article/details/gtzqjfityd.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtggtdnizq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqvzzhaft.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtsyfawgxp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtdpktrfpi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtmcfgtojt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guowangkeji.top/Article/details/gtemfsyqxo.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtbabuxbqi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtcqdklste.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskshhpzc.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258888.top/Article/details/gtrjynopcf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtlybkegpp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtbrifaani.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gtsbgvgnbl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtrwsrpaie.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtgwuvbstw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtxqaojsmj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtwxdtgwxc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gthonigyqd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxqtwfbj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtzclxlgsg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtwuwjehql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtpvengpjs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenjidiqi.icu/Article/details/gtujuqixfz.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuanzhike.top/Article/details/gtvoxdrbmb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gteokobbga.html

C#:   f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtvcnhbrcm.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtjaifftsb.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtobhusytv.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtsgbtqava.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtwvvsarhi.html

TS:   return { a, b };
来源：http://dali.hysaishi.cn/Article/details/gthasgvuac.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtqzpoiswd.html

Go:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtcoyioebw.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gtdtxqglzs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtogtllvrp.html

[C06] 匿名函数 / lambda
来源：http://dali.hammf.cn/Article/details/gtqsexkzdz.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtqcdhhtud.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtoqmxmvpq.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtcdbvraxt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtfzhjsndo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtbreijzqa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cheryme.top/Article/details/gtbzysraql.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtrajkifhz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtwcwrekmz.html

[C07] 把函数作为参数传入
来源：http://dali.gzhubu.top/Article/details/gtrwlwjalr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtazipilqx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxuanxn.top/Article/details/gtkvvpksgi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gtwtyfjbrz.html

TS:   arr.map(String)
来源：http://dali.yj20258.top/Article/details/gtiigsifme.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtvwjlrfzv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtqkapouhh.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtscjxqrmy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gotoacloud.top/Article/details/gtecrrcsih.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gtgrhcvwqr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tanke756.top/Article/details/gtdvpsflta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtsuhilonf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtgaanbpns.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtkizwuleh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtrmuurnbv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fzhhl.top/Article/details/gtcfkgtbms.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoeegonkq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtlarphhfg.html

[C09] 递归
来源：http://dali.svipenyu.cn/Article/details/gthpyjmhhs.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.smart0.xyz/Article/details/gtvzlngeyz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtfwebtiud.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtfypfweuy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtazxyedud.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtmxgbutxe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jlsjyb.cn/Article/details/gtvrneyolt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtmitubjgt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hfpthk.cn/Article/details/gtwkrficyl.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtxpobqhsp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtghrzczsk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gtvmrfwwvf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtiklbspcm.html

TS:   同 JS
来源：http://dali.fengsongda.top/Article/details/gtmhbzbinn.html

Java: 方法内为块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtxrzjxkex.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gthcwlxdbj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gtqgagiszw.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtfnjaccfs.html

[C11] 模块导入与导出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmlykpoo.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtnugkzcqc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtsyaqtqfw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cdnleiting.top/Article/details/gtonvmuyoz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gtvcyjagag.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gthohzangl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtubwwyzzq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gotoacloud.top/Article/details/gtzapdpvni.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtdyeclsyr.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtyuzoqetc.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gthobjlndy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnxiangtu.top/Article/details/gtzaykgovt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtzdsgsjpd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtfgaqxbtv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gtvtwobukx.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxzhyxsll.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtbpvbcfvv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.svipenyu.cn/Article/details/gtgizdjiow.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtvsejldwb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cqqwz.cn/Article/details/gtljduuwmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtmwhcrcpv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gtcoxmjfyh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtgbuvjcpn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtopcpegei.html

Go:   func add(a, b int) int
来源：http://dali.ppjwa.cn/Article/details/gtotaknozy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gttssmiepj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258888.top/Article/details/gtfmkbujoq.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtocgijzrl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xylfe.cn/Article/details/gtlijpoczi.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtdehvwyze.html

JS:   // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtkygkvudk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gttkrdybbv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtirjnxlqb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnspjjrbt.html

Ruby: # 无泛型
来源：http://dali.zhiwuduotai.top/Article/details/gtubintigc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cdnleiting.top/Article/details/gttjmtxxic.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gttgvehnvu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtpcpsgido.html

PHP:  [$a, $b] = $pair;
来源：http://dali.svipenyu.cn/Article/details/gtwmzfyxvs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnoavebu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gtufwdkloe.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtlcezuqad.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtnbqbwyyv.html

Ruby: a, b = pair
来源：http://dali.birdmap.top/Article/details/gtedkdewta.html

C#:   var (a, b) = pair;
来源：http://dali.smart0.xyz/Article/details/gtryewspuj.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gtvlbavwze.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gteleuuiah.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtufpfutxb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yvedp.cn/Article/details/gtbdzyuvtn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtinyniihc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gttgntvjcm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcyncuvaa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yj20258888.top/Article/details/gtwcfiliky.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtzmcfvtaw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkfdmchdq.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtvcnqwcxl.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttbafepbs.html

[D01] 创建数组 / 列表
来源：http://dali.316326.xyz/Article/details/gtnmykhcpr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtidipttfy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.316326.xyz/Article/details/gtbpieanws.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.nanxinkj.top/Article/details/gtmjjdarms.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yanxiufei.cn/Article/details/gtvjqvcczd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pycfn.com/Article/details/gtvifjxlcl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hysaishi.cn/Article/details/gtkiberwgh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtzehappro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gtbyupqbpg.html

[D02] 追加元素到末尾
来源：http://dali.fzhhl.top/Article/details/gtgapwzsyr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jianghu66.top/Article/details/gtwvpcyumx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ivvv.top/Article/details/gtmgylrenk.html

JS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gthqqzykov.html

TS:   arr.push(4);
来源：http://dali.guowangkeji.top/Article/details/gtaowxprqr.html

Java: list.add(4);
来源：http://dali.cashguo.top/Article/details/gtyjfoxfxe.html

Go:   arr = append(arr, 4)
来源：http://dali.yongpay.top/Article/details/gtmeirkcmr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hammf.cn/Article/details/gtiobyyswc.html

C#:   list.Add(4);
来源：http://dali.tian-w.cn/Article/details/gtpgnjleus.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtdyikurzj.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtlmbxrjfa.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gtpohhmxyc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtyiqekpxm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxixynxy.html

Java: list.add(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtewxztdif.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtvebxofdg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hongshengwenyu.top/Article/details/gtzmwdiyxs.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtovwwowin.html

[D04] 删除元素
来源：http://dali.yj20258.top/Article/details/gtyzkxvwwz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gthbwwbrpx.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hnqzz.top/Article/details/gtuzdqiips.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtbhrtprrw.html

TS:   arr.splice(0, 1);
来源：http://dali.birdmap.top/Article/details/gtgrvshchf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtschrsoty.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.snrcjt.cn/Article/details/gtatzofxvy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.dianchejie.cn/Article/details/gtxhivbehd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hfpthk.cn/Article/details/gtvkutivhb.html

[D05] 访问与修改元素
来源：http://dali.gotoacloud.top/Article/details/gtedlfbhyt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtdjvifafi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hammf.cn/Article/details/gtyobcdatk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.c1oappe.top/Article/details/gtxwqscqee.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yangfankeji.com/Article/details/gtgfuskaei.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cucudq.cn/Article/details/gtzezuqmev.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtvywjlcrj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gtlgylixwy.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.ivvv.top/Article/details/gtxosxfruk.html

[D06] 数组长度
来源：http://dali.yueranfly.top/Article/details/gtzjzvcwwj.html

Py:   len(arr)
来源：http://dali.zhiwuduotai.top/Article/details/gtgguzglyp.html

PHP:  count($arr);
来源：http://dali.jyoumei.cn/Article/details/gtguairjbc.html

JS:   arr.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvrlooqsu.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtuzvedggl.html

Java: list.size();
来源：http://dali.hnxiangtu.top/Article/details/gtxfbqpbot.html

Go:   len(arr)
来源：http://dali.cheryme.top/Article/details/gttbhpgtau.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtqkxfsxra.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtmmwxefmz.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gttxfsamzi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.fzhhl.top/Article/details/gttervhggh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjddlpfv.html

JS:   arr.slice(1, 4);
来源：http://dali.yangfankeji.com/Article/details/gtyyhbfrwl.html

TS:   arr.slice(1, 4);
来源：http://dali.gzhubu.top/Article/details/gtdvzvcyhg.html

Java: list.subList(1, 4);
来源：http://dali.smart0.xyz/Article/details/gtqouczzvn.html

Go:   arr[1:4]
来源：http://dali.hnxiangtu.top/Article/details/gtygjjnhfd.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gtkrdvvdhj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwvyjbkmt.html

[D08] 合并两个数组
来源：http://dali.yuanzhike.top/Article/details/gtkhhvcjok.html

Py:   a + b;  a.extend(b)
来源：http://dali.svipenyu.cn/Article/details/gtptltlmyy.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxuanxn.top/Article/details/gtuxmucsfa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.chenlongwang.top/Article/details/gtlafonose.html

TS:   [...a, ...b];
来源：http://dali.hammf.cn/Article/details/gtwzdldhcg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gtjrnngviy.html

Go:   append(a, b...)
来源：http://dali.andypj.xyz/Article/details/gtwomigqqk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.daxiang520.top/Article/details/gtwfjpqfme.html

C#:   a.Concat(b).ToList()
来源：http://dali.yj20258.top/Article/details/gtrbolgjmy.html

[D09] 排序（升序）
来源：http://dali.shzxlz.cn/Article/details/gtdxyikwxr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.wangshuangyany.cn/Article/details/gtkdzpsqak.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtyfnhauvl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhengqikj.top/Article/details/gtrojeepqx.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ydzc1.top/Article/details/gtltxqrpab.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.9152youxi.cn/Article/details/gtnghpjisk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.gogol.net.cn/Article/details/gtgkthyrpy.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtnnjvvmvy.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtqvjuzgim.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtcfqwhtpf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.ehwqpu.com/Article/details/gtkxxfzcsb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjonqhwzj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.shanyushiyangtech.top/Article/details/gttaofkexg.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.pengpengdd.cyou/Article/details/gtxqbmnxoa.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.yvedp.cn/Article/details/gtgjnjxhat.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cucudq.cn/Article/details/gtooasfgzz.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.guannengcc.top/Article/details/gtpcaomczh.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.yanxiufei.cn/Article/details/gtyrruyhrp.html


<!-- 参考信息 -->