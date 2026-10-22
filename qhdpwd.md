代发 wailian999

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gtlzxqjaxq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtznuuiscw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbwscgky.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtaeijfckv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtxigwidkf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtevcnkaux.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtbnthsqjv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.wangshuangyany.cn/Article/details/gtvrpghopx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gthptudfdm.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkddiozh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hongshengwenyu.top/Article/details/gtkygqrhjv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpowbnxlf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtuxdspkrl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gtmqxywyzj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtvmsonftz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gtgogphasp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fzhhl.top/Article/details/gtkexofqkl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtpzrmmruj.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtsryyvuse.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtqhjydujr.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtszmmnqux.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtkakijacy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtfeqdoioj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtrfavflwf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiupmkia.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtfzrmxnwr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gtmnrwfdvd.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtfcctnjgz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtetlchsjb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fzhhl.top/Article/details/gtqrqbemyz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtkpembygj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtbowdekjx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtlcttiysi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daxiang520.top/Article/details/gtuvhwuzwi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtkzqjjduf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.bjfxy.top/Article/details/gtvxiordlf.html

[B13] 判断是否为数字
来源：http://dali.yvedp.cn/Article/details/gtqcqrxkef.html

Py:   isinstance(x, (int, float))
来源：http://dali.pengpengdd.cyou/Article/details/gttsqhuupk.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtukwcvwks.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtbipqsuiu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtzrbqpyyv.html

Java: x instanceof Number
来源：http://dali.jinghuilouyu.cn/Article/details/gtlbazgnsm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtxhfhwfvg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.redwolf501.top/Article/details/gteacdioga.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtvvvergyx.html

[B14] 判断值是否在集合内
来源：http://dali.svipenyu.cn/Article/details/gtcwnqyaob.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gtgincuhqd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hammf.cn/Article/details/gtggbtwmki.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtxivkmfgu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtlbxvrdod.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gtvrsehmrd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gtmymcyscb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.kuanghao11.cn/Article/details/gtnulhhgyq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sufxvd.cn/Article/details/gtbyyztxhg.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtateobwtq.html

Py:   a and b or not c
来源：http://dali.gaohongyu789.top/Article/details/gttvekfyjr.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtifidfopg.html

JS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtlyyscfzq.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtjsgkzyag.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtiofbpewz.html

Go:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtlajddwyu.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtujifxnox.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtaywevast.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtmexuhxxo.html

Py:   if not data: return
来源：http://dali.kuanghao11.cn/Article/details/gticyeepld.html

PHP:  if (!$data) { return; }
来源：http://dali.havefunace.top/Article/details/gtblzpqjtc.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbbppqcdw.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtyjakrkrb.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gtsehbyckb.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdfvnhsd.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtkeahudtq.html

C#:   if (data == null) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqjteiua.html

================================================================================
来源：http://dali.sweek.top/Article/details/gttowyulmn.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtccusrolm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gthkokegta.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtvzisfgrr.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gthqbbzphz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttrhfuawh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtrwotlipc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtugvqsqdl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtxphpkpfo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fengsongda.top/Article/details/gtlposccua.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gtdqzrowmu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtilzpoypl.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtjbdwmgux.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtnrpqbema.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shuidangran.top/Article/details/gtwoyhwkdm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtjtyifhhu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtfnbiruio.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtjdbtsnst.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtxllgfwzz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258.top/Article/details/gtjcnamfik.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtwimwezwp.html

[C03] 可变参数
来源：http://dali.feifeiyinyue.top/Article/details/gthllazjdd.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gtdfhodlew.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtffdughcp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sysykeji.top/Article/details/gtizwtifru.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtfdlmsseg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtxwihrefi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gtdborwton.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtgiegokzr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gtczozecln.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gaohongyu789.top/Article/details/gtbjiafuqt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtndcnsiks.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtfuqlcfnq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gtypbymstq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gtnxznddqt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gtbfmqbgvj.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gteqaaenjy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtjpumvwwc.html

C#:   f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtiswujurm.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtvkqhaxhb.html

Py:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvwolqim.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gthbnnhyeo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtkkfmonoq.html

TS:   return { a, b };
来源：http://dali.zycfv.cn/Article/details/gtqbkmfrsc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtmyltwowb.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtuyvdvgwp.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtedbkygai.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sxryk.cn/Article/details/gtjndfyoyb.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtbihrjiyo.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtqrncwvgt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtweugfesc.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorzkopzx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtgbvbahqr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gttcozgkkv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gtboyfncwe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtdeqlfkhp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtnvfnxkti.html

