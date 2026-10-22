代发 wailian999

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtokzmrqig.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtforflvqo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtayeqkqyb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtjavufkaj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfyuahgz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.vqdsnc.cn/Article/details/gtiqewjmdm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gtekirsyrj.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtoloyuyvb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtvgjuuddb.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqsjthgyt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gtkdrzokvg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gotoacloud.top/Article/details/gtgyyrojuy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtcfcoblnr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtrqfsdwut.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gtfqvjdxql.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtanxtraax.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtbrhwvpck.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbylpxpfk.html

[B11] 生成数字序列 / 区间
来源：http://dali.cucudq.cn/Article/details/gtauqkgitr.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtcegobpdj.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtpzsuzfzl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtqfomuyay.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xziqi.cn/Article/details/gtdasnifio.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtszaixnfw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtnwykrxtp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtzcrhqufq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ydzc1.top/Article/details/gtwqsccfqa.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtjjqfdbxy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangdashe.top/Article/details/gtknhzftdq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gtnxxhodri.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtdiwrznkn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtfkvrgcwl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtnhqsyfdk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuftcroia.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yangfankeji.com/Article/details/gtjmjzogur.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtzfacwpka.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtdlpdkrkm.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtqzelqwtp.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtwoatnjes.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtrnxeqhgy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtlkrkrvrb.html

Java: x instanceof Number
来源：http://dali.aizwys.cn/Article/details/gtyyaabhur.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.0kj1m.cn/Article/details/gtxaiszqof.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sxryk.cn/Article/details/gtdybwikhj.html

C#:   x is int or double or decimal
来源：http://dali.havefunace.top/Article/details/gtkonmydtt.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtchazlkrl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtyttqyvgy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtrhnqocnt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiynsdphe.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtpyuenkox.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtdzrkocjw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtvxnxhcjp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.quarkkingdee.top/Article/details/gtfurcdwta.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqmibbpc.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtgxncufzv.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtazyukfwg.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtgcjfvnvi.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtdxskzkta.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtgjtrbtgi.html

Java: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtldwwvmet.html

Go:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtlhemoaon.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtjrndbcrx.html

C#:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtitffjhkj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gtwnhzepik.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtsgitbldm.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzbgjakf.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gtfiimujsq.html

TS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtsphjwgjc.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtchhikkeu.html

Go:   if data == nil { return }
来源：http://dali.yj202588.top/Article/details/gttrmtmwdt.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqnshqab.html

C#:   if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtuwmduaax.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtjgladoww.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtsvbmtbcb.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttpswtbmw.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtbjrdfxmq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gtzxzvxcod.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtseruhetd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtavgnrrxx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtywpaxlhm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtskkyiusi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtwcwwxonj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtgdxcpayr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtloeyqnrk.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtyxdjpsqa.html

Py:   def greet(name="World"): return name
来源：http://dali.daria6918.cn/Article/details/gtnmefipbg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtlauiqvwk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.redwolf501.top/Article/details/gtrvcxocmf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pycfn.com/Article/details/gtdqdkztgs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtoccbjviy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.gzhubu.top/Article/details/gtnyuyzozs.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gtysfawnqj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtqruvsbbc.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gtswotuvye.html

Py:   def total(*args): return sum(args)
来源：http://dali.andypj.xyz/Article/details/gtlwknrrbx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyknatrta.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtaefbleyp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtatclqgak.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.redwolf501.top/Article/details/gtgiuzjkaz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gtktwlmdws.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtdlmhlcnu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gtbjmuvvds.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtegjykqxw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guowangkeji.top/Article/details/gtzhmddbwc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gthprvobpr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yueranfly.top/Article/details/gtvypjtcwt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gtahufqxnq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtonhahgbr.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gtjfflixcy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtgcvvcljn.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtauqsbxgd.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtccieshqa.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtqdskbrdx.html

PHP:  return [$a, $b];
来源：http://dali.yj20258888.top/Article/details/gtyxtyqmbf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gteyaibdnt.html

TS:   return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtquzrcdsw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.kuanghao11.cn/Article/details/gtnyysclbk.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtdfvprjzr.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtcbcsttgr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtwczqywqh.html

[C06] 匿名函数 / lambda
来源：http://dali.jiagoushi.top/Article/details/gtactoewbv.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gtcggajvhu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.guowangkeji.top/Article/details/gtkvdfkdhb.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtbzyouydv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gtnlpuiirq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtmhavumkr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtxljbcnlh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258888.top/Article/details/gtwcsvhgdt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gtkgrdcwin.html

