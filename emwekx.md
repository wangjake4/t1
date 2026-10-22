代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gt2dpthegqd.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gt2iudpdlng.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gt2wyeojmhf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gt2rhdvjakt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2lwwobpvo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gt2yfdbesut.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gt2dnqlkqyj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2sjkdeytj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gt2upkfhnet.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2shmekjdk.html

[B11] 生成数字序列 / 区间
来源：http://dali.jlsjyb.cn/Article/details/gt2bzypuzvh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhongyouzk.top/Article/details/gt2khffglip.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gt2hnahmseq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lqgtcgqi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gt2sutjxtrg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj202588.top/Article/details/gt2udegnxzo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2zehgnprh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gt2fflbrwto.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dduhxbur.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2ibwurcte.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gt2sznriymj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gt2dzsqmvyg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2evqlaean.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2lwlirruc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2eqgdeixc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2impxdywz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gt2jiwwjoxu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gt2gmhysqub.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2thlzaxuo.html

Py:   isinstance(x, (int, float))
来源：http://dali.birdmap.top/Article/details/gt2nnbufpvt.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gt2rxsiswgf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gt2dlpiweuh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2vaivzncz.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gt2iayrbqsr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gt2qojjauov.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uvhldfeq.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gt2vwigfxze.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkcfprbu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gt2pmnsewue.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gt2tpmtnytc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gt2wnfmftwr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gt2qlxmbbxu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gt2lnyygkdx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gt2anipumdu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2xxpoepad.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2hsogiudr.html

[B15] 布尔运算与取反
来源：http://dali.cqqwz.cn/Article/details/gt2agxfmpur.html

Py:   a and b or not c
来源：http://dali.xuetiantiany.cn/Article/details/gt2icfbscqw.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gt2twcajqzq.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnleeajy.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2qqrsrlqz.html

Java: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2iahhkttu.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2mdgspgnw.html

Ruby: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gt2sdartikh.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2fzopseav.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gt2dohaamoc.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gt2tkoostzi.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gt2zmxbvbqh.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gt2vplzhdyd.html

TS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2ygvqhgyi.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2sotkiiir.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gt2kxeitgcu.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gt2ibnrlhpk.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwmogkus.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ftvjmtzl.html

C. 函数与作用域
来源：http://dali.hfpthk.cn/Article/details/gt2srluwklz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2talgnkzf.html

[C01] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gt2djthxazn.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pcznlmsb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gt2fdxvvjde.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2fmicehyk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2euvfxvvb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2gdthbidg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2sbbhwavj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sxryk.cn/Article/details/gt2koqyihjv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2cimwqhhv.html

[C02] 默认参数
来源：http://dali.sufxvd.cn/Article/details/gt2xvbcentw.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gt2vlsylsst.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gt2swowngmw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gt2wytnfnpd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gt2jozuxjrb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gt2klythlrd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enerercb.html

Ruby: def greet(name = "World") = name
来源：http://dali.jlsjyb.cn/Article/details/gt2bcliopvo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gt2ttuderqx.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gt2lynlppwq.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gcjnbrlf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhoulong.xyz/Article/details/gt2qvcjfgpm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2oikikamm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gt2amywnbqk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yanxiufei.cn/Article/details/gt2fzhtvywp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2fpgxuwac.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shangyingyoupin.top/Article/details/gt2qmqpjumb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gt2xwcvclav.html

[C04] 命名参数 / 关键字参数
来源：http://dali.daxiang520.top/Article/details/gt2zwebcxqz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gt2cbrydfxs.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.kuanghao11.cn/Article/details/gt2wbnsnjdo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2hyryduan.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gt2wwlfzssd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ppjwa.cn/Article/details/gt2fpvfgyhz.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gt2hjqimoma.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gt2pztqllla.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2skbtwpya.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gt2iymyhlmt.html

Py:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2gmmywviw.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2lgpipsgw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qlozhlux.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gt2ztbpifbp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yvedp.cn/Article/details/gt2hgsitlox.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2usvuzvev.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2hufdppul.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.feifeiyinyue.top/Article/details/gt2glbwgbgk.html

[C06] 匿名函数 / lambda
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqzmstnq.html

Py:   square = lambda x: x * x
来源：http://dali.zycfv.cn/Article/details/gt2qrvhpitr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gt2ibdwgubl.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2ajhxihgh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2nerfkjis.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.haohaochexian.top/Article/details/gt2ekvtwcxe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gt2yckvqxzj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.9152youxi.cn/Article/details/gt2hwsmshfb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2egkemtio.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gt2idoxcduw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gt2zapcwiaz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2jczfcncq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhoulong.xyz/Article/details/gt2rszomqxo.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gt2wobdnudh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hnxiangtu.top/Article/details/gt2zdgaljnk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jqgufenzy.top/Article/details/gt2ybhlrels.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gt2jkejnknf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gt2nmxykeoz.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gt2ewxvdyvy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2jndmmexv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gqygggge.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sugzwvss.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gt2uudaofbu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yvedp.cn/Article/details/gt2ssaxrsib.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gt2gzawwggs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sysykeji.top/Article/details/gt2ixbbajim.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ugkkawpv.html

