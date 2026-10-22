代发 wailian999

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gtetpkfdec.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gttugrqmpt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtdczcxwim.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gtjdhccokq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtkjxvgxqy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtfndvuovn.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtmxbnisof.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gtxrkcibnp.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gtpgckyurk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtgnkbmxdi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.c1oappe.top/Article/details/gtgiltoibq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aizwys.cn/Article/details/gthfnbrjez.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtcxzpjuun.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gtgapcoyga.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtntyhhths.html

[B12] 跳出多层循环
来源：http://dali.guowangkeji.top/Article/details/gthrmkmrmt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtjkjzermh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xziqi.cn/Article/details/gtuicwivux.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtaqyrqika.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtopgnqtfv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gtyiqfuafs.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtwlykyasr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinqigfzy.top/Article/details/gtjvkcmuqx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtiinfyjnm.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gtytonychy.html

Py:   isinstance(x, (int, float))
来源：http://dali.sysykeji.top/Article/details/gthbmqlife.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtyjqbepqu.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtytdwgemj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtgjhywxzq.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gtfrmbxcyc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtqqffqrxz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtfigdnkhe.html

C#:   x is int or double or decimal
来源：http://dali.nwbrower.top/Article/details/gtyvmymobr.html

[B14] 判断值是否在集合内
来源：http://dali.xinyue.icu/Article/details/gtfbpvrffo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nwbrower.top/Article/details/gthdyspmxf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gtfcohkuzx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtwxszkkrp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtzcaesrec.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtwkmgtcye.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gttjhfznyq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gtjvpdqtxg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtytwalyik.html

[B15] 布尔运算与取反
来源：http://dali.haohaochexian.top/Article/details/gtwkaukger.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtteyfmlht.html

PHP:  $a && $b || !$c
来源：http://dali.9152youxi.cn/Article/details/gtdxxoilvp.html

JS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gttzmddhnp.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtyqylkgwv.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtausctbpu.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtpoobaryr.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtgvrmkiuw.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvilskdc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gttglsgxer.html

Py:   if not data: return
来源：http://dali.zhoulong.xyz/Article/details/gtqsetwjie.html

PHP:  if (!$data) { return; }
来源：http://dali.jianghu66.top/Article/details/gtydlsipth.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtujskviiv.html

TS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtjldxynwy.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtatsdnfzg.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gtnyahewca.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtbhpvuqcy.html

C#:   if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gtlwpysbnp.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtggetuart.html

C. 函数与作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtjslyjjox.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gthtjdebxp.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtqdfrkcmt.html

Py:   def add(a, b): return a + b
来源：http://dali.hammf.cn/Article/details/gtqvwglfbr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcvdgsjsg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtehilnxeg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtjgwyoriv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtjlbkbwlg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtbppmubyz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gthagfzlub.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gthnvhchgv.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtacccbwcq.html

Py:   def greet(name="World"): return name
来源：http://dali.cheryme.top/Article/details/gtwctygxnl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtxemdmhfy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xinyue.icu/Article/details/gtfheeihtu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtwxvgtrkm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gtedjgwsou.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtluwimrdc.html

Ruby: def greet(name = "World") = name
来源：http://dali.fengsongda.top/Article/details/gtvrjdntdp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtzzbsfwus.html

[C03] 可变参数
来源：http://dali.hammf.cn/Article/details/gtcdwdubxs.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtsosbppty.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrstiemgy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtwyhozjzh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtlhusnbaw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hywenlv.cn/Article/details/gtvjlnedez.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtahkkuosc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gtxblcucmj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtgmnjkviu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ydzc1.top/Article/details/gtoflgotcg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.smart0.xyz/Article/details/gtezbacwwp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.pycfn.com/Article/details/gtwpbhbegz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.aibaodan.cn/Article/details/gtjecwovno.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtdyfmbkvm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtlizqmrsk.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gtmncidudw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtocsmwdmi.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtllwmtogt.html

[C05] 返回多个值
来源：http://dali.yj202588.top/Article/details/gtydvoaumj.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtczlaqimd.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gttqoeqegs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gtncgnhqed.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtlhgpsltj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.316326.xyz/Article/details/gtycdiauci.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtgwlfeppa.html

