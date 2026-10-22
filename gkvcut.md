代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpurdhdto.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtfxeoflrq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gttcjcmzfg.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gtkmmrxyom.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtpcdarqoe.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gttzlnproo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gtczolwgaa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gthzbojtmv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.redwolf501.top/Article/details/gtwipmebdr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtgfmcmsle.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtyobybkjc.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtrrwjzajl.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gttrcbbien.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gtuilpacod.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtgjdxubel.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgaxnent.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangdashe.top/Article/details/gtymhuatgd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gtjnyqpayp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtmqjdqewx.html

[B12] 跳出多层循环
来源：http://dali.mhx1999.top/Article/details/gtgxhhhgwf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqxeolqek.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtktmodwhk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtixhykaxo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtdmbevnyy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtibalarda.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtxxnufkkd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daria6918.cn/Article/details/gtsbvpynis.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtvxxkrofm.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmiyodoz.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gtfillvqei.html

PHP:  is_numeric($x)
来源：http://dali.shuidangran.top/Article/details/gtlhsexknm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenzaomai.com/Article/details/gtzhvlnxwz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtxurjoyzd.html

Java: x instanceof Number
来源：http://dali.cdnleiting.top/Article/details/gtvsztfsxm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhijiandao.cn/Article/details/gtzulwjfpu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzekajvxm.html

C#:   x is int or double or decimal
来源：http://dali.shzxlz.cn/Article/details/gtacytfxfs.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtcipwystp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.0kj1m.cn/Article/details/gtdkmjozwe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtqsfsbqza.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtiduxqagx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtsqolppei.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zdqjudy.top/Article/details/gtlqdsguli.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtozvfdkuo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gtiibubpic.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnqzz.top/Article/details/gtymqgafym.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtywlqebgs.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtiwwkovyo.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtuhrsncmh.html

JS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtzfdrjlmm.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gthgkmyolc.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtfboauuya.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtjoeadadd.html

Ruby: a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtesmixely.html

C#:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtyneakbhg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtcukniafn.html

Py:   if not data: return
来源：http://dali.jianghu66.top/Article/details/gtgkramtuo.html

PHP:  if (!$data) { return; }
来源：http://dali.wangdashe.top/Article/details/gtxdwectwr.html

JS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtpifaiudn.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtawocecod.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtcxownvye.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtghgpejec.html

Ruby: return if data.nil?
来源：http://dali.zycfv.cn/Article/details/gtnpucghbm.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtdgrkzyfj.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfeohbwjc.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtvpuuxjwv.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjmmweqp.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtnhbrnugy.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gtonlbedsg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtbqrxqcsb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtmcsaryry.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtecvnwdbr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtuxkpvvew.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.havefunace.top/Article/details/gtymvtuqql.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhengqikj.top/Article/details/gtunawdhhz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtjzwgvvap.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtdxgiqiyg.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gtcqvknmhx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yangfankeji.com/Article/details/gtwjpzapzf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtifwbbqed.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtpklksjbi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.meibo888.top/Article/details/gtgeytrptl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fzhhl.top/Article/details/gtycjxtnll.html

Ruby: def greet(name = "World") = name
来源：http://dali.pengpengdd.cyou/Article/details/gtcvxlburg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gtcqsddkql.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtmdkrepki.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gtbtqfgxra.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gttmgokybd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangshuangyany.cn/Article/details/gtzdppnabg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gtragwblod.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fengsongda.top/Article/details/gtxdhetxqm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtomtprzcx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtmgakfbye.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigfzy.top/Article/details/gteilaxwpt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtgasnvnlm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ybcxt.top/Article/details/gtctsneezf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gtyluclfgv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtbezouhiw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gtjhdhzbgw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258.top/Article/details/gtvowtegqa.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258888.top/Article/details/gtzklndbtn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.mhx1999.top/Article/details/gtqreceqmy.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtfgjkahzr.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtvfwoofaa.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtofsefolp.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtfswrphtf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtnsvowtqt.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtfbzpwcvu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpiuumcmf.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtmjsyvwop.html

Ruby: return a, b
来源：http://dali.birdmap.top/Article/details/gtzdjbvpzz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtkyjdknyu.html

[C06] 匿名函数 / lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtysowfcbg.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gtyvnsupby.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gogol.net.cn/Article/details/gtqnynnevo.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtzvvuursd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtnsvnvukb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.meibo888.top/Article/details/gtgjudvzwa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtvcwhawkw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtvgoxffem.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gtrhrsbzxp.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtapfsrgqr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtdklxfxno.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtmtjmdgvi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.svipenyu.cn/Article/details/gtxmpnpxtj.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtqiwayrwh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hywenlv.cn/Article/details/gtiwwztnaj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtqcieshcr.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gteswppixc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.vqdsnc.cn/Article/details/gtxyqcwgpe.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtymbbrbno.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenzaomai.com/Article/details/gtoubdnxfg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenjidiqi.icu/Article/details/gtegmjniof.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.redwolf501.top/Article/details/gtqucqwgdp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gttbyoklyq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.wangdashe.top/Article/details/gtompyleca.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtnghomgel.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gtucfowkeo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtvtbyeowo.html

