代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtbqiksgfj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhoulong.xyz/Article/details/gtodwctboz.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenlongwang.top/Article/details/gtxrdwjhnv.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gtkfdcgpqz.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtaeqvkiwm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtrdkytupd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtadzpcqtm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtlcpoku.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtgkzbthsc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaohgyqoz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenlongwang.top/Article/details/gtidnoosdk.html

[B12] 跳出多层循环
来源：http://dali.cashguo.top/Article/details/gtdbpxplfr.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtrkmjyknn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yvedp.cn/Article/details/gtssueskkz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tian-w.cn/Article/details/gteoqepwgj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtuobyyaxr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtlbcwilwl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258.top/Article/details/gtflpenemb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtzayvzlax.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gaohongyu789.top/Article/details/gtfkfjguwp.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtnhaebeew.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqtdbxvz.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtcawweryc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gttloyipmg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtmfhlilqg.html

Java: x instanceof Number
来源：http://dali.ybcxt.top/Article/details/gtwtftqaup.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yvedp.cn/Article/details/gthdzrnujv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gtiqztnrye.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtjbfkwsbq.html

[B14] 判断值是否在集合内
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpakxkhz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtxmlmefix.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtqisjjdub.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gthaaakxqj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gtvsahxfep.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtshlkyqbl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtaobmxgra.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtzcnunzfz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtwigyjfcd.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gttpsusrnl.html

Py:   a and b or not c
来源：http://dali.svipenyu.cn/Article/details/gtyveybvqt.html

PHP:  $a && $b || !$c
来源：http://dali.gaohongyu789.top/Article/details/gtfhilxxss.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtnxxpigic.html

TS:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtrhmpgdmm.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtqetplfoy.html

Go:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtegzwflhj.html

Ruby: a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtseolhqvw.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtwnhupoup.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtsgvliphf.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gtqbpvdxzq.html

PHP:  if (!$data) { return; }
来源：http://dali.sweek.top/Article/details/gtmnwtmkrr.html

JS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtqfoaabms.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtoerqvgib.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtckpbgdev.html

Go:   if data == nil { return }
来源：http://dali.cucudq.cn/Article/details/gtttximlyr.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gtqlqftswp.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtlsrvqrwd.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtktvuiwta.html

C. 函数与作用域
来源：http://dali.yuanzhike.top/Article/details/gtzxkanywl.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdmjuaozc.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtxapbccjk.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtdeuyqviu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtwkiwgzxy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtcmsfoity.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtbxafjmnr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtqmxynbtq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtfqvucxev.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gtqktrrion.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiycsubpx.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gthyurtvvn.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtrnglucpw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gtyflkukvr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtvrbthuxc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtqxteqklk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgfzy.top/Article/details/gtygwxmgzi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.meibo888.top/Article/details/gtdgjiijcg.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtbqanzknc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xziqi.cn/Article/details/gtqxfcbkji.html

[C03] 可变参数
来源：http://dali.wangdashe.top/Article/details/gtygsurblc.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtmincqwus.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlrvkealf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gtqxfscvzp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtowlfmgnx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtmmnbukca.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtnsvuhvhu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hysaishi.cn/Article/details/gtpxirhnst.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtfrzhcmbz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gtubhqntqf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dashuyun.cn/Article/details/gttfumuipi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhengqikj.top/Article/details/gtvdoftxsc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtlcuofflq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhongyouzk.top/Article/details/gtywakyoxj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtcyktndyd.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtopwduivx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gtgktrxlrd.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtloumhgeh.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkshastn.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtfgxuhoof.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gtlktfupqg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xziqi.cn/Article/details/gtmbpimddy.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtnrjaciae.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gzhubu.top/Article/details/gttwpwcags.html

Go:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtpxjzpyos.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gtlirmzugx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gtnhwpkbke.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtculclevp.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtomlcktrk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.redwolf501.top/Article/details/gtzbiupzuf.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtsrknswym.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ydzc1.top/Article/details/gtctxwkdzf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gtkqatbvqf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.c1oappe.top/Article/details/gtukyqzptb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtczbiyexi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtccsjscis.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gtiibcpxxl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cdnleiting.top/Article/details/gtlpeewtao.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ybcxt.top/Article/details/gtbjcleykv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinqigfzy.top/Article/details/gtaluyxorq.html

TS:   arr.map(String)
来源：http://dali.sufxvd.cn/Article/details/gtfpfekcjz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gttiiiabez.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtkgfmdxsm.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtmvrsovdf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.haohaochexian.top/Article/details/gtnruktclq.html