Ruby: return a, b
来源：http://dali.9152youxi.cn/Article/details/gtqggexpll.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ivvv.top/Article/details/gtqnhmasya.html

[C06] 匿名函数 / lambda
来源：http://dali.daria6918.cn/Article/details/gttygdluui.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtyyvqqcym.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gtggxygquv.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtlvdswads.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gteanjumjg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.birdmap.top/Article/details/gtphnoowxr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daxiang520.top/Article/details/gtozrtrsef.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xinyue.icu/Article/details/gtciiibohf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtqydigsnv.html

[C07] 把函数作为参数传入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwsftccur.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jianghu66.top/Article/details/gtzathqghf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtghtaynuq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenjidiqi.icu/Article/details/gteraeuode.html

TS:   arr.map(String)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegunjvln.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gtpepuviuc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtuasmeetx.html

Ruby: arr.map(&:upcase)
来源：http://dali.sysykeji.top/Article/details/gtqyumbpym.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtxnzebxks.html

[C08] 闭包
来源：http://dali.yangfankeji.com/Article/details/gtcbrgofpz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtdyhygkgl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gtvwhxeuia.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtnocqgxiq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewixbbci.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xuanzx.com/Article/details/gtqxzhdddx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangdashe.top/Article/details/gtnljvgrmx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtcmrxyiav.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtuzjqbyyw.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtxxrwezfj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtvownwnan.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sxryk.cn/Article/details/gtuglrofaw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258888.top/Article/details/gtonhdgqyb.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtvenddnbt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtqwedtmjr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daria6918.cn/Article/details/gtbvaredag.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtobighjvb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtdtylxwoz.html

[C10] 变量作用域
来源：http://dali.yvedp.cn/Article/details/gtnrphrpiy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cdnleiting.top/Article/details/gtoqlgmdxe.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sufxvd.cn/Article/details/gtiaaegmnt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cucudq.cn/Article/details/gtkatqtvxo.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtikgngeob.html

Java: 方法内为块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtsctputud.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gtztbynoex.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtcphkcopg.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtydsbbhjc.html

[C11] 模块导入与导出
来源：http://dali.fengsongda.top/Article/details/gtvqakxeob.html

Py:   from module import func
来源：http://dali.hongshengwenyu.top/Article/details/gtukuvozxu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtetopblwx.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgufenzy.top/Article/details/gtknsdgpgr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gtpratwnjz.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtiqqvdkjk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigfzy.top/Article/details/gtyixdoodn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuxnrfwu.html

C#:   using System.Text;
来源：http://dali.jinqigufen.top/Article/details/gthevelpzx.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258.top/Article/details/gtgtnsggro.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtgnvazcvv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zdqjudy.top/Article/details/gtysgukxsa.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gththqsaxz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gticoplmjh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gtkvszryww.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtbxrshxzs.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtfxfgjxng.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidjzbeev.html

[C13] 类型声明 / 类型注解
来源：http://dali.smart0.xyz/Article/details/gttqhhvuub.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtjdvphzlv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtlcibeocf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtjvqztkxx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtopwvpfik.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtsllbilnn.html

Go:   func add(a, b int) int
来源：http://dali.yj202588.top/Article/details/gtfyxrvqsz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gtgoeelgrf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtczgqftnq.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtabhvisva.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtlsbfajqe.html

PHP:  // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtbclibhdb.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtzdgaytji.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.svipenyu.cn/Article/details/gteofsmhkb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.haohaochexian.top/Article/details/gtaiepjtuh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.dashuyun.cn/Article/details/gturyyxglh.html

Ruby: # 无泛型
来源：http://dali.ydzc1.top/Article/details/gtlbmcbjfv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhoulong.xyz/Article/details/gtqtsiciou.html

[C15] 解构 / 展开参数
来源：http://dali.316326.xyz/Article/details/gtpebtlnyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gthrrlgldb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgfzy.top/Article/details/gtfcvxozjd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gttojlmxex.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtlqvoqmem.html

Java: // 无解构
来源：http://dali.cheryme.top/Article/details/gtlqkamdcl.html

Go:   // 无解构
来源：http://dali.ivvv.top/Article/details/gtwtkyfpmg.html