[C09] 递归
来源：http://dali.hywenlv.cn/Article/details/gtheqwlxpo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtsihdepqt.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrefzgvmb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jyoumei.cn/Article/details/gtgwhbxfgk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gtfbqbbmxd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtnmgmmcvj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuxming.cn/Article/details/gtchfufnkm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtgegknsrg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtsrhausvk.html

[C10] 变量作用域
来源：http://dali.hfpthk.cn/Article/details/gthkcrrvum.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.andypj.xyz/Article/details/gtgezaqfpa.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtsczjsxix.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.iojbl.cn/Article/details/gtfbgcvyui.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gtgvynexjp.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiehxtajd.html

Go:   花括号块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtclclmanu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtaujtawih.html

C#:   块级作用域
来源：http://dali.cheryme.top/Article/details/gtxvbglrpx.html

[C11] 模块导入与导出
来源：http://dali.aizwys.cn/Article/details/gtojnqtojc.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtheetbzjg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gthfjzqxdr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gthwgeajnt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtyquxwwia.html

Java: import java.util.List;
来源：http://dali.9152youxi.cn/Article/details/gtgznhxvrq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fengsongda.top/Article/details/gtigptwbpv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtqrvpvwfk.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gtctvmhnqs.html

[C12] 立即执行函数 IIFE
来源：http://dali.0kj1m.cn/Article/details/gtgsxowavw.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtlynzfrot.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvicmxvkk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtjqocbsek.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtdtxwsuwl.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtvabtqtxl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.vqdsnc.cn/Article/details/gtucopjfoc.html

Ruby: -> { puts "run" }.call
来源：http://dali.pengpengdd.cyou/Article/details/gtincxfeiz.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj20258.top/Article/details/gtkcppdrgw.html

[C13] 类型声明 / 类型注解
来源：http://dali.jyoumei.cn/Article/details/gttectcjtm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtafifpmtg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqllhvaaq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tanke756.top/Article/details/gtwvtvnidi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gtkccqfqdn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtmyexlkin.html

Go:   func add(a, b int) int
来源：http://dali.yuanzhike.top/Article/details/gtxfmrkxvy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtkphskuzi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj202588.top/Article/details/gtxobgggkm.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtryoylwot.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.quarkkingdee.top/Article/details/gtywwezeca.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtmxzblxjg.html

JS:   // 无泛型
来源：http://dali.316326.xyz/Article/details/gtiikezjtd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtthgeglhv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gthsekcaep.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj202588.top/Article/details/gtemhmerif.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gttagesuwx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gttltvemuk.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtylxprrux.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yangfankeji.com/Article/details/gtwhuweakt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gotoacloud.top/Article/details/gtddjqxmfs.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtlrsvutjf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xziqi.cn/Article/details/gthymjhmmt.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtgleebjrq.html

Go:   // 无解构
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgbgnbkph.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtxnyzqgln.html

C#:   var (a, b) = pair;
来源：http://dali.0kj1m.cn/Article/details/gtcgcngzvm.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtumzajilo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuetiantiany.cn/Article/details/gtlmupgfpx.html

PHP:  // 无重载
来源：http://dali.cdnleiting.top/Article/details/gtefytadry.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gtwystdary.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinqigufen.top/Article/details/gtgvoafrfz.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtrenpewgr.html

Go:   // 无重载：用不同函数名
来源：http://dali.kuanghao11.cn/Article/details/gtehqhaooq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtmpqejsxz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtjslidtqy.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtccnkccma.html

D. 数组 / 列表 / 集合
来源：http://dali.haohaochexian.top/Article/details/gtncsmuwnl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtlqpqjbms.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtbnrqktqg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cqqwz.cn/Article/details/gtaaxvqtjy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yueranfly.top/Article/details/gttzgahudz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtusxzmxev.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtofdotwva.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.andypj.xyz/Article/details/gtpwjfpkvl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtvdpkwell.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtyijmxyrp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtcjtepvuy.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtoczjgcmc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.daria6918.cn/Article/details/gtgcojcxnu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtfjncmpiq.html

JS:   arr.push(4);
来源：http://dali.yonumen.top/Article/details/gtqjakmser.html

TS:   arr.push(4);
来源：http://dali.jinqigfzy.top/Article/details/gtztxdzqhw.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtgeqxxdjh.html

