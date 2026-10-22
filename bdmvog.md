代发 wailian999

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gtemsueshb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aibaodan.cn/Article/details/gtlgjexjnj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtfasuxxtm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gtgbsirrhm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtmpyssznp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtgarmtqcm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gtjqzcresq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gtosleblik.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtwgwvdgqa.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtxvyeohro.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shzxlz.cn/Article/details/gtyhnauqyq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtjztzqaqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtagtvosus.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gtvpasuxft.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtixbldgjk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtpuuggnqz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangdashe.top/Article/details/gtlavlachx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtkzwbqrps.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gttluotjyk.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtyuedwjkn.html

PHP:  range(0, 10, 2);
来源：http://dali.cashguo.top/Article/details/gtzlrwjcsj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtylxszhfe.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtbucltqkc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.guowangkeji.top/Article/details/gttniaskpv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtrzopgsnk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtzavinyvg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tian-w.cn/Article/details/gtxujzhbgy.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gtzjypflfj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gtijqvlwrk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtlrqpdqqz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtvhrsztsw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtvgpwxoqr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtrlazjneu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gtvneqwlgq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtfwvfgfka.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtfactweba.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtnkbbpppt.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gtpznlzzqy.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gtqcqrekmw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtblfulloo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtxdaxdozv.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtfcnrznfj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gogol.net.cn/Article/details/gtshhoysgy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gthryvqwsy.html

C#:   x is int or double or decimal
来源：http://dali.gotoacloud.top/Article/details/gtzddtkmur.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gtswkipozw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ivvv.top/Article/details/gtqgltioez.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cqqwz.cn/Article/details/gtezwrgtkg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtqgrqunmt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gthsdkiyrr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gtzqqhafmz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.redwolf501.top/Article/details/gtetjdptwq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmlipjip.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthtuweiex.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtevvqkpoy.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtlvtcpjae.html

PHP:  $a && $b || !$c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjiownamz.html

JS:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtnxlcfmji.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtakptlpfo.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gttysxiztk.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gttzqyzglk.html

Ruby: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtmsqywhxv.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxssmfvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gthoxvftci.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtygzyvqjr.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtewbhxkuk.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtyabhdiif.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gtelgegdny.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtyumbvqfb.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gtxpeaifna.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtxretcbcr.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtdbllxkzh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtwqozseck.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gtowjpgmwg.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtoqzdzjhq.html

[C01] 定义函数
来源：http://dali.chenlongwang.top/Article/details/gtsbmpmmql.html

Py:   def add(a, b): return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtgwizpouk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtvsclkauk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtbjgoiguz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtqoifcitx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtsclsyohv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtwaomqdtq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtpkigatyp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtrsrurnjp.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtyqdqrplh.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtaysbgyzw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtwkdzbbum.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.svipenyu.cn/Article/details/gtjsrojcze.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtrlxjwbcf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.birdmap.top/Article/details/gttgosrdhe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhengqikj.top/Article/details/gturszshcp.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtiwygyaqi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtabxodynt.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtzvptgekr.html

Py:   def total(*args): return sum(args)
来源：http://dali.gogol.net.cn/Article/details/gtvmuzgyrp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtiruutqfj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtujpivags.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtzakltqnp.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtddloujpv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.mhx1999.top/Article/details/gtpmfcmofh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258.top/Article/details/gtkomdjqje.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtabwiodek.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gttnzgyvgi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gtwmhhrnhd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtectvlabu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtuhgwhytf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gtkludgamx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gthusluqan.html

Go:   // 无：用配置结构体参数
来源：http://dali.svipenyu.cn/Article/details/gtfgdcovlq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcppsrza.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtumnlewym.html

[C05] 返回多个值
来源：http://dali.bjfxy.top/Article/details/gtgmshzhxs.html

Py:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtzpfakxbw.html

PHP:  return [$a, $b];
来源：http://dali.wangdashe.top/Article/details/gtdcyrovug.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pycfn.com/Article/details/gtbrliqumi.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtsewovcqs.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gtdtkbefkq.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtffdimwpk.html

Ruby: return a, b
来源：http://dali.tianlin.xyz/Article/details/gtszoievgz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtxucwdusg.html