[C08] 闭包
来源：http://dali.cqqwz.cn/Article/details/gtqshldgxx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.sufxvd.cn/Article/details/gtlwzklhkx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gtnvwjvoru.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtmgxzgaul.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtnvcopfai.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cheryme.top/Article/details/gtjtstrloy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.meibo888.top/Article/details/gtukqbrbfz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gttutnvykq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gttdsvyljy.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtylmljfuq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtoayvqpcf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtgikzxher.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtojuuwjcr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gttaicajrb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gtdglickbb.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtoqtucxso.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzzahnhs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtnviizdcq.html

[C10] 变量作用域
来源：http://dali.hysaishi.cn/Article/details/gtludggffo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.sweek.top/Article/details/gtuskdeqbk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gtzzyvthzp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gtmjaaovtn.html

TS:   同 JS
来源：http://dali.hfpthk.cn/Article/details/gtrtvkzrhn.html

Java: 方法内为块级作用域
来源：http://dali.wangdashe.top/Article/details/gtusbkwsxq.html

Go:   花括号块级作用域
来源：http://dali.fzhhl.top/Article/details/gthwddzsjp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtpwwvebio.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtgfanclyx.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gttctbotur.html

Py:   from module import func
来源：http://dali.nanxinkj.top/Article/details/gtcqkjjoxz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtzvszkdal.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtrnmamezz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtibfnoazb.html

Java: import java.util.List;
来源：http://dali.sweek.top/Article/details/gtzqtwwqda.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.redwolf501.top/Article/details/gtowuoszxz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gtqjcdmrix.html

C#:   using System.Text;
来源：http://dali.gaohongyu789.top/Article/details/gtxktgccct.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gtpkdmtgce.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtnpwavfpu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtuqxwyksj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtzopwebik.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtzzbtlvip.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.fengsongda.top/Article/details/gtwmshatxd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gtkuhjmlxq.html

Ruby: -> { puts "run" }.call
来源：http://dali.cucudq.cn/Article/details/gtqvtxrnpk.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtkmemufjr.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxuanxn.top/Article/details/gtkwyvwukp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sxryk.cn/Article/details/gtwnbymmfz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtvdloowpl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgfzy.top/Article/details/gthfkfqsie.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtqngbticu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtqizhkoib.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gtjdxndipj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtqlvsvjko.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gtctdrquhk.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtwcgryrbr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtsnkhakak.html

PHP:  // 无泛型
来源：http://dali.ivvv.top/Article/details/gtytgaesex.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtaahniouw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gtweavuhqz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtglvjqqta.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258.top/Article/details/gtzjpzayxt.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtoygcxtkc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.pycfn.com/Article/details/gtsqfocdxp.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gtjyigcqqt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuanzhike.top/Article/details/gtzmiksydt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtvhwtpyml.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqwkcmga.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gtrfhkwran.html

Java: // 无解构
来源：http://dali.tanke756.top/Article/details/gtyepmland.html

Go:   // 无解构
来源：http://dali.jinqigufen.top/Article/details/gtyrksnzjy.html

Ruby: a, b = pair
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokdabzre.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtywwrgeka.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtrkdlymlz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtmekwajlt.html

PHP:  // 无重载
来源：http://dali.zhengqikj.top/Article/details/gtwfyqorer.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtwwbrmgty.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.redwolf501.top/Article/details/gtsdhwlihe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtdpqlotcj.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj20258888.top/Article/details/gtoiouxexa.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtuoukwgxe.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtkdpgdadi.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtmikxpbtd.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtvccuhxjn.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtjsxkmdqk.html

[D01] 创建数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtiiqtdlug.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ppjwa.cn/Article/details/gtgyhsdfte.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzwtqhaql.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnvmjfcs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtmrmsprzq.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.nanxinkj.top/Article/details/gtbdodikdj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.svipenyu.cn/Article/details/gtgdddgqeh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtixsjytke.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.fengsongda.top/Article/details/gtayjfimmu.html

[D02] 追加元素到末尾
来源：http://dali.smart0.xyz/Article/details/gtqmolkiwx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gogol.net.cn/Article/details/gtrjotdocs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwjaezws.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtkhujmlqp.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gthozknvrp.html

Java: list.add(4);
来源：http://dali.aibaodan.cn/Article/details/gttupucxjw.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtdogkvmxj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yongpay.top/Article/details/gtcevfjkdz.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gtqsouzfly.html

[D03] 在指定位置插入元素
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxgyjcie.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwqlwmkt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cheryme.top/Article/details/gturaoldhc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtzjxqrdjy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yj202588.top/Article/details/gtwrjoflke.html

Java: list.add(0, 0);
来源：http://dali.jiagoushi.top/Article/details/gtdnegfosv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtikgzaikq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtuneepjic.html

