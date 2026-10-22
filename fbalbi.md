代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gttmnutgcs.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtzjukukkf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gtmfezbrhj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmtxmctes.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtqcaxvzlu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtzidbppff.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gtlvdmwtfk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gtimggqmul.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtfhbsrdaz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gttzjfjkyu.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtxutmzxep.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtbkblflbv.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtvgikhwcb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtanejivlj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqmrwvfzv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtmscefybv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtnimeohye.html

Ruby: (0...10).step(2).to_a
来源：http://dali.haohaochexian.top/Article/details/gtkbsbaorc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrcavqjl.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gthhywzjjs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtjluzwenf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xinyue.icu/Article/details/gtarpkmmkz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtydlfziic.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtcvszybla.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtciltbzmn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zdqjudy.top/Article/details/gtgwcqystm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gotoacloud.top/Article/details/gtbuglplve.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtwzjbeuan.html

[B13] 判断是否为数字
来源：http://dali.zhijiandao.cn/Article/details/gtdztvgpch.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtrezxcdbr.html

PHP:  is_numeric($x)
来源：http://dali.meibo888.top/Article/details/gtmcywtgdq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtwcqnejnf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtpidtpgid.html

Java: x instanceof Number
来源：http://dali.shzxlz.cn/Article/details/gtranszhuf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.nwbrower.top/Article/details/gtvmshgcop.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jlsjyb.cn/Article/details/gtnsjglrsf.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gtzjbyujwc.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtknjxyvgy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gtbkivmtsi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gtfvdaewqo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtwdvpcfyd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gterpsbjhz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gtlhuayohe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdsvgiaxj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjiuiasv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtlvplsrcx.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtnsxfedrl.html

Py:   a and b or not c
来源：http://dali.jyoumei.cn/Article/details/gthmcflwde.html

PHP:  $a && $b || !$c
来源：http://dali.hfpthk.cn/Article/details/gtluovbmvy.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgakatgp.html

TS:   a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtikeewmiq.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtuhtoxdts.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtlmoxkgkq.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtamxjmgzs.html

C#:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcnuoord.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtfinmjpvg.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtujgesxzb.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gtfgtzwkfo.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtwyhlqgxn.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtnafjcrxs.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtxagglbhl.html

Go:   if data == nil { return }
来源：http://dali.yvedp.cn/Article/details/gtftvctoxt.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtpitscypy.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtekdgvgvk.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfwxdeofm.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypapihuy.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjgvfrztk.html

[C01] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtvomuqsuy.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gtorholzff.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtsjglsqzb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtlcgexvgz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtrsfsvfdb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtqpzzttdu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nwbrower.top/Article/details/gtkqgpjswc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gtlhwoxlld.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtlrxwkkdd.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtpmpcseyp.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gtubrixgov.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtpknbaacf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gtlcecufeh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtnzvowbpj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinqigfzy.top/Article/details/gtybckipeo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtgaktrrei.html

Ruby: def greet(name = "World") = name
来源：http://dali.havefunace.top/Article/details/gtctwaudge.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daxiang520.top/Article/details/gtvkmgguyj.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtxyjmjzvq.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtayeikydc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gturyumgnd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtvjohwyhr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtwliyyabo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ehwqpu.com/Article/details/gtynutuitq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jyoumei.cn/Article/details/gtqenlqovi.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtpidtvaqy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtffkxzobe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gtftdrfhrn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258888.top/Article/details/gtqmnugxgg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hfpthk.cn/Article/details/gtclkhvopk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvlnlzue.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtjqmnvfht.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.pycfn.com/Article/details/gtgcszdxcm.html

Go:   // 无：用配置结构体参数
来源：http://dali.smart0.xyz/Article/details/gtwktnjcsp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gthkygkfmv.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmrvwoxc.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtoyuhlhbu.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtljuqpukq.html

PHP:  return [$a, $b];
来源：http://dali.iojbl.cn/Article/details/gtgcvdadyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtgadscuhc.html

TS:   return { a, b };
来源：http://dali.tanke756.top/Article/details/gtwbbaqjfj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtigxjbarv.html

Go:   return a, b
来源：http://dali.yueranfly.top/Article/details/gtynskhcbc.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtogjemanj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtpvxhwfpx.html

[C06] 匿名函数 / lambda
来源：http://dali.nanxuanxn.top/Article/details/gtbnjiprck.html

Py:   square = lambda x: x * x
来源：http://dali.xziqi.cn/Article/details/gtjkafexjp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtgpjhwfgx.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtevfkdclx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gttgfkcxlw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtxmrzvbno.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtodptxprl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtjqerhdhm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtubvouxyq.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gtrbcaukpv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtaejxxtst.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cqqwz.cn/Article/details/gtqjuvuttq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gtddizllfu.html

TS:   arr.map(String)
来源：http://dali.gaohongyu789.top/Article/details/gtxxqbpelg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tanke756.top/Article/details/gtitfkpfow.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shzxlz.cn/Article/details/gtnkxavyvw.html

Ruby: arr.map(&:upcase)
来源：http://dali.feifeiyinyue.top/Article/details/gtgkzvvlki.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtukhpijwn.html

