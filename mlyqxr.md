代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtdvikmkuf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gthgkysvex.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gtwsrdojsw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtkxijkbfc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtfimqglfb.html

[B10] 遍历同时拿索引
来源：http://dali.nwbrower.top/Article/details/gtixhinkql.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtuaqugukp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtuwlkpfzl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jianghu66.top/Article/details/gtttyvrvms.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtonsgpouk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xziqi.cn/Article/details/gtkgsqdvys.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtqrimkami.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtdpiypidg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gtpvtlssdu.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtfbdyiydq.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiqapjvge.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtehwgdbol.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtclxlkuad.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gtimcwmkco.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.9152youxi.cn/Article/details/gtnmbfhsva.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.mhx1999.top/Article/details/gttbegepwa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gtpuuslsba.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gthtsbrevd.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtxhzuacjq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gtfhyfsnaf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gtllysquzk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtfkinsaot.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtoyhufscv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtfqxzimua.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ydzc1.top/Article/details/gtagkztggt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtzwnjnuna.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dashuyun.cn/Article/details/gtffbpkstc.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangtech.top/Article/details/gthcxsurzq.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtdhzvgpgz.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gtdilrjrqv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqvdykce.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtcnoqbvog.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtjilgslyr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtqbotwded.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtkkddhuex.html

C#:   x is int or double or decimal
来源：http://dali.chenjidiqi.icu/Article/details/gtylznwsfg.html

[B14] 判断值是否在集合内
来源：http://dali.jqgfzy.top/Article/details/gtrfwsqakm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gogol.net.cn/Article/details/gtpjnafgmi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cdnleiting.top/Article/details/gtaswhtqap.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtqnhsrhvg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtokezszff.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtpccjrusv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenzaomai.com/Article/details/gtbpooxaio.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtohhqdmrv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtkfvpwwqx.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtuowanssy.html

Py:   a and b or not c
来源：http://dali.jqgufenzy.top/Article/details/gtbezczhtp.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gttckzajjl.html

JS:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtraibcgcu.html

TS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtvrjtggdc.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqtroqyn.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtrhteejpm.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtxxwfmiww.html

C#:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtrfdtbleb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gttmxneuxd.html

Py:   if not data: return
来源：http://dali.yuxming.cn/Article/details/gtxloahmgk.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtnpwnasdp.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gttontuzsf.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtilrpabym.html

Java: if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gtockupqtq.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtzhgfzhid.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtttvrcbrx.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gtrjdwfwou.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtrhjqolor.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtazqrugik.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfqpqhsuf.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtxpkqughp.html

Py:   def add(a, b): return a + b
来源：http://dali.316326.xyz/Article/details/gtmxcpnwkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtpzchnibz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtzclbdvhr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtexiziuov.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtmmxykxny.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtbneculkd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.kuanghao11.cn/Article/details/gtikvrilkm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtyeovcpht.html

[C02] 默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtlbbencqx.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtuawsenzo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtbemqvjzl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sufxvd.cn/Article/details/gtooprspqg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteawgclur.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtpgepjrhb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtbgpfvltj.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangkeji.top/Article/details/gtminksvpl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgxfniun.html

[C03] 可变参数
来源：http://dali.xylfe.cn/Article/details/gtohcytnbg.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtzzcsgkvz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gturcsoumh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtijtdthns.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvtnvcvl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xinyue.icu/Article/details/gtcrpbpfbt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xinyue.icu/Article/details/gtfkjhyzuz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfxznrpw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtrxchlazv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtykprkyyn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtntrtlgql.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtfqhirplx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtyovleesq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtkusdcyfd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtgtawaapj.html

Go:   // 无：用配置结构体参数
来源：http://dali.yvedp.cn/Article/details/gtvutfbizu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtsqnnlsqq.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtkaugcyal.html

[C05] 返回多个值
来源：http://dali.fzhhl.top/Article/details/gtwjjivxds.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gttpcysarr.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gtwojtjtym.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtppwmracy.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtjzkudwem.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtizdavcto.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtvcphfyph.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gtyfbqdqsb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gtdkkuzcri.html

[C06] 匿名函数 / lambda
来源：http://dali.cucudq.cn/Article/details/gtfqnfgmww.html