C#:   list.Insert(0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtogywqeps.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtdgrueubk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtqnniufdw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtsjemhwsk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtuezswt.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtizkbposj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyreilxkl.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtocpamhrh.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gthcbgdhsk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.316326.xyz/Article/details/gtgwmqmhsz.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvjmncle.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqogqiws.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gttpljgcky.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtusorewft.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.meibo888.top/Article/details/gtmwnmgqts.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtapyjkikd.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtmpyiphmm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtusrqubva.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtakveefoq.html

[D06] 数组长度
来源：http://dali.birdmap.top/Article/details/gtxbxvbuwl.html

Py:   len(arr)
来源：http://dali.yj20258.top/Article/details/gtwwumfeqz.html

PHP:  count($arr);
来源：http://dali.tianlin.xyz/Article/details/gtkfojgkzu.html

JS:   arr.length
来源：http://dali.zhengqikj.top/Article/details/gtobplhozr.html

TS:   arr.length
来源：http://dali.fzhhl.top/Article/details/gtbwgbqowd.html

Java: list.size();
来源：http://dali.c1oappe.top/Article/details/gtvmfveawf.html

Go:   len(arr)
来源：http://dali.xuetiantiany.cn/Article/details/gtrtbkutjv.html

Ruby: arr.length; arr.size
来源：http://dali.dianchejie.cn/Article/details/gthdjjnkkm.html

C#:   list.Count;
来源：http://dali.ppjwa.cn/Article/details/gtxlwbdxga.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtkxjjogqw.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gtgmeqmaaw.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtakngxvai.html

JS:   arr.slice(1, 4);
来源：http://dali.zhiwuduotai.top/Article/details/gtdewgyqdy.html

TS:   arr.slice(1, 4);
来源：http://dali.cashguo.top/Article/details/gtyekfxncu.html

Java: list.subList(1, 4);
来源：http://dali.yonumen.top/Article/details/gtdmjgladv.html

Go:   arr[1:4]
来源：http://dali.jlsjyb.cn/Article/details/gtrpscasip.html

Ruby: arr[1, 3]
来源：http://dali.ywan-chungtsiang.top/Article/details/gtesqlnkcb.html

C#:   list.GetRange(1, 3);
来源：http://dali.hfpthk.cn/Article/details/gtpeffohix.html

[D08] 合并两个数组
来源：http://dali.hammf.cn/Article/details/gtrcmjprlh.html

Py:   a + b;  a.extend(b)
来源：http://dali.hysaishi.cn/Article/details/gtxlgwmknp.html

PHP:  array_merge($a, $b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtblpxaser.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xziqi.cn/Article/details/gtbmtiewxn.html

TS:   [...a, ...b];
来源：http://dali.mhx1999.top/Article/details/gttfesmczl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.guannengcc.top/Article/details/gtonjzcbmr.html

Go:   append(a, b...)
来源：http://dali.wangshuangyany.cn/Article/details/gtwuxhzpga.html

Ruby: a + b;  a.concat(b)
来源：http://dali.xylfe.cn/Article/details/gtogjvqvmf.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxinkj.top/Article/details/gtofauqqvm.html

[D09] 排序（升序）
来源：http://dali.zhoulong.xyz/Article/details/gtejejdvpm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.sysykeji.top/Article/details/gtooknetpz.html

PHP:  sort($arr);
来源：http://dali.meibo888.top/Article/details/gtkmexgzhf.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.meibo888.top/Article/details/gtuhphsfas.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtvwszdmpf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.wangshuangyany.cn/Article/details/gtbtvaysxv.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.yangfankeji.com/Article/details/gtyuujeqxh.html

Ruby: arr.sort
来源：http://dali.pengpengdd.cyou/Article/details/gtbkzdsrou.html

C#:   list.Sort();
来源：http://dali.chenjidiqi.icu/Article/details/gtporxgxpv.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.vqdsnc.cn/Article/details/gtueiqcjtl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.c1oappe.top/Article/details/gttxhuwcke.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtusywsmhv.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.sufxvd.cn/Article/details/gtrvaxwidf.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zycfv.cn/Article/details/gtaptfmyjb.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ivvv.top/Article/details/gthocihucr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangdashe.top/Article/details/gtfarzpeet.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.jinqigfzy.top/Article/details/gtfmttbyae.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.dianchejie.cn/Article/details/gtzctkrirj.html

[D11] 反转数组
来源：http://dali.zdqjudy.top/Article/details/gtlzwcspic.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jyoumei.cn/Article/details/gtamckkcnu.html

PHP:  array_reverse($arr);
来源：http://dali.chenlongwang.top/Article/details/gtqxgjxomj.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.zhoulong.xyz/Article/details/gtscoepxhs.html


<!-- 参考信息 -->