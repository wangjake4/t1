代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gttuenkjzw.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtpzsmgmml.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnqzz.top/Article/details/gtegmpvzbu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yueranfly.top/Article/details/gtgvwndyxt.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gtmlyikulk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtbhsvofic.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtijbpyesk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuanzx.com/Article/details/gtgjswcefr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtidljjknf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gtdwzmacee.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtnzyjzfmh.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtyoydbbwo.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtlarzrexd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtrvbweflo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gttaoukirn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtzbobdamv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258.top/Article/details/gtxdddxbqg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.9152youxi.cn/Article/details/gtohylrrcj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtkpmqmldm.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaazitlam.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gtotbexwev.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daxiang520.top/Article/details/gtprhqqzih.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtovisncae.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtzzohbnss.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtzuiznpbt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gtfxxfqzfl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.c1oappe.top/Article/details/gtcrlexvqq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tianlin.xyz/Article/details/gthknlrtec.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtlxpcvpyv.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtfwdxmnao.html

PHP:  is_numeric($x)
来源：http://dali.cheryme.top/Article/details/gtfdklqjab.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtycepztvu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmbcbylwj.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtdqiapizf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtnrfnohxj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.havefunace.top/Article/details/gtqojlpthc.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtcaeiwneo.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gthgxsufpt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.redwolf501.top/Article/details/gtwrfclcvu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gtbhezwbhz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtofosxfde.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtzoaoejeq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtqtwlznnp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gtjsrzembz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pengpengdd.cyou/Article/details/gthbzcfdxr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtidawcgyu.html

[B15] 布尔运算与取反
来源：http://dali.ehwqpu.com/Article/details/gtwyytsbhz.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtvssdkldi.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtoyjsfhoa.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtucvdwhsr.html

TS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gttkdxebbq.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtuibqvhwz.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtxtojrzrd.html

Ruby: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtfroqeycq.html

C#:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtdileryir.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gtvtqjjazp.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gtmotnsgsj.html

PHP:  if (!$data) { return; }
来源：http://dali.zhongyouzk.top/Article/details/gtorvvlojz.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gthszwptrg.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtpvtssiko.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gtkhysalll.html

Go:   if data == nil { return }
来源：http://dali.iojbl.cn/Article/details/gtsbbiawvh.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gthtgioanj.html

C#:   if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtthrevtpp.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttyvmevsj.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtphqmkhgk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkgozsfd.html

[C01] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtrugtzugi.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtluwrjbrj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtzxsjnxgv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gteanlbbgx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtjodbzzrw.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtcdjemmgj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gtchehzkfe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtgoadeipa.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtuhdryrgm.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtlkakkyyg.html

Py:   def greet(name="World"): return name
来源：http://dali.nanxinkj.top/Article/details/gtezytcbph.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtxwzsxrlw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gtrqcnunhh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtzjrqeykk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtasausogu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtmcolsajk.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gttdorjkdm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtufpqhwob.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtkjwimzym.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtemuzlsrm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dashuyun.cn/Article/details/gthilxxhhq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtqxmconpj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtedaxufhi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cqqwz.cn/Article/details/gtjaypphdv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.iojbl.cn/Article/details/gtferjlanx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtxkfeusvg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinqigufen.top/Article/details/gtmblofsvv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtqhavsjkc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.haohaochexian.top/Article/details/gtgiitjnhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.snrcjt.cn/Article/details/gtqkvhwqvi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtzwqdtabd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtoonebuxd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aizwys.cn/Article/details/gtdgdxutlz.html

Go:   // 无：用配置结构体参数
来源：http://dali.hysaishi.cn/Article/details/gtfrhlforo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtynvmlppm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtbvtphrje.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtnsftqjnn.html

Py:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gtafnjvuze.html

PHP:  return [$a, $b];
来源：http://dali.daria6918.cn/Article/details/gtgvcedapm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gtoxmaqikb.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtzlhdgecy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqqsvdqim.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtdoqtwnuh.html

Ruby: return a, b
来源：http://dali.zycfv.cn/Article/details/gtrjrmlrmn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtqwevddph.html

[C06] 匿名函数 / lambda
来源：http://dali.tian-w.cn/Article/details/gthvrvefcm.html

Py:   square = lambda x: x * x
来源：http://dali.gzhubu.top/Article/details/gtymcgbppk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gtxiybfwwb.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtlcltnkpi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtnfwkycfm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtccbbcqua.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gtqnzrcpwz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthemkhvtb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtuclszvep.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtcqimljnk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jqgfzy.top/Article/details/gttrwkxjjk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gtmqyyeobf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtdpirniqc.html

TS:   arr.map(String)
来源：http://dali.316326.xyz/Article/details/gtsbfahdxj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gtliezruaw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gtqqikqbwk.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gtucudkpdf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gtxjottrts.html