Py:   square = lambda x: x * x
来源：http://dali.havefunace.top/Article/details/gtgmkpozpl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtktertlhs.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtqagdcwon.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtvnqhnint.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtfzhsryvq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.nanxinkj.top/Article/details/gtlytpaxvb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tianlin.xyz/Article/details/gtylqoenpu.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtzumumxju.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtvywgirsb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.0kj1m.cn/Article/details/gtigegvskh.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtpcwjbyve.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtsxkdwcus.html

TS:   arr.map(String)
来源：http://dali.zhijiandao.cn/Article/details/gtvdxmwmgo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtcfogxtpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tian-w.cn/Article/details/gtagufcuao.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkiklwkzm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtqtpngyvd.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtnlmhlixf.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtitrjanus.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cashguo.top/Article/details/gtcecdpqll.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtpuwbagrv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtkpwpjwfv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtafmvonce.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gttvyuwhsv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gtrkqjwzam.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gthmfwmnyg.html

[C09] 递归
来源：http://dali.meibo888.top/Article/details/gtmfbrqvdp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gtqhjyhzze.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tianlin.xyz/Article/details/gtpdhjcgbp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtzaegbnjk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtdcafvcsp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtxdsvlzxo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gttbwdvpjo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtopyemuhx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuanzhike.top/Article/details/gtqcxeorvu.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtmaylpsvf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigfzy.top/Article/details/gtlxmbdhbr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtjchmcbcd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhijiandao.cn/Article/details/gtmlnruhbx.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxspnzfq.html

Java: 方法内为块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gtetvvwgwe.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtzhjfgwyx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gteawyavtl.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtdxjpjqga.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnxuwlawp.html

Py:   from module import func
来源：http://dali.zhengqikj.top/Article/details/gtjohzvege.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cdnleiting.top/Article/details/gtsgqnzcnd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtnjoqytts.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtslrzdtxs.html

Java: import java.util.List;
来源：http://dali.yangfankeji.com/Article/details/gtzabhlawn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtqpniakuv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gthbhurdzw.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gtcxkuzmar.html

[C12] 立即执行函数 IIFE
来源：http://dali.hammf.cn/Article/details/gtzkarfovi.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtacngqgik.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gtgmixqwjn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtcaefttpb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtthhpjnbw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtvqqzqctn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gthkcagwso.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtemlzumbs.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtqxtovrwl.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gthkqagxsn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.316326.xyz/Article/details/gtvhnryspe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gtixmngthm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gthjhsjwpy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtwhmntzbd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpdmsgto.html

Go:   func add(a, b int) int
来源：http://dali.sysykeji.top/Article/details/gtgqcesdoz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zdqjudy.top/Article/details/gtcpmjtllu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gtnsqxyyol.html

[C14] 泛型函数
来源：http://dali.shzxlz.cn/Article/details/gtoikqnrhe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtybzsvvlt.html

PHP:  // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtkgnfniyt.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtwakbqtbg.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gtcckxpmdk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jiagoushi.top/Article/details/gtdtaekhyk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtpgmszluu.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtvgbeuckx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dashuyun.cn/Article/details/gtdnnwleaq.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gtbuirxmgg.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gtthkpjtef.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gtmwomyesv.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gtfjerreoj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gzhubu.top/Article/details/gtbjrxheil.html

Java: // 无解构
来源：http://dali.aibaodan.cn/Article/details/gtoryiixtr.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gtclxfxviz.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtaxmeammp.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258.top/Article/details/gtxezlufci.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqgkfzdw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cheryme.top/Article/details/gthnpdeuye.html

PHP:  // 无重载
来源：http://dali.cheryme.top/Article/details/gtdkkcxeis.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daxiang520.top/Article/details/gtedzkecsa.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.svipenyu.cn/Article/details/gtjhsbohvy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.andypj.xyz/Article/details/gteivlpjzl.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gtwlsqrxbp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tian-w.cn/Article/details/gtumlwsadi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtdrnhnotj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtsuunmiei.html

D. 数组 / 列表 / 集合
来源：http://dali.cheryme.top/Article/details/gtgbctpfwg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtwzloevoc.html

[D01] 创建数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtnymyerfs.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenzaomai.com/Article/details/gtvwcqsynv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtolzzsetn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtytmgvsgk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhjpykds.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xylfe.cn/Article/details/gtzvjicaja.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gtscpwfbse.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtjarafsou.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijzgsyci.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtoiexbdgo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtbxwrzgxi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ppjwa.cn/Article/details/gtzeqmfuel.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtgytiptwn.html

