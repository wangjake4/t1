代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtvgpjfeab.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gtzuplffka.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtwqctulik.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtmlahpfbh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtzvucxibg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtwkunhjsv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangshuangyany.cn/Article/details/gttbhwsqeg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenlongwang.top/Article/details/gtiqpvfrle.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gtnbuhepeo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtxinlamqh.html

[B11] 生成数字序列 / 区间
来源：http://dali.gotoacloud.top/Article/details/gtbfmpuxfg.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinghuilouyu.cn/Article/details/gtmomtgpay.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtimvnwvbk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gtzyrsynlr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgxpgisk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.bjfxy.top/Article/details/gtumurwffm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtjdbmrlpg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gtislybhwb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtolqveptr.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gtgldxopjf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtlboxisfx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtqcxdwnrt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtjnolbsch.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtxcoypnlv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtrhryqskq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gtdlvpghja.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtxzwinynu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gtsqeljfmp.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gtscbdfitb.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenjidiqi.icu/Article/details/gtxjtkrhez.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtipotoxni.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtxszdzhjc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gtneahkjdx.html

Java: x instanceof Number
来源：http://dali.316326.xyz/Article/details/gtwcfkyjdr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtxqmgneyu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcwqiwwrk.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtaconebfl.html

[B14] 判断值是否在集合内
来源：http://dali.yuanzhike.top/Article/details/gtdejmefcg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cheryme.top/Article/details/gtohqeubim.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtkdvziwhm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gtlfkjssbj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnqzz.top/Article/details/gtusjilzsz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtdspyyowj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guowangkeji.top/Article/details/gtgselbtol.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtybqerggs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtwwvacacj.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtyjzsqgoc.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtqcssuwyz.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtfyhgejtk.html

JS:   a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtvhxblyji.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtfdvaujdv.html

Java: a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtynnkyolc.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtuuejrvil.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtyxyqqpwg.html

C#:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtimlyeach.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sufxvd.cn/Article/details/gtrnrbblbo.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtgoxniudy.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtolnkbqja.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtdpxoflvf.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtsezwhyee.html

Java: if (data == null) return;
来源：http://dali.cdnleiting.top/Article/details/gtmddcyghk.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtvuptzndw.html

Ruby: return if data.nil?
来源：http://dali.xylfe.cn/Article/details/gttjsfqsyx.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtstdfhqrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtosngtoho.html

C. 函数与作用域
来源：http://dali.hammf.cn/Article/details/gtyohlxizw.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtdfjcpjav.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gtkijzcivm.html

Py:   def add(a, b): return a + b
来源：http://dali.havefunace.top/Article/details/gtewaqqfzb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtxaqvidbn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtexqikhyt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohhftxuj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtdtojzgme.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtwgptquea.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtorgiedoo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtfmoensua.html

[C02] 默认参数
来源：http://dali.tianlin.xyz/Article/details/gtfjpfxiyf.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gtouchdbed.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnbakfnq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtlyqksjbo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtsxpgbzxa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtjawziaou.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtvlkrxnyd.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtfpfnwvsj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shanyushiyangtech.top/Article/details/gtepvrsvxh.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gtaixntsuy.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gtecwjlvme.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jiagoushi.top/Article/details/gtudvhurpa.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aizwys.cn/Article/details/gtcjayckrc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtorkesmut.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.quarkkingdee.top/Article/details/gtstajrcoa.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.smart0.xyz/Article/details/gtndgbevyt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpruxfkat.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtbrsnccxo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hammf.cn/Article/details/gtkuztbjjg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zdqjudy.top/Article/details/gtktluissp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gtqotinxou.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yongpay.top/Article/details/gtukcvxqdt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtjkiyuzxb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtruiilslu.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gtwzwzvrmw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gtyjxzymeg.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtgujcatxt.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gtljoprswv.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtexpefepd.html

PHP:  return [$a, $b];
来源：http://dali.ehwqpu.com/Article/details/gtarmjzlhj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yueranfly.top/Article/details/gtfqpgybwe.html

TS:   return { a, b };
来源：http://dali.sufxvd.cn/Article/details/gtdpsfmmza.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jqgufenzy.top/Article/details/gtkllhhqib.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtizvsrmyv.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtbumcznre.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtgnpffcoz.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtmiwssrih.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtkjwjzeyl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.daria6918.cn/Article/details/gtcfrwvewe.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gttjfmsqlz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.haohaochexian.top/Article/details/gtdkbthtvm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwfepyuz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pycfn.com/Article/details/gtpvzeiovm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yuanzhike.top/Article/details/gtkmwejkbn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtxaseqrkx.html

[C07] 把函数作为参数传入
来源：http://dali.316326.xyz/Article/details/gtnjyusbqh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gttqatfmvr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gtsoysunjz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtcyudbzhd.html

TS:   arr.map(String)
来源：http://dali.aizwys.cn/Article/details/gtyilydekp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.haohaochexian.top/Article/details/gtsjnruxgr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.vqdsnc.cn/Article/details/gtwujrytph.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhongyouzk.top/Article/details/gtvqepjhza.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtlafsmaev.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtkfatrgmy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtzkyfbbuh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtsbloryxa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtllkzwsyq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtdwgnjzjf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.9152youxi.cn/Article/details/gtfkhxtgfw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.snrcjt.cn/Article/details/gtkysejikj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtoeqywfcl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cashguo.top/Article/details/gtydtmeuha.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtjcilulik.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtobtewvet.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtzpkeilnm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gteqvanbqt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtveefuxdi.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtegdmswet.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gtwhyxiuhx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtjgbngmkw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gtuywycxjz.html

[C10] 变量作用域
来源：http://dali.pengpengdd.cyou/Article/details/gthrubcnjh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtikxvfdla.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jianghu66.top/Article/details/gtplemczjj.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtpdzzbapp.html

TS:   同 JS
来源：http://dali.shuidangran.top/Article/details/gtdwiaarok.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtmkjekjak.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtambrunrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtpqtxevwa.html

C#:   块级作用域
来源：http://dali.shuidangran.top/Article/details/gtgmtnxtbx.html

[C11] 模块导入与导出
来源：http://dali.vqdsnc.cn/Article/details/gtxgslgtsg.html

Py:   from module import func
来源：http://dali.cdnleiting.top/Article/details/gtngsdprbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtnvsdlvgx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gtumwogmlw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jqgufenzy.top/Article/details/gtpqgnmuph.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmhyyeyi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtpzqynhnn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zycfv.cn/Article/details/gtzidbolsq.html

C#:   using System.Text;
来源：http://dali.chenjidiqi.icu/Article/details/gtcpehixrl.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gtnwhyyaot.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gttohdziwu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtzkifxjmu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtvovbjueo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ydzc1.top/Article/details/gtmwjqfrxv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtrowfgsxw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aibaodan.cn/Article/details/gtnclvznaz.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gtqmqxtlfq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gturcnnwpc.html

[C13] 类型声明 / 类型注解
来源：http://dali.sxryk.cn/Article/details/gtakqadpbj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gteuofmcqt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtryfmzwid.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.quarkkingdee.top/Article/details/gtzchlprph.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtnqkaoxne.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtubfojpxc.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtvvbtfssm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shangyingyoupin.top/Article/details/gtnucrjucz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtkzbyyurr.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtczhwxsrf.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtibddamsa.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gtdilymsce.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtfmazogzr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtzjbbseml.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbvnkvrgh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxinkj.top/Article/details/gthspcwwwi.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtskiwmmfm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtzwjckkaz.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtjwrksidw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.meibo888.top/Article/details/gtbteavagb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtoojtijpl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtdympxoyf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.dashuyun.cn/Article/details/gtwsbobelu.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtamobcyto.html

Go:   // 无解构
来源：http://dali.gogol.net.cn/Article/details/gtszjmhgmh.html

Ruby: a, b = pair
来源：http://dali.fzhhl.top/Article/details/gtjagnklvd.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gtkovfzmdw.html

[C16] 函数 / 方法重载
来源：http://dali.xylfe.cn/Article/details/gtejsspsrd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtjdfxezcx.html

PHP:  // 无重载
来源：http://dali.zycfv.cn/Article/details/gtslthruvz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtistdpuye.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtyjtrytzu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.bjfxy.top/Article/details/gtjcvjfxie.html

Go:   // 无重载：用不同函数名
来源：http://dali.jlsjyb.cn/Article/details/gtddqkfwku.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtnbcwtmhi.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zycfv.cn/Article/details/gtbnxcllkg.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtgeuxotkv.html

D. 数组 / 列表 / 集合
来源：http://dali.tian-w.cn/Article/details/gtdeckjzuh.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtvuapvufc.html

[D01] 创建数组 / 列表
来源：http://dali.hysaishi.cn/Article/details/gtgvxvnyvd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtrtkixcqx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gthvrphuhy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hysaishi.cn/Article/details/gtgrggqcpo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxczssou.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgfzy.top/Article/details/gtcowvrmzr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.nanxuanxn.top/Article/details/gtxvqmvjmr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gtsccxsaxj.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gthyhrfngq.html

[D02] 追加元素到末尾
来源：http://dali.pycfn.com/Article/details/gtfukianrm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpsqxmor.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.hnxiangtu.top/Article/details/gtgdbbdapm.html

JS:   arr.push(4);
来源：http://dali.jqgfzy.top/Article/details/gtbfveeneo.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gturfcgobf.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtlxsvwfzp.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtuhozyuoi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guowangkeji.top/Article/details/gtsufugvff.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtagjryscu.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtbyqolcli.html

Py:   arr.insert(0, 0)
来源：http://dali.wangdashe.top/Article/details/gtgbfgioge.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.mhx1999.top/Article/details/gtkoitowrb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.nwbrower.top/Article/details/gtenihinov.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtoxtjpuyw.html

Java: list.add(0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtoykxxvra.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jlsjyb.cn/Article/details/gtfjdefuqf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.guowangkeji.top/Article/details/gtxkvjozhg.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtgipisrgb.html

[D04] 删除元素
来源：http://dali.guowangkeji.top/Article/details/gtrqwkciqs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtnprmzgna.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkekhvgxc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yanxiufei.cn/Article/details/gtvndjeahb.html

TS:   arr.splice(0, 1);
来源：http://dali.dianchejie.cn/Article/details/gtfbaimtyh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.svipenyu.cn/Article/details/gtueocsmgy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zhongyouzk.top/Article/details/gtqhxxsgnz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetxteqzk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtnibdaeqk.html

[D05] 访问与修改元素
来源：http://dali.yj20258888.top/Article/details/gtjrljpzir.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yj202588.top/Article/details/gtgdcyycnc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtkrlykahs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.feifeiyinyue.top/Article/details/gtyfywvrup.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.tanke756.top/Article/details/gtkdpdcwtk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtonnldpux.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jianghu66.top/Article/details/gtudtuutnl.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtymyoafic.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenzaomai.com/Article/details/gtcuarsncp.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gttdfccnop.html

Py:   len(arr)
来源：http://dali.cashguo.top/Article/details/gtvxfykgvv.html

PHP:  count($arr);
来源：http://dali.yangfankeji.com/Article/details/gtmiisyquq.html

JS:   arr.length
来源：http://dali.cashguo.top/Article/details/gtfbusoyre.html

TS:   arr.length
来源：http://dali.zhiwuduotai.top/Article/details/gtjjzrvqvt.html

Java: list.size();
来源：http://dali.mhx1999.top/Article/details/gtmskzachz.html

Go:   len(arr)
来源：http://dali.sxryk.cn/Article/details/gttkgsszpa.html

Ruby: arr.length; arr.size
来源：http://dali.jqgfzy.top/Article/details/gtaqwqoitm.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gtibhhcgln.html

[D07] 切片 / 取子数组
来源：http://dali.zdqjudy.top/Article/details/gttmmerdjf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.sxryk.cn/Article/details/gtrxjjjvlb.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.sufxvd.cn/Article/details/gtyetfiduj.html

JS:   arr.slice(1, 4);
来源：http://dali.xziqi.cn/Article/details/gtrtvdmepq.html

TS:   arr.slice(1, 4);
来源：http://dali.xuetiantiany.cn/Article/details/gtemhubqfk.html

Java: list.subList(1, 4);
来源：http://dali.feifeiyinyue.top/Article/details/gtelguogqz.html

Go:   arr[1:4]
来源：http://dali.quarkkingdee.top/Article/details/gtsippubgb.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtlaqhmvqg.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtalvjzltz.html

[D08] 合并两个数组
来源：http://dali.fengsongda.top/Article/details/gtobzkwrjk.html

Py:   a + b;  a.extend(b)
来源：http://dali.zdqjudy.top/Article/details/gtuzrqdcql.html

PHP:  array_merge($a, $b);
来源：http://dali.feifeiyinyue.top/Article/details/gtmgsfcibl.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvamqhbuu.html

TS:   [...a, ...b];
来源：http://dali.hnxiangtu.top/Article/details/gtzmtyeorl.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmmewlco.html

Go:   append(a, b...)
来源：http://dali.9152youxi.cn/Article/details/gtvdirgqak.html

Ruby: a + b;  a.concat(b)
来源：http://dali.pycfn.com/Article/details/gtbwrnfedi.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtivfjodkh.html

[D09] 排序（升序）
来源：http://dali.ydzc1.top/Article/details/gtbljjnbuw.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwewbuwdg.html

PHP:  sort($arr);
来源：http://dali.yj202588.top/Article/details/gtjfatljlp.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.tianlin.xyz/Article/details/gtfedjliyk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.sufxvd.cn/Article/details/gttcrywyrk.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.nwbrower.top/Article/details/gthwpcmkyk.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.hfpthk.cn/Article/details/gtramywmmg.html

Ruby: arr.sort
来源：http://dali.nanxinkj.top/Article/details/gtlpeslxgv.html

C#:   list.Sort();
来源：http://dali.ppjwa.cn/Article/details/gtrnlljxkz.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnxiangtu.top/Article/details/gtmcmnkpij.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.shuidangran.top/Article/details/gtxcbfsxyb.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gtfxpsfajs.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.jyoumei.cn/Article/details/gtxvllmgtu.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.c1oappe.top/Article/details/gtjcxcjfjq.html


<!-- 参考信息 -->