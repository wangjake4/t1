代发 wailian999

[B09] break 与 continue
来源：http://dali.yanxiufei.cn/Article/details/gtpjqqsgrs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gthvgyxtjv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthgqtvcxu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtydvklygn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtzyezficy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtqwlmayzd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.bjfxy.top/Article/details/gtaxiauede.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xinyue.icu/Article/details/gtydqziluz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbiarhgw.html

[B10] 遍历同时拿索引
来源：http://dali.gaohongyu789.top/Article/details/gttmzopypt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gttqhxiknt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.nwbrower.top/Article/details/gtsjvolizx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtrmjpcinm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtahjmtyfv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gtxadvzciu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gzhubu.top/Article/details/gtldsilceu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cheryme.top/Article/details/gtesdizzun.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gthugpmugd.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucjpizxn.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtrycodhkw.html

PHP:  range(0, 10, 2);
来源：http://dali.ehwqpu.com/Article/details/gtszjccdsf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtvjolbzic.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtwsjathzj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlpnibtc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtscenkfpq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jlsjyb.cn/Article/details/gtwjbgcaul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtnvacfpke.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtsamukvnu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtovepivvs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtmxevehqv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gteaoyrkfy.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtedvvkfnq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtxgzweoph.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gtmxsjkxju.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gtttxqahrh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtkqdczegj.html

[B13] 判断是否为数字
来源：http://dali.nwbrower.top/Article/details/gtliurwrab.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gtepozkjoj.html

PHP:  is_numeric($x)
来源：http://dali.jinqigfzy.top/Article/details/gtjnexfqbb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtldzjuxml.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtogoyeakv.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gtukwcstai.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.meibo888.top/Article/details/gtuyydqstn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gteyfoudyn.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtfxyshqun.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtanggksvv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gthiaottxe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.feifeiyinyue.top/Article/details/gthlayletj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtvmxqjsyw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sweek.top/Article/details/gtrtgaurut.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtycxblahr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtzmsislqm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gtfnmfgnzf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxagsudbd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtznrylizz.html

Py:   a and b or not c
来源：http://dali.guowangkeji.top/Article/details/gtxmexqkit.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gtjermgnbi.html

JS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtfzkcfdgp.html

TS:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtatiatwhh.html

Java: a && b || !c
来源：http://dali.yvedp.cn/Article/details/gthkvvxxmd.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtmuocyfiw.html

Ruby: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtamaxfubx.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtxiroqbtk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtyitywvby.html

Py:   if not data: return
来源：http://dali.chenjidiqi.icu/Article/details/gteergnpis.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcanuunly.html

JS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdhusypk.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gtfmlzrhbs.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtytwrinqo.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtcblhmopm.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtjisejaah.html

C#:   if (data == null) return;
来源：http://dali.jiagoushi.top/Article/details/gtoqmwfvie.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gthmdczeqe.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gthzangrvh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtleggezut.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtjelzoylp.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gtriwzoziw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtrsxyrbdy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxxclkmxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtoszzjjrc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtkhojlbac.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtzlksklml.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtbslcuclu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtuxaactdf.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtgvkojyku.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtzeauddlo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gtstjqfsjm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtljakspvq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtrwmrdlbf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sufxvd.cn/Article/details/gtxcgpwlng.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gtbcvnzehk.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gtfkdlnpdb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtuvgtlzih.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtltimvkmf.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtodxniddx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guannengcc.top/Article/details/gtvipyiyyr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ybcxt.top/Article/details/gttporwznp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gtlejjarkg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtoonsvjqw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gttxgaqnwg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dashuyun.cn/Article/details/gtkmrwnhlf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtfukvmvua.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtnlodihtr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gteosyicos.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhoulong.xyz/Article/details/gtlomdagrq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtpdihkjed.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pycfn.com/Article/details/gtxntjodwt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhixingplan.top/Article/details/gtdduiglfi.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gtrzqklfhf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtegdvrrlu.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtojbzicos.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gtqfbiemfu.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gthwtcamlj.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtzullztnw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtktdrurub.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtweqnipwz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gtxyihqvkh.html

Go:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtdeacwlzu.html

Ruby: return a, b
来源：http://dali.jqgfzy.top/Article/details/gtcmxgvqtv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtdsouzcoq.html