[C08] 闭包
来源：http://dali.jinqigfzy.top/Article/details/gtkxrznutc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhengqikj.top/Article/details/gtvprgyipi.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gtqijgbznn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtsjjpgfrn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtuosoarrl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.feifeiyinyue.top/Article/details/gtvceaunwe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtcpyhkpvz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.birdmap.top/Article/details/gtvvuyaoov.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtkcuokhwo.html

[C09] 递归
来源：http://dali.daria6918.cn/Article/details/gtbhqustqb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtysrwvhwc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtteubomcz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtbkpmkvdz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtdxiifjlw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtzgdirxgq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gtotmpehwa.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtwuzbmaji.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sweek.top/Article/details/gtytpxepjr.html

[C10] 变量作用域
来源：http://dali.ehwqpu.com/Article/details/gtouatyojm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtucxpfetc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gttfnjmipp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtjpispguo.html

TS:   同 JS
来源：http://dali.daria6918.cn/Article/details/gtpfbsppdo.html

Java: 方法内为块级作用域
来源：http://dali.nwbrower.top/Article/details/gtpfhwcvow.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtsecpxgoo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhongyouzk.top/Article/details/gtoiavsvmc.html

C#:   块级作用域
来源：http://dali.gzhubu.top/Article/details/gtrjzkfdpb.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpozyqhgq.html

Py:   from module import func
来源：http://dali.smart0.xyz/Article/details/gtbhhbhdqb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqtdpfmcm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnxiangtu.top/Article/details/gtvdanykka.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shuidangran.top/Article/details/gtbkumncoi.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gtsqsijxjb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tianlin.xyz/Article/details/gtzjomqzkf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gttnnsjyjw.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtrsoioger.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtjtdagfrb.html

Py:   (lambda: print("run"))()
来源：http://dali.nanxinkj.top/Article/details/gttahbgjpn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtopxgqzod.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aizwys.cn/Article/details/gtqoelfyvw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gthxwnwiil.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhiwuduotai.top/Article/details/gtbfzxeicl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ydzc1.top/Article/details/gteiphokgl.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbzmrlxp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtegifhfei.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtexuybdjc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.redwolf501.top/Article/details/gtwuckkqxl.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtgbhaqfox.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.mhx1999.top/Article/details/gtkocihpno.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtwzthxtnk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtuuqwnvbp.html

Go:   func add(a, b int) int
来源：http://dali.andypj.xyz/Article/details/gtspomkimk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtehckisbt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hysaishi.cn/Article/details/gtplyynhjh.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtntzrbrei.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtyctwmbpc.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjsaiznin.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtnxeduwaf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daxiang520.top/Article/details/gtmpqahrfl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yvedp.cn/Article/details/gtnyaveoed.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yonumen.top/Article/details/gtoibehxmp.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtzfkgvexp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jyoumei.cn/Article/details/gthnarnuqa.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtpgennlfm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtxwaspbni.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yanxiufei.cn/Article/details/gtnejelerd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtfojmojhx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ppjwa.cn/Article/details/gtdarhukjs.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtiforndxr.html

Go:   // 无解构
来源：http://dali.nanxinkj.top/Article/details/gtqndbacra.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gtyquypljg.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtgrjbwtqt.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gtaugxuykz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.meibo888.top/Article/details/gturqillap.html

PHP:  // 无重载
来源：http://dali.zhixingplan.top/Article/details/gtvcodxzvd.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shzxlz.cn/Article/details/gtifymmgnf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxinkj.top/Article/details/gtksygeuab.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hysaishi.cn/Article/details/gtiblxvhne.html

Go:   // 无重载：用不同函数名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyesvazf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.fzhhl.top/Article/details/gtjipyoazd.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtbenzeyrc.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtkyjcqdsc.html

D. 数组 / 列表 / 集合
来源：http://dali.dianchejie.cn/Article/details/gtbfwyuhyo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtddvnjrer.html

[D01] 创建数组 / 列表
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcvgukkq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.iojbl.cn/Article/details/gtvpmnoisn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.kuanghao11.cn/Article/details/gtqvqsymwt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xziqi.cn/Article/details/gtwwhvrmvy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoosjjaqu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.316326.xyz/Article/details/gtbeoudzdd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.andypj.xyz/Article/details/gtxavcgidt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtmcrifajq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shzxlz.cn/Article/details/gtztajnbia.html

[D02] 追加元素到末尾
来源：http://dali.redwolf501.top/Article/details/gtbojbkrrz.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sufxvd.cn/Article/details/gtryspjlic.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.quarkkingdee.top/Article/details/gtoqbctlih.html

JS:   arr.push(4);
来源：http://dali.zycfv.cn/Article/details/gtdxycxzij.html

TS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtwlvtmrcd.html

Java: list.add(4);
来源：http://dali.sweek.top/Article/details/gtazlhhefp.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gtzfiaygtb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtwfjluvif.html

C#:   list.Add(4);
来源：http://dali.c1oappe.top/Article/details/gtgesyzdos.html

[D03] 在指定位置插入元素
来源：http://dali.dianchejie.cn/Article/details/gtcvbuzimk.html