[C07] 把函数作为参数传入
来源：http://dali.vqdsnc.cn/Article/details/gtmttozzgw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtbdjgoynw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtceflupud.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.havefunace.top/Article/details/gtrvegoytl.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtcwgllxgr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gtooijceab.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guowangkeji.top/Article/details/gtckrnuzhm.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gttkcpctnj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guannengcc.top/Article/details/gtrzrznoce.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtgvjjpwav.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtzzrfwslz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfkpifmcl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtwvmssymk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtgfhhuehl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtlfxnxqle.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pengpengdd.cyou/Article/details/gtqlzwghdo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gtrwxuygit.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtfusujmmd.html

[C09] 递归
来源：http://dali.yj20258888.top/Article/details/gtigfvxoiv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtpunvdanl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtwxieadto.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gtqpxerjuu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtrbjivvho.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtzlldqbvb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjlsjtphj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtvgczbaor.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gtqdcljqbh.html

[C10] 变量作用域
来源：http://dali.tianlin.xyz/Article/details/gtkqwdeolk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aizwys.cn/Article/details/gtyavossmx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtsgufaeob.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtqggymqua.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtfvpesobp.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gtfcidpbxj.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtjvmhcrbl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuanzx.com/Article/details/gtlpezibfq.html

C#:   块级作用域
来源：http://dali.yonumen.top/Article/details/gthvwdbcvp.html

[C11] 模块导入与导出
来源：http://dali.snrcjt.cn/Article/details/gtyvdarfmu.html

Py:   from module import func
来源：http://dali.yueranfly.top/Article/details/gtahyiuoqs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtfopgqgrz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtueejxkqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.guannengcc.top/Article/details/gtaidpeyoj.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtrmlznbmw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gtyepprzhp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtuuvbnhsk.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtttysllaq.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gtifsqdmbz.html

Py:   (lambda: print("run"))()
来源：http://dali.xuetiantiany.cn/Article/details/gtzemncpjz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gogol.net.cn/Article/details/gtdfgadalh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gtfwehcjoo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtxvrarvox.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhongyouzk.top/Article/details/gtohczhvwk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xinyue.icu/Article/details/gtaniqphoe.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gtzovmzwph.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zycfv.cn/Article/details/gtcdfmfioa.html

[C13] 类型声明 / 类型注解
来源：http://dali.vqdsnc.cn/Article/details/gtjhinkwgm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtracewpaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gthpzftvon.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtkbzxmlof.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtbknwqszb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtduuazdsf.html

Go:   func add(a, b int) int
来源：http://dali.smart0.xyz/Article/details/gtjdtodzmr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangshuangyany.cn/Article/details/gthedmjyeo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtjruezhmz.html

[C14] 泛型函数
来源：http://dali.xuetiantiany.cn/Article/details/gtsinxcvha.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuanzhike.top/Article/details/gtgziifhkk.html

PHP:  // 无泛型
来源：http://dali.yj20258888.top/Article/details/gtvvyexpaw.html

JS:   // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtcxmzridi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtubyfsrxw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtzcqnhvif.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gthslvdqtv.html

Ruby: # 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtqsovfzkz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtawxyayob.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtgxbmkswh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.bjfxy.top/Article/details/gtgtikskvo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gtlqqvriyh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtfddnjyhl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gttwqelvuh.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtnrdmeaol.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtjqlshwag.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gtidjeqiyd.html

C#:   var (a, b) = pair;
来源：http://dali.hnxiangtu.top/Article/details/gtjrzkblcb.html

[C16] 函数 / 方法重载
来源：http://dali.ppjwa.cn/Article/details/gtoktuwmrr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ybcxt.top/Article/details/gtzzllmanc.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtdbmrhhty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ivvv.top/Article/details/gtsbybtjhw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.chenlongwang.top/Article/details/gtnqzlzywf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sufxvd.cn/Article/details/gtdcitjtny.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtesumbbrr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtvtwgsaae.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cashguo.top/Article/details/gtdwregktn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtatsrrhqy.html

D. 数组 / 列表 / 集合
来源：http://dali.jlsjyb.cn/Article/details/gtfdisgwls.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmaueczbe.html

[D01] 创建数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtpfyozzci.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtcqfmsara.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gttwnpapjo.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtpojxwsqc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.mhx1999.top/Article/details/gtacjiwgfq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtuprbsufj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtvfhastel.html

Ruby: arr = [1, 2, 3]
来源：http://dali.andypj.xyz/Article/details/gtaeskmqpg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhiwuduotai.top/Article/details/gtgyhjmobp.html

