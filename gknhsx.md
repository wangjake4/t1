代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tkisfyhr.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gt2ixrhlfyn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2dvrcajlj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ebhhsnds.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gt2norprwjr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.0kj1m.cn/Article/details/gt2lykcciga.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2haiwirui.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gt2tuyzbnat.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ydzc1.top/Article/details/gt2uwudakky.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2isxvrram.html

[B11] 生成数字序列 / 区间
来源：http://dali.fzhhl.top/Article/details/gt2evgvdick.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgfzy.top/Article/details/gt2jlnwrjil.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gt2fdetwpov.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.smart0.xyz/Article/details/gt2jgnaaqkv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2canbwkam.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2kwnfxpjx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gt2xxxwtlty.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gt2vqpteuzf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2qnocraip.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xjphxhof.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gt2ccyigcqr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dlwwznzb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2iphlvloj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gt2tqphtcbg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2nklsvmyp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gt2vgxfxaiz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gt2ekosyzyj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gt2grkpetzm.html

[B13] 判断是否为数字
来源：http://dali.nanxuanxn.top/Article/details/gt2wpnqmomm.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2ryuvlyho.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gt2lveoizdr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwroujhl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzumfqtk.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gt2jigfpmwn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2kobdrljg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gt2gxvupmsr.html

C#:   x is int or double or decimal
来源：http://dali.tianlin.xyz/Article/details/gt2umgdxvjp.html

[B14] 判断值是否在集合内
来源：http://dali.redwolf501.top/Article/details/gt2zizjsylx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gt2wsrqbfdg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gt2uxblgupt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2xqeqjdwp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.andypj.xyz/Article/details/gt2pbscthmv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gt2espkypiw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kplxirnb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ybqdxqiq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2ohoxjluc.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gt2tbyvcqbd.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gt2rrkttedp.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gt2avyvtaea.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2dbtjgrst.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2gkpdhnbi.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2wvqwcbos.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2avpyeqfq.html

Ruby: a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gt2qnlbebdt.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gt2qmeucgyv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gt2knxcwczk.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gt2cobhmehm.html

PHP:  if (!$data) { return; }
来源：http://dali.hammf.cn/Article/details/gt2opamofor.html

JS:   if (!data) return;
来源：http://dali.yueranfly.top/Article/details/gt2pwlnaomq.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2ezqlqkzm.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gt2ctofmzhc.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2gourujqe.html

Ruby: return if data.nil?
来源：http://dali.xinyue.icu/Article/details/gt2galfputk.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2doazugoi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2afgbmqxa.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gt2pmkroxdg.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2ttyxohlp.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2ntekukje.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlbwavls.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2uavilwnl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gxdujdhl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2qenaxjne.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2edtaigni.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gt2qtvgvjwp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gt2tecuvrba.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gt2ksjyjowz.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2rvmbhjbi.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gt2iejdhddo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nwbrower.top/Article/details/gt2mfhywuph.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyjgszsy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gt2gkqvzfld.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gt2gsugiyqv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2mxwoxlpa.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gt2ywghpfmh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gt2btvevezi.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gt2edwxtdzy.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenlongwang.top/Article/details/gt2liutwdgf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gt2ehkyurfy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2ojmpnpgx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdfckbwl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gt2ibtpdsam.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gt2kjdofgtr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yraboqsy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xuetiantiany.cn/Article/details/gt2hydacmst.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gt2tqnoxlcn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gt2uhadylch.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gt2zbqdgobh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2crnhqerq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jiagoushi.top/Article/details/gt2zdobdxti.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gt2fdhjtzwa.html

Go:   // 无：用配置结构体参数
来源：http://dali.zycfv.cn/Article/details/gt2ophvzver.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2sarouljn.html

C#:   f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gt2ympjdmxl.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gt2dmkueviu.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2jeoplqbj.html

PHP:  return [$a, $b];
来源：http://dali.svipenyu.cn/Article/details/gt2sciwezgw.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ydzc1.top/Article/details/gt2uixpxqpt.html

TS:   return { a, b };
来源：http://dali.ydzc1.top/Article/details/gt2fpplhyjx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gt2eqhufesy.html

Go:   return a, b
来源：http://dali.redwolf501.top/Article/details/gt2svtghgvv.html

Ruby: return a, b
来源：http://dali.hnqzz.top/Article/details/gt2mzbjjexj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gt2habwzbfh.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gt2kbaeltwb.html

Py:   square = lambda x: x * x
来源：http://dali.daxiang520.top/Article/details/gt2fexsnfsp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gt2cddcunig.html

JS:   const square = x => x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2fatmyiqk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2zxkgrfuv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cheryme.top/Article/details/gt2cpkspmtn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgufenzy.top/Article/details/gt2lfgufypj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.snrcjt.cn/Article/details/gt2ownxiips.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gt2doqdangh.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gt2gfxnwusu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gt2jbtqaxbz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2fzcjzqzo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gt2keadxiaa.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gt2jasojkwm.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gt2grreblcd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hovdjpfl.html