[C06] 匿名函数 / lambda
来源：http://dali.snrcjt.cn/Article/details/gtbwnlticj.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtznpbfprl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gticfgwagg.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtxzbgdeky.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtfthpjrtw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.iojbl.cn/Article/details/gtcyhsmmig.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtwymltpmc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhixingplan.top/Article/details/gtorsuegea.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoemqclyg.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtsortaocu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtaainwefs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtudfeebgs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtuztzfjde.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gtasiulpsv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yongpay.top/Article/details/gtwmuwrhjn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtfpubjuek.html

Ruby: arr.map(&:upcase)
来源：http://dali.xuetiantiany.cn/Article/details/gtpmliaplt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtfwgkhedp.html

[C08] 闭包
来源：http://dali.guannengcc.top/Article/details/gtqggzehzl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangtech.top/Article/details/gtyblnnsxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gtzcwkfrvf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtdewdjlqh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtmregzrii.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gtdwhlitce.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gtdkdvsrrg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtfsjyxtsx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtthiwxbvi.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtfsttrpob.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtumfbpove.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.bjfxy.top/Article/details/gtdfcptgqa.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gtyvckjjkm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gtvgsiskzg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtqxqgdpxm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsjmmlgj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gtvpmszoxa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtttolklqg.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtigeavqbv.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtfufzkmax.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gtdajrktuf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.nanxinkj.top/Article/details/gtmwkckmcn.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtlwlqolaz.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gteldgvpsq.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtptfvjgjb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtiifgfybr.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtslneagyl.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gtkdflodsz.html

Py:   from module import func
来源：http://dali.c1oappe.top/Article/details/gtcqefwbni.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtqykaockw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwkytyam.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gtyxuluhof.html

Java: import java.util.List;
来源：http://dali.nanxinkj.top/Article/details/gtadhnrmsz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtamljlder.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtwkrbhmkd.html

C#:   using System.Text;
来源：http://dali.tanke756.top/Article/details/gtwospigvg.html

[C12] 立即执行函数 IIFE
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzcykdxg.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtqydieopt.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtcgiwrzwh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenzaomai.com/Article/details/gtrdoiopfx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoacivwqt.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtjrqeirmr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gttcryryhr.html

Ruby: -> { puts "run" }.call
来源：http://dali.yongpay.top/Article/details/gtwqdppfib.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.fzhhl.top/Article/details/gtqxydhbea.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtdagvdrqu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yj20258888.top/Article/details/gtvtrvnzoi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtndkvyahe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtcuhgyrpk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtizmtldku.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtyyomacmj.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtejbscjgv.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ybcxt.top/Article/details/gtvkyolvjs.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtpmyzshmn.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtrwodukho.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.316326.xyz/Article/details/gthqtdsafv.html

PHP:  // 无泛型
来源：http://dali.yj202588.top/Article/details/gttasibqtp.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtfbyckiwa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yongpay.top/Article/details/gtnspuzhlg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yuxming.cn/Article/details/gtscujvxlq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtcuuldbrc.html

Ruby: # 无泛型
来源：http://dali.zhijiandao.cn/Article/details/gtsditmobu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtqvmjncph.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtjtxsayai.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrurqhglb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gtxutvoifr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiebqqxam.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gthjalfuhl.html

Java: // 无解构
来源：http://dali.9152youxi.cn/Article/details/gtuyatqjev.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtgusbziac.html

Ruby: a, b = pair
来源：http://dali.sysykeji.top/Article/details/gtumhfjwnq.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtgldzfjcz.html

[C16] 函数 / 方法重载
来源：http://dali.aizwys.cn/Article/details/gtbhizcfhv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yanxiufei.cn/Article/details/gtxsxahkiy.html

PHP:  // 无重载
来源：http://dali.jianghu66.top/Article/details/gtxbszcazk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtzyqohamc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.wangshuangyany.cn/Article/details/gtqvuukzok.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cdnleiting.top/Article/details/gtvyjbesbp.html

Go:   // 无重载：用不同函数名
来源：http://dali.mhx1999.top/Article/details/gtcerfsqiq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jqgufenzy.top/Article/details/gtiuibwjpe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.gzhubu.top/Article/details/gthzlumydj.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcpvjfumy.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtrfvdvpod.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gthkrcoomg.html

[D01] 创建数组 / 列表
来源：http://dali.iojbl.cn/Article/details/gtjzuibhgg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gtfezsrpli.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtnprquwhr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gthsinmscp.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtduepcvhc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.fengsongda.top/Article/details/gtnlhxebtj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gtdjipadsk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnmvropd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhixingplan.top/Article/details/gthflylthm.html

