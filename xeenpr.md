代发 wailian999

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtxkvrdgpd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtbltiqkay.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtdocpvtbg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gthrxhnbot.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtazqmqwqh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtrahwgcmr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtdjfkeium.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.daria6918.cn/Article/details/gtmbjbbkcq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtdsqrjohm.html

[B10] 遍历同时拿索引
来源：http://dali.meibo888.top/Article/details/gtqkjyequt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenlongwang.top/Article/details/gtfkgyzcko.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gtrbkdxwpd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuncjklz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtfrnzotuv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtgeacoyey.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gtdhmyhlsg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cqqwz.cn/Article/details/gteynrckoa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gtbvqjalzi.html

[B11] 生成数字序列 / 区间
来源：http://dali.zdqjudy.top/Article/details/gtkgnrtouz.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtpwuhgusc.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gtvfugrmor.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtvbkjgmzu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtylkkggwc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gtahtnmvdi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gtaimotbln.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sysykeji.top/Article/details/gtzcvwnknl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtpfstehis.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gtfftzaefi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtkublsote.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zycfv.cn/Article/details/gtbrayzqvz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtcpkzuifx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtalgomnnl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtgdnvapub.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.0kj1m.cn/Article/details/gtxnsawoer.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenzaomai.com/Article/details/gtngtuxlpy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtbmaiesnn.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gtqtcmxdel.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gteenzmiiz.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtfojwlpbj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gttpeyqnas.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtaoxjwveg.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtimfwakdt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gtpcnxarti.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gtoybsffyc.html

C#:   x is int or double or decimal
来源：http://dali.feifeiyinyue.top/Article/details/gtxiagmwim.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gtxoaookgc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtcozzqxkw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhongyouzk.top/Article/details/gtunlxhzsm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbhvrowvk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gthamjftyn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtuomkwrgj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtnzqquqiw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtuqolgqyw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gtpqjbxapl.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gtpthkvrjb.html

Py:   a and b or not c
来源：http://dali.hywenlv.cn/Article/details/gtmojvdtbt.html

PHP:  $a && $b || !$c
来源：http://dali.guannengcc.top/Article/details/gtysvozivw.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtnraddgsz.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtwhmwudwo.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtljdzirga.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gttntlawsh.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtgqfykuey.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtbdlapqoi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtpkiwuffn.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gttebscysr.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gtliqaioue.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtruzdzpby.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gtynmtrviz.html

Java: if (data == null) return;
来源：http://dali.yj20258888.top/Article/details/gtiipotvvm.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtqnzrlywz.html

Ruby: return if data.nil?
来源：http://dali.iojbl.cn/Article/details/gtrbyaqjuk.html

C#:   if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtaidschzv.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtdaucfnfz.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtvwkksxve.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwiwpxmi.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtweqmcvep.html

Py:   def add(a, b): return a + b
来源：http://dali.snrcjt.cn/Article/details/gtupbarbnc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtxsvxxllp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtvoptmodl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtmdlgtmvi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtzwxhctry.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtsgoccupt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gtvqdjelah.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gturxkwfhp.html

[C02] 默认参数
来源：http://dali.jyoumei.cn/Article/details/gtsqagjtxx.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtzawfrlkq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tianlin.xyz/Article/details/gtclkefgvv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtlndlvjcq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtybjawzbi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtudbqmqfo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlekhtywd.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtywshpxes.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwlqvmfd.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrtjlumq.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gthklwqywq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cdnleiting.top/Article/details/gtfwjkpktk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtcfmjfhoj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtvdujkmju.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ivvv.top/Article/details/gtdksydklf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnecjsoub.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzrieojhi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtxefxrkdu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtjwdutlug.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtjxaxugrn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gtjpxehshz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gthffxudri.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtsxpgwpqq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtfepdamkh.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtmaktavol.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtcauklpfx.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gttnwjimkz.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtbfbzwyml.html

Py:   return a, b
来源：http://dali.0kj1m.cn/Article/details/gtfgiauamt.html

PHP:  return [$a, $b];
来源：http://dali.shangyingyoupin.top/Article/details/gtblxlvicn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtbgtbivhc.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtaalypafs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtzhclpozo.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtfsvfkyor.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gtnvedfknq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtkbjvlwji.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gtktblnqqp.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtcrsqjjhc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shangyingyoupin.top/Article/details/gtnwrdjhon.html