Ruby: a, b = pair
来源：http://dali.jianghu66.top/Article/details/gtvojvzxmh.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gtdhssaplq.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtmnqssrmc.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhengqikj.top/Article/details/gtnbhlsqxw.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtspeovqtz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.wangdashe.top/Article/details/gtcnrjvsxe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tian-w.cn/Article/details/gtldcthaaf.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gthfghhgbb.html

Go:   // 无重载：用不同函数名
来源：http://dali.shanyushiyangtech.top/Article/details/gtzakhwqzn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtugrnwwjo.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.fzhhl.top/Article/details/gtlfzqwzfy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtvdyxlsbb.html

D. 数组 / 列表 / 集合
来源：http://dali.svipenyu.cn/Article/details/gttfqjocul.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmprqtqfz.html

[D01] 创建数组 / 列表
来源：http://dali.gogol.net.cn/Article/details/gtywwonflo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtomxdovsc.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zhoulong.xyz/Article/details/gtgawarlzy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtcovqsudq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj202588.top/Article/details/gtxanicbcw.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ybcxt.top/Article/details/gtumhgwakx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtnvrllfdg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guannengcc.top/Article/details/gtfltbpnln.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.316326.xyz/Article/details/gtupufkdnp.html

[D02] 追加元素到末尾
来源：http://dali.nwbrower.top/Article/details/gtdxyquglc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yongpay.top/Article/details/gtahrmampw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgyscvpuv.html

JS:   arr.push(4);
来源：http://dali.jqgufenzy.top/Article/details/gtokfxbdmy.html

TS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtxqqptzda.html

Java: list.add(4);
来源：http://dali.cheryme.top/Article/details/gtqvytmiby.html

Go:   arr = append(arr, 4)
来源：http://dali.ppjwa.cn/Article/details/gtwwekdevh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlfboaah.html

C#:   list.Add(4);
来源：http://dali.xylfe.cn/Article/details/gtuahamwnq.html

[D03] 在指定位置插入元素
来源：http://dali.ybcxt.top/Article/details/gtjqfketop.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtmsagptxo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.andypj.xyz/Article/details/gtaikgxhct.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jianghu66.top/Article/details/gtokoeeals.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.tian-w.cn/Article/details/gtqxqujeva.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkoqaatmm.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhongyouzk.top/Article/details/gtqcmwcfpq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtzqclvlaq.html

C#:   list.Insert(0, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjczvetxf.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtwkufircq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ppjwa.cn/Article/details/gtvgkosziz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhijiandao.cn/Article/details/gtndxvicsu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtihxvtayx.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gthtlqcuzb.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gtetcezlag.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtydxwnvlu.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.bjfxy.top/Article/details/gtgoisbzpc.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gtxufjosdt.html

[D05] 访问与修改元素
来源：http://dali.ydzc1.top/Article/details/gtadwjmfnp.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtizprsziz.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gtnzzdjbcv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.cqqwz.cn/Article/details/gtopsvgylv.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xuanzx.com/Article/details/gtdeibnkxd.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbbkwgpks.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gttlkroynm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gtunnzokcf.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.quarkkingdee.top/Article/details/gtleehtlbv.html

[D06] 数组长度
来源：http://dali.nanxuanxn.top/Article/details/gtwrpepopv.html

Py:   len(arr)
来源：http://dali.nanxinkj.top/Article/details/gtzzamjbeh.html

PHP:  count($arr);
来源：http://dali.jiagoushi.top/Article/details/gtdyxyffdp.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtrfsjqpdn.html

TS:   arr.length
来源：http://dali.snrcjt.cn/Article/details/gtlxhazwdp.html

Java: list.size();
来源：http://dali.gzhubu.top/Article/details/gtdoeiyvvu.html

Go:   len(arr)
来源：http://dali.fzhhl.top/Article/details/gtwogkcdjd.html

Ruby: arr.length; arr.size
来源：http://dali.yj202588.top/Article/details/gtziwydlkf.html

C#:   list.Count;
来源：http://dali.zhiwuduotai.top/Article/details/gtdispissq.html