Ruby: arr.map(&:upcase)
来源：http://dali.cheryme.top/Article/details/gt2wycwygsy.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dianchejie.cn/Article/details/gt2hplfhpjh.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gt2djtdpetv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gt2lgldgduo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.dashuyun.cn/Article/details/gt2zzhnkejf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2nsfbxhcc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gt2ptijkbwp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gt2nvaxjekn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2vdqmlqqz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhongyouzk.top/Article/details/gt2tdcawkrk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2cfzzamhi.html

[C09] 递归
来源：http://dali.jinqigfzy.top/Article/details/gt2jbpsnjhf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gt2qslmjsph.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2bxnubjea.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.redwolf501.top/Article/details/gt2rskabiqu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2cxrstcus.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gt2wxzvtisp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gt2xzkvwopk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bremlseg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gt2cqkxzjwp.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gt2hnfcaukf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yangfankeji.com/Article/details/gt2nnroyyzq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.vqdsnc.cn/Article/details/gt2ejrwetam.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2pxpswkkb.html

TS:   同 JS
来源：http://dali.yueranfly.top/Article/details/gt2jdysliky.html

Java: 方法内为块级作用域
来源：http://dali.dianchejie.cn/Article/details/gt2agmkozvl.html

Go:   花括号块级作用域
来源：http://dali.shzxlz.cn/Article/details/gt2znuuqdsw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gt2ddmqigqi.html

C#:   块级作用域
来源：http://dali.cashguo.top/Article/details/gt2scnegmsp.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gt2lhilgadf.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gt2ywjijzil.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhoulong.xyz/Article/details/gt2tiluaphd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gt2klnmxsah.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.wangdashe.top/Article/details/gt2txcwihua.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gt2nmwddxdv.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhixingplan.top/Article/details/gt2lioggzmq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jlsjyb.cn/Article/details/gt2hyeinnbh.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gt2ioybxnci.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gt2bgheczjg.html

Py:   (lambda: print("run"))()
来源：http://dali.yuanzhike.top/Article/details/gt2budpgwnp.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gt2jlweokcm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.cucudq.cn/Article/details/gt2toldcdxw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gt2reusarwr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gt2eycpyexn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.smart0.xyz/Article/details/gt2yggaekup.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gt2gpdpqaid.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hywenlv.cn/Article/details/gt2fogdfbeu.html

[C13] 类型声明 / 类型注解
来源：http://dali.gogol.net.cn/Article/details/gt2qzfzedws.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2byvpkxrp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2lqpmlrph.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258.top/Article/details/gt2ukutzbyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gt2vzcwzwny.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bciwikdi.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2itzypmgl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gt2wqlzdtms.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sysykeji.top/Article/details/gt2hsdwojov.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2zaencayd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dashuyun.cn/Article/details/gt2tozhurjf.html

PHP:  // 无泛型
来源：http://dali.nwbrower.top/Article/details/gt2jfmhijnd.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2gemlxggo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gt2gcfwyeyy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gt2eiwgwbqo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangdashe.top/Article/details/gt2njrvepgo.html

Ruby: # 无泛型
来源：http://dali.sufxvd.cn/Article/details/gt2kxxppsnb.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gt2zsjwkmqh.html

[C15] 解构 / 展开参数
来源：http://dali.zycfv.cn/Article/details/gt2lmfmdben.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2sbeujwrt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hywenlv.cn/Article/details/gt2hnsjrwfq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2wyjxcnoz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gt2grvryhlw.html

Java: // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2avjajjkq.html

Go:   // 无解构
来源：http://dali.yongpay.top/Article/details/gt2ajgdwvik.html

Ruby: a, b = pair
来源：http://dali.havefunace.top/Article/details/gt2fxpdlhca.html

C#:   var (a, b) = pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2xpkbywxl.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258888.top/Article/details/gt2vmvxrfjx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.iojbl.cn/Article/details/gt2xleraxqv.html

PHP:  // 无重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yngznsad.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.bjfxy.top/Article/details/gt2yaobdhll.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.haohaochexian.top/Article/details/gt2idprdkjg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.wangdashe.top/Article/details/gt2pilsbkig.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gt2yzilljym.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gt2eifmnbth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ehwqpu.com/Article/details/gt2rkclqjxc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2ygopfyaa.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gt2zzypaant.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gt2aiuiuwax.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gt2footzhkv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ybcxt.top/Article/details/gt2dnytjixa.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gt2ptdtdgfw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znkncply.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gt2ojgdlpsu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gt2uuhixqrc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gt2havaczcj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ydzc1.top/Article/details/gt2ihznhvks.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gt2lddeqkcq.html

[D02] 追加元素到末尾
来源：http://dali.zycfv.cn/Article/details/gt2fcnuiawl.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yxhyxisl.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.xylfe.cn/Article/details/gt2uspqwcaz.html

