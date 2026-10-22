代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtytodecjc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtywoosuub.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuanzx.com/Article/details/gtwdbrrkuq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtilfryuwm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtbevjnang.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzysfrulk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gtqjnozzur.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ehwqpu.com/Article/details/gtkwfasalx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigfzy.top/Article/details/gtcgzourqx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtlkccwqhc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hfpthk.cn/Article/details/gtridmzkox.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cqqwz.cn/Article/details/gtbcnwtsxd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gthrsjvmzm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtzcfuozvn.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhijiandao.cn/Article/details/gtbjjomjdk.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtbohylpod.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtoimhyzdd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnbhynqn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gtlztecnjc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gtljhembym.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtjvarzmpn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajotmjoh.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtcgzmfvlb.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtqhpyminv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtmnrkpxkg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtkjyoirnu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtvqwyvxlp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtsqosfrpg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtvmypxqlm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtcldqgojz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtazkhzvxj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.316326.xyz/Article/details/gtuzaxswli.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtbivtzkff.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtghoenghd.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gttergvawl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtoymwobeb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtclgfexiu.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gtalozcxui.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gthrqsmnpa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gtkzmvmkeg.html

C#:   x is int or double or decimal
来源：http://dali.chenlongwang.top/Article/details/gtgbcxnocv.html

[B14] 判断值是否在集合内
来源：http://dali.yonumen.top/Article/details/gtneuvgjzx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtnmlqdosu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtekrrwmor.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtjmnxmtws.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtgdidastc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtmejmrlxy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtuhfqytki.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtonahhwij.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttgiijfnt.html

[B15] 布尔运算与取反
来源：http://dali.quarkkingdee.top/Article/details/gtpjrfgsjx.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtkfujbbse.html

PHP:  $a && $b || !$c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvllgcsw.html

JS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gthehfqkps.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtiqnghccf.html

Java: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtiusdddyg.html

Go:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtwetcmjcn.html

Ruby: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtjauaxdwr.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtjxvzahvb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtokoyzehb.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gtcximhhmu.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gtaxjhemje.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtwxkkafmz.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtymhblrdu.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtraywxkmq.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gttcnixnur.html

Ruby: return if data.nil?
来源：http://dali.hnxiangtu.top/Article/details/gtsszyygst.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gttncxamfy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtgakfvdes.html

C. 函数与作用域
来源：http://dali.ppjwa.cn/Article/details/gtwggpltef.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtzoyxgday.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtjnagcrij.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtpekoiyiw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtevrfbpvf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtuiakrolq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtfthbhxkt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtanpnlaad.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtnzqmfezc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtdtmowrjk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtljktjxvx.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtdduixnuo.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtmanpsdnn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtjnfkmjpd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.vqdsnc.cn/Article/details/gttzneyawn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqfxgqrn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtyltangcq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtouazqbcl.html

Ruby: def greet(name = "World") = name
来源：http://dali.jqgfzy.top/Article/details/gtjndxqsuh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gtqrkguxwh.html

[C03] 可变参数
来源：http://dali.meibo888.top/Article/details/gtdtaedblu.html

Py:   def total(*args): return sum(args)
来源：http://dali.ydzc1.top/Article/details/gtajpmkaul.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtdcweagcp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtuoshtywg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtkfdswu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hongshengwenyu.top/Article/details/gtaplreewd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtlclmisxs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.mhx1999.top/Article/details/gtzwtjbmhr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtrkvsfmxf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.wangdashe.top/Article/details/gtrzkjqpbt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtddaggjdl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtfxqrmgvp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtjmrxctiz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtyfusbxgi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gtffmayvss.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtccfkirdx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtxyvpxfxn.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtakiuyawu.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtpvyklaqz.html

Py:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gtxczhsxdj.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzdfwacd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtuttefgjl.html

TS:   return { a, b };
来源：http://dali.cheryme.top/Article/details/gtyxjsajce.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gttnkwvlfz.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gthhpepshy.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtfblympnl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtylmlfupe.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtgezwzjxc.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtonahudwi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtqjjcklfx.html

JS:   const square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtimmvgdao.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtczzmmmfz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtartkmkap.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yueranfly.top/Article/details/gtcqwyuvoc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zdqjudy.top/Article/details/gtnfnvdczk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtvachxxej.html