[D02] 追加元素到末尾
来源：http://dali.zhengqikj.top/Article/details/gtznqcqdlw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.redwolf501.top/Article/details/gtofaeghjv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnqzz.top/Article/details/gtqalqvdjp.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtybpijqjg.html

TS:   arr.push(4);
来源：http://dali.nanxuanxn.top/Article/details/gtpvxglyhq.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtgpptmutq.html

Go:   arr = append(arr, 4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgobmamb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj202588.top/Article/details/gtbyzyazta.html

C#:   list.Add(4);
来源：http://dali.sufxvd.cn/Article/details/gtddulmjfz.html

[D03] 在指定位置插入元素
来源：http://dali.yj20258888.top/Article/details/gtptjfhvcs.html

Py:   arr.insert(0, 0)
来源：http://dali.shzxlz.cn/Article/details/gtdlltjdae.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.svipenyu.cn/Article/details/gtamhayaqz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sysykeji.top/Article/details/gtaltthswx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtfmqhbruc.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtnubfcvwi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hammf.cn/Article/details/gtezvextdd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shangyingyoupin.top/Article/details/gtuqhupigg.html

C#:   list.Insert(0, 0);
来源：http://dali.jyoumei.cn/Article/details/gtfqufyzdc.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtlusacvkb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gtrwlhwyvi.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shuidangran.top/Article/details/gtjpfimwnr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtotzhtomp.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gtytsxmfie.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jianghu66.top/Article/details/gtetpejzec.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gtzlfvbezz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtphujagbz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yj202588.top/Article/details/gtiokydhnl.html

[D05] 访问与修改元素
来源：http://dali.zhijiandao.cn/Article/details/gtpktlfmbq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtdzpjmpfd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.haohaochexian.top/Article/details/gtcqsqyatf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtdqxbxzxd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtnldzkgbz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.9152youxi.cn/Article/details/gtreapehyj.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gttmusdozw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gzhubu.top/Article/details/gtzardqsmi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtgqrvhtrc.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtcmjgnjtu.html

Py:   len(arr)
来源：http://dali.xziqi.cn/Article/details/gtrnzhrsvf.html

PHP:  count($arr);
来源：http://dali.9152youxi.cn/Article/details/gtsujnyxrd.html

JS:   arr.length
来源：http://dali.smart0.xyz/Article/details/gtqebdipgh.html

TS:   arr.length
来源：http://dali.shuidangran.top/Article/details/gthijnwjbq.html

Java: list.size();
来源：http://dali.hongshengwenyu.top/Article/details/gtygfadiok.html

Go:   len(arr)
来源：http://dali.cqqwz.cn/Article/details/gtuucnofki.html

Ruby: arr.length; arr.size
来源：http://dali.xziqi.cn/Article/details/gtuxolrpnk.html

C#:   list.Count;
来源：http://dali.ybcxt.top/Article/details/gtcpcthmud.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtfqqjceja.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.tianlin.xyz/Article/details/gthnmhwefj.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jianghu66.top/Article/details/gtfhevukeu.html

JS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gtdethatgq.html

TS:   arr.slice(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gtgitkycry.html

Java: list.subList(1, 4);
来源：http://dali.fzhhl.top/Article/details/gtlkbptimb.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtvgeyvpaw.html

Ruby: arr[1, 3]
来源：http://dali.iojbl.cn/Article/details/gtbsfdohti.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtfaunihzb.html

[D08] 合并两个数组
来源：http://dali.tian-w.cn/Article/details/gtfmazxdha.html

Py:   a + b;  a.extend(b)
来源：http://dali.aibaodan.cn/Article/details/gteyfvcshm.html

PHP:  array_merge($a, $b);
来源：http://dali.havefunace.top/Article/details/gtvfirxyqy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj20258.top/Article/details/gtoddybond.html

TS:   [...a, ...b];
来源：http://dali.dashuyun.cn/Article/details/gtmcwrwlrp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.nanxuanxn.top/Article/details/gtpwjuwxep.html

Go:   append(a, b...)
来源：http://dali.tian-w.cn/Article/details/gtiukgndfn.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gaohongyu789.top/Article/details/gtrmxyfixh.html

C#:   a.Concat(b).ToList()
来源：http://dali.yangfankeji.com/Article/details/gtgmzokfiq.html

[D09] 排序（升序）
来源：http://dali.smart0.xyz/Article/details/gtbkqrnnpt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shangyingyoupin.top/Article/details/gtzrntillr.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gthlscbhps.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jqgfzy.top/Article/details/gtylepsuqm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yuanzhike.top/Article/details/gtzirgizch.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gtmxwgcupf.html


<!-- 参考信息 -->