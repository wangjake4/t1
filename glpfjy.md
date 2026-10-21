代发 wailian999

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gtbgjzsvfz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gtzfiglyry.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gtsufwhbyd.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gtdebjvqwo.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmknlsbyr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtvajfqcxf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtitwerffw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtqprqeblg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gthnienhdk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtgrgpzqqe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.kuanghao11.cn/Article/details/gtceicpjvl.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtzzbvirso.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtrzbtdfom.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhongyouzk.top/Article/details/gtpnjehoco.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtcmtoghtl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtzzibjogf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtoogahbzb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.svipenyu.cn/Article/details/gtjlkjixrl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gtbjzwusmr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gtwxfdzluc.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtezbwzexb.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhengqikj.top/Article/details/gtqrbhymtt.html

PHP:  is_numeric($x)
来源：http://dali.tian-w.cn/Article/details/gtqloxyxwv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigfzy.top/Article/details/gtfaqmqqyi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtxtbzcsxm.html

Java: x instanceof Number
来源：http://dali.ydzc1.top/Article/details/gtrkminlup.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtwnahpqrg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgfzy.top/Article/details/gtceteoikg.html

C#:   x is int or double or decimal
来源：http://dali.dashuyun.cn/Article/details/gtxvuqixfl.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtqkkupudu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtnkfwuviv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtpiklchkz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtnemqnpxj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtsntgcnom.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtfqjwursx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtgztrtxfm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj202588.top/Article/details/gtkoljagzd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtjqckmuyz.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtakxfpaee.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gtyrbkfvdx.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gtlpyryjhi.html

JS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtncyxsbxb.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtsnhgwhys.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtxrmimohj.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtyqnyghzu.html

Ruby: a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtklysxlea.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyqxqmvh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sxryk.cn/Article/details/gtmhgwwbiq.html

Py:   if not data: return
来源：http://dali.tanke756.top/Article/details/gtkgefeptl.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtokxmbaxi.html

JS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gttflvpyip.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gtsawflpxp.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtkcnmabtn.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gtytgaidxg.html

Ruby: return if data.nil?
来源：http://dali.vqdsnc.cn/Article/details/gtirbatqjb.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtqhhruooi.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtegzqycha.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtqgvxhmpj.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gthwtgrler.html

[C01] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gtpbqpqels.html

Py:   def add(a, b): return a + b
来源：http://dali.sxryk.cn/Article/details/gtlzpoetsz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtieikzkoe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtobatiwlv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtytmsgpyr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwkcppxjs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtknymusdm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gtphxthqzk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtxlcubqkt.html

[C02] 默认参数
来源：http://dali.gogol.net.cn/Article/details/gtymovvkoy.html

Py:   def greet(name="World"): return name
来源：http://dali.iojbl.cn/Article/details/gttkspcrgm.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.fengsongda.top/Article/details/gtbebfvsvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtoqysuphh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hnxiangtu.top/Article/details/gtnjjfjatz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtqgpofdtp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtedzpcjwl.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtwnousvqq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cucudq.cn/Article/details/gtsrpknyqa.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtoqbztrga.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtpemsydpt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gtkkmtzxdk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtkckhbnws.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj202588.top/Article/details/gtagvtgryu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtxjajiavf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gotoacloud.top/Article/details/gtippssuwm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.snrcjt.cn/Article/details/gteqtmpnwy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtxwvrajlk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gtunrtuuoq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtuutfvgyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtasiroafs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtfuybxtqh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtsxotjusc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtzivekuav.html

Go:   // 无：用配置结构体参数
来源：http://dali.ppjwa.cn/Article/details/gtsyntzvvg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtgnxqeffh.html

C#:   f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuprtwla.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtrubbwuyb.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gtohdftdyw.html

PHP:  return [$a, $b];
来源：http://dali.jqgufenzy.top/Article/details/gtsguuelgi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gtojgeppft.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtvputwton.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtgcvqkmgq.html

Go:   return a, b
来源：http://dali.daxiang520.top/Article/details/gtgfvhwvta.html

Ruby: return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbdfbrrd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtcavjptyv.html