[D07] 切片 / 取子数组
来源：http://dali.svipenyu.cn/Article/details/gtcirribbt.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zhongyouzk.top/Article/details/gtlvqagzln.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.haohaochexian.top/Article/details/gtegznszan.html

JS:   arr.slice(1, 4);
来源：http://dali.0kj1m.cn/Article/details/gthqzldhdg.html

TS:   arr.slice(1, 4);
来源：http://dali.andypj.xyz/Article/details/gtvwliylzz.html

Java: list.subList(1, 4);
来源：http://dali.wangshuangyany.cn/Article/details/gtdsvfesgv.html

Go:   arr[1:4]
来源：http://dali.kuanghao11.cn/Article/details/gtnqtyncpz.html

Ruby: arr[1, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtlcsfhlqe.html

C#:   list.GetRange(1, 3);
来源：http://dali.guowangkeji.top/Article/details/gtpuhmyfqi.html

[D08] 合并两个数组
来源：http://dali.wangshuangyany.cn/Article/details/gtnxvdhidq.html

Py:   a + b;  a.extend(b)
来源：http://dali.yangfankeji.com/Article/details/gtqwabzxnx.html

PHP:  array_merge($a, $b);
来源：http://dali.yuanzhike.top/Article/details/gtthufvxev.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtggqiwdno.html

TS:   [...a, ...b];
来源：http://dali.gotoacloud.top/Article/details/gttqchsejk.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.andypj.xyz/Article/details/gtjhdvuhwh.html

Go:   append(a, b...)
来源：http://dali.ydzc1.top/Article/details/gtnpbxshoj.html

Ruby: a + b;  a.concat(b)
来源：http://dali.hongshengwenyu.top/Article/details/gtmfonlcyg.html

C#:   a.Concat(b).ToList()
来源：http://dali.chenlongwang.top/Article/details/gtfcrlklcn.html

[D09] 排序（升序）
来源：http://dali.fzhhl.top/Article/details/gtqiozxavy.html

Py:   sorted(arr);  arr.sort()
来源：http://dali.cucudq.cn/Article/details/gtefxqhjer.html

PHP:  sort($arr);
来源：http://dali.snrcjt.cn/Article/details/gtjxhsirfw.html

JS:   [...arr].sort((x, y) => x - y)     // 默认按字符串比较，数字必须给比较器
来源：http://dali.yuanzhike.top/Article/details/gtmmgccapk.html

TS:   [...arr].sort((x, y) => x - y);
来源：http://dali.yanxiufei.cn/Article/details/gtolkpfmen.html

Java: Collections.sort(list);  list.sort(null);
来源：http://dali.hongshengwenyu.top/Article/details/gtktjpbsmp.html

Go:   sort.Ints(arr);  slices.Sort(arr)
来源：http://dali.birdmap.top/Article/details/gtfvwxepty.html

Ruby: arr.sort
来源：http://dali.svipenyu.cn/Article/details/gthfbtizlk.html

C#:   list.Sort();
来源：http://dali.yongpay.top/Article/details/gtauebfezb.html

[D10] 自定义排序（按字段 / 多条件）
来源：http://dali.hnqzz.top/Article/details/gtkchhpldm.html

Py:   arr.sort(key=lambda x: x["age"]);  sorted(arr, key=len, reverse=True)
来源：http://dali.jinqigufen.top/Article/details/gtzmgemrsf.html

PHP:  usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtycbjaxoj.html

JS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.fengsongda.top/Article/details/gtzbwogdkr.html

TS:   arr.sort((a, b) => a.age - b.age)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtliqtxpok.html

Java: list.sort(Comparator.comparing(Person::age));
来源：http://dali.ehwqpu.com/Article/details/gtwnnxhqwr.html

Go:   sort.Slice(items, func(i, j int) bool { return items[i].Age < items[j].Age })
来源：http://dali.jianghu66.top/Article/details/gtvbbuuknp.html

Ruby: arr.sort_by { |x| x[:age] }
来源：http://dali.zhiwuduotai.top/Article/details/gtonyztrow.html

C#:   list.Sort((a, b) => a.Age.CompareTo(b.Age));
来源：http://dali.chenlongwang.top/Article/details/gteyiltdsd.html


<!-- 参考信息 -->