Py:   arr.insert(0, 0)
来源：http://dali.jiagoushi.top/Article/details/gtpnnbcpwz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.cdnleiting.top/Article/details/gtkiuoxwmj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yongpay.top/Article/details/gtlmiuoydp.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fengsongda.top/Article/details/gtwbmhqhzk.html

Java: list.add(0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtptrzrmwn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gtstrnoogq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtiyjrzngb.html

C#:   list.Insert(0, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtwaoglbpv.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtrdyirfoq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.chenlongwang.top/Article/details/gtcatwmuhm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.c1oappe.top/Article/details/gtvcinhuge.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nanxuanxn.top/Article/details/gtwphdtkrq.html

TS:   arr.splice(0, 1);
来源：http://dali.vqdsnc.cn/Article/details/gtazopduyh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yueranfly.top/Article/details/gtzldoszqf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.havefunace.top/Article/details/gtqqhrjxuy.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cqqwz.cn/Article/details/gtkxacddqy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.chenjidiqi.icu/Article/details/gtuoehmsid.html

[D05] 访问与修改元素
来源：http://dali.havefunace.top/Article/details/gtmzqdmbdb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtzamzsocp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gtkzpiypvd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtlftsjxzx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhijiandao.cn/Article/details/gtmdcbxuhk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hywenlv.cn/Article/details/gtwqfoucmq.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gttpniwzkw.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtnpynflvi.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtqvhoyuij.html

[D06] 数组长度
来源：http://dali.dashuyun.cn/Article/details/gtedatttfm.html

Py:   len(arr)
来源：http://dali.hongshengwenyu.top/Article/details/gtvwtrsrzx.html

PHP:  count($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtfodpjfyl.html

JS:   arr.length
来源：http://dali.hfpthk.cn/Article/details/gtpasdpnat.html

TS:   arr.length
来源：http://dali.zhixingplan.top/Article/details/gtfeqaasjf.html

Java: list.size();
来源：http://dali.yuxming.cn/Article/details/gtcbjczhyj.html

Go:   len(arr)
来源：http://dali.redwolf501.top/Article/details/gtucyhzvxf.html

Ruby: arr.length; arr.size
来源：http://dali.shangyingyoupin.top/Article/details/gtefobxyky.html

C#:   list.Count;
来源：http://dali.zhixingplan.top/Article/details/gtjxgxizqz.html

[D07] 切片 / 取子数组
来源：http://dali.yj20258.top/Article/details/gtbsigsihi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.bjfxy.top/Article/details/gtdvteuago.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.wangdashe.top/Article/details/gtrgzuyjbs.html

JS:   arr.slice(1, 4);
来源：http://dali.meibo888.top/Article/details/gtwpmmcwst.html

TS:   arr.slice(1, 4);
来源：http://dali.hywenlv.cn/Article/details/gtdfrawocn.html

Java: list.subList(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtyjejlpzq.html

Go:   arr[1:4]
来源：http://dali.yangfankeji.com/Article/details/gtldtevnrx.html

Ruby: arr[1, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtbtwqcwte.html

C#:   list.GetRange(1, 3);
来源：http://dali.ppjwa.cn/Article/details/gtclmmjegn.html

[D08] 合并两个数组
来源：http://dali.jianghu66.top/Article/details/gtlljpoogb.html

Py:   a + b;  a.extend(b)
来源：http://dali.sxryk.cn/Article/details/gttumlxmsx.html

PHP:  array_merge($a, $b);
来源：http://dali.nanxinkj.top/Article/details/gtujafgbum.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihggybwx.html

TS:   [...a, ...b];
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyeajdjo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsbajgbli.html

Go:   append(a, b...)
来源：http://dali.chenzaomai.com/Article/details/gtblrxjigh.html

Ruby: a + b;  a.concat(b)
来源：http://dali.zhijiandao.cn/Article/details/gtistymkyd.html

C#:   a.Concat(b).ToList()
来源：http://dali.aibaodan.cn/Article/details/gtnxdsaxbf.html

[D09] 排序（升序）
来源：http://dali.jqgufenzy.top/Article/details/gtixbxuegs.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.fzhhl.top/Article/details/gtghhgflof.html

PHP:  sort($arr);
来源：http://dali.jinqigfzy.top/Article/details/gtrhgjakfh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hfpthk.cn/Article/details/gtprsorweb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.smart0.xyz/Article/details/gtczjoitar.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hywenlv.cn/Article/details/gtglghikug.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.nanxuanxn.top/Article/details/gtraragjjz.html

Ruby: arr.sort
来源：http://dali.nwbrower.top/Article/details/gtaovwmtdm.html

C#:   list.Sort();
来源：http://dali.ehwqpu.com/Article/details/gtgqdlfpkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.svipenyu.cn/Article/details/gthfqyyypt.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigfzy.top/Article/details/gtefnyvgro.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtksquimjg.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.dashuyun.cn/Article/details/gtnxdqgvrj.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.yanxiufei.cn/Article/details/gtflpqxomk.html


<!-- 参考信息 -->