[C06] 匿名函数 / lambda
来源：http://dali.shuidangran.top/Article/details/gtofjtqrar.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gtpcqihmqb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtcgjgqvon.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtelvbjrdo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gtesaggkro.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jlsjyb.cn/Article/details/gtzpxjrods.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.iojbl.cn/Article/details/gtojzvxgpb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtcvgtgmqw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtpqtcqmug.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtbifkbavp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.haohaochexian.top/Article/details/gtxvbcsknu.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtheydvfnq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtrbuawghb.html

TS:   arr.map(String)
来源：http://dali.shanyushiyangtech.top/Article/details/gtknwwzvpl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtbraifsvt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtkwrygbeu.html

Ruby: arr.map(&:upcase)
来源：http://dali.aizwys.cn/Article/details/gtgxkvbxnc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gtgovejuyt.html

[C08] 闭包
来源：http://dali.xuetiantiany.cn/Article/details/gtmkleousk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangshuangyany.cn/Article/details/gtsjmgayje.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkoklzzhn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gttgdzxcbp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zycfv.cn/Article/details/gtpndmzfvr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtplpxpfvy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shzxlz.cn/Article/details/gthwfglavf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.haohaochexian.top/Article/details/gtcfqwmile.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtomknkkuy.html

[C09] 递归
来源：http://dali.pycfn.com/Article/details/gtvmdxqnmy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtgpnwmjov.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xinyue.icu/Article/details/gthawgewom.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddjtpmsn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gtxziadyeo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gtbgpeknjq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtortpnjsx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtbpspeatf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gtzxrpszbo.html

[C10] 变量作用域
来源：http://dali.xylfe.cn/Article/details/gtowmiwcdj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hysaishi.cn/Article/details/gtohgxviys.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gthjmpvead.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtjhmwzkbb.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gtgqbmmlbk.html

Java: 方法内为块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtpikxxjkk.html

Go:   花括号块级作用域
来源：http://dali.guannengcc.top/Article/details/gtbqgrtmjh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtsvywmmkl.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gtczzengmr.html

[C11] 模块导入与导出
来源：http://dali.shzxlz.cn/Article/details/gtptscfkjx.html

Py:   from module import func
来源：http://dali.zhongyouzk.top/Article/details/gtseronrsa.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.feifeiyinyue.top/Article/details/gtfblvbwfm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj202588.top/Article/details/gtdpknavaa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.daria6918.cn/Article/details/gtivbrljbu.html

Java: import java.util.List;
来源：http://dali.wangshuangyany.cn/Article/details/gturkjfjmd.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtufmljinr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nwbrower.top/Article/details/gtktibuztu.html

C#:   using System.Text;
来源：http://dali.316326.xyz/Article/details/gtffefkfcc.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtgupvdhjj.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gtxletvprz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hfpthk.cn/Article/details/gtdvavygrt.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shuidangran.top/Article/details/gtqjnlmexc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gtrcnzejme.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangshuangyany.cn/Article/details/gtrrghoyqh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbpvnlnf.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtqglqsnst.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.smart0.xyz/Article/details/gtaposhhcy.html

[C13] 类型声明 / 类型注解
来源：http://dali.chenzaomai.com/Article/details/gttmgvafuv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gotoacloud.top/Article/details/gtjbzfuuvd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtooifqhcr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtevqolics.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtslpzkcxk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sufxvd.cn/Article/details/gtkdartuvo.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gtgshkbqvj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pengpengdd.cyou/Article/details/gthssjckkk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gtbwjctvqd.html

[C14] 泛型函数
来源：http://dali.hnxiangtu.top/Article/details/gtcjvhcaxe.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtljihaccw.html

PHP:  // 无泛型
来源：http://dali.bjfxy.top/Article/details/gtgmhqflgg.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtprjvgbeb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hammf.cn/Article/details/gtjzflxpny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gturjxegaw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gthtsiquep.html

Ruby: # 无泛型
来源：http://dali.sweek.top/Article/details/gtkqjwvire.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtlwlsljhp.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtvxoouowi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gtneilanhx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hongshengwenyu.top/Article/details/gthagejwhc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtikmpfrqi.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gtgypaaazt.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtseolknwt.html