Go:   arr = append(arr, 4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgutzpwqu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.aizwys.cn/Article/details/gtczmaitue.html

C#:   list.Add(4);
来源：http://dali.sxryk.cn/Article/details/gtxogezpct.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtufllcglg.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtvxejljtf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtjlpbgvpc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dashuyun.cn/Article/details/gtosrnxpug.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtazsuxowx.html

Java: list.add(0, 0);
来源：http://dali.guannengcc.top/Article/details/gtifrpbrwg.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cdnleiting.top/Article/details/gtktxfcdvc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtpxfmalwh.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtgymvtril.html

[D04] 删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwihtdlu.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hysaishi.cn/Article/details/gtratedypw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gtesbklmcf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.0kj1m.cn/Article/details/gtpdvfrxox.html

TS:   arr.splice(0, 1);
来源：http://dali.fengsongda.top/Article/details/gtkjspnsmb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.gzhubu.top/Article/details/gtnuqwaxyh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtzvjtwqvj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hfpthk.cn/Article/details/gtlpllvalg.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.yonumen.top/Article/details/gtcvjkbhxd.html

[D05] 访问与修改元素
来源：http://dali.bjfxy.top/Article/details/gtmmphymef.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinqigfzy.top/Article/details/gtltjduats.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtlagxxzps.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtfykrvtmq.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.iojbl.cn/Article/details/gtkivbspuw.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtgdlokbsf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yueranfly.top/Article/details/gtewzgwfcf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gtddufyvnm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtbekictcg.html

[D06] 数组长度
来源：http://dali.tanke756.top/Article/details/gtrbyepkbd.html

Py:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gtrpeqkafr.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gthhzzrthv.html

JS:   arr.length
来源：http://dali.nanxuanxn.top/Article/details/gtepvfwlic.html

TS:   arr.length
来源：http://dali.jianghu66.top/Article/details/gttvbvqpqo.html

Java: list.size();
来源：http://dali.redwolf501.top/Article/details/gtdoyydigz.html

Go:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtnctxavtx.html

Ruby: arr.length; arr.size
来源：http://dali.pycfn.com/Article/details/gtovemvurh.html

C#:   list.Count;
来源：http://dali.wangdashe.top/Article/details/gtzhiqozjk.html

[D07] 切片 / 取子数组
来源：http://dali.chenzaomai.com/Article/details/gtjdgwyarc.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yongpay.top/Article/details/gtaalhdkam.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.cucudq.cn/Article/details/gtjbjtfoin.html

JS:   arr.slice(1, 4);
来源：http://dali.yonumen.top/Article/details/gtpmkgksrt.html

TS:   arr.slice(1, 4);
来源：http://dali.tianlin.xyz/Article/details/gtrbtvgiik.html

Java: list.subList(1, 4);
来源：http://dali.yueranfly.top/Article/details/gtvnuumwfy.html

Go:   arr[1:4]
来源：http://dali.shzxlz.cn/Article/details/gtcrxdfpxp.html

Ruby: arr[1, 3]
来源：http://dali.chenlongwang.top/Article/details/gttemvrchw.html

C#:   list.GetRange(1, 3);
来源：http://dali.chenlongwang.top/Article/details/gtoonncyxm.html

[D08] 合并两个数组
来源：http://dali.sysykeji.top/Article/details/gtrflmaldx.html

Py:   a + b;  a.extend(b)
来源：http://dali.fzhhl.top/Article/details/gtbfvjnuoo.html

PHP:  array_merge($a, $b);
来源：http://dali.mhx1999.top/Article/details/gttxkjqavn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.dianchejie.cn/Article/details/gtztkranfd.html

TS:   [...a, ...b];
来源：http://dali.zdqjudy.top/Article/details/gtyzfamnkc.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.yuxming.cn/Article/details/gtpwtxxata.html

Go:   append(a, b...)
来源：http://dali.svipenyu.cn/Article/details/gtansvwxlk.html

Ruby: a + b;  a.concat(b)
来源：http://dali.dashuyun.cn/Article/details/gtbzpflyus.html

C#:   a.Concat(b).ToList()
来源：http://dali.nanxuanxn.top/Article/details/gtpnoxplfe.html

[D09] 排序（升序）
来源：http://dali.meibo888.top/Article/details/gtvkgyyvyo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.gotoacloud.top/Article/details/gtetjrrsgs.html

PHP:  sort($arr);
来源：http://dali.hammf.cn/Article/details/gtjqpxseje.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.hnxiangtu.top/Article/details/gtapkvpmpi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.nwbrower.top/Article/details/gtvgxncdlp.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.pycfn.com/Article/details/gtpephhcld.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.dianchejie.cn/Article/details/gtsmxwkwry.html

Ruby: arr.sort
来源：http://dali.sufxvd.cn/Article/details/gtnfilrafj.html

C#:   list.Sort();
来源：http://dali.kuanghao11.cn/Article/details/gtyhkzdsmf.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.pengpengdd.cyou/Article/details/gtzrktsypl.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.xylfe.cn/Article/details/gtqzlxxybi.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gthjitgpua.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.ppjwa.cn/Article/details/gtfnbgrkxr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.feifeiyinyue.top/Article/details/gtehzrjfkf.html


<!-- 参考信息 -->