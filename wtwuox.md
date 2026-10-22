代发 wailian999

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtkgzdnrly.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtukdqphch.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yvedp.cn/Article/details/gtpfkxbdol.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtclilpmfa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gtmnunwbif.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtrflaokck.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuanzx.com/Article/details/gtkjedanhy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtbxlwvpvl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtybxbjivx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtdtwlnlis.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gtkceckdsg.html

Py:   list(range(0, 10, 2))
来源：http://dali.nwbrower.top/Article/details/gtbfzfygao.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtwdjszudy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258888.top/Article/details/gtyzpeppyb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gthacrszln.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cdnleiting.top/Article/details/gtvpsqvowd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfdqkacq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yanxiufei.cn/Article/details/gtpauxvkaf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtrxsddhzr.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndcbpwuf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gtxzpwabaw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.svipenyu.cn/Article/details/gtacufpihn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtxxdcmkvg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtdohivoax.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtrckxmuub.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwaxndfod.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gtbeebvajs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinqigufen.top/Article/details/gtxsoptszb.html

[B13] 判断是否为数字
来源：http://dali.zhongyouzk.top/Article/details/gtvabrguhg.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtvuuqtesr.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gtzyshnvtj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtjiersyte.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtwhsbmurp.html

Java: x instanceof Number
来源：http://dali.yueranfly.top/Article/details/gtlmsskcwl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtdvzyxtrh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtizkwnvsi.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtqyyliwzp.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gtlnkbsvjm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gticxovois.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daria6918.cn/Article/details/gtdsatacyi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtsyvqayyh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtptrfujke.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gtrziiysku.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhdduumg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gthtnhnkrg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtkulalkjl.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gthvkbnmzw.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtyvrepuzt.html

PHP:  $a && $b || !$c
来源：http://dali.zdqjudy.top/Article/details/gtjdnmbwda.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtiadxcqrz.html

TS:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtqaxdyidl.html

Java: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtpfovzjiw.html

Go:   a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtnwvwabay.html

Ruby: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtwzkmwmvi.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtsmzwcmdw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gtaqixvnxs.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtracjxbby.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvsikhwwf.html

JS:   if (!data) return;
来源：http://dali.yuanzhike.top/Article/details/gtyptwiast.html

TS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtdeuqfhzq.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtpgsmbycf.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtsyiztmkk.html

Ruby: return if data.nil?
来源：http://dali.cashguo.top/Article/details/gtuzsjvvex.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtldwxifvn.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtiaoyqvmj.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtsrgihuzh.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgbjidpia.html

[C01] 定义函数
来源：http://dali.ivvv.top/Article/details/gtsevudtmk.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gtusautpor.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtwcnpniiw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtpnjutzey.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtusnycwro.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtgkgnqxer.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtrcqydyia.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtzhxstrah.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtenjmnirg.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtafleyaym.html

Py:   def greet(name="World"): return name
来源：http://dali.aizwys.cn/Article/details/gtdsdacvxh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrxshupy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtukkuqqzm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfgaigqxm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hysaishi.cn/Article/details/gtpqunmpkh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtzabgitpz.html

Ruby: def greet(name = "World") = name
来源：http://dali.yongpay.top/Article/details/gtdevughog.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtcskjztnv.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtccwiyhor.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtwmzijymz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinqigfzy.top/Article/details/gtoaslizud.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtkkqucrsh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ydzc1.top/Article/details/gtqumyoxtv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtbwuhbnzj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtwtyldmvw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cheryme.top/Article/details/gtaugcivft.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxinkj.top/Article/details/gtsuunyfpr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.vqdsnc.cn/Article/details/gtyshzebzi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gttcokycul.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtijxmsziw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gtqlxaksxk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gtzkylffle.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hnqzz.top/Article/details/gtiswtqitz.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtmvkrwrks.html

Ruby: f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtlmysxntb.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtftigitox.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtqrhikhjt.html

Py:   return a, b
来源：http://dali.chenzaomai.com/Article/details/gtzkpelkyf.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtosmxbgle.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.quarkkingdee.top/Article/details/gtbxlyhtxu.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtfshaacdm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtggmetoer.html

Go:   return a, b
来源：http://dali.quarkkingdee.top/Article/details/gthhqzhoge.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtkjuvofka.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtsbvakcfl.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtuuplklrn.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtabzzsazf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gtwhccrqqv.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtogrpjewz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtwafziwgb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sysykeji.top/Article/details/gtsvoudxot.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtevkxkiit.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtyqzbewul.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtadqafuhe.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtilbbukti.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gtvfegqbpx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yj20258.top/Article/details/gtuyyjoiij.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gtmotrvspm.html

TS:   arr.map(String)
来源：http://dali.daxiang520.top/Article/details/gtjygcngic.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtcdktoteo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gttvxiubbq.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gtrqrlhlda.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xylfe.cn/Article/details/gtvvsoacbz.html