Go:   // 无解构
来源：http://dali.sweek.top/Article/details/gtfytgjfwn.html

Ruby: a, b = pair
来源：http://dali.sufxvd.cn/Article/details/gthmgkeyko.html

C#:   var (a, b) = pair;
来源：http://dali.shzxlz.cn/Article/details/gtlazxmprj.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gtgqfrrafx.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.daria6918.cn/Article/details/gtgrpxggga.html

PHP:  // 无重载
来源：http://dali.guannengcc.top/Article/details/gtotuvxtub.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gtwjxnaxdi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gtxqicwjdg.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gogol.net.cn/Article/details/gtpzpzlauq.html

Go:   // 无重载：用不同函数名
来源：http://dali.guannengcc.top/Article/details/gtvzfceuea.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gogol.net.cn/Article/details/gtmcyfznkf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtwdjjloja.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtnllkdfof.html

D. 数组 / 列表 / 集合
来源：http://dali.gzhubu.top/Article/details/gtbtyzzudk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrrjfuwdk.html

[D01] 创建数组 / 列表
来源：http://dali.jqgufenzy.top/Article/details/gtqluskhyl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gteaocjfod.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ybcxt.top/Article/details/gtmnuzwxbb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zdqjudy.top/Article/details/gtqhydrsok.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtztnacvyd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.meibo888.top/Article/details/gtpjmtjkoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.9152youxi.cn/Article/details/gtjtswtdun.html

Ruby: arr = [1, 2, 3]
来源：http://dali.quarkkingdee.top/Article/details/gtlowboqyg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtxymarudr.html

[D02] 追加元素到末尾
来源：http://dali.dashuyun.cn/Article/details/gtrdqzrspa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.sweek.top/Article/details/gtpenmdscx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cheryme.top/Article/details/gtndfzswrw.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrvxrtmqq.html

TS:   arr.push(4);
来源：http://dali.yuanzhike.top/Article/details/gtxaqhvtfb.html

Java: list.add(4);
来源：http://dali.dashuyun.cn/Article/details/gturlqsqda.html

Go:   arr = append(arr, 4)
来源：http://dali.yueranfly.top/Article/details/gtvfgyknfu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cqqwz.cn/Article/details/gtakkuzzww.html

C#:   list.Add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtddyqgoyp.html

[D03] 在指定位置插入元素
来源：http://dali.zdqjudy.top/Article/details/gtqewrfhie.html

Py:   arr.insert(0, 0)
来源：http://dali.sweek.top/Article/details/gttmzqjeup.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yongpay.top/Article/details/gthfsncsyi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyaezuuw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtqduwdhip.html

Java: list.add(0, 0);
来源：http://dali.ivvv.top/Article/details/gtycsedfcb.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.redwolf501.top/Article/details/gtyibmwbum.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhixingplan.top/Article/details/gtzoujeofn.html

C#:   list.Insert(0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtmexvitzo.html

[D04] 删除元素
来源：http://dali.yj202588.top/Article/details/gtksvqhjhe.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgkgtwna.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jianghu66.top/Article/details/gtbermwwkv.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.birdmap.top/Article/details/gtrfgvawoo.html

TS:   arr.splice(0, 1);
来源：http://dali.ivvv.top/Article/details/gtfgqnaavd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.chenzaomai.com/Article/details/gttcodiwno.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.gzhubu.top/Article/details/gtxyadvuvl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ivvv.top/Article/details/gtnutxwamp.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xuetiantiany.cn/Article/details/gtppdxysys.html

[D05] 访问与修改元素
来源：http://dali.hnqzz.top/Article/details/gtupfbaykb.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangdashe.top/Article/details/gtbffmbzhg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jinghuilouyu.cn/Article/details/gtujuuatnt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtlocnokxm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.fzhhl.top/Article/details/gtcsogkvvx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.dashuyun.cn/Article/details/gtggyckuyg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklhylhzf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtwrwzwtkn.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtdhwisznw.html

[D06] 数组长度
来源：http://dali.0kj1m.cn/Article/details/gtfixloxki.html