JS:   const square = x => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtfvjbetdh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtvjpcwmpy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.316326.xyz/Article/details/gtqsdumosk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hysaishi.cn/Article/details/gtzyxnkiby.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtckkukalo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtyzwnumja.html

[C07] 把函数作为参数传入
来源：http://dali.gotoacloud.top/Article/details/gtkfnjlntq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzvhitwn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.c1oappe.top/Article/details/gtkwfhngoz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtmiunumij.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtriqgvxkj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258.top/Article/details/gtlkupzjlk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtxbclwjuc.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gtvnkrdtiz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ybcxt.top/Article/details/gtccldgmbt.html

[C08] 闭包
来源：http://dali.hfpthk.cn/Article/details/gtovsboeeu.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtzhdcnxgt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtidrncfvi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gtbphgsgnn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqujzogxa.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gtdjpbowxl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.bjfxy.top/Article/details/gttfqfgjra.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yanxiufei.cn/Article/details/gtqshdiasd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtiwfkbfba.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtzwchuonh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.c1oappe.top/Article/details/gtwvjgtjbi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtxnqqeygq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.meibo888.top/Article/details/gtmfhzicui.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtbdbtgeio.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtciyskwvy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gtseowijlb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtoamgzgbf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtrymtqesl.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gtdejuxtvr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gtgkowxclk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sxryk.cn/Article/details/gtpmlzccja.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtojjnkodm.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtlhffalgl.html

Java: 方法内为块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtfzvnpuht.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtcrsqmzbs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aibaodan.cn/Article/details/gtnclxnndz.html

C#:   块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtyercnqcv.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtgdeacjvr.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtthtkswiu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.vqdsnc.cn/Article/details/gtjsruxtvb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gtgabuoyfk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtjmwijqms.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtsvbkbxwj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmohakcy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtoibvisso.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtzzyyezag.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuanzx.com/Article/details/gttiwdgwpt.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtfxlleoli.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkspazep.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtaaiifvym.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gtkacscrgi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ivvv.top/Article/details/gtwjxzdfpz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yvedp.cn/Article/details/gtuqyejamz.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtmbboudda.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pycfn.com/Article/details/gtozofvtdd.html

[C13] 类型声明 / 类型注解
来源：http://dali.c1oappe.top/Article/details/gtgjetcxip.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigfzy.top/Article/details/gtvnrmlinc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtfamvumsl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtlnsnplmr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtatyvybdj.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtxalotdkf.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gtmuzsgcut.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmxwbzok.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hfpthk.cn/Article/details/gtjolgdssu.html

[C14] 泛型函数
来源：http://dali.bjfxy.top/Article/details/gtqydyvxpa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtgnbmyyzj.html

PHP:  // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtrhtjbaga.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtkxpshiuh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.iojbl.cn/Article/details/gtsgheoxed.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gtbukiehfd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gtwtfduadi.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtivqjrxfz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtwscxwvfi.html

[C15] 解构 / 展开参数
来源：http://dali.yuanzhike.top/Article/details/gtugdhlvse.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jianghu66.top/Article/details/gtxdffdavo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.birdmap.top/Article/details/gtqxmkdlci.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gtzsqazsko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhengqikj.top/Article/details/gtcuhtlqqx.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtiiyksfmm.html

Go:   // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gtonqzcohp.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gtpsjirxbx.html

C#:   var (a, b) = pair;
来源：http://dali.ybcxt.top/Article/details/gtdwldgvdv.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gtnfftauii.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenzaomai.com/Article/details/gtknedaexs.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtgvbnnxly.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.mhx1999.top/Article/details/gtflltfoud.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sxryk.cn/Article/details/gtwnaxiofj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtqiroixzn.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtbknebqfp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbnwpytz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gtckzcxcrc.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtwdxkijyn.html

D. 数组 / 列表 / 集合
来源：http://dali.kuanghao11.cn/Article/details/gtjbqsthik.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtotktqwxm.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtmenyfhei.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtkkroemis.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtqsxzyeaw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenlongwang.top/Article/details/gtdsgbnqmf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gttupmbixp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.vqdsnc.cn/Article/details/gtorbutxes.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gttqwkpsin.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yanxiufei.cn/Article/details/gtuwbydidi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.haohaochexian.top/Article/details/gtvqmydtdd.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtqslhpbtw.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzabkymm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqhinxbpq.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gtgvfpdxym.html

TS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gthvnftfso.html

Java: list.add(4);
来源：http://dali.yvedp.cn/Article/details/gtlmkbetqe.html