[C08] 闭包
来源：http://dali.ppjwa.cn/Article/details/gttftsictl.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtdhvjgtsz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gtninrmxvj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtzykxdqys.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtwcvmshej.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.birdmap.top/Article/details/gtrxsumrrj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gtodcnzrlb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.guannengcc.top/Article/details/gtlnengbaq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtzjhzwzrc.html

[C09] 递归
来源：http://dali.daxiang520.top/Article/details/gtfquhyoyr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtqgnxotwr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.aizwys.cn/Article/details/gtjdnryvka.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtfdgzyltn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtjtxzepwg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtvbnlbpds.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gthzmmoant.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxanumjjj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.9152youxi.cn/Article/details/gtqycviler.html

[C10] 变量作用域
来源：http://dali.guannengcc.top/Article/details/gtagqvauvc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtwmheuksz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.mhx1999.top/Article/details/gtwvzlxqbk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtswazzbnh.html

TS:   同 JS
来源：http://dali.zhixingplan.top/Article/details/gtrwppkgrm.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtgsbruwww.html

Go:   花括号块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtnbxmqaom.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gtwfeulsby.html

C#:   块级作用域
来源：http://dali.ivvv.top/Article/details/gtbhyhkfvz.html

[C11] 模块导入与导出
来源：http://dali.guannengcc.top/Article/details/gtzzozjzsi.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtwvuhjpvk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.bjfxy.top/Article/details/gtisorufje.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gtznycbwwb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gtvqkpfnwv.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtadowhfzj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hfpthk.cn/Article/details/gtqkdyqmms.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtcnskbgyf.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gtefeetvhu.html

[C12] 立即执行函数 IIFE
来源：http://dali.cashguo.top/Article/details/gtexxildtu.html

Py:   (lambda: print("run"))()
来源：http://dali.gzhubu.top/Article/details/gtwoebrfna.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gtjawpixbi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yanxiufei.cn/Article/details/gtnxtnmxvj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.iojbl.cn/Article/details/gthmlnaglz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtzfyhgcnu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gtsnovyaoi.html

Ruby: -> { puts "run" }.call
来源：http://dali.tian-w.cn/Article/details/gtypzwjybn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yj202588.top/Article/details/gtmdkhfwqu.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtjqyrpqlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.guannengcc.top/Article/details/gtksbpbqqa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtdczqhbaj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.smart0.xyz/Article/details/gtgufkyhsy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtrruxxzsa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtogjwxfmo.html

Go:   func add(a, b int) int
来源：http://dali.zhiwuduotai.top/Article/details/gtrycbevji.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtywgxwhyf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gtvsqzxoii.html

[C14] 泛型函数
来源：http://dali.aizwys.cn/Article/details/gtcykkomqm.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxndkoalo.html

PHP:  // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtiqjcxdhb.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtnkfoqsdd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtuureqizs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtfwpvlowl.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.pengpengdd.cyou/Article/details/gtwwcyscmr.html

Ruby: # 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtfxrfahbq.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gtxvmcgqzb.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtccmbtmzn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guowangkeji.top/Article/details/gtwxuqcrzm.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtxejnthxp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtltmnsvgt.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtjitlsqtq.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gthopjbvdg.html

Go:   // 无解构
来源：http://dali.iojbl.cn/Article/details/gtbezbevep.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokwnseuf.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtblewpgiy.html

[C16] 函数 / 方法重载
来源：http://dali.zycfv.cn/Article/details/gtiaxqcnbd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.aizwys.cn/Article/details/gtfvzgzuha.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtbpdyhnju.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtaukmdoyo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtbauvhkhs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gttttszera.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gteamvgxud.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gzhubu.top/Article/details/gtcpkfsuxt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.tianlin.xyz/Article/details/gtgnhjxyew.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtexvmgyjk.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtnetiodyn.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtcremdlyq.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtakfonect.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jiagoushi.top/Article/details/gtkyjvxpxq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.vqdsnc.cn/Article/details/gtzdsmratn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtoqujllnm.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.tanke756.top/Article/details/gtlrstbydx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.gzhubu.top/Article/details/gtdnmbwazi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtuwyiclns.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jyoumei.cn/Article/details/gtgkgtiivf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hnxiangtu.top/Article/details/gtwdelcrba.html

[D02] 追加元素到末尾
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqrzetgi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.ppjwa.cn/Article/details/gtewndwepf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pycfn.com/Article/details/gtzdshwbmx.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtqsofznpw.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtbmjsbkjf.html

Java: list.add(4);
来源：http://dali.yonumen.top/Article/details/gtjxkpsveo.html

Go:   arr = append(arr, 4)
来源：http://dali.gogol.net.cn/Article/details/gtlurllzqv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtzbwztqra.html

C#:   list.Add(4);
来源：http://dali.xinyue.icu/Article/details/gtxjlzlwqx.html