[C06] 匿名函数 / lambda
来源：http://dali.316326.xyz/Article/details/gtqjxkvirt.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gteydimimw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hfpthk.cn/Article/details/gtvtuyhfhj.html

JS:   const square = x => x * x;
来源：http://dali.cashguo.top/Article/details/gtdxkbqhin.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtjygfvvum.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtsqmolymh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gttomomrjo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxgtzwls.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtorembnsv.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gttscenibd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pengpengdd.cyou/Article/details/gturbxyezb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gthpymncpi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtyfmggccx.html

TS:   arr.map(String)
来源：http://dali.ppjwa.cn/Article/details/gtqqavspan.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gtfnghttjk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtrplarvlv.html

Ruby: arr.map(&:upcase)
来源：http://dali.ybcxt.top/Article/details/gtwyjrgvmg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yj20258.top/Article/details/gtwukkhjtw.html

[C08] 闭包
来源：http://dali.gzhubu.top/Article/details/gtoiqezwgs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pycfn.com/Article/details/gthfegorap.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtwxyvlxqf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtbwkcuevg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gtvnuvaukq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtcefinxgk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbhfarvt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daxiang520.top/Article/details/gtieftwgle.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtijbppmym.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gtrnvkcays.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gtxyudgjxh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtpldnijof.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtzuqwpsdx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtogcpknkc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbpshelp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dashuyun.cn/Article/details/gtgxeooale.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gtjewhreaz.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.havefunace.top/Article/details/gtwkawccdd.html

[C10] 变量作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtjtnrlxxh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.0kj1m.cn/Article/details/gtlbehpmjq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.0kj1m.cn/Article/details/gtumvkhzah.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtxquuqdvz.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtipfbrktw.html

Java: 方法内为块级作用域
来源：http://dali.xuanzx.com/Article/details/gtevpemunq.html

Go:   花括号块级作用域
来源：http://dali.fengsongda.top/Article/details/gtckjroofd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhengqikj.top/Article/details/gtkvpqirhy.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtzruabzpk.html

[C11] 模块导入与导出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtajezsqsv.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtfwwdkakx.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fzhhl.top/Article/details/gtxqfvksqy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtwiboxcuc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenzaomai.com/Article/details/gtymbuqspq.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gthdnmyxdk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtproluocg.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtfuhmetqw.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtcxlgpxql.html

[C12] 立即执行函数 IIFE
来源：http://dali.ppjwa.cn/Article/details/gtntgshwop.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtvfslbspg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtfjbphcxi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtinxpdscs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuetiantiany.cn/Article/details/gtdylnwjsx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jiagoushi.top/Article/details/gttsrndslc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xylfe.cn/Article/details/gtexwcbnze.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbezgaszp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtdpqwmcxp.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtztnjmdxc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtjbsphhhe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtcskbtpvn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xziqi.cn/Article/details/gtysvgdmfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtbneglqds.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtvfdzyyvb.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtlibzhsen.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hysaishi.cn/Article/details/gterbqzjjt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jlsjyb.cn/Article/details/gtczrlsams.html

[C14] 泛型函数
来源：http://dali.yongpay.top/Article/details/gtzqkuhbdr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sysykeji.top/Article/details/gtcprtgnfp.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtspggevyd.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtwzxuorex.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gaohongyu789.top/Article/details/gtezxejcpi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxlguxeaz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtahibvrwa.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gttmtudmto.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtnlvvahhq.html

[C15] 解构 / 展开参数
来源：http://dali.chenlongwang.top/Article/details/gtmyhuawra.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtibmxewhz.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtkfjydqvy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtolnxfkvn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtdbgtbvga.html

Java: // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbfhgdftf.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtqjqehegv.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gtcwghcjnv.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsitptoh.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtibbwashi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hongshengwenyu.top/Article/details/gtdgsnanyn.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtfucnypil.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhengqikj.top/Article/details/gttrzhfebz.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gtfccolsyq.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.dashuyun.cn/Article/details/gtlpybyngm.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtasjefauk.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfvboojwy.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtdlkrwaft.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtssoshryp.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtszxthnpt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkxdknihw.html