[C07] 把函数作为参数传入
来源：http://dali.tian-w.cn/Article/details/gtllfybkmr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj202588.top/Article/details/gtwrxtssmn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtgjaisuvv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtbsvshdcf.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtaazfjanb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnqzz.top/Article/details/gthawkwqhw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtxtmnrwhn.html

Ruby: arr.map(&:upcase)
来源：http://dali.cdnleiting.top/Article/details/gtbcvsebmo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jyoumei.cn/Article/details/gthhuhqnfm.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtjzutqrzv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gtiwpdzqtk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.nwbrower.top/Article/details/gtsdkdfbvh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtasrembqy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gteoyepwsh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangshuangyany.cn/Article/details/gtgcxoaibb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.mhx1999.top/Article/details/gtswhpdjkl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtjhevzqjo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtafiutmvx.html

[C09] 递归
来源：http://dali.hammf.cn/Article/details/gtbnrrmuan.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtzzplylqq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.pycfn.com/Article/details/gtpfbtzwnp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtcksdkceq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtcggifxkr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.sweek.top/Article/details/gtajfpkaag.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtiedznspl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtpgxfjrda.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtaxrigztt.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtkawqizoh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtfmlnqyms.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxuanxn.top/Article/details/gtekrhdbqi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinqigufen.top/Article/details/gtovbvavzt.html

TS:   同 JS
来源：http://dali.gzhubu.top/Article/details/gticovscjl.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtstegqyjj.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtvvnscbbc.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gtkgcdodxr.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtxomroxij.html

[C11] 模块导入与导出
来源：http://dali.yongpay.top/Article/details/gtohoyfdfn.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtdvfekact.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jiagoushi.top/Article/details/gtxgkpuuag.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtgjjbpqup.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxqxcxys.html

Java: import java.util.List;
来源：http://dali.hnxiangtu.top/Article/details/gtzsgdijbe.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hysaishi.cn/Article/details/gtooifcitz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtiveoamyo.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gtbniiklud.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhongyouzk.top/Article/details/gtmrrmugrh.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncxpwbpr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.316326.xyz/Article/details/gtngtesjxz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hysaishi.cn/Article/details/gtljbnkeld.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gttjnzmjtc.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtowalpqbh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtkpclyqty.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gtzrlikhmw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gtacburprv.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtehpggtwj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtgukcremq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtgdhnoffp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gttjltmtjl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtprzbipyu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtxsklbjly.html

Go:   func add(a, b int) int
来源：http://dali.zhongyouzk.top/Article/details/gtwzuuwlbz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhchzeqq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtufohtzhx.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtpcrczomq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gtlvoqjmur.html

PHP:  // 无泛型
来源：http://dali.havefunace.top/Article/details/gtecsxkqlf.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gteogccgsc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.0kj1m.cn/Article/details/gtoeeqiukt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gtskktiinr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gtdeytpzyx.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtitlwrfxc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gtbfchtehr.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdmljnskv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtzkvsbumn.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhnmrjhu.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gtusktidbp.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yj20258888.top/Article/details/gtotmmhmyi.html

Java: // 无解构
来源：http://dali.ivvv.top/Article/details/gtcdachlmv.html

Go:   // 无解构
来源：http://dali.dashuyun.cn/Article/details/gtvlxkazpm.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtovqwklhv.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtnarrnpoo.html

[C16] 函数 / 方法重载
来源：http://dali.xziqi.cn/Article/details/gtxltkowly.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.0kj1m.cn/Article/details/gtffupciia.html

PHP:  // 无重载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmsoyhrmm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gtmizfmnog.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ppjwa.cn/Article/details/gtngoegrhr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yongpay.top/Article/details/gtwjkebkce.html

Go:   // 无重载：用不同函数名
来源：http://dali.ydzc1.top/Article/details/gtlxgrnljs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gttdsalewv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.bjfxy.top/Article/details/gtafuotitj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtlvorybhs.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtwrpxqcfp.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtcvcujejh.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtvgjxioqq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenjidiqi.icu/Article/details/gtfhggouss.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.bjfxy.top/Article/details/gtheqmxbzl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtnznxhfvc.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtnanxcrsp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.cdnleiting.top/Article/details/gtxutslrae.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtzutatdlz.html

Ruby: arr = [1, 2, 3]
来源：http://dali.havefunace.top/Article/details/gtevxqpckd.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtptjspsux.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtwnitagmh.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtkkgkaguv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hfpthk.cn/Article/details/gtoriiluob.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtqpjtnkub.html

