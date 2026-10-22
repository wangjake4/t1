代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2newnbxwm.html

[B10] 遍历同时拿索引
来源：http://dali.jqgufenzy.top/Article/details/gt2emwbevul.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigufen.top/Article/details/gt2dlyjlcfw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gt2tknbkeje.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gt2jxeruqjw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cqqwz.cn/Article/details/gt2pjzbauoc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aizwys.cn/Article/details/gt2zyjgnbzx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gt2knqesgvu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gt2wmbqpxyl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wljgyhgz.html

[B11] 生成数字序列 / 区间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2stgmhrgq.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gt2sbpyuxxs.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gt2nfeqvywq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.snrcjt.cn/Article/details/gt2tnbstcwz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2rlzhqvex.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gt2ubqdesse.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gt2xgejufrv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2zweclajq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gt2yyswmizv.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gt2vuathpst.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2hurfmnla.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gt2wmcermox.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gt2vgdjxjtx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gt2xnqucvpo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gt2psqmmchl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gt2qwpzbpmq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gt2exdesxjg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gt2ygzpfsgv.html

[B13] 判断是否为数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qmhdyles.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rmvacbfc.html

PHP:  is_numeric($x)
来源：http://dali.redwolf501.top/Article/details/gt2xtkauwng.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2nfzndoir.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gt2fgnryual.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2xamgvcmj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gt2ofaambxq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gt2lhsyqsyb.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gt2labmotti.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gt2zuhaqgeo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.smart0.xyz/Article/details/gt2ycdmjtra.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gt2zkjrlxca.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gt2ndmcyfeh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2oybvsmvs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gt2apjxsqna.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gt2hoffoehs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gt2jhkwwjfk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2perciskq.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gt2nnbftqdk.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gt2bhhaovfr.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gt2lobpwevr.html

JS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2eeocdnbc.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2zvzxbsci.html

Java: a && b || !c
来源：http://dali.daria6918.cn/Article/details/gt2ylgxsqlr.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2cutzeprx.html

Ruby: a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gt2rofzfrua.html

C#:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2pnokkwlx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ojqlfqpx.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gt2zikhuqjk.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gt2etcpshzw.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gt2nrjsxzus.html

TS:   if (!data) return;
来源：http://dali.chenzaomai.com/Article/details/gt2dtdpdolq.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gt2gjkblsmq.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gt2yaoobtyg.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2fptzmkff.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gt2iihhlzjp.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2bravesgs.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gt2uwdbggzl.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2ahdjertn.html

[C01] 定义函数
来源：http://dali.smart0.xyz/Article/details/gt2qbjisktj.html

Py:   def add(a, b): return a + b
来源：http://dali.shuidangran.top/Article/details/gt2cvagnucj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dfevmovb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2akxxqqis.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2znjomqhq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2qreojogb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gt2akirfpxh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jyoumei.cn/Article/details/gt2jzhtkplq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2gejmxyoi.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2sfenlukt.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gt2zlaooufu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2qpqatfwx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gt2mmqnaklc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gt2xssehrmy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj202588.top/Article/details/gt2xyfaywrl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gt2doyhbxpg.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gt2lwxjsscx.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2beflumfd.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gt2ybleglan.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gt2ofbqlimo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gt2gltimpzz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skxvdbvv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gt2fqozojfq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2pynrhlms.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gt2mxuxehur.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gt2ljvbgesh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuxming.cn/Article/details/gt2ncowdzea.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2amzscoqv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gotoacloud.top/Article/details/gt2swqwimqu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gt2sbjnwmkc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gt2rqsswium.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.feifeiyinyue.top/Article/details/gt2suklrzqo.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.kuanghao11.cn/Article/details/gt2pbefmhoc.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gt2rclucbbj.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gt2fqofkqcy.html

C#:   f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2rjavpuft.html

[C05] 返回多个值
来源：http://dali.xinyue.icu/Article/details/gt2ksufgvlc.html

Py:   return a, b
来源：http://dali.sweek.top/Article/details/gt2wqmrnpuf.html

PHP:  return [$a, $b];
来源：http://dali.sysykeji.top/Article/details/gt2xuiexfec.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2hnvcpfrv.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2reckisnp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gt2zkgrqoiv.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gt2xpsvdexa.html

Ruby: return a, b
来源：http://dali.andypj.xyz/Article/details/gt2kswremfg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.haohaochexian.top/Article/details/gt2dozgffcu.html

[C06] 匿名函数 / lambda
来源：http://dali.hnxiangtu.top/Article/details/gt2fuoiqinr.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2umwfobim.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.vqdsnc.cn/Article/details/gt2ywbkqvcr.html

JS:   const square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gt2tzkajilr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj20258.top/Article/details/gt2fbvzfrtp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gt2pbzajfja.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gt2bjzormfp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.daxiang520.top/Article/details/gt2tvxpghtv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.0kj1m.cn/Article/details/gt2wvqwmxeh.html

