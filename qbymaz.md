代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtjnimopae.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gteublsmfo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ivvv.top/Article/details/gtbovqtmol.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuxming.cn/Article/details/gtbunmwvis.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtxhjpnxtj.html

[B10] 遍历同时拿索引
来源：http://dali.zhiwuduotai.top/Article/details/gtguqznznw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gtfaigfalb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.0kj1m.cn/Article/details/gtmeiixjpr.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtewxkpokf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtbpggvzxq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtgudleouf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.havefunace.top/Article/details/gtrebsdaek.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtdtxkugoh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtgirciouc.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtdswfbpbq.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtwjmrgbbh.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gthlhoqiuz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtokjgaoan.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gthghycnlk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gtcaopqnqw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtmutubkev.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtyyphbypm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gteoufavvw.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtfspieuaj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.mhx1999.top/Article/details/gtccwljrtg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtqhldiyyf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gthlklhbmx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtxpjbkeyb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtutkkjwur.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhiwuduotai.top/Article/details/gtzkgbgwic.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.bjfxy.top/Article/details/gtqwxhattk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtaqtxsxuq.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gtfqrcnavr.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gtuwzrrzzq.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gttcnfaobb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthruxpmpv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtvqwjnreb.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gtbiibwdng.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtblfinwyh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtoclsrnbx.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtypokpnop.html

[B14] 判断值是否在集合内
来源：http://dali.aizwys.cn/Article/details/gtxqlyqbvx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fengsongda.top/Article/details/gtrcrszqqo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gtzcnvexac.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshnrdfrd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtxwmhquue.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtbpqfewmb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtwuixlaei.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtrpqpkiky.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtldmsrxcf.html

[B15] 布尔运算与取反
来源：http://dali.wangshuangyany.cn/Article/details/gtfnpzxkuy.html

Py:   a and b or not c
来源：http://dali.yueranfly.top/Article/details/gtucktrgge.html

PHP:  $a && $b || !$c
来源：http://dali.cucudq.cn/Article/details/gtorlqfcxz.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gteigavxiy.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtzltrmqmr.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtscgmymjp.html

Go:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtawvdxvoh.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtoiidvxsz.html

C#:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtoxwkjyyn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtvdyzhphy.html

Py:   if not data: return
来源：http://dali.guannengcc.top/Article/details/gtypjaihsx.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtitskkuqy.html

JS:   if (!data) return;
来源：http://dali.c1oappe.top/Article/details/gtkuajtoxs.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gttbxmwilp.html

Java: if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtljskhden.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtfbzanpzf.html

Ruby: return if data.nil?
来源：http://dali.fengsongda.top/Article/details/gtjkdrxdmd.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtudwzanfv.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmknlpega.html

C. 函数与作用域
来源：http://dali.jianghu66.top/Article/details/gteqfagzdk.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdfoemvkj.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtipamtprx.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtalbcptkr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjwrkuhlh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtpfgkdgaq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtfpubxoam.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtogsihmnn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtjjhkvzil.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtyeojfbjb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtbpnznjmu.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gttlmuuhuq.html

Py:   def greet(name="World"): return name
来源：http://dali.meibo888.top/Article/details/gthulstqhi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtsieivwhz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtzdcxgafg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmpugnva.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtygjjqgbi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtncuvqdsn.html

Ruby: def greet(name = "World") = name
来源：http://dali.hysaishi.cn/Article/details/gtkdorpqek.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.havefunace.top/Article/details/gtqswrnlwe.html

[C03] 可变参数
来源：http://dali.havefunace.top/Article/details/gtdignadau.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtgwxfzkdq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtbpkkrmxy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtyoqgmhxz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtlmktgibk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtzfqjpazz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtmvpcyknp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gtyxgyvhpf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gtxkswxmve.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtqmqezrnk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtaglyyuir.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fzhhl.top/Article/details/gtysxfnkng.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtqfueeduy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtpwwuoldb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnxiangtu.top/Article/details/gtdwuacjje.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtbjygkbep.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtydcnleng.html

C#:   f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtndxffrqs.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtitmgzdsd.html

Py:   return a, b
来源：http://dali.ppjwa.cn/Article/details/gtyezbtysl.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gthbymnkza.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgerjaps.html

TS:   return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtiqgzgejz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dashuyun.cn/Article/details/gtphgkpqog.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtuvjwedty.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtlgvkxear.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaatdhuyd.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtwuzmetbh.html

Py:   square = lambda x: x * x
来源：http://dali.hammf.cn/Article/details/gtxdiihffx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.aizwys.cn/Article/details/gtezyvofoy.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtooqjiqoi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtdduoyfti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gttwtjpbwl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgndhkua.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwbokryg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtddcpbrrh.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtvgjrdaoz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhoulong.xyz/Article/details/gtgwzipvgb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.haohaochexian.top/Article/details/gtmdpqmmvw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nwbrower.top/Article/details/gtrgbsgbjc.html