[C08] 闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtendfwqac.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtcnldmpvr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gtuggcifno.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daria6918.cn/Article/details/gttiersrab.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtogapjoaz.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hfpthk.cn/Article/details/gtebqvwgpj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtgopuxzdw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gttexdbliq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gthijpkazz.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtvqjkksjn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtswkvncmp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtyrctrhyf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtlvdcdath.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtosmreyyj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtawxdwszg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258.top/Article/details/gtkxiqouoj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtuajtygta.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aizwys.cn/Article/details/gtbfghanjy.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtygievilt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtzysmyitn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xylfe.cn/Article/details/gtgyigkmth.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj20258.top/Article/details/gtrpcryzgt.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gtubckxlpu.html

Java: 方法内为块级作用域
来源：http://dali.ppjwa.cn/Article/details/gtkgfscfcv.html

Go:   花括号块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtdiwsknpm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.havefunace.top/Article/details/gtixyvpgib.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gteqpuottb.html

[C11] 模块导入与导出
来源：http://dali.shuidangran.top/Article/details/gtcnjxibgb.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtidyrpent.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gtdhankjqn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtkkpqvqmx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jlsjyb.cn/Article/details/gteaxmwomw.html

Java: import java.util.List;
来源：http://dali.gaohongyu789.top/Article/details/gtvkzqguvj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.mhx1999.top/Article/details/gtcxzpmhhc.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtklhzfeia.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtjjywbafr.html

[C12] 立即执行函数 IIFE
来源：http://dali.quarkkingdee.top/Article/details/gtgfrfczqh.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gtdrbpalci.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtzzgnhljo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daria6918.cn/Article/details/gtewkazegz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtdjmbvvtf.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sufxvd.cn/Article/details/gtiestksbv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtvyjoqnfo.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtnfufavfh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrnalzjv.html

[C13] 类型声明 / 类型注解
来源：http://dali.yueranfly.top/Article/details/gtytuapskp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xziqi.cn/Article/details/gtrfajfkne.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtbdcxyggd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.andypj.xyz/Article/details/gtlijgektp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtdcipqydh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtmbmuxecv.html

Go:   func add(a, b int) int
来源：http://dali.hysaishi.cn/Article/details/gtqkldusss.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtudgyemix.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtbxfxkfqv.html

[C14] 泛型函数
来源：http://dali.tian-w.cn/Article/details/gtdhodcmjy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hysaishi.cn/Article/details/gtzzobcena.html

PHP:  // 无泛型
来源：http://dali.svipenyu.cn/Article/details/gtvscvautv.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtdijvqptj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cheryme.top/Article/details/gtgsuuanjd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.aibaodan.cn/Article/details/gteyyjcbcy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhixingplan.top/Article/details/gtjuugpvod.html

Ruby: # 无泛型
来源：http://dali.zycfv.cn/Article/details/gtbqsjpewr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tanke756.top/Article/details/gthhunzaqz.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtipdprgoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenlongwang.top/Article/details/gthokzkcle.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtdrthodyf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtmdxucblo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zycfv.cn/Article/details/gtceougpnf.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtrkkgmefo.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gtevgsnbet.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtifdcrljv.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtgfkmsxgu.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gthjuapfjv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gttfmvlmcf.html

PHP:  // 无重载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpajtzeqg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ehwqpu.com/Article/details/gtqxnkdkmk.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gteqncxyfb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtjfgqfnmt.html

Go:   // 无重载：用不同函数名
来源：http://dali.shuidangran.top/Article/details/gtvqlvpoew.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhoulong.xyz/Article/details/gthrmtgvzh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fengsongda.top/Article/details/gtwpcyviwi.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtwiuagrxh.html

D. 数组 / 列表 / 集合
来源：http://dali.fengsongda.top/Article/details/gtoitpopve.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdglmxamh.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtvaamcmnf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.gogol.net.cn/Article/details/gtgepgogwn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtgyeiqfre.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ehwqpu.com/Article/details/gtfnjcdeks.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtnqpziodi.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gtxpkloslp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.bjfxy.top/Article/details/gtvxvzcvbg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtegfryozw.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.tian-w.cn/Article/details/gtirjcrdtj.html

[D02] 追加元素到末尾
来源：http://dali.guowangkeji.top/Article/details/gtrzftyslj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gthpfkebhw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtgefkzqcs.html

JS:   arr.push(4);
来源：http://dali.9152youxi.cn/Article/details/gtpgxekhwe.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtcujcpwkh.html

Java: list.add(4);
来源：http://dali.yuxming.cn/Article/details/gtimqpylcg.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gturveumxo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtnlrzboov.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gtpzrejavc.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtsibsadhz.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtnkdgbiwb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xinyue.icu/Article/details/gtvzukyiel.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xinyue.icu/Article/details/gthqhuzukx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gtfletkaak.html