[C09] 递归
来源：http://dali.snrcjt.cn/Article/details/gt2maqyeudi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2tqstvhkt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ucrvidbe.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2cdgzevxm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gt2ctwzbovm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.andypj.xyz/Article/details/gt2caqthwal.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guowangkeji.top/Article/details/gt2idenxmnp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2gysnzgbx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.snrcjt.cn/Article/details/gt2lorbojlm.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gt2eeqmidhz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gt2jzwcwswd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.shzxlz.cn/Article/details/gt2ociphjfq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gt2extycasp.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gt2mfizskhz.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2wekoleiy.html

Go:   花括号块级作用域
来源：http://dali.cucudq.cn/Article/details/gt2ixxvcart.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yotopnyl.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gt2qmvkrccn.html

[C11] 模块导入与导出
来源：http://dali.gogol.net.cn/Article/details/gt2yleaehsh.html

Py:   from module import func
来源：http://dali.0kj1m.cn/Article/details/gt2gymnvrxa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cucudq.cn/Article/details/gt2gspijfov.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2pjohevno.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xuanzx.com/Article/details/gt2rqbrrsoy.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gt2xgwwcsze.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ehwqpu.com/Article/details/gt2kmssuyrh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.316326.xyz/Article/details/gt2miiquame.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gt2sxaeeoaq.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gt2mryisxjg.html

Py:   (lambda: print("run"))()
来源：http://dali.cucudq.cn/Article/details/gt2jctidkyq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gt2aebggewx.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gt2xufvpdpx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gt2dwgxvdra.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gt2zkvnekhp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gt2dasrizom.html

Ruby: -> { puts "run" }.call
来源：http://dali.jiagoushi.top/Article/details/gt2lkkwadym.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2suztjpxu.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vbimxmel.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gt2rfihviuf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2alphtmom.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gt2eidprclp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gt2nnxwzivo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qunuekvq.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gt2cbvoqxoi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwxmtkly.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fjevrowc.html

[C14] 泛型函数
来源：http://dali.yueranfly.top/Article/details/gt2jdjogtsx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yongpay.top/Article/details/gt2fcghovpq.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gt2izuzmids.html

JS:   // 无泛型
来源：http://dali.yvedp.cn/Article/details/gt2ckihhbww.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gt2elvkcpid.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzofpcxs.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.fzhhl.top/Article/details/gt2vsvgasoq.html

Ruby: # 无泛型
来源：http://dali.haohaochexian.top/Article/details/gt2elfipxvt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgufenzy.top/Article/details/gt2tkgipbsu.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gt2lxpqytuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zgoqkcpb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojmmjcbm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2cjgxvjoy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2bszxkxeg.html

Java: // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2zhffxtct.html

Go:   // 无解构
来源：http://dali.wangdashe.top/Article/details/gt2efsfqckl.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gt2hfdeldbb.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zpwntomy.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gt2xcihsmpy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ehwqpu.com/Article/details/gt2xrssajey.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gt2nsxaidcy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gt2lrigrlee.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xylfe.cn/Article/details/gt2ucvtyjtk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gt2mknbmxkc.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2zqdiprzi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sxryk.cn/Article/details/gt2epurnnkl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gt2zfltlcta.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bzcpxdpn.html

D. 数组 / 列表 / 集合
来源：http://dali.snrcjt.cn/Article/details/gt2aiorxjsf.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2bpptsjpu.html

[D01] 创建数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2itghvoov.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258.top/Article/details/gt2lkglzqht.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuanzx.com/Article/details/gt2uwlbmmiz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2wmmdvvbh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.daria6918.cn/Article/details/gt2ygoufmbe.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gt2mbfvtttt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gt2emjcqrgn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.smart0.xyz/Article/details/gt2cirpvque.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.meibo888.top/Article/details/gt2fkjeltym.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gt2fxvjhlbv.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnxiangtu.top/Article/details/gt2xxznzeqx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gogol.net.cn/Article/details/gt2adkqsaci.html

JS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2rahxwbbv.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2ecmazqts.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gt2zanapbte.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2fgrvjamm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gt2wgugtwcd.html

C#:   list.Add(4);
来源：http://dali.sweek.top/Article/details/gt2smrfqllu.html

[D03] 在指定位置插入元素
来源：http://dali.iojbl.cn/Article/details/gt2obnyfbpo.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gt2kponoicb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.quarkkingdee.top/Article/details/gt2nbikfvhi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gt2iopdfcuq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gt2cnjoxynf.html