TS:   arr.map(String)
来源：http://dali.xinyue.icu/Article/details/gtztkxexan.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.wangdashe.top/Article/details/gtyukoaexh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtemubihkz.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtodpkaunx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cheryme.top/Article/details/gtebkbrijl.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtijjzmteb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gtlonlsfgg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dianchejie.cn/Article/details/gtpnjtaduc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtiiasqxbt.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtiptcrxpj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtqmfysjen.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtwgzhyyhv.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtejdlhfic.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtwiqnrtzv.html

[C09] 递归
来源：http://dali.jyoumei.cn/Article/details/gtthhohnxo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtdixuaxfz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gtgxqbyxqp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtqzhqyrwv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtbdcooxfm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtjaargqrk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtqtlrsqbl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtowsqnyad.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.dianchejie.cn/Article/details/gtpozzwchr.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtrfmqpusb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xuanzx.com/Article/details/gtilqqqahs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtpyoswhin.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fzhhl.top/Article/details/gtnpvquqwc.html

TS:   同 JS
来源：http://dali.mhx1999.top/Article/details/gtvkbckuhi.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtljvejhxu.html

Go:   花括号块级作用域
来源：http://dali.ybcxt.top/Article/details/gtjnvolvak.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xylfe.cn/Article/details/gtmrpodbdl.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtmjlzodjz.html

[C11] 模块导入与导出
来源：http://dali.0kj1m.cn/Article/details/gtjttzryqy.html

Py:   from module import func
来源：http://dali.sufxvd.cn/Article/details/gtzjfxbvxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dashuyun.cn/Article/details/gtcghpyllk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtennjuelk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gtysewmwpp.html

Java: import java.util.List;
来源：http://dali.zhengqikj.top/Article/details/gtnuntdkdv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xziqi.cn/Article/details/gtxvjjepyl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtsuxgylsv.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gtxsiuxyex.html

[C12] 立即执行函数 IIFE
来源：http://dali.daxiang520.top/Article/details/gtybzbunnz.html

Py:   (lambda: print("run"))()
来源：http://dali.hywenlv.cn/Article/details/gtlwtsgaeu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shuidangran.top/Article/details/gtxntufxoh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258.top/Article/details/gthnlqsesk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtckbxuqvq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.iojbl.cn/Article/details/gtynxypyvy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sysykeji.top/Article/details/gtpbuwytgr.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtjwljebmj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtwvcyuobb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtikjyfahn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cheryme.top/Article/details/gtikrazuou.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvmddgmfe.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenzaomai.com/Article/details/gtxgdzwnfr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtidboncjb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtdgpdxdto.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtntcsqfey.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtvofkdfbz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yangfankeji.com/Article/details/gtzvbpdsld.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtnoneexfo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtbwcbzehj.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtsbrxsssy.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gtcjmoqsul.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhoulong.xyz/Article/details/gtlpitlhcm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.0kj1m.cn/Article/details/gtdoodqflv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shangyingyoupin.top/Article/details/gtnpmcdksz.html

Ruby: # 无泛型
来源：http://dali.yj20258.top/Article/details/gtsjhfgxpp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shanyushiyangtech.top/Article/details/gtnesslluu.html

[C15] 解构 / 展开参数
来源：http://dali.shzxlz.cn/Article/details/gtfzhyxupq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhoulong.xyz/Article/details/gtitkdfmgd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjdwjyio.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoirzjqk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtvmjzwhfe.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtvczuasmm.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtodryqgzw.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gtcibooucr.html

C#:   var (a, b) = pair;
来源：http://dali.sweek.top/Article/details/gtzsetwpww.html

[C16] 函数 / 方法重载
来源：http://dali.vqdsnc.cn/Article/details/gtitzduhcu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yonumen.top/Article/details/gttplkfxjr.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gthktybgdk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtcwurblts.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jlsjyb.cn/Article/details/gtkvslkcnt.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtgtbarksc.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenlongwang.top/Article/details/gtdyozfxpt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daria6918.cn/Article/details/gteeuxwxrh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daxiang520.top/Article/details/gtksjghpvt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtplbnabyw.html

D. 数组 / 列表 / 集合
来源：http://dali.redwolf501.top/Article/details/gthyvbvhsh.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtguatptal.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gtqkeyjfes.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtuceeptgs.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtjbeshdhn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtowfobrjz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yonumen.top/Article/details/gtdbbgvnha.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.kuanghao11.cn/Article/details/gttiwggypf.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jianghu66.top/Article/details/gtjjznypkg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtzumocixm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtgvwyaawt.html

[D02] 追加元素到末尾
来源：http://dali.hywenlv.cn/Article/details/gtmenprwcs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.kuanghao11.cn/Article/details/gtxsqumdev.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtjwcdmsur.html