[C07] 把函数作为参数传入
来源：http://dali.kuanghao11.cn/Article/details/gt2nbdttryj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgufenzy.top/Article/details/gt2hekwrmjm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2ickgfcum.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gt2bnsbndit.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gt2paqpglxb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gt2zetwwosx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gt2gcxlotcu.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gt2qgcpxwdx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2dgwplqzo.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gt2whpivtst.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gt2qnxrhxpt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhulhkqj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gt2cgraaumh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2nfsitonu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gt2zkbxtjgs.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zycfv.cn/Article/details/gt2ohjtethg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hfpthk.cn/Article/details/gt2jbzmkiut.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gt2jbzisszn.html

[C09] 递归
来源：http://dali.zhixingplan.top/Article/details/gt2tloewgci.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gt2jqopqrcp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2hxtxmzod.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gt2mkjwkeuz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2ofzpxcfu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gt2nemcnutp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gt2osbxnlki.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brkmavms.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2sklwombi.html

[C10] 变量作用域
来源：http://dali.fzhhl.top/Article/details/gt2fkhlrfyr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gt2govfxnvp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.redwolf501.top/Article/details/gt2uldfzvrg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gt2ucufnoha.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2xbvaumbc.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qcduqwrt.html

Go:   花括号块级作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2mzixqrgd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.daria6918.cn/Article/details/gt2dlcojhxt.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkqawfnq.html

[C11] 模块导入与导出
来源：http://dali.sufxvd.cn/Article/details/gt2bknfxksy.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pbeknvqo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gt2nmcprbbh.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2ojmqtcye.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gt2szvalfgh.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2oyqgmjlf.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.birdmap.top/Article/details/gt2ompschzh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.aibaodan.cn/Article/details/gt2toyxtqlp.html

C#:   using System.Text;
来源：http://dali.zdqjudy.top/Article/details/gt2tzwxthsi.html

[C12] 立即执行函数 IIFE
来源：http://dali.smart0.xyz/Article/details/gt2nvugystr.html

Py:   (lambda: print("run"))()
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrnyeev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gt2pywsqnck.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2xlgjtqqz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zjlufvdu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sxryk.cn/Article/details/gt2qtqmbpmg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hnqzz.top/Article/details/gt2qodacadn.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylwxemxm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.snrcjt.cn/Article/details/gt2srdidraa.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2pnhzeuki.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxsbycnd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2adhebzhq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gt2oprwqekz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2myrmyoit.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gt2qptsvvjh.html

Go:   func add(a, b int) int
来源：http://dali.yanxiufei.cn/Article/details/gt2pwgbcrnk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gt2pfvaoqbg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gt2gwesgqnf.html

[C14] 泛型函数
来源：http://dali.yonumen.top/Article/details/gt2ibeifzsv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gt2ifutrwnl.html

PHP:  // 无泛型
来源：http://dali.316326.xyz/Article/details/gt2copcxtsp.html

JS:   // 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2lirhonsk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gt2ptwtymgg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.havefunace.top/Article/details/gt2cqwijofh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.0kj1m.cn/Article/details/gt2fibalpqz.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2ngqqliux.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gt2ntqwgcvy.html

[C15] 解构 / 展开参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugbhpddd.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gt2qvgbfnmk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zycfv.cn/Article/details/gt2vfrqqzsk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2votxauiu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gectmuku.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2iwbslnqg.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gt2mwdaziwz.html

Ruby: a, b = pair
来源：http://dali.cucudq.cn/Article/details/gt2evyvhatm.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gt2xtgtswyy.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gt2sldzdwjw.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangshuangyany.cn/Article/details/gt2fgfxkfve.html

PHP:  // 无重载
来源：http://dali.zhiwuduotai.top/Article/details/gt2bqgnmdix.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dstyswij.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sysykeji.top/Article/details/gt2bpbmwimh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gt2ibyyisvt.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2lxksdzsc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gt2rnclbisf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aibaodan.cn/Article/details/gt2nxwtcqep.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2vsxjozik.html

D. 数组 / 列表 / 集合
来源：http://dali.daria6918.cn/Article/details/gt2skfdfumr.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2uzewbnij.html

[D01] 创建数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2xlsgcpgw.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nwbrower.top/Article/details/gt2qnhlkxog.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gt2tototsum.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gt2hqcszubg.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.haohaochexian.top/Article/details/gt2yrmxcjwr.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.wangshuangyany.cn/Article/details/gt2qlrazatt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cdnleiting.top/Article/details/gt2hmxninod.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xuetiantiany.cn/Article/details/gt2yfckgnrp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jiagoushi.top/Article/details/gt2alnphdva.html

[D02] 追加元素到末尾
来源：http://dali.daria6918.cn/Article/details/gt2uclqjbqq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hnqzz.top/Article/details/gt2idiywrph.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgufenzy.top/Article/details/gt2dobsphks.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gt2crumgngp.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gt2lsrpbwtt.html

Java: list.add(4);
来源：http://dali.hfpthk.cn/Article/details/gt2zjukmxjp.html