[C07] 把函数作为参数传入
来源：http://dali.hywenlv.cn/Article/details/gtxxmtghhs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ivvv.top/Article/details/gttumbsmhs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gtyvmcwewi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.gotoacloud.top/Article/details/gtntjoxkyy.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtxwnyjzeh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gtndjkxdhg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yueranfly.top/Article/details/gtssgjvhht.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttyktlwhv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hnqzz.top/Article/details/gtwmyxymvx.html

[C08] 闭包
来源：http://dali.sxryk.cn/Article/details/gtwrqagogu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtjxmxkfai.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yangfankeji.com/Article/details/gtemlnwwby.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gttwwqimfx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtxankcfnz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guannengcc.top/Article/details/gtunnfbzei.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gttebxjszs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tianlin.xyz/Article/details/gtfwdvswqr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtarcdufqa.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gtnokaixgy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtvtlegdhc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tanke756.top/Article/details/gtcdqxubas.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dashuyun.cn/Article/details/gtqkytrkhh.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtogvundiu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtxfpjnqgo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtxfmpiymk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtgpatqsyc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xziqi.cn/Article/details/gtihlhdmdl.html

[C10] 变量作用域
来源：http://dali.shzxlz.cn/Article/details/gtglwsznvb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtlligpuab.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxglsyqv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtbxfswrut.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gtdbqabovl.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbefmvxey.html

Go:   花括号块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtbswzbnqn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gttakkftpx.html

C#:   块级作用域
来源：http://dali.0kj1m.cn/Article/details/gtmpfbsydo.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gtdeellybb.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtwrgfcsuk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtjpuiopki.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gtdwfnzsds.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.meibo888.top/Article/details/gtfvepnhgs.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gtijmavwlp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gteejowakj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtyrxpotwt.html

C#:   using System.Text;
来源：http://dali.yj202588.top/Article/details/gtchfhvsnd.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqvjrheyx.html

Py:   (lambda: print("run"))()
来源：http://dali.feifeiyinyue.top/Article/details/gtqqebuizc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtqqqwojfm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gttjhktlqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtzitprbkg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtppepwjex.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtirtxzwcz.html

Ruby: -> { puts "run" }.call
来源：http://dali.shuidangran.top/Article/details/gtysuniwlh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtmnauakra.html

[C13] 类型声明 / 类型注解
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiltfiah.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gogol.net.cn/Article/details/gthleqelig.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtjktoptyj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gtgqsrgqzl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtkzobcvel.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtzeblzocl.html

Go:   func add(a, b int) int
来源：http://dali.xuanzx.com/Article/details/gtewlcqwna.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.aizwys.cn/Article/details/gtymaqznqp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gthdgojmid.html

[C14] 泛型函数
来源：http://dali.snrcjt.cn/Article/details/gtdrfgpxdh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gthdnlokxm.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtwiektkwx.html

JS:   // 无泛型
来源：http://dali.tian-w.cn/Article/details/gtteftqyvl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtwjnzflne.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtldlucska.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gtecpwezwr.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtoembdufe.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtqlbwbyfw.html

[C15] 解构 / 展开参数
来源：http://dali.nanxuanxn.top/Article/details/gtmjvnwunf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258.top/Article/details/gtduvebcsd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtqpoujpqh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtuiunjcjr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtxwkwzerl.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gtxlumcprq.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtbmlinmcr.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtlnzlrtvd.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtxuoqkcwv.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gtnaeouvof.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinqigufen.top/Article/details/gttrdnmjqe.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gtuybglaas.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuanzhike.top/Article/details/gtfnynteyo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shangyingyoupin.top/Article/details/gtwlhcrydf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtsbeahscy.html

Go:   // 无重载：用不同函数名
来源：http://dali.tianlin.xyz/Article/details/gtrqdlunoc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdbiohdx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzugvazi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtyhibvgoy.html

D. 数组 / 列表 / 集合
来源：http://dali.yongpay.top/Article/details/gtnlbazcur.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtecivlbjo.html

[D01] 创建数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtsjtkcqtk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.0kj1m.cn/Article/details/gtmvdmfmod.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwxprwmg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuxming.cn/Article/details/gtvihlvyaq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gogol.net.cn/Article/details/gtuvvfonuh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shangyingyoupin.top/Article/details/gtcbuduauw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtqetjnewr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtuhshmozv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtzsgkgszs.html

[D02] 追加元素到末尾
来源：http://dali.yj20258.top/Article/details/gtqduczuxi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gtqosuezji.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaflirafw.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtzaoezusd.html

