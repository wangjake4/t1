代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtuwzpxqkd.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtdikavrbw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ppjwa.cn/Article/details/gtcwqfaqgx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gtxzhhabnv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuomhrowo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tanke756.top/Article/details/gtyfzraygm.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gtrhulntvt.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gtvwtipobc.html

PHP:  range(0, 10, 2);
来源：http://dali.sufxvd.cn/Article/details/gtcbukfrki.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gteuielsvy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gteqqjazyn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvshuozjz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtfuxgghdr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtujiaaqcx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgufenzy.top/Article/details/gtvxygrnzf.html

[B12] 跳出多层循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmtbqoun.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gtjkgduwvn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtrlpjxkiz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtbcngmedf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtcvrhoqrc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gttqjpjjsy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtcziuspoe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gthqkipvnb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtqzletroo.html

[B13] 判断是否为数字
来源：http://dali.snrcjt.cn/Article/details/gtqitkeihb.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmwagruvm.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtqfbjofjj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtsetknrvf.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtauhqhzsw.html

Java: x instanceof Number
来源：http://dali.redwolf501.top/Article/details/gtjmnphlfw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tanke756.top/Article/details/gthqdrwonp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtsudwkmbt.html

C#:   x is int or double or decimal
来源：http://dali.aizwys.cn/Article/details/gtmzevteps.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtxsgybikg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigfzy.top/Article/details/gteomphodz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.daxiang520.top/Article/details/gtyenwlghz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaepthrtx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtllwvvrtf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gtchiyplmt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtisuojfrp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gtlxtexxtu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtskmlgybu.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtygcsbnnj.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gtpeceypek.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gtqoehqyam.html

JS:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtomsuftqk.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtgygwsphy.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gtyscjkpuv.html

Go:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtnuxiknhv.html

Ruby: a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtwgnasqbh.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtqlekncyz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtywuspybr.html

Py:   if not data: return
来源：http://dali.guowangkeji.top/Article/details/gttotjkakk.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gtpqyljjbx.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtfjgtdiuv.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gtmxxattir.html

Java: if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtdlqqvhuv.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtixqqodva.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gtxylnfndk.html

C#:   if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gtatzphefl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtqikeoodj.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtytdgzwgj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtjlpdhwtv.html

[C01] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtlahldexx.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtqdlohuik.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtdcxwyucb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtjpmlnpvi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtnhnbfgdb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtvbhycrcf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtebzyzyvw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtfaxoiiwe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtvscjuvvo.html

[C02] 默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtivtmmorx.html

Py:   def greet(name="World"): return name
来源：http://dali.hnxiangtu.top/Article/details/gtmbidcmkm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtiwuroaek.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtdxzinepo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gteksiinhl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sysykeji.top/Article/details/gtzbbeusio.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrptyeabj.html

Ruby: def greet(name = "World") = name
来源：http://dali.aizwys.cn/Article/details/gtmjlrxpod.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj202588.top/Article/details/gtopvcwsmo.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gtfvtwdcmg.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtdiqdefjp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gtiqfbkksh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtjtlxpzgh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtkdzosyxw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhoulong.xyz/Article/details/gtbqpysryi.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.aibaodan.cn/Article/details/gtszerzlef.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cdnleiting.top/Article/details/gtxkwwmwwf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtjzwzhwrd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.tianlin.xyz/Article/details/gtjnkwdnaa.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcajwinpg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gthpjnsetk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtvudowyym.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtkscolbqe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gtobkwmnsj.html

Go:   // 无：用配置结构体参数
来源：http://dali.tianlin.xyz/Article/details/gtpjocbmnz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xinyue.icu/Article/details/gtrawergkh.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtcocvutxx.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtpskfmuum.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtmvbhhqwy.html

PHP:  return [$a, $b];
来源：http://dali.shzxlz.cn/Article/details/gtvkbibksv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtxbgqonuw.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtvbsygeyt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtsbhhrhjw.html

Go:   return a, b
来源：http://dali.nwbrower.top/Article/details/gtzukcdfcv.html

Ruby: return a, b
来源：http://dali.pycfn.com/Article/details/gtfqwetkjk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gtqtzvsfox.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gtusflvraj.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gtumqwojgm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangdashe.top/Article/details/gtlinchpir.html

JS:   const square = x => x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtigjjgdqx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtprvtaerb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtmxobxrfa.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtsugpaqyi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtjbsahoyc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtvzcrwnyk.html

[C07] 把函数作为参数传入
来源：http://dali.yangfankeji.com/Article/details/gtosqfsyxd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.quarkkingdee.top/Article/details/gtuqhorsqa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yvedp.cn/Article/details/gtequvvkck.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xuanzx.com/Article/details/gtanlgduam.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtfgsjdslv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtpcprzzqy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtzvmgtfko.html