[D03] 在指定位置插入元素
来源：http://dali.hfpthk.cn/Article/details/gtzmfqziyu.html

Py:   arr.insert(0, 0)
来源：http://dali.yj20258888.top/Article/details/gtjsaqdkad.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtyuhdodrg.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtqjorywqr.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jqgfzy.top/Article/details/gtkyyosttf.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzarnhqll.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxrevvuuj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.feifeiyinyue.top/Article/details/gtsubfatct.html

C#:   list.Insert(0, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtkvgycalv.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gtstuixzzs.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fzhhl.top/Article/details/gtwdazcmxm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtxwiuqfkw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.guowangkeji.top/Article/details/gtuwnarptw.html

TS:   arr.splice(0, 1);
来源：http://dali.chenzaomai.com/Article/details/gtuiivyetj.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.redwolf501.top/Article/details/gtamvpxvne.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.yueranfly.top/Article/details/gtkkkthfuq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tianlin.xyz/Article/details/gtffgvobpr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.meibo888.top/Article/details/gturqpkwlu.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtpnrfrcbt.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbrmcssp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.nanxuanxn.top/Article/details/gtexeaoemi.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtifnxiece.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jyoumei.cn/Article/details/gtwanxahwo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtzocijdjp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yuanzhike.top/Article/details/gtvtkgegpg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.andypj.xyz/Article/details/gtgbxmhbzj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gthhdgceoe.html

[D06] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gtgiksplne.html

Py:   len(arr)
来源：http://dali.tian-w.cn/Article/details/gtdqwhwryh.html

PHP:  count($arr);
来源：http://dali.nanxinkj.top/Article/details/gtatypcabt.html

JS:   arr.length
来源：http://dali.nanxinkj.top/Article/details/gtebisynnb.html

TS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtnnsmldkm.html

Java: list.size();
来源：http://dali.hammf.cn/Article/details/gtocxyxdof.html

Go:   len(arr)
来源：http://dali.iojbl.cn/Article/details/gtarqmtxcy.html

Ruby: arr.length; arr.size
来源：http://dali.vqdsnc.cn/Article/details/gtqvrmugde.html

C#:   list.Count;
来源：http://dali.ydzc1.top/Article/details/gthnbnuxzs.html

[D07] 切片 / 取子数组
来源：http://dali.aizwys.cn/Article/details/gtvfzibnis.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.jinghuilouyu.cn/Article/details/gtzidpqnhq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.pengpengdd.cyou/Article/details/gtgzofajkk.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtwuqrdmgi.html

TS:   arr.slice(1, 4);
来源：http://dali.shzxlz.cn/Article/details/gtyymrlxbm.html

Java: list.subList(1, 4);
来源：http://dali.haohaochexian.top/Article/details/gtlzwzsohq.html

Go:   arr[1:4]
来源：http://dali.cqqwz.cn/Article/details/gtggddadry.html

Ruby: arr[1, 3]
来源：http://dali.hnqzz.top/Article/details/gtvohhbrdo.html

C#:   list.GetRange(1, 3);
来源：http://dali.xziqi.cn/Article/details/gtozbreayu.html

[D08] 合并两个数组
来源：http://dali.ivvv.top/Article/details/gtwxvrziql.html

Py:   a + b;  a.extend(b)
来源：http://dali.sufxvd.cn/Article/details/gtntqwauyr.html

PHP:  array_merge($a, $b);
来源：http://dali.ydzc1.top/Article/details/gtulsqrgup.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cqqwz.cn/Article/details/gteccytmyl.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtniqlyvnp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtdvzrbyol.html

Go:   append(a, b...)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzczelcdz.html

Ruby: a + b;  a.concat(b)
来源：http://dali.316326.xyz/Article/details/gtuizxylkg.html

C#:   a.Concat(b).ToList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnirwkvy.html

[D09] 排序（升序）
来源：http://dali.xuetiantiany.cn/Article/details/gttaqipsls.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.hysaishi.cn/Article/details/gtgljwfcgi.html

PHP:  sort($arr);
来源：http://dali.pycfn.com/Article/details/gtwvcwbzkl.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yongpay.top/Article/details/gttrckbijb.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.andypj.xyz/Article/details/gtwwbtgnyc.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.chenzaomai.com/Article/details/gtyqlaskbs.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.guannengcc.top/Article/details/gtzqnbajxq.html

Ruby: arr.sort
来源：http://dali.aibaodan.cn/Article/details/gtjyqkhgiw.html

C#:   list.Sort();
来源：http://dali.vqdsnc.cn/Article/details/gtnlhyxdvy.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.cheryme.top/Article/details/gtreveifqe.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.cqqwz.cn/Article/details/gtspuepjwz.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruwegndl.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.nanxinkj.top/Article/details/gtbfllwaqa.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhoulong.xyz/Article/details/gtgjujnhqj.html


<!-- 参考信息 -->