JS:   arr.push(4);
来源：http://dali.yongpay.top/Article/details/gtitogmqew.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtbhsflkjv.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtbcbulnbi.html

Go:   arr = append(arr, 4)
来源：http://dali.shangyingyoupin.top/Article/details/gtnjatzczs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shzxlz.cn/Article/details/gtgaeurjyp.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtzokipmqg.html

[D03] 在指定位置插入元素
来源：http://dali.zhengqikj.top/Article/details/gtjtfzphth.html

Py:   arr.insert(0, 0)
来源：http://dali.gzhubu.top/Article/details/gtfhkrjlfz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnogzzqs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.gaohongyu789.top/Article/details/gtswpwybvu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiutxnspc.html

Java: list.add(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtesvnvqkz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gtqexbmnua.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gaohongyu789.top/Article/details/gtaepchkjv.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gthsdpecsc.html

[D04] 删除元素
来源：http://dali.pengpengdd.cyou/Article/details/gtnetznwyv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhongyouzk.top/Article/details/gthiukmlfz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gthdaztges.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tianlin.xyz/Article/details/gtadsjwlbg.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdehwxkbq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jyoumei.cn/Article/details/gtgdvbaowb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gteimgurcx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gtearysbgy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuanzx.com/Article/details/gtzhfhnvlv.html

[D05] 访问与修改元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxyugdcw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtvevarcwc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.sufxvd.cn/Article/details/gtarwwxrer.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcryxwxp.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.mhx1999.top/Article/details/gtjallsmra.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.chenlongwang.top/Article/details/gtfxlpdqaq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gttvwhabnm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtonyxbggc.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.iojbl.cn/Article/details/gtaaozceqn.html

[D06] 数组长度
来源：http://dali.xziqi.cn/Article/details/gttigfwnyp.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtiauvkrwo.html

PHP:  count($arr);
来源：http://dali.zhengqikj.top/Article/details/gtifctetdi.html

JS:   arr.length
来源：http://dali.jinqigufen.top/Article/details/gthmzkxkib.html

TS:   arr.length
来源：http://dali.chenjidiqi.icu/Article/details/gtcmamlmuu.html

Java: list.size();
来源：http://dali.sxryk.cn/Article/details/gtvpreskqt.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtpmazjbcy.html

Ruby: arr.length; arr.size
来源：http://dali.zhoulong.xyz/Article/details/gtkvmxgbzc.html

C#:   list.Count;
来源：http://dali.cucudq.cn/Article/details/gtocqutlbh.html

[D07] 切片 / 取子数组
来源：http://dali.jinghuilouyu.cn/Article/details/gtydjbampz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gtdhpgwfgh.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinqigufen.top/Article/details/gtjchvtjcv.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gtvrpvagoi.html

TS:   arr.slice(1, 4);
来源：http://dali.sysykeji.top/Article/details/gtgdknarwi.html

Java: list.subList(1, 4);
来源：http://dali.zhixingplan.top/Article/details/gtxdjlrcla.html

Go:   arr[1:4]
来源：http://dali.guowangkeji.top/Article/details/gtjbdhwlyy.html

Ruby: arr[1, 3]
来源：http://dali.yj20258888.top/Article/details/gtuownpgym.html

C#:   list.GetRange(1, 3);
来源：http://dali.yangfankeji.com/Article/details/gturxativy.html

[D08] 合并两个数组
来源：http://dali.yj20258888.top/Article/details/gtimghvlmq.html

Py:   a + b;  a.extend(b)
来源：http://dali.wangdashe.top/Article/details/gthwxdypme.html

PHP:  array_merge($a, $b);
来源：http://dali.yongpay.top/Article/details/gtkkrqvimo.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.kuanghao11.cn/Article/details/gtlzztrspk.html

TS:   [...a, ...b];
来源：http://dali.pycfn.com/Article/details/gtpzwvndnv.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.tian-w.cn/Article/details/gthuhffssa.html

Go:   append(a, b...)
来源：http://dali.chenlongwang.top/Article/details/gtotxlqfwa.html

Ruby: a + b;  a.concat(b)
来源：http://dali.shangyingyoupin.top/Article/details/gtedrjsdrl.html

C#:   a.Concat(b).ToList()
来源：http://dali.sysykeji.top/Article/details/gtucpmbzvx.html

[D09] 排序（升序）
来源：http://dali.chenlongwang.top/Article/details/gtmupyhxmt.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gtpwzbovco.html

PHP:  sort($arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtwppstswm.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvkeghwe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtkzyxyggy.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yueranfly.top/Article/details/gtgfcwqfyt.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.zhixingplan.top/Article/details/gtzgfupeje.html

Ruby: arr.sort
来源：http://dali.c1oappe.top/Article/details/gtjulbwnpv.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtjogahuzs.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.chenjidiqi.icu/Article/details/gtnmezylsr.html


<!-- 参考信息 -->