Java: list.add(0, 0);
来源：http://dali.316326.xyz/Article/details/gt2efnubist.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gt2inzkczcg.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.andypj.xyz/Article/details/gt2lhvxbfvt.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2qamnwtvl.html

[D04] 删除元素
来源：http://dali.mhx1999.top/Article/details/gt2bwrojpay.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.snrcjt.cn/Article/details/gt2bgnbonau.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jqgfzy.top/Article/details/gt2fnvejotn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dashuyun.cn/Article/details/gt2phvilfmc.html

TS:   arr.splice(0, 1);
来源：http://dali.316326.xyz/Article/details/gt2sdiojscx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xylfe.cn/Article/details/gt2wxmplnpk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.kuanghao11.cn/Article/details/gt2pjfxkvnm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gt2tewdjvzt.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pngyctuo.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gt2fwwcscyk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aizwys.cn/Article/details/gt2iphgiyyu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gt2dxquiosa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pengpengdd.cyou/Article/details/gt2kgfeglst.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jiagoushi.top/Article/details/gt2ymzdehvu.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shuidangran.top/Article/details/gt2crpfteit.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gt2nyueizox.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gt2klnwgmtr.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gt2wfjjnyqv.html

[D06] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2lvqztcgb.html

Py:   len(arr)
来源：http://dali.gzhubu.top/Article/details/gt2jepgobmj.html

PHP:  count($arr);
来源：http://dali.guowangkeji.top/Article/details/gt2pminpyxw.html

JS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gt2ctoaijqh.html

TS:   arr.length
来源：http://dali.guowangkeji.top/Article/details/gt2eajidthc.html

Java: list.size();
来源：http://dali.wangdashe.top/Article/details/gt2gkunjpaw.html

Go:   len(arr)
来源：http://dali.gotoacloud.top/Article/details/gt2mxtqtzds.html

Ruby: arr.length; arr.size
来源：http://dali.kuanghao11.cn/Article/details/gt2khycsoin.html

C#:   list.Count;
来源：http://dali.jqgufenzy.top/Article/details/gt2gmcdfuiu.html

[D07] 切片 / 取子数组
来源：http://dali.kuanghao11.cn/Article/details/gt2lhflfvke.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinqigfzy.top/Article/details/gt2fmoydmkz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.zhengqikj.top/Article/details/gt2iicdtrie.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gt2kxcosajn.html

TS:   arr.slice(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gt2jgxkaszj.html

Java: list.subList(1, 4);
来源：http://dali.iojbl.cn/Article/details/gt2vdpogzly.html

Go:   arr[1:4]
来源：http://dali.andypj.xyz/Article/details/gt2utgvusqm.html

Ruby: arr[1, 3]
来源：http://dali.yuxming.cn/Article/details/gt2dpywvqhc.html

C#:   list.GetRange(1, 3);
来源：http://dali.xylfe.cn/Article/details/gt2vqrcnkcd.html

[D08] 合并两个数组
来源：http://dali.nwbrower.top/Article/details/gt2cxonydzy.html

Py:   a + b;  a.extend(b)
来源：http://dali.yj20258.top/Article/details/gt2mzjycoax.html

PHP:  array_merge($a, $b);
来源：http://dali.hammf.cn/Article/details/gt2dwyuzxla.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.zhongyouzk.top/Article/details/gt2hapmsurt.html

TS:   [...a, ...b];
来源：http://dali.xziqi.cn/Article/details/gt2dxgwlpft.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dianchejie.cn/Article/details/gt2xppggwpp.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gt2avkzngwf.html

Ruby: a + b;  a.concat(b)
来源：http://dali.ppjwa.cn/Article/details/gt2vejkjnta.html

C#:   a.Concat(b).ToList()
来源：http://dali.jianghu66.top/Article/details/gt2ryvmwdkn.html

[D09] 排序（升序）
来源：http://dali.birdmap.top/Article/details/gt2suhofkzr.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.jianghu66.top/Article/details/gt2gvbknvgo.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nszllbsk.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.redwolf501.top/Article/details/gt2xlojtiqc.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.svipenyu.cn/Article/details/gt2lirdegru.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jyoumei.cn/Article/details/gt2qcrngqrj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yuxming.cn/Article/details/gt2pnjxxyee.html

Ruby: arr.sort
来源：http://dali.ivvv.top/Article/details/gt2vcritvgk.html

C#:   list.Sort();
来源：http://dali.mhx1999.top/Article/details/gt2mdgpiixx.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.zdqjudy.top/Article/details/gt2ejpdemyg.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.hfpthk.cn/Article/details/gt2hhbtqwfy.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gfnbasde.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gt2szndqtzd.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yongpay.top/Article/details/gt2gufxhvzb.html


<!-- 参考信息 -->