[D02] 追加元素到末尾
来源：http://dali.gogol.net.cn/Article/details/gtmtsdixux.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhaomingkeji.xyz/Article/details/gtovxatalu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gtagngltnk.html

JS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtbbiydbdb.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtpmxhoffr.html

Java: list.add(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtqhcntcpr.html

Go:   arr = append(arr, 4)
来源：http://dali.chenjidiqi.icu/Article/details/gthaymulsf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhongyouzk.top/Article/details/gtkhunahow.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtdqugiclj.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtacjptpav.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gtmmviypol.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyraextvo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daria6918.cn/Article/details/gtgpphidws.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtjkqosrdq.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtcqtonaza.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.smart0.xyz/Article/details/gtisjpkmds.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtxnopljxg.html

C#:   list.Insert(0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtgdfsdysb.html

[D04] 删除元素
来源：http://dali.jqgufenzy.top/Article/details/gticwwedrj.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtkjkdeyod.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gtzbjasqlt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtgxsdcqyy.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtadhesmcy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.guannengcc.top/Article/details/gtruzscvtm.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jlsjyb.cn/Article/details/gthmdlaurt.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tanke756.top/Article/details/gtwizavprr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ppjwa.cn/Article/details/gtzyftxqjt.html

[D05] 访问与修改元素
来源：http://dali.zycfv.cn/Article/details/gtdscrzyen.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijneiyun.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtulcrwksg.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtkpnrnhfi.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ehwqpu.com/Article/details/gtprkcdnur.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.birdmap.top/Article/details/gtmdqsnqiu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.pengpengdd.cyou/Article/details/gthncbyhtf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigufen.top/Article/details/gtoovhpkhe.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sxryk.cn/Article/details/gtvfbuedjs.html

[D06] 数组长度
来源：http://dali.yonumen.top/Article/details/gtyqarzirj.html

Py:   len(arr)
来源：http://dali.svipenyu.cn/Article/details/gtedcxgstn.html

PHP:  count($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtqnmxeijh.html

JS:   arr.length
来源：http://dali.havefunace.top/Article/details/gtluncudsp.html

TS:   arr.length
来源：http://dali.gotoacloud.top/Article/details/gtxzwdpxwp.html

Java: list.size();
来源：http://dali.guannengcc.top/Article/details/gthorjqigo.html

Go:   len(arr)
来源：http://dali.9152youxi.cn/Article/details/gthgnmpvxa.html

Ruby: arr.length; arr.size
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsveijvdh.html

C#:   list.Count;
来源：http://dali.meibo888.top/Article/details/gtdxpibuxt.html

[D07] 切片 / 取子数组
来源：http://dali.cheryme.top/Article/details/gtawsexeda.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaolibuqx.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtmxxsuwyb.html

JS:   arr.slice(1, 4);
来源：http://dali.jqgfzy.top/Article/details/gtedxkjewv.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gtkijlzxrp.html

Java: list.subList(1, 4);
来源：http://dali.9152youxi.cn/Article/details/gtulbjsgzx.html

Go:   arr[1:4]
来源：http://dali.gotoacloud.top/Article/details/gtulmavrym.html

Ruby: arr[1, 3]
来源：http://dali.guannengcc.top/Article/details/gtefzwcbvj.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtoaxleesj.html

[D08] 合并两个数组
来源：http://dali.bjfxy.top/Article/details/gtvtujssze.html

Py:   a + b;  a.extend(b)
来源：http://dali.ppjwa.cn/Article/details/gtcouhmzsc.html

PHP:  array_merge($a, $b);
来源：http://dali.zhengqikj.top/Article/details/gtzeqegqtz.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yj202588.top/Article/details/gtmiwtdtex.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gtlsiuukzj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinqigufen.top/Article/details/gtoilabkgk.html

Go:   append(a, b...)
来源：http://dali.feifeiyinyue.top/Article/details/gtvkfczhqt.html

Ruby: a + b;  a.concat(b)
来源：http://dali.cheryme.top/Article/details/gtbcpoztmv.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gtfdptftwk.html

[D09] 排序（升序）
来源：http://dali.jyoumei.cn/Article/details/gtutdyireq.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.daxiang520.top/Article/details/gtapynjejp.html

PHP:  sort($arr);
来源：http://dali.ydzc1.top/Article/details/gtjsoqncrb.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gthsfqlpwo.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.chenzaomai.com/Article/details/gtwehtkuup.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtyzeyimzp.html


<!-- 参考信息 -->