TS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtdspwrhhd.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gthdokraxc.html

Go:   arr = append(arr, 4)
来源：http://dali.haohaochexian.top/Article/details/gttvesrhfg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtdvfiyviw.html

C#:   list.Add(4);
来源：http://dali.aibaodan.cn/Article/details/gtqtfaoqls.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtmiesqwal.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtendqmddk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtybboofss.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gthhxvtjuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.daria6918.cn/Article/details/gtajudnwna.html

Java: list.add(0, 0);
来源：http://dali.ybcxt.top/Article/details/gtvrfstuim.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.bjfxy.top/Article/details/gtbhpymuem.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsserbyvi.html

C#:   list.Insert(0, 0);
来源：http://dali.hfpthk.cn/Article/details/gtxtitcvol.html

[D04] 删除元素
来源：http://dali.guannengcc.top/Article/details/gtrlorilcq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258.top/Article/details/gthvzbwhiy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtpubpolnf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtjwmkrcmj.html

TS:   arr.splice(0, 1);
来源：http://dali.zhongyouzk.top/Article/details/gtbjvwbxne.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yongpay.top/Article/details/gtahoqsbtq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtfbxwcava.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yvedp.cn/Article/details/gthorvktpn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtfbhsfpis.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtswnymecn.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gtgrmbygmn.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtleriervm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtcaejdyfu.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zdqjudy.top/Article/details/gtbwzpsogn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtvkfyxurg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtbsmeblhn.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtehosuyvo.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtkhzzpenx.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtpipklgkd.html

Py:   len(arr)
来源：http://dali.316326.xyz/Article/details/gtkyuggpgl.html

PHP:  count($arr);
来源：http://dali.tanke756.top/Article/details/gtonukcktg.html

JS:   arr.length
来源：http://dali.cheryme.top/Article/details/gtfvvredpj.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtpkzozlep.html

Java: list.size();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrokhvhyn.html

Go:   len(arr)
来源：http://dali.yanxiufei.cn/Article/details/gtlauuvblq.html

Ruby: arr.length; arr.size
来源：http://dali.chenjidiqi.icu/Article/details/gtqbcshape.html

C#:   list.Count;
来源：http://dali.sysykeji.top/Article/details/gtiucnynrh.html

[D07] 切片 / 取子数组
来源：http://dali.dianchejie.cn/Article/details/gthwqamrth.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.kuanghao11.cn/Article/details/gtpzjnxhwp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtjpjptknh.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtjltsyyaf.html

TS:   arr.slice(1, 4);
来源：http://dali.zhijiandao.cn/Article/details/gtkuqyejhm.html

Java: list.subList(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtlcdwtxwx.html

Go:   arr[1:4]
来源：http://dali.cucudq.cn/Article/details/gtaqwghlwx.html

Ruby: arr[1, 3]
来源：http://dali.zhixingplan.top/Article/details/gtwrayvnon.html

C#:   list.GetRange(1, 3);
来源：http://dali.yonumen.top/Article/details/gtaqnewgtk.html

[D08] 合并两个数组
来源：http://dali.ybcxt.top/Article/details/gtpgcdqwpn.html

Py:   a + b;  a.extend(b)
来源：http://dali.zhixingplan.top/Article/details/gtooqkvynn.html

PHP:  array_merge($a, $b);
来源：http://dali.redwolf501.top/Article/details/gtwjnergxx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.meibo888.top/Article/details/gtbrfetmdl.html

TS:   [...a, ...b];
来源：http://dali.xylfe.cn/Article/details/gtfqexkerh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yueranfly.top/Article/details/gtkqafqyxe.html

Go:   append(a, b...)
来源：http://dali.gaohongyu789.top/Article/details/gtdgdbxefj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gtbtdxteqn.html

C#:   a.Concat(b).ToList()
来源：http://dali.hammf.cn/Article/details/gtebpfswfm.html

[D09] 排序（升序）
来源：http://dali.quarkkingdee.top/Article/details/gtmftwjsoy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.zhijiandao.cn/Article/details/gtogsfzraf.html

PHP:  sort($arr);
来源：http://dali.jqgufenzy.top/Article/details/gtyypfpizp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.sufxvd.cn/Article/details/gtimyxgfdc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yangfankeji.com/Article/details/gthkhwnfub.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtvcuaaucd.html


<!-- 参考信息 -->