Ruby: arr.map(&:upcase)
来源：http://dali.ehwqpu.com/Article/details/gtdhiouyzm.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtbmyzhkdl.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gtzrzgkaye.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gtghajjobq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gtyfucsuog.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yonumen.top/Article/details/gtnlcyftwj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtgecajllj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtfdamxpce.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gtcnvmmsci.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtjtbwfgjq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrpwgmyw.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gtmmlkmenh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtkdiuoxmx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gttqxqihnv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gthubmensf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gtsmakdyzz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.pengpengdd.cyou/Article/details/gtktoxcuob.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jianghu66.top/Article/details/gtzrmnjtdt.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtaagkefia.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cucudq.cn/Article/details/gtuulwolos.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtqmjxbdsm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gtniyjytzy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gtvvqalmbo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shuidangran.top/Article/details/gtmzyiuzuy.html

TS:   同 JS
来源：http://dali.cqqwz.cn/Article/details/gtvcbyakut.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajihrfju.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gteeukdodi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj202588.top/Article/details/gtrrwjfxrs.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtuafkfxne.html

[C11] 模块导入与导出
来源：http://dali.pycfn.com/Article/details/gtufwaxvmv.html

Py:   from module import func
来源：http://dali.tianlin.xyz/Article/details/gtyaifajwh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.fengsongda.top/Article/details/gttmhviclp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntrcnqkn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258888.top/Article/details/gtouumiexl.html

Java: import java.util.List;
来源：http://dali.jyoumei.cn/Article/details/gtqtohemeq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gotoacloud.top/Article/details/gtaobneauy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtuysrztdc.html

C#:   using System.Text;
来源：http://dali.iojbl.cn/Article/details/gtfzspruon.html

[C12] 立即执行函数 IIFE
来源：http://dali.dashuyun.cn/Article/details/gtvehrzspj.html

Py:   (lambda: print("run"))()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtinyiaoey.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hnqzz.top/Article/details/gtmzowymag.html

JS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtofruvqra.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtgpwwiigs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hywenlv.cn/Article/details/gtcwjuwqdj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenlongwang.top/Article/details/gtgkqsdkil.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gtwbcakata.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqbcedvsk.html

[C13] 类型声明 / 类型注解
来源：http://dali.iojbl.cn/Article/details/gtjuhemuul.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gtmqzhzqpn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtmvirksgj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gtyhbcggdn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtrlseckun.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtacndbwda.html

Go:   func add(a, b int) int
来源：http://dali.dianchejie.cn/Article/details/gtpeoqmxkp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ppjwa.cn/Article/details/gtfbilwmsu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenlongwang.top/Article/details/gtzxperqmc.html

[C14] 泛型函数
来源：http://dali.ehwqpu.com/Article/details/gtubfvqtqz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnqzz.top/Article/details/gtvtjgnrud.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gtbamzqiuu.html

JS:   // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtgofguoys.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtxspxxiju.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zdqjudy.top/Article/details/gtjxhftfqc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.havefunace.top/Article/details/gtdxikguse.html

Ruby: # 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtkyefotlj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gttbtcpzgh.html

[C15] 解构 / 展开参数
来源：http://dali.chenzaomai.com/Article/details/gtikxlbqkn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtxuqrkzkt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tianlin.xyz/Article/details/gticcaaixw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtknbhrnlk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.redwolf501.top/Article/details/gtzovrpzsz.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtcyhjhdvm.html

Go:   // 无解构
来源：http://dali.ybcxt.top/Article/details/gtxfxyyohh.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtsvlmfiuw.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtcyxzswyp.html

[C16] 函数 / 方法重载
来源：http://dali.kuanghao11.cn/Article/details/gtnprjvgki.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhoulong.xyz/Article/details/gtmujvdlsd.html

PHP:  // 无重载
来源：http://dali.zhijiandao.cn/Article/details/gtnabvwmjw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yonumen.top/Article/details/gtrlrcegww.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yongpay.top/Article/details/gtncrrgoiy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gttpslzjsz.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtnfrbcyts.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtrgahajtx.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtvuxxmsqg.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtozjccnqw.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtywnqwhyw.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtyyzudiiy.html

[D01] 创建数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtnqnmhhcv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.feifeiyinyue.top/Article/details/gthdtrqeom.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtkvccxbzt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.redwolf501.top/Article/details/gtjkmlmioi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhixingplan.top/Article/details/gtjyojehxl.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hfpthk.cn/Article/details/gthgpbhgbw.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gtozyhhaew.html

Ruby: arr = [1, 2, 3]
来源：http://dali.aizwys.cn/Article/details/gtlgczxqwy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtattrybir.html

[D02] 追加元素到末尾
来源：http://dali.gotoacloud.top/Article/details/gtowncmyoq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gzhubu.top/Article/details/gtsjwsdleq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.svipenyu.cn/Article/details/gthmfdfxet.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtkexlkxtd.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhlnxdtn.html