TS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtbszmpzjk.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtffgwcpbp.html

Go:   arr = append(arr, 4)
来源：http://dali.jinqigfzy.top/Article/details/gtzdaywicn.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtgibstfrx.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gttgdpcodj.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtlyqdhlgf.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtsledxhwn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtutkizneh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tianlin.xyz/Article/details/gtnatekgod.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.bjfxy.top/Article/details/gtskghvnlh.html

Java: list.add(0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtbzdljbvl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gthawswkta.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hywenlv.cn/Article/details/gtbgsypwjm.html

C#:   list.Insert(0, 0);
来源：http://dali.andypj.xyz/Article/details/gtaxpyjjeq.html

[D04] 删除元素
来源：http://dali.ybcxt.top/Article/details/gtotznfviz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.havefunace.top/Article/details/gtkafpunvs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gticbyvjuj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtjctaccbh.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveoxnuip.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.sxryk.cn/Article/details/gtprekrufk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dianchejie.cn/Article/details/gtriiumcve.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yanxiufei.cn/Article/details/gtvtoaundb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtpkptuxxt.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtrayjpkgb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gtqiaovjuz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtumemozqt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gtboefbziu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258888.top/Article/details/gtevxszxhz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtgwpgjhbx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtpphzctpg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinghuilouyu.cn/Article/details/gtacklhhie.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.kuanghao11.cn/Article/details/gtmdaycqhq.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtuzlfmuiy.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gttjoohdih.html

PHP:  count($arr);
来源：http://dali.birdmap.top/Article/details/gtdzhqpfki.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtgcyvhwpq.html

TS:   arr.length
来源：http://dali.daxiang520.top/Article/details/gttwhamxcs.html

Java: list.size();
来源：http://dali.chenzaomai.com/Article/details/gthaouuxdj.html

Go:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtsohsspoq.html

Ruby: arr.length; arr.size
来源：http://dali.hnxiangtu.top/Article/details/gtsaonyklq.html

C#:   list.Count;
来源：http://dali.xuetiantiany.cn/Article/details/gtxcgezwkj.html

[D07] 切片 / 取子数组
来源：http://dali.cashguo.top/Article/details/gtnvezfbvr.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtblowfvqa.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.guannengcc.top/Article/details/gtcjhoywzh.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvwmhoct.html

TS:   arr.slice(1, 4);
来源：http://dali.ppjwa.cn/Article/details/gtunamuxqy.html

Java: list.subList(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuyobglzp.html

Go:   arr[1:4]
来源：http://dali.jinqigfzy.top/Article/details/gtoymjhvtf.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtjbfhqdvz.html

C#:   list.GetRange(1, 3);
来源：http://dali.quarkkingdee.top/Article/details/gtkzlswmtr.html

[D08] 合并两个数组
来源：http://dali.cashguo.top/Article/details/gtzfebqzbp.html

Py:   a + b;  a.extend(b)
来源：http://dali.chenjidiqi.icu/Article/details/gtxwujqrjb.html

PHP:  array_merge($a, $b);
来源：http://dali.ivvv.top/Article/details/gtpfcbnqsy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jinghuilouyu.cn/Article/details/gtviciywcq.html

TS:   [...a, ...b];
来源：http://dali.shuidangran.top/Article/details/gtxbcgsydx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthezksakf.html

Go:   append(a, b...)
来源：http://dali.zhixingplan.top/Article/details/gtnfjirwka.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtustuggyp.html

C#:   a.Concat(b).ToList()
来源：http://dali.birdmap.top/Article/details/gtjemjgafb.html

[D09] 排序（升序）
来源：http://dali.chenzaomai.com/Article/details/gtlfkmgdev.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.bjfxy.top/Article/details/gtreoqhpsp.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtwytnxqph.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.shangyingyoupin.top/Article/details/gtclykxswn.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtflvrnxns.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hnxiangtu.top/Article/details/gtcevuaghw.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.jinqigufen.top/Article/details/gtvdlskgws.html

Ruby: arr.sort
来源：http://dali.daxiang520.top/Article/details/gtelorlwur.html

C#:   list.Sort();
来源：http://dali.xylfe.cn/Article/details/gtcvswfelo.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.shanyushiyangtech.top/Article/details/gtyvtsbmnx.html


<!-- 参考信息 -->