Go:   arr = append(arr, 4)
来源：http://dali.wangdashe.top/Article/details/gtceuvxeqq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xuetiantiany.cn/Article/details/gtkxxcjfwp.html

C#:   list.Add(4);
来源：http://dali.yj202588.top/Article/details/gtsewmzopk.html

[D03] 在指定位置插入元素
来源：http://dali.hnqzz.top/Article/details/gtvtffsskv.html

Py:   arr.insert(0, 0)
来源：http://dali.mhx1999.top/Article/details/gtkhoeeyhn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenjidiqi.icu/Article/details/gtcwwxrszv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhixingplan.top/Article/details/gtsubedair.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.aizwys.cn/Article/details/gtqfhnrnhd.html

Java: list.add(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtkgkvibxh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuazsnzf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.bjfxy.top/Article/details/gtwiqzaxaf.html

C#:   list.Insert(0, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtaiuzwpky.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gtghumdivu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtpghpqnut.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtgkpgywcs.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtmpnshptc.html

TS:   arr.splice(0, 1);
来源：http://dali.xuanzx.com/Article/details/gtshxlrcpm.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yj202588.top/Article/details/gttlnnvxyo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtxvegyqyn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hnqzz.top/Article/details/gtuzaszerh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gtmszxejzr.html

[D05] 访问与修改元素
来源：http://dali.xziqi.cn/Article/details/gtguhgissc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtlljqnnmd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtauiutqlc.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.nanxinkj.top/Article/details/gtdspawvxu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtcpsvleyt.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhongyouzk.top/Article/details/gtzehywuji.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtovguwemc.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenzaomai.com/Article/details/gtmvjapupt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gtnbvshnor.html

[D06] 数组长度
来源：http://dali.xuetiantiany.cn/Article/details/gtibgrdpie.html

Py:   len(arr)
来源：http://dali.xinyue.icu/Article/details/gtfqrhoulz.html

PHP:  count($arr);
来源：http://dali.pengpengdd.cyou/Article/details/gtepqlmrue.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtasnotsks.html

TS:   arr.length
来源：http://dali.zdqjudy.top/Article/details/gtsafonuyo.html

Java: list.size();
来源：http://dali.aizwys.cn/Article/details/gtrybmokhy.html

Go:   len(arr)
来源：http://dali.haohaochexian.top/Article/details/gtnabkvezl.html

Ruby: arr.length; arr.size
来源：http://dali.snrcjt.cn/Article/details/gtncxmijpa.html

C#:   list.Count;
来源：http://dali.andypj.xyz/Article/details/gtivrrqykn.html

[D07] 切片 / 取子数组
来源：http://dali.ybcxt.top/Article/details/gtdopbjrcx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ybcxt.top/Article/details/gtmwiteyqk.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yueranfly.top/Article/details/gtjhvwxjyk.html

JS:   arr.slice(1, 4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtftqhonip.html

TS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpwrsrzqp.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtvcpuaqmc.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtlobnblfg.html

Ruby: arr[1, 3]
来源：http://dali.chenzaomai.com/Article/details/gtjljqtgzo.html

C#:   list.GetRange(1, 3);
来源：http://dali.yj202588.top/Article/details/gtfnrsdbve.html

[D08] 合并两个数组
来源：http://dali.zhijiandao.cn/Article/details/gtlbrsyjfw.html

Py:   a + b;  a.extend(b)
来源：http://dali.tanke756.top/Article/details/gtwfiwkcty.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtfccvmcta.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ehwqpu.com/Article/details/gtgrdsmkyg.html

TS:   [...a, ...b];
来源：http://dali.jlsjyb.cn/Article/details/gtobdvdrcx.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jianghu66.top/Article/details/gtgbmztmja.html

Go:   append(a, b...)
来源：http://dali.cheryme.top/Article/details/gtqyreskny.html

Ruby: a + b;  a.concat(b)
来源：http://dali.nwbrower.top/Article/details/gtgearappj.html

C#:   a.Concat(b).ToList()
来源：http://dali.quarkkingdee.top/Article/details/gtjzjvhqxn.html

[D09] 排序（升序）
来源：http://dali.guowangkeji.top/Article/details/gtfdprtidj.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gtixkaofoe.html

PHP:  sort($arr);
来源：http://dali.hysaishi.cn/Article/details/gtrjzpjwia.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtjmvhvkac.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yj202588.top/Article/details/gtshcquhzf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.gogol.net.cn/Article/details/gtnzmlorwz.html


<!-- 参考信息 -->