Py:   len(arr)
来源：http://dali.guannengcc.top/Article/details/gteqylgoow.html

PHP:  count($arr);
来源：http://dali.jqgfzy.top/Article/details/gtycifovie.html

JS:   arr.length
来源：http://dali.xylfe.cn/Article/details/gtbaxtxhcz.html

TS:   arr.length
来源：http://dali.dianchejie.cn/Article/details/gtpzojwsiw.html

Java: list.size();
来源：http://dali.9152youxi.cn/Article/details/gtitctbavm.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtkswicokm.html

Ruby: arr.length; arr.size
来源：http://dali.pengpengdd.cyou/Article/details/gtvprenyiq.html

C#:   list.Count;
来源：http://dali.sxryk.cn/Article/details/gtsjvczkul.html

[D07] 切片 / 取子数组
来源：http://dali.sweek.top/Article/details/gtzbbdtklf.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhixingplan.top/Article/details/gtisgohywe.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.c1oappe.top/Article/details/gtsvjjbrcq.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbmcklxja.html

TS:   arr.slice(1, 4);
来源：http://dali.yongpay.top/Article/details/gtokyjtemh.html

Java: list.subList(1, 4);
来源：http://dali.cqqwz.cn/Article/details/gtnfuluibj.html

Go:   arr[1:4]
来源：http://dali.cashguo.top/Article/details/gtkznazznw.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gthovxzveg.html

C#:   list.GetRange(1, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtaddsfmtt.html

[D08] 合并两个数组
来源：http://dali.yj20258.top/Article/details/gttnjwputu.html

Py:   a + b;  a.extend(b)
来源：http://dali.mhx1999.top/Article/details/gtsuihgrhf.html

PHP:  array_merge($a, $b);
来源：http://dali.daria6918.cn/Article/details/gtlnbwunmx.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.cdnleiting.top/Article/details/gthnjaqpqt.html

TS:   [...a, ...b];
来源：http://dali.ydzc1.top/Article/details/gtcjvfwesp.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.ydzc1.top/Article/details/gtnmgvszpa.html

Go:   append(a, b...)
来源：http://dali.gotoacloud.top/Article/details/gtptczpgtj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.guannengcc.top/Article/details/gtsufwsdky.html

C#:   a.Concat(b).ToList()
来源：http://dali.dashuyun.cn/Article/details/gtlldzymon.html

[D09] 排序（升序）
来源：http://dali.tanke756.top/Article/details/gtfbdjauwo.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.yuxming.cn/Article/details/gtsjhmaqyf.html

PHP:  sort($arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrhkiglh.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.bjfxy.top/Article/details/gtshjqcefi.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.zdqjudy.top/Article/details/gtskxxhmye.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.daxiang520.top/Article/details/gtofcuhkfj.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtkrifwsno.html

Ruby: arr.sort
来源：http://dali.yongpay.top/Article/details/gtawabwhyv.html

C#:   list.Sort();
来源：http://dali.zhongyouzk.top/Article/details/gtchzuxync.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.9152youxi.cn/Article/details/gtucpfrxcf.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.andypj.xyz/Article/details/gtyqlcatby.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhongyouzk.top/Article/details/gtrwqsdrrm.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.cdnleiting.top/Article/details/gtaqjfnbgc.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.hongshengwenyu.top/Article/details/gtyvriislc.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.andypj.xyz/Article/details/gtykrthpxf.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.wangshuangyany.cn/Article/details/gthwkvcvtv.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.gzhubu.top/Article/details/gtolmixrku.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.xylfe.cn/Article/details/gtkmltdinh.html

[D11] 反转数组
来源：http://dali.jinqigfzy.top/Article/details/gtvkfjxlim.html

Py:   arr[::-1];  arr.reverse()
来源：http://dali.jiagoushi.top/Article/details/gtiseiqgqg.html

PHP:  array_reverse($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtogpphyeg.html

JS:   [...arr].reverse();  arr.toReversed()
来源：http://dali.xziqi.cn/Article/details/gtjaqcisns.html


<!-- 参考信息 -->