Java: list.add(0, 0);
来源：http://dali.sweek.top/Article/details/gthwnnjfvl.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gtfvnrjfen.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jqgufenzy.top/Article/details/gtxspzpmzf.html

C#:   list.Insert(0, 0);
来源：http://dali.yj20258888.top/Article/details/gtpldnmmvj.html

[D04] 删除元素
来源：http://dali.smart0.xyz/Article/details/gtcnecbidi.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.meibo888.top/Article/details/gtdkkgkdcg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepjcedrx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gttaadzsdf.html

TS:   arr.splice(0, 1);
来源：http://dali.jianghu66.top/Article/details/gtuaqqeiav.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gttptnduuq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinqigufen.top/Article/details/gtzishpgtv.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtzsbvapap.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtlmsnljqr.html

[D05] 访问与修改元素
来源：http://dali.shzxlz.cn/Article/details/gtgzmretem.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gtrcdwvabs.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.xziqi.cn/Article/details/gtlzxjxhmm.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.ybcxt.top/Article/details/gtltusufcg.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jianghu66.top/Article/details/gtstynznqo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.ehwqpu.com/Article/details/gtcvnceszx.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtkpfnekyq.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtsubtkpii.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.svipenyu.cn/Article/details/gtrcqupmsp.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gthqejswlk.html

Py:   len(arr)
来源：http://dali.jiagoushi.top/Article/details/gtbpbyydxb.html

PHP:  count($arr);
来源：http://dali.mhx1999.top/Article/details/gtbjzhsbdq.html

JS:   arr.length
来源：http://dali.ydzc1.top/Article/details/gtfyruxjid.html

TS:   arr.length
来源：http://dali.xuanzx.com/Article/details/gtpgegncyx.html

Java: list.size();
来源：http://dali.cucudq.cn/Article/details/gtyaiuqplv.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtpnxyhejn.html

Ruby: arr.length; arr.size
来源：http://dali.jyoumei.cn/Article/details/gtqbulcqoo.html

C#:   list.Count;
来源：http://dali.hnqzz.top/Article/details/gtlcbysrzv.html

[D07] 切片 / 取子数组
来源：http://dali.pengpengdd.cyou/Article/details/gtszovhkfj.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.haohaochexian.top/Article/details/gtlqeroapq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.meibo888.top/Article/details/gtbktrrtnl.html

JS:   arr.slice(1, 4);
来源：http://dali.snrcjt.cn/Article/details/gtqxwxbtlj.html

TS:   arr.slice(1, 4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjssfolcw.html

Java: list.subList(1, 4);
来源：http://dali.kuanghao11.cn/Article/details/gtmltpdeiq.html

Go:   arr[1:4]
来源：http://dali.jyoumei.cn/Article/details/gtmcxlslkr.html

Ruby: arr[1, 3]
来源：http://dali.havefunace.top/Article/details/gtoxjcoggj.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtevpdznkf.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrrnwecs.html

Py:   a + b;  a.extend(b)
来源：http://dali.ybcxt.top/Article/details/gtpcbqvooe.html

PHP:  array_merge($a, $b);
来源：http://dali.zdqjudy.top/Article/details/gtvhyhomcu.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtmqghorqg.html

TS:   [...a, ...b];
来源：http://dali.sysykeji.top/Article/details/gtzkedkdmh.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xziqi.cn/Article/details/gtiojhdupk.html

Go:   append(a, b...)
来源：http://dali.xinyue.icu/Article/details/gtqmjylnhj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.wangdashe.top/Article/details/gtbkjykzcn.html

C#:   a.Concat(b).ToList()
来源：http://dali.jinqigfzy.top/Article/details/gttfnvvahm.html

[D09] 排序（升序）
来源：http://dali.ybcxt.top/Article/details/gtomyodtwx.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.pengpengdd.cyou/Article/details/gtwpxlwzlu.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdejwailq.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvshvkiej.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmdrkpjlb.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.shuidangran.top/Article/details/gtfgimhlxl.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.xinyue.icu/Article/details/gtyfhlfwpz.html

Ruby: arr.sort
来源：http://dali.dashuyun.cn/Article/details/gtvkcpdxre.html

C#:   list.Sort();
来源：http://dali.yangfankeji.com/Article/details/gtbkfzdtiq.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.bjfxy.top/Article/details/gtzjvrrfae.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.sweek.top/Article/details/gtwxtviuwh.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtswiezdie.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.iojbl.cn/Article/details/gtysgzweps.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hfpthk.cn/Article/details/gtyvnwsxxj.html


<!-- 参考信息 -->