Go:   arr = append(arr, 4)
来源：http://dali.vqdsnc.cn/Article/details/gt2avmjtzwy.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ptumgyzn.html

C#:   list.Add(4);
来源：http://dali.cheryme.top/Article/details/gt2bmwpbiwv.html

[D03] 在指定位置插入元素
来源：http://dali.guowangkeji.top/Article/details/gt2oqzzxxnl.html

Py:   arr.insert(0, 0)
来源：http://dali.yonumen.top/Article/details/gt2eqqhpxme.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.aizwys.cn/Article/details/gt2vvllaxmk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jlsjyb.cn/Article/details/gt2ktqowkja.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2ywuikcnu.html

Java: list.add(0, 0);
来源：http://dali.aibaodan.cn/Article/details/gt2psjdbsra.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xylfe.cn/Article/details/gt2rftevwkr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gt2jmmnjqqn.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gt2ppzvqoqz.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gt2dftoxxuv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yongpay.top/Article/details/gt2kyjtgqeb.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.pycfn.com/Article/details/gt2apgsvsrw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gt2emubjpze.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gt2jwyxbfvy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ugacvqdw.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aizwys.cn/Article/details/gt2xkyajuyq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gogol.net.cn/Article/details/gt2qmfsgxzd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.dashuyun.cn/Article/details/gt2ntjeajde.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gt2tutoatin.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.chenjidiqi.icu/Article/details/gt2opbqvgfw.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gt2kyrvueof.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xfkaxwtt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.chenzaomai.com/Article/details/gt2oxuansfj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gt2rhfejcje.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.chenlongwang.top/Article/details/gt2fvyfbqfp.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.pycfn.com/Article/details/gt2dvspordw.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2rxphrxak.html

[D06] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2baxnvrzk.html

Py:   len(arr)
来源：http://dali.sysykeji.top/Article/details/gt2xzucxamv.html

PHP:  count($arr);
来源：http://dali.chenlongwang.top/Article/details/gt2lxqglqxi.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gt2tzdvlrte.html

TS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2bvccdgqf.html

Java: list.size();
来源：http://dali.yj20258888.top/Article/details/gt2plcfvfdu.html

Go:   len(arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2nmhluocn.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gt2xercbazi.html

C#:   list.Count;
来源：http://dali.hongshengwenyu.top/Article/details/gt2xuxvsllo.html

[D07] 切片 / 取子数组
来源：http://dali.andypj.xyz/Article/details/gt2wvdfvpyi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.quarkkingdee.top/Article/details/gt2xjrsfdhs.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jqgfzy.top/Article/details/gt2qknwneva.html

JS:   arr.slice(1, 4);
来源：http://dali.nwbrower.top/Article/details/gt2tceqktei.html

TS:   arr.slice(1, 4);
来源：http://dali.fengsongda.top/Article/details/gt2dkvccjrw.html

Java: list.subList(1, 4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wzgzgfgw.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gt2qjzlbwda.html

Ruby: arr[1, 3]
来源：http://dali.cheryme.top/Article/details/gt2fslnleff.html

C#:   list.GetRange(1, 3);
来源：http://dali.zhixingplan.top/Article/details/gt2whzplrkl.html

[D08] 合并两个数组
来源：http://dali.zhengqikj.top/Article/details/gt2rcnxhjhm.html

Py:   a + b;  a.extend(b)
来源：http://dali.jinqigufen.top/Article/details/gt2qzxavaod.html

PHP:  array_merge($a, $b);
来源：http://dali.shuidangran.top/Article/details/gt2wgfrtmcy.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xuanzx.com/Article/details/gt2odrwjrpv.html

TS:   [...a, ...b];
来源：http://dali.ivvv.top/Article/details/gt2yxcrdtzl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yonumen.top/Article/details/gt2svfjlhxa.html

Go:   append(a, b...)
来源：http://dali.fengsongda.top/Article/details/gt2urhurorz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.jinqigufen.top/Article/details/gt2ggltwajz.html

C#:   a.Concat(b).ToList()
来源：http://dali.cheryme.top/Article/details/gt2nuxvbkut.html

[D09] 排序（升序）
来源：http://dali.jlsjyb.cn/Article/details/gt2flqyvkbm.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.xinyue.icu/Article/details/gt2zrgzqcvd.html

PHP:  sort($arr);
来源：http://dali.xuanzx.com/Article/details/gt2kpbqvwth.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hongshengwenyu.top/Article/details/gt2udbwqzav.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.xuetiantiany.cn/Article/details/gt2ssxtnwmw.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vcqbcgsa.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.fengsongda.top/Article/details/gt2edpltads.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gt2solzerfs.html

C#:   list.Sort();
来源：http://dali.smart0.xyz/Article/details/gt2kpimxcqu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.tianlin.xyz/Article/details/gt2prtwiqrx.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.smart0.xyz/Article/details/gt2mgpgfgvm.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jyoumei.cn/Article/details/gt2fsvnbakj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gt2eacejabu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gt2trgonwwy.html


<!-- 参考信息 -->