TS:   arr.push(4);
来源：http://dali.nwbrower.top/Article/details/gtbsxjjhhh.html

Java: list.add(4);
来源：http://dali.birdmap.top/Article/details/gtsvwbwznp.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtxsphomne.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtawvknmib.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtyzgsojvf.html

[D03] 在指定位置插入元素
来源：http://dali.nanxuanxn.top/Article/details/gttfehyiwe.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gthxzwxtok.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gtqhrsmtjf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.kuanghao11.cn/Article/details/gtdtjizrsj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daxiang520.top/Article/details/gtbeuslvnj.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtzdugadnb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtujksusch.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtugfitqqw.html

C#:   list.Insert(0, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtbegebgma.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtaioabizi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cashguo.top/Article/details/gtwtuaywnf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtjhakoyzy.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtqbcugnfq.html

TS:   arr.splice(0, 1);
来源：http://dali.daxiang520.top/Article/details/gtqpififkf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gtplctcbxr.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shangyingyoupin.top/Article/details/gtelotkaxg.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtpqdxntku.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtgswcwoll.html

[D05] 访问与修改元素
来源：http://dali.jinqigfzy.top/Article/details/gthjdublir.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ehwqpu.com/Article/details/gtvwofdozg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtmheijvwf.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtlsrpyyqz.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtdshtvrwz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zdqjudy.top/Article/details/gternmpvng.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtvsnhvhju.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gttpepeekl.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xylfe.cn/Article/details/gtcaqelpvr.html

[D06] 数组长度
来源：http://dali.guannengcc.top/Article/details/gtglifoohk.html

Py:   len(arr)
来源：http://dali.hywenlv.cn/Article/details/gtkoxoqssf.html

PHP:  count($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtxxltnene.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gttoxnggrl.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtegcebqvf.html

Java: list.size();
来源：http://dali.haohaochexian.top/Article/details/gtskkvoaut.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtfxaqkujv.html

Ruby: arr.length; arr.size
来源：http://dali.fengsongda.top/Article/details/gthezrtrdk.html

C#:   list.Count;
来源：http://dali.tianlin.xyz/Article/details/gtshgmlwhe.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtgurklozm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.ywan-chungtsiang.top/Article/details/gttansjtvr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.birdmap.top/Article/details/gtlkgemytg.html

JS:   arr.slice(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gtjwdvyqxu.html

TS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtnrkdekqg.html

Java: list.subList(1, 4);
来源：http://dali.gogol.net.cn/Article/details/gtaqcsvfro.html

Go:   arr[1:4]
来源：http://dali.jqgufenzy.top/Article/details/gtfwqujmfp.html

Ruby: arr[1, 3]
来源：http://dali.sufxvd.cn/Article/details/gtjggikshh.html

C#:   list.GetRange(1, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyynfufl.html

[D08] 合并两个数组
来源：http://dali.iojbl.cn/Article/details/gtdwxtqeyl.html

Py:   a + b;  a.extend(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaphozndu.html

PHP:  array_merge($a, $b);
来源：http://dali.yueranfly.top/Article/details/gtcppwccoa.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.nwbrower.top/Article/details/gtxttvnose.html

TS:   [...a, ...b];
来源：http://dali.cqqwz.cn/Article/details/gtzciqqtjo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.aizwys.cn/Article/details/gtekzlznat.html

Go:   append(a, b...)
来源：http://dali.sxryk.cn/Article/details/gtoeugtgfv.html

Ruby: a + b;  a.concat(b)
来源：http://dali.snrcjt.cn/Article/details/gtoqfrpboq.html

C#:   a.Concat(b).ToList()
来源：http://dali.zhengqikj.top/Article/details/gtierovxye.html

[D09] 排序（升序）
来源：http://dali.tianlin.xyz/Article/details/gtczldlchh.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jinqigfzy.top/Article/details/gtethnolve.html

PHP:  sort($arr);
来源：http://dali.sxryk.cn/Article/details/gtrukprmjr.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.cheryme.top/Article/details/gtfagbgmaw.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.jianghu66.top/Article/details/gtywrzmtlj.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.tianlin.xyz/Article/details/gtzpswbfyd.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtrowrrplz.html

Ruby: arr.sort
来源：http://dali.zhiwuduotai.top/Article/details/gtismkexqc.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtbigqxdbu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hammf.cn/Article/details/gtiatvulvo.html


<!-- 参考信息 -->