[D01] 创建数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsybdqafq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gteeqeoqjn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtqbmsdrkd.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jianghu66.top/Article/details/gtpgholonh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.wangdashe.top/Article/details/gtvxdhjcow.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gtudtirqtg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gtxvptxgsi.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hongshengwenyu.top/Article/details/gtxqvdesfe.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.mhx1999.top/Article/details/gtldplimvz.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtkltokejk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.chenzaomai.com/Article/details/gtruxphkmm.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gtzkfdtzoz.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gthqksdkac.html

TS:   arr.push(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtguowvyrv.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtnqdrbnfk.html

Go:   arr = append(arr, 4)
来源：http://dali.gotoacloud.top/Article/details/gtlhoccdgl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.0kj1m.cn/Article/details/gtiicmpumi.html

C#:   list.Add(4);
来源：http://dali.dianchejie.cn/Article/details/gtfgkanznr.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtztojzjmw.html

Py:   arr.insert(0, 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtarlvtgii.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gthqwmjlha.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fengsongda.top/Article/details/gtgqnhglaj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtqkksnskk.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtzwurmply.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtxfavrrwq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cashguo.top/Article/details/gtioifckow.html

C#:   list.Insert(0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtejpxzzgd.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtfcfnyaiq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gthsylthuv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yanxiufei.cn/Article/details/gtmhpxwieq.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xziqi.cn/Article/details/gtcwhswhuw.html

TS:   arr.splice(0, 1);
来源：http://dali.hysaishi.cn/Article/details/gttfdopvzg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvakkrrk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cashguo.top/Article/details/gtynoxsxgu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.haohaochexian.top/Article/details/gtwjkihsvu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqswuojc.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtcqoczjqg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtlatdgqrb.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.wangshuangyany.cn/Article/details/gtudsgxeox.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtxihvvlnd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hysaishi.cn/Article/details/gtuerxuwwn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tianlin.xyz/Article/details/gtsifpuffh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtommbyufk.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yonumen.top/Article/details/gthywohnqg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtouqqannq.html

[D06] 数组长度
来源：http://dali.tian-w.cn/Article/details/gtvfpkucxn.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtexswsclp.html

PHP:  count($arr);
来源：http://dali.xylfe.cn/Article/details/gtqohjpgyi.html

JS:   arr.length
来源：http://dali.jiagoushi.top/Article/details/gtzkchspkt.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtfhrylusp.html

Java: list.size();
来源：http://dali.sysykeji.top/Article/details/gtopivpxtc.html

Go:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gtbfrvrqms.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gtaqqejxoz.html

C#:   list.Count;
来源：http://dali.guowangkeji.top/Article/details/gtgvrvqrtp.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtciutwgqa.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.guowangkeji.top/Article/details/gtyxkngbnp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cheryme.top/Article/details/gtfhsfcmeb.html

JS:   arr.slice(1, 4);
来源：http://dali.yj202588.top/Article/details/gtmygiwvpd.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtnxwsodyc.html

Java: list.subList(1, 4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbdxueabq.html

Go:   arr[1:4]
来源：http://dali.vqdsnc.cn/Article/details/gtwxzsxacj.html

Ruby: arr[1, 3]
来源：http://dali.tanke756.top/Article/details/gtehitjaob.html

C#:   list.GetRange(1, 3);
来源：http://dali.fzhhl.top/Article/details/gtwagjpbad.html

[D08] 合并两个数组
来源：http://dali.hongshengwenyu.top/Article/details/gteueszyaj.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtumxexwdj.html

PHP:  array_merge($a, $b);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpshxawwc.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.gotoacloud.top/Article/details/gtcsvwnevs.html

TS:   [...a, ...b];
来源：http://dali.hywenlv.cn/Article/details/gtnhhssmph.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.316326.xyz/Article/details/gtwwkmzyxl.html

Go:   append(a, b...)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvlngbmy.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj202588.top/Article/details/gtxgazamjn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jlsjyb.cn/Article/details/gthaqitkbg.html

[D09] 排序（升序）
来源：http://dali.andypj.xyz/Article/details/gtahckhorn.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cashguo.top/Article/details/gtknanmkqo.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gttwxmbpcl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.fengsongda.top/Article/details/gtyjalswvm.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtmwpetbdn.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yuanzhike.top/Article/details/gtmhzcywpe.html


<!-- 参考信息 -->