JS:   arr.push(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2yqueiyqn.html

TS:   arr.push(4);
来源：http://dali.nanxinkj.top/Article/details/gt2shsdeuvp.html

Java: list.add(4);
来源：http://dali.snrcjt.cn/Article/details/gt2czhsqmuo.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gt2emqovtsr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hysaishi.cn/Article/details/gt2iaxymscz.html

C#:   list.Add(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2bpdkoxup.html

[D03] 在指定位置插入元素
来源：http://dali.daxiang520.top/Article/details/gt2ukxnyuss.html

Py:   arr.insert(0, 0)
来源：http://dali.xylfe.cn/Article/details/gt2namufvho.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gt2wnuhxhui.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gt2zokuzlef.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.svipenyu.cn/Article/details/gt2fzvsdfjc.html

Java: list.add(0, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gt2uwaiegaq.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gt2bqvrxhbp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gt2eaajnmve.html

C#:   list.Insert(0, 0);
来源：http://dali.quarkkingdee.top/Article/details/gt2idfrkdtq.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2hglsplqy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zymejxpp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xinyue.icu/Article/details/gt2wnboucfj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258888.top/Article/details/gt2pjxbysdt.html

TS:   arr.splice(0, 1);
来源：http://dali.smart0.xyz/Article/details/gt2wltzayxf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ehwqpu.com/Article/details/gt2chlaafec.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pycfn.com/Article/details/gt2rxfwpira.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gt2bwvrczjy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gt2etpwbkse.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gt2jxkyujpu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gt2qbwfacax.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yj20258888.top/Article/details/gt2slkwafaw.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gt2gynkdrqa.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gt2lwnrvgla.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2izcifcqu.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gt2tzbutcih.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gt2jnziqomq.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.aizwys.cn/Article/details/gt2sdkcmlqw.html

[D06] 数组长度
来源：http://dali.aizwys.cn/Article/details/gt2ezrmqkqv.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2qdsxqrhk.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gt2krsiecbd.html

JS:   arr.length
来源：http://dali.gogol.net.cn/Article/details/gt2guuhingr.html

TS:   arr.length
来源：http://dali.tianlin.xyz/Article/details/gt2bttxfxvl.html

Java: list.size();
来源：http://dali.ydzc1.top/Article/details/gt2otlthcoz.html

Go:   len(arr)
来源：http://dali.jyoumei.cn/Article/details/gt2afouwfze.html

Ruby: arr.length; arr.size
来源：http://dali.fzhhl.top/Article/details/gt2efffhlsu.html

C#:   list.Count;
来源：http://dali.316326.xyz/Article/details/gt2edcryzmd.html

[D07] 切片 / 取子数组
来源：http://dali.zhoulong.xyz/Article/details/gt2bfwyfugy.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gt2ltxaecfn.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.svipenyu.cn/Article/details/gt2xnqoxzur.html

JS:   arr.slice(1, 4);
来源：http://dali.cheryme.top/Article/details/gt2awqmgrax.html

TS:   arr.slice(1, 4);
来源：http://dali.tian-w.cn/Article/details/gt2uqsgtbzx.html

Java: list.subList(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gt2odtbhruh.html

Go:   arr[1:4]
来源：http://dali.daxiang520.top/Article/details/gt2laxlsahd.html

Ruby: arr[1, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pumovkmd.html

C#:   list.GetRange(1, 3);
来源：http://dali.meibo888.top/Article/details/gt2yobjflkt.html

[D08] 合并两个数组
来源：http://dali.gogol.net.cn/Article/details/gt2hzznkotl.html

Py:   a + b;  a.extend(b)
来源：http://dali.yvedp.cn/Article/details/gt2buuncxhe.html

PHP:  array_merge($a, $b);
来源：http://dali.zhixingplan.top/Article/details/gt2bqzraigk.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuetiantiany.cn/Article/details/gt2lopsmbcd.html

TS:   [...a, ...b];
来源：http://dali.aizwys.cn/Article/details/gt2wjynfchj.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.dashuyun.cn/Article/details/gt2fwwxpwhz.html

Go:   append(a, b...)
来源：http://dali.nwbrower.top/Article/details/gt2nhcpdfnc.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jyoumei.cn/Article/details/gt2jauklgwd.html

C#:   a.Concat(b).ToList()
来源：http://dali.feifeiyinyue.top/Article/details/gt2edebnnay.html

[D09] 排序（升序）
来源：http://dali.fengsongda.top/Article/details/gt2pvmtowid.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gt2iwatwuwq.html

PHP:  sort($arr);
来源：http://dali.yj20258.top/Article/details/gt2zwxpsqho.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.birdmap.top/Article/details/gt2vzvsohhh.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yonumen.top/Article/details/gt2zratebvh.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.bjfxy.top/Article/details/gt2gegbmfpk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.snrcjt.cn/Article/details/gt2smifcfwt.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gt2rvyfyhog.html

C#:   list.Sort();
来源：http://dali.guannengcc.top/Article/details/gt2oazublhz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.316326.xyz/Article/details/gt2aauhjspu.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.tanke756.top/Article/details/gt2jnittnna.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gt2bxddjbja.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yqzkzrer.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gt2eacpfoik.html


<!-- 参考信息 -->