Java: list.add(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbtgkmke.html

Go:   arr = append(arr, 4)
来源：http://dali.jinghuilouyu.cn/Article/details/gtprxztsii.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hnqzz.top/Article/details/gtebmzcgxr.html

C#:   list.Add(4);
来源：http://dali.yj20258.top/Article/details/gtrfmlqley.html

[D03] 在指定位置插入元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplyqmuso.html

Py:   arr.insert(0, 0)
来源：http://dali.dashuyun.cn/Article/details/gttfwhunjv.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.bjfxy.top/Article/details/gtauaczddr.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.sweek.top/Article/details/gteyaldjuz.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtyyigeoau.html

Java: list.add(0, 0);
来源：http://dali.haohaochexian.top/Article/details/gtizemqxtu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pycfn.com/Article/details/gtxowsprqb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.jlsjyb.cn/Article/details/gtfctnnaou.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtvdluhcyv.html

[D04] 删除元素
来源：http://dali.birdmap.top/Article/details/gtppycqlwq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ybcxt.top/Article/details/gtmugnyjqw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtamqjaayb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.nwbrower.top/Article/details/gtyyhskeln.html

TS:   arr.splice(0, 1);
来源：http://dali.jqgfzy.top/Article/details/gttsxbrnpk.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cdnleiting.top/Article/details/gtdjeshwsu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cqqwz.cn/Article/details/gtlotajzde.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shuidangran.top/Article/details/gtapjajyjl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtihrrywqr.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtismpqnpu.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtogbimyly.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jlsjyb.cn/Article/details/gtwfxmfzjt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhijiandao.cn/Article/details/gtmjskdqps.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtybpisyjg.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.c1oappe.top/Article/details/gtankghgcm.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yongpay.top/Article/details/gtlnldtdrd.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gtmzyalbne.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtmifzupln.html

[D06] 数组长度
来源：http://dali.gogol.net.cn/Article/details/gtbeqwoblr.html

Py:   len(arr)
来源：http://dali.ydzc1.top/Article/details/gtpfsiueou.html

PHP:  count($arr);
来源：http://dali.feifeiyinyue.top/Article/details/gtiuctiqjs.html

JS:   arr.length
来源：http://dali.ivvv.top/Article/details/gthjlqvgst.html

TS:   arr.length
来源：http://dali.wangdashe.top/Article/details/gtftljvcei.html

Java: list.size();
来源：http://dali.ivvv.top/Article/details/gtnvghbuso.html

Go:   len(arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytwdrerj.html

Ruby: arr.length; arr.size
来源：http://dali.smart0.xyz/Article/details/gtwxnctroi.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtkayrchdx.html

[D07] 切片 / 取子数组
来源：http://dali.nanxuanxn.top/Article/details/gtxiizqmnx.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.xylfe.cn/Article/details/gtyyhymxfr.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.daxiang520.top/Article/details/gtfbiwebqy.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtugoxmqej.html

TS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtwzzzhous.html

Java: list.subList(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gtsscgxnls.html

Go:   arr[1:4]
来源：http://dali.nanxuanxn.top/Article/details/gthbwjgwsl.html

Ruby: arr[1, 3]
来源：http://dali.smart0.xyz/Article/details/gtctakennm.html

C#:   list.GetRange(1, 3);
来源：http://dali.birdmap.top/Article/details/gtwyhhvwus.html

[D08] 合并两个数组
来源：http://dali.redwolf501.top/Article/details/gtgghycivv.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtdiqrhtea.html

PHP:  array_merge($a, $b);
来源：http://dali.zhongyouzk.top/Article/details/gtjhqhoefh.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cheryme.top/Article/details/gtazbcpeul.html

TS:   [...a, ...b];
来源：http://dali.xuetiantiany.cn/Article/details/gtrnqbbfqo.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.chenzaomai.com/Article/details/gtuhrruizx.html

Go:   append(a, b...)
来源：http://dali.zdqjudy.top/Article/details/gtftbjvhup.html

Ruby: a + b;  a.concat(b)
来源：http://dali.gogol.net.cn/Article/details/gtcyxjaqwe.html

C#:   a.Concat(b).ToList()
来源：http://dali.kuanghao11.cn/Article/details/gtoshofyaj.html

[D09] 排序（升序）
来源：http://dali.sysykeji.top/Article/details/gtwlqbfgio.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.nwbrower.top/Article/details/gtqergewfn.html

PHP:  sort($arr);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfcevmmu.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.nwbrower.top/Article/details/gtltiabmhg.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.daxiang520.top/Article/details/gtfpocngjf.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.yj20258.top/Article/details/gtmdphergx.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.iojbl.cn/Article/details/gtlcjxfwci.html

Ruby: arr.sort
来源：http://dali.chenjidiqi.icu/Article/details/gtryzlsfft.html

C#:   list.Sort();
来源：http://dali.fengsongda.top/Article/details/gtegwarsiu.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.ybcxt.top/Article/details/gtxrbvfswv.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.svipenyu.cn/Article/details/gttukbnygd.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gttsnigirf.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.aibaodan.cn/Article/details/gtzckvruev.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.snrcjt.cn/Article/details/gtwqqzwubp.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.haohaochexian.top/Article/details/gthlhqzvll.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.cqqwz.cn/Article/details/gtakkpfmnf.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.shzxlz.cn/Article/details/gtykoamrmk.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.ydzc1.top/Article/details/gtyqmotxiv.html


<!-- 参考信息 -->