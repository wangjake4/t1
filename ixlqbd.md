代发 wailian999

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gznrbqcz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2wicsdnuq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gt2ihpnldtc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gt2yrwlmtge.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2krofopnb.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gt2pqhlwypn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sxryk.cn/Article/details/gt2tbedgjnl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gt2aqqpmqjk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gt2zcmkyanj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gt2mfoklrsi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gt2biygirye.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gt2ksuswwuh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gt2iibhmkkc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxinkj.top/Article/details/gt2gbyylwqe.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gt2ujlaymqj.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gt2ybfvotbn.html

PHP:  range(0, 10, 2);
来源：http://dali.yangfankeji.com/Article/details/gt2pdlrwqlc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2paucumnb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2aiztdtgo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnqzz.top/Article/details/gt2vcyrfsvn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gt2smzcvord.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gt2nqvyghul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gt2uizptwsx.html

[B12] 跳出多层循环
来源：http://dali.0kj1m.cn/Article/details/gt2tbilxgxr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gt2kuudaqcr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gt2gdnmbdqx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gt2ohveejtw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gt2ufmomrem.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gt2mgxfvwex.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gt2zyjsooyv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zhxqjdpu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tanke756.top/Article/details/gt2uohhbdyo.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gt2cdkqgtav.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gt2bxnmwwsm.html

PHP:  is_numeric($x)
来源：http://dali.9152youxi.cn/Article/details/gt2ieyvgead.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hedxjukx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2lyogfqkc.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gt2oriztxhf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gt2bztjmhga.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gt2kahoqgsy.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gt2qnpszyjw.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gt2pcsjxied.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2qsddyimq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gt2zpmbwgew.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gt2hexlbkai.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2xitgikbn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2tewqnfbw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gt2jyytoozw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yueranfly.top/Article/details/gt2juaeqnyt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qtyrsqoo.html

[B15] 布尔运算与取反
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpnavfzy.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gt2qirvhpal.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gt2dmhogaft.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2xfldpwqn.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2vjjsliti.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2bhahrooi.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gt2qvwbpgpc.html

Ruby: a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gt2wqidqfij.html

C#:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2vkcsbkns.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gt2lzrpgptw.html

Py:   if not data: return
来源：http://dali.yj20258.top/Article/details/gt2qldmexcy.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gt2ntdnyppd.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gt2cnbkgrne.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2mhgywhws.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gt2bzbqbdhr.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gt2ollyntyf.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gt2yggylgih.html

C#:   if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gt2xuiwdgei.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2kwlhimeu.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gt2cokzmrqx.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pprgcfht.html

[C01] 定义函数
来源：http://dali.kuanghao11.cn/Article/details/gt2kuyccvab.html

Py:   def add(a, b): return a + b
来源：http://dali.jyoumei.cn/Article/details/gt2axrxxdav.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2etywgnjm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2mbnbuhcs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2xcbnccbs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2zyucpjha.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2xjepvskc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gt2urhepdqa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2qesrtmrr.html

[C02] 默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2qonysuxk.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2hrfpbjzu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sufxvd.cn/Article/details/gt2fxuxyvmh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gt2isexjodm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2ormzaupr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2tiglfppl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2piensvmc.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gt2qnlgqiim.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.c1oappe.top/Article/details/gt2dkbkszhl.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gt2aissxxam.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2hxdxaajs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gt2oylducsq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gt2voegxmud.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gt2dpnakjbv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gt2khkwojkc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gt2lkjjupoj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2gumwkuvn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj202588.top/Article/details/gt2vprfoyua.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gt2wzvitumk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenzaomai.com/Article/details/gt2secegami.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gt2nnqrscyu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2mahsuckw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gt2uugjmrbw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xziqi.cn/Article/details/gt2axlojmlo.html

Go:   // 无：用配置结构体参数
来源：http://dali.yongpay.top/Article/details/gt2xrspmqmw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gt2bxknxwes.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gt2momcgxem.html

[C05] 返回多个值
来源：http://dali.pycfn.com/Article/details/gt2azdcvupd.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gt2dlgcxccl.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gt2lrtvbxwa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gt2bqdrlfra.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2bmcgypnc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yongpay.top/Article/details/gt2izfmyqzu.html

Go:   return a, b
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiloyemq.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2bqbyivar.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zycfv.cn/Article/details/gt2exmhjvlt.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2kabnhrjj.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gt2xmpjfvgf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj202588.top/Article/details/gt2dmaxbvvp.html

JS:   const square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2dkmghxfh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gt2beqplrgn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2lsezbkto.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.redwolf501.top/Article/details/gt2zwcublet.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gt2kosaeegf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gt2rmddduqj.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gt2nghphqid.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cheryme.top/Article/details/gt2gucfgjjf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gotoacloud.top/Article/details/gt2nzhxuxhv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.bjfxy.top/Article/details/gt2bhsauell.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gt2fqylgrlu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gt2ysccidil.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2rkegluko.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gt2exsipowz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gt2rewfeael.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gt2xrybxagl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.havefunace.top/Article/details/gt2waesxzxa.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2edelthke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2mtzsxipe.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gt2ioaxkdzu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gt2ieppyiuh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2xkgroaub.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2oxjltdjx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gt2fnnapefc.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gt2rtnbpyuq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2dryyrebx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2dzannzkz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.andypj.xyz/Article/details/gt2owfpknvc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gt2czainwar.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gt2irjhztkf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gt2ccghqisa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2eoybdnao.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gt2wnajnhlw.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rydjknde.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yuxming.cn/Article/details/gt2qiipnttn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2duetyzow.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnqzz.top/Article/details/gt2cggovlyv.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gt2mlyzgxxc.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2zyzlxucj.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2fjsexsfy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sufxvd.cn/Article/details/gt2ewnykqzz.html

C#:   块级作用域
来源：http://dali.havefunace.top/Article/details/gt2vkcvehme.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gt2ldfxemzt.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gt2yscczyfa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gt2ljvkkfeu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gt2waaejlcc.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gt2kiagxukh.html

Java: import java.util.List;
来源：http://dali.hammf.cn/Article/details/gt2uznrwqfo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gt2rrruzesl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gt2ikytdmjh.html

C#:   using System.Text;
来源：http://dali.ppjwa.cn/Article/details/gt2jzgviklt.html

[C12] 立即执行函数 IIFE
来源：http://dali.kuanghao11.cn/Article/details/gt2dzwnjwhs.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gt2vluzuqps.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xziqi.cn/Article/details/gt2gbtdndwe.html

JS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gt2gbqxksex.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gt2tjdqvdnn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeuxcqkq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2sibttlqi.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigfzy.top/Article/details/gt2cxsdhqvt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.c1oappe.top/Article/details/gt2dxsajdlx.html

[C13] 类型声明 / 类型注解
来源：http://dali.zycfv.cn/Article/details/gt2exskclpb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2ydxinmib.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2ujkmrgne.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2ftenhzto.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cbaeqafg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeffvjxv.html

Go:   func add(a, b int) int
来源：http://dali.zycfv.cn/Article/details/gt2zvafuzrg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yongpay.top/Article/details/gt2nkupytae.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2bfnzanhj.html

[C14] 泛型函数
来源：http://dali.iojbl.cn/Article/details/gt2zafpylvj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gt2nikfcrfo.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gt2tchrptvb.html

JS:   // 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2ubfnlnta.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gt2ehyiboez.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2imxkpbcw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hfpthk.cn/Article/details/gt2dneiqhie.html

Ruby: # 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2wzpkqtwv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.c1oappe.top/Article/details/gt2hotzrcqb.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gt2srsetykv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.kuanghao11.cn/Article/details/gt2hvrkodgm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gt2pidqzvzc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2zscovmqc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2vymmxlvp.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2xkftfvit.html

Go:   // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2qtyrbcqh.html

Ruby: a, b = pair
来源：http://dali.gaohongyu789.top/Article/details/gt2nbfxtvmu.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gt2eixejrps.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gt2eiocbscw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkowkhtc.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gt2vzjmuevg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhongyouzk.top/Article/details/gt2lnzrldnm.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gt2jdpundad.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuanzhike.top/Article/details/gt2llkpmuoj.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2rezkrzll.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gt2yqpihpjb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jdyypsnm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2qrdzaegk.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gt2iufuvrnf.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ktlvdugt.html

[D01] 创建数组 / 列表
来源：http://dali.hammf.cn/Article/details/gt2wmjzmhjg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gt2irvmradb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2plogcvho.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.havefunace.top/Article/details/gt2ipcvpuqg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tian-w.cn/Article/details/gt2kyzbjcmd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gt2ewndjdmk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.jinqigfzy.top/Article/details/gt2lyvfjgkp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ehwqpu.com/Article/details/gt2jlkfxpfr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gt2qayldonf.html

[D02] 追加元素到末尾
来源：http://dali.yuxming.cn/Article/details/gt2ywvcxqkj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zfppacdf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gt2xqbjjjvs.html

JS:   arr.push(4);
来源：http://dali.0kj1m.cn/Article/details/gt2edmnngea.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gt2gonxapju.html

Java: list.add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2migvhhca.html

Go:   arr = append(arr, 4)
来源：http://dali.daxiang520.top/Article/details/gt2mhukjlsu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ehwqpu.com/Article/details/gt2ylaeajqm.html

C#:   list.Add(4);
来源：http://dali.hammf.cn/Article/details/gt2nmssqbty.html

[D03] 在指定位置插入元素
来源：http://dali.hammf.cn/Article/details/gt2zghcmpxc.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2hcvxlwnk.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.iojbl.cn/Article/details/gt2wvlnsdfv.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tian-w.cn/Article/details/gt2fydlamen.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jyoumei.cn/Article/details/gt2bsjseltd.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gt2mwvgzybk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gt2nxyteiry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.smart0.xyz/Article/details/gt2bwstwmzo.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2dalqypbb.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gt2bdkrsvdk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tanke756.top/Article/details/gt2nmcctqah.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jiagoushi.top/Article/details/gt2urxsxkvt.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alkdhdab.html

TS:   arr.splice(0, 1);
来源：http://dali.kuanghao11.cn/Article/details/gt2spbcftwu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cheryme.top/Article/details/gt2uzmsadqz.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhoulong.xyz/Article/details/gt2rmgveljb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hysaishi.cn/Article/details/gt2otfbzcjl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yongpay.top/Article/details/gt2ctuhqimj.html

[D05] 访问与修改元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2vrbtprbs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fengsongda.top/Article/details/gt2kowkuejd.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2nycmqfcz.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qduyslzb.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fengsongda.top/Article/details/gt2qjcnsrrs.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.tanke756.top/Article/details/gt2lvqfwytk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2ufpwsast.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gt2xoclfzgj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.daxiang520.top/Article/details/gt2kxujexyn.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gt2gavvnoxt.html

Py:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gt2bxoyfuoz.html

PHP:  count($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2loeopcpj.html

JS:   arr.length
来源：http://dali.jyoumei.cn/Article/details/gt2xqrhyvsm.html

TS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gt2ihurgfzb.html

Java: list.size();
来源：http://dali.hfpthk.cn/Article/details/gt2ayamprjo.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2bjcgzzcl.html

Ruby: arr.length; arr.size
来源：http://dali.hammf.cn/Article/details/gt2bmfohlzh.html

C#:   list.Count;
来源：http://dali.nanxinkj.top/Article/details/gt2jkcseffu.html

[D07] 切片 / 取子数组
来源：http://dali.daria6918.cn/Article/details/gt2leybqotm.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.shuidangran.top/Article/details/gt2dcucigxn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.yuanzhike.top/Article/details/gt2srhximiy.html

JS:   arr.slice(1, 4);
来源：http://dali.yuanzhike.top/Article/details/gt2akhtcczd.html

TS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gt2dxkwrsgf.html

Java: list.subList(1, 4);
来源：http://dali.hongshengwenyu.top/Article/details/gt2rsjnkspe.html

Go:   arr[1:4]
来源：http://dali.yonumen.top/Article/details/gt2gjliqvxo.html

Ruby: arr[1, 3]
来源：http://dali.cdnleiting.top/Article/details/gt2lsulpdif.html

C#:   list.GetRange(1, 3);
来源：http://dali.jinqigufen.top/Article/details/gt2kppiyoam.html

[D08] 合并两个数组
来源：http://dali.pycfn.com/Article/details/gt2rnxjgjhr.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gt2qidalpvw.html

PHP:  array_merge($a, $b);
来源：http://dali.wangdashe.top/Article/details/gt2kkbvcejx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.mhx1999.top/Article/details/gt2esgyozxn.html

TS:   [...a, ...b];
来源：http://dali.jinqigufen.top/Article/details/gt2xtdkdjky.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ehwqpu.com/Article/details/gt2hejuopnl.html

Go:   append(a, b...)
来源：http://dali.zhengqikj.top/Article/details/gt2kfzhbotr.html

Ruby: a + b;  a.concat(b)
来源：http://dali.yj20258888.top/Article/details/gt2gifslmkv.html

C#:   a.Concat(b).ToList()
来源：http://dali.guowangkeji.top/Article/details/gt2grvrhtzb.html

[D09] 排序（升序）
来源：http://dali.9152youxi.cn/Article/details/gt2tvmsewvy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.shuidangran.top/Article/details/gt2upovylwg.html

PHP:  sort($arr);
来源：http://dali.gogol.net.cn/Article/details/gt2rzjtziqg.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.dianchejie.cn/Article/details/gt2iiphbcfe.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.snrcjt.cn/Article/details/gt2nmalyynm.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbbruobc.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.chenzaomai.com/Article/details/gt2dbiopatd.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gt2uddeksla.html

C#:   list.Sort();
来源：http://dali.gzhubu.top/Article/details/gt2bcmlwbyw.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.gzhubu.top/Article/details/gt2nkkyoqty